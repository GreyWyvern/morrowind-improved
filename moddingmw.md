# MODDING MORROWIND

[Back to main page](https://github.com/Sigourn/morrowind-improved/blob/master/readme.md)

## INDEX

- [Following Modding Morrowind](https://github.com/Sigourn/morrowind-improved/blob/master/moddingmw.md#following-modding-morrowind)
  - [Creating separators in Mod Organizer 2](https://github.com/Sigourn/morrowind-improved/blob/master/moddingmw.md#creating-separators-in-mod-organizer-2)
  - [Installing the modules](https://github.com/Sigourn/morrowind-improved/blob/master/moddingmw.md#installing-the-modules)
- [User interface](https://github.com/Sigourn/morrowind-improved/blob/master/moddingmw.md#user-interface)
- [Content restoration](https://github.com/Sigourn/morrowind-improved/blob/master/moddingmw.md#content-restoration)
- [Internal logic](https://github.com/Sigourn/morrowind-improved/blob/master/moddingmw.md#internal-logic)
- [Visuals](https://github.com/Sigourn/morrowind-improved/blob/master/moddingmw.md#visuals)
    - [Less intrusive magic glow](https://github.com/Sigourn/morrowind-improved/blob/master/moddingmw.md#less-intrusive-magic-glow)
    - [Readable signposts](https://github.com/Sigourn/morrowind-improved/blob/master/moddingmw.md#readable-signposts)
    - [MGE XE mods](https://github.com/Sigourn/morrowind-improved/blob/master/moddingmw.md#mge-xe-mods)
- [Audio](https://github.com/Sigourn/morrowind-improved/blob/master/moddingmw.md#audio)
- [Overhauls](https://github.com/Sigourn/morrowind-improved/blob/master/moddingmw.md#overhauls)
- [Gameplay](https://github.com/Sigourn/morrowind-improved/blob/master/moddingmw.md#gameplay)
  - [Gameplay MWSE](https://github.com/Sigourn/morrowind-improved/blob/master/moddingmw.md#gameplay-mwse)
  - [Gameplay MWSE abot](https://github.com/Sigourn/morrowind-improved/blob/master/moddingmw.md#gameplay-mwse-abot)
- [Game balance](https://github.com/Sigourn/morrowind-improved/blob/master/moddingmw.md#game-balance)
  - [Game balance MWSE](https://github.com/Sigourn/morrowind-improved/blob/master/moddingmw.md#game-balance-mwse)
- [Dialogue](https://github.com/Sigourn/morrowind-improved/blob/master/moddingmw.md#dialogue)
- [Finishing touches](https://github.com/Sigourn/morrowind-improved/blob/master/moddingmw.md#finishing-touches)
    - [Manual conflict resolution](https://github.com/Sigourn/morrowind-improved/blob/master/moddingmw.md#manual-conflict-resolution)
    - [Adjusting your load order](https://github.com/Sigourn/morrowind-improved/blob/master/moddingmw.md#adjusting-your-load-order)
    - [Automated conflict resolution](https://github.com/Sigourn/morrowind-improved/blob/master/moddingmw.md#automated-conflict-resolution)
    - [Synchronizing mod masters](https://github.com/Sigourn/morrowind-improved/blob/master/moddingmw.md#synchronizing-mod-masters)
    - [Running Distant Land](https://github.com/Sigourn/morrowind-improved/blob/master/moddingmw.md#running-distant-land)
    - [In-game configuration](https://github.com/Sigourn/morrowind-improved/blob/master/moddingmw.md#in-game-configuration)

## FOLLOWING MODDING MORROWIND

### BEGINNING WITH MENDING MORROWIND

Modding Morrowind is a follow up guide to [**Mending Morrowind**](https://github.com/Sigourn/morrowind-improved/blob/master/mendingmw.md). Whereas Modding Morrowind is about installing mods that expand on the original game, Mending Morrowind has all the pre-requisites needed to enjoy a stable and mostly bug-free Morrowind experience. Because of this, Modding Morrowind assumes you have already followed through with Mending Morrowind.

### CREATING SEPARATORS IN MOD ORGANIZER 2

Separators allow you to neatly separate installed mods in Mod Organizer 2 for ease of viewing. I recommend creating a separator for the following sections before installing these mods.

- Right click on the empty space on the mod order window, and click **Create Separator**.
- Name it accordingly to its category and click **OK**.

### INSTALLING THE MODULES

As explained in the main page, this guide is modular, and each module can be installed independent from each other. That said, for the sake of simplicity these are the steps you should following when installing any of these modules.

- Install a given module.
- Clean whatever dirty plugins it may have, as per their corresponding **Cleaning plugins** section.
- Jump into the **Finishing touches** section, which will contain the most general information.

Always remember that though these modules are independent from each other, they work with minimum conflicts if you install them in order, and if you install their respective mods in order as well. This doesn't mean you can't install modules and mods out of order, as Mod Organizer 2 lets us rearrange mod and plugin order after installing them. It just means following this guide in order will be your best bet at preserving your sanity.

Good luck!

## USER INTERFACE

These mods expand on the readibility and functionality of Morrowind's user interface. They don't really alter how the game plays but how more useful the user interface is.

[**Better Dialogue Font**](https://www.nexusmods.com/morrowind/mods/36873) by Hrnchamd  
High resolution replacer for the Magic Cards font, used in most of the user interface.  
- Only install the **Better Dialogue Font** main file.

[**Better Daedric Font**](https://www.nexusmods.com/morrowind/mods/44540?) by hardek  
High resolution replacer for the Daedric font used in scrolls.  
- MO2 will tell you there's no game data on top level.
  - Right click on **data**, and click **Create directory...**. Name this new folder **fonts** and click **OK**.
  - Drag **daedric_font.fnt** and **daedric_font_obw.tex** into the **fonts** folder and click **OK**.

[**Better Questlist**](https://www.nexusmods.com/morrowind/mods/48272) by Virnetch  
Allows highlighting and hiding quests in the Journal questlist. Shift-Click on a quest to highlight it, Shift-Click again to hide and Shift-Click a third time to return to normal.

[**Book Worm**](https://www.nexusmods.com/morrowind/mods/46851) by Merlord  
Keep track of what books you have read by showing a "(Read)" indicator next to their names. You can also see a list of previously read books in the MCM menu.

[**Class Description Tooltip**](https://www.nexusmods.com/morrowind/mods/47527) by Merlord  
Restores the class description tooltip to the class selection menu.

[**Continue**](https://www.nexusmods.com/morrowind/mods/45952?) by Petethegoat  
Adds a continue button to the main menu to instantly load your most recent save.

[**Essential Indicators**](https://www.nexusmods.com/morrowind/mods/48267) by Anumaril21  
Provides configurable, dynamic crosshair indicators while sneaking and for essential NPCs, quest items, owned objects, and more. In addition, a variety of settings are included to manage how these aspects of the game work. 

[**Hotkeys Extended**](https://www.nexusmods.com/morrowind/mods/48055) by Virnetch  
Expands the vanilla Quick Menu by adding different hotkeys for holding or double tapping a button and/or when holding a specific button. All hotkeys use the same keys as in vanilla. In total there can now be 81 different hotkeyed items/spells.

[**HUD Weapon Charge**](https://www.nexusmods.com/morrowind/mods/47962) by Virnetch  
Adds a fillbar that shows the currently equipped weapon's charge under the weapon condition bar on the HUD.

[**inom - Inventory mouse wheel**](https://www.nexusmods.com/morrowind/mods/46847) by isNaN  
Allows the use of the mouse wheels to move items into and out of containers.

[**MWSE Alchemy Filter**](https://www.nexusmods.com/morrowind/mods/44808) by Greatness7  
Adds the ability to filter ingredients based on their magic effects.

[**MWSE Clock Block**](https://www.nexusmods.com/morrowind/mods/46292) by Aleist3r  
Adds clock to UI that displays either game world time or real time.

[**New Game Confirmation**](https://www.nexusmods.com/morrowind/mods/47693?) by hardek  
Adds a confirmation popup when you click on New Game in the main menu.

[**Quick Equip**](https://www.nexusmods.com/morrowind/mods/48341) by Merlord  
Holding down a hotkey (default left Shift) while clicking an item in your inventory will equip that item instead of picking it up.

[**Right Click Menu Exit**](https://www.nexusmods.com/morrowind/mods/48458) by Merlord  
Allows exiting any menu by right clicking (or whatever your menu key is mapped to).

[**Shrine Tooltips**](https://www.nexusmods.com/morrowind/mods/48275) by Virnetch  
Adds tooltips with the effect's name to shrines when hovering over the different options.

[**Tooltips Complete**](https://www.nexusmods.com/morrowind/mods/46842) by Anumaril21  
Provides helpful and lore-friendly flavour texts for nearly every item in Morrowind, Tribunal, Bloodmoon, the Official Plugins, and an expanding collection of mods.

[**User Interface Expansion**](https://github.com/NullCascade/morrowind-mods/) by NullCascade  
Development release of UI Expansion that expands on this mod’s features. 
- To download the file from GitHub you need to click on the **Clone or download** button on the upper right and click **Download Zip**.
- MO2 will tell you there's no game data on top level.
  - Expand the **morrowind-mods-master** folder. 
  - Right click **User Interface Expansion** and click **Set data directory**.
  - Rename the mod to **UI Expansion**. Click **OK**.

[**Title Screen and Logo Video Intro Reworked**](https://www.nexusmods.com/morrowind/mods/43657) by Phobos  
HD recreation of the Title and Logo Intro, in widescreen.
- Install both main files.

[**Widescreen Splash Replacer**](https://www.nexusmods.com/morrowind/mods/47163) by NZdawghaus  
Replaces the default splash screens with better quality widescreen versions (16:9), and adds three missing Bethesda splash screens.

[**Widescreen Splash Additions**](https://www.nexusmods.com/morrowind/mods/48001) by Tixen  
Adds the three missing Bethesda splash screens not covered by NZdawghaus' mod in widescreen resolution.
- MO2 will tell you there's no game data on top level.
  - Right click on **data**, and click **Create directory...**. Name this new folder **splash** and click **OK**.
  - Drag the three .tag files into the **splash** folder and click **OK**.

> An alternative to the above mods which modify the title screen and the splash screen is Half11's [**Unstretched Splash Screens**](https://www.nexusmods.com/morrowind/mods/45800). This mod adds black bars on both sides of the splash screens and the main menu so that they will no longer be stretched when playing in widescreen resolutions. It also includes the six missing Bethesda splash screens.

## CONTENT RESTORATION

These mods restored content cut from the finished game. There's an emphasis on mod that took the shortest route to restore this cut content, and most importantly, on cut content that works well.

- [**Blight Storms Restored**](https://www.nexusmods.com/morrowind/mods/45558?) by half11: restores the function of catching blight disease while out in a blight storm.
- [**Bloated Caves**](https://www.nexusmods.com/morrowind/mods/43141) by ManaUser: adds the unused Bloatspore to over 20 caves and caverns of Vvardenfell.
- [**Creature VFX Restoration**](https://www.nexusmods.com/morrowind/mods/46194?) by rot: restores visual effects on creatures.
- [**Great Service**](https://www.nexusmods.com/morrowind/mods/47767) by Von Djangos: enables over 100 lines of voiced dialogue for shopkeepers that were shipped with the original game but never used.
- [**Services Restored**](https://www.nexusmods.com/morrowind/mods/47068?tab=files) by half11: adds Cinia Urtius, a master trainer for Medium Armor (as per the Morrowind Prophecies Official Strategy Guide), and restores Hecerinde's Secret Master vendor items.
- [**Silt Strider Animation Restored**](https://www.nexusmods.com/morrowind/mods/44150?) by R-Zero: restores an unused Silt Strider animation and an unused sound.
  - MO2 will tell you there's no game data on top level.
    - Right click **Data Files** and click **Set data directory**. Click **OK**.
- [**Sound Spell Sound Effect**](https://www.nexusmods.com/morrowind/mods/43300) by R-Zero: the player will hear an actual noise when he's under the effects of the Sound magic. Its volume depends on the total magnitude of the effect.
  - MO2 will tell you there's no game data on top level. 
    - Right click **Data Files** and click **Set data directory**. Click **OK**.
- [**The Publicans**](https://www.nexusmods.com/morrowind/mods/45410?) by half11: fixes several places in the vanilla game that are set up like inns, but in which Bethesda for some reason forgot to add the option to rent a room in.

### CLEANING PLUGINS

The following plugins are dirty and require cleaning. [Follow the instructions here on how to clean plugins.](https://github.com/Sigourn/morrowind-improved/blob/master/mwtools.md#cleaning-plugins)

- **Bloated Caves.esp**
  - Clean with TESTool and tes3cmd.
  - Delete the following records in TESAME:
    - Container **cavern_spore00**
    - Lev Item **MU_Bloat_Random**

## INTERNAL LOGIC

These mods increase the internal consistency of the game, taking into account aspects such as lore and dialogue.

- [**Blighted Mine Means Blighted Workers**](https://www.nexusmods.com/morrowind/mods/33920) by Cliffworms: if a mine is blighted, the kwama worker standing outside of it will now be blighted as well.
- [**Corprus Fix**](https://www.nexusmods.com/morrowind/mods/45544) by grasscid: gives you the disease resisting effects of Corprus as soon as you catch it from Dagoth Gares rather than after Divayth Fyr cures you, as according to the lore.
- [**Dubdilla Location Fix**](https://www.nexusmods.com/morrowind/mods/46720) by half11: moves the entrance to the cavern of Dubdilla to a more logical place according to in-game information.
- [**FMI - Hospitality Papers Expanded**](https://www.nexusmods.com/morrowind/mods/46107) by quorn, PoodleSandwich, Jeff Baker, and SuperQuail: expands quorn's HospitalityPapers Mod, including newly recorded lines from original Morrowind voice actor Jeff Baker.
- [**FMI - Legion Dialogue**](https://www.nexusmods.com/morrowind/mods/47318) by PoodleSandwich: fixes several inconsistencies in dialogue spoken by members of the Imperial Legion.
- [**FMI - Misc**](https://www.nexusmods.com/morrowind/mods/47637) by PoodleSandwich: fixes a handful of small inconsistencies between lore and what is found in game.
  - Install both main files.
- [**FMI - Nice to Meet You**](https://www.nexusmods.com/morrowind/mods/47329) by PoodleSandwich: NPCs no longer will greet you as if they had just met you.
- [**FMI - NotAllDunmer**](https://www.nexusmods.com/morrowind/mods/47569) by PoodleSandwich: not all Dunmer are slavers. Not all Argonians are slaves. Idle dialogue filtering has been improved to reflect this. 
- [**FMI - Service Refusal and Contraband**](https://www.nexusmods.com/morrowind/mods/47456) by PoodleSandwich: fixes lore to gameplay inconsistencies pertaining to contraband items and service refusal. 
- [**LDM - Context Matters**](https://www.nexusmods.com/morrowind/mods/48273) by Lucevar: edits, re-filters, or adds on to vanilla dialogue to add more situational nuance - tavern owners will no longer talk about themselves in third person, Ashlanders will no longer curse vampires in the name of Almsivi, slave owners won't talk lovingly about abolitionists, and thieves will be less blase about incriminating themselves to strangers.
- [**Ownership Overhaul**](https://www.nexusmods.com/morrowind/mods/48051) by Necrolesian: assigns ownership to the many, many items and containers that rightly should be owned but weren't, and otherwise makes adjustments to item ownership. 
- [**Religions Elaborated**](https://www.nexusmods.com/morrowind/mods/47843) by Caeris: adds supply chests, missing temple markers, healing services to healers, disallows you to be a member of both Tribunal Temple and Imperial Cult, adds roleplay options to *some* persuasion quests, and decentralizes the Imperial Cult quests away from Ebonheart.
  - Only install the **No Quest Changes** optional file.
- [**Silence**](https://www.nexusmods.com/morrowind/mods/37921?) by Jyggalag117: the player will not be able to speak to NPCs when silenced.
- [**Synthesis Series - Creatures and Diseases**](https://www.nexusmods.com/morrowind/mods/48279) by Half11: edits existing creatures and adds new creature variants according to in-game lore, restoring unused diseases into the game.
- [**Telvanni Staff for the Telvanni Staff**](https://www.nexusmods.com/morrowind/mods/47869/) by Gavrilo93: according to in-game information, it seems that a Telvanni Mouth's symbol of office is the Silver Staff of Peace. Yet in vanilla, only you get one when you become a Mouth, which you would have to give to Fast Eddie when he becomes your Mouth. Therefore this mod adds a Silver Staff of Peace into the inventory of the six other Telvanni Mouths, including Baladas' Mouth, who only shows up mid-game.
- [**Temples with Shrines**](https://www.nexusmods.com/morrowind/mods/45535) by Leyawynn: adds shrines to the temples in Maar Gan, Molag Mar, Suran and Vos.
- [**The Dream is the Door**](https://www.nexusmods.com/morrowind/mods/47423) by Melchior Dahrk: to align with what the in-game dialogue suggests, the entrance to the Cavern of the Incarnate will now only be visible during the magical hours of twilight. 
- [**The Madstone**](https://www.nexusmods.com/morrowind/mods/47653) by Melchior Dahrk: makes the Madstone work as described on the lore, adds a new model to the Madstone, and expands on in-game dialogue.
- [**Wizards Staff for Wizards**](https://www.nexusmods.com/morrowind/mods/48302) by Endify: gives a Wizards Staff to high ranking members of the Mages Guild, four in total. 

### CLEANING PLUGINS

The following plugins are dirty and require cleaning. [Follow the instructions here on how to clean plugins.](https://github.com/Sigourn/morrowind-improved/blob/master/mwtools.md#cleaning-plugins)

- **Dubdilla Location Fix.esp**
  - Clean with TESTool and tes3cmd.
- **true corprus.esp**
  - Clean with TESTool and tes3cmd.

## VISUALS

These mods aim to improve specific visual aspects of the game I personally found deficient, especially when the game is paired alongside MGE XE in the case of water sources. This section also includes mods to make interiors and nights darker, and add groundcover to most of Morrowind's regions. Other little mods included tweak certain silly-looking meshes, or add neat visual effects to some of the game's statics.

- [**Apel's Rain Replacer**](https://www.nexusmods.com/morrowind/mods/42555) by Apel and HedgeHog-12: replaces rain with a more heavy rain look.
- [**Arukinn's Better Books and Scrolls**](https://www.nexusmods.com/morrowind/mods/43100/) by Arukinn: replaces all the books, book pages and scroll textures with ones that have the look and feel of the original textures.
  - Hide/delete all .dds files inside **Data Files\Textures** minus **Tx_book_01.dds through Tx_book_16.dds**.
- [**Anumaril's Minor Mods**](https://www.nexusmods.com/morrowind/mods/48291) by Anumaril21.
  - **Ashmire Replacer**: replaces the ashmires found throughout the ashen regions of Vvardenfell with models that feature a subtle bubbling effect, edits that allow dropping and activating objects through the mire plane, and optionally removal of their nonsensical flowing animation.
    - MO2 will install this mod as BAIN package. Tick only **01 Still Mire** and click **OK**.
  - **Bitter Coast Scum Replacer**: replaces the scum found throughout the Bitter Coast using the animation method and edited textures of Tamriel Rebuilt's water statics and Pherim's Vanilla-Friendly Scum Texture.
    - MO2 will install this mod as a BAIN package. Tick the following options and click **OK**:
      - **00 Core**
      - **01 Animated Replacer - Original Color**
  - **Vivec Palace Water Replacer**: replaces the water in the Palace of Vivec's canals.
    - MO2 will install this mod as a BAIN package. Tick the following options and click **OK**:
      - **00 Core**
      - **01 Original Color**
- [**Better Waterfalls**](https://www.nexusmods.com/morrowind/mods/45424?) by Melchior Dahrk: new effects and textures for the waterfalls. Includes LOD on the particle effects to improve performance.
- [**Bloodmoon Hide Replacer BHR**](https://www.nexusmods.com/morrowind/mods/21725?) by Alaisiagae: replaces the Bear, Snow Bear, Wolf, and Snow Wolf ingredients so that they look like pelts instead of mutilated heads.
- [**Buoyant Lord Vivec**](https://www.nexusmods.com/morrowind/mods/48312) by Stripes: adds a simple script to make Vivec properly loop his idle animation.
  - MO2 will install this mod as a BAIN package. Only tick **00Vanilla** and click **OK**.
- [**Cave Drips**](https://www.nexusmods.com/morrowind/mods/43488) by R-Zero: adds a visual effect to all vanilla cave drip sound emitters.
  - MO2 will tell you there's no game data on top level.
    - Right click **Data Files** and click **Set data directory**. Click **OK**.
- [**Complete Armor Joints**](http://mw.modhistory.com/download-4-12572) by Kahkahra: adds the unused forearm joint to the Orcish Pauldrons, Dwemer Pauldrons, and the three types of Bonemold Pauldrons, and modifies the Dwemer, Daedric, Chitin and Netch greaves and pauldron to prevent them showing clothing underneath.
  - Download the mod from the main link at the top of the page, *not* the outdated v1.0 link at the bottom.
- [**correctUV Diverse Ore Veins**](http://mw.modhistory.com/download-42-13484) by CJW-Craigor and Nich: matches the ore container textures to the caves the containers are placed in, with better UV mapping by Nich.
  - This mod is incorrectly packaged. 
    - Drag the **Meshes** folder into the mod's root directory in MO2.
- [**Creeper the Drummer**](https://www.nexusmods.com/morrowind/mods/42451) by Faelian: alters Creeper's animations making him randomly sit on the ground and play his drums.
  - MO2 will tell you there's no game data on top level.
    - Expand the **Creeper the drummer** folder. 
    - Right click **Data Files** and click **Set data directory**. Click **OK**.
- [**Facelift**](https://www.nexusmods.com/morrowind/mods/47617) by kartoffels: vanilla-friendly improvement of the head meshes and textures.
  - Install the **kart_facelift_default** main file and the **kart_facelift_update_0-10-3** update file.
    - Hide/delete the **Textures** folder. **Intelligent Textures** includes better textures.
- [**Flies**](https://www.nexusmods.com/morrowind/mods/43481) by R-Zero: adds a visual effect to all vanilla flies sound emitters.
  - MO2 will tell you there's no game data on top level.
    - Right click **Data Files** and click **Set data directory**. Click **OK**.
- [**FMI - Caius Big Package**](https://www.nexusmods.com/morrowind/mods/47580) by PoodleSandwich: makes the Package for Caius Cosades an actual package.
- [**FMI - Belladonna - Unique and Deadly**](https://www.nexusmods.com/morrowind/mods/47046) by PoodleSandwich: gives ripened Belladonna a unique vanilla-friendly look, matching its real life appearance.
  - Only install the **Unique Rippened Belladonna** optional file.
- [**Folded in Port**](https://www.nexusmods.com/morrowind/mods/46113) by Texture Freak, PoodleSandwich, Alaisiagae, and Remiros: folds up the sails of longboats in port.
  - Hide/delete **Meshes\x\Ex_longboat01.nif**. This mesh is buggy and unnecessary for this mod to work as intended.
- [**Glow in the Dahrk**](https://www.nexusmods.com/morrowind/mods/45886) by Melchior Dahrk and NullCascade: makes windows glow in the dark.
  - MO2 will install this mod as a BAIN package. Tick the following options and click **OK**:
    - **00 Core**
    - **01 Hi Res Window Texture Replacer**
    - **02 Interior Sunrays**
    - **03 Nord Glass Windows Interior Sunrays**
    - **05 Raven Rock Glass Windows Interior Sunrays**
- [**Project Atlas**](https://www.nexusmods.com/morrowind/mods/45399) by the Project Atlas Team: optimizes the most performance heavy areas of vanilla Morrowind through texture atlases. 
  - MO2 will install this mod as a BAIN package. Only tick **10 Glow in the Dahrk Patch - Interior Sunrays**.
  - Rename the mod to **Project Atlas - Glow in the Dahrk Patch**. Click **OK**.
- [**Golden Saint Feminine Walk**](https://www.nexusmods.com/morrowind/mods/42703/) by dopey fish: gives the base golden saint the feminine walk animation instead of the default male walk animation.
  - MO2 will tell you there's no game data on top level. 
    - Right click on **data**, and click **Create directory...**. Name this new folder **meshes**. Click **OK**. 
    - Right click the **meshes** folder and click **Create directory...**. Name this new folder **r**. Click **OK**. 
    - Expand the **meshes** folder. Drag the three loose files into the **meshes\r** folder. Click **OK**.
- [**Guarskin Drum Replacer**](https://www.nexusmods.com/morrowind/mods/37539?) by Alaisiagae: gives the guarskin drum a unique model.
- [**Have You Seen the Muffin Mod**](https://www.nexusmods.com/morrowind/mods/46116) by Taddeus and PoodleSandwich: gives an unique mesh to the in-game muffin.
- [**Hopesfire Glow**](https://www.nexusmods.com/morrowind/mods/45855) by grasscid: allows Hopesfire to act as a torch when drawn, illuminating the particle effects on the blade and casting ambient lighting around the player just like Trueflame does.
  - Hide/disable **Hopesfire Torch.esp.** 
- [**Improved Nordic Iron Helm Mesh**](https://www.nexusmods.com/morrowind/mods/43816/) by Daemonjax: modifies the Nordic Iron Helm to look less stupid.
  - Only install the **Improved Nordic Iron Helm 1.0-alternate** optional file.
- [**Improved Thrown Weapon Projectiles**](https://www.nexusmods.com/morrowind/mods/44763?) by R-Zero: makes thrown weapon projectiles fly pointy end forward and, some of them, spin in the air.
  - MO2 will tell you there's no game data on top level. 
    - Right click **Data Files** and click **Set data directory**. Click **OK**.
- [**Keg Drip**](https://www.nexusmods.com/morrowind/mods/47903/) by Melchior Dahrk and Greatness7: implements a previously unused keg droplet texture from the game files to add a new effect to select kegstands in the game. Now you might notice a leaky tap upon closer inspection just like Bethesda may have intended with this texture but never followed through on.
  - MO2 will install this mod as a BAIN package. Tick the following options and click **OK**:
    - **00 Core**
    - **01 MWSE Version**
- [**Let There Be Darkness - Lua Lighting Overhaul**](https://www.nexusmods.com/morrowind/mods/47912/) by Greatness7, Merlord, OperatorJack, Petethegoat, and RedFurryDemon: configurable mod for automatical adjustment of lighting, including override values, cell whitelist, and light object editing.
- [**Melchior's Magnificent Manuscripts**](https://www.nexusmods.com/morrowind/mods/45626?) by Melchior Dahrk: replaces the book meshes and scrolls. Also adds new scroll textures. 
  - MO2 will install this mod as a BAIN package. Tick **00 Core** and click **OK**.
- [**Mistify**](https://www.nexusmods.com/morrowind/mods/48112) by Melchior Dahrk: enhances the ambiance of the Bitter Coast by adding a new mist effect throughout region which appears during the night and certain weather conditions. It will burn off in the morning sun. The effect has been optimized to minimize performance impact. The mod also includes an optional mesh replacer for the vanilla effect. 
  - MO2 will install this mod as a BAIN package. Tick the following options and click **OK**:
    - **00 Core**
    - **01 Vanilla Mist Replacer**
- [**Mist Retexture**](https://www.nexusmods.com/morrowind/mods/44322) by Remiros: improves the texture for the mist. The mist is now much smoother and more detailed, as well as less opaque and flat. This also makes it play much nicer with SSAO.
  - Only install the **Mist Retexture** main file.
- [**Nordic Chest Replacer**](https://www.nexusmods.com/morrowind/mods/45383) by Remiros: replaces the standard wooden chests in Nordic Tombs with a unique model, because the original looked horribly out of place.
- [**Parasol Particles**](https://www.nexusmods.com/morrowind/mods/47755) by Melchior Dahrk: adds falling spores particle effects to the iconic emperor parasol mushrooms.
  - MO2 will install this mod as a BAIN package. Only tick **00 Core** and click **OK**.
- [**Pete's Scroll 2018 ...in 2020**](https://www.nexusmods.com/morrowind/mods/47863/?) by Petethegoat: replacement scroll and journal textures, rendered out in 1k, 2k, and 4k dimensions.
  - Only install the **Pete's Journal and Scroll** optional file.
  - MO2 will install this mod as a BAIN package. Tick **01 Journal and Scroll - 2K** and click **OK**.
- [**Realistic Blood v1.0**](http://mw.modhistory.com/download-50-10419) by Leatherpoker: makes blood more liquid and less smoke-like.
  - This mod is incorrectly packaged. 
    - Right click on **data**, and click **Create directory...**. Name this new folder **textures**. Click **OK**. 
    - Drag **tx_blood.dds** into the **Textures** folder. Click **OK**.
- [**R-Zero's Throbbing Meat - a Corprus Meat Replacer**](https://www.nexusmods.com/morrowind/mods/45339) by R-Zero: replaces corprus meat models with animated, twitching ones ones.
  - MO2 will tell you there's no game data on top level. 
    - Right click **Data Files** and click **Set data directory**. Untick the **Textures** folder. Click **OK**.
- [**Signs-Banners Tweak Edit**](https://www.mediafire.com/file/gsoqn3n2za8c5it/Signs-Banners_Tweak_Edit.zip/file) by ddfields and Sigourn: corrects the UV Set TexCoord so that signs will display the same on both sides.
- [**Simple Golden Gold**](https://www.nexusmods.com/morrowind/mods/45124) by McChuggernaut: turns the green coins into gold coins.
  - Only install the **Gold coins** main file.
- [**Skeleton and Metal Sparks blood retexture**](https://www.nexusmods.com/morrowind/mods/43359) by R-Zero: retextures the Skeleton (white) and Metal Sparks (gold) textures.
  - MO2 will tell you there's no game data on top level. 
    - Right click **Data Files** and click **Set data directory**. Click **OK**.
- [**Soldier Belts Fix**](https://www.nexusmods.com/morrowind/mods/25556?) by Alaisiagae: gives the Templar, Imperial, and Indoril Belts unique ground meshes and icons.
- [**Spear-Staff Fix**](https://www.nexusmods.com/morrowind/mods/43353/?) by hollaajith: changes the position where Spears/Staffs are held. Now they are held closer the end.
  - MO2 will tell you there's no game data on top level.
    - Expand **Spear Only**.
    - Right click **Data Files** and click **Set data directory**. Click **OK**.
  - Hide/delete **Data Files\Meshes\w\w_silver.staff.nif**. This mesh was incorrectly included into this option.
- [**Subtle Smoke**](https://www.nexusmods.com/morrowind/mods/47341) by wazabear: makes it so many smoke effects are much more laid back and easier on the eyes.
- [**Transporter Lights**](https://www.nexusmods.com/morrowind/mods/48050) by Eq: Caravaners, Gondoliers, and Shipmasters equip lights at night for more immersion.
- [**Unto Dust**](https://www.nexusmods.com/morrowind/mods/48435?) by Melchior Dahrk and Greatness7: adds floating dust to areas where dead are entombed similar to what is seen in Skyrim barrows.
  - MO2 will install this mod as a BAIN package. Tick the following options and click **OK**:
    - **00 Core**
    - **01 Default Dust**
- [**Visually Filled Soul Gems**](https://www.nexusmods.com/morrowind/mods/46709) by NullCascade: makes in-world soul gems that are filled appear as enchanted items.
- [**Waterfalls Tweaks**](https://www.nexusmods.com/morrowind/mods/46271) by multiple: reduces the water splash from **Better Waterfalls** to a more reasonable size.
- [**Weapon Sheathing**](https://www.nexusmods.com/morrowind/mods/46069) by akortunov, Greatness7, Heinrich, Hrnchamd, London Rook, Lord Berandas, Melchior Dahrk, MementoMoritius, NullCascade, PetetheGoat, PikachunoTM, and Remiros: equipped weapons will be shown on the character's hip or back. This new functionality affects both the player and all other characters, and works with all weapons from all mods. Additionally features a comprehensive set of high quality quiver and scabbard assets.
  - Only install the **WeaponSheathing 1.6-MWSE** main file.
  - MO2 will tell you there's no game data on top level. 
    - Right click **Data Files** and click **Set data directory**. Click **OK**.
- [**Morrowind Optimization Patch**](https://www.nexusmods.com/morrowind/mods/45384?) by Remiros and Greatness7: greatly improves performance and fixes some mesh errors.
  - MO2 will install the mod as a BAIN package. Only tick **04 Weapon Sheathing Patch**.
  - Rename the mod to **Morrowind Optimization Patch - Weapon Sheathing Patch**. Click **OK**.
- [**Weapon Sheathing - Bow Position Edit**](https://www.nexusmods.com/morrowind/mods/48473?) by Kyim: a simple mesh edit, the bows should now better line up with the sheathing animation.
- [**Weather Adjuster**](https://www.nexusmods.com/morrowind/mods/46816) by Hrnchamd: regional weather colours, skies and lighting. Visual weather editor and region-based presets. Seamless transitions between regions.
  - This mod lets you adjust many variables about Morrowind's weather. Read the description to learn how to do this. The reason I recommend it (aside because of how great the mod is) is that users can share their presets: the mod on its own will not change the appearance of the game until you configure it so.
- [**Weather Adjuster - Morrowind Improved json**](http://www.mediafire.com/file/r7vlwhoko8rg2co/Weather_Adjuster_-_Sigourn%2527s_Mod_List_json.zip/file) by Sigourn: personal preset for darker nights and less horrible fog.
  - This mod has to be installed manually. Unpack the file and merge the **overwrite** folder with your Mod Organizer 2 **overwrite** folder, found inside the **Mod Organizer 2** folder. The contents of the folder should like so: **Mod Organizer 2\overwrite\MWSE\config\Weather Adjuster.json**.
  - [**Comparison here.**](https://imgsli.com/MTUwMjI)
- [**Well Diversified**](https://www.dropbox.com/sh/7fv2wojbp6y3uo9/AABIH_hMYjbqmZCPBnyu4NPqa?dl=0&preview=Well+Diversified.7z) by Slartibartfast: creates variants of the well mesh to better fit Imperial and Solstheim architecture.
  - This mod is incorrectly packaged.
    - Create a folder called **Meshes** in the mod's root directory in Mod Organizer 2.
    - Drag the **x** folder into the **Meshes** folder.
- [**Wolf Helmet Replacer**](https://www.nexusmods.com/morrowind/mods/29281) by Alaisiagae: replaces the Wolf and Snow Wolf Helmets with a ferocious wolf head with gaping jaws.

### READABLE SIGNPOSTS

Choose between one of these two alternatives for readable signposts. My personal preference is PeterBitt's, but if you are a vanilla purist nothing beats Atrayonis'.

- [**Near Vanilla Road Sign Replacer**](https://www.nexusmods.com/morrowind/mods/44957?) by Atrayonis: makes road signs legible. Uses vanilla background and resolution.
  - MO2 will install this mod as a BAIN package. Tick the following options and click **OK**:
    - **00 Core**
    - **01 Vvardenfell only**
- [**Signposts Retextured**](https://www.nexusmods.com/morrowind/mods/42126?) by PeterBitt: makes road signs legible. Uses higher quality vanilla-friendly textures.
  - Install only one of the main files.

### LESS INTRUSIVE MAGIC GLOW

Choose between one of these two alternatives for less intrusive magic glow. My personal preference is Assetless No Glow, but if you are a vanilla purist nothing beats Subtle Magic Glow.

- [**Subtle Magic Glow**](https://www.nexusmods.com/morrowind/mods/4468?) by atteSmythe: replaces the "plastic wrap" effect around in-game magic items (those equipped by characters or on the ground) with less-obtrusive versions.
  - MO2 will install this mod as a BAIN package. Tick **faint** and click **OK**.
- [**Assetless No Glow**](https://www.nexusmods.com/morrowind/mods/47925/) by NullCascade: removes the "plastic wrap" effect around in-game magic items (those equipped by characters or on the ground). Uses less memory and is more compatible than other "no plastic wrap effect" mods.
  - For **Weapon Sheathing** to not add the glow effect back into sheathed equipment, we will need to comment some lines in **Weapon Sheating\MWSE\mods\weaponSheathing\main.lua**. We must add "-- " in front of these three lines, as seen here:
    - -- tes3.worldController:applyEnchantEffect(visual, quiver.enchantment)
    - -- tes3.worldController:applyEnchantEffect(visual, shield.enchantment)
    - -- tes3.worldController:applyEnchantEffect(visual, weapon.enchantment)
  - This will allow **Weapon Sheathing** to work flawlessly with **Assetless No Glow**.
  
### MGE XE MODS

The following mods require additional MGE XE configuration after installation to work as intended. Read the mod pages carefully.

- [**Remiros' Groundcover**](https://www.nexusmods.com/morrowind/mods/46733) by Remiros, vtastek, and Hrnchamd: adds groundcover to almost all regions.
  - Only install the **Remiros' Groundcover** main file.
  - MO2 will install this mod as a BAIN package. Tick the following options and click **OK**:
    - **00 Core**
    - **04b Thicker Grass**
- [**Shattered Stones - An Earthquake Mod**](https://www.nexusmods.com/morrowind/mods/45105) by Greatness7, R-Zero, and vtastek: adds recurring earthquakes to certain volcanically active regions of Vvardenfell. The quakes are implemented strictly for atmospheric purposes and should not directly affect gameplay or conflict with any other mods.
  - MO2 will tell you there's no game data on top level. 
    - Right click **Data Files** and click **Set data directory**. Click **OK**.

### CLEANING PLUGINS

The following plugins are dirty and require cleaning. [Follow the instructions here on how to clean plugins.](https://github.com/Sigourn/morrowind-improved/blob/master/mwtools.md#cleaning-plugins)

- **correctUV Ore Replacer 1.0.esp**
  - Clean with TESTool and tes3cmd.
- **Creeper the drummer.esp**
  - Clean with TESTool and tes3cmd.
- **Nordic Chest Replacer.esp**
  - Clean with TESTool and tes3cmd.
  - Delete the following records in TESAME:
    - Cell **Solstheim, Bloodskal Barrow**

## AUDIO

These mods don't so much replace existent sound effects, but like the Visuals section, they seek to improve on the game by adding neat sound effects where there previously weren't any. Overall, most of these tend to improve immersion.

- [**Distant Thunder**](https://www.nexusmods.com/morrowind/mods/43471) by TheInkBunny: adds a randomized bit of lead time to thunderclaps after lightning strikes for additional realism.
  - Only install the **Distant Thunder v1.1 (No Scripts)** optional file.
  - In MO2, click on the Tools icon, which resembles a jigsaw puzzle, and select INI Editor.
  - On the morrowind.ini that just opened, use CTRL+F to find the following entries and replace them with the data in bold:
    - Thunder Sound ID 0=**Distant_Thunder_00**
    - Thunder Sound ID 1=**Distant_Thunder_01**
    - Thunder Sound ID 2=**Distant_Thunder_02**
    - Thunder Sound ID 3=**Distant_Thunder_03**
- [**Haunted Barrows**](https://www.nexusmods.com/morrowind/mods/46826) by Melchior Dahrk: gives Nordic barrows on Solstheim their own unique sound. You will hear some deep-voiced chanting and perhaps some drums in the distance if you listen closely enough; hearkening back to ancient battles and burial rites.
  - MO2 will install this mod as a BAIN package. Tick the following options and click **OK**:
    - **00 Core**
    - **01 Fire Sound Replacer**
- [**Heartthrum**](https://www.nexusmods.com/morrowind/mods/47178?) by RedFurryDemon and OperatorJack: allows the player to listen to the Heart of Lorkhan when inside the Ghostfence.
- [**Outdoor Banners With Sound**](https://www.nexusmods.com/morrowind/mods/47068) by Half11: outdoor banners now play sound alongside their animations. During clear weather types the unused flag.wav sound file is used (it fits this weather type better compared to the standard flag2.wav). For stormy weather types the script uses the regular flag2.wav sound file.
- [**Sheep-no-More**](https://www.nexusmods.com/morrowind/mods/45168) by McChuggernaut: removes the sheep sounds from Morrowind.
- [**Shut the Fuck up Cliff Racers**](https://www.nexusmods.com/morrowind/mods/46588) by Merlord: drastically reduces the frequency of idle Cliff Racer screeches, by editing the kf file of the cliff racer mesh.
- [**Silent Assassins**](https://www.nexusmods.com/morrowind/mods/44371) by R-Zero: Assassin class NPCs will be 10 times less likely to grunt or taunt you in combat, living up to their reputation of being deadly silent killers.
- [**Sounds of Souls**](https://github.com/NullCascade/morrowind-mods/) by NullCascade: soul gems in the world, in the player's inventory, and that the player interacts with will play sounds, corresponding to the creature trapped inside of it.
  - To download the file from GitHub you need to click on the **Clone or download** button on the upper right and click **Download Zip**.
  - MO2 will tell you there's no game data on top level.
    - Expand the **morrowind-mods-master** folder. 
    - Right click **Sounds of Souls** and click **Set data directory**.
    - Rename the mod to **Sounds of Souls**. Click **OK**.
- [**Tunnel Cough**](https://www.nexusmods.com/morrowind/mods/47603) by R-Zero: makes Miner class NPCs cough.
- [**Water Sounds**](https://www.nexusmods.com/morrowind/mods/47794) by abot: simulates water sounds when colliding with generic fake animated water meshes.

## OVERHAULS

These mods make changes to many different game locations with the intention to make them stand out or feel more adequate to what they are supposed to be. These are not your average "clutter" mods, but mods which thoughtfully improve the locations they overhaul.

- [**Atmospheric Delights**](https://www.nexusmods.com/morrowind/mods/47472) by Lucevar: interior overhaul of Desele's House of Earthly Delights to be more atmospheric. Adds several new NPCs with unique dialogue, including a bouncer and several new patrons. The NPCs now use a custom set of vanilla voice lines to better capture their role and personalities.
- [**Cavern Of The Incarnate Overhaul - NPC Changes Only**](https://www.mediafire.com/file/q8jpeviwgkzg43m/Cavern_of_the_Incarnate_Overhaul_-_NPC_Changes_Only.zip/file) by Aoimevelho: modifies the armor and clothes of the failed incarnates to better reflect their backgrounds.
  - This is a stripped down version of [Cavern Of The Incarnate Overhaul](https://www.nexusmods.com/morrowind/mods/42860/) by Aoimevelho, which removes all visual edits to the cavern.
- [**Duke's Throne Room Overhaul**](https://www.nexusmods.com/morrowind/mods/48235) by Gavrilo93: makes the upper floor of the Grand Council Chambers of Ebonheart a proper throne room.
- [**Meteorite Ministry**](https://www.nexusmods.com/morrowind/mods/45506) by Zobator: adds a tail of smaller rocks to the Ministry of Truth, giving it a more dramatic and moving-object-suspended-in-mid-flight look.
  - Hide/delete the following plugins:
    - Meteorite Ministry Palace - Higher.ESP
    - Meteorite Ministry Palace.ESP
    - Meteorite Ministry Temple - Higher.ESP
- [**Yet Another Guard Diversity**](https://www.nexusmods.com/morrowind/mods/45894) by Half11, SkoomaPro, and Danke: replaces the generic, copy-pasted guards of Morrowind with different variations. Some guards have different loadouts and armor, and each have different faces.
- [**No-Frills Closed Molag Mar**](https://www.nexusmods.com/morrowind/mods/47190) by Atrayonis: closes the Molag Mar canton, on account of the ashstorms.
  - MO2 will install this mod as a BAIN package. Tick **00 Core** and click **OK**.
- [**No-Frills Open Vivec**](https://www.nexusmods.com/morrowind/mods/43714) by Atrayonis: opens up the Vivec cantons.
  - MO2 will install this mod as a BAIN package. Tick the following options and click **OK**:
    - **00 Core**
    - **01 Vanilla Placement (ESP)**
- [**Open Mournhold**](https://www.nexusmods.com/morrowind/mods/44981) by LondonRook and Greatness7: changes the passageways between the different city districts, making the transitions more immersive.
- [**Reclamations In Holamayan**](https://www.nexusmods.com/morrowind/mods/43226) by Aoimevelho: places shrines of the Anticipations/Reclamations and a fresco with Boethiah in the Holamayan Monastery.
- [**Seven Graces Shrines Enhanced**](https://www.nexusmods.com/morrowind/mods/46417) by QueenLunara: redesigns the shrines associated with the Seven Graces pilgrimage, making them look more important and like actual pilgrimage sites.
  - Also install the **Seven Graces Shrines Enhanced - No Script Edits** optional file.
  - If you installed **Simple Golden Gold** earlier, also install [**Seven Graces Shrines Enhanced - Simple Golden Gold Patch**](https://www.mediafire.com/file/c62opmbrjgilge6/Seven_Graces_Shrines_Enhanced_-_Simple_Golden_Gold_Patch.zip/file). This will patch Seven Graces Shrines Enhanced's new gold piles with a golden texture.
- [**Shrine of Azura**](https://www.nexusmods.com/morrowind/mods/48278) by Endoran: adds some worshipers and other NPCs to make the shrine feel more like a real place of worship.
- [**Talos Cult Revised - G93's Version**](https://www.nexusmods.com/morrowind/mods/47571) by Gavrilo93: improves the Talos Cult shrine in the Gnisis legion barracks in an attempt to give a more interesting depiction of the cult.
- [**Wolverine Hall Overhaul**](https://www.nexusmods.com/morrowind/mods/46672) by mort: completely overhauls the notoriously confusing Wolverine Hall in Sadrith Mora.
  - MO2 will tell you there's no game data on top level.
    - Expand the **Wolverine Hall Overhaul** folder. 
    - Right click **Data Files** and click **Set data directory**. Click **OK**.

### CLEANING PLUGINS

The following plugins are dirty and require cleaning. [Follow the instructions here on how to clean plugins.](https://github.com/Sigourn/morrowind-improved/blob/master/mwtools.md#cleaning-plugins)

- **Clean Atmospheric Delights.esp**
  - Clean with tes3cmd.
- **Duke's Throne Room Overhaul.esp**
  - Clean with tes3cmd.
- **QL_SevenGracesShrines.esp**
  - Clean with tes3cmd.
- **ReclamationsInHolamayan.esp**
  - Clean with tes3cmd.
- **Talos Cult Revised.esp**
  - Clean with tes3cmd.

## GAMEPLAY

These mods tweak certain annoying or deficient aspects of the game's gameplay. Some of these are quality of life improvements, other simply make sense.

- [**Abundant Adamantium Ore**](https://www.nexusmods.com/morrowind/mods/45726) by grasscid: every Raw Adamantium rock is guaranteed to have at least 2 pieces of Adamantium Ore. This means even at the bare minimum amount, if you visit every Raw Adamantium rock in the game, you'll be guaranteed to be able to craft yourself at least one full set of Adamantium Armor.
- [**Adamantium Weapons Ignore Normal Weapon Resistance**](https://www.nexusmods.com/morrowind/mods/45774) by AresGAWDofWar:  adamantium weapons, much stronger than silver, will now ignore Normal Weapon resistance.
- [**Divayth Fyr Puzzle Fixed**](https://www.nexusmods.com/morrowind/mods/45155) by Remiros: reworks Divayth Fyr’s puzzle so that you require the correct key to open the chests as well as locking up all the artifacts, which now require the final key to be opened.
- [**Early Transport to Mournhold**](https://www.nexusmods.com/morrowind/mods/47985) by Necrolesian: allows travel to Mournhold before the Dark Brotherhood attacks begin.
- [**Fix those bastard rope fences**](https://www.nexusmods.com/morrowind/mods/45741) by EJ-12 and Petethegoat: modifies collision boxes on rope-related meshes to prevent getting stuck in them, as well as the player and NPC's hitboxes, making it easier to squeeze past NPCs in tight situations.
- [**FMI - Sane Ordinators**](https://www.nexusmods.com/morrowind/mods/47381) by PoodleSandwich: makes it so Ordinators will not kill you for wearing Indoril armor once you have been named Nerevarine by Vivec, or if you are Master or Patriarch of the Temple.
- [**Gondolier Destinations**](https://www.nexusmods.com/morrowind/mods/42306/?) by PeterBitt: each gondolier in Vivec will now get you to all gondolier ports in Vivec.
- [**Higher Faction Requirements**](https://www.nexusmods.com/morrowind/mods/45732) by King Feraligatr: makes factions have higher requirements for advancing.
  - Hide/disable **higher faction requirements - Morrowind Only.esp**.
- [**Hunter's Mark - A Marksman Mod**](https://www.nexusmods.com/morrowind/mods/46656) by Remiros: adds a lot of new marksman weapons in an attempt to improve progression and fill in the gaps in the vanilla game. It includes new bows, crossbows, arrows, bolts and throwing weapons. All weapons have been seamlessly integrated into the game world via leveled lists and other means. The new Stalhrim items can be crafted in the same way as the vanilla items. All weapons have sheaths and quivers that are compatible with Weapon Sheathing.
- [**Lower First Person Sneak Mode**](https://www.nexusmods.com/morrowind/mods/43108) by Androl: lowers the position of the first person camera when sneaking/crouching, making it easier to tell if you are sneaking.
- [**Projectile Enchant Capacity**](https://www.nexusmods.com/morrowind/mods/46685) by pianobadger: creates balanced enchant values for all projectiles in Morrowind to better make use of the Morrowind Code Patch "Arrow enchanting" option.
- [**Speed and Movement Rebalanced**](https://www.nexusmods.com/morrowind/mods/46029/) by Remiros: rebalances the speed attribute and overall movement in the game in an attempt to make it feel more natural.
  - In TESAME, delete the following records: 
    - GMST **fJumpRunMultiplier**
  - Save the plugin as **Speed and Movement.ESP**, overwriting the original when asked.
  - This restores the higher speed when jumping, allowing to clear larger gaps as intended in the vanilla game.
- [**Supply Chests Merged**](https://www.mediafire.com/file/0imsxgeox22x49g/Supply_Chests_Merged_v1.0.zip/file) by Gavrilo93 and CryptsOfTheDead: merge of the [Imperial Cult](https://www.nexusmods.com/morrowind/mods/47836), [Morag Tong](https://www.nexusmods.com/morrowind/mods/47753), and [Tribunal Temple](https://www.nexusmods.com/morrowind/mods/47656) Supply Chest series, and [Imperial Legion Goods](https://www.nexusmods.com/morrowind/mods/43002).
  - MO2 will install this mod as a BAIN package. Tick the corresponding options and click **OK**:
    - **00 Complete**: only if you didn't install **Religions Elaborated** earlier.
    - **02 Religions Elaborated Compatible**: only if you installed **Religions Elaborated** earlier.

### CLEANING PLUGINS

The following plugins are dirty and require cleaning. [Follow the instructions here on how to clean plugins.](https://github.com/Sigourn/morrowind-improved/blob/master/mwtools.md#cleaning-plugins)

- **Divayth Fyr Puzzle Fixed.ESP**
  - Clean with TESTool and tes3cmd.
- **Religions Elaborated.ESP**
  - Clean with tes3cmd.

### GAMEPLAY MWSE

These gameplay mods require MWSE to work properly. Thanks to the power of MWSE, many of these mods add neat new mechanics into the game, some present in older Elder Scrolls games, others entirely new. In many cases, these mods can be configured in-game to suit your particular tastes.

- [**Bed Buddies**](https://www.nexusmods.com/morrowind/mods/46632) by Merlord: prevents you from sleeping in owned beds unless the owner really likes you. Disposition requirement is based on your Personality. Attempting to sleep in an owned bed no longer triggers a crime, even if the owner doesn't like you.
- [**Book Pickup**](https://www.nexusmods.com/morrowind/mods/46625) by NullCascade: enables picking up books by default, instead of opening them. This can be disabled by holding shift. The behavior can be inverted using the mod config menu.
- [**Brutal Backstabbing**](https://www.nexusmods.com/morrowind/mods/45890) by Merlord: do more damage when stabbing an enemy from behind (based on Agility/Sneak). NPCs can backstab you as well. Mod Configuration Menu includes option for Short Blades only or all weapons.
- [**Dahrk's Super-Sized Storage (D'sSSS)**](https://www.nexusmods.com/morrowind/mods/45147?) by Melchior Dahrk: increases the capacity of all containers (BM and TR included) by x100. Enough to help you sort out those pesky dwemer cogs.
  - MO2 will tell you there's no game data on top level. 
    - Right click **Data Files** and click **Set data directory**. Click **OK**.
- [**Diligent Defenders**](https://www.nexusmods.com/morrowind/mods/45717?) by NullCascade: when the player or the player's companions are attacked, any companions will launch into action in defense.
- [**Easy Escort**](https://www.nexusmods.com/morrowind/mods/45712?) by NullCascade: ensures that your followers get warped to you if they get too far away. Compatible with any follower from any mod, without any special script attached to that NPC.
- [**Graphic Herbalism - MWSE and OpenMW Edition**](https://www.nexusmods.com/morrowind/mods/46599) by Stuporstar and Greatness7: automatically harvests herbs, instead of opening the container interface. Picked herbs will now have their meshes modified or disappear altogether (they will still respawn).
  - MO2 will install this mod as a BAIN package. Tick **00 Core + Vanilla Meshes** and click **OK**.
  - Also install the **GH Patches and Replacers** optional file. MO2 will install this mod as a BAIN package. Tick the corresponding options and click **OK**:
    - **00 Correct UV Ore + README**: only if you installed **correctUV Diverse Ore Veins** earlier.
    - **10 Atlas - Vanilla BC Mushrooms**: only if you installed **Project Atlas** earlier.
  - Hide/disable **correctUV Ore Replacer_fixed.esp**
  - From **correctUV Diverse Ore Veins**, hide/disable **correctUV Ore Replacer 1.0.esp**
- [**Kill Command**](https://www.nexusmods.com/morrowind/mods/46723) by Merlord: adds a configurable hotkey that will send all companions to attack whatever you are currently looking at.
  - MO2 will tell you there's no game data on top level. 
    - Right click **Data Files** and click **Set data directory**. Click **OK**.
- [**Less Aggressive Creatures**](https://www.nexusmods.com/morrowind/mods/48292) by Merlord: allows you to create a list of creatures which will have a chance to be spawned passively, with an MCM option to set the passive chance. Defaults to a 50% chance of non-diseased cliff racers being passive.
- [**Lock Bashing**](https://www.nexusmods.com/morrowind/mods/44857) by Greatness7: adds the ability to bash open locked doors and chests, as was an option in previous TES games.
- [**Lucky Strike - a Critical Hit Mod**](https://www.nexusmods.com/morrowind/mods/45765) by R-Zero: add as Luck-based Critical Strike mechanic reminiscent of the one in Daggerfall.
  - This mod is incorrectly packaged.
    - Expand the **Data Files** folder.
    - Drag the **mwse** folder into the mod's root directory in MO2.
- [**Magicka Based Skill Progression**](https://www.nexusmods.com/morrowind/mods/48330) by JaceyS: spellcasting skills advance based on the amount of Magicka spent, rather than the number of spell casts.  
- [**Marksman Rebalanced**](https://www.nexusmods.com/morrowind/mods/46715) by Merlord: takes into account the distance to target when calculating the hit chance for ranged weapons. This applies to both the player and NPCs. Crouching also provides a boost to hit chance.
  - MO2 will tell you there's no game data on top level. 
    - Right click **Data Files** and click **Set data directory**. Click **OK**.
- [**Merlord's Starting Equipment**](https://www.nexusmods.com/morrowind/mods/47283?) by Merlord: adds starting equipment, based on the items seen in the images in the class selection screen for vanilla classes, or on major/minor skills for custom classes. 
  - MO2 will tell you there's no game data on top level. 
    - Right click **Data Files** and click **Set data directory**. Click **OK**.
- [**Misc Mates**](https://www.nexusmods.com/morrowind/mods/48122) by Merlord: NPCs will allow you to take small inexpensive items if their disposition towards you is high enough. The disposition required is based on the gold value of the item and the player's personality.
  - MO2 will tell you there's no game data on top level. 
    - Right click **Data Files** and click **Set data directory**. Click **OK**.
- [**MWSE Character Creation Name Generator**](https://www.nexusmods.com/morrowind/mods/46189) by Aleist3r: allows you to generate a random name for you character upon character creation.
- [**MWSE Magicka Regen**](https://www.nexusmods.com/morrowind/mods/48129) by Anumaril21: provides functional and configurable magicka regeneration for the player, NPCs, and creatures within Morrowind.
- [**No Rest Without Beds**](https://www.nexusmods.com/morrowind/mods/46724) by Kaedius: prevents the player from resting unless they activate a bed.
- [**Plain Paper Fix**](https://www.nexusmods.com/morrowind/mods/47735) by abot: allows you to pick up a blank sheet of paper without having to read it first.
- [**Poison Crafting**](https://www.nexusmods.com/morrowind/mods/45729) by Greatness7: grants the ability to use potions offensively, as poisons applied to your weapons. Supports all potions, including those added by other mods or crafted by the player. Additionally includes new HUD elements and various other improvements to the alchemy system as a whole.
- [**Putting Power In Willpower**](https://www.nexusmods.com/morrowind/mods/45742) by R-Zero: rebalances the willpower-based spell resist mechanic, giving all in-game actors, Player, NPCs and Creatures an ability to shrug off spells through the sheer force of will.
  - MO2 will tell you there's no game data on top level.
    - Expand the **2.0** folder. 
    - Right click the **Data Files** folder and click **Set data directory**. Click **OK**.
- [**Realistic Movement Speeds**](https://www.nexusmods.com/morrowind/mods/46248) by OperatorJack: modifies movement speeds when strafing or backpedalling so that they are more realistic. NPCs and player alike will no longer be able to fire volleys of arrows while running backwards to safety. Movement direction is now tactically important.
- [**Realistic Repair**](https://www.nexusmods.com/morrowind/mods/46673) by Merlord: overhauls the repair mechanic, by making it so that repair hammers can only be used by activating an anvil, and prongs used by activating a forge. Optionally, when an NPC dies, all their equipped gear is damaged to <20% condition.
  - Right click **Data Files** and click **Set data directory**.
  - Untick **Realistic_Repair_Optional.esp**. Click **OK**.
- [**Corsair83's Realistic Repair - Add-on**](http://www.mediafire.com/file/p1dhscj4t966b83/Corsair83%2527s_Realistic_Repair_-_Add-on_v1.1.zip/file) by Corsair83: adds additional forges and anvils to major cities and settlements that did not previously contain any.
- [**Corsair83's Realistic Repair - Add-on - Patch for Purists Patch**](https://www.mediafire.com/file/zsbdfs0dvj8doh0/Corsair83%27s_Realistic_Repair_-_Add-on_v1.1_-_Patch_for_Purists_Patch.zip/file): fixes conflicts in Arrille's inventory.
- [**Retroactive Health Gain**](https://www.nexusmods.com/morrowind/mods/47959) by hardek: increases health upon level up as though endurance was at its current value for past levels.
- [**Security Enhanced**](https://www.nexusmods.com/morrowind/mods/47038) by OperatorJack: adds hotkeys for lockpicks and probes, as well as hotkey cycling options, ordering options, and auto-equip options for activating locked or trapped objects.
- [**Sneaky Strike**](https://www.nexusmods.com/morrowind/mods/48317) by VitruvianGuar: modifies critical strike coefficient depending on the weapon you use.
- [**Switchable Scriptures**](https://www.nexusmods.com/morrowind/mods/46680) by Stuporstar and NullCascade: lets you open or close any book or scroll in the game.
  - MO2 will install this mod as a BAIN package. Tick the corresponding options and click **OK**:
    - **00 Core**
    - **01 Closed Book Icons**
    - **03 Melchior's Magnificent Manuscripts**: only if you installed **Melchior's Magnificent Manuscripts** earlier.
- [**The Midnight Oil - Lighting Overhaul**](https://www.nexusmods.com/morrowind/mods/48293) by Merlord: toggle lights on and off. Town lights turn off during the day. Lights no longer destroyed underwater. Lanterns aren't destroyed when they run out of fuel. Refill lanterns with candles and lamps with oil.
- [**Torch Hotkey**](https://www.nexusmods.com/morrowind/mods/45747?) by Remiros, Greatness7, and NullCascade: adds "C" as a dedicated hotkey for light sources. It will equip/unequip the first light source in your inventory when pressed and prioritizes already used lights. It will also re-equip previously equipped shields, two-handed weapons and ranged weapons.
- [**Wings of Will - Willpower Based Levitation Speed**](https://www.nexusmods.com/morrowind/mods/46626) by Sataniel: levitation speed is now based on Willpower attribute instead of Speed. Calculations are otherwise the same.

### GAMEPLAY MWSE ABOT

These mods all belong to the same author, abot. They receive a dedicated section because they need to be installed before **MWSEabotlib** for all of them to work correctly.

- [**Smart Ammo**](https://www.nexusmods.com/morrowind/mods/47383?) by abot: ammo autoequip while bow/crossbow/thrown weapon readied. It will remember and prefer last hand-picked ammo if pressing Alt while equipping it.
- [**Loading Doors Lock Tune**](https://www.nexusmods.com/morrowind/mods/46094) by abot: automatically synchronizes linked doors locked/unlocked state on activate, lock/unlock by spell, unlock by lockpick, key. Makes loading doors play close sound a short time after opening.
- [**Smart Map**](https://www.nexusmods.com/morrowind/mods/46634) by abot: automatically switches between the local and world map depending on user configuration.
- [**MWSEabotlib**](https://www.nexusmods.com/morrowind/mods/47717) by abot: up-to-date **abot\lib.lua**, shared by all of the above mods.

## GAME BALANCE

These gameplay mods seek to improve deficient aspects of the game's balance, such as the overabundace of overpowered equipment, how easy it is to get it, or the rebalance of the game's official expansions which were originally designed with an end-game character in mind.

- [**Tribunal Rebalance**](https://www.nexusmods.com/morrowind/mods/45713) by mort: rebalances Tribunal as if it shipped with Morrowind.
- [**Bloodmoon Rebalance**](https://www.nexusmods.com/morrowind/mods/45714) by mort: rebalances Bloodmoon as if it shipped with Morrowind.
- [**Morrowind Anti-Cheese**](https://www.mediafire.com/file/dgk6tqjzm4ebj67/Morrowind_Anti-Cheese_v1.2_%28Modding_Morrowind%29.zip/file) by Remiros and Half11: fixes the biggest exploits and balance issues in the game.
  - I've edited this mod for compatibility with **Ownership Overhaul**. [**You can find the original mod here.**](https://www.nexusmods.com/morrowind/mods/47305)
- [**Better Balanced Booze**](https://www.nexusmods.com/morrowind/mods/45844) by mort: rebalances alcohol so that it is less effective than potions.
  - Only install the **Better Balanced Booze - Heavy Drinker Mode** main file.

### CLEANING PLUGINS

The following plugins are dirty and require cleaning. [Follow the instructions here on how to clean plugins.](https://github.com/Sigourn/morrowind-improved/blob/master/mwtools.md#cleaning-plugins)

- **Morrowind Anti-Cheese.ESP**
  - Clean with TESTool and tes3cmd.

### GAME BALANCE MWSE

These gameplay mods require MWSE to work properly. Most importantly, they deal with particularly broken gameplay mechanics.

- [**Controlled Consumption**](https://www.nexusmods.com/morrowind/mods/45624) by NullCascade: provides a configurable restriction on the amount of potions the player can drink at any one time, removing one of the largest exploits in the game.
- [**Harder Barter**](https://www.nexusmods.com/morrowind/mods/46188) by mort: dynamically adjusts how much merchants will pay for items. Expensive items will be much less valuable while cheap items will be more or less the same price. Pluginless, compatible with everything.
  - MO2 will tell you there's no game data on top level. 
    - Right click **Data Files** and click **Set data directory**. Click **OK**.
- [**Limited Leaping**](https://www.nexusmods.com/morrowind/mods/46299) by NullCascade: puts optional restrictions on jumping, including a cooldown and/or minimum fatigue.

## DIALOGUE

For a dialogue mod to be included in this list, it must address a considerable problem with the game's existing dialogue. As it is, the most noticeable issues with Morrowind's dialogue (that aren't addressed by the **Internal logic** module) are minor annoyances or issues with its repetition.

- [**GreetDistanceReducer**](https://www.nexusmods.com/morrowind/mods/43994) by helswake: NPCs will not shout at you as often when you walk by. They will still greet you, though, you just have to be a bit closer.
- [**Greetings for No Lore**](https://www.nexusmods.com/morrowind/mods/46063) by Caeris: replaces the three standard No Lore greetings with over sixty new ones. 
- [**Outfit Greetings Tweaked**](https://www.nexusmods.com/morrowind/mods/46066?) by Anille: greetings regarding clothes are now limited to clothiers, nobles and snooty High Elves.

## FINISHING TOUCHES

### MANUAL CONFLICT RESOLUTION

The following plugins will conflict with each other. [Follow the instructions here on how to delete records using TESAME.](https://github.com/Sigourn/morrowind-improved/blob/master/mwtools.md#tesame)

- Delete the following records from **Yet Another Guard Diversity - Regular.esp** for compatibility with **Morrowind Anti-Cheese.esp**:
    - Cell **Balmora, Eastern Guard Tower**
    - This ensures there aren't new instances of guards in the Eastern Guard Tower.

### ADJUSTING YOUR LOAD ORDER

Before running the automated conflict resolution tools, we need to confirm your installed mods and plugins are in the right order. [**Follow the mod order and load order in this page**](https://github.com/Sigourn/morrowind-improved/blob/master/moddingmworder.md) and adjust your mod installation order and plugin load order accordingly before proceeding to the next step.

### AUTOMATED CONFLICT RESOLUTION

TES3Merge lets us merge the objects in our active plugins in order to reduce conflicts, generating a **Merged Objects.esp** file which we will have to place at the end of our load order. This is very useful when, for example, you have a mod that modifies the stats on the Glass Armor while another modifies how it looks like: TES3Merge will merge both changes into a single plugin.

- Run TES3Merge in MO2. Once it's finished, press any key to exit.
- **Merged Objects.esp** will now be present at the end of your load order.

TESTool lets us merge the leveled lists in our active plugins in order to reduce conflicts, generating a **Merged_Leveled_Lists.esp** file which we will have to place at the end of our load order. This is very useful when, for example, you have a mod that adds certain weapons for sale to vendor leveled lists, and another mod also does the same.

- Run TESTool in MO2.
- A window will pop up, asking you if you want to use your Morrowind root folder instead of registry settings. Click **Yes**.
- Select **Merge Leveled Lists for active plugins** and click **Execute**.
- Close the program. **Merged_Leveled_Lists.esp** will now be present at the end of your load order.

### SYNCHRONIZING MOD MASTERS

Wrye Mash lets us synchronize the masters of mods we have installed. This will prevent certain error messages from popping up when launching the game.

- Run WryeMash in MO2.
- In the **Mods** tab, you will see a list with all your plugins, both active and inactive. Plugins that do not need to have their masters synchronized have a **green box** next to them. Those that do need to have their masters synchronized will have a box of a different color.
- Click on the faulty plugin, and a panel to the right will display the plugin's masters. Right click on either of them, and an **Update Masters** window will appear. Click **Yes**. 
- Once the window has closed, click on the **Save** button further below the same panel.

### RUNNING DISTANT LAND

MGE XE's Distant Land setup should be re-run. If you followed the steps [in this section](https://github.com/Sigourn/morrowind-improved/blob/master/setup.md#distant-land-tab) earlier, the process will be much easier.

- Run MGE XE in MO2.
- In the **Distant Land** tab, click **Distant land generator wizard**.
- Click **Select all**, and then **Continue**.
- Click **Run above steps using saved / default settings**.
- Once the statics have been created, simply click **Finish**.

### IN-GAME CONFIGURATION

Unless explicitly stated, configure these mods through the in-game **Mod Configuration** menu.

**Book Pickup**
- Set **Pickup by default?** to **No**.

**Clock Block**
- Set **Clock type** to **Game time**.

**Continue**
- Set **Hide Credits Button** and **Hide New Game Button (In Game)** to **Yes**.

**Essential Indicators**
- In the **General Settings** tab you can disable the features of the mod. I personally prefer playing with all settings off minus the following:
  - Enable Ownership Indicator. 
  - Enable Sneak Indicator.
  - Enable Messages.
  - Enable Tooltip for Quest Items.
- The remaining tabs offer additional configuration options. Feel free to configure them as you wish.

**Less Aggressive Creatures**
- In the **Peaceful Creatures Whitelist** tab, add the following creatures to the **Blocked** list:
  - cliff racer
  - cliff racer_diseased
  - mudcrab
  - mudcrab_diseased
  - rat
  - rat_diseased

**Let There Be Darkness - Lua Lighting Overhaul**
- In the **General and Cell Settings** tab, set **Cell lighting value overrides** to **NONE**.
- In the **Light Settings** tab, set the **Light radius scaling** slider to **120%**.
- In the **Light Settings** tab, set **Disable lights without a mesh** to **On**.

**Putting Power in Willpower**
- Set **Allow negative Resist Bonus** to **On**.

**Security Enhanced**
- Set the **Assign Keybind for Lockpick Hotkey** key to **O** (the **L** is used by **Let There Be Darkness**).

**Shattered Stones - An Earthquake Mod**
- Access the in-game console by pressing the key to the left of the "1" key.
- Type **set fQuakeChance to 5** to reduce earthquake chance from 30% to 5%.

The mods installed in this guide and configured as mentioned above will use the following keys:

- **Quick Equip**: left click + Left Shift when clicking on inventory items will equip them or use them (in the case of consumables).
- **Kill Command**: button **K** to order attacks.
- **Scriptable Scriptures**: button **B** to switch between open and closed scriptures.
- **Security Enhanced**: buttons **O** and **P** to equip lockpicks and probes respectively.

Congratulations, your modded Morrowind installation is ready!

[Back to main page](https://github.com/Sigourn/morrowind-improved/blob/master/readme.md)
