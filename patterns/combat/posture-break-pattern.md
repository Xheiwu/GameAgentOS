# Posture Break Combat Pattern

## Intent

Create boss encounters where player skill and timing are more important than raw damage output.

## Problem

Pure HP reduction often creates repetitive boss fights.

## Solution

Introduce a secondary state/resource representing enemy stability.

Players can create advantage through:

- perfect defense
- accurate timing
- exploiting openings

## Required Systems

- Attack Telegraph
- Defense Timing
- Secondary Resource
- State Transition
- Reward Window

## Design Rules

1. Enemy attacks must communicate intent.
2. Defensive success should create offensive opportunities.
3. Major rewards should require mastery.
