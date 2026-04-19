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

Before writing a single line of code for any system — loot, economy, taming, skill progression — I'd open a conversation and think out loud.

What should this system do?
How does it interact with the loop?
Where are the design traps?

That back-and-forth shaped every major system in Adventure Dreams before implementation started.

It's not that AI made the decisions.
It's that it made the decisions harder to get wrong.

---

### On Code: Direction, Not Delegation

When it came to implementation, the split was clear.

I directed the approach.
AI handled the implementation details.

That meant I needed to understand what I was building well enough to lead it — and review what came back critically enough to catch what was wrong.

It's pair programming with an incredibly fast partner who occasionally misses the point entirely.

The procedural floor generation system was built this way.
So were the combat mechanics, the artifact system, and the Soul Trap taming ability.

None of those would have shipped as fast without it.

---

### Where It Failed

The clearest failure was art.

I went in assuming AI image generation could maintain a coherent pixel art style across assets.

It couldn't.

Each generated asset looked plausible in isolation.
Together, they looked like they came from five different games.

The limitation isn't capability in the abstract — it's consistency over time and across a visual language.

I ended up doing what any engineering team does when a dependency fails:

Placeholder assets. Ship the mechanics. Return to the problem later.

That debt is still open.

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

—
Part 6 — Engineering an Indie Game
The Role AI Actually Plays in This Project

Full archive: https://github.com/gugalp/engineering-an-indie-game
#gamedev #indiedev #solodev #softwareengineering #buildinpublic