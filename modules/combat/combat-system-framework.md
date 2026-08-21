# Combat System Framework

## Purpose

Define combat as a collection of reusable capabilities that AI agents can combine.

Combat is not a single feature. It is a loop of actions, rules, state changes and feedback.

## Combat Loop

```
Player Intent
    ↓
Action Execution
    ↓
Rule Evaluation
    ↓
State Change
    ↓
Event Generation
    ↓
Feedback Response
    ↓
Next Decision
```

## Core Elements

- Entities
- Actions
- Resources
- Rules
- States
- Events
- Feedback
- Progression

## Agent Requirement

Before implementing combat, the agent should define:

1. Who can act?
2. What actions exist?
3. What limits actions?
4. How does the world react?
5. How does the player understand the result?
