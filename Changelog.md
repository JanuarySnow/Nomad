## **v0.90**
Near total rebuild.

Gone are many many awkward and problem prone mods, simplified and streamlined.

Removed BLD and Agony and Survival First Aid etc

Replaced with a complementary set of mods that are designed for each other - Maim, Scourge, True Damage.

Added bullet penetration framework, and weapon jam framework, patched for all gun mods with synthesis automation.

Added a few quest mods for a testing phase

Added a bunch of weapon casing/sound/impact mods for more dynamic gunplay.

Added performout fancy textures as a base replacer for all Betheseda textures, before more specific texture mods overwrite certain ones.

Added A Forest and grass mods for a more realistic overgrown post-apocalyptic world.

Changed pipe weapon retexture mod to one thats less rusty

Added True Grass

Fixed Blood Textures on corpses

Removed VATS

Added Scaling weapon damage based on perception - now that VATS is gone, perception needs more of a use.

Added ammo switching with ECO quick menu to Crossbow, LString bow, and RPG.

Added critical hits outside of vats but reduced their frequency.

Added locky bastard mod for more lockpicking options

Added more carry weight bonuses in power armor

But no sneaking in power armor

HEavy weapons require strength to use effectively

Remove combat boundaries so enemies can follow more often through loading doors

Added better strenght bonuses to bashing with guns

Added more feral ghouls and feral ghouls expansion pack

Added a bunch of base object swapper mods for more variety in the world

Added playable guitars

Fixed more handless and naked gunner armor spawns, there will probably be more though, that mod is a pain in my ass

Added flashbang mod

Speeded up character creation by removing initial voice-over

Added mutant menagerie


## **v0.71**

Added wheelmenu

Fixed version number in Mo2

## **v0.70**

Added Boat to Spectacle Island mod
Added Junkier Junk mod - so misc static junk can be picked up and scrapped

Fixed ECO workbench AGAIN as my previous fix unfixed it.

## **v0.60**

Fixed Gunner Combat Outfit(Grunt) had no hands

Fixed Makeshift SMG OMOD description referring to old calibers

Reduced stats slightly on Makeshift SMG as it was too good ( its meant to be makeshift! )

Increased stats on XM2076 sniper slightly to match its rarity and cost

Increased stats on DKS-501 sniper slightly ( as above )

Reduced protection and raised weight of Scavenged NCR Armor as it was pretty much better than anything else

FIxed Stetchkin APS going to a fire rate of 0 when converted back to semi-auto

Increased ammo availability from Vendors at mid-range levels and higher

Increased damage of FN FAL slightly as it was weaker than comparable combat rifles

Reduced Stetchkin APS damage when converted to 10mm, as it was much higher than comparable pistols

Added Binoculars and Tactical optics to levelled lists as they were pretty much impossible to find

Removed Preston as script properties in quests trying to reference him

Removed most of the "Last man standing" mod; the only thing really left of it is the name and a few edits - as the only feature I used from it was the quest changes to remove the minutemen, and I reimplemented that in a better way ( see below )

Previously quests like Mionrecruit02 ( Abernathy farm ) werent able to start, even by talking directly to Blake, because of the way I removed Workshops, a few quests actually required the workshops to be present.
So what I did was enable the workbenches, but move them far underground so player cant use them, but quests can.

Id rather not fix it this way as it seems that some more bugs could creep through, but the only other alternative was to just not have these quests available at all, which wasnt acceptable for me.

Fixed a lot of dangling properties and such causing mostly harmless spam in papyrus log

Removed Nicotine addiction from cigs, its just annoying when smoking cigs is the primary saving method now

Disabled papyrus logging in release build

Disabled BLD popping up its messages on every game load

ACtually for real removed Junk Category from ECO workbench

Made SLeepness nights too safe a few patches ago, bumped up its chances a bit now. Might tweak to find the middle ground later

Goodneighbor neighborhood watch outfits , clipped more than usual with the torso armor part of their leveled lists, so removed that part.

Fixed M1 Carbine automatic conversion actually reducing rate of fire

Reduced price of antibiotics slightly

## **v0.52**

Changed all projectile gravity settings as they were dropping hugely, the author of caliber complex I think associated gravity with projectile weight, with values as high as 6.0 for 50 bmg but 1.0 for .22 LR , which didnt always give correct drop off behavior considering projectile velocity.

10mm at average engagement range of approx 20m needed to aim 2 inches (screenspace measurements) above targets head - obviously too much

Have edited all of the gravity values individually on a caliber by caliber basis, and tested the results ingame. 308 is relatively flat for example, and handgun calibers drop off more, but less than they did.

Fixed projectiles from suppressed guns always pointing their flash graphic North

Reduced length of new game start popup message to make text not so small

updated and expanded Readme

## **v0.51**

Removed ECO Junk crafting option as it was empty anyway
Fixed Lstring bow MCM hotkey for arrow switching
Restored Lstring bow arrow switcher item COBJ

## **v0.50**

Removed ECO options for directly modifying legendary slots and damage/zoom levels of every weapon

Added compass back to HUD but without enemy markers etc

removed ihud compass/toggle aid items

Removed mental health mod, it was simplistic and ended up having zero gameplay interactions in every playthrough I did, I want to bring it back at some point but only when its a full concept that really impacts gameplay

Fixed a couple of OMOD naming issues

## **v0.40**

