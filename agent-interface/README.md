# Agent Retrieval Architecture

## Purpose

Define how AI agents access GameAgentOS knowledge.

GameAgentOS is not a document dump. Different agents should retrieve different knowledge layers.

## Knowledge Flow

```
Research Layer
(raw investigation)
        |
        v
Pattern Layer
(design principles)
        |
        v
Agent Module Layer
(executable knowledge)
        |
        v
Engine Implementation
```

## Default Agent Rule

Coding agents should NOT load the entire repository.

They should retrieve the smallest relevant Agent Module first.

Research and Pattern layers are loaded only when deeper reasoning is required.
