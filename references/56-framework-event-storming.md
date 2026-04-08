# Event Storming

Event Storming brings developers, product managers, and domain experts together around a wall of sticky notes so they can model a system together. It is one of the clearest ways to expose hidden complexity.

## Why It Matters

Different roles usually describe the same system in completely different ways.

Event Storming creates a shared language. It is not a document or a meeting note. It is a wall, a stack of sticky notes, and a group of people willing to question assumptions together.

## The Color Legend

| Color | Meaning |
|---|---|
| Blue | Commands - actions or requests |
| Orange | Events - things that already happened |
| Yellow | Aggregate roots - consistency boundaries |
| Purple | External systems |
| Green | Policies or business rules |
| Pink | Read models |
| Gray | Questions |
| Black | Boundaries |

## When to Use It

Event Storming is especially useful for:

- Legacy system refactoring
- New system design
- Cross-team collaboration
- Domain-driven design
- Agile planning and retrospectives

## Miro Case Study

Miro used Event Storming during a microservices migration.

The workshop helped the team identify events, commands, aggregates, external dependencies, and business rules. It also revealed service boundaries that were not obvious before the workshop.

### Results

- Migration time was cut roughly in half
- Hidden external dependencies were discovered
- Reusable microservice candidates were identified
- The team gained a much deeper shared understanding of the system

## How to Run a Workshop

1. Prepare the room, wall, sticky notes, and markers.
2. Storm the events from the user perspective.
3. Add commands that trigger the events.
4. Identify aggregates and their boundaries.
5. Mark external systems and policies.
6. Add read models and unresolved questions.
7. Review the map together and plan the next step.

## Time Guidance

| Phase | Suggested Time |
|---|---|
| Preparation | 30 minutes |
| Event storming | 2 hours |
| Command storming | 1 hour |
| Aggregate identification | 1 hour |
| External systems | 45 minutes |
| Policies and rules | 45 minutes |
| Read models | 30 minutes |
| Questions and wrap-up | 30 minutes |

## Facilitator Notes

- Stay neutral.
- Encourage quiet people to speak.
- Keep the pace moving.
- Allow debate, but do not let it drift forever.
- Capture key decisions.
- Photograph the wall when you are done.

