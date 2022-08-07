Instructions:

0: Skip to step 4 if already setup.
1: Extract ModEngine2 to any location https://github.com/soulsmods/ModEngine2/releases
2: Extract mod folder(s) to ModEngine folder.
3: Check config_eldenring.toml has the folder path for each mod and that mod_onion_ring_randomizer is above mod_onion_ring if used.
4: Run game via launchmod_eldenring.bat in ModEngine2 folder.


Seamless Co-op Compatibility Instructions: 
Compatibility article:	https://www.nexusmods.com/eldenring/articles/94
Seamless co-op mod:		https://github.com/LukeYui/EldenRingSeamlessCoopRelease/releases
1: Setup seamless co-op mod, run it and create a character at least once to ensure a .co2 save file exists. Saves can be checked in "C:\Users\Username\AppData\Roaming\EldenRing"
2: Download Elden Mod Loader https://www.nexusmods.com/eldenring/mods/117
3: Extract the contents of EldenModLoader.zip to your Elden Ring \Game folder, e.g. "C:\SteamLibrary\steamapps\common\ELDEN RING\Game\".
4: Move elden_ring_seamless_coop.dll and seamlesscoopsettings.ini files to mods folder.
5: Run game via launchmod_eldenring.bat in ModEngine2 folder.

Current mods installed:
- Sword Mastery v1.13.2 (NOT FOR ER MODATHON 2022)-1890-1-13-2-1658957588 (reworked combat system)
- unlocked_unique_skills_free-1410-1-003-1655708155 (all skills on all weapons)
- unlocked summons-336-v5-2-1655449788 (summon anywhere)
- firebending-1693-2-0-1656952723 (replaces fist weapon Katar moveset)
- Elden Ring Randomizer-428-v0-4-2-1655244478 ( mix up enemy placements)
- other regulation.bin tweaks



config_eldenring.toml example:
mods = [
	{ enabled = true, name = "onionringrandomizer", path = "mod_onion_ring_randomizer" },
	{ enabled = true, name = "onionring", path = "mod_onion_ring" },
]