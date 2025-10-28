---
title: NotebookLM Became Our Best Onboarding Tool in 15 Minutes (And Yours Can Too)
date: 2025-10-28
tldr: no tldr
tags: [LLM,Google,NotebookLM, Gemini, software-engineering]
---

# NotebookLM Became Our Best Onboarding Tool in 15 Minutes (And Yours Can Too)

I set up NotebookLM as our team's onboarding buddy in 15 minutes. Now new engineers can explore our system's architecture and understand our questionable 2020 decisions without bothering Steve, the guy who knows everything and will absolutely tell you why your idea won't work.

This isn't another AI fanboy post. This is about why I had coffee and configured NotebookLM in the same meeting while your team is still debating if documentation is "worth the time."

Spoiler: **we actually write things down**.

## The Auto-Complete Trap
![typing](https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExMmJkOGxwaG5xYzBwOW84MGwyNzJpcGl6cXR0ZGltZTVrYjJ1M3l4aSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/3o6Ztr9s7vPAS8XtK0/giphy.gif)

We live in the golden age of LLMs and autocomplete on steroids. We barely finish our own sentences anymore. Claude code writes entire functions while we're thinking about variable names.

But here's the uncomfortable truth: as engineers, we need to write about what we're going to do *more* than we actually do it.

I know, I know. Writing is boring. You got into engineering to build things, not play technical novelist. But if you can't articulate your plan before you build it, you either have no idea what you're doing, or you're in "move fast and break things" mode. which is terrifying when you're modifying production systems actual humans depend on.

Good documentation isn't just communication, It's proof you actually thought this through.

## The Four Pillars of Looking Like You Knew What You Were Doing

### 1. Start with an Actual Problem Statement

"Performance is bad" is not a problem statement. That's a complaint.

"API response times increased from 200ms to 2.5s at the 95th percentile, and customers are rage clicking the submit button" is a problem statement.

See the difference? One makes you sound competent. The other gives you... vibes.

![](https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExYmV4dWV2cG9xbmppZjJ0dGJobzNxeWl2ZHF2eHJnb2JzazVramlqMiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/vwI4mYEHP8k0w/giphy.gif)

### 2. Write Context Like Everyone's Clueless

Because they are. And future you, staring at this code six months from now, will also be clueless.

What's the background? What's the status quo? Why did we end up here?

Document the constraints, dependencies, and historical decisions. "Because Steve built it" is not acceptable context.

![](https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExMnQ1MWxid2V5dm0ydWN2Z2w4azVlaWxlMXVrM3c3ZXlhbTd2NXVweiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/v0eHX3n28wvoQ/giphy.gif)

### 3. Document All Solutions (Even the Dumb Ones)

I used to think "just write down the solution you already picked" was efficient.

Then I grew up and realized documenting every option, even the ones that make you go "lol no", prevents your brain from going sideways during implementation. You've already addressed why Solution B won't work. You don't need to rediscover this at random on a wednesday halfway through.

Plus, it makes the design process actually collaborative instead of "here's the solution, fight me."

![](https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExbWZlOHFjajNvemJpaXdsZjFibnJrZXIzZHRnYmxmYWlkMXNrMHJseSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/sG4zmff2zDOp7t2MNA/giphy.gif)

### 4. Add FAQ and Appendix (Or Admit You Winged It)

If you don't have questions about your own solution, you haven't thought about it hard enough.

If you see your design as invincible, you've missed something. I guarantee it.

Write an FAQ. What could go wrong? What assumptions are you making? What happens when Product changes requirements halfway through?

Include an appendix. Did you benchmark anything? Read any blog posts? No? Then your doc is a vibe check, not a design.

![](https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExbjBhd21vbGlucXc2dm5qYm4yajJxdXRoOWoyMWZ1dXp3dzNqenFtbSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/4xWGyVKoXqg2eVCiq9/giphy.gif)

## Finally

When you do this for every project, something wild happens: **you can actually use AI tools effectively**.

NotebookLM doesn't just work because Google made a good product. It works because we gave it good inputs. Clear problem statements. Historical context. Design decisions with explanations.

New engineers can ask an AI about our architecture and get *accurate answers*. They can understand why we chose approach X over Y without another meeting with Steve (who doesn't want another meeting either).


That 15-minute NotebookLM setup wasn't impressive because I'm an AI wizard. It was impressive because we spent years writing things down like adults.

So next time you're tempted to skip the design doc because "we need to move fast," remember: future you doesn't know the context. Your teammates don't know the context. And that fancy AI tool you want to use? It definitely doesn't know the context.

Start writing things down. Or don't, and spend the rest of your career explaining the same architectural decisions to every new engineer who joins.

Your choice.

---

*Built something that scales? Have war stories from your first year? I'd love to hear them. Find me on [LinkedIn](https://www.linkedin.com/in/muhammad-khalil/) [Twitter](https://x.com/mo7amad_khalil).*