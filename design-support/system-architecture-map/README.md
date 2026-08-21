# H1.3.3 Game System Architecture Map

## Purpose

This module provides an analysis framework for AI agents to understand how game systems connect and support each other.

It is not a fixed game template and does not prescribe implementation.

The goal is to help agents reason from:

Player Experience → System Relationship → Architecture → Modules

## Core Idea

A commercial game is not a collection of isolated features.

Systems should form value loops.

Example:

Combat
↓
Reward
↓
Progression
↓
New Capability
↓
Higher Challenge
↓
Continued Engagement

## Architecture Thinking Questions

When analyzing a game idea, agents should consider:

1. What player behavior is the core activity?
2. Which systems reinforce that behavior?
3. Which systems create long-term motivation?
4. Which systems consume and generate resources?
5. Which systems create new content opportunities?

## Relationship Types

### Experience Driver

A system that directly creates player feeling.

Example:
Combat → excitement

### Feedback Loop

A system that reinforces repeated behavior.

Example:
Challenge → Reward → Growth

### Content Support

A system that allows future expansion.

Example:
Equipment → New builds → New content

### Economy Relationship

A system that controls resource flow.

Example:
Reward → Currency → Upgrade → Consumption

## Agent Usage

Use this framework to understand architecture.

Do not copy structures blindly.

The final design should adapt to:

- target platform
- audience
- development scope
- game identity
