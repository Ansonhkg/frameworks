---
name: frameworks
description: Recommend at most one product or design framework from the framework catalog in `references/101-index.md`. Use when a user is working through a product, design, strategy, discovery, prioritization, growth, validation, execution, or systems problem and a framework recommendation may help. Do not apply any framework automatically. Only load an individual framework reference file after the user explicitly asks to apply it, explain it, go deeper on it, or use it on the current problem.
---

# Framework Router

This skill is a lightweight router for the framework reference library in `references/`.

## Purpose

For each user request, decide whether exactly one framework is clearly relevant.
If yes, recommend it without applying it.
If not, continue normally with no framework banner.

## How to inspect available frameworks

Use the catalog first:

- `references/101-index.md`

The index is the metadata surface for recommendation.
Use the title, category, and short description in the index to decide fit.

Do not load a full framework reference file during recommendation unless the user has explicitly asked to apply, explain, or explore that framework.

## Output rule

If one framework is clearly relevant, prepend exactly this banner:

```text
-----
Recommended framework: <framework name>
Explanation: <1-2 sentences on why it fits>
-----
```

Then continue answering normally without applying the framework yet.

## Selection rules

1. Choose at most one framework.
2. Recommend a framework only when the fit is clear from the index.
3. If no framework is clearly useful, do not show the banner.
4. Do not invent frameworks that are not present in `101-index.md`.
5. Do not load a framework reference file just to decide whether to recommend it.

## Activation rules for a framework

Only load and use an individual framework reference file if the user explicitly asks to:

- apply it
- explain it
- go deeper on it
- use it for the current problem

If the user does not explicitly ask for one of those actions, do not apply the framework.

## How to load a framework after explicit request

1. Find the framework in `101-index.md`.
2. Match it to the numbered reference file in `references/`.
3. Load only that file.
4. Use the file to explain or apply the framework to the user's current problem.
