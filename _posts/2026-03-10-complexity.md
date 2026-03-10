---
layout: post
title: "The New Complexity Trap"
date: 2026-03-10 12:00:00 +1100
---
# The New Complexity Trap

<span class="publish-date"> Published on  {{ page.date | date: "%d %B %Y" }}

In my professional life I’ve repeatedly seen the same pattern.

The first example involves a system a bit like the tax system. It’s made up of rules for revenue generation, those rules are supposed to encourage good behaviour, which in turn requires that they be understandable by the general public. The rules also have to be administered by government, which nowadays means being encoded in software implementations.

This system, like modern tax systems, is incredibly convoluted, so that it’s impossible to get the incentives right. No-one could follow those incentives even if they did exist because no-one understands the system anyway and the taxpayers are deeply unhappy because they suspect they’re being rorted by government in the fine print. The cost to administer the system is so high that it eats into a lot of the revenue it’s supposed to generate.

Everyone with any knowledge of this system is appalled with the unnecessary complexity and has implored the government to simplify it. The minister’s office, which has no understanding of the system whatsoever, has repeatedly rejected these pleas.

The second example is the machinery of government. Every few years there’s a government restructure. The portfolio is a byzantine mess riddled with waste, duplication and inefficiency. Even when teams do important work, no-one can find them because there’s no internal logic in the org-chart. Anyone with a working knowledge of this system can easily proffer many simplifications which would restore some level of order.

Unfortunately the decisions are made by people with no working knowledge of the system; typically senior-managers who’ve been parachuted in from the private sector who don’t know what anyone does, who further delegate the work to consultants who are even more clueless. Consequently with every restructure the government becomes even more labyrinthine, which ultimately confounds the senior managers who made the decision as they’re most often the ones who might need to consult an org-chart.

The third example is one many will be familiar with: tech debt. Like many I’ve seen archaic systems where something that should take an hour might take a week. The trouble, as anyone who’s ever been in this situation can attest to, is that non-technical managers invariably fail to understand the problem.

Of course the standard claim at this point is that engineers are just bad at communicating. They simply need to re-express their ideas around refactoring etc. in terms of ‘value to the business’ or some such. But I’ve never seen this work. Instead I’ve seen the same thing over and over: people who understand complex systems also understand the importance of minimising that complexity wherever possible; people who have never understood a complex system in their life never ever grasp this and cannot be convinced.

Imagine you’re a dumb non-technical manager. You think coding is basically magic. Sometimes when you ask the engineers to add a feature (which is like casting a spell), they give some weird story about how they could cast the spell quickly, but it’s better to do so slowly to prevent their magic becoming impotent and making future spells take longer. This is obviously unconvincing; it sounds like something slackers would say. So why are we surprised when managers who think like this fail to grasp the importance of controlling tech debt?

***

Joseph Tainter famously claimed that the rise and fall of civilisations can be explained through the lens of complexity. Simple societies adapt to crises through adaptations which increase complexity. As these societies advance they accumulate more and more complexity, scars from past traumas, which make them too sclerotic to adapt to future challenges.

While I think this narrative is overdrawn, there’s some truth to it. And what we’re doing as a civilisation is speed-running this process. All our systems are growing more complex more rapidly than is necessary, because the people who make the decisions which control how complex they become are idiots who’ve never had to wrangle with complexity and so cannot grasp the advantages of simplicity.

***
\
Next consider AI. Assuming we see only marginal improvements hereafter (plausible given the trajectory over the last few years) it has two qualities:

1. A tremendous superiority to humans in terms of working-memory and the ability to traverse documentation, which means it can easily work with systems much too complicated for a human to keep in their head.

2. It’s presently inferior to humans in controlling complexity when modifying systems. It fails to see things in a holistic fashion; in some sense it is brute-forcing the problem.

Even if 2 is solved, there’s no reason to expect AIs not to run into the same problem humans do. Just as human-coded projects tend to reach a level of complexity with which its own authors struggle, so too will AIs, even if that level of complexity is unfathomable to humans.

***
\
So let’s consider what might happen when you combine AIs with the phenomenon I began with.


Take the legal system, a textbook example of a system that’s grown too complex. We have tried to cope through ever-greater specialisation so that individual legal experts can stay on top of their specific area of the law, but this is not a sustainable solution. The problem is exacerbated because new laws from legislators and regulators tend to be poorly written, verbose, overly vague, sometimes contradicting other laws, etc. This is because the best legal minds aren’t going into politics or working for the government regulators, so we have idiotic managerial-types vandalising the system as described in the opening section.

LLMs are especially well-equipped to handle the situation. They can trawl through regulations or case-law to find relevant precedent. Their linguistic capabilities are sufficient for the task. Their lack of creativity, undoubtedly a demerit in many fields, is almost a positive when it comes to legal reasoning. So even today we should expect the rapid adoption of AI by legislators, regulators, lawyers, judges, etc.

What this means, in practice, is that humans will increasingly not interact with the laws directly, but will interface with them through AI. The law becomes a black-box. Some predictions from this:

1. The marginal cost of idiotic modifications to the system will go down. Consider how many pages of regulation get churned out currently, then imagine how much greater it will be once you no longer need to employ people to do it.

2. The immediate downside to this is obviated because it will be the LLMs who have to contend with these changes.

3. In the long-run the legal code in the black-box will degrade in quality to such an extent that even AI struggles. In part this is because they’re bad at controlling the complexity budget when modifying systems, but mostly it will simply be that the directives they’re receiving are stupid and they’re too obsequious to push back.

4. Naturally the power and market compensation of people who do understand complex systems will be destroyed by competition with the AIs. We might have a generation or two that doesn’t invest any time or effort into understanding complex systems because there’s no reward, only for us to collectively find out that all the systems are broken.

To reiterate, the problem here is not really the AI. The problem is we have a lot of very dumb managers who think they can control systems they don’t understand. This it not possible. They will not be able to articulate what they want from these systems, they will not be able to understand the outputs of these systems, they will regularly ask for things which are impossible, and we know this because we see it *today* when managers interact with high-skilled professionals. Replacing the high-skilled professionals with AI won’t address the major problem, it will make it worse.

Put another way: we should be worrying not just about AI-alignment, but the alignment of the complex systems AI interacts with. If the tax code is already misaligned, why we would expect AI to fix it just because it can speak English, is reasonably benevolent and intelligent? The people who currently work with the tax code also speak English, are reasonably benevolent and intelligent, and yet the tax code is horribly misaligned (according to everyone: tax officials, economists, politicians, voters, lobbyists, accounting bodies, etc.)

And while this post has so far mentioned systems already over-burdened with complexity, there are others that still work fairly well. The electricity grid, air traffic control, banking, code compilers, etc. We need to consider what happens if by 2060 no-one understands these systems at all but they still need to be modified. My suspicion is that if people who don’t understand these systems try to control them it will go about as successfully as say Number 10 controlling the British government currently.

Unless AI gets considerably *smarter* than humans it could end up being a net-negative. AI is going to do for intellectual labour what slaves did for manual labour. Slaves mostly did work that would otherwise have been done by freemen, while devaluing the status of work and creating an idle culture. AI is going to devalue intellectual work while, like slavery, having negative second-order implications for the political economy. So we better hope they’re superior substitutes or complements for high-skill professionals, not mere equals.