Removed ECO OMOD stripper mod as it was un-needed and had problems in this setup

removed redundant SKK OMOD stripper as it was workshop only

Removed other workshop/settlement mods as they were redundant

Some consistency patching for various armor pieces

Slightly reduced armor encumbrance penalty

Amended stash bag script to not stash caps and lockpicks by default

Added Journal of the sole survivor mod, and edited it to be added to inventory on game start

Replaced useless Local Leader perk with one that improves charisma while only wearing non-combat, non-armor clothing

Made vanilla projectiles more inline with WOF-style BLD-style Caliber-complex projectiles, even when most vanilla stuff is converted to calcomplex, certain OMODs will revert to vanilla projectiles.

Edited startup text to be non gender-specific with the mention of killed "wife"

Edited consitency and naming with various guns

Removed HK GSG3 as it had unexplainable range issues I couldnt fix.

Fixed HK23 INNR naming conventions

## **v0.30**

Removed G43 rifle damage mods

Removed Makarov Pistol, it had issues

Reduced PMC Operator armor stats

Updated ENB binaries

Fixed a bunch of unused data and other minor errors that xedit reported on a load of mods

Removed ACO and swapped in ECO

Added Startup information box to describe first steps and changes

Removed most of survivalist first aid except for Splints

Added Sleep on Couches

Added ECO crafting bench to start game items

Custom Fast Travel Beacons

Removed Journey mod

Removed all misc junk and unbalanced vanilla armor recipes from ECO COBJ lists

Use BLD Bleeding mechanics instead

Use DamnApo/BLD/Agony multi-patch to integrate

Removed all workshops, and all workbenches, and all settlement building (except for vault 88, mechanists lair , boston airport )

Pulowski Bomb shelters protect from rad storms

Rebalance VATS slowdown to be a bit easier

Alcohol reduces pain

Added ECO OMOD stripper

Buff Crossbow slightly

Removed Hunting Kit COBJ ( as using Hunter of the commonwealth instead )

Removed Weapons of Fate as Caliber COmplex had same features anyway

Added BLD bleeding notification script

Custom placeable storage duffel bag

Reduced chances of sleepness nights encounters

various other consistency and bug patches


## **v0.21**

Added Quicktrade

Fixed up some weirdness in the purified water recipes ( now water purifier outputs 3 at once, and recipes arent duplicated )

Blocked Covenant workshop from becoming under player control after its quest

Fixed crosshairs in immersive hud

Fixed weirdness with bandages and their recipes.

Fixed radio stations not becoming available on new game with SKK Fast start

Fixed some more nude NPCs by removing hooded rags from body leveled lists

Fixed ENB stealth update


## **v0.2**

Fall UI minimal HUD preset added

Immersive HUD now correctly hides all HUD elements when pressing X key

Remove hooded rags from leveled lists that were supposed to be head-free, causing clothes-less NPCs

Removed NEST Bunkers mod - neat idea, too much free stuff.

Exclude companions ( dogmeat etc ) from the bleeding mechanics, which caused them to constantly re-die.

Remove Quaz vehicle overhaul, some missing textures and vehicles in the path of NPCs and dogmeats sniffing quest.

Block activation of the "smoke to save" animation of cigars and cigarettes, whilst in combat.

Fix Sanctuary Bridge doubling

Covert Pistol was showing as unique - fixed.

Even less food now placed in the world

Bandage recipes were duplicated, one with a bobby pin - removed duplicates

Changed bandage recipes to be slightly more expensive in components when crafted at a campfire, compared to chem bench

Reduced gun prices by around 25% across the board

But added a silent perk to player that reduces sell prices by 15% and raises buy prices by 15%

Removed Youre SPECIAL perk overhaul and tag skills mod - I didnt like the level up menu, and it had problems with lockpicking/hacking/pacify while aiming

Removed P90 SMG gun, as it had its animation subgraphdata overwritten anyway, and a patch would be very messy

Workshop scrap time wasnt working correctly, no time was passing when object scrapped, fixed this.

Doctors now remove the Death Penalty mod debuffs as part of their usual health restore services

Changed threshold for low health Monochrome screen space effect, reduced it so it dosnt happen as much

Removed PJAR Pistol mod, it had some weird spawn settings with its legendary variants, and it didnt add much that I didnt already have anyway.

Removed everyones best friend mod, as it was being overwritten anyway from survival mods, and I want Dogmeat to be a choice rather than a default companion + dogmeat.

Fixed Notifications popping up with black bars from overlapping elements.


## **v0.12**

Road Goggles were causing crashes in workbenches - dont know why. Just removed them

Fixed Makeshift Shotgun model

Reduced protection values for PMC operator outfits, they were very high.

Increased Health and Damage Resist and speed of supermutants and deathclaws, they were far too easy in my playthrough

fixed script for pet dogmeat so it forces third person when you activate dogmeat, so the animation can actually start

Ensured that PTSD is not alleviated for every "chem" as it previously was set to, so that bandages etc dont reduce PTSD.

Added Binoculars to levelled lists

Added Coffee to Levelled lists

I had intended to cap health at 80% after dying, but had set 20% in the Death Penalty MCM instead, this was very harsh and could cause death spirals, fixed to 80% now

Not quite happy with survival first aid mod, but will save that for a future version to overhaul it.

Added messagebox after character creation to explain that some things will be very different, so that hopefully players read the readme.
