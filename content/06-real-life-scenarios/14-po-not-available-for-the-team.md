# The Product Owner Who's Never in the Room

*One Product Owner spread across three products means the Developers can't get a backlog question answered mid-Sprint, so they've started guessing — and guessing wrong.*

## The Situation

Simone Achebe is Product Owner for three products at Fernbank Analytics: a dashboard team, an API team, and Team Halcyon, supported by Scrum Master Marcus Webb. Simone attends Halcyon's Sprint Planning and Sprint Review reliably, but during the Sprint itself she's effectively unreachable — messages in the team channel sit unanswered for two or three days at a stretch.

In Sprint 19, developer Yara Solano asks in the team channel whether a CSV export feature should include soft-deleted records. No answer comes for two days. She makes a call — "no" — and builds it that way. At Sprint Review, a stakeholder from Finance flags that the audit trail specifically requires soft-deleted records to be included. The item gets reopened, costing roughly a day and a half of rework. This is the third guessed-and-wrong decision this Sprint alone. The developers have started joking, only half-joking, "when in doubt, guess no" as their actual working process.

## Why This Happens

A Product Owner who's structurally unreachable is rarely a discipline problem — it's almost always a resourcing problem the organization hasn't named:

- **One Product Owner across three products is an overcommitment the role was never designed to absorb.** Product Ownership assumes availability the organization didn't actually resource when it assigned Simone to a third product.
- **"Available during the Sprint" was never concretely defined**, so it defaults to whatever time is left over after Simone's highest-visibility obligations — which, in practice, is very little.
- **Developers, trained toward self-management, fill the gap rather than escalate it.** Nobody wants to look blocked, so a guess feels like progress in a way that raising "I've been waiting two days for an answer" as a blocker doesn't.
- **The cost stays invisible until Sprint Review**, because a guessed decision that turns out right looks identical, day to day, to a well-informed one — the gap only becomes visible when it's wrong, by which point the rework has already happened.

## The Scrum Master's Approach

1. **Make the cost visible with real numbers.** Marcus tallies the pattern across the last three Sprints: seven guessed decisions, three of them wrong, roughly four developer-days of rework total — turning a vague sense of friction into something concrete.
2. **Talk to Simone about capacity, not blame.** Marcus frames it plainly: "You're Product Owner for three products with no protected time carved out for any of them specifically. Halcyon lost about four developer-days to guessed decisions over the last three Sprints because we couldn't reach you in time." This names a structural reality Simone likely already feels but hasn't had data to describe to her own manager.
3. **Negotiate a specific, concrete availability commitment**, not a vague promise to "try to be more responsive" — for example, a standing thirty-minute daily or every-other-day window plus an agreed maximum response time, such as four business hours, for anything genuinely blocking.
4. **Establish a delegate for lower-stakes questions.** Marcus coaches Simone to name a business-side delegate — a business analyst or a senior developer with real product context — who can make smaller calls, with clear agreement on which categories (like anything touching compliance or Finance, as in the soft-delete case) must still go to Simone directly.
5. **Change how the team handles ambiguity in the meantime.** Instead of guessing quietly, Marcus coaches the team to flag "blocked on Product Owner decision" visibly at the Daily Scrum and, where the item isn't urgent, park it rather than build against a coin flip.
6. **Raise the structural problem upward as an organizational impediment**, using the rework data as evidence — one Product Owner across three products is a capacity decision above Marcus's authority to fix, and it needs to be named to Simone's manager directly rather than absorbed indefinitely by the team.
7. **Push ambiguity resolution earlier, into refinement, where Simone is actually present.** Marcus works with the team to surface more clarifying questions during [Product Backlog](../02-scrum-framework/product-backlog.md) refinement sessions Simone does attend, reducing how many decisions have to be made live, mid-Sprint, in the first place.

## Likely Outcome

After the data-backed conversation, Simone commits to a standing thirty-minute daily window, and response time on blocking questions drops from two or three days to same-day. The delegate arrangement — business analyst Tomas Reyes — absorbs roughly half the lower-stakes questions that used to go unanswered. Guessed-and-wrong incidents drop from three in a single Sprint to roughly one every couple of Sprints. The deeper structural problem — one Product Owner genuinely can't serve three products well — isn't solved, since that requires a hiring decision above Marcus's authority, but it's now documented and part of a capacity conversation Simone's manager can no longer treat as invisible.

## Certification Exam Angle

A common framing: *"The Product Owner is unavailable to the Development Team during the Sprint, and Developers have started making their own assumptions about backlog item details. What should the Scrum Master do?"* Trap answers include having the Scrum Master answer the Developers' backlog questions directly on the Product Owner's behalf (the Scrum Master isn't accountable for product decisions and this just creates a second, equally unreliable proxy), telling the Developers to stop asking and simply build to their best interpretation (formalizes the guessing instead of addressing it), or moving straight to replacing the Product Owner (well outside the Scrum Master's authority and skips every less drastic option first).

The correct-mindset answer is that the Scrum Master's job is to make the availability gap and its real cost transparent, coach the Product Owner toward a sustainable way to serve the team — including delegation where appropriate — and treat chronic unavailability as an organizational impediment to raise upward, never to quietly absorb the Product Owner's accountability. See [Managing Products with Agility](../03-professional-scrum-competencies/03-managing-products-with-agility.md) for the fuller model of what Product Ownership actually requires, and [scenario 02](02-product-owner-wont-prioritize.md) for a related but distinct failure mode where the Product Owner is present but still won't make the call.
