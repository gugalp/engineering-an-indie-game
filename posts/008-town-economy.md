---
title: "The Town Economy: Making the Hub Feel Alive"
series: Engineering an Indie Game
part: 8
date: 2026-05-25
tags: [gamedev, solo-dev, devlog, unity, economy]
---

# Part 8 — Engineering an Indie Game
## The Town Economy: Making the Hub Feel Alive

The loop sends you into the tower.

But the town is where the loop closes.

---

Post 7 covered the loot system — how items drop, how rarity works, how the data-driven structure keeps it maintainable.

That system answers one question: what do you find in the tower?

Post 8 answers the next one: what do you do with it?

---

The town in Adventure Dreams isn't a menu screen with a backdrop.

It's a physical space you navigate between runs.

Buildings are visible. Upgradeable. And when you upgrade them, they look different.

That detail matters more than it sounds.

Visual feedback on progression makes the town feel like it's responding to what you've done.
You can look at the town and read your own progress.
That's a different feeling than a number going up in a stat screen.

---

The town has eight buildings, each with its own services and upgrade path:

- **Equipment Shop**: buy and sell weapons, armor, and consumables; higher levels unlock better stock and class-specific items
- **Smithy**: craft blueprints, add enchantments, and unlock masterwork upgrades
- **Training Grounds**: permanent HP/MP increases and class-specific ability unlocks
- **Inn**: rest, and stash access; higher levels expand storage and rest bonuses
- **Library**: bestiary and tower maps; higher levels reveal enemy weaknesses and hidden areas
- **Guild Hall**: quests and reputation rewards; higher levels unlock bounties and epic quest chains
- **Player House**: personal storage and display; higher levels expand stash capacity
- **Town Hall**: unlocked at mid-game; manages building synergies for powerful combination bonuses

None of these are decorative.

Building upgrades gate most of the depth.
Higher-tier shop stock. Crafting access. Quest tiers.
The town starts limited — and expands as you invest in it.

That's intentional. Early runs should feel constrained.
The town growing is part of the progression arc.

---

Two things drive the economy: gold and tower materials.

Gold comes from combat — enemies drop it, and it's the primary currency for purchases and upgrades.

Tower materials are what you bring back from runs.
There are nine distinct types across three rarity tiers — Timber, Stone, and Iron are common; Steel, Crystal, and Herbs are uncommon; Mythril, Ethereal Essence, and Ancient Tomes are rare.
Each material is linked to specific tower environments, so which tower you're farming shapes what you can build.

Spending decisions require both.

That separation is a design choice, not an accident.
Single-currency economies tend to collapse into one optimal strategy.
Gold and materials create tradeoffs.
Do you upgrade the shop now, or save materials for the Smithy?
Do you spend Mythril on a building, or hold it for a crafting recipe?

Those are the decisions that make a hub feel like a place worth returning to.

---

The honest state: the system is fully implemented.

Not fully tested.

Balancing is still ahead — drop rates, resource costs, upgrade pricing.
Some building functions may need to be revisited once playtesting surfaces the friction points.

The structure is sound.
The tuning isn't done.

That's a normal place to be at this stage.
You build the system first. You tune it against real play.

---

The town exists now.
It responds to progress.
It creates decisions.

Making those decisions feel genuinely interesting — that's the next layer of work.

In the next part: the skill tree.
How do you design progression that rewards exploration without making early floors feel pointless?

—
Part 8 — Engineering an Indie Game
The Town Economy: Making the Hub Feel Alive

Full archive: https://github.com/gugalp/engineering-an-indie-game
#gamedev #indiedev #solodev #softwareengineering #buildinpublic
