# Root Cause Analysis

Find the root of the problem quickly and prevent it from happening again.

Root Cause Analysis (RCA) is a systematic way to trace errors back to their true origin. It helps us see beyond surface symptoms and build durable solutions that stop repeat failures.

## Why do problems keep coming back?

When a system keeps breaking, fixing the bug is not enough. If the same type of issue keeps returning, the team is treating symptoms instead of the cause.

5 Whys and the Fishbone Diagram were created to solve exactly this kind of problem. They help teams move from "what broke" to "why it keeps breaking."

## Three layers of cause

- Direct cause: the immediate trigger
- Contributing cause: the conditions that made the problem easier to happen
- Root cause: the real source of the issue

### Fishbone Diagram

A visual RCA framework.

Typical dimensions:

| Category | English | Example |
|----------|---------|---------|
| People | PEOPLE | Lack of training, weak skills, fatigue |
| Process | PROCESS | Missing approvals, poor communication, incomplete docs |
| Technology | TECHNOLOGY | Architectural issues, outdated dependencies, performance bottlenecks |
| Environment | ENVIRONMENT | Unstable network, hardware failures, third-party service issues |
| Materials | MATERIALS | Poor data quality, configuration errors, resource shortages |
| Management | MANAGEMENT | Unclear goals, weak ownership, lack of oversight |

## When Should You Use It?

Use RCA for incident reviews, customer complaints, system performance issues, and security investigations.

## NASA Challenger Disaster (1986)

The Challenger exploded 73 seconds after launch, killing all seven astronauts. RCA showed this was not just a technical problem.

### Direct cause
- O-ring failure caused hot gas leakage

### Contributing causes
- Cold launch temperatures
- Engineer warnings ignored by management
- Broken communication paths

### Root causes
- Safety was not treated as the top organizational priority
- Technical expertise was overridden by schedule pressure
- A known design weakness had never been fully fixed

## What changed

| Dimension | Before | After |
|-----------|--------|-------|
| Safety culture | Launch on time first | Safety first |
| Decision making | Management-led | Engineers got veto power |
| Communication | Hierarchical and distorted | Direct technical reporting path |

## Five Keys to Making RCA Work

1. Cross-functional collaboration
2. Data-driven evidence
3. No-blame culture
4. Action-oriented outcomes
5. Continuous follow-up

## Timeline

RCA began in the nuclear and aerospace sectors and later spread into manufacturing, healthcare, DevOps, and product teams.

## Companion Tools

| Tool | Value |
|------|-------|
| Prometheus + Grafana | Detect anomalies and trigger RCA |
| Jira / Linear | Track RCA actions |
| Slack / Feishu | Coordinate the RCA team |
| Confluence / Notion | Build a knowledge base |
| ELK / Datadog | Provide data for root cause analysis |

