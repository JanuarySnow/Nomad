![Fallout4 2023-07-23 23-51-03](https://github.com/JanuarySnow/Nomad/assets/85711747/84a3ab0d-ff0e-4c3c-b4be-a6123f9f77f6)# NOMAD

![nomad-banner](Cover/nomad-banner.webp)

<table stlyle="border: none;">
<tr>
<td><img src="https://raw.githubusercontent.com/The-Animonculory/AVO/main/.github/GitHub.png" width="72px" /></td>
<td><a href="https://discord.gg/DffHKcszfg">Support Discord</a></td>
</tr>
</table>

## Contents
- [Nomad](#Nomad)
  - [CONTENTS](#contents)
  - [PREAMBLE](#preamble)
  - [READ THIS BIT FIRST](#read-this-bit-first)
  - [PERFORMANCE](#Performance)
  - [MAJOR FEATURES](#Major-features)
  - [NOT INCLUDED](#Not-included)
  - [INSTALLATION](#INSTALLATION)
  - [GRAPHICS](#Graphics)
  - [QUICKSTART](#QUICKSTART)
  - [GAMEPLAY TIPS](#GAMEPLAY-TIPS)
  - [CONTROLLER SUPPORT](#CONTROLLER-SUPPORT)
  - [CHANGES AND NOTABLE MODS](#CHANGES-AND-NOTABLE-MODS)
  - [CONTROLS](#CONTROLS)
  - [KNOWN ISSUES](#KNOWN-ISSUES)
  - [CREDITS AND THANKS](#CREDITS-AND-THANKS)
  - [SCREENSHOTS](#SCREENSHOTS)

## PREAMBLE ##

**"I think getting shot in the head fucks you really bad but yeah I think its balanced if your not a shitter"** - User Feedback

This is a wabbajack list for Fallout 4 that aims to shape the gameplay into a unique direction, one of solitude and atmosphere, and gritty immersion.

Id say I was inspired by the S.T.A.L.K.E.R games and their associated overhaul mods, also Ultimate Skyrim for Skyrim LE and Serenity for Skyrim SE.
Immersion and realism are kinda dirty words in modding these days, but I still like them.

It builds upon the excellent Welcome to Paradise Fallout 4 list by Phoenix, but uses only the graphics and bugfixes sections of that list, the rest is custom.

## READ THIS BIT FIRST

First and foremost - PLEASE READ THIS IF NOTHING ELSE: I have HEAVILY modified many many mods in this list, so they often look nothing like what they started out as.
For this reason please do NOT go to the original authors on Nexusmods for support if something seems wrong, come to me on the Animonculory Discord linked above in the Nomad channels, or log an issue on this github.

For example - for many of the weapon mods I have added patches to remove the scripted leveled list injections and remade leveled lists by hand, and stopped them from being hand-placed in the world. If you read the original mods description you may be expecting something to appear ingame, that would not in this list.  If you go to the original mod author saying something is wrong you will either make them angry or be laughed at.

This is currently a testing release, I am fixing bugs in my own testing as I encounter them, but having more eyes will allow me to fix bugs far quicker, so please give me your bug reports, my Discord name is JanuarySnow and I can be found in the server linked above, or drop an issue here on github.

## PERFORMANCE:

Using a HDD rather than an SSD will result in a LOT more stuttering, please use an SSD if possible.

Here are some known results on different GPUs and resolutions, tested wandering around the wasteland, not in Inner Boston ( because everyones performance struggles in Boston, no matter the hardware, its just how Fallout 4 is )

1070ti @ 1440p = 60 fps

1070ti @ 1080p = 80 fps

1080ti @ 4k = 65 fps

1080ti @ 1440p = 70 fps

1080ti @ 1080p = 95 fps

2060 @ 1080p = 60fps

3070ti @ 1440p = 90 fps

4090 @ 4k = 120fps ( Id hope so )

Added a few optional mods to improve performance - Upscaler and Shadowboost and Lowspec tree textures and LOD

Enable these mods as per the instructions in MO2, and select which fps target you are aiming for, and it will dynamically adjust shadows and FPS cap to match.

This list requires a total install size of around 190GB ( of which around 90GB is Download size, and around 100GB is install files )

## MAJOR FEATURES

Quick and lethal gunplay, both for you and the enemies.

A death alternative - respawning instead of save scumming.

Expanded calibers with fully simulated projectiles with drop-off and bullet penetration of cover depending on the caliber and material of the cover.

Over 170 new guns and weapons, patched and cleaned and distributed manually to leveled lists.

Over 550 new pieces of armor and clothing, patched, cleaned and distributed manually to leveled lists and worn by NPCs/enemies.

Expanded survival system with wounds and bleeding, a harsher world, more radiation, less healing from sleeping and eating.

Enemies can approach you as you sleep.

Hunting and Fishing.

Added realism to crafting - it now makes time pass.

Armor Encumbrance System

Portable placeable storage bag.

Gun jamming / quality system.

And much more.

## NOT INCLUDED

NSFW stuff

Additional quests ( going to remove all the ones I was testing in v0.95 ), why? because it seems every single quest mod breaks something
The burden to test them all when you add a bunch at once is insurmountable, so ill add one at a time as things progress, to make it easier to test each one thoroughly.

## INSTALLATION
Have Fallout 4 on steam, a clean copy, no mods installed, with all DLC except the HD DLC ( see below )

Ensure that the HD DLC is not activated in the Steam "Manage DLC" page

A Nexusmods account will be required, preferably premium to make this go much faster.


Get [Wabbajack](https://www.wabbajack.org/).

Mod Organizer 2 requires the latest Microsoft Visual C++ Redistributable, and .net

Install both the console and desktop x64 apps from [Here](https://dotnet.microsoft.com/en-us/download/dotnet/5.0/runtime)

And Visual C++ from [Here](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads)

Either download the release nomad.wabbajack file from the github releases page and open it with Wabbajack, or - if and when this list becomes "official" or has an unofficial release, it will then be browsable from the main Wabbajack gallery.

After the download has finished, open ModOrganizer2.exe from the location you chose, and click "Launch Nomad"


## GRAPHICS:


Mostly carried over from Welcome to Paradise list by Phoenix, although I have added a reshade filter, to add a gloomier atmosphere and darker nights, and a sharpening filter to get rid of the TAA blurry smear.
If you arent a fan of this , you can press the HOME button on your keyboard to bring up the reshade menu and disable the filters.

To change the resolution edit `isizeh` and `isizew` in fallout4prefs.ini from the Mod Organizer 2 ini editor ![alt text](https://cdn.discordapp.com/attachments/623261438022254612/866498313606922260/unknown.png)

If you have Ultrawide - enable the ultrawide mod in the Optional section of Mo2 left pane ( note - I dont have ultrawide so im hoping someone will let me know how this works with the list )

What works best for me with a gsync monitor, is disabling vsync and adding an FPS cap of 60

If you want to change this, then the best place is in highfpsphysicsfix.ini in MO2 right pane -> data -> skse -> plugins ( edit this to enable or disable vsync, screen tearing, and fps cap - use this INSTEAD of ENB cap/vsync and ipresentinterval in fallout4.ini )

## QUICKSTART:


After starting the game, you will go straight from the Bathroom scene where you create your character , and then pick your stats, then teleport to the vault exit sequence.

After this the game will save, then quit, automatically - around 10 seconds after the vault exit, this is essential to avoid bugs that appear to be at an engine-level in the game ( specifically damage amounts applied to ammo records dont function until a game has been saved and loaded - and a few other things )

**After this, open the mod config menu, select the very first entry there on the top which is "MCM settings manager" and then click apply on the preset that is displayed there.**

Thats it, your done.

## GAMEPLAY TIPS

ENSURE YOU DID THE ABOVE - SELECT MCM SETTINGS MANAGER AND APPLY THE PRESET.

You will die easily. Saving happens at campfires, sleeping in beds, and smoking cigars or ciggarettes - Make use of these before battles.

Again, you will die easily, the best tactic is not get shot at all, getting shot sucks, be sneaky, use grenades and traps and ambush tactics.

Laser/plasma weapons have higher armor pentration.

light armor(leather) will only give you brief protection against pistol calibers, heavy armor(combat armor) will give you protection against a few rifle caliber hits.
So you see - it aint much either way, but power armor is an absolute tank for you and enemies.

Return to camp often to save and heal and rest.
You will not heal from food and water at all, you will heal a bit from sleeping.
You will not heal much from stimpaks, bandages and rest are what you need.

After you die you will respawn at last bed you slept in, with 80% cap on your health, with stat penalties, Kill some enemies to recover from these penalties, this simualtes you crawling back to base and recovering over time.

If you die in a location that cannot be re-entered ( Nuka World Gauntlet etc ) then just use the Death Penalty MCM to return to place of last death ( perhaps after preparing to not instantly die again )

Armor pieces can protect somewhat against bleeding to various locations, the more coverage, the better.

Crippled limbs can be healed with splints or (better) First aid kits.

There is no settlement building at all, except for at Vault 88 or Mechanists Lair. Player housing is currently a work in progress ( I need to find a good replacement for settlement building in home plate for example )

There are no Minutemen anymore, no Preston. I found that questline to be more focused on settlement building and (as above) that wasnt the focus of this list, its a distraction and it feels out of character for main story, it just felt a bit silly and lessened the feeling of survival in the wasteland.

You will not get the good pistols appearing in loot until level 10+, and rifles level 20+

good pre-war guns sell for a lot and cost a lot, but are rarer to drop - they are the guns that (generally) are of a much higher quality and jam far less.

You start the game with a mobile workbench in a metal box near the exit to the vault, this simulates all of the vanilla workbenches plus some more in a menu, drop the ECO workbench or hotkey its related tool to access it, use this to craft anything.

Use the ECO quick menu (G key by default ) to switch ammo types for Crossbow/Bow/RPG

Craft camping gear early on, craft bedroll so you can rest in safe locations ( not all locations are completely safe to rest in, be warned! - interiors are slightly safer than exteriors, and NPC owned settlements are even safer. And your luck attribute contributes to this safety calculation )

You cannot camp in the grounds of a faction/NPC settlement, until you are allied to them.

Craft bandages, youll need them, craft splints, have stashes of food and water and medicaal supplies at your most recent basecamp, if you respawn there.

Craft custom fast travel beacons from the Utility section of the ECO bench, you can place up to 5 of these at a time, and travel between them for a cost.

Radiation is now far more prevalent in hot pockets dotted around the landscape, and is far more damaging, and amplified in food and water.
Choosing equipment with radiation protection over physical protection is now a very real choice.
In vanilla F4 radiation was hardly ever a concern, now it is.

Craft a placeable storage bag from the Utility section of the ECO bench so you can stash your loot at your basecamps.

Hunt animals to get their meat and skin. - Ensure you have a knife or other sharp melee weapon to butcher them.

When you are in pain, use painkillers or strong booze to reduce it.

You can also use a fishing rod to fish in rivers.

Dogmeat can be equipped with backpacks to increase his carrying capacity, so can you.

Crossbows and Bows are a good fallback option to craft as their ammo wont be as scarce as others - use with stealth for maximum effect.

Crafting objects will now take time, based on the number of their components. 

Crafting does not give any XP

Armor now has encumbrance values based on its weight, which slows down the player speed and reduces action points, making lighter armor a more viable option later into the game.

More purified water recipes, craft empty bottles, get bottles back from drinking. More adhesive recipes.

## CONTROLLER SUPPORT

I dont use a controller for Fallout 4, but it is on my TODO list to try and fully support it at some point. 

Ive been told there are minor issues in the UI with a controller, but it is not a major priority for me to support as of right now.

## CHANGES AND NOTABLE MODS

True Damage

Scourge

Maim

Damn Apocalypse

Perception increases ranged damage

NO VATS

Luck helps avoid weapon jams

JSRS and MGWS weapon sounds

Simple impact weapon effects

Weapon Penetration Framework applied to all relevant projectiles

Minutemans Last Stand

Crafting Takes Time

Campsite

Hunter of the Commonwealth

Equipment and Crafting Overhaul (modified)

Caliber Complex

Armor Encumbrance

Lock bashing and blowing up

Many new ammo calibers that are also craftable, with the features from Weapons of Fate integrated

Most of the armor is craftable however, but gated behind later perks.

Power Armor Redux for tanky enemies and player

West-tek tactical optics

No Power armor or minigun in Concord, because life isnt fair.

No already-built crafting benches or power armor crafting bench in Sanctuary or Red Rocket, because life isnt fair.

Weapons are uniformly more expensive to purchase, especially prewar ones!

Nuka world ending now has no option to expand raider settlements into the commonwealth, dosnt fit the theme of this list, as most settlement stuff is completely slimmed down or removed

## CONTROLS

custom hotkeys are defined in the MCM for "Hotkey Manager"

`G` key opens ECOs quick weapon mod menu ( useful for attaching or stripping weapon mods on the fly / changing ammo on supported weapons etc )

`,` Butchers a creature in the crosshair

`.` Examines the current weapon to see if it is suitable for butchery

`x` to toggle HUD

`Mouse4` to throw grenade

`Mouse5` to bash with weapon

`;` toggle Night Vision if using West tek tactical optic

`#` toggle thermal vision if using west tek tactical optic

`middle mouse(m3)` Opens quick wheel menu

## KNOWN ISSUES

I really like the synthesis random facepart patcher that remixes the appearance of all NPCs automatically, but it does mean some hairstyles might clip with some hats, im trying to think of an automated solution, I like automation.

Some slight floor shimmering in Home Plate

Trees clipping through Nuka-World entrance train ride cinematic.

Crafting bench categories are a bit of a mess; At first I did all the COBJs by hand, then I added ECO and ECO integrated which adds their own huge-ass list of recipes, so now they sit alongside my own in their own categories, some appear in both chemistry bench standalone, and ECO bench, some only in the ECO bench.
At some point I will neaten this all up with a synthesis patcher or something to keep things standardised, and dynamically adjust to any mods I add/remove.


## CREDITS AND THANKS

- Xanza for knowledge
- Lively for knowledge
- Luca for knowledge
- Fornication for extensive bug-testing
- Halgari for this playground we play in
- Althro and the animonc...animcnolur... animonculory? for giving me a home
- Baka for the framework that helped me get through some roadblocks
- Everyone else in the wabbajack team who make it a repository of knowledge, and also interesting times.
- the creator of ReShade with its generous [License](Reshade/RESHADELICENSE.md) that allows me to include it.
- The author of this mod for New Vegas, where I used the dry fire sounds, https://www.nexusmods.com/newvegas/mods/68941
- Cover artwork from Bethesedas pre-production concept art, used with assumed permission as per Nexusmods policy on Betheseda assets used to mod Betheseda games.


## SCREENSHOTS

<img src="Screenshots/Fallout4 2023-07-23 23-51-03.png" alt="Alt text" title="Optional title">
<img src="Screenshots/Fallout4 2023-07-23 23-51-50.png" alt="Alt text" title="Optional title">
<img src="Screenshots/Fallout4 2023-07-23 23-51-59.png" alt="Alt text" title="Optional title">
<img src="Screenshots/Fallout4 2023-07-23 23-52-29.png" alt="Alt text" title="Optional title">
<img src="Screenshots/Fallout4 2023-07-23 23-52-33.png" alt="Alt text" title="Optional title">
<img src="Screenshots/Fallout4 2023-07-23 23-53-46.png" alt="Alt text" title="Optional title">
<img src="Screenshots/Fallout4 2023-07-23 23-54-18.png" alt="Alt text" title="Optional title">


