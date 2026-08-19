# unvibeshit

> Search first. Grill second. Build last.

`unvibeshit` is a tiny Agent Skill for stress-testing software ideas **before** requirements, architecture, or code.

Vibe coding makes implementation cheap. It does not make bad ideas valuable.

This skill exists to stop projects that should never have been built: duplicated tools, imagined user needs, feature-shaped solutions looking for problems, and prototypes whose only advantage is that an AI can generate them quickly.

## What it does

`unvibeshit` starts from a deliberately skeptical position:

> **DON'T BUILD until the idea earns its way out.**

Before interrogating the user, it performs a **Substitute Scan** when research tools are available. It looks for:

- existing commercial products and SaaS
- open-source projects and GitHub repositories
- libraries, frameworks, plugins, CLIs, and packages
- built-in platform/vendor capabilities
- adjacent tools solving the same job in a simpler way

The agent should surface the closest alternatives with links first, then ask the important question:

> Given that these already exist, what concrete problem remains unsolved — and is that gap valuable enough to justify another project?

## What it challenges

The skill keeps pressure on eight areas:

1. **Problem** — Is the pain real, frequent, and evidenced?
2. **Substitutes** — Does something already solve it well enough?
3. **Necessity** — Why build anything at all?
4. **Value** — What meaningful outcome improves for whom?
5. **Differentiation** — What is materially better, not merely different?
6. **Defensibility** — What survives if an incumbent copies it?
7. **Economics** — Is the value worth build, maintenance, adoption, and switching costs?
8. **Falsifiability** — What is the cheapest way to prove the idea wrong?

## Verdicts

Every interrogation ends with exactly one verdict:

- **DON'T BUILD** — the problem is weak, unnecessary, or not worth solving.
- **USE EXISTING** — adopt, configure, integrate, fork, or contribute instead.
- **PROTOTYPE** — critical assumptions still need cheap validation.
- **BUILD** — the problem is real, substitutes are insufficient, value is meaningful, and the advantage is credible.

A **BUILD** verdict must be earned.

## Usage

Install `SKILL.md` using the skill mechanism supported by your agent, then invoke it before starting a new project or feature.

Example:

```text
Use unvibeshit to evaluate this idea before we write any requirements or code:

I want to build ...
```

Or simply invoke the skill by name if your agent supports explicit skill invocation.

## Philosophy

- Occam's razor: **entities should not be multiplied without necessity.**
- YAGNI: do not build speculative capability just because implementation is cheap.
- Search before inventing.
- Problem before solution.
- Evidence over enthusiasm.
- Complexity is not differentiation.
- First-version coding cost is not lifecycle cost.
- When in doubt, do less.

## Why the name?

Vibe coding is useful when it compresses the cost of implementing a well-understood idea.

When implementation starts before anyone checks whether the problem is real, whether a mature solution already exists, or whether the result has any defensible value, vibe coding turns into **vibeshit**.

`unvibeshit` is the gate before that happens.
