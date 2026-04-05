---
title: Building the First Prototype of Adventure Dreams
series: Engineering an Indie Game
part: 4
date: 2026-04-05
tags: [gamedev, solo-dev, devlog, unity, prototype]
---

# Engineering an Indie Game — Part 4

## Building the First Prototype of Adventure Dreams

I had a core loop on paper.

Explore → Fight → Collect → Improve

Now I needed to find out if it actually worked.

The only way to know was to build it.

---

### Where to Start

There's no single right answer for where to begin a prototype.

Before writing any code, I designed each system first.

For every major piece of the game, I brainstormed with AI to draft a lightweight roadmap —
not a rigid specification, but enough structure to move with intention.

Then I started building, picking up whatever felt most foundational at each step:

- Main menu and character creation
- Town and world movement
- Player inventory
- Equipment mechanics
- Entry point into the first tower
- Tower structure and turn-based movement
- Enemies
- Combat

Each roadmap evolved as implementation revealed things the design hadn't anticipated.

But the habit of designing before building kept the work from becoming reactive.

Two months later, I had something playable.

Not polished.
Not complete.

But playable.

---

### The Technical Decision That Shaped Everything

One of the earliest design decisions was how to build the tower floors.

I could hand-craft them.
Or I could generate them procedurally.

I chose procedural generation.

Not for scope reasons — but because it's the right design decision for this kind of game.

Replayability matters in a dungeon crawler.

If every run feels the same, players stop exploring.

So I built a random floor generation system from scratch, with the help of AI as a development tool.

That system became one of the core technical pillars of the prototype.

---

### What the Prototype Revealed

The loop worked structurally.

Players could explore the tower, encounter enemies, fight, and return to town.

But something felt thin.

The **Collect** step had almost nothing meaningful in it.
No real loot.
Just gold with nowhere interesting to spend it.

The **Improve** step had the same problem.
Basic level-up foundation.
A skills system that was more skeleton than substance.
A town that felt completely static.
A world that felt empty.

The loop was technically running.

But it wasn't pulling players forward.

In software terms: the critical path was functional, but the system had no meaningful state changes.
Nothing the player did felt like it mattered yet.

That gap became the clearest signal from the prototype:

**The skeleton was right. The depth wasn't there yet.**

---

### The Surprise I Didn't See Coming

The gameplay gaps I expected.

Prototypes are supposed to be incomplete.

What I didn't expect was the art problem.

I went in assuming I could generate consistent pixel art assets using AI tools.

That turned out to be wrong.

Keeping a coherent visual style across AI-generated assets was harder than I anticipated.
The tooling was also a challenge I hadn't fully accounted for.

In the end I made a pragmatic decision:

**Placeholders first.**

Ship the mechanics. Worry about visual identity later.

It was the right call — but it also meant the art challenge was now a debt I was carrying forward.

---

### What the Prototype Was Actually For

A prototype isn't supposed to tell you that everything works.

It's supposed to tell you **what doesn't** — before you've invested too much in the wrong direction.

After two months, I knew the core loop held up structurally.
Collect and Improve needed significantly more depth.
And the art was going to be a harder problem than planned.

But the most important signal was subtler:

The scope constraint I had set in Part 2 was already being tested.

Not broken — but tested.

The prototype didn't validate the game.

It validated the **direction** — and showed me exactly where the real work was waiting.

In the next part, I'll talk about how I started addressing the depth problem:
building out the systems that make Collect and Improve actually feel meaningful.

—  
**Engineering an Indie Game** is a series documenting my journey building *Adventure Dreams*.

Part engineering journal, part devlog, part learning process.

Full archive: [GitHub](https://github.com/gugalp/engineering-an-indie-game)