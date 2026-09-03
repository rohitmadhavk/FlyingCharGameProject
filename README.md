# FlyingCharGame (Unreal Engine 5)

A small solo gameplay programming prototype built in a day, exploring flight and missile-combat mechanics for a robot/mech-style character. The focus was on core combat systems.

**[▶ Watch the 30s gameplay reel](https://youtu.be/GjAnMx7kW2U)**

## What's in the demo

- **Flight movement** - free-flight traversal system for the player character
- **Homing missile system** - shared core targeting/projectile logic used by both the player and enemy AI, tuned asymmetrically: player missiles home with higher precision, while enemy missiles are intentionally more dodgeable to keep the encounter fair and readable
- **Target lock-on** - player-controlled target acquisition for firing missiles
- **Enemy AI** - a jet that fires homing missiles at the player, which the player must dodge
- **Combat loop** - dodge an incoming enemy missile, then counter-fire with a homing missile of your own to destroy the jet
- **Gameplay Ability System (GAS)** - attribute sets (health/damage) drive combat resolution, with explosion VFX triggered on hit

## Scope notes

This was built in about two days as a proof of concept, so the map is small and the enemy jet's speed/behavior is intentionally simple as the goal was to get the targeting, homing, and GAS-driven combat loop working end-to-end, not to build out a full level or tune difficulty.

## Tech

- Unreal Engine 5
- Gameplay Ability System (GAS) for attributes and combat resolution

## Credits

- Character/animation assets retargeted from Epic Games' **Paragon** asset packs (free via Unreal Marketplace / Fab), used under Epic's content license terms.
- All gameplay systems, blueprints, and combat logic implemented by me.

## About

Built by Rohit Madhav Krishnan as a Computer Science Student exploring combat systems in UE5. Feel free to reach out at [here](https://www.linkedin.com/in/rohit-madhav-krishnan-465520291/).

---
