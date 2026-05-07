# Framing Terms Catalog

The Framing Terms Catalog is a communication framework for agent-assisted work. Instead of telling an agent how much to say, tell it what kind of thinking you need.

The core idea: instruction terms like "verdict first", "triage mode", or "actionable only" act as cognitive controls. They set the shape of the response before content generation begins.

## Why It Matters

Generic style instructions such as "be concise" or "be detailed" are ambiguous. They control length, not thinking. Framing terms reduce output friction by naming the decision mode, diagnostic lens, execution style, or review posture you want.

The terms compose. For example:

> triage mode, verdict first, actionable only

That short stack tells the agent to rank severity, lead with the answer, and avoid background explanation.

## When to Use It

Use this framework when:

- An agent keeps giving the wrong shape of answer
- You are context-switching and need fast orientation
- You need a decision, diagnosis, review, or execution plan
- You want reusable prompts for team or agent communication
- You need to lower cognitive load without writing a long prompt

Do not use it when the request is already precise or when the user needs domain expertise more than response-shaping.

## Term Catalog

### Decision

| Term | Use |
|---|---|
| verdict first | Lead with the answer, justify after. |
| recommend one | Force a single pick instead of a menu of options. |
| tradeoff table | Compare real options with upside, downside, and a pick. |
| go/no-go | Make a binary decision gate. |
| blast radius | Scope the impact before changing something. |
| reversibility check | Identify whether the decision can be undone and what being wrong costs. |

### Diagnosis

| Term | Use |
|---|---|
| broken system explanation | Explain expected behavior, actual behavior, and the gap. |
| root cause, not symptoms | Skip surface errors and identify the underlying cause. |
| fault isolation | Identify which layer or component is broken. |
| five whys | Drill down until the structural cause is visible. |
| smoke test | Find the quickest possible check to validate a hypothesis. |
| delta analysis | Identify what changed between working and broken. |

### Orientation

| Term | Use |
|---|---|
| lay of the land | Map the moving parts before diving in. |
| zoom level | Set the altitude of explanation. |
| breadcrumb trail | Trace a flow end-to-end. |
| mental model | Build an intuitive way to think about the system. |
| dependency map | Show what depends on what. |
| glossary mode | Define terms before explaining. |

### Triage

| Term | Use |
|---|---|
| triage mode | Rank by severity and identify what to fix first. |
| critical path only | Ignore anything that is not blocking. |
| 80/20 | Find the smallest change with the biggest leverage. |
| parking lot | Acknowledge non-urgent items and set them aside. |
| stop the bleeding | Choose the fastest stabilizing fix, not the perfect fix. |

### Review and Validation

| Term | Use |
|---|---|
| diff-level explanation | Explain only what changed and why. |
| red team this | Actively search for holes and failure modes. |
| steel man, then critique | Present the strongest version before criticizing. |
| assumption audit | Surface hidden assumptions that could be wrong. |
| premortem | Imagine the plan shipped and failed, then explain what killed it. |
| rubber duck mode | Reflect the user's logic and identify where it breaks. |

### Teaching and Understanding

| Term | Use |
|---|---|
| explain like a diagram | Give a structural explanation rather than a narrative one. |
| before/after | Show the transformation created by a change. |
| analogy mode | Map the concept to a familiar domain. |
| teach the concept, not the code | Separate the underlying idea from implementation details. |
| contrast with | Explain through comparison with something known. |
| narrate the why | Explain the intent behind each decision. |

### Execution

| Term | Use |
|---|---|
| actionable only | Include only things the user can act on now. |
| recipe mode | Provide numbered steps without extra explanation. |
| copy-paste ready | Make the output directly usable. |
| guard rails | State what not to do. |
| checkpoint mode | Break work into verifiable stages. |
| spike mode | Optimize for quick validation, not production quality. |

### Context Switching

| Term | Use |
|---|---|
| cold resume | Catch the user up as if they have been away for hours. |
| status line | Give a one-sentence project status. |
| next action | Skip recap and identify the next move. |
| parking lot recap | List deferred items to revisit. |
| handoff brief | Summarize as if passing the work to another operator. |

## How to Use It

1. Identify the kind of thinking needed: decision, diagnosis, orientation, triage, review, teaching, execution, or context-switching.
2. Pick one to three terms from the relevant category.
3. Put the terms at the front of the request.
4. Add the actual task.
5. If the result is still off, change the framing terms before adding more background.

## Examples

| Situation | Prompt |
|---|---|
| Too many errors | Triage mode, verdict first, actionable only: what do I fix first? |
| Risky deployment | Go/no-go, blast radius, reversibility check: is this safe to deploy? |
| Confusing system | Lay of the land, architecture zoom level: what are the moving parts? |
| Code review | Diff-level explanation, assumption audit: what changed and what could be wrong? |
| Returning after a break | Cold resume, status line, next action: where are we and what should I do next? |

## Escape Hatch

When the user cannot articulate the problem, use this prompt:

> I know something is wrong but I can't articulate it. Here's what I'm seeing: [symptoms]. Use Socratic questioning to narrow the scope.

This flips the cognitive load. The agent does the precision work instead of requiring the user to name the frame upfront.

## Common Mistakes

| Mistake | Why It Fails |
|---|---|
| Using too many terms | The response gets over-constrained and muddled. |
| Asking for brevity only | Length control does not specify the reasoning mode. |
| Combining incompatible frames | For example, "recipe mode" and "teach the concept" pull in different directions. |
| Adding more context before fixing the frame | The issue may be response shape, not missing information. |

## Related Frameworks

| Framework | Relationship |
|---|---|
| Five Why | A specific diagnosis frame for root-cause analysis. |
| RICE | A prioritization method that can follow triage. |
