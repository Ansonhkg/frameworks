# Premortem

A premortem is the opposite of a postmortem. Instead of explaining what went wrong after a plan fails, imagine the plan has already failed and work backward to identify why before execution begins.

The method comes from psychologist Gary Klein. It was published in *Harvard Business Review*, and Daniel Kahneman called it one of the most valuable decision-making techniques he knew. The core mechanism is prospective hindsight: people identify more specific and honest risks when asked, "This already failed. What happened?" than when asked, "What could go wrong?"

## When to Use It

Use a premortem for commitments where the cost of being wrong is high:

- A product or feature launch
- A strategy, positioning, or pricing shift
- A major hire or partnership
- A go-to-market plan
- A capital allocation decision
- A legal, operational, or reputation-sensitive move

Do not use it for:

- Vague ideas with no concrete plan yet
- Factual questions with one right answer
- Creative feedback on a draft
- Decisions that are already irreversible

## Trigger Phrases

Strong fit when the user says things like:

- "premortem this"
- "run a premortem"
- "what could kill this?"
- "future-proof this"
- "stress test this plan"
- "what am I missing here?"
- "find the blind spots"
- "poke holes in this"
- "where will this break?"
- "devil's advocate this"

Do not trigger on simple feedback requests or when the user is asking for multiple perspectives rather than failure analysis.

## Minimum Context Threshold

Before running the premortem, gather enough context to answer three questions:

| Need | Question |
|---|---|
| What is it? | What plan, launch, product, hire, strategy, or decision is being premortemed? |
| Who is affected? | Who are the users, customers, team members, stakeholders, or counterparties? |
| What is success? | What outcome would make this plan a win? |

First scan available conversation and workspace context. If one of the three essentials is missing, ask only the most important missing question. Do not make the user fill out a form if the answer can be inferred.

## How to Run a Premortem

### 1. Set the Frame

State the premise explicitly:

> It is six months from now. This plan has failed. We are looking back to understand exactly why it died.

This frame matters. It moves the analysis out of polite risk assessment and into concrete failure explanation.

### 2. Generate Raw Failure Reasons

List every genuine reason the plan could have failed. The list should be comprehensive but not padded.

Each failure reason should be:

- Specific to the actual plan
- Grounded in available context
- A real threat, not a generic inconvenience
- Stated in one or two direct sentences

### 3. Deep-Dive Each Failure Mode

For each failure reason, analyze how it would actually unfold.

Use this structure:

| Section | Content |
|---|---|
| Failure Story | A concrete narrative of how this failure played out, including the moments where the plan started breaking. |
| Underlying Assumption | The one assumption that made the failure possible. |
| Early Warning Signs | One or two observable signals that would show this failure mode starting. |

For complex work, each failure mode can be delegated to a separate investigator or sub-agent and run in parallel. Keep each deep dive short, direct, and grounded in the plan.

### 4. Synthesize the Findings

Produce a premortem report with five parts:

1. **Most Likely Failure** — the scenario most likely to happen and why.
2. **Most Dangerous Failure** — the scenario that would cause the most damage even if it is less likely.
3. **Hidden Assumption** — the biggest assumption the plan depends on that has not been sufficiently tested.
4. **Revised Plan** — concrete changes that make the plan more resilient.
5. **Pre-Launch Checklist** — three to five things to verify, test, or put in place before execution.

The revised plan must be specific. Avoid vague advice like "consider pricing risk." Prefer concrete actions like "run a $47 pilot with 20 buyers before announcing the $297 workshop."

## Output Format

For lightweight use, answer directly in chat with:

```text
Premortem frame: It is six months from now and this failed because...

Most likely failure: ...
Most dangerous failure: ...
Hidden assumption: ...
Revised plan: ...
Pre-launch checklist:
- ...
- ...
- ...
```

For high-stakes or complex work, also save:

```text
premortem-report-[timestamp].html
premortem-transcript-[timestamp].md
```

The HTML report should be self-contained, visually scannable, and put the synthesis at the top. The transcript should include gathered context, raw failure reasons, deep dives, and final synthesis.

## Example

A founder plans a $297 live workshop for 50 marketing managers at companies with 10-50 employees.

Raw failure reasons might include:

1. Managers at that company size need approval for a $297 professional-development purchase, adding friction the launch plan ignored.
2. The tool-specific pitch assumes buyers already know they need AI workflow training, but most are still deciding whether AI matters.
3. The people who actually buy may be solopreneurs, creating a mismatch between the content and the intended audience.
4. The workshop requires realistic demo environments and multi-seat workflows, which take longer to prepare than expected.
5. Testimonials from the wrong attendee segment will make future cohorts harder to sell.

Synthesis:

- **Most likely failure:** audience mismatch and purchase friction.
- **Most dangerous failure:** building proof points from the wrong audience, which compounds positioning problems.
- **Hidden assumption:** the target buyers are reachable as a coherent segment and willing to self-identify around this pain.
- **Revision:** run a $47 pilot with 20 buyers first, then rebuild the full workshop around whoever actually buys and succeeds.

## Common Mistakes

| Mistake | Why It Fails |
|---|---|
| Asking "what could go wrong?" | Produces polite, hedged risk lists instead of specific failure stories. |
| Running without context | Creates generic failure modes that do not help decision-making. |
| Padding the list | Dilutes attention away from the risks that actually matter. |
| Stopping at risks | The value is in the revised plan and checklist, not the fear list. |
| Sugarcoating | The point is to hear the uncomfortable truth before reality delivers it. |

## Related Frameworks

| Framework | Relationship |
|---|---|
| SWOT Analysis | Broader strategic scan of strengths, weaknesses, opportunities, and threats. |
| Porter's Five Forces | Industry structure analysis rather than plan-specific failure analysis. |
| Assumption Validation Board | Useful after the premortem to test the hidden assumptions. |
| AAR | Looks backward after execution; premortem looks backward from an imagined future failure. |
