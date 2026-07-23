# Definition of Done

*The Scrum Team's shared, formal description of what "done" means for any Increment — the quality bar every Product Backlog item must clear before it counts as finished.*

The Definition of Done is a formal description of the state the [Increment](increment.md) must be in to meet the quality measures required for the product. It's not a checklist bolted onto the process as an afterthought — it's the actual boundary between "in progress" and "finished." The moment a Product Backlog item meets the Definition of Done, an Increment is born; before that, no matter how complete it looks, it's still work in flight.

## Why it matters — transparency, made concrete

The whole reason the Definition of Done exists is to give everyone on the Scrum Team, and everyone outside it, a shared understanding of what work was actually completed. Without it, "done" means whatever the person who wrote a given card intended, which is different for every person and drifts over time even for the same person. That's precisely the mechanism behind [Transparency](scrum-theory-pillars.md) as one of Scrum's three pillars: a Sprint Backlog or Increment can only be genuinely transparent if there's a shared, objective standard behind the word "done" that everyone is actually applying the same way. A team with five different private definitions of "done" can still run every event on schedule and still have nothing honest to inspect.

## Who sets it, and who has to follow it

Developers are the ones who must adhere to the Definition of Done — it's a direct extension of their [accountability](scrum-team.md) to instill quality in the Increment. If the organization already has a standard definition of done for the kind of work being produced, every Scrum Team in that organization follows it as a minimum baseline; they can add to it, but they can't drop below it. If no such organizational standard exists, the Scrum Team creates a Definition of Done appropriate to its own product. When multiple Scrum Teams are contributing to the same product, they need a shared, mutually compatible Definition of Done — otherwise one team's "done" Increment can silently fail to integrate with another team's, and nobody notices until it breaks in front of a customer.

## What happens when work doesn't meet it

If a Product Backlog item doesn't meet the Definition of Done, it isn't released, and it isn't presented at [Sprint Review](sprint-review.md) as finished work — those are things that only happen to actual Increments. Instead, it goes back to the [Product Backlog](product-backlog.md) for future consideration, and it doesn't count toward the Sprint's completed work, however far along it looked.

A concrete example: a Developer marks a Product Backlog item "done" going into Sprint Review, but it shipped with no automated tests and skipped code review because the usual reviewer was out that week. Against the team's actual Definition of Done, that item isn't done — it's not part of the Increment, it doesn't count toward the Sprint's completed work or velocity, and it goes back into the Product Backlog to be finished, either picked up in a future [Sprint Backlog](sprint-backlog.md) as leftover work or reprioritized by the Product Owner if it's no longer worth finishing exactly as started. This is the practical, unglamorous enforcement mechanism behind the idea that quality doesn't get to slide just because a deadline is close — see [the Sprint](sprint.md) on why quality is one of the two things explicitly protected during a Sprint.

## How it evolves over time

A team's Definition of Done isn't meant to stay fixed for the life of the product. As Developers gain experience and gather feedback from real use of the Increment, they can decide the current bar isn't catching enough — and raise it. When that happens, the new, stricter Definition of Done applies going forward; it isn't applied retroactively to Increments that were already Done under the old standard. This evolution is one of the few things the [Sprint Retrospective](sprint-retrospective.md) can directly and explicitly decide to change, and it's one of the clearest signs a Retrospective is doing real work rather than just going through the motions.

A concrete example of that evolution: a team's Definition of Done starts out as "code reviewed, unit tests pass, merged to main." Six Sprints in, three separate production incidents all trace back to the same gap — nothing was catching integration failures between services before release. At the next Retrospective, the team adds "integration tests pass in staging" to the Definition of Done. From that Sprint forward, no Product Backlog item counts as an Increment without it — not because a manager mandated it, but because the team that owns the standard raised its own bar in response to what it actually observed.

## A working checklist

Turning "code reviewed, tests pass, deployed to staging" style criteria into something a team can actually run through consistently, Sprint after Sprint, is covered practically in [Definition of Done Checklist](../08-templates-and-toolkit/definition-of-done-checklist.md) — useful both as a starting point for a team writing its first Definition of Done and as a sanity check for a team that suspects its current one has quietly gone stale.
