---
theme: apple-basic
highlighter: shiki
title: Temporal + XState

layout: intro
---

# Temporal + XState

Use XState with Temporal TypeScript SDK

<div class="absolute bottom-10">
  <span class="font-700">
    Baptiste Devessier - 2021
  </span>
</div>

---

# Who am I?

- Web developer
- Student at 42 Paris
- Interested in Temporal and state machines

---

# Demonstration

[Open Github repository](https://github.com/Devessier/temporal-electronic-signature#readme)

---
layout: statement
---

# What are state machines?

---

# Finite State Machines (FSM)

- Finite number of *states*
- In exactly one state at a time
- An *initial* state
- Wait for inputs (*events*)
- Events trigger *transitions* from one state to another one

## Examples:

- [Opened/Closed](https://en.wikipedia.org/wiki/Finite-state_machine#/media/File:Finite_state_machine_example_with_comments.svg)
- [Pacman ghosts](https://blog.scottlogic.com/2020/12/08/finite-state-machines.html#explicit-finite-state-machines)

---

# Statecharts

- Originated by David Harel in 1987
- Hierarchical states
- Parallel states
- Delayed transitions
- Guarded transitions

## Examples:

- [Citizen Quartz Multi Alarm III](https://andyjakubowski.github.io/statechart-watch/)
