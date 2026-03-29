---
title: Designing the Core Gameplay Loop of Adventure Dreams
series: Engineering an Indie Game
part: 3
date: 2026-03-15
tags: [gamedev, solo-dev, devlog]
---

# Engineering an Indie Game — Part 3

## Designing the Core Gameplay Loop of Adventure Dreams

At that point, I had a problem.
I didn’t actually know what the game was.
And that’s a bigger problem than it sounds.

What exactly will players do in this game?

Not the story.
Not the world.

The moment-to-moment activity.

In software architecture, this is similar to identifying a system's primary execution path.

In games, it's called the core gameplay loop.

The core loop is the cycle of actions players repeat again and again.
It’s the rhythm of the game.

If the loop is satisfying, players keep playing.
If it's not, no amount of content will fix the game.

Some examples:

- Explore → Fight → Loot → Upgrade
- Build → Defend → Expand
- Farm → Craft → Improve

After a few iterations (and a few bad ideas), I landed on a first version.
For Adventure Dreams, the first version of the loop became:

Explore → Fight → Collect → Improve

Explore

- Navigate the tower
- Discover enemies, secrets, and resources

Fight

- Turn-based combat encounters

Collect

- Loot, items, and crafting materials
- Conquer sections of the tower

Improve

- Upgrade equipment and abilities
- Improve the hometown

Visually, the gameplay loop looks like this:

![Initial Core Gameloop Diagram](/assets/InitialCoreGameLoop.png "Initial Core Gameloop Diagram")

The goal sounds simple:

Every step should make the next step more interesting.

As a software engineer, this reminded me of designing high-throughput systems.

You identify the critical path.
Then optimize it.
Remove friction.
Make sure the system can scale.

In games, the core loop is the critical path of the player experience.

Defining the loop isn't the hard part.

It's making every step meaningful and satisfying.

Exploration must feel rewarding.
Combat must feel responsive.
Progression must feel meaningful.

With the core loop defined, the next step was obvious.

I needed to prototype it quickly and see if it was actually fun.

That meant building the first playable prototype.

In the next post, I'll share how I approached building it.

Curious how others approach this:
Do you define the “core loop” first — or discover it while building?

—  
**Engineering an Indie Game** is a series documenting my journey building *Adventure Dreams*.

Part engineering journal, part devlog, part learning process.

Full archive: [GitHub](https://github.com/gugalp/engineering-an-indie-game)