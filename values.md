# Hi

I've made this document as a way for you to see and hear my thought processes while we work together.  New team members and leaders always come in with new perspectives (see [smell test](#smell-test)) and I've done my best to lay out who I am, what I care about and how I hope to act.  If you see me violating any of this, please [call me out](#feedback).

## Trade Offs

> “Give me a one-handed economist.  All my economists say, ‘on the one hand...', then, 'but on the other...'” - Harry Truman

I view engineering as a series of trade-offs.  Trade-offs, by definition implies that there's more than one answer but to me, some questions only have one answer.  For example, if you ask me whether to ship now and test later or test now and ship later, I will always answer that we should test now.  Some answers like this are automatic but most answers start with 'it depends...'

### One-sided answers

* Tests are part of code complete
* You own any manual tests in any environment your code lives (where automation isn't feasible)
* Automation over process

### Multi-sided answers

One of the ways I get a glimpse into your thought process is around your ability to foresee and communicate trade-offs.  For engineering decisions I've found this best by using an RFC process that forces you and the team to talk about a problem with multiple solutions.  These documents give you the chance to share the problem, the solutions you are thinking about while also allowing the team to contribute.  It's also the best way I've found to build consensus, share knowledge and challenge each other to do the right long term thing on behalf of the customer and the team.  We won't reach consensus every time - see [decision making](#decision-making).

[RFC Template](broken-link)

## Craft vs Greenfield

In management I think a lot about what engineers care about, what their interests are and what they value.  Those topics are vast but I've settled on the idea of a two sided spectrum.  On the left side of the spectrum is craft and on the other end of the spectrum is greenfield.  Let's look at these in better detail:

#### Craft

Craft engineers love to build highly reliable, well architected systems.  They look at dashboards showing throughput and latency for fun and long to squeeze out every inch of the available compute resources whenever possible.  When things are on fire a craft engineer is the person you call and after the fire is out, they already have a dozen ideas of how to prevent the system(s) from having these problems ever again.  If you value principles like great code, highly available systems, test coverage, performance then you likely align with the craft mindset.

#### Greenfield

Greenfield engineers love to build new products and ship those to users.  Their motivation is at its peak when a product person comes down from the user-research mountain top and shares the next big thing that needs to be built.  Shipping new products and features gets a greenfield engineer motivated and at the end of the year when a greenfield engineer reflects on their achievements, the list always starts with the products they've shipped.

#### Identify Where You Are

During your career you will shift and move across this spectrum as will the company and its culture.  I share this because if you know where you are on this spectrum (hard craft, hard greenfield, somewhere in between) it can help you find initiatives, teams and companies that better align with your values.  There is nothing more frustrating than being on a team that only ships new features when all you want to fix is reliability.

For example, you've probably been on a team where you worked really hard on new products, then out of desperation due to a recent incident, finally a sprint was carved out to deal with tech debt.  This is a greenfield team acknowledging that it can't ship new features indefinitely because craft will suffer, however, craft already suffered and worse, customers saw it.  Going from one end of the spectrum to another then back then forth in quick succession can be exhausting for you as an engineer.

#### Ideas

* I've found the best teams have a balance but that a team with awareness of where they are on the spectrum have the best results.
* Tell me where you are in this spectrum today and I'll work with you to find common ground.
* I will always do my best to showcase where the team should be on the spectrum for a given sprint.
* Major projects should start as greenfield and end with craft (sometimes you have to go craft -> greenfield -> craft).

Anecdotally I've bounced to each side of the spectrum about every 2 years.  When I was an IC there were some years I only cared about shipping new features and other times I only wanted to make those systems hum.

##### Big Picture

You gain new users with new products but you __keep__ those users with a focus on craft - I'll explain this to product managers and engineering leaders until my last breath.

## Smell Test

When you first step foot in someones house, you always notice the smell - good, bad or indifferent.  Over time though, the more you go to that house, the less the smell catches your attention until eventually it becomes normal to you.

When you join a new team or a new company, in those first 90 days, I promise you will notice some smells.  For example, when I joined Braintree I noticed we did weekly releases via manual deploy checklists but I had just come from a company that did GitOps - this was a smell.  I encourage everyone that joins my team(s) to write down those smells and present them either to me or back to the team.  I'd prefer the latter but that assumes we have built up [psychological safety](#pyschological-safety).

## Project Aristotle

In 2012 Google's research was [informally published][project-aristotle-nyt] on what made some teams so much more successful than others.  They've since created more on the topic in [re:Work][project-aristotle]. There are 3 big takeaways, each of which I want to embrace on the team:

### Clear Goals

You should know exactly how the work you do on your team contributes to our company's mission.  There should be no mental gymnastics needed here.

### Culture of Dependability

Teammates need to *trust* that you are going to do what you said you would.  When trust breaks within a team and others pick up the slack, we have violated this principle.

### Psychological Safety

>  ... to feel ‘‘psychologically safe,’’ we must know that we can be free enough, sometimes, to share the things that scare us without fear of recriminations. We must be able to talk about what is messy or sad, to have hard conversations with colleagues who are driving us crazy. We can’t be focused just on efficiency. Rather, when we start the morning by collaborating with a team of engineers and then send emails to our marketing colleagues and then jump on a conference call, we want to know that those people really hear us. We want to know that work is more than just labor.

Team members feel safe to take risks, speak their mind and be vulnerable in front of one another.

## Leveling Up and Expectations

One of the hardest and most complicated areas regarding your career are your own expectations and where that intersects with your companies expectations.  PayPal has the [Step Up Guide](https://go/stepup) which is a great guide to help you think about what you're great at and where you need to improve.  In addition to that guide, here is where I stand on high performers and level expectations.

### High Performers at the Senior+ Level

High performers deliver with autonomy, clarity and efficiency.  You see trade-offs a mile away and offer up solutions for both short term and long term perspectives.  You understand the business risks associated with all solutions and have no problems communicating to technical and non-technical stakeholders alike.

You take ownership of projects, code and mentees.  Did a bug of yours make it to production?  You own it.  Did your mentee create a bug?  You own it.  Is a project going to miss a deadline?  You've informed me well in advance and you own it.

Owning it can mean different things in different context but let's take an example:

#### Your Mentee Shipped A Bug

Your mentee just shipped a bug and we're talking about it in our 1/1:

Me:  Let's talk about Incident-123.
You: Thanks for bringing this up.  The code that broke production came from the project we were both working on.  I missed the problem during code review and we clearly missed some automated tests to go along with it.  I've chatted with mentee about it, we talked about how to tighten up future code changes and what tests are needed for a feature to be shipped.  If there's more to share with the rest of the team we'll present it at our next retro.

Breaking that down:

1. You took ownership for a mistake that wasn't directly yours
1. You showed me your dove into the problem enough to know what went wrong
1. You have ideas on solutions
1. You're accountable to the rest of the team

By having this mindset and accountability you will create such a positive impact on your mentee and your team.  I promise that for any teams I am part of, failing is never a blame game.  Owners feel that blame without it being directed towards them but bugs are not one persons fault - we all have to be active and vigilant to raise the bar and ship higher quality products.


## Resources

[project-aristotle-nyt]: https://www.nytimes.com/2016/02/28/magazine/what-google-learned-from-its-quest-to-build-the-perfect-team.html#commentsContainer
[project-aristotle]: https://rework.withgoogle.com/print/guides/5721312655835136/
