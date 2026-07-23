# The Cross-Team Velocity Leaderboard

*Leadership starts publishing every team's story points side by side, and within two Sprints, teams that never gamed an estimate before are quietly inflating them to avoid looking slow.*

## The Situation

Anchorpoint Software runs six Scrum teams. The VP of Engineering, Radha Iyer, launches a weekly "Delivery Dashboard" emailed to all of engineering leadership, ranking teams by Sprint velocity: Team Sable at 54 points, Team Lynx at 41, Team Halyard — supported by Scrum Master Connor Blake — at 29, last place. Radha's cover note reads: "Great work, Sable — let's see if we can get everyone closer to that number."

Two Sprints later, Halyard's velocity has jumped to 38 with no visible increase in actual scope delivered. Developer Priyam Verma admits quietly to Connor: "We just started calling three-point stories fives. Pretty sure everyone's doing some version of it now." Meanwhile Team Sable, publicly "winning," has started padding too — worried about looking replaceable if a rival team closes the gap. Within weeks, story points no longer mean the same thing across teams, or even reliably within the same team over time — but the dashboard keeps climbing every team's numbers, which Radha reads, incorrectly, as across-the-board improvement.

## Why This Happens

This is a close-to-textbook case of Goodhart's law — a measure that stops being a good measure the moment it becomes a target — applied to a metric that was never designed for the use it's being put to:

- **Velocity is a team-relative capacity signal**, built from a team's own history and its own private sense of what a point means. Comparing it across teams is a category error even when the person doing it means well — Halyard's "5" and Sable's "5" were never the same unit to begin with.
- **A visible, rewarded number under leadership pressure predictably gets gamed.** This isn't a discipline failure in any one team; it's the expected outcome of exposing an internal forecasting tool to external competitive pressure.
- **Nobody explained the metric's actual purpose to leadership before it got published.** The difference between "a local forecasting tool" and "an objective productivity measure" looked like a harmless distinction until the dashboard made it load-bearing.
- **Inflation spreads even to teams that didn't start it.** Once one team's number climbs, every other team faces competitive pressure to keep pace or look worse by comparison — the dysfunction is contagious by design of the leaderboard itself.
- **The dashboard actively destroys the thing it was meant to surface.** Leadership now has a chart trending consistently upward and reads it as good news, when in fact it has systematically worse data than before the dashboard existed.

## The Scrum Master's Approach

1. **Name the mechanism directly and early, before it calcifies into a permanent fixture.** Connor raises it with Radha proactively: "Comparing velocity across teams isn't giving you what you think it's giving you, and here's what's already happening because of it."
2. **Bring specific evidence, not abstract theory.** Connor gathers concrete cases — Priyam's admission, a side-by-side of what a "5" meant on Halyard's board in March versus June — so the conversation is about observed behavior, not a philosophical objection to metrics in general.
3. **Reframe what leadership actually wants, and offer a real alternative.** Most leaders publishing a velocity leaderboard actually want predictability and throughput visibility, not a point-counting contest. Connor proposes forecast accuracy — did each team deliver what it committed to — or cycle time as substitutes, grounded in real dates and real delivered outcomes rather than a locally-defined unit; see [metrics and forecasting](../04-scrum-master-role/metrics-and-forecasting.md) for the fuller set of options that resist this kind of gaming.
4. **Protect the team's own estimation integrity in the meantime.** Connor coaches Halyard explicitly not to re-baseline its points to chase the dashboard, reaffirming in refinement that estimates exist for the team's own forecasting, not as an entry in someone else's scoreboard.
5. **Coordinate with the other five Scrum Masters rather than raise this alone.** Connor brings it to the cross-team Scrum Master sync; a consistent message from all six Scrum Masters carries more weight than one team's objection, and prevents the org from dismissing Halyard's concern as sour grapes over ranking last.
6. **Propose retiring the leaderboard, or at minimum the ranking, in favor of a per-team trend view** — is this team's own predictability improving over time — which is genuinely useful without inviting cross-team comparison at all.
7. **Keep coaching the team's estimation integrity regardless of whether leadership changes course immediately.** If the leaderboard survives the pushback, Connor treats this as a long-running organizational impediment to re-raise periodically with fresh evidence, not a single conversation to win or lose once.

## Likely Outcome

Radha doesn't kill the dashboard after one conversation — she invested real political capital building it — but she agrees to pilot a forecast-accuracy column alongside velocity and stops naming a weekly "winner" in her email. Estimate inflation slows but doesn't fully reverse on Halyard for a couple of Sprints, since trust in the number was already damaged; Connor has to run an explicit re-calibration exercise with the team to reset a meaningful baseline. About two quarters later, the forecast-accuracy numbers turn out to tell leadership a more useful story on their own, and cross-team velocity ranking quietly disappears from the dashboard without anyone having to fight for it a second time.

## Certification Exam Angle

A typical question: *"Organizational leadership publishes a report comparing Sprint velocity across multiple Scrum Teams, and team members have begun inflating story point estimates in response. What should the Scrum Master do?"* Trap answers include instructing the team to simply estimate honestly (addresses the symptom in one team while leaving the organization-wide incentive that caused it fully intact), recalibrating the team's points to match the top-performing team's scale (formalizes the gaming as official policy instead of fixing the underlying metric misuse), or ignoring it as an internal team matter outside the Scrum Master's concern (technically true that velocity is internal, but abdicates the responsibility to address an organizational impediment once its misuse is visibly damaging the team).

The correct-mindset answer recognizes velocity as a team-specific forecasting tool that is invalid for cross-team comparison, coaches the organization directly on why this particular metric use produces exactly the gaming behavior observed, and works to change the organizational practice itself — not merely to police the symptom inside one team. This is core [organizational-impediment](../04-scrum-master-role/the-4-sm-service-areas.md) territory, and it pairs closely with [scenario 11](11-fake-agile-scrumbut-organization.md), where a different organizational pattern similarly rewards the appearance of progress over the substance of it.
