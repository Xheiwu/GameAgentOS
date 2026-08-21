# State Change System

## Module Identity

Name: State Change System

Category: Core Gameplay Infrastructure

Purpose: Define how game entities and systems change state in a way AI agents can reason about.

---

## Agent Intent

Games are built around state transitions.

Examples:

- Enemy alive -> dead
- Player normal -> buffed
- Boss phase 1 -> phase 2
- Card available -> consumed

---

## Input Contract

```yaml
entity:
current_state:
new_state:
trigger_event:
```

---

## Output Contract

State changes may trigger:

- Events
- Feedback
- AI decisions
- Rewards
- Animations

---

## Behavior Logic

```
Current State
 ↓
Condition Check
 ↓
Transition Rule
 ↓
New State
 ↓
Notify Systems
```

---

## Agent Rules

- States must be explicit.
- Transitions must have conditions.
- Avoid hidden logic.

---

## Validation

An AI agent should be able to explain every important state transition in the game.
