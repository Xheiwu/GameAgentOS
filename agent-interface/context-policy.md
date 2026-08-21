# Agent Context Policy

## Goal

Prevent unnecessary context loading and keep agent reasoning focused.

## Loading Priority

### Level 1: Always Load

Agent Module metadata only.

Contains:

- intent
- tags
- requirements
- compatibility

### Level 2: Load When Selected

Specific Agent Module.

Contains:

- components
- events
- parameters
- rules
- validation

### Level 3: Load When Needed

Pattern Layer.

Used for deeper design decisions.

### Level 4: Research Layer

Only for:

- extracting new patterns
- verifying uncertain decisions
- creating new modules

## Principle

Retrieve minimum sufficient knowledge.

More context does not always mean better output.
