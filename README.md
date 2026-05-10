# Ibis Belly Turret Cargo Hook Patch

A Nuclear Option BepInEx plugin for the UH-90 Ibis, intended to work alongside the QoL mod.

QoL changes the Ibis cargo hook equipment slot into a forward-shifted ventral/belly turret slot. This patch keeps QoL's Ventral Mount for belly turret weapons, removes CargoHook from that slot, and adds a separate cargo-hook-only slot near the original cargo hook position.

## Requirements

- Nuclear Option
- BepInEx 5
- QoL mod

## What it does

- Keeps QoL's Ventral Mount / belly turret options.
- Removes CargoHook from the Ventral Mount slot.
- Adds a separate Cargo Hook slot.
- Cargo Hook slot only offers CargoHook.
- Places the cargo hook closer to the original UH-90 Ibis cargo hook position.

## Install

Install with NOMM once listed there, or manually place:

`IbisBellyTurretCargoHookPatch.dll`

in:

`Nuclear Option/BepInEx/plugins/IbisBellyTurretCargoHookPatch/`

## Notes

This mod is designed to be used with QoL. It does not try to support the non-QoL UH-90 loadout.
