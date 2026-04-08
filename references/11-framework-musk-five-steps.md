# Musk Five-Step Method

Disruptive thinking and design thinking from SpaceX engineering practice: before you optimize or automate anything, question whether it should exist at all. Then simplify.

**Author**: Musk  
**Date**: January 2024

## Most Teams Optimize Things That Should Not Exist

Engineering and product teams often get stuck on how to build, how to optimize, and how to iterate before asking the more important question: should this thing exist in the first place?

Teams usually jump straight into tools and workflow automation to make a bad process faster. But if the thing should not exist at all, why optimize it?

The Musk five-step method reverses that instinct. First question the necessity, then remove everything unnecessary, and only then think about optimization. Once useless work is cut away, things usually become much simpler.

## Five Steps, In Order

These five steps cannot be rearranged. Each one creates the conditions for the next. Automating a bad process only makes the bad outcome happen faster.

**Step 1 - Question the requirement**
- Time stamp: 2024.01.15 | Musk interview clip
- Title: Question the requirement
- Body: Never accept a requirement blindly. Every request rests on an assumption. Who asked for it? What do they really want? Is there a better path no one has considered?

**Step 2 - Remove the steps**
- Time stamp: 2024.01.15 | Interview notes
- Title: Remove the steps
- Body: In any workflow, roughly 70% of the steps, features, code, or even team roles may never be used. Remove them now; do not wait for optimization first.

**Step 3 - Simplify what remains**
- Time stamp: 2024.01.15 | Internal discussion
- Title: Simplify what remains
- Body: Only after the requirement is real and the unnecessary pieces are gone should you improve usability, ease of adoption, or runtime efficiency.

**Step 4 - Prepare for automation**
- Time stamp: 2024.01.15 | Internal discussion
- Title: Prepare for automation
- Body: If a process still matters after the first three steps, structure it so the correct work can happen faster and with less friction.

**Step 5 - Automate last**
- Time stamp: 2024.01.15 | Internal discussion
- Title: Automate last
- Body: Automation is the final step, not the first. Optimizing a bad process only makes the bad result happen faster and harder to reverse.

### Warning

**Where did you skip the questioning step?**

Many teams treat a requirement document like a commandment. Someone drops a request and the team starts building immediately, without even asking what problem it solves. That leaves two questions unanswered: from whose perspective is this, and what does "better" actually mean?

## When Should You Use It?

Use this framework whenever a product or engineering team is under pressure and needs to ask, "Do we really need this?"

### Six Scenarios

**Scenario 1 - Repetitive, clunky work**
- Every day at 12:30 PM you spend 15 minutes exporting data from different systems and pasting it into another spreadsheet.

**Scenario 2 - Features that never end**
- The roadmap is full, but users keep saying the one feature they want most gets delayed again and again.

**Scenario 3 - Obvious engineering bottlenecks**
- The CTO complains that 70% of the team time goes to bug fixes and documentation instead of creating new value.

**Scenario 4 - The most important requirement was never built**
- Users look at the shipped feature and say, "This is not what I wanted."

**Scenario 5 - Technical debt is growing**
- The complaint is not that the code is bad; it is that the architecture never considered high-concurrency scenarios.

**Scenario 6 - Product and business are drifting apart**
- Product, marketing, and engineering meet every week and still cannot explain why the launch had no user response.

## SpaceX Falcon 9 Engine Mount Case

### Falcon 9 Merlin engine mount: 85 parts into 1

SpaceX was designing the Merlin rocket engine when an engineer proposed an aggressive manufacturing solution: use a 3D-printed bracket instead of the traditional temporary fixture. That change became one of the most direct cost reductions in the product.

### SpaceX logo area

SpaceX
Falcon 9 Merlin engine mount case study

### Left panel: Question the need, then remove the unnecessary

1. Traditional manufacturing workflow: design the frame, then weld the connection points. That usually requires a temporary fixture to hold the parts in place.
2. The engineer asked: "Do we really need a temporary bracket?"

### Right panel: Simplify, speed up, automate

- Simplify: Merge two manufacturing steps into one continuous printing process and remove assembly and welding work.
- Speed up: Cut the manufacturing cycle from weeks to days.
- Automate: Once the file is designed, the 3D printer does the work.

### Five-step results table

| Step | Time stamp | Content |
|------|------------|---------|
| 01 | 2024.01.15 | Question the requirement - do we really need a temporary bracket before welding? |
| 02 | 2024.01.15 | Remove the step - 3D printing can produce the bracket and engine structure together. |
| 03 | 2024.01.15 | Simplify - the cycle drops from weeks to days. |
| 04 | 2024.01.15 | Automate - the printer executes once the file is ready. |
| 05 | 2024.01.15 | Automate last - only the filtered, necessary work deserves automation. |

### Outcome

Cost dropped by 75%, and the manufacturing cycle shrank from weeks to days. The new process also removed a critical temporary part, cutting labor and material cost while speeding up time to market.

## Five Principles That Make the Framework Work

The method sounds simple, but the details determine whether it is actually effective or just theater.

**01 Senior managers should question the requirement first**
- The person with decision power should not start with implementation details or tool selection. First ask: "Does this really need to exist?"

**02 Every step needs a clear owner**
- Decide up front who can choose what to remove. Accountability can be delegated, but the decision power cannot be vague.

**03 Removing the unnecessary is already an optimization**
- If you can eliminate the temporary bracket, the welding step, the cooling wait, and the rework, you already have the best solution.

**04 Re-examine every feature and workflow in your team**
- Every time the team discusses a new feature, ask whether it is truly needed. Deleting an unnecessary feature is cheaper than building it and then deleting it later.

**05 Ask whether removing 90% is enough**
- Do not overthink the removal step. If cutting the requirement does not break the system, cut it.

## From Rocket Factory to Product Teams

The Musk five-step method comes from early aerospace practice and was refined through years of high-pressure engineering work at Tesla and SpaceX. It now applies well to software products too, because the core idea is the same: many failures come from spending unnecessary cost on fake or low-priority needs.

### Timeline

**2002 - SpaceX is founded**
- The early SpaceX mindset already emphasized removing unnecessary manufacturing steps and reducing temporary fixture cost.

**2012 - Tesla Model S reaches high-end production**
- Tesla used the same pattern: remove unnecessary steps, then simplify and optimize the system.

**2017 - Starlink launches**
- The same thinking appears in satellite design and manufacturing: simplify the structure, reduce cost, and improve reliability.

**2022 - Cybertruck enters mass production**
- A similar approach shows up in stainless steel bodies, integrated casting, and structural simplification.

**2023 - More AI and robotics integration**
- Optimus, Neuralink, and Starship continue the same pattern: remove unnecessary steps, then simplify, then optimize.

**Today - Ongoing iteration**
- The method applies beyond aerospace and automotive to software, product design, and even daily life.

## Companion Tools

| Tool | Description |
|------|-------------|
| First Principles | Start from basic facts and derive the best solution |
| 5 Whys | Find the root cause through repeated questioning |
| SWOT Analysis | Evaluate strengths, weaknesses, opportunities, and threats |
| Value Stream Mapping | Visualize and optimize the full flow from input to product |
| Lean Startup | Validate assumptions through rapid iteration and customer feedback |

