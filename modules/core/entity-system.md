# Entity System Module

## Purpose

Define the fundamental objects that exist inside a game world so AI agents can reason about gameplay entities consistently.

## Core Concept

A game is composed of entities:

- Player
- Enemy
- NPC
- Item
- Skill
- Card
- Building
- Pet

Each entity contains:

```
Entity
 ├── Components
 ├── Attributes
 ├── State
 └── Events
```

## Agent Understanding

The agent should not think about objects as code classes first. It should identify:

- What exists?
- What data does it own?
- What actions can it perform?
- What events can affect it?

## Input

Entity definition:

- type
- components
- attributes
- relationships

## Output

A structured entity model that can be implemented in different engines.

## Example

Enemy Entity:

```
Entity: Goblin

Components:
- Health
- Movement
- Combat
- Loot

States:
- Idle
- Alert
- Attack
- Dead

Events:
- Damaged
- Defeated
```

## Engine Mapping

Unity:
- GameObject + Components

Godot:
- Node + Components

UrhoX:
- Node + Attributes
