<style>
/* GLOBAL FORMATTING  */

  /* Resize page to international A4 */
  .phb {
    width: 210mm;
    height: 296.8mm;
  }
  .phb:after { content: ""; }


/* TABLE OF CONTENTS  */

  /* toc specifically wants black text. This resets the headers*/
  .toc a {
    color: inherit !important;
  }
  /* Allow dot leaders to fill remaining space but not overlap */
  .toc li span:nth-child(2) {
    width: auto;
    overflow: hidden;
    white-space: nowrap;
    display: block;
  }
  .toc li span:nth-child(2):after {
    font-family: BookSanity;
    font-size: 0.317cm;
    font-weight: normal;
    color: black;
    content:
      " ........................................"
      "........................................."
      ".........................................";
    }

  /* Style TOC page numbers*/
  .toc li span:first-child {
    float: right;
    font-family: BookSanity;
    font-size: 0.317cm;
    font-weight: normal;
    color: black;
    margin-left: 1px;
  }

  /* Adjust TOC H3 styles */
  .toc li h3 span:nth-child(2):after {
  	content: " ";
  }
  .toc li h3 {
    margin-bottom: 4px !important;
    margin-top: 10px !important;
    line-height: initial !important;
  }
  .toc li h3 span:first-child {
  	line-height: 1.8em !important;
  }

  /* Reduce TOC list indentation*/
  .toc ul ul {
  	margin-left: 10px !important;
  }
  .toc>ul>li {
    margin-bottom: initial !important;
  }


/* TABLES AND BLOCKS */

  /* Clear internal padding and add gap above for green note blocks*/
  .phb blockquote {
    padding-left: 0px;
    padding-right: 0px;
  }
  .phb blockquote { margin-top: 1em;
  }


/* INK BLOT STYLES */

  /* Root style for inkblots. Use alone, or together with
  one of the inkb lotstyle classes below. Essentially:
  <img url='{url}' class='inkblot inkblot-blue' />
  */
  .inkblot {
    position: absolute;
    mix-blend-mode: multiply;
    opacity: 0.6;
  }

  .inkblot-blue {
    filter: hue-rotate(190deg) saturate(120%)
  }

  .inkblot-green {
    filter: hue-rotate(120deg)
  }

</style>

<style>
/* Background */
  .phb{ background-image: url('https://gmbinder.com/images/KN1O92T.png') }
  .phb{ background-size: cover }

