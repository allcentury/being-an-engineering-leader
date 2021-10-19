# Hi

I've made this document as a way for you to see and hear my thought processes while we work together.  New team members and leaders always come in with new perspectives (see #smell-test) and I've done my best to lay out who I am, what I care about and how I hope to act.  If you see me violating any of this, please [call me out](#feedback).

## Trade Offs

> “Give me a one-handed economist.  All my economists say, ‘on the one hand...', then, 'but on the other...'” - Harry Truman

I view engineering as a series of trade-offs.  Trade-offs, by definition implies that there's more than one answer but to me, some questions only have one answer.  For example, if you ask me whether to ship now and test later or test now and ship later, I will always answer that we should test now.  Some answers like this are automatic but most answers start with 'it depends...'

### One-sided answers

* Tests are part of code complete; you also own any manual tests in any environment your code lives (where automation isn't feasible)
* Automation over process

### Multi-sided answers

One of the ways I view your seniority is around your ability to foresee and communicate trade-offs.  For engineering decisions I've found this best by using an RFC process that forces you and the team to talk about a problem with multiple solutions.  These documents give you the chance to share the problem, the solutions you are thinking about while also allowing the team to contribute.  It's the best way I've found to build consensus, share knowledge and challenge each other to do the right long term thing on behalf of the customer and the team.

[RFC Template](broken-link)

## Craft vs Greenfield

In management I think a lot about what engineers care about, what their interests are and what they value.  Those topics are vast but I've settled on the idea of a two sided spectrum.  On the left side of the spectrum is craft and on the other end of the spectrum is greenfield.  Let's look at these in better detail:

#### Craft

Craft engineers love to build highly reliable, well architected systems.  They look at dashboards showing throughput and latency for fun and look to squeeze out every inch of the available compute resources whenever possible.  When things are on fire a craft engineer is the person you call and after the fire is out, they already have a dozen ideas of how to prevent the system(s) from having these problems ever again.  If you value principles like great code, highly available systems, test coverage, performance then you likely align with the craft mindset.

#### Greenfield

Greenfield engineers love to build new products and ship those to users.  Their motivation is at its peak when a product person comes down from the user-research mountain top and shares the next big thing that needs to be built.  Shipping new products and features gets a greenfield engineer motivated and at the end of the year when a greenfield engineer reflects on their achievements, the list always starts with the products they've shipped.

#### Identify Where You Are

During your career you will shift and move across this spectrum as will the company and its culture.  I share this because if you know where you are on this spectrum (hard craft, hard greenfield, somewhere in between) it can help you find initiatives, teams and companies that better align with your values.  There is nothing more frustrating than being on a team that only ships new features when all you want to fix is reliability.

For example, you've probably been on a team where you worked really hard on new products, then out of desperation due to a recent incident, finally a sprint was carved out to deal with tech debt.  This is a greenfield team acknowledging that it can't ship new features forever because craft will suffer, however, craft already suffered and worse, customers saw it.  Going from one end of the spectrum to another then back, then forth in quick succession can be exhausting for you as an engineer.

#### Ideas

* I've found the best teams have a balance but that a team with awareness of where they are on the spectrum have the best results
* Tell me where you are in this spectrum today and I'll work with you to find common ground.
* I will always do my best to showcase where the team should be on the spectrum for a given sprint.
* Major projects should start as greenfield and end with craft (sometimes you have to go craft -> greenfield -> craft)

Anecdotally I've bounced to each side of the spectrum about every 2 years.  When I was an IC there were some years I only cared about shipping new features and other times I only wanted to make those systems hum.

##### Big Picture

You gain new users with new products but you __keep__ those users with a focus on craft - I'll explain this to product managers and engineering leaders until my last breath.


## Smell Test

When you first step foot in someones house, you always notice the smell - good, bad or indifferent.  Over time though, the more you go to that house, less the smell catches your attention until eventually it becomes normal to you.

When you join a new team or a new company, in those first 90 days, I promise you will notice some smells.  For example, when I joined Braintree I noticed we did weekly releases via manual deploy checklists but I had just come from a company that did GitOps - this was a smell.  I encourage everyone that joins my team(s) to write down those smells and present them either to me or back to the team.  I'd prefer the latter but that assumes we have built up [psychological safety](#pyschological-safety).

## Psychological Safety

