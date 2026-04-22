---
title: The Loot System: Making Items Feel Meaningful
series: Engineering an Indie Game
part: 7
date: 2026-04-22
tags: [gamedev, solo-dev, devlog, unity, loot]
---

# Part 7 — Engineering an Indie Game
## The Loot System: Making Items Feel Meaningful

The prototype told me the loop worked.

It also told me something else.

Finding an item didn't feel like anything.

---

That's a specific kind of failure.

It's not that the system was broken.
Items dropped. Players picked them up. Stats went up.

But there was no moment.

No "wait — what is this?"
No decision to make.
No story to tell after the run.

That's what a bad loot system produces.
Not broken mechanics — missing feeling.

The enemy isn't bugs. It's predictability.

When everything feels expected, nothing feels earned.

---

Fixing that starts with rarity.

Not rarity as a number — rarity as a signal.

Common items should feel common.
Rare items should feel like the floor just gave you something it didn't have to.

That gap in feeling is what makes a player stop, look at an item, and actually think about it.

Adventure Dreams is built around a procedural tower.
Floors are different every run.
Enemies are different.

The loot had to match that energy.

If the items are predictable, the procedural layer stops mattering.
Players stop exploring because they already know what exploration pays.

---

The system itself is more than a skeleton.

Six rarity tiers. Forty-five creature-specific drop tables.
Drops that scale with floor depth, double for elites, quadruple for bosses.
Equipment only spawns on humanoid enemies — and scales in material tier as you go deeper.

That last decision matters more than it looks.
Creature type becomes a loot signal.
Players learn to read the room differently depending on what's in it.

That's not the part that's missing.

What's missing is the top end.

A Common sword and a Legendary sword both give you numbers right now.
But a Legendary sword should give you a choice you didn't have before.
A strategy that wasn't possible.

Six rarity tiers exist.
The design work ahead is making sure Legendary and Artifact items have behaviors — not just better stats.

---

Every item in Adventure Dreams is defined as a ScriptableObject in Unity.

For engineers outside the Unity world: think of it as a data container you can configure in the editor without touching code.

Each item is a config entry — not hardcoded logic.

That decision has a consequence that matters:
adding a new item requires no new code.

Open the editor. Define the values. Save. Done.

That's the right foundation for a system where the design work is still ahead.

It means iteration is cheap.
Testing a new idea costs minutes, not a refactor.
Tuning drop rates, adjusting stat ranges, rebalancing rarity thresholds — all config changes, not code changes.

When you're a solo developer, that's not a nice-to-have.
It's what keeps item design from becoming a blocker.

---

The loot system is ready.

Now it needs to be filled with things worth finding.

In the next part, I'll go deeper on where loot actually goes — the town economy, how items flow into shops and building upgrades, and what crafting might look like as the system matures.

Does rarity alone create the feeling — or does it need something else?

—
Part 7 — Engineering an Indie Game
The Loot System: Making Items Feel Meaningful

Full archive: https://github.com/gugalp/engineering-an-indie-game
#gamedev #indiedev #solodev #softwareengineering #buildinpublic