/* Notes */
  .phb section blockquote {background-color: #f6e5d4}
  .phb hr + section blockquote tr:nth-child(odd) td {background-color: transparent;}

/* Tables */
  table tr:nth-child(odd) td {background-color: #cccccc}

/* Footer */
  .phb .pageNumber {color: rgba(0, 0, 0, 0.5)}
  .phb .footnote {color: rgba(0, 0, 0, 0.5)}
  .phb:nth-child(odd):after{ 
    content          : '';
    position         : absolute;
    bottom           : -7px;
    left             : 10px;
    z-index          : -1;
    height           : 336px;
    width            : 100%;
    background-image : url('https://www.gmbinder.com/images/bNTz1nk.png');
    background-size  : cover;
}

.phb:nth-child(even):after{ 
    content          : '';
    position         : absolute;
    bottom           : -7px;
    left             : -10px;
    z-index          : -1;
    height           : 336px;
    width            : 100%;
    background-image : url('https://www.gmbinder.com/images/6NCzAN0.png');
    background-size  : cover;
}

/* Page Number */
.phb .pageNumber{
    position   : absolute;
    bottom     : 30px;
    width      : 50px;
    text-align : center;
}
.phb:nth-child(even) .pageNumber{
    left      : 12px;
}
.phb:nth-child(odd) .pageNumber{
    right      : 12px;
}

.phb .pageNumber.auto{
    position   : absolute;
    bottom     : 41px;
    width      : 50px;
    text-align : center;
}
.phb:nth-child(even) .pageNumber.auto{
    left[text](http://address "title")      : 12px;
}
.phb:nth-child(odd) .pageNumber.auto{
    right      : 12px;
}

/* INK BLOT STYLES */

  /* Root style for inkblots. Use alone, or together with
  one of the inkb lotstyle classes below. Essentially:
  <img url='{url}' class='inkblot inkblot-blue' />
  */
  .inkblot {
    position: absolute;
    mix-blend-mode: multiply;
    opacity: 0.6;}

  .inkblot-blue {
    filter: hue-rotate(190deg) saturate(120%)}

  .inkblot-green {
    filter: hue-rotate(120deg) }

</style>

<style>
  .phb#p1:after { display:none; }
</style>

## Races
<br> **Title:** Grummle Race
<br> **Creator:** Nagash 
<br> **Date Shared:** 03/06/2020
<br> **Links:** 
[Grummle Race](https://docs.google.com/document/d/1c8soks7hRXAcsTFK6LTNWFHACNXRkH4j4gjg0QPaUjQ/edit?usp=sharing )
<br>
[Grumlee Detect Balance](https://docs.google.com/spreadsheets/d/1vq1kz6PRAbw5LHy6amH-bNb4OuB8DBXL1RsZROt03Sc/edit?usp=sharing)

<br> **Title:** New Races
<br> **Creator:** Tyloris
<br> **Date Shared:** 4/13/2020
<br> **Description:** Gnome subraces, as well as a new murloc race. Potentially more in the future.
<br> **Links:** [Link](https://www.gmbinder.com/share/-M4p7mh2aKvPNqMo_k-O)

<br> **Title:** Rebalanced Races 
<br> **Creator:** Tyloris
<br> **Date Shared:** 04/29/2020
<br> **Description:** A rework of existing races to be equivalent in terms of race points. Almost all races are overall more powerful than before and hopefully are balanced in terms of each other. The title is intended to mean "rebalanced to be equal in terms of power in comparison to each other" not "the WC5e races are unbalanced, so I fixed them." This isn't necessarily better than the WC5e races, just different.

Also included are new racial feats and new races. New races include the Arakkoa, Leper and Mechagon Gnomes, High Elves, Human subraces, Mag'har Orcs, Murlocs, Vulpera, and Yaungol.
<br>**Link:** [Link](https://www.gmbinder.com/share/-M4tKMatmtJK3TjvThC)

<br> **Title:** Naaru, an Enlightened Race
<br> **Creator:** Nagash
<br> **Data Shared:** 09/01/2020 
<br> **Description:** Naaru vary from powerful beings to one-note vendors, become crystal chandeliers!
<br> **Link:** [Link](https://www.gmbinder.com/share/-MCyNul8RHKzH05xv0eV)

<br> **Title:** Grazz's Hodgepodge Races
<br> **Creator:** Grazz
<br> **Data Shared:** 11/05/2020
<br> **Description:** Grazz's hodgepodge races
Description: Various docs of races my friends and I worked to homebrew. Nothing fancy but people might be able to use them to draw inspiration for their own iterations on them. I'm not good with coding or document design so this is just a bunch of ideas slapped onto google docs.
<br> **Link:** 
<br>[Children of Cenarius](https://docs.google.com/document/d/1_r7LqL5CsrhRPMqGAzUf1h8M6XUP-q8uK5x53ahSDH4)
<br>[Mok'nathal](https://docs.google.com/document/d/1upZgXivI9DLg3VBaaoUi1eSoMRvriMBoiPMeaQkFA7c)
<br>[Drogbar](https://docs.google.com/document/d/1VA5qTqU7sWZ5sN1EbPUZRtsMqOt5SVpxXZPFPvMHOEQ)
<br>[Ethereal](hWAdxDCuY-DvjiL_Wp3_YPMZY0DMYqTQ)
<br>[Furbolg](https://docs.google.com/document/d/1_8ecFuHLe-R251KMW1EU3qjXzR6QVQfvdiCHNdtrLDc)
<br>[Gnoll](https://docs.google.com/document/d/1mIK7C_J0IkgIfPf2kG6KIXj1_CnEiewCX9El__dBk-w)
<br>[Half-Elf](https://docs.google.com/document/d/120MIzHjPOM7I1RzXgaRZSgKrPcIM9fbRocJPNinUVXs)
<br>[Half-Orc](https://docs.google.com/document/d/1AIa-zjeHpIgfK9sNO5bQZEOLb5ponOLiQ9F7chjkqCs)
<br>[Quilboar](https://docs.google.com/document/d/1WREWDvamvrmldLhlYGJSw99U6gjwIdI17Ha5Kx5TAsA)
<br>[Sethrak](https://docs.google.com/document/d/1E4O3F3f1ESnLEKBg5Pw4nt6k7HQvax8jm-l7AgXxpm8)
<br>[Tol'vir](https://docs.google.com/document/d/1AY-YEZo7-mQR5lmf3NFIeRO2TcnBmLyCEPQFTbJRZvw)
<br>[Tortollan](https://docs.google.com/document/d/1z2xZ_YR3FJ8nk4Jw8asJiS3Nv4n96I6R3WKSZ82PWnc )

\columnbreak

<br> **Title:** MythMaker's Shadowlands Races
<br> **Creator:** MythMaker
<br> **Data Shared:** 01/05/2021
<br> **Description:** Races from all four covenants, as well Brokers and Attendants. I have to add a picture to the final page, but it doesn't seem to be working, so I'll do it another time. It's also likely I'll add the drust.
<br> **Link:** [Link](https://www.gmbinder.com/share/-MNTZ7eq_Q-CyutkUNIy)

<br> **Title:** The Botani Race 
<br> **Creator:** Limefiend 
<br> **Data Shared:** 01/14/2021
<br> **Description:** A race of primal plantfolk from Draenor
<br> **Link:** [Link](https://www.gmbinder.com/share/-MQsVpa6vA1O-_bqVd4D)

<br> **Title:** WoW RPG 3E Races
<br> **Creator:** MagusRogue 
<br> **Data Shared:** 07/25/2021 
<br> **Description:** Blood Elf and Draenei Races for the WoW RPG 3e
<br> **Link:** [Draenei](https://drive.google.com/file/d/1KUT1PPUttfoRt1hu0q-owLUX3c5wU11L/view?usp=sharing )
<br> **Link:** [Blood Elf](https://drive.google.com/file/d/1MR4zfRO9ITDfxDCtboh4Hbqj4mgyh2zm/view?usp=sharing)

<br> **Title:** Arakkoa
<br> **Creator:**  ◄βҜ►LyokoBarbossa 
<br> **Data Shared:** 10/22/2021
<br> **Description:** Arrakoa race
<br> **Link:** [Link](https://drive.google.com/file/d/1Fky6UdPNVwdTmdi8x24CZa0MbmdHgW03/view?usp=drivesd)

\pagebreak

## Classes
<br> **Title:** WC5e Death Knight Rework v0.1
<br> **Creator:** Tyloris
<br> **Date Shared:** 03/26/2020
<br> **Links:** 
[Link](https://www.gmbinder.com/share/-M3OWX0ypfj8t_StcWXd)

<br> **Title:** Hunter Rework
<br> **Creator:** Tyloris
<br> **Date Shared:** 04/20/2020
<br> **Description:** There's been some discussion about reworking the hunter class to fill dead levels and bring it up to par with it's core equivalent, the ranger. This is an attempt to do so. Since a lot of it is pulled from the 3.0 document, new sections are italicized and/or bolded. Some old ability names have been changed to avoid confusion.
<br> **Links:** [Link](https://www.gmbinder.com/share/-M557ljXjEZYS7ktOV77)

<br> **Title:** WoW Classes, Blackhack Edition 
<br> **Creator:** Alzenrider
<br> **Date Shared:** 05/23/2020
<br> **Description:** Given that my DM was unsatisfied with the direction the current 3.0 classes are taking, the joke "We should make our own versions, with blackjack and hookers" became a thing and then we actually did it. This was worked on by 3 people, each with different amount of experience and knowledge regariding WoW and 5e. 
After blatantly copy pasting the code from Jih's Dmhub account and ripping of abilities from Silverblade's version being inspired by the current 3.0 and hombrews we created our own version that we'll be using in our own game and we decided to show everyone what we have done in hopes of inspiring people to create their own works or giving ideas to the main 3.0 team. Some of the classes saw little change from their 3.0 versions, such as the paladin and warrior, while others recieved extensive rework such as Demon Hunter and Mage.

Warning: Some of the classes, such as mage and warlock, were intentially overtuned to represent their power level in the WoW lore.
<br> **Link:** [Link](https://drive.google.com/open?id=1vIY8EEG2MZ1s0YjPVobJqy7s5dsxITGc )

<br> **Title:** Alzenrider's Necromancer 
<br> **Creator:** Alzenrider
<br> **Date Shared:** 07/14/2020
<br> **Description:** Created out of wanting to make a class for the remain power on the cosmology chart. Features three specs, focused on dealing unhealable damage, traditional minion swarming, and being the closest thing to a tank a no armor 1d6 class can be. Meant to work with the 3.0 classes and not my previous Blackjack Edition classes. 
<br> **Link:** [Link](https://drive.google.com/file/d/1WdGK8yBCEgGGHeDFfDvZVxnTc_xIkETJ/view?usp=sharing)

<br> **Title:** Silverblade's Warlock (Redux)
<br> **Creator:** Silverblad
<br> **Data Shared:** 8/12/2020 
<br> **Description:** Long time, no homebrew! While I've been saving my new content for a big reveal coming Soon(TM), there was enough interest in my revised warlock that I wanted to share it. Compared to my previous warlock, I wanted to move closer to core 5E warlock design (welcome back invocations), while deemphasizing the class's role as a semi-martial striker and increasing its capabilities as a caster. If references are off, it's because this will eventually fit into a larger compendium. Updated 8/20: new affliction based on collaboration with Auvreannia, some new destruction spells designed to work well with Havoc, minor fixes and changes, and the completion of greater demons.
<br> **Link:** [Link](https://drive.google.com/file/d/1LpzZ0q-RYJroGN7qj4EB844WL3hJnpYC/view?usp=sharing)

<br> **Title:** Sammy Priest Rework
<br> **Creator:** Sammy 
<br> **Data Shared:** 10/21/2020
<br> **Description:** Following on from my Priest rework, I've taken some feedback on board and now have a completed version that is actually readable. 

Major changes are: AC boost through Inner Fire, a slight reduction in power for Faith Points in favour for some new, later game abilities : Miraculous Memory and Prayer to the Beyond

All subclasses have had a makeover with a new 'Embrace Calling' ability that functions like Channel Divinity, with a main goal of making Holy and Discipline less heal-centric, and Shadow no longer has to keep track of how close to madness they are.

Also some minor alterations to the spell list to give more utility abilities, and making the subclass spells more distinct.
<br> **Link:** [Link](https://homebrewery.naturalcrit.com/share/igaAeCQ_UUzx)

<br> **Title:** PrismCat's Lich Base Class
<br> **Creator:**  PrismCat
<br> **Data Shared:** 03/13/2021
<br> **Description:** Level 1-20 Lich Base Class.
I've played the Warcraft and World of Warcraft d20 rpgs for quite some time, based on D&D 3.5. I was going to make it into a 15 level prestige class like Death Knight and Demon Hunter, but they are being updated into a base class. So I went all in for a full 1-20 class as well.

You can convert an existing Mage or Warlock into a Lich, or start at level 1 as a new Lich who is still recovering from the transformation process and must build back their power.

Enjoy!!

"In the Lich King's name!"
<br> **Link:** [Link](https://www.gmbinder.com/share/-MVJ6rl0PFrh4EAr2F1B)

\pagebreak

## Subclasses

<br> **Title:** Magical Study: Astromancy 
<br> **Creator:** Acely
<br> **Date Shared:** 04/07/2020
<br> **Description:** It's been a while since I did some homebrewing, so I think it was about time I remedied that fact. Since mages do not really have many if at all racial subclasses that I was interested in making, I instead decided to try my hands non-restricted subclass and make Study of Astromancy. Enjoy!
<br> **Links:** [Link](https://www.gmbinder.com/share/-M4JWyIANalgJJMo1cox)

<br> **Title:** Sacred Path: Zeal
<br> **Creator:** Acely
<br> **Date Shared:** 04/10/2020
<br> **Description:** At it again!
Since Scarlet Crusaders have very little distinctive abilities to their name, mostly they just use generic abilities, I had to be a bit creative. So, the Path of Zeal has focus on damage dealing (By fire, be purged!) as well as a bit supporting to your allies damage dealing and fighting capabilities. Plus I had to make being resurrected to be easier because it's one of the Crusade's iconic things.
<br> **Link:** [Link](https://www.gmbinder.com/share/-M4Yoiw4U_xlhsm4g--)

<br> **Title:** Mythmaker's Transcendent Shamanic Binding
<br> **Creator:** MythMaker 
<br> **Data Shared:** 10/15/2020
<br> **Description:** This one takes a little explaining, this is a pandaren-specific subclass for shamans, based off of summoning a pandaren elemental spirit.
<br> **Link:** [Link](https://www.gmbinder.com/share/-MHEFCCDpd0_RfP9erFw)

<br> **Title:** Expanded Clerical Domains
<br> **Creator:** Grazz  
<br> **Data Shared:** 11/16/2020 
<br> **Description:** While the project has the Priest. For those who wanted to still use cleric in their campaigns myself and my collaborators homebrewed 5 domains (Earth, Moon, Sea, Sky, and Venom). Moon Domain takes spells from the druid spell list.
<br> **Link:** [Link](https://drive.google.com/drive/u/0/folders/1uhnHhx3_YSvaseejttTMrnzj6u8MxKvI)

<br> **Title:** Mage: Arcane Study [Homebrewed Version]
<br> **Creator:** LordWillmonte(Sam) 
<br> **Data Shared:** 10/25/2021 
<br> **Description:** Got some inspiration and decided to update my approach to Arcane Mage, considering 3.0 test version of Mage class. Main Focus of my version is to show the flexibility of Arcane Mages with their skills of manipulating raw magic, which is arcane. My plan was to keep it simple, yet enjoyable and unique enough to play. 

Would be glad to hear what do you think about it! (also, ready to answer any questions regarding the content :P)
<br> **Link:** [Link](https://www.gmbinder.com/share/-LmZLLILmtizVfOD0LxI)

<br> **Title:** Divine Calling: Elune
<br> **Creator:**  AsperTheGhost 
<br> **Data Shared:** 01/01/2022
<br> **Description:** An alternative to the usual three Priest Callings for use with the 3.0 Priest document. It's based on the unique Priest racials available to Night Elves in World of Warcraft. My first attempt at homebrewing. Edit: Feedback would be greatly appreciated. Even though its Homebrew I would like this to be balanced and usable.
<br> **Link:** [Link](https://www.gmbinder.com/share/-MsH2LmC4ow_dPVB6Dgz)

\pagebreak

## Compendiums

<br> **Title:** Silverblade's WC5E Classes & Other Assorted Goodies
<br> **Creator:** Silverblade
<br> **Date Shared:** 3/31/2020
<br> **Description:** As a side project, I have been designing my own version of Warcraft classes (and probably some other stuff eventually), inspired by but not officially affiliated with the official WC5E project. You can access all of my revisions, as well as a design manifesto, at the link below. A huge thank-you to the designers and contributors of the WC5E project; without their hard work and excellent foundation, none of this would have been possible!
<br> **Links:** 
[Link](https://drive.google.com/drive/folders/1X_UJ7ynxnejgZ_S6CJHagsnBQlf_SoWp)

<br> **Title:** Tyloris' WC5e Content
<br> **Creator:** Tyloris 
<br> **Date Shared:** 05/13/2020
<br> **Description:** In order to avoid bogging down the channel with a bunch of individual creations, I've turned the most finished content into a single document. 
<br> **Link:** [Link](https://www.gmbinder.com/share/-M7ALlfMw2SKSxxMsMwC) 

<br> **Title:** WC5e - MythMaker's Unfathomable Tome of the Black Empire 
<br> **Creator:** Mythmaker
<br> **Date Shared:** 07/15/2020 
<br> **Description:** In the pursuit of breaking the game, I have delved into the nightmare realm of Ny'alotha and brought back a few character options for use in your game. Except they won't be used in any game, probably, because they are all broken as all hell. It includes Nerubians, Qiraji, Mantids, N'raqi, and K'thir. It will also have a couple subclasses and other character options.
<br> **Link:** [Link](https://www.gmbinder.com/share/-MCCfEG6R1xDONQ2EpgQ)

<br> **Title:**  Silverblade's Champions of Azeroth
<br> **Creator:**  Silverblade 
<br> **Data Shared:** 01/23/2021
<br> **Description:** A project long in the making, this is an alternative take on some of the fundamental elements of WC5E, drawing on my own design sensibilities, priorities, and opinions (5E and Warcraft alike). After many internal iterations and revisions, I'm finally ready to show it off in an 'alpha' state, and hopefully receive some wider feedback that might help me improve things further (and fix the inevitable typos and errors). Note that this document contains only 'vanilla' Warcraft content; I plan to do additional supplements with more content, after learning from the reception and feedback of this core Champions of Azeroth supplement. To be clear: this is a different take on Warcraft in 5E, and not necessarily better or worse than the main WC5E project, which I have the utmost respect and admiration for. You can read more about my design goals and philosophy in the "00 - Cover+Intro+Back" pdf. Please, take a look, and let me know what you think!
<br> **Link:** [Link](https://drive.google.com/drive/folders/1CmUbMBEaKgvDy2qm_emJDjbpt2rVE_uE?usp=sharing)

<br> **Title:** Hearthstone (the item, not the game)
<br> **Creator:**  Lintian
<br> **Data Shared:** 02/09/2021
<br> **Description:** A fairly straightforward one, admittedly.
<br> **Link:** [Link](https://www.gmbinder.com/share/-MT6lRzEzdzCKfA9eTrS)

<br> **Title:** Silverblade's Champions of Outland
<br> **Creator:**  Silverblade
<br> **Data Shared:** 02/17/2021
<br> **Description:** New and revised content related to Outland and all things demonic, including The Burning Crusade races and a new demon hunter class focusing on unleashing the demon within. This is building off my previously-linked Champions of Azeroth project, though it should be usable with other WC5E content with potentially minimal alteration. Please, take a look, and let me know what you think! 
<br> **Link:** [Link](https://drive.google.com/file/d/1glHE5_sSPK5C8k6HYnaHlGRcK1QvEKPl/)

<br> **Title:** Silverblade's Champions of Northrend
<br> **Creator:**  Silverblade
<br> **Data Shared:** 03/09/2021
<br> **Description:** New and revised content related to Northrend, including a few new races (including a universal undead subrace) and a lightly-revised death knight. This is building off my previously-linked Champions of Azeroth project, though it should be usable with other WC5E content with potentially minimal alteration. Please, take a look, and let me know what you think! On a personal note, this is the last such supplement I had pretty much ready to go (sorry monks), and on reflection I think it's best to take the rest of my Champions project in a different direction. As such, this is the last of these supplements I expect to post here. After any initial feedback, I'll leave these documents in their present forms for posterity. If you want to keep informed of my future updates and progress, please let me know, and I'll be sure to keep you in the loop. 
<br> **Link:** [Link](https://drive.google.com/file/d/1OBoyu669MtcE_fi5CdUMNK5hmvPBdPa1)

<br> **Title:** PrismCat's Sea Compendium
<br> **Creator:**  PrismCat 
<br> **Data Shared:** 04/28/2021
<br> **Description:** Murloc, Naga, and Tuskarr Player Races, and Monster Blocks for Hydras, Sea Giants, and Tuskarr.
I did have more, and had more planned, but there were some issues with GMBinder so this will have to do :)
<br> **Link:** [Link](https://www.gmbinder.com/share/-MZ03iZ7YWT2HG6xNZBB)

<br> **Title:** PrismCat's Fel Collection
<br> **Creator:**  PrismCat 
<br> **Data Shared:** 06/01/2021
<br> **Description:** Corrupted and Fel-sworn options/abilities for Characters to take, monster blocks for Helboar, Succubus, Felguards, Dreadlords, & Lord Kazzak, and The Secret Cow Level!! complete with two unique magic items
<br> **Link:** [Link](https://www.gmbinder.com/share/-M_CCfJwp8RtGlyQl__t)

<br> **Title:** Forest Trolls vs. High Elves
<br> **Creator:**  PrismCat 
<br> **Data Shared:** 08/28/2021
<br> **Description:** Hunter & Warrior options and Archetypes for Forest Trolls and High Elves.
Related Magic Items.
<br> **Link:** [Link](https://www.gmbinder.com/share/-MiF-XqZoFVawKK_qQcI)

\pagebreak

## Magic Items, Equipment, and Spells 

<br> **Title:** Legendary Weapons of Azeroth v2
<br> **Creator:** Tyloris
<br> **Date Shared:** 04/06/2020
<br> **Description:** I've been working on magic items for a while now. Here's one of the sections of the final document, for review. It's titled 'Legendary Weapons of Azeroth', since the weapons are for the most part Legendary items. Only Benediction and Rhok'delar are not, since they are 'quasi-legendary' items, in my opinion.
<br> **Links:** [Link](https://www.gmbinder.com/share/-M4FNvCOdJfdG_Zu0RPY)

<br> **Title:** Extraordinary Equipment
<br> **Creator:** Tyloris
<br> **Date Shared:** 04/13/2020
<br> **Description:** New items for use in the WC5e setting. Very much a work in progress, but I wanted to get some feedback and suggestions while I am working on it.
<br> **Links:** [Link](https://www.gmbinder.com/share/-M2qIUSQvnbiTQaPmGEp)

<br> **Title:** Grasping Gauntlet?
<br> **Creator:** MythMaker 
<br> **Data Shared:** 10/15/2020
<br> **Description:** Don't know if I ever shared this, but Shadowlands have gauntlet-looking crawling claws that work perfectly as these versions I made a while ago.
<br> **Link:** [Link](https://www.gmbinder.com/share/-M9zz-Yt7gLZlV64GfOm)

<br> **Title:** Elune's Lantern
<br> **Creator:** Lintian 
<br> **Data Shared:** 11/19/2020
<br> **Description:** A magic item description I wrote for my campaign.
<br> **Link:** [Link](https://www.gmbinder.com/share/-MMWOpE2RxfQrqJSv1vN)

<br> **Title:** Acely's Artifacts - WIP
<br> **Creator:** Acely 
<br> **Data Shared:** 01/04/2021 
<br> **Description:** A handful of the Legion artifacts (so far) I tinkered in the freetime, feedback welcome.
<br> **Link:** [Link](https://www.gmbinder.com/share/-MQCXhgdTXEztNhF0UJL)

<br> **Title:** Puzzle Box of Yogg-Saron
<br> **Creator:**  Lintian
<br> **Data Shared:** 02/24/2021
<br> **Description:** A humorous, "just for fun" magic item modeled after Hearthstone's take on it.
<br> **Link:** [Link](https://www.gmbinder.com/share/-MUJThImQZ_gttPvbt_7)

<br> **Title:** Wrenchcalibur, updated.
<br> **Creator:** Mythmaker
<br> **Data Shared:** 10/20/2021
<br> **Description:** Hi. My first TotM submission, Wrenchcalibur, had some art that broke, so I fixed it all up. I noticed the early submissions in totm-archives were removed somehow, so I opted to resubmitting it here.
<br> **Link:** [Link](https://www.gmbinder.com/share/-MQIpiD70HXzV8vO4gTd)

<br> **Title:** Curios of Azeroth
<br> **Creator:**  Elly 
<br> **Data Shared:** 12/16/2021
<br> **Description:** 7 common items, 26 uncommons, 43 rares, 19 very rares, 12 legendaries, 4 artifacts, and 8 Item Sets (4 rare, 4 very rare). It's intended for 'base' 5e rules rather than WC5e but converting shouldn't require significant effort, if any. The mention of Shaman is for a subclass I've got on the backburner. 
<br> **Link:** [Link](https://homebrewery.naturalcrit.com/share/dMbfDOTkSHRK)

<br> **Title:** Alchemy of Azeroth
<br> **Creator:**  Elly 
<br> **Data Shared:** 12/22/2021
<br> **Description:** 40+ consumable potions and a few weapon oils adapted from WoW's alchemy list.
<br> **Link:** [Link](https://homebrewery.naturalcrit.com/share/pCCGVMjSh8hZ)

<br> **Title:** Acely's Anxious Addenda to Arcane Arts
<br> **Creator:** Acely
<br> **Data Shared:** 11/03/2020
<br> **Description:** Just some spells I cobbled together, some that I felt like their absence was too much to bear, some that I just thought would be fun to experiment with. Probably not very well tuned for balance (yet, critical eye appreciated), but might work as proofs of concept.
<br> **Link:** [Link](https://www.gmbinder.com/share/-MLCH3ecBdjWglFXuq7-)

\pagebreak

## Monsters 

<br> **Title:** Warcraft 3 Creeps/Creature Simple Stat Blocks
<br> **Creator:** GoC45
<br> **Date Shared:** 04/19/2020
<br> **Description:** A simple little statblock using a template I developed for ease of tracking and editing the stats, with a creature based on the Warcraft 3 creep of the same name as referrence. Will try to add more creatures to this as well.
<br> **Links:** [Link](https://docs.google.com/spreadsheets/d/1L8IdhL3zVDo9hqwOUpzusOW6Aqu8LLiXQ9uD_21TQcM/edit?usp=sharing)

<br> **Title:** MythMaker's Wolpertinger. 
<br> **Creator:** Mythmaker
<br> **Date Shared:** 6/18/2020 
<br> **Description:** It's a Wolpertinger, what do you want from me? Usable as a familiar.
<br> **Link:** [Link](https://www.gmbinder.com/share/-M3EOEYkxoGT2-uEEu5I)

<br> **Title:** ICC Bosses
<br> **Creator:** Llamadom
<br> **Date Shared:** 06/20/2020 
<br> **Description:** All the ICC bosses Ive done so far!! Have done all of them except Marrowgar, Gunship, Professor Putricide, and Valitheria. Also, some of the stat blocks are numbers-fuzzy, I just wanted critique on the mechanics over the specific numbers like AC, HP, saving DCs, etc. Also, CRs arent set in stone yet, just the ones I used to design each for in terms of prof bonus and AC
<br> **Link:** [Link](https://www.gmbinder.com/share/-M8JyvV1sAQPmnyVHgjJ)

<br> **Title:** Monsters - MythMaker's Mongrel Horde
<br> **Creator:** Mythmaker
<br> **Date Shared:** 7/27/2020
<br> **Description:** I want to make a mongrel horde campaign eventually, and I'd need higher level statblocks to add variety and perpetuate the fight against the mongrel horde! So I made these.
<br> **Link:** [Link](https://www.gmbinder.com/share/-MA6eLqZLfJQ_ISwciwe )

<br> **Title:** The Dragon Aspects
<br> **Creator:** Llamadom
<br> **Data Shared:** 08/12/2020
<br> **Description:** Creation of stat blocks of the original five Dragon Aspects, From Alexstrasza to Deathwing himself! These are just the dragons themselves, and didnt model any of the dragons after a particular in game fight (Deathwing especially). Still partially a WIP for some stat blocks and want to add more flavor text, but overall its done. Any critiques and suggestions, especially on the unfinished ones, be appreciated!
<br> **Link:** [Link](https://www.gmbinder.com/share/-MASCQQb7l38fXACTUSM<)

<br> **Title:** The Elemental Lords
<br> **Creator:** Llamadom
<br> **Data Shared:** 08/12/2020
<br> **Description:** My initial stat blocks of the Elemental Lords! Still plan on adding Mythic Actions and Traits, wanted to share the initial work I had done so far. Any critiques or additional ideas be appreciated! 
<br> **Link:** [Link](https://www.gmbinder.com/share/-MEyjwjrylxFa8YSqCVQ<)

<br> **Title:** Itty Bitty Familiar Options
<br> **Creator:** MythMaker 
<br> **Data Shared:** 09/02/2020
<br> **Description:** I made these a little while ago, battle pet-esque familiar versions of classic Warlock demons! Might add more if I feel so inclined.
<br> **Link:** [Link](https://www.gmbinder.com/share/-MFFovqu9AXjZSL5d8v1)

<br> **Title:** Human Paladin Monster Stats CR 1, 5, 10ish
<br> **Creator:**  Mirror
<br> **Data Shared:** 04/29/2021
<br> **Description:** the beginning in a long line of custom monster stats for special race/class base monster stats for low, mid, and highish level, included is image of stats and files for giffyglyph monster maker (note: .json file can be imported in vault window of maker page.) feel free to customize and improve on it, and if you have any improvements please let me know or share it. I sadly do not have experience with gmbinder, but I hope this is make it easier for someone who does and is working on a similar project. 
<br> **Link:** [Link]()

<br> **Title:** Alliance Monster Stats CR 1, 5, 10ish Classic
<br> **Creator:**  Mirror
<br> **Data Shared:**04/30/2021
<br> **Description:** Custom Alliance Race/Class variations based on classic class limitations that can be used and modify to the hearts desire via the monster maker (Note: .json file will only import in the vault tab)
<br> **Link:** [Link](https://drive.google.com/drive/folders/1B4sEXumWDLRgYylU-YkwlrjOSdwzH_fx?usp=sharing)

<br> **Title:** The Dread Devilsaur Pirate King
<br> **Creator:**  PrismCat
<br> **Data Shared:**  07/02/2021
<br> **Description:** Guess I should be it in the Archives
<br> **Link:** [Link](https://www.gmbinder.com/share/-Md_Hy9Ke0lIj0ze7V78)

<br> **Title:** 5e Monster Lore For Warcraft Universe
<br> **Creator:**  Grazz 
<br> **Data Shared:** 07/05/2021
<br> **Description:**  Over the past 2-3 months I've been going through official 5e monsters that I think could fit, either aesthetically or thematically, in the Warcraft setting and rewriting or editing their lore to try and make them fit into the history. Some monsters have their lore absolutely unchanged due to being generic enough as to fit into any setting and just literally copy/pasted into the document to keep things tidy for my own game and others just have wording tweaked for the Warcraft universe and others still just have their entire lore rewritten. 
Note: some of the lore written deals with the cosmology in the direction I've decided to take it and some retcons and headcanon is introduced from my own internal expansion on the universe.
<br> **Link:** [Link](https://docs.google.com/document/d/1Qg1L-3H89ugzlODceXGJ6YtA4BaQBOkFaTye9VpygDM/)

\pagebreak

## Monsters (Continued)

<br> **Title:** Satyr
<br> **Creator:** Kildrak 
<br> **Data Shared:** 09/20/2021 
<br> **Description:** Hi! I am playing, as a master, a campaign set on a journey from Durotan to Azshara just before the events of WoW Classic. Passing through Ashenvale the group had to face the Satyrs and therefore, starting from the ones in the WC5E manual, I created / modified the monsters based on those of W3.
And nothing, I felt I wanted to share them.
<br> **Link:** [Link](https://homebrewery.naturalcrit.com/share/ErkwyFeJbrKG)

<br> **Title:** The Headless Horseman
<br> **Creator:**  PrismCat 
<br> **Data Shared:** 10/31/2021
<br> **Description:** The Headless Horseman encounter (low-ish level)
<br> **Link:** [Link](https://www.gmbinder.com/share/-MnMJ7LR8syRsT9J9khO)

<br> **Title:** Scarlet Monastery Mobs
<br> **Creator:**  PrismCat 
<br> **Data Shared:** 12/01/2021
<br> **Description:**  All the mobs in Vanilla Scarlet Monastery. Made for a party of lvl 7-8 characters.

Collaboration with MythMaker, Llamadom, Lorestalker Nemzal, Siravia, & Geamros.
<br> **Link:** [Link]( https://www.gmbinder.com/share/-Mpo3MPqfGrjYm0XYIFa)

\pagebreak

## Addtional or Variant Rules 

<br> **Title:** Variant to Racial Abilities
<br> **Creator:** Bowie
<br> **Date Shared:** 05/06/2020
<br> **Description:** A shift from racial ability bonuses/ASIs to them being linked to classes and backgrounds instead. This simulates how gameplay feels, rather than how lore feels. Racial Features remain, of course, but Abilities get moved.
<br> **Link:** [Link](https://www.gmbinder.com/share/-M6fuk7fpjZj4BkoO017)

<br> **Title:** Traitor's Requiem's take on Energy Points and Combo Spenders 
<br> **Creator:** Traitor's Requiem 
<br> **Date Shared:** 06/09/2020
<br> **Description:** Exactly what it says on the Tin. Threw this together in fifteen minutes, looking for feedback.

Context: In my game, I'm intending my players to be stronger than normal. I'm not too worried about damage numbers, as they can be tweaked later. Mostly looking to see if this looks like it could work and if there are any changes to the mechanic(s) presented to make them work a little better for 5e.
<br> **Link:** [Link](https://docs.google.com/document/d/1Td9O7ao3uykjHaPyp9b0QwC9Pj7XKzYJxE6GM6KPVeE/edit?usp=sharing )

<br> **Title:** Traitor's Requiem's take on a Shaman Secondary Resource
<br> **Creator:** Traitor's Requiem
<br> **Date Shared:** 06/12/2020
<br> **Description:** Exactly what it says on the Tin. Threw this together in fifteen minutes, looking for feedback. 

Context: In my game, I'm intending my players to be stronger than normal. I'm not too worried about damage numbers, as they can be tweaked later. Mostly looking to see if this looks like it could work and if there are any changes to the mechanic presented to make them work a little better for 5e.
<br> **Link:** [Link](https://docs.google.com/document/d/1js1lppgijLDy0Oub_tx8R2jwOt2wad1IdI5jC6pSAAo/edit?usp=sharing)

<br> **Title:** Silverblade's Expanded Crafting
<br> **Creator:** Silverblade 
<br> **Data Shared:** 01/19/2021
<br> **Description:** Guidelines for adding new depth and gameplay to the existing 5E crafting rules presented in Xanathar's Guide to Everything, including a system to build your own magic items. This is a more formal write-up of the crafting rules I use in my games, and they work for me--maybe they'll work for you too! In particular, they really are guidelines rather than a guide, and are intending to provide structure and inspiration for how crafting might work in 5E games, rather than a completely comprehensive system. This is intentional; I want to encourage DMs and players to work together, creatively and collaboratively, to accomplish the crafting experience they want. This document simply provides a good starting point for such conversations. (Note: This is hardly specific to Warcraft games, but there was recent interest in crafting systems, so I thought I'd write up and offer what works for me.)
<br> **Link:** [Link](https://drive.google.com/file/d/1HvJFSxCuxySB3Zu6-ySjyY07W_wqZM-K/view?usp=sharing)

<br> **Title:** Gathering Rules
<br> **Creator:**  Muad'dib65 (Ward of Iron Dock)
<br> **Data Shared:**  04/06/2021
<br> **Description:** Included Mining as well as Herbalism and tried to integrate the current WoW MMO style levelling system. It's quite janky but hopefully someone can improve on it from here or propose something better if they haven't already. I know some people have their own systems already in place
<br> **Link:** [Link 1 ](https://drive.google.com/file/d/1WCKSNRP-DShHF6KbKzg87VMgjHiM_Xu_/view?usp=drivesdk)
<br> **Link:** [Link 2 ](https://drive.google.com/file/d/1WLI3eHPQ2hKigIaKXTG8Mf-kVT2kNPGb/view?usp=drivesdk)

\pagebreak

## Maps

<br> **Title:** Scarlet Monastery Maps
<br> **Creator:**  Tangerine 
<br> **Data Shared:** 11/06/2021
<br> **Description:** Hell yeah, got it done. 💪 Created a collection of maps from around the Scarlet Monastery, in Dungeondraft. Not everything in there just yet, a few ones from the Scarlet Halls I have not done, but it's mostly a complete set of maps from key encounters around the dungeon. 
<br> **Link:** [Link](https://drive.google.com/drive/folders/1SeC0yKeCseT7YNmajZWPfUyEIJmgfTSL)


\pagebreak

## Other 

<br> **Title:** Fantasy Grounds Class Supplemnt - Death Knight Class
<br> **Creator:** Klandaghi.Silentclaws
<br> **Date Shared:** 05/13/2020
<br> **Description:** A Fantasy Grounds Adaptation of the Death Knight v3.0 Playtest rules into the Fantasy Grounds Platform.  Requires The Official Modules for Player's Guide, Xanthar's Guide to Everything, Sword Coast Adventurer's Guide, and Unearthed Arcana to use.
<br> **Link:** [Link](https://drive.google.com/open?id=1LTWbnVFfOqOzKaW49To-2K3NxGUjJEJo)

<br> **Title:** Fantasy Grounds WC5e Mod 
<br> **Creator:** GedeonMcBain 
<br> **Data Shared:** 09/03/2020
<br> **Description:** I don't know if this is where I should post this, but I created a mod for fantasy grounds (unity) for the 3.0 content.
<br> **Link:** [Link](https://drive.google.com/file/d/1T8riVtagm4ghanAdPI6NBgpLAqicD7ZN/view?usp=sharing)

<br> **Title:** Themed Character Sheets (Horde&Alliance)
<br> **Creator:** Valten 
<br> **Data Shared:** 02/27/2021
<br> **Description:** 
<br> **Link:** [Link](https://drive.google.com/drive/folders/1BtaZvw_TI3AFf1CrKbrUl2pM6CA1OeiT?usp=sharing)

<br> **Title:** Foundry Warcraft Theme
<br> **Creator:**  Elfonochasis 
<br> **Data Shared:** 09/03/2021
<br> **Description:** A World of Warcraft themed reskin for Foundry VTT
<br> **Link:** [Link](https://github.com/syl3r86/vtt-craft )


