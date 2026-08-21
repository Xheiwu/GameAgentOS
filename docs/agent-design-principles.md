# GameAgentOS Agent Design Principles

## Core Philosophy

GameAgentOS is designed for AI agents, not only human readers.

The goal is not to describe games. The goal is to create executable knowledge that agents can understand, combine and implement.

## Human Documentation vs Agent Documentation

Human oriented:

"This boss feels heavy and exciting."

Agent oriented:

"The boss requires attack anticipation, reaction windows, impact feedback and recovery states."

## Every Module Should Define

1. Intent

Why does this capability exist?

2. Input Contract

When should an agent call this module?

3. Output Contract

What does this module produce?

4. Behavior Logic

How should the system behave?

5. Parameters

Which values can be tuned?

6. Dependencies

What other capabilities are required?

7. Validation

How can an agent judge the result?

## Design Rule

Do not store game copies.

Extract reusable game design patterns.

A module should describe the principle behind an experience, allowing agents to recreate it in different engines and genres.
