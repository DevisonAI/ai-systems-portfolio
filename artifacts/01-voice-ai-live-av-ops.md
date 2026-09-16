# Voice-AI meets live AV ops

## Thesis

Voice-AI products fail the same way live AV fails: latency budgets, clock domains, failover, and who is holding control when something glitches. Prompt quality is not the bottleneck once agents sit next to microphones and people.

## Mapping

| Live AV (Tesira / Dante) | Agent / Voice-AI analogue |
| --- | --- |
| Clock and sample-rate discipline | Turn-taking and barge-in latency budgets |
| Redundant paths / failover | Tool fallback and clear stop rules when upstream flips |
| Gain structure before effects | Context hygiene before complex prompting |
| Operator at front of house | Explicit human approval on irreversible steps |
| Show continues when a node dies | Partial degrade instead of hard crash |

## Experience this draws on

- Live venue audio at Colorado Convention Center scale (Biamp Tesira and networked audio)
- Multi-agent systems with gated irreversible steps
- Active certification path in Dante (Level 2 toward Level 3) and AWS Certified AI Practitioner

## Good fit

- Voice-AI and conversational systems that must hold up under real latency and failure
- Operational design for agent fleets (verification, ceilings, controlled pause)
- Connecting pro-audio / AV constraints to AI product work

## Scope

Not positioning as a pure ML researcher. Venue AV experience informs the systems work on this profile.
