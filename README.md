# unvibeshit

> Search first. Grill second. Build last.

`unvibeshit` is a tiny Agent Skill for stress-testing software ideas **before** requirements, architecture, or code.

Vibe coding makes implementation cheap. It does not make bad ideas valuable — but the answer is not to become a contrarian that kills everything.

The goal is **better decisions**: understand the real intent, research what already exists, reason from first principles, challenge weak assumptions, and still leave room for legitimate innovation, experimentation, learning, fun, and creative nonsense.

## Operating style

The skill uses an **INTJ-like reasoning style** as shorthand for being independent, systems-oriented, strategically skeptical, emotionally neutral, and willing to challenge assumptions.

That does **not** mean performative cynicism.

- A clever **NO** is not better than a justified **YES**.
- The success metric is decision quality, not idea kill rate.
- First principles should be used to discover better formulations, not only to tear ideas apart.

## Search before inventing

Before interrogating the user, `unvibeshit` performs a **Substitute Scan** when research tools are available. It looks for:

- existing commercial products and SaaS
- open-source projects and GitHub repositories
- libraries, frameworks, plugins, CLIs, and packages
- built-in platform/vendor capabilities
- adjacent tools solving the same job in a different way

The closest alternatives should be surfaced with links and interpreted as evidence.

### Similar does not mean duplicate

Existing projects are **high-signal evidence, not an automatic veto**.

Competition may mean:

- the need is already validated
- an incumbent already covers the core job well
- a segment is underserved
- the current workflow is too expensive, complex, locked-in, unsafe, or inconvenient
- the capability is commoditized and should probably be reused
- there is room for a materially better approach
- the existing implementation is useful reference material

`unvibeshit` uses this evidence to raise or lower the burden of proof. It does not kill an idea merely because something similar exists.

## Value is broader than money

Not every project is a startup.

Before judging an idea, the skill identifies what kind of value it is trying to create:

- **Commercial / product** — adoption, willingness to pay, distribution, differentiation, defensibility
- **Productivity / automation** — time saved, errors reduced, friction removed
- **Infrastructure / technical** — control, performance, security, portability, interoperability
- **Learning / research** — knowledge gained, skills developed, hypotheses tested
- **Creative / entertainment / meme** — fun, humor, expression, novelty, virality, social interaction
- **Personal utility / hobby** — enjoyment, convenience, customization, craftsmanship, curiosity

A joke project does not need TAM. A weekend toy does not need a moat. A learning project does not need revenue.

For a low-cost playful idea, **"this is fun and worth an evening" can be enough value**.

For a high-cost commercial or operational commitment, the evidence burden should be much higher.

Economic value is one kind of value, not the definition of value.

## Decision hygiene

`unvibeshit` explicitly considers:

- **First principles** — separate fundamental constraints from inherited assumptions.
- **Sunk cost** — past effort already spent is not a reason to continue spending.
- **Opportunity cost** — compare the idea with the best realistic use of the same resources.
- **Reversibility** — cheap experiments deserve a lower burden of proof than expensive commitments.
- **YAGNI / Occam's razor** — do the smallest thing that achieves the intended value.

## Avoiding contrarian failure modes

The skill must not:

- reject ideas simply because alternatives exist
- demand commercial metrics from hobby, learning, creative, or entertainment projects
- treat subjective value as fake value
- over-index on moats when a project does not need one
- confuse "not economically optimal" with "not worth doing"
- use first principles only to deconstruct instead of finding sharper or more innovative formulations

The target is **vibeshit**, not vibes.

## Decision compression

Deep thinking should produce a sharp decision, not a long consulting report.

`unvibeshit` now follows a simple rule:

> **Reason broadly. Conclude narrowly.**

The final answer should default to roughly **150–250 words**, avoid repeated tradeoffs, mention no more than three alternatives unless they materially change the decision, and end with exactly five items:

1. **Verdict** — `DON'T BUILD`, `USE EXISTING`, `PROTOTYPE`, or `BUILD`
2. **Core reason** — the single strongest reason
3. **Biggest risk** — the one factor most likely to make the decision wrong
4. **Scope cut** — what not to build or optimize yet
5. **Next step** — one concrete, preferably reversible action

This is intentionally opinionated: the agent should not hide behind "it depends" or dilute a verdict with a page of caveats.

## Verdicts

- **DON'T BUILD** — unlikely to create enough intended value to justify forward and opportunity costs.
- **USE EXISTING** — an existing option already provides the intended value well enough, and rebuilding adds too little.
- **PROTOTYPE** — one important assumption should be tested cheaply first.
- **BUILD** — the intended value is credible and worth the forward/opportunity cost, even if alternatives exist.

## Usage

Install `SKILL.md` using the skill mechanism supported by your agent, then invoke it before starting a new project or feature.

```text
Use unvibeshit to evaluate this idea before we write any requirements or code:

I want to build ...
```

## Philosophy

- Search first. Grill second. Build last.
- Problem before solution.
- First principles before inherited assumptions.
- **Similar is not duplicate.**
- Existing alternatives are evidence, not verdicts.
- Ignore sunk cost; consider opportunity cost.
- Match rigor to stakes.
- Subjective value can still be real value.
- Complexity is not differentiation.
- First-version coding cost is not lifecycle cost.
- Skepticism should create clarity, not cynicism.
- **Reason broadly. Conclude narrowly.**

## Why the name?

Vibe coding is useful when it compresses the cost of implementing an idea worth trying.

When implementation starts before anyone checks the real intent, what already exists, which assumptions are false, or whether the result creates enough of the value it actually seeks, vibe coding turns into **vibeshit**.

`unvibeshit` is the check before that happens.