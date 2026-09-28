# Project

This repository is the public research project for Trusted Autonomous Systems.

## Mission

Develop deep expertise in systems where autonomous software can
understand context, receive bounded authority, perform consequential
actions, and remain controllable.

## Research tracks

1. Trusted autonomous enterprise systems
2. Trusted autonomous financial systems

Both share one trust layer: identity, authority, policy, delegation,
verification, audit, control, recovery.

## Repository structure

- `docs/knowledge-map/` — the versioned Trusted Autonomous Systems Knowledge Map.
- `docs/research/` — structured research documents, one per topic (see template below).
- `docs/architecture/` — architecture analyses: actors, components, trust boundaries, flows.
- `docs/experiments/` — experiment write-ups (`NNN-slug.md`): hypothesis, setup, attack, result, interpretation, limitations.
- `docs/decisions/` — decision records and workflow retrospectives (`NNN-slug.md`).
- `content/` — public articles by section: `foundations/`, `enterprise/`, `financial/`, `experiments/`.
- `sources/` — primary-source notes and excerpts with citations.
- `experiments/` — runnable experiment code, one directory per experiment.
- `site/` — the research website.
- `scripts/` — deterministic checks (links, markdown, citations).
- `resources/` — the strategy documents and `progress.md` (learning log). Not research content.
- `.claude/skills/` — reusable workflows (research-topic, architecture-analysis, technical-article, fact-check).

## Research topic template

Every `docs/research/*.md` uses these sections: Current understanding,
Definitions, Established facts, Architecture, Security properties, Threats,
Failure modes, Competing approaches, Open questions, Experiments, Sources,
Related topics, Last reviewed.

## Research principles

- Accuracy is more important than publication speed.
- Prefer primary sources: standards, specifications, official architecture docs, papers, incident reports.
- Never fabricate facts or citations.
- Separate facts, interpretation, hypotheses, and uncertainty.
- Challenge assumptions.
- Identify trust boundaries.
- Identify security properties.
- Identify failure modes.
- Verify important claims experimentally where possible.

## Writing

Content is written for technically sophisticated practitioners.
The bar: would a senior engineer learn something from this?

Prefer:
- concrete examples;
- architecture diagrams;
- sequence diagrams;
- threat models;
- experiments;
- primary sources;
- explicit uncertainty.

Avoid:
- generic AI-generated explanations;
- SEO-driven filler;
- unsupported claims.

## Agent behavior

For substantial work:
1. Inspect the relevant repository/context.
2. Understand the task.
3. Identify uncertainties.
4. Produce a plan.
5. Implement only after the plan is understood.
6. Test the result.
7. Report what changed and what remains uncertain.

Authority is granted progressively: read → analyze → propose → modify → test → commit → deploy.
Do not commit or deploy unless asked.

Never invent sources, technical facts, test results, or evidence.
