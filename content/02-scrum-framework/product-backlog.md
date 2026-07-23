# The Product Backlog

*The single, emergent, ordered list of everything needed to improve the product — anchored by a Product Goal and refined continuously, never finished in one big upfront pass.*

The Product Backlog is an emergent, ordered list of what's needed to improve the product. It is the single source of work undertaken by the Scrum Team — if it's not on the Product Backlog, it isn't planned work, no matter how it entered the conversation. Managing it is the core of the [Product Owner's accountability](scrum-team.md), specifically: developing and communicating the Product Goal, creating and clearly communicating Product Backlog items, ordering them, and ensuring the whole list stays transparent and understood.

## The Product Goal

The Product Goal describes a future state of the product that the Scrum Team can plan against — it's the long-term objective the Sprint-level work is in service of. It lives at the top of the Product Backlog, and the rest of the backlog exists to answer one question: what needs to be true to fulfill it? A Scrum Team pursues one Product Goal at a time; the current one must be fulfilled, or deliberately abandoned, before the next one is taken up. This is what gives a sequence of otherwise-disconnected Sprints a shared direction — without it, a series of Sprint Goals is just a series of unrelated increments of activity, not progress toward anything in particular.

## Emergent, not fixed

"Emergent" is doing real work in the definition, and it's worth taking literally: the Product Backlog is never complete, never fully specified, and never meant to be. It's dynamic — constantly changing to reflect what the product actually needs to be viable, competitive, and useful as the market, the users, and the team's own understanding change. A backlog that stops changing isn't a sign of stability; it's usually a sign nobody's inspecting it against reality anymore. The Product Backlog exists for as long as the product exists, which means, practically, it never reaches a state of "done."

## Refinement is continuous, not an event

Product Backlog refinement is the act of breaking down and further defining items into smaller, more precise pieces — adding description, order, and size as more becomes known. This is genuinely ongoing work, not a scheduled ceremony: the 2020 Guide is explicit that refinement is *not* one of the five formal Scrum events, and it doesn't happen on a fixed calendar slot the way Sprint Planning or the Retrospective do. It happens throughout the Sprint, as needed, whenever the Scrum Team decides an upcoming item needs more clarity.

This is a common trap for people coming from older Scrum vocabulary or exam prep material: "backlog grooming" as a mandatory weekly meeting is a widespread practice, but it isn't Scrum Guide terminology, and treating refinement as a required formal event is a factual error worth correcting early — see [the history of Scrum](../01-agile-foundations/history-of-scrum.md) for where that legacy vocabulary came from. As a practical guardrail, refinement typically shouldn't consume more than roughly 10% of the Developers' capacity in a Sprint — enough to keep the near-term backlog usable, not so much that it eats into the Sprint's actual delivery work.

Sizing itself belongs to the Developers doing the work — they're the ones accountable for the estimate, though the Product Owner can and should influence the conversation by helping the team understand trade-offs and business context.

## What makes a good backlog item

A useful, informal way to think about the quality of any given item — without treating it as gospel from the Guide itself, since this is a synthesis rather than Scrum Guide vocabulary — is whether it's appropriately **detailed, estimated, emergent, and prioritized**:

- **Detailed appropriately** — items near the top of the backlog, likely to be pulled into the next Sprint, are broken down with enough clarity that Developers could plan them in a single Sprint Planning session. Items further down stay intentionally coarse; there's no value in polishing detail on something that might not be built for six months and might change entirely before then.
- **Estimated** — Developers can size it well enough to forecast it credibly, which usually means it's been through at least one round of refinement.
- **Emergent** — the item, and the backlog as a whole, is expected to change as more is learned. An item's description today is the team's best current understanding, not a locked specification.
- **Prioritized** — every item has a place in a single ordered list, not a "priority bucket" alongside a dozen other same-priority items. Order implies exactly one answer to "what should we pull next," and that answer belongs to the Product Owner, informed by — but not dictated by — the Developers' technical judgment.

## How it connects to the rest of the Sprint

Items that are refined enough to be completed within a single Sprint are what the Developers select from during [Sprint Planning](sprint-planning.md), where the Sprint Goal and selected items become the [Sprint Backlog](sprint-backlog.md). Items that meet the team's [Definition of Done](definition-of-done.md) by the end of a Sprint become part of the [Increment](increment.md). None of that works if the Product Backlog itself isn't kept genuinely transparent — the top of the list needs to actually reflect what the Product Owner believes matters most right now, not what mattered most three months ago when it was last touched.
