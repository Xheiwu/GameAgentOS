# Event Trigger System

## Module Identity

Name: Event Trigger System

Category: Core Gameplay Infrastructure

Purpose: Provide a universal event layer that allows AI agents to connect player actions, game state changes and system responses.

---

## Agent Intent

This module defines **when something should happen**.

AI agents should use this module whenever a gameplay event needs to activate another system.

Examples:

- Player attacks enemy
- Card is played
- Quest completed
- Item obtained
- Boss enters new phase

---

## Input Contract

Required:

- event_type
- source
- target
- context

Example:

```yaml
event_type: damage_dealt
source: player
 target: enemy
```

---

## Output Contract

The event system can trigger:

- Feedback systems
- AI behavior systems
- Reward systems
- UI systems
- Animation systems

---

## Behavior Logic

Flow:

```
Action
 ↓
Event Created
 ↓
Event Filter
 ↓
Subscribed Systems Execute
```

---

## Agent Rules

- Do not hard-code unrelated systems together.
- Use events as communication between modules.
- Prefer reusable triggers.

---

## Validation

A generated game should allow new mechanics to subscribe without rewriting existing systems.
