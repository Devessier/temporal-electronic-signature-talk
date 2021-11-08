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

# Demonstration

<div class="flex items-center justify-center">
  <video src="https://user-images.githubusercontent.com/29370468/136715088-f016acc4-dd5f-4153-8e1b-f63ff1e40c14.mp4" controls="controls" muted="muted" style="max-height: 400px;" class=""></video>
</div>

---

# State machines

- Finite number of *states*
- In exactly one state at a time
- An *initial* state
- Wait for inputs (*events*)
- Events trigger *transitions* from one state to another one
- Transitions are deterministic

---

# XState

- https://xstate.js.org/docs/
- Library to create state machines in JavaScript/TypeScript
- Can be used anywhere JavaScript can be run (browser, Node.js, Temporal Workflows, ...)

## Examples

- [Fetch machine](https://stately.ai/viz/7c0ec648-09d6-46fe-a912-fc0e46da5094)

---

# Code

[Workflow code on Github](https://github.com/Devessier/temporal-electronic-signature/blob/main/packages/temporal/src/workflows/index.ts)

---

# Pros and cons of using XState with Temporal

### Pros

- Explicit behaviour
- Visualization
- Prevents impossible states and race conditions
- Scale well

### Cons

- Learning curve
- For now there is boilerplate

---

# Thank you!

- <mdi-github /> [Devessier](https://github.com/Devessier)
- <mdi-link /> [baptiste.devessier.fr](https://baptiste.devessier.fr)
- <mdi-twitter /> [BDevessier](https://twitter.com/BDevessier)
- Code: [github.com/Devessier/temporal-electronic-signature](https://github.com/Devessier/temporal-electronic-signature)
- Slides: [temporal-electronic-signature-talk.netlify.app](https://temporal-electronic-signature-talk.netlify.app/1)
