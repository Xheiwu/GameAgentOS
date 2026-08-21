# Agent Query Understanding Schema (D1)

## Purpose

Convert natural language game development requests into structured retrieval queries.

The goal is not to generate code directly.

The goal is to understand intent and retrieve the correct Agent Modules.

## Flow

```
User Request
    |
    v
Query Understanding
    |
    v
Structured Intent
    |
    v
Module Retrieval
    |
    v
Agent Module Loading
```

## Principle

A user describes desired experience.
The system converts experience into reusable game design requirements.

Example:

User:
"Create a fast Chinese fantasy boss fight with satisfying impact"

Becomes:

- genre: action_rpg
- theme: chinese_fantasy
- feature: boss_combat
- requirements: feedback, telegraph, vulnerability_window
