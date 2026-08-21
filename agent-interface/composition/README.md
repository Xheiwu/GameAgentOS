# Module Composition Layer

## Purpose

Define how GameAgentOS combines independent game design modules into a complete game architecture.

A module is not a game template. It is a reusable capability.

Example:

```
Roguelike Core
+
Action Combat
+
Boss Pattern
+
Build System
=
Complete game blueprint
```

## Principles

- Compose capabilities, not copy games.
- Separate core modules from extensions.
- Detect incompatible combinations before implementation.
- Respect dependency order.
