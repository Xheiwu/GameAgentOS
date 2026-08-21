# Module Matching Strategy

## Purpose

Define how structured user intent maps to GameAgentOS modules.

Retrieval should not only match keywords. It should understand game design requirements.

## Matching Dimensions

### 1. Intent Matching

Example:

User wants:

- boss combat

Match:

- boss modules
- combat modules

### 2. Experience Matching

Example:

User wants:

- high tension
- precise timing
- strong feedback

Match:

- parry systems
- posture systems
- impact feedback systems

### 3. System Dependency Matching

A module may require other modules.

Example:

Posture Break Boss requires:

- Entity System
- Event System
- State Change System

### 4. Platform Matching

Consider:

- mobile
- PC
- web

Different platforms may require different parameter presets.

## Retrieval Result

Return:

- Primary modules
- Supporting modules
- Conflicting modules
- Missing dependencies
