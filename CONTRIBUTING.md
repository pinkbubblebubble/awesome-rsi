# Contributing to Awesome RSI

Thank you for helping make this a precise, high-signal resource.

## Inclusion criteria

An entry should be directly useful for studying recursive self-improvement, persistent self-improvement, automated AI R&D, evaluation, or associated safety questions. Prefer primary sources, official implementations, and reproducible artifacts.

For systems that claim self-improvement, a contribution must say:

1. **What persists?** Model weights, code, prompts, memory, tools, skills, workflow, or another component.
2. **What supplies the signal?** Formal proof, executable verifier, held-out benchmark, environment reward, model judge, or human review.
3. **What is recursive?** Does the system improve the mechanism that creates later improvements, or only a fixed target component?
4. **What is the evidence?** Multi-generation results, baselines, artifacts, and limitations.

One-shot answer revision, generic agent frameworks, promotional claims without evaluation, duplicate links, and abandoned toy projects with no distinct technical contribution are normally out of scope.

## Pull requests

- Add one item per pull request when practical.
- Place it in the narrowest relevant section.
- Use the canonical paper title and link to the publisher, conference, or arXiv abstract page.
- Link the official code repository when one exists.
- Write one factual sentence explaining why the item belongs here; do not copy the source abstract.
- Apply one of the README labels: `RSI`, `Self-improvement`, or `Enabler`.
- Do not use marketing adjectives or report unverified performance claims.
- Confirm that every added link resolves.

Use this format for papers:

```markdown
- [`RSI` Paper Title](https://example.com/paper) (Venue Year) - What changes, how it is evaluated, and why the loop is recursive. [Code](https://github.com/org/repo)
```

Use this format for projects:

```markdown
- [org/repo](https://github.com/org/repo) - One-sentence technical description. ![GitHub stars](https://img.shields.io/github/stars/org/repo?style=social)
```

## Classification guide

- **`RSI`**: a persistent self-change is evaluated and the same or an improved process acts again; the improvement capability is inside the loop.
- **`Self-improvement`**: a persistent component improves across iterations, while the outer updater remains fixed.
- **`Enabler`**: the work supplies research automation, search, evaluation, verification, or safety machinery relevant to RSI.

When uncertain, use the weaker label and explain the limitation. Classification is about the demonstrated system, not its stated ambition.

## Safety

Do not contribute instructions that encourage running self-modifying code with broad host access or production credentials. Projects that execute generated code should document isolation, permissions, resource limits, logs, and rollback behavior.
