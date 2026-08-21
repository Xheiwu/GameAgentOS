# Action Impact Response Module

> AI Agent oriented gameplay feedback module.

## Module Intent

Convert important gameplay events into multi-channel player-perceived responses.

This module does not define a specific combat system. It defines how an AI agent should transform a state change into meaningful feedback.

## Supported Events

- damage_dealt
- skill_triggered
- enemy_defeated
- item_obtained
- card_played
- level_up
- state_changed

## Input Contract

Required data:

```yaml
EventType:
Target:
Position:
Value:
Severity:
```

## Output Contract

The module can generate:

```yaml
VisualFeedback:
AudioFeedback:
MotionFeedback:
CameraFeedback:
TimeControl:
UIFeedback:
```

## Behavior Logic

The agent should select feedback intensity based on event importance.

Example:

```
Low Impact
 -> small visual/audio feedback

Medium Impact
 -> animation + particles + sound

High Impact
 -> camera response + time control + strong visual feedback
```

## Parameter Model

```yaml
impact_strength:
  range: 0-10

feedback_channels:
  visual: true
  audio: true
  motion: true
  camera: optional
  time_control: optional
```

## Dependencies

Required:

- Event System
- Animation System
- Audio System

Optional:

- Camera System
- Particle System
- UI System

## Engine Mapping

Unity:
- Animation Events
- Particle System
- Audio Source
- Cinemachine

Godot:
- AnimationPlayer
- GPUParticles
- AudioStreamPlayer

UrhoX:
- Lua gameplay logic
- NanoVG/UI feedback
- Effect system

## Validation Rules

An implementation should verify:

- Player understands the event immediately.
- Important events have stronger feedback.
- Feedback improves clarity without blocking gameplay.

## AI Agent Instruction

When implementing this module:

1. Identify the gameplay event.
2. Evaluate event importance.
3. Select suitable feedback channels.
4. Generate implementation according to target engine.
5. Test whether player perception matches the intended event importance.
