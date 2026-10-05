# FF8 gameplay mods for Junction VIII

Three gameplay mods for **Final Fantasy VIII**, the original PC version (not Remastered),
packaged for the [Junction VIII](https://github.com/tsunamods-codes/Junction-VIII) mod manager.

**Requires the Steam 2013 English release** (`FF8_EN.exe`). Other languages, the 2000 CD
release and the Remastered edition use different code and are not supported. Junction VIII's
automatic 4GB patch is fine.

| Mod | What it does |
|---|---|
| **Triple Triad Rule Select** | Pick each card rule (Open, Same, Plus, Random, Sudden Death, Same Wall, Elemental) as region default, always on or always off, plus the trade rule. Applies to every match. |
| **Unlimited GF Abilities** | Removes the 22-ability limit per GF. Teach any number of abilities with items; every GF ability list gets as many pages as it needs. |
| **All Magic Per Character** | Each character holds every spell at once (64 slots instead of 32), up to 100 each. All magic screens page through the full list. |

All three can be active together.

## Install

In Junction VIII, find the mods under **Browse Catalog**, or download the zips from
[Releases](../../releases) and use **Import Mod**. Open a mod's **Configure** screen to pick
its settings (Triple Triad Rule Select), then press **Play**.

## Notes

- **All Magic Per Character** keeps the extra magic inside your normal save. Older saves load
  fine and their magic is converted. A save made with this mod needs the mod active to load
  its magic correctly, and save editors won't understand the extra magic. Magic is listed in
  spell order after a save and reload.
- **Unlimited GF Abilities** keeps the vanilla save format. If you turn it off, a GF with more
  than 22 abilities keeps them all, but the vanilla menus only list the first 22.
- If something misbehaves, launch with **Play With Debug Log** and open an issue with
  `log.txt` from the game folder.
