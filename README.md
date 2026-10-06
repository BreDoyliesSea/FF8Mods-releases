# FF8 Unlimited for Junction VIII

A gameplay mod for **Final Fantasy VIII**, the original PC version (not Remastered),
packaged for the [Junction VIII](https://github.com/tsunamods-codes/Junction-VIII) mod manager.

**Requires the Steam 2013 English release** (`FF8_EN.exe`). Other languages, the 2000 CD
release and the Remastered edition use different code and are not supported. Junction VIII's
automatic 4GB patch is fine.

FF8 Unlimited has three parts, each an option in Junction VIII's **Configure** screen that
can be switched off on its own:

| Part | What it does |
|---|---|
| **Card rules** | Pick each card rule (Open, Same, Plus, Random, Sudden Death, Same Wall, Elemental) as region default, always on or always off, plus the trade rule. Applies to every match. |
| **Unlimited GF Abilities** | Removes the 22-ability limit per GF. Teach any number of abilities with items; every GF ability list gets as many pages as it needs. |
| **All Magic Per Character** | Each character holds every spell at once (64 slots instead of 32), up to 100 each. All magic screens page through the full list. |

Page numbers past 9 show both digits ("P.12").

Version 1.0 released the three parts as separate mods. From 1.1 they are one mod; if you
installed the 1.0 mods, deactivate and remove them before activating FF8 Unlimited.

**Cronos / FF8 Gameplay Customizer:** keep FF8 Unlimited below them in the mod list (Junction
VIII warns if not). With All Magic on, their Junction value rework can't use
JunctionDependOfMinLevelQuantity; Vanilla and JunctionDependOfLevel work.

## Install

In Junction VIII, find **FF8 Unlimited** under **Browse Catalog**, or download the zip from
[Releases](../../releases) and use **Import Mod**. Open **Configure** to pick the options,
then press **Play**.

## Notes

- **All Magic Per Character** keeps the extra magic inside your normal save. Older saves load
  fine and their magic is converted. A save made with this part on needs it on to load
  its magic correctly, and save editors won't understand the extra magic. Magic is listed in
  spell order after a save and reload.
- **Unlimited GF Abilities** keeps the vanilla save format. If you turn it off, a GF with more
  than 22 abilities keeps them all, but the vanilla menus only list the first 22.
- If something misbehaves, launch with **Play With Debug Log** and open an issue with
  `log.txt` from the game folder.
