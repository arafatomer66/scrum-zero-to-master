# The Sprint

*The container for all other Scrum events — a fixed-length, one-month-or-less box in which a Done, usable Increment gets created, and inside which almost nothing is allowed to change the goal.*

Sprints are the heartbeat of Scrum — the mechanism by which ideas actually turn into value on a predictable cadence. Everything else in the framework happens inside one: [Sprint Planning](sprint-planning.md), the [Daily Scrum](daily-scrum.md), the [Sprint Review](sprint-review.md), and the [Sprint Retrospective](sprint-retrospective.md) are not separate from the Sprint, they're how the Sprint gets executed and inspected. A Scrum Team that isn't running Sprints isn't running Scrum, no matter what else it's doing.

## Fixed length, back to back

Sprints are fixed-length events of one month or less, chosen up front by the Scrum Team and generally kept consistent Sprint over Sprint — a team doesn't run a two-week Sprint, then a five-week Sprint, then a ten-day Sprint, because a moving cadence destroys the predictability that the fixed length exists to create. A new Sprint starts immediately when the previous one concludes, with no gap in between. This matters more than it sounds: a gap between Sprints is a gap in inspection and adaptation, and it's exactly the kind of thing that quietly turns Scrum into a stop-start delivery process instead of a continuous empirical one.

The one-month ceiling isn't arbitrary. It's the outer bound on how long the Scrum Team goes without a full cycle of inspecting real, working output against the Product Goal — see [Scrum Theory: The Three Pillars](scrum-theory-pillars.md) for why that cadence is the whole mechanism Scrum depends on. Shorter Sprints (one or two weeks are common) tighten that feedback loop further, at the cost of more overhead spent on the events themselves.

## What can and can't change mid-Sprint

During the Sprint, two things are protected and one thing is allowed to move:

- **No changes are made that would endanger the Sprint Goal.** The Sprint Goal, set during [Sprint Planning](sprint-planning.md), is the commitment the whole Sprint exists to serve. It doesn't get renegotiated because week two turned out to be harder than expected.
- **Quality does not decrease.** Pressure to hit a deadline is never a legitimate reason to skip parts of the [Definition of Done](definition-of-done.md). If the Sprint Goal is genuinely at risk, the answer is to cut scope, not cut quality.
- **Scope may be clarified and renegotiated with the Product Owner as more is learned.** This is the part people miss: the Sprint Goal is fixed, but the exact set of Product Backlog items serving it is not sacred. If Developers learn midway through that one selected item isn't actually necessary to achieve the goal, or that a smaller version of it would serve the goal just as well, that's a normal, expected conversation with the Product Owner — not a violation of the Sprint's stability. The [Product Backlog](product-backlog.md) itself is also refined as needed throughout the Sprint; refinement of future work never stops just because a Sprint is in progress.

The distinction to hold onto: the *goal* is stable, the *path to it* can flex. A team that treats every locked-in Product Backlog item as equally untouchable ends up either padding Sprint Planning with buffer nobody admits to, or blowing every Sprint Goal the moment reality diverges from the plan — neither is what the Guide intends.

## Cancellation

A Sprint can be cancelled, but only under one condition: the Sprint Goal has become obsolete. Only the Product Owner has the authority to cancel a Sprint, though they may do so under the influence of stakeholders, Developers, or the Scrum Master raising the issue with them — the authority is theirs alone, not a team vote.

"Obsolete" is a high bar, and it's worth being concrete about what clears it versus what doesn't. If a client the entire Sprint's feature work was being built for cancels their contract mid-Sprint, the Sprint Goal is genuinely obsolete — there's no longer any value in finishing it, and cancelling is the honest move. If the market shifts so completely that the direction the Product Goal itself was serving no longer makes sense, that can cascade into Sprint cancellation too. What does *not* clear the bar: the work turning out to be harder than estimated, a key person going on unplanned leave, or stakeholders simply changing their minds about priority mid-Sprint without the goal itself becoming meaningless. Those are adaptation problems to be handled inside the Sprint — via the Daily Scrum, via renegotiating scope with the Product Owner, via the next Sprint Planning — not cancellation triggers.

Cancellation is rare in mature Scrum Teams for a good reason: it throws away the coordination cost that went into Sprint Planning and typically demoralizes the team, so a Scrum Team that finds itself cancelling Sprints often should treat that as a signal to look harder at how Sprint Goals are being set in the first place, not just accept it as a normal outcome.

## Why the container matters

The Sprint's fixed length and protected goal are what make the rest of the framework's timing guarantees possible. Because a Sprint is fixed and bounded, [Sprint Review](sprint-review.md) and [Sprint Retrospective](sprint-retrospective.md) happen on a predictable rhythm regardless of how any individual Sprint went. Because the Sprint Goal is protected from mid-Sprint reshuffling, the [Sprint Backlog](sprint-backlog.md) that Developers build during Planning stays meaningful all the way through — there's a stable target to actually check daily progress against in the [Daily Scrum](daily-scrum.md). Remove the container's stability and every other event loses the thing it's supposed to be inspecting.
