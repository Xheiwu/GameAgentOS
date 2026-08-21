# System Composition Foundation

## Purpose

Compose retrieved game modules into a playable game architecture.

The goal is not module stacking, but system relationship design.

## Input

- User game idea
- Classified genre
- Reference analysis
- Selected modules

## Output

- Core gameplay loop
- System dependency graph
- Feature composition plan
- Development blueprint

## Example

Hades-like action roguelike:

Combat Core + Roguelike Core + RPG Progression

becomes:

Run Loop -> Combat Encounter -> Reward -> Build Upgrade -> Boss -> Meta Progression
