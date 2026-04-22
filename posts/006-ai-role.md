---
title: The Role AI Actually Plays in This Project
series: Engineering an Indie Game
part: 6
date: 2026-04-19
tags: [gamedev, solo-dev, devlog, ai-tools, unity]
---

# Engineering an Indie Game — Part 6

## The Role AI Actually Plays in This Project

I couldn't have gotten this far without AI.

I also want to be honest about what that means.

Because the way AI gets talked about in dev circles is usually one of two things:

It's either going to replace developers.
Or it's overhyped and barely useful.

Neither matches my experience.

---

### What AI Actually Did for This Project

I'm a solo developer.

No team. No art director. No second opinion down the hall.

AI filled a specific gap that's hard to name until you've felt it:

**The thinking partner gap.**

Before writing a single line of code for any system, I'd open a conversation and think out loud.

What should this system do?
How does it interact with the loop?
Where are the design traps?

That conversation became a spec.
The spec became a roadmap.
The roadmap became implementation.

I didn't know it at the time, but that's essentially what spec-driven development is —
a methodology that was just starting to surface when I was already doing it.

Not because I read about it.
Because it's what made sense as an engineer building alone.

The spec kept me honest.
It made scope pressure visible before it became a crisis.
And it gave me something to return to when a system started drifting.

It's not that AI made the decisions.
It's that it made the decisions harder to get wrong.

---

### On Code: Direction, Not Delegation

When it came to implementation, the split was clear.

I directed the approach.
AI handled the implementation details.

That meant I needed to understand what I was building well enough to lead it —
and review what came back critically enough to catch what was wrong.

That second part matters more than it sounds.

AI is a fast partner. It will produce something that compiles, passes a quick read, and looks reasonable.

It won't always produce something that fits the architecture you had in mind.

More than once, I got back code that technically worked and was structurally wrong for where the system needed to go.

Catching that required understanding the game deeply enough to know the difference.

It's pair programming — but the other developer doesn't carry your intent.
The code is readable. The reasoning behind it isn't always.
That gap is yours to manage.

---

### What This Means for Solo Dev

AI didn't replace the discipline this project requires.

It compressed the feedback loop.

Design decisions that would have taken days of research, prototyping, or waiting for input — happened in hours.

Implementation details that would have pulled me into Unity documentation rabbit holes — got resolved faster.

The bottleneck was never AI.

The bottleneck was — and still is — judgment.

Knowing what to build.
Knowing when something is wrong.
Knowing when good enough is actually good enough.

That part doesn't get outsourced.

In the next part, I'll go deeper on one of the systems that benefited most from this workflow:
the loot system — and the surprisingly tricky design problem of making items feel meaningful.

How are you using AI in your own projects — and where has it let you down?

—
Part 6 — Engineering an Indie Game
The Role AI Actually Plays in This Project

Full archive: https://github.com/gugalp/engineering-an-indie-game
#gamedev #indiedev #solodev #softwareengineering #buildinpublic