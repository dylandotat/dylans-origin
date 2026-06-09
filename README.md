# Peregrine Falcon

A standalone Minecraft Origins datapack based on the Pixie origin from [Origins++](https://github.com/QuantumXenon/origins-plus-plus).

## Changes from Pixie

- Magical Boost cooldown changed from 500 ticks / 25 seconds to 40 ticks / 2 seconds.
- Display name changed to **Peregrine Falcon**.
- Namespaced as `dylans_origin:dylans_origin` so it can be installed alongside Origins++.
- Removed the Pixie vegetarian-only food drawback.
- Added Birb's armor restriction, shoulder-riding ability, and 2x damage while fall-flying.

## Included Pixie traits

- Elytra flight
- Fall immunity
- Bite Sized: four times smaller, five fewer hearts, slightly lower movement speed, slightly higher attack speed
- Pixies Blessing: glowing aura and hidden luck effect
- Magical Boost
- No fireworks
- Pixie dust particles
- Hidden Speed II effect
- Extreme Need for Mobility: restricted armor choices
- Shoulder Rider: ride on other players
- Aerial Advantage: 2x damage while fall-flying

## Server display text

Inline `name` and `description` fields are included in the origin and power JSON files so the Origins UI displays text correctly on servers even when clients do not have a separate resource pack installed.

## Requirements

- Minecraft/loader setup compatible with Origins++ data format (`pack_format: 12`)
- Origins / Apoli
- Pehkui for player scaling (`scale` commands)

## Install

Place this repository folder, or a zip of its contents, into your world's `datapacks/` folder, then run `/reload`.

## Attribution

Derived from the Pixie origin in QuantumXenon's Origins++ repository. Origins++ `LICENSE.md` states: "All origins belong to their original authors, who retain the rights to their work."
