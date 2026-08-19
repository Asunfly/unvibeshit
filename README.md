# unvibeshit

> **Search first. Value first. Grill hard. Build only when the value survives.**

`unvibeshit` is a small Agent Skill for deciding whether a software idea deserves to be built **before** requirements, architecture, or code.

Vibe coding makes implementation cheap. It does not make low-value ideas worth doing.

The core rule is simple:

> **Value first. Cost second.**

A project does not become worthwhile just because AI can generate it in an evening.

## What it does

`unvibeshit` uses an INTJ-like, first-principles reasoning style to challenge an idea on four things:

1. **Value** — what meaningful outcome does this create, for whom, and why does it matter?
2. **Existing solutions** — what already solves the same job, and what does that imply?
3. **Delta** — if alternatives exist, what materially improves and is that improvement actually valuable?
4. **Opportunity cost** — is this worth the time, attention, maintenance, and alternatives it displaces?

It also ignores sunk-cost reasoning and considers lifecycle cost when relevant.

## Search before inventing

When research tools are available, the agent searches first: commercial products, platform-native features, open source, libraries, packages, plugins, CLIs, and adjacent workflows.

It surfaces the closest alternatives with links before asking the user to defend the idea.

**Similar is not duplicate.** Existing projects are evidence, not a veto. They may validate demand, prove the problem is already solved, reveal an underserved niche, or establish the baseline a new idea must beat.

## Value first

For non-entertainment projects, the agent expects a credible value case: a real recurring need, a meaningful improvement, concrete user behavior, or another strong reason the outcome matters.

**Low implementation cost is not evidence of value.** Cheap and reversible experiments only affect *how* to validate an idea after there is plausible value to validate.

### Entertainment exception

Meme, joke, art, creative, and entertainment projects do not need business metrics. Fun, expression, novelty, social interaction, or cultural resonance can be the intended value.

The skill should judge whether they deliver that value, not whether they have TAM, ROI, or a moat.

## Verdicts

Every evaluation ends with one verdict:

- **DON'T BUILD** — the value is too weak to justify the opportunity cost.
- **USE EXISTING** — the need is real, but an existing solution already captures the value well enough.
- **PROTOTYPE** — potential value is credible, but one decisive assumption needs a cheap test.
- **BUILD** — the value is clear enough and there is a meaningful reason to build rather than stop or reuse.

`PROTOTYPE` is not a consolation prize for cheap ideas. If the value case is weak, the answer is still **DON'T BUILD**.

## Output style

Deep reasoning should end in a short decision, not a consulting report.

The final answer contains only:

- **Verdict**
- **Value judgment**
- **Existing signal**
- **Decisive issue**
- **Next step**

## Usage

```text
Use unvibeshit to evaluate this idea before we write requirements or code:

I want to build ...
```

## Philosophy

- Value before feasibility.
- Problem before solution.
- First principles before inherited assumptions.
- Search before inventing.
- Similar is not duplicate.
- Existing alternatives are evidence, not verdicts.
- Ignore sunk cost; respect opportunity cost.
- Complexity does not create value.
- Cheap code can still be wasted work.
- Entertainment value is still value.
- Reason deeply; conclude sharply.

The target is not vibe coding. The target is **vibeshit**: implementation momentum without a value case.