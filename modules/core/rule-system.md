# Rule System Module

## Purpose

Define how game logic decisions are represented so AI agents can create consistent gameplay rules.

## Core Idea

Rules describe:

Condition → Action → Result

Example:

```
IF enemy HP < 50%
THEN change Boss phase
RESULT unlock new abilities
```

## Rule Structure

```
Rule
 ├── Trigger Condition
 ├── Evaluation
 ├── Action
 └── Result
```

## Input

- Events
- States
- Parameters
- Conditions

## Output

- State changes
- New events
- Gameplay effects

## Agent Constraints

Rules should be:

- Explicit
- Testable
- Parameterized
- Engine independent

## Examples

Combat:

```
Condition:
player attacks enemy

Action:
calculate damage

Result:
create damage event
```

Economy:

```
Condition:
player has enough currency

Action:
purchase item

Result:
remove currency and add item
```
