---
title: Adding Depth — Four Systems to Make the Loop Feel Real
series: Engineering an Indie Game
part: 5
date: 2026-04-12
tags: [gamedev, solo-dev, devlog, unity]
---

# Engineering an Indie Game — Part 5

## Adding Depth — Four Systems to Make the Loop Feel Real

The prototype told me what was missing.

Collect and Improve were structurally there.
But they had no weight.

Players could fight through a tower and come back to town with nothing interesting to show for it.

That had to change.

---

### Four Systems. One Goal.

To make the loop actually feel meaningful, I needed to build four interconnected systems:

- A **loot system** — so what you find in the tower matters
- A **town economy** — so there's somewhere interesting to spend and trade
- A **skill tree** — so character growth feels like real progression
- A **taming system** — so the monsters you fight can become companions

Each connects to a different part of the core loop.
Some feed Collect. Some feed Improve. One feeds both.

![Collect and Improve Depth Diagram](/assets/collectImproveDepth.png "Collect and Improve Depth Diagram")

---

### The Taming System — and How It Enters the Game

I always planned to have a taming system.

The inspiration comes from *Azure Dreams*, where monsters fight alongside you as companions.

But I didn't want taming handed to the player at the start.

I wanted it to feel earned.

So I designed the artifact system around it: each tower in Adventure Dreams has a unique artifact waiting at the top — something with a meaningful, lasting impact on how you play. Inspired by the idea of labyrinths concealing something powerful at their core — a theme that runs through *Magi: The Labyrinth of Magic*.

The first tower's artifact grants the capture ability.

Tamed creatures fight alongside you on future runs — and grow stronger over time through leveling and evolution in town.

That's why taming sits at the intersection of both Collect and Improve.

---

### Designing the Systems

Building these four systems wasn't a single breakthrough moment.

It was a series of design conversations.

How should item rarities affect drop rates — and how do they interact with the economy without breaking it?
How should the taming system interact with the rest of the loop without breaking it?
How fast should the skill tree open up without making early floors feel pointless?

These aren't coding questions.
They're design questions with engineering consequences.

Having the right tools made all the difference.

---

### Where Things Stand

The foundation is there.
The depth isn't fully there yet.

Loot exists — but item variety and balance still need work.
The economy functions — but isn't creating interesting decisions yet.
The skill tree has structure — but not enough meaningful choices.
The taming system works — and it's the one I'm most confident in.

Good enough to feel like a game.
Not good enough to feel like *the* game yet.

---

### What's Next

In the next part, I'll talk about something I haven't addressed directly yet:

The role AI actually plays in this project — and what it means for solo development at this scope.

—  
**Engineering an Indie Game** is a series documenting my journey building *Adventure Dreams*.

Part engineering journal, part devlog, part learning process.

Full archive: [GitHub](https://github.com/gugalp/engineering-an-indie-game)