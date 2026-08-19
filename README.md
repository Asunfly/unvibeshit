# unvibeshit

> Search first. Grill second. Build last.

`unvibeshit` is a tiny Agent Skill for stress-testing software ideas **before** requirements, architecture, or code.

Vibe coding makes implementation cheap. It does not make bad ideas valuable.

This skill exists to stop projects that should never have been built: imagined user needs, feature-shaped solutions looking for problems, unnecessary complexity, and products whose only advantage is that an AI can generate them quickly.

## What it does

`unvibeshit` starts from a skeptical, evidence-driven position.

Before interrogating the user, it performs a **Substitute Scan** when research tools are available. It looks for:

- existing commercial products and SaaS
- open-source projects and GitHub repositories
- libraries, frameworks, plugins, CLIs, and packages
- built-in platform/vendor capabilities
- adjacent tools solving the same job in a simpler way

The agent should surface the closest alternatives with links first, then ask the important question:

> Given what already exists, what concrete value remains underserved — and is that delta meaningful enough to justify another project?

### Similar does not mean duplicate

Existing projects are **high-signal evidence, not an automatic veto**.

Competition can mean several different things:

- the need is already validated
- an incumbent already covers the core job well
- a specific user segment is still underserved
- an existing workflow is too expensive, complex, locked-in, insecure, or inconvenient
- the capability is commoditized and should probably be reused rather than rebuilt
- there is room for a materially better approach

`unvibeshit` should use existing projects to **raise or lower the burden of proof**, not to kill an idea simply because something similar exists.

**USE EXISTING** is appropriate only when an existing option covers the core job well enough and the remaining advantage is too small or too weakly evidenced to justify build, switching, and maintenance costs.

## What it challenges

The skill keeps pressure on eight areas:

1. **Problem** — Is the pain real, frequent, and evidenced?
2. **Substitutes** — What already exists, and what does that evidence actually imply?
3. **Necessity** — Why build anything at all?
4. **Value** — What meaningful outcome improves for whom?
5. **Differentiation** — What is materially better, not merely different?
6. **Defensibility** — What survives if an incumbent copies it?
7. **Economics** — Is the value worth build, maintenance, adoption, and switching costs?
8. **Falsifiability** — What is the cheapest way to prove the idea wrong?

## Verdicts

Every interrogation ends with exactly one verdict:

- **DON'T BUILD** — the problem is weak, unnecessary, or not worth solving.
- **USE EXISTING** — a current solution covers the core job well enough and the remaining delta does not justify a new project.
- **PROTOTYPE** — critical assumptions still need cheap validation.
- **BUILD** — the problem is real, the value is meaningful, and there is a credible reason to build even if alternatives already exist.

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
- **Similar is not duplicate.**
- Existing alternatives are evidence, not verdicts.
- Problem before solution.
- Evidence over enthusiasm.
- Complexity is not differentiation.
- First-version coding cost is not lifecycle cost.
- When in doubt, validate before expanding scope.

## Why the name?

Vibe coding is useful when it compresses the cost of implementing a well-understood idea.

When implementation starts before anyone checks whether the problem is real, what already exists, what users actually value, or whether the result has any defensible advantage, vibe coding turns into **vibeshit**.

`unvibeshit` is the check before that happens.
