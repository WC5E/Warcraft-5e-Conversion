<style>.phb{width : 210mm;height : 296.8mm;} .phb:after {content: "";} </style>
<style>.phb hr+section blockquote { padding-left: 0px; padding-right: 0px; }</style>
<style>.phb blockquote { padding-left: 0px; padding-right: 0px; }</style>
<style> .phb blockquote { margin-top: 1em; } </style>


<style>

  /* Workaround fix for the line height displacement that GM Binder is
    experiencing right now thanks to under the hood Chromium changes */
  .phb p{ line-height: 15px; } 
  .phb blockquote p{ line-height: 14px; } 
  .phb h2{ line-height: 26px; } 
  .phb h3{ line-height: 19px; } 
  .phb h4{ line-height: 15px; padding-bottom: 3px; } 
  .phb h5{ line-height: 17px; } 
  th, td { line-height: 14px; }


/* TABLES AND BLOCKS */

  /* Clear internal padding and add gap above for green note blocks*/
  .phb blockquote {
    padding-left: 0px;
    padding-right: 0px;
  }
  .phb blockquote { margin-top: 1em;
  }
  
  /* Use black tones for statblock backgrounds */
  .phb blockquote {
    box-shadow: 1px 4px 14px rgba(0,0,0,0.42);
  }
  

/* APPENDIX STYLES */

  /* Avoid upscaling first letter on an appendix page */
  .phb:nth-of-type(n+0):nth-of-type(-n+100) h1+p::first-letter {
    font-family: BookSanity;
    font-size: .317cm;
    text-rendering: optimizeLegibility;
    float: initial;
  }
  
  /* For creature statblocks within range (start and end must be specified),
  don't show a background. Used for the appendix creatures 
  !! Disabled to test appendix with standard statblock appearance
  */
  /* 
  .phb:nth-of-type(n+0):nth-of-type(-n+100) hr+section blockquote {
    background: none;
    border: none;
    box-shadow: none;
    margin-top: 12px;
    margin-bottom: 12px;
    padding-top: 6px;
    padding-bottom: 6px;
  } 
  */
  
  /* For double-wide creature statblocks that we want to have anchored to the
  bottom of the page regardless of content flow. */
  .statblock-bottom-wide {
    position:absolute;
    bottom:63px;
    right:1.7cm;
    left:1.7cm;
    margin-top:1200px;
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

/* FOOTER STYLES  */

  .phb .pageNumber { color: #7e735c; z-index:1000; }
  .phb .footnote { color: #7e735c; }
  
  .phb:nth-child(odd):after {
    content: '';
    height: 125px;
    background-image: url(https://www.gmbinder.com/images/PB8On0U.png), url('https://gmbinder.com/images/YWardeu.png');
    background-size: 120px 120px, 816px 55px;
    background-repeat: no-repeat, no-repeat;
    background-position: bottom right -10px, bottom;
  }

  /* Reversed for alternating pages */
  .phb:nth-child(even):after {
    content: '';
    height: 125px;
    background-image: url(https://www.gmbinder.com/images/PB8On0U.png), url('https://gmbinder.com/images/YWardeu.png');
    background-size: 120px 120px, 816px 55px;
    background-repeat: no-repeat, no-repeat;
    background-position: bottom right -10px, bottom;
    -webkit-transform: scaleX(-1);
    transform: scaleX(-1);
  }    


/* Monster Manual alphabetical chapter letters */

.mml-a {background-image: url(https://gmbinder.com/images/fVVv93s.png);}
.mml-b {background-image: url(https://gmbinder.com/images/21X6N0B.png);}
.mml-c {background-image: url(https://gmbinder.com/images/MvnpOWF.png);}
.mml-d {background-image: url(https://gmbinder.com/images/AFbLU4P.png);}
.mml-e {background-image: url(https://gmbinder.com/images/28NVNf9.png);}
.mml-f {background-image: url(https://gmbinder.com/images/Oyrhmqy.png);}
.mml-g {background-image: url(https://gmbinder.com/images/fRyiQn4.png);}
.mml-h {background-image: url(https://gmbinder.com/images/N8NamlT.png);}
.mml-i {background-image: url(https://gmbinder.com/images/xWI93aa.png);}
.mml-j {background-image: url(https://gmbinder.com/images/GgIzsun.png);}
.mml-k {background-image: url(https://gmbinder.com/images/OcObsWl.png);}
.mml-l {background-image: url(https://gmbinder.com/images/B7AUyR6.png);}
.mml-m {background-image: url(https://gmbinder.com/images/q4wXoxt.png);}
.mml-n {background-image: url(https://gmbinder.com/images/OJtC4w9.png);}
.mml-o {background-image: url(https://gmbinder.com/images/adeRr5d.png);}
.mml-p {background-image: url(https://gmbinder.com/images/EEhcrSR.png);}
.mml-q {background-image: url(https://gmbinder.com/images/O1AhfzL.png);}
.mml-r {background-image: url(https://gmbinder.com/images/w66eIuZ.png);}
.mml-s {background-image: url(https://gmbinder.com/images/YEoe0PP.png);}
.mml-t {background-image: url(https://gmbinder.com/images/7Bk9D35.png);}
.mml-u {background-image: url(https://gmbinder.com/images/uVJZYUg.png);}
.mml-v {background-image: url(https://gmbinder.com/images/gKjngey.png);}
.mml-w {background-image: url(https://gmbinder.com/images/14WWpsC.png);}
.mml-x {background-image: url(https://gmbinder.com/images/ojIYjh0.png);}
.mml-y {background-image: url(https://gmbinder.com/images/Gi1ePwY.png);}
.mml-z {background-image: url(https://gmbinder.com/images/0ZTFNVs.png);}

/* letter at bottom of page */

  .pageLetter {
    font-family:;
    position:absolute;
    right:25px;
    bottom:87.5px;
    color:#673e1c;
    z-index:1000;
    font-size:135%;
  }

  .phb:nth-child(even) .pageLetter {
    left:25px;
  }
 
</style>

# Nonplayer Characters

This is a partial release from the *Warcraft 5E* project's *Manual of Monsters*; a small group of friends having fun writing and sharing *Warcraft* material for D&D 5th Edition. 

We're mainly a group of friends looking to have fun with this, as our little hobby project with big ambitions. It is entirely out of our own time, and entirely for free. 

If you want to see more, follow the links at the bottom of this page. 

##### About these statblocks

This document contains statistics for different humanoid nonplayer characters (NPCs) that might be encountered during an adventure. 

Many of these statblocks are taken from the Dungeons & Dragons SRD 5.1, following guidelines on copying and modifying SRD content. From there, we've rewritten them with new features, new spell lists, and new text to better work for us as Warcraft NPCs. 

We also have a lot of more stand-out unique statblocks both made and otherwise planned, here we just wanted to have a lot of more typical NPCs flavoured for the setting. Check out the project link above for that.

At some point, we'd like to have an overview of what could be added to an NPC to reflect different races (the statblocks are all written for medium-sized humanoids), but that is a priority some way down the line for now. 


## Contributor Credits

*Contributors listed by community usernames.*
<div style='margin-top:-10px;'></div>

<br> **Original project authors** 
<br><span style="margin-left:12px"></span> Jih, Tangerine

<br />**Current core team**
<br><span style="margin-left:12px"></span> Ace Azzermeen, Geamros, Lorestalker Nemzal,
<br><span style="margin-left:12px"></span> MagusRogue MythMaker, Nagash, Llamadom,
<br><span style="margin-left:12px"></span> Tangerine, Tyloris

<br />**Inactive & former team members**
<br><span style="margin-left:12px"></span> 123jrf, ApolloLumina, Artipo, Auvreannia, Christinekn,
<br><span style="margin-left:12px"></span> ClockWorkTank, Elenus, Jih, Prometheus, Reiga,
<br><span style="margin-left:12px"></span> Silverblade, Tseims, Wyken

<br />**Big thanks to** 
<br><span style="margin-left:12px"></span> Everyone at our community Discord and Subreddit

<br> **Also thanks to**
<br><span style="margin-left:12px"></span> This entire book was made using GM Binder. It is an
<br><span style="margin-left:12px"></span> amazing tool for creating authentic-looking homebrew
<br><span style="margin-left:12px"></span> material for 5th Edition Dungeons and Dragons. Without
<br><span style="margin-left:12px"></span> it, this project would've likely never been considered.

<br> **Based on the original D&D game created by**
<br><span style="margin-left:12px"></span> E. Gary Gygax and Dave Arneson, as well as
<br><span style="margin-left:12px"></span>Brian Blume, Rob Kuntz, James Ward and Don Kaye.

<br> **Based on the Warcraft franchise by**
<br><span style="margin-left:12px"></span> © Blizzard Entertainment


\columnbreak


## Art Credits 

<div style='margin-top:-14px;'></div>

<br />**Page 1 Art:** "Acolyte" from [Warcraft III: Reforged](https://wowpedia.fandom.com/wiki/Acolyte?file=Reforged_credits_art_13.png)
<br />**Page 2 Art:** "Archmage" by [breath-art](https://www.deviantart.com/breath-art/art/archmage-male-204726889)
<br />**Page 3 Art:** "Val'Sharah Concept" by [Phillip Zhang](https://www.artstation.com/artwork/RYen2r)
<br />**Page 4 Art:** "WoW Tribute" by [r-trigger](https://www.deviantart.com/r-trigger/art/WoW-Tribute-393940543)
<br />**Page 5 Art:** Uncaptioned troll art by [Francis Brunet](https://www.artstation.com/francisbrunet)
<br />**Page 6 Art:** "Crusader" by [Da Guo](https://bigguo.artstation.com/projects/LJl5R)
<br />**Page 7 Art:** "The Cultist" by [Rogier van de Beek](https://www.artstation.com/artwork/oG3OJ)
<br />**Page 8 Art:** "Demon Hunter" by [Szabados Zsolt](https://www.wowhead.com/news=249763.3/legion-art-contest-winners-gallery)
<br />**Page 9 Art:** "Wild Growth" by [EmberWickArt](https://twitter.com/emberwickart/status/1072575420850208768)
<br />**Page 10 Art:** "Guard" by [Bigball Gao](https://www.artstation.com/artwork/0l3ZG)
<br />**Page 11 Art:** "Draenei Frost Mage" by [Aaron Lovett](https://www.artstation.com/artwork/y2w6x)
<br />**Page 12 Art:** "Kel'Thuzad" by [Alexey Kruglov](https://www.artstation.com/artwork/V5BWN)
<br />**Page 13 Art:** "Night Elf Ranger" by [Grace Liu](https://www.deviantart.com/nightblue-art/art/Night-Elf-Ranger-374201887)
<br />**Page 14 Art:** "Scout Kurgo" by [Dan Scott](https://wowpedia.fandom.com/wiki/Scout_Kurgo)
<br />**Page 15 Art:** "Bubula del Kissel" by [Phroilan Gardner](https://wowpedia.fandom.com/wiki/Bubula_del_Kissel)
<br />**Page 16 Art:** "Troll Warrior" by [VanHarmontt](https://www.deviantart.com/vanharmontt/art/Troll-warrior-832831281)
<br />**Page 17 Art:** "Belf Warlock" by [VanHarmontt](https://www.deviantart.com/vanharmontt/art/Belf-Warlock-772984259)
<br />**Page 18 Art:** "Fire Mage" by [Matheus Fernando](https://www.artstation.com/artwork/W8mLJ)
<br /> **Backpage Art:** "Wardens of Nordrassil" by [Kan Liu](https://666kart.artstation.com/projects/6qo6)


## Other Thanks 

**Other projects we like and want to give thanks to**
- [World of Warcraft 5E](https://www.thepiazza.org.uk/bb/viewtopic.php?t=13979) by Arrius Nideal
- [Champion of Azeroth](https://drive.google.com/drive/folders/1f07sWuQJ_MBJxKbToalevudGQ8hjnma7) by Silverblade#9212
- [These WoW Dungeon modules](https://www.gmbinder.com/profile/wyken) by Wyken
- All of the awesome homebrew that has been shared within the community, it's super cool to see it all! <br /> You can see a lot of it on our Discord, and in this [Theme of the Month](https://drive.google.com/drive/folders/1_inQbI4jjd6WF3ghzhr_9RYBFygAkVK1) collection.


## Project Links

**Other Warcraft 5E books**
<br><span style="margin-left:12px"></span> We've been working creating both player material and
<br><span style="margin-left:12px"></span> dungeon master material for playing Warcraft in
<br><span style="margin-left:12px"></span> D&D 5th Edition. You can check them all out here:

<div style="text-align:center">

#### [Warcraft 5E on GDrive](https://drive.google.com/drive/folders/1kVoAMR8TiO3CXFYcigFN2B6zk62xcnv9)

</div>

<br> **Want to join our community?**
<br><span style="margin-left:12px"></span> We're a relatively small group working together on this,
<br><span style="margin-left:12px"></span> and we think it's fun to hear the thoughts and opinions
<br><span style="margin-left:12px"></span> of people who have played with it. If you want to share
<br><span style="margin-left:12px"></span> your stories with us, suggest changes, or just join our
<br><span style="margin-left:12px"></span> Warcraft RPG community, we have both a Discord
<br><span style="margin-left:12px"></span> server and a subreddit going.

<div style="text-align:center">

#### [Discord Server](https://discord.gg/dKMJmmD) <span style="margin-left:40px"></span> [Subreddit](https://www.reddit.com/r/wc5e/)

</div>


\pagebreakNum

___
> ## Acolyte <!-- https://wc5e-cr-calculator.frogvall.com/?0;11;27;2;12;4;0;4;0;4;0;0;0;0;0;0;0;;;;;3;;;;;;;;;;1;;;;;;;;10;;;;;;;1;1;1;1;Sacred%20Flame (Divine Glow not factored in) -->
>*Medium humanoid (any race), any alignment*
> ___
> - **Armor Class** 11
> - **Hit Points** 27 (6d8)
> - **Speed** 30 ft.
>___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |10 (+0)|10 (+0)|10 (+0)|10 (+0)|12 (+1)|14 (+2)|
>___
> - **Skills** Medicine +3, Religion +2
> - **Senses** passive Perception 11
> - **Languages** any one language (usually Common)
> - **Challenge** 1/4 (50 XP)
> ___
>
> ***Spellcasting.*** The acolyte is a 1st-level spellcaster. Its spellcasting ability is Charisma (spell save DC 12). The acolyte has following priest spells prepared:
>
> Cantrips (at will): *light*, *sacred flame*, *spare the dying*
> <br/> 1st level (3 slots): *cause fear* ^XGE^, *cure wounds*, <br/>   *sanctuary*
>
> ### Actions
>
> ***Dagger.*** *Melee or Ranged Weapon Attack:* +2 to hit, reach 5 ft. or ranged 20/60 ft., one target. *Hit:* 2 (1d4) piercing damage.
>
> ***Divine Glow (1/Day).*** The acolyte becomes a source of celestial light. Each undead creature in a 15-foot radius centered on the acolyte must make a DC 12 Dexterity saving throw. On a failed save, a creature takes 3 (1d6) radiant damage.

**Acolytes** are the novice priests in creeds and orders, great or small, that follow the teachings of a divine power. 
<br /> In this capacity, simple deeds and physical grunt
<br /> work are often made part of their tutelage.

\columnbreak


> ##### Variant: Acolyte of the Damned <!-- https://wc5e-cr-calculator.frogvall.com/?0;11;27;2;12;4;0;4;0;4;6;0;0;0;0;0;0;;;;;3;;;;;;;;;;1;;;;;;;;10;;;;;;;1;1;1;1;Sacred%20Flame -->
> One particularly notable group of acolytes are those who fell to the sway of the Damned and became servants of the Lich King and the Scourge.
> 
> An acolyte of the Damned have the same statistics as an acolyte, except that its *cure wounds* spell can affect undead creatures. It also has the following trait in place of an acolyte's Divine Glow action:
>
> <br/> ***Spirit Release.*** When the acolyte dies, its spirit escapes from its body in a violent burst of energy. Each creature in a 10-foot radius of the priest must make a DC 12 Constitution saving throw. On a failed save, a creature takes 3 (1d6) necrotic damage.

___
> ## Arcanist <!-- https://wc5e-cr-calculator.frogvall.com/?0;14;54;4;12;14;0;14;0;14;0;0;0;0;0;0;0;;;;;3;;;;;;;;;;1;;;;;;;;10;;;;;;;2;2;2;4;Arcane%20Blast;Fire%20Bolt;Magic%20Missile -->
>*Medium humanoid (any race), any alignment*
> ___
> - **Armor Class** 11 (14 with *mage armor*)
> - **Hit Points** 54 (12d8)
> - **Speed** 30 ft.
>___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |10 (+0)|12 (+1)|10 (+0)|15 (+2)|11 (+0)|12 (+1)|
>___
> - **Skills** Arcana +4, Perception +2
> - **Senses** passive Perception 12
> - **Languages** any one language (usually Common)
> - **Challenge** 1 (200 XP)
> ___
>
> ***Arcane Master (2/Day).*** Whenever the arcanist uses a cantrip spell to make a ranged spell attack, it can add its Intelligence modifier to the damage roll.
>
> ***Spellcasting.*** The arcanist is a 4th-level spellcaster. Its spellcasting ability is Intelligence (spell save DC 12, +4 to hit with spell attacks). The arcanist has following mage spells prepared:
>
> Cantrips (at will): ✦ *arcane blast*, *dancing lights*, *fire <br/>   bolt*, *mage hand*
> <br/> 1st level (4 slots): *detect magic*, *feather fall*, *mage <br/>   armor*, *magic missile*
> <br/> 2nd level (3 slots): *hold person*, *magic mouth*, *misty <br/>   step*
>
> ### Actions
>
> ***Quarterstaff..*** *Melee Weapon Attack:* +2 to hit, reach 5 ft., one target. *Hit:* 3 (1d6) bludgeoning damage, or 4 (1d8) bludgeoning damage if wielded with two hands.

Be it in a bastion of magic such as Dalaran or in smaller societies further afield, **arcanists** form the bulk of any magical community; always looking for a chance to learn and grow stronger as they indulge in their findings together with their teachers and peers.


<div class='footnote'>APPENDIX B: NONPLAYER CHARACTERS </div>
<img src="https://www.gmbinder.com/images/AYuE5Qf.png" class="inkblot" style="left: -35px;bottom: -355px;width: 520px;transform: rotate(107deg);">
<img src="https://www.gmbinder.com/images/cNVEirW.png" style="position:absolute;bottom: -35px;left: -20px;width: 430px;">

\pagebreakNum


___
> ## Archmage <!-- https://wc5e-cr-calculator.frogvall.com/?2;15;181;10;18;108;0;98;0;90;0;0;0;0;0;0;0;1;;;1;2;;;;;;;;;;1;1;;;;;;;10;;;;;;;9;8;7;18;Arcane%20Barrage;Alextrasza%27s%20Fury;Blizzard;Frostfire%20Bolt;Fire%20Bolt;Ray%20of%20Frost;Cone%20of%20Cold;Magic%20Missile -->
>*Medium humanoid (any race), any alignment*
> ___
> - **Armor Class** 12 (15 with *mage armor*)
> - **Hit Points** 181 (33d8 + 33)
> - **Speed** 30 ft.
>___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |10 (+0)|14 (+2)|12 (+1)|20 (+5)|15 (+2)|16 (+3)|
>___
> - **Saving Throws** Int +10, Wis +7
> - **Skills** Arcana +10, Perception +7
> - **Damage Resistance** damage from spells
> - **Senses** passive Perception 17
> - **Languages** any six languages
> - **Challenge** 14 (11,500 XP)
> ___
>
> ***Innate Spellcasting.*** The archmage's innate spellcasting ability is Intelligence (spell save DC 18). It can innately cast the following spells, requiring no material components:
>
> At will: *disguise self*, *invisibility*
>
> ***Magic Resistance.*** The archmage has advantage on saving throws against spells and other magical effects.
>
> ***Presence of Mind.*** While maintaining concentration on a spell, the archmage has a +2 bonus to AC and all saving throws.
>
> ***Spellcasting.*** The archmage is an 18th-level spellcaster. Its spellcasting ability is Intelligence (spell save DC 18; +10 to hit with spell attacks). The archmage has the following mage spells prepared:
>
> Cantrips (at will): *fire bolt*, *light*, *mage hand*, <br/>   *prestidigitation*, *ray of frost*
> <br/> 1st level (4 slots): *detect magic*, ✦ *frostfire bolt*, <br/>   *mage armor*, *magic missile*
> <br/> 2nd level (3 slots): *detect thoughts*, *mirror image*, <br/>   *misty step*
> <br/> 3rd level (3 slots): ✦ *blizzard*, *counterspell*, *slow*
> <br/> 4th level (3 slots): ✦ *arcane barrage*, *banishment*, <br/>   ✦ *ice block*
> <br/> 5th level (3 slots): *cone of cold*, *teleportation circle*, <br/>   *wall of force*
> <br/> 6th level (1 slot): *globe of invulnerability*
> <br/> 7th level (1 slot): *teleport*
> <br/> 8th level (1 slot): ✦ *alexstraza's fury*
> <br/> 9th level (1 slot): *time stop*  
>
> The archmage casts *mage armor* on itself before combat.
>
> ### Actions
> ***Dagger.*** *Melee or Ranged Weapon Attack:* +7 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.
>
> ### Reaction
>
> ***Arcane Ward (1/Day).***  When the archmage is hit by an attack, it can create a magic shield that can absorb up to 20 damage dealt by this attack. If the shield absorbs more than 15 damage this way the archmage can restore one spell slot of 3rd or lower level.


\columnbreak

<div style="margin-top:20px;"></div>

The talented few that put the work into magical mastery may be recognized as an **archmage**, standing at the pinnacle of their power -- garnering great influence, as well as a few tricks of their own, along the way. Though often gruff and aloof, these prestigious spellcasters are powerful enough to turn the tide of battles that put the fate of the world at stake. 


<div class='footnote'>APPENDIX B: NONPLAYER CHARACTERS </div>
<img src="https://www.gmbinder.com/images/uOQOURz.png" class="inkblot" style="right: -62px;top: 145px;width:640px;">
<img src="https://www.gmbinder.com/images/PGGwqOC.png" style="position:absolute;top: 78px;right: -178px;width: 810px;">

\pagebreakNum

<div style="margin-top:110px"></div>

Among druidic communities, there is nobody more respected and heeded than the wise **archdruid**. Few have ever existed, and those that do live long lives devoted to nature, and many of those few spend their time bound to the Emerald Dream.

\columnbreak

<div class="statblock-bottom-wide">

___
___
> ## Archdruid <!-- https://wc5e-cr-calculator.frogvall.com/?2;17;231;10;18;98;25;84;25;76;18;83;18;90;18;0;0;;;;1;2;;;;;;;;;;1;;;;;;;;10;;;;;;;9;8;7;17;Solar%20Wrath;Starfire;Starsurge;Wrath%20of%20Nature;Starfall;Sunbeam;Wall%20of%20Thorns;Whirlwind  Extra damage from Wrath of the Moon (+7 per spell w/ at least 5d6 damage) and Fury of Elune worked in. Turn  4 is bear form, turn 5 is cat form. -->
>*Medium humanoid (any race), any alignment*
> ___
> - **Armor Class** 14 (hide armor) in spellcaster or flight form, 16 with *barkskin*; 19 in bear form, or 16 in cat form.
> - **Hit Points** 231 (42d8 + 42)
> - **Speed** 30 ft., 50 ft. in cat form, fly 60 ft. in flight form
>___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |10 (+0)|14 (+2)|12 (+1)|12 (+1)|20 (+5)|11 (+0)|
>___
> - **Saving Throws** Int +6, Wis +10
> - **Skills** Medicine +10, Nature +6, Perception +10
> - **Damage Resistances** radiant
> - **Senses** passive Perception 20
> - **Languages** Druidic plus any two languages
> - **Challenge** 14 (11,500 XP)
> ___
> 
> ***Shapeshifting.*** As a bonus action, the archdruid can magically polymorph into its Bear form, Cat form, Flight form, or Spellcaster form. Outside of its normal human&shy;oid form, any equipment it is wearing or carrying is absorbed or borne by the alternate form (the archdruid's choice). It reverts to its humanoid form when it dies
>
> - ***Bear Form.*** While in the form of a Large bear, if the archdruid moves at least 20 feet straight toward a target and then hits with a melee attack on the same turn, the target takes an extra 18 (4d8) damage. If the target is a creature, it must succeed on a DC 18 Strength saving throw or be knocked prone.
>
> - ***Cat Form.*** While in the form of a Medium cat, the archdruid can take the Disengage or Hide action as a bonus action on each of its turn.
>
> - ***Flight Form.*** While in the form of a Medium bird, the archdruid does not provoke opportunity attacks when it moves out of an enemy's reach.
> 
> - ***Spellcaster Form.*** While in its normal humanoid form, or in the form of a Medium owlbear, a creature that suc&shy;ceeds on a saving throw against a cantrip cast by the archdruid still takes half the cantrip's damage (if any) but suffers no additional effects.
>
> <span></span> <!-- Break intendation on the line below -->
>
> ***Speak with Beasts and Plants.*** The archdruid can communicate with beasts and plants as if they shared a language.
>
> ***Wrath of the Moon (2/Day).*** When the archdruid casts a spell that deals damage, it can reroll up to 5 damage dice and use either roll.
> 
> ***Spellcasting (Spellcaster Form Only).*** The archdruid is an 18th-level spellcaster. Its spellcasting ability is Wisdom (spell save DC 18, +10 to hit with spell attacks). The archdruid has the following druid spells prepared:
>
> Cantrips (at will): *druidcraft*, *shape water* ^XGE^, <br/>   *shillelagh**, ✦ *solar wrath*
> <br/> 1st level (4 slots): *cure wounds*, *entangle*, *speak with <br/>   animals*, ✦ *starfire*
> <br/> 2nd level (3 slots): *animal messenger*, *barkskin**, <br/>   ✦ *cyclone*
> <br/> 3rd level (3 slots): *conjure animals*, *speak with plants*, <br/>    ✦ *starsurge*, *water breathing*
> <br/> 4th level (3 slots): *dominate beast*, *grasping vine*, <br/>   *guardian of nature*
> <br/> 5th level (3 slots): *commune with nature*, *mass cure <br/>   wounds*, *wrath of nature* ^XGE^
> <br/> 6th level (1 slot): *heal*, ✦ *starfall*, *sunbeam*, *wall of <br/>   thorns*
> <br/> 7th level (1 slot): *whirlwind* ^XGE^
> <br/> 8th level (1 slot): *control weather*
> <br/> 9th level (1 slot): *foresight*
>
> *The archdruid casts these spells on itself before combat.
>
> ### Actions
>
> ***Multiattack (Bear or Cat Forms Only).*** The archdruid makes two melee attacks while in bear form, or four melee attacks while in cat form.
>
> ***Maul (Bear Form Only).*** *Melee Weapon Attack:* +10 to hit, reach 5 ft., one target. *Hit:* 32 (5d10 + 5) bludgeoning damage.
>
> ***Rake (Cat or Flight Form Only).*** *Melee Weapon Attack:* +10 to hit, reach 5 ft., one target. *Hit:* 22 (5d6 + 5) slashing damage.
>
> ***Quarterstaff (Spellcaster Form Only).*** *Melee Weapon Attack:* +10 to hit, reach 5 ft ., one target. *Hit:* 14 (2d8 + 5) bludgeoning damage.
>
> ***Renewal (Recharges after Short or Long Rest).*** The arch&shy;druid chooses any one creature within 30 feet of it, which regains 41 (8d8 + 5) hit points.
>
> ### Reactions
>
> ***Fury of Elune.*** When the archdruid is hit by a melee attack, it can use its reaction to deal 18 radiant damage to the attacker. The attacker must also make a DC 18 Strength saving throw. On a failed save, the attacker is pushed in a straight line up to 20 feet away from the archdruid.

</div>

\columnbreak

<div class='footnote'>APPENDIX B: NONPLAYER CHARACTERS </div>
<img src='https://i.imgur.com/6u511ES.jpg' style='position:absolute; top:-100px; left:-38px; width:920px;' />
<img src='https://i.imgur.com/NO1EQoX.png' style='position:absolute; top:-245px; left:0; width:800px;' />
<img src='https://i.imgur.com/NO1EQoX.png' style='position:absolute; bottom:0; left:0; width:800px;' />


\pagebreakNum

___
> ## Assassin <!-- https://wc5e-cr-calculator.frogvall.com/?1;15;156;6;15;82;0;60;0;74;0;0;0;0;0;0;0;;;;1;2;;;;;;;;;;1;;;;;;;;10;;;;;; -->
>*Medium humanoid (any race), any non-good alignment*
> ___
> - **Armor Class** 15 (studded leather)
> - **Hit Points** 156 (24d8 + 48)
> - **Speed** 30 ft.
>___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |11 (+0)|16 (+3)|14 (+2)|13 (+1)|11 (+0)|10 (+0)|
>___
> - **Saving Throws** Dex +6, Int +4
> - **Skills** Acrobatics +6, Deception +3, Perception +3, Stealth +9
> - **Damage Resistances** poison
> - **Senses** passive Perception 13
> - **Languages** any two languages
> - **Challenge** 8 (3,900 XP)
> ___
>
> ***Assassinate.*** During its first turn, the assassin has advantage on attack rolls against any creature that hasn’t taken a turn. Any hit the assassin scores against a surprised creature is a critical hit.
>
> ***Deep Wound (1/Day).*** Whenever the assassin makes a melee attack, it can stab the target causing it to stumble around. For 1 minute, if the target moves more than half its speed in a single action, it falls prone at the end of its movement.
>
> ***Sneak Attack (1/Turn).*** Once per turn, the assassin deals an extra 14 (4d6) damage when it hits a target with a weapon attack and has advantage on the attack roll, or when the target is within 5 feet of an ally of the assassin that isn’t incapacitated and the assassin doesn’t have disadvantage on the attack roll.
>
> ### Actions
>
> ***Multiattack.*** The assassin makes two shortsword attacks.
>
> ***Shortsword.*** *Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage, and the target must make a DC 15 Constitution saving throw, taking 24 (7d6) poison damage on a failed save, or half as much damage on a successful one.
>
> ***Light Crossbow.*** *Ranged Weapon Attack:* +6 to hit, range 80/320 ft., one target. *Hit:* 7 (1d8 + 3) piercing damage, and the target must make a DC 15 Constitution saving throw, taking 24 (7d6) poison damage on a failed save, or half as much damage on a successful one.
>
> ### Reactions
> 
> ***Uncanny Dodge.*** When a creature that the assassin can see hits it with an attack, the assassin can halve the attack's damage against it.

An **assassin** is a hired killer for those who desire skill, grace, and no evidence left behind. No mere rogue or cut-throat, an assassin has class, distinction, and at least five methods of killing any one person.

\columnbreak

<div style='margin-top:470px;'></div>

___
> ## Bandit <!-- https://wc5e-cr-calculator.frogvall.com/?0;12;5;3;13;4;0;4;0;4;0;0;0;0;0;0;0;;;;;2;;;;;;;;;;1;;;;;;;;10;;;;;; -->
>*Medium humanoid (any race), any non-lawful alignment*
> ___
> - **Armor Class** 12 (leather armor)
> - **Hit Points** 5 (1d8 + 1)
> - **Speed** 30 ft.
>___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |11 (+0)|12 (+1)|12 (+1)|10 (+0)|10 (+0)|10 (+0)|
>___
> - **Skills** Sleight of Hand +3, Stealth +3
> - **Senses** passive Perception 10
> - **Languages** any one language (usually Common)
> - **Challenge** 1/8 (25 XP)
> ___
>
> ### Actions
>
> ***Scimitar.*** *Melee Weapon Attack:* +3 to hit, reach 5 ft., one  target. *Hit:* 4 (1d6 + 1) slashing damage.
>
> ***Javelin.*** *Melee or Ranged Weapon Attack:* +2 to hit, reach 5 ft. or range 30/120 ft., one target. *Hit:* 3 (1d6) piercing damage.


Across Azeroth, some find themselves eking out a life as a criminal; preying upon the communities around them. Whether will or chance brought a person to become a **bandit**, it is often a game of chance for whether these bands of thieves and pillagers rise to legend -- or fall to adventurers chasing a bounty placed upon them. 


<img src='https://www.gmbinder.com/images/tiU4RnD.png' class='inkblot' style='right:-160px; top:-60px; width:640px; transform:rotate(120deg);' />
<img src="https://www.gmbinder.com/images/9cQNovm.png" style="position:absolute; top:10px; right:0px; width:400px;">
<img src="https://www.gmbinder.com/images/uOQOURz.png" class="inkblot" style="right: 275px;bottom: -715px;width:700px;transform:rotate(-296deg);">


<div class='footnote'>APPENDIX B: NONPLAYER CHARACTERS </div>


\pagebreakNum

___
> ## Bandit Captain <!-- https://wc5e-cr-calculator.frogvall.com/?0;15;45;5;13;18;0;18;0;18;0;0;0;0;0;0;0;;;;1;2;;;;;;;;;;1;;;;1;;;;10;;;;;;;;;;; -->
>*Medium humanoid (any race), any non-lawful alignment*
> ___
> - **Armor Class** 15 (studded leather)
> - **Hit Points** 45 (7d8 + 14)
> - **Speed** 30 ft.
>___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |15 (+2)|16 (+3)|14 (+2)|14 (+2)|11 (+0)|14 (+2)|
>___
> - **Saving Throws** Dex +5, Wis +2
> - **Skills** Athletics +4, Deception +4, Sleight of Hand +5, Stealth +5
> - **Senses** passive Perception 10
> - **Languages** any two languages
> - **Challenge** 2 (450 XP)
> ___
>
> ### Actions
> ***Multiattack.*** The captain makes three melee attacks: two with its scimitar and one with its dagger. Or the captain makes a net attack and a scimitar attack.
>
> ***Scimitar.*** *Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) slashing damage.
>
> ***Dagger.*** *Melee or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage.
>
> ***Net.*** *Ranged Weapon Attack:* +3 to hit, range 5/15 ft., one Large or smaller creature. *Hit:* The target is restrained. A creature
can use its action to make a DC 10 Strength check to free itself or another creature in a net, ending the effect on a success. Dealing 5 slashing damage to the net (AC 10) frees the target without harming it and destroys the net.
> ### Reactions
>
> ***Parry.*** The captain adds 2 to its AC against one melee attack that would hit it. To do so, the captain must see the attacker and be wielding a melee weapon.

Always searching for a chance to use their freshly sharp&shy;ened blade, a **banit captain** is the leader of a community of cunning cutthroats. It is not unlike such a leader to turn to ruthless tactics to keep their band in check, or risk their own purse cut -- along with their throat.

<div></div>

**Bersekers** are terrifying warriors who head no warning when they rush forth into battle, lost in the haze of violence so pure as to drown out any pain they might feel. Simply powering through until all around them lay dead. They are particularly common among trolls and dwarves, though not unique to them.

> "I'm gonna enjoy guttin' you, lemme hear your bones crunch! GRaaAaAAH!!"
>
> - A berserker rousing before a fight


\columnbreak


___
> ## Berserker <!-- https://wc5e-cr-calculator.frogvall.com/?0;13;67;5;13;18;0;18;0;18;0;0;0;0;0;0;0;;;;;2;;;;;;;;;;1;;;;;;;;10;;;;;; -->
>*Medium humanoid (any race), any chaotic alignment*
> ___
> - **Armor Class** 13 (hide armor)
> - **Hit Points** 67 (9d8 + 27)
> - **Speed** 30 ft.
>___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |16 (+3)|12 (+1)|17 (+3)| 9 (-1)|11 (+0)| 9 (-1)|
>___
> - **Skills** Athletics +5
> - **Senses** passive Perception 10
> - **Languages** any one language (usually Common)
> - **Challenge**  2 (450 XP)
> ___
>
> ***Reckless.*** At the start of its turn, the berserker can gain advantage on all melee weapon attack rolls during that turn, but attack rolls against it have advantage until the start of its next turn.
>
> ***Charge (Recharges after a Short or Long Rest).*** The berserker can take the Dash action. If it moves at least 20 feet straight towards a target it can make one weapon attack against it with advantage.
> 
> ### Actions
>
> ***Multiattack.*** The berserker makes two greataxe attacks.
>
> ***Greataxe.*** *Melee Weapon Attack:* +5 to hit, reach 5 ft. , one target. *Hit:* 9 (1d12 + 3) slashing damage.
>
> ### Reactions
>
> ***Ignore Pain (Recharges after a Short or Long Rest).*** When the berserker is hit by a weapon attack, it can give itself resistance towards bludgeoning, piercing, and slashing damage from nonmagical attacks until the start of its next turn.


<img src="https://i.imgur.com/tiU4RnD.png" class="inkblot" style="right: -60px;bottom: -180px;width:660px;transform: rotate(-141deg);">
<img src="https://i.imgur.com/wP0RUsf.png" style="position:absolute; bottom:-200px; right:-25px; width:480px;" />

<div class='footnote'>APPENDIX B: NONPLAYER CHARACTERS </div>


\pagebreakNum


___
> ## Commoner <!-- https://wc5e-cr-calculator.frogvall.com/?0;10;4;2;11;2;0;2;0;2;0;0;0;0;0;0;0;;;;;2;;;;;;;;;;1;;;;;;;;10;;;;;; -->
>*Medium humanoid (any race), any alignment*
> ___
> - **Armor Class** 10
> - **Hit Points** 4 (1d8)
> - **Speed** 30 ft.
>___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |10 (+0)|10 (+0)|10 (+0)|10 (+0)|10 (+0)|10 (+0)|
>___
> - **Senses** passive Perception 10
> - **Languages** any one language (usually Common)
> - **Challenge** 0 (0 or 10 XP)
> ___
>
> ### Actions
>
> ***Club.*** *Melee Weapon Attack:* +2 to hit, reach 5 ft., one target. *Hit:* 2 (1d4) bludgeoning damage.

Be they orcish peons or human peasants, merchants at the stalls or old women heading for the town well, every culture across Azeroth features some form of **commoner** among them -- the everyday folk tending to their own lives.

<div></div>

Blessed by the Light to bring forth justice, **crusaders** are the brave and bold; the valiant holy warriors who stand forefront in the battle against darkness. They are often recognized by their brilliant librams, and for the zeal by which they keep to their cause. This zeal has driven some to fanaticism, such as the case of the Scarlet Crusade.


\columnbreak 


___
> ## Crusader <!-- https://wc5e-cr-calculator.frogvall.com/?0;18;78;5;11;14;13;14;13;14;9;0;0;0;0;0;0;;;;1;3;;;;;;;;;;1;;;;1;;;;10;;;;;; -->
>*Medium humanoid (any race), any lawful alignment*
> ___
> - **Armor Class** 18 (chain mail, shield)
> - **Hit Points** 78 (12d8 + 24)
> - **Speed** 30 ft.
>___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |17 (+3)|11 (+0)|14 (+2)|11 (+0)|11 (+0)|16 (+3)|
>___
> - **Saving Throws** Str +5, Con +4, Cha +5
> - **Skills** Athletics +5, Insight +2, Religion +4
> - **Senses** passive Perception 10
> - **Languages** any one language (usually Common)
> - **Challenge** 4 (1,100 XP)
> ___
>
> ***Brave.*** The crusader has advantage on saving throws against being frightened.
>
> ***Crusader Strike.*** As a bonus action, the crusader can expend a spell slot to deal an extra 9 (2d8) radiant damage to a target on the next hit before the end of its turn. If the crusader expends a spell slot of 2nd level or higher, the extra damage increases by 1d8 for each level above 1st. If the target is an undead or a fiend, the damage increases by 1d8.
>
> ***Spellcasting.*** The crusader is a 6th-level spellcaster. Its spellcasting ability is Charisma (spell save DC 13). The crusader has following paladin spells prepared:
>
> 1st level (4 slots):  *bless*, *cure wounds*, *heroism*, <br/>   *protection from evil and good*
> <br/> 2nd level (2 slots): *lesser restoration*, *protection from <br/>   poison*
>
> ### Actions
>
> ***Multiattack.*** The crusader makes two melee attacks, one of which can be replaced with its light's hammer.
>
> ***Longsword.*** *Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with two hands.
>
> ***Warhammer.*** *Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) bludgeoning damage, or 8 (1d10 + 3) bludgeoning damage if used with two hands.
>
> ***Light's Hammer (Recharge after a Short or Long Rest).*** As an action, the crusader slams a divine maul into the ground at a point within 30 feet of you, causing the ground to erupt in holy light in a 10-ft radius. Any ally within range is healed by 6 hit points, and all enemies within range must make a Constitution saving throw, taking 6 radiant damage on a failed save, and half as much on a successful one.
> ### Reactions
>
> ***Parry.*** The crusader adds 2 to its AC against one melee attack that would hit it. To do so, the crusader must see the attacker and be wielding a melee weapon.


<div class='footnote'>APPENDIX B: NONPLAYER CHARACTERS </div>
<img src="https://i.imgur.com/AYuE5Qf.png" class="inkblot" style="left: 12px;bottom: -175px;width: 550px;transform: rotate(108deg);">
<img src="https://i.imgur.com/fTCd9Sk.png" style="position:absolute;bottom: -190px;left: -88px;width: 525px;transform:scaleX(-1);">

\pagebreakNum


___
> ## Cult Fanatic <!-- https://wc5e-cr-calculator.frogvall.com/?0;13;99;4;12;22;0;22;0;22;0;0;0;0;0;0;0;;;;;3;;;;;;;;;;1;;;;;;;;10;;;;;;;2;2;2;4;Sacred%20Flame;Inflict%20Wounds;Spiritual%20Weapon -->
>*Medium humanoid (any race), any non-good alignment*
> ___
> - **Armor Class** 13 (leather armor)
> - **Hit Points** 99 (18d8 + 18)
> - **Speed** 30 ft.
>___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |11 (+0)|14 (+2)|12 (+1)|10 (+0)|13 (+1)|14 (+2)|
>___
> - **Skills** Deception +4, Persuasion +4, Religion +2
> - **Senses** passive Perception 11
> - **Languages** any one language (usually Common)
> - **Challenge** 3 (700 XP)
> ___
>
> ***Dark Devotion.*** The fanatic has advantage on saving throws against being charmed or frightened.
>
> ***Spellcasting.*** The fanatic is a 4th-level spellcaster. Its spell casting ability is Charisma (spell save DC 12, +4 to hit with spell attacks). The fanatic has the following priest spells prepared:
> 
> Cantrips (at will): *light*, *resistance*, *sacred flame*
> <br/> 1st level (4 slots):  *cause fear* ^XGE^, *inflict wounds*, <br/>   *shield of faith*
> <br/> 2nd level (3 slots): *hold person*, *mind spike* ^XGE^
>
> ### Actions
>
> ***Multiattack.*** The fanatic makes two melee attacks.
> 
> ***Dagger.*** *Melee or Ranged Weapon Attack:* +4 to hit, reach 5 ft. or range 20/60 ft., one creature. *Hit:* 4 (1d4 + 2) piercing damage plus 3 (1d6) necrotic damage.

Those determined enough to survive the rigors of cult initiation may find themselves facing power and knowledge they had never thought possible, as they grow into true **cult fanatics** -- the dental plans are also excellent.


\columnbreak

___
> ## Cultist <!-- https://wc5e-cr-calculator.frogvall.com/?0;12;4;3;11;5;0;4;0;4;0;0;0;0;0;0;0;;;;;3;;;;;;;;;;1;;;;;;;;10;;;;;;;1;;;1;Dark%20Void -->
>*Medium humanoid (any race), any non-good alignment*
> ___
> - **Armor Class** 12 (leather armor)
> - **Hit Points** 4 (1d8)
> - **Speed** 30 ft.
>___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |11 (+0)|12 (+1)|10 (+0)|10 (+0)|10 (+0)|12 (+1)|
>___
> - **Skills** Deception +2, Religion +2
> - **Senses** passive Perception 10
> - **Languages** any one language (usually Common)
> - **Challenge** 1/8 (25 XP)
> ___
>
> ***Dark Devotion.*** The cultist has advantage on saving throws against being charmed or frightened.
>
> ***Innate Spellcasting.*** The cultist's innate spellcasting ability is Charisma (spell save DC 11, +3 to hit with spell attacks). It can innately cast the following spells, requiring no material components:
> 
> At will: *resistance*, *spare the dying*
> <br/> 1/day each: *cause fear* ^XGE^, ✦ *dark void*
>
> ### Actions
>
> ***Scimitar.*** *Melee Weapon Attack:* +3 to hit, reach 5 ft, one creature. *Hit:* 4 (1d6 + 1) slashing damage.

Those in the world who are weakest are often those most easily exploited, brought into the bidding of dark masters looking to swell ever impressive ranks of loyal **cultists**.


<div class='footnote'>APPENDIX B: NONPLAYER CHARACTERS </div>
<img src="https://i.imgur.com/y0m5pEu.png" style="position:absolute;bottom: -36px;left: -30px;width: 870px;">

\pagebreakNum

<div style="margin-bottom:770px;"></div>

___
___
> ## Demon Hunter <!-- https://wc5e-cr-calculator.frogvall.com/?1;16;112;7;11;108;0;48;0;48;0;0;0;0;0;0;0;;;;1;2;;;;;;;;;;1;;;;;;;;10;;;;;;;;;;; -->
>*Medium humanoid (elf), any alignment*
> ___
> - **Armor Class** 16
> - **Hit Points** 112 (15d8 + 45)
> - **Speed** 30 ft.
>___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |15 (+2)|18 (+4)|16 (+3)|15 (+2)|12 (+1)|10 (+0)|
>___
> - **Saving Throws** Dex +7, Con +6
> - **Skills** Perception +4, Investigation +5, Survival +4
> - **Condition Immunities** blinded
> - **Senses** passive Perception 14
> - **Languages** any two languages
> - **Challenge** 7 (2,900 XP)
> ___
> ***Unarmored Defense.*** While the demon hunter is wearing no armor and wielding no shield, its AC includes its Intelligence modifier.
>
> ***Blade Dance.*** When the demon hunter uses Multiattack, it can teleport up to 15 feet before each attack to an unoccupied space it can see. 
>
> ***Evasion.*** When the demon hunter is subjected to an effect that allows it to make a Dexterity saving throw to take only half damage, the demon hunter instead takes no damage if it succeed on the saving throw, and only half damage if it fails.
>
> ***Magic Weapons.*** The demon hunter's weapon attacks are magical.
>
> ***Metamorphosis.*** Whenever the demon hunter starts its turn with 50 hit points or fewer, it takes on the shape of its inner demon. While transformed, its size increases to Large, its reach increases to 10 feet, it gains a fly speed of 60 ft., and a creature who starts their turn within 10 feet of the demon hunter or hits it with a melee attack takes 5 (1d10) fire damage.
>
> ***Spectral Sight.*** The demon hunter can see normally in both normal and magical darkness within 60 feet of it and is able to discern colors in darkness.
>
> ### Actions
>
> ***Multiattack.*** The demon hunter makes three warglaive attacks.
>
> ***Warglaive.*** *Melee or Ranged Weapon Attack:* +7 to hit, reach 5 ft. and range 20/60, one target. *Hit:* 8 (1d8 + 4) slashing damage plus 7 (2d6) fire damage. Thrown warglaives return to hand after the attack resolves.
>
> ***Eye Beam (Recharges after a Short or Long Rest).*** The demon hunter can blast energy in a 50 feet long and 5 feet wide line out from it in a direction it chooses. Each creature in the line must make a Dexterity saving throw. A creature takes 27 (5d10) fire damage and 27 (5d10) force damage on a failed save, or half as much on a successful one.
>
> ### Reactions
>
> ***Demon Wings.*** When the demon hunter falls, it can sprout a pair of leathery wings from its back making it land on its feet and taking no damage from the fall.

Following Illidan Stormrage to battle the Burning Legion, a determined few have sacrificed everything to harness the powers of demonkind and become **demon hunters**. 

\columnbreak

They hold a burning determination in their work against demons and stand ever on guard for demonic corruption, even among their own ranks.


<img src="https://i.imgur.com/dSG1nle.jpg" style="position:absolute;top: -75px;right: -40px;width: 860px;">
<img src="https://i.imgur.com/C2bOp8u.png" style="position:absolute;bottom: -320px;right:0px;width:820px;">


<div class='footnote'>APPENDIX B: NONPLAYER CHARACTERS </div>


\pagebreakNum

___
___
> ## Druid <!-- https://wc5e-cr-calculator.frogvall.com/?0;16;60;4;12;22;0;22;0;22;0;0;0;0;0;0;0;;;;;2;;;;;;;;;;1;;;;;;;;10;;;;;;;2;2;2;4;Solar%20Wrath;Starfire;Moonbeam Turn  4 is bear form, turn 5 is cat form. -->
>*Medium humanoid (any race), any alignment*
> ___
> - **Armor Class** 11 (16 with *barkskin*)
> - **Hit Points** 60 (11d8 + 11)
> - **Speed** 30 ft.
>___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |10 (+0)|12 (+1)|13 (+1)|12 (+1)|15 (+2)|11 (+0)|
>___
> - **Skills** Medicine +4, Nature +3, Perception +4
> - **Senses** passive Perception 14
> - **Languages** Druidic plus any two languages
> - **Challenge** 3 (700 XP)
> ___
>
> ***Shapeshifting.*** As a bonus action, the druid can magically polymorph into its Bear form, Cat form, or Flight form, or back to its normal humanoid form. Outside of its normal form, any equipment it is wearing or carrying is absorbed or borne by the alternate form (the druid's choice). It reverts to its humanoid form when it dies
>
> - ***Bear Form.*** While in the form of a Large bear, if the druid moves at least 20 feet straight toward a target and then hits with a melee attack on the same turn, the target takes an extra 9 (2d8) damage. If the target is a creature, it must succeed on a DC 12 Strength saving throw or be knocked prone.
>
> - ***Cat Form.*** While in the form of a Medium cat, the druid can take the Disengage or Hide action as a bonus action on each of its turn.
>
> - ***Flight Form.*** While in the form of a Medium bird, the druid does not provoke opportunity attacks when it moves out of an enemy's reach.
>
> <span></span> <!-- Break intendation on the line below -->
> 
> ***Renewal (Recharges after a Short or Long Rest).*** The druid can use its bonus action to regain 9 (2d6 + 2) hit points.
>
> ***Speak with Beasts and Plants.*** The archdruid can communicate with beasts and plants as if they shared a language.
>
> ***Spellcasting.*** The druid is a 4th-level spellcaster. Its spellcasting ability is Wisdom (spell save DC 12, +4 to hit with spell attacks). It has the following druid spells prepared:
>
> Cantrips (at will): *druidcraft*, ✦ *solar wrath*, *shillelagh**
> <br/> 1st level (4 slots): *cure wounds*, *entangle*, *feather fall*, <br/>   ✦ *starfire*
> <br/> 2nd level (3 slots): *barkskin**, *moonbeam*
>
> *The druid casts these spells on itself before combat.
>
> ### Actions
> 
> ***Multiattack (Cat Form Only).*** The druid makes two melee attacks while in cat form.
>
> ***Maul (Bear Form Only).*** *Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 13 (2d10 + 2) bludgeoning damage.
>
> ***Rake (Cat or Flight Form Only).*** *Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 11 (2d8 + 2) slashing damage.
>
> ***Quarterstaff (Spellcaster Form Only).*** *Melee Weapon Attack:* +4 to hit, reach 5 ft ., one target. *Hit:* 6 (1d8 + 2) bludgeoning damage.
>
> <span /> <!-- Break in extra space to change statblock split -->

Through a connection to the Emerald Dream, **druids** druids are guardians of nature who seek to preserve balance and protect life. They have an immense versatility on the field of battle, harnessing a wide breadth of abilities through the forms of different beasts. 

Druids often band together in smaller groups or larger clans, that focus their teachings in around a particular animal totem and aspect of their powers, though 
<br /> it is not unusual for them to embrace multiple 
<br /> totems regardless of their clan. 

As examples, the Druids of the Claw keep 
<br /> cat and bear totems; the Druids of the Talon
<br /> keep bird totems; and the Druids of the Moon
<br /> keep totems of the great owlbear.

\columnbreak


<img src='https://i.imgur.com/AYuE5Qf.png' class='inkblot' style='left: 210px;bottom: -360px;width: 630px;transform: rotate(-85deg) scaleX(-1);' />
<img src="https://i.imgur.com/diOKboU.png" style="position:absolute;bottom: -35px;right: -135px;width: 620px;transform: rotate(12deg);">

<div class='footnote'>APPENDIX B: NONPLAYER CHARACTERS </div>


\pagebreakNum

___
___
> ## Gladiator <!-- https://wc5e-cr-calculator.frogvall.com/?1;16;112;7;15;33;0;33;0;33;0;0;0;0;0;0;0;;;;1;3;;;;;;;;;;1;;;;1;;;;10;;;;;; -->
>*Medium humanoid (any race), any alignment*
> ___
> - **Armor Class** 16 (studded leather, shield)
> - **Hit Points** 112 (15d8 + 45)
> - **Speed** 30 ft.
>___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |18 (+4)|15 (+2)|16 (+3)|10 (+0)|12 (+1)|15 (+2)|
>___
> - **Saving Throws** Str +7, Dex +5, Con +6
> - **Skills** Athletics +10, Intimidation +5
> - **Senses** passive Perception 11
> - **Languages** any one language (usually Common)
> - **Challenge** 5 (1,800 XP)
> ___
>
> ***Brave.*** The gladiator has advantage on saving throws against being frightened.
>
> ***Brute.*** A melee weapon deals one extra die of its damage when the gladiator hits with it (included in the attack).
>
> ### Actions
>
> ***Multiattack.*** The gladiator makes three melee attacks or two ranged attacks.
>
> ***Spear.*** *Melee or Ranged Weapon Attack:* +7 to hit, reach 5 ft. and range 20/60 ft., one target. *Hit*: 11 (2d6 + 4) piercing damage, or 13 (2d8 + 4) piercing damage if used with two hands to make a melee attack.
>
> ***Shield Bash.*** *Melee Weapon Attack:* +7 to hit, reach 5 ft., one creature. *Hit:* 9 (2d4 + 4) bludgeoning damage. If the target is a Medium or smaller creature, it must succeed on a DC 15 Strength saving throw or be knocked prone.
>
> ### Reactions
>
> ***Parry.*** The gladiator adds 3 to its AC against one melee attack that would hit it. To do so, the gladiator must see the attacker and be wielding a melee weapon.

For a **gladiator**, Azeroth is host to a multitude of bloody arenas in which they may risk it all for coin and fame -- sometimes even for freedom, though seldom for honor. 

The bombastic nature of these gladiatorial displays owe back to the traditions of the ogre lords of Draenor, to whom the sport is a long-standing cultural tentpole. 

\columnbreak

> ##### Variant: Net-Throwing Gladiator
> Throwing nets are a common tool for seasoned gladiators. A gladiator fighting this way gains the following traits in place of its Shield Bash action:
>
> <br /> ***Net Thrower.*** The gladiator can throw a net in place of any melee or ranged attack it makes. It can only throw one net per turn.
> 
> <br /> ***Reinforced Net.*** *Ranged Weapon Attack*: +5 to hit, range 5/15 ft., one Large or smaller creature. *Hit*: The target is restrained. A creature can use its action to make a DC 15 Strength check to free itself or another creature within reach on a success. Dealing 20 slashing damage to the net (AC 15) frees the target without harming it and destroys the net.
>
> The gladiator carries 2 (1d4+1) nets. 


<img src="https://i.imgur.com/Lb5BP9S.jpg" style="position: absolute;bottom: -100px;right: 0px;width: 850px;">
<img src="https://i.imgur.com/MVDaLa2.png" style="position:absolute;top: -171px;right: -20px;width: 830px;transform: scaleX(-1);">

<div class='footnote'>APPENDIX B: NONPLAYER CHARACTERS </div>


\pagebreakNum

___
> ## Guard <!-- https://wc5e-cr-calculator.frogvall.com/?0;16;5;3;11;4;0;4;0;4;0;0;0;0;0;0;0;;;;;3;;;;;;;;;;1;;;;;;;;10;;;;;; -->
>*Medium humanoid (any race), any alignment*
> ___
> - **Armor Class** 16 (chain shirt, shield)
> - **Hit Points** 5 (1d8 + 1)
> - **Speed** 30 ft.
>___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |13 (+1)|12 (+1)|12 (+1)|10 (+0)|11 (+0)|10 (+0)|
>___
> - **Skills** Perception +2
> - **Senses** passive Perception 12
> - **Languages** any one language (usually Common)
> - **Challenge** 1/4 (50 XP)
> ___
>
> ### Actions
>
> ***Spear.*** *Melee or Ranged Weapon Attack:* +3 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 4 (1d6 + 1) piercing damage, or 5 (1d8 + 1) piercing damage if used with two hands to make a melee attack.
>
> ***Shortsword.*** *Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 4 (1d6 + 1) piercing damage.

Going by many titles, the often faceless and sometimes nameless **guards** of the world are eternally vigilant in their work to protect grand cities and small hamlets alike from scoundrels and monsters alike. Often enough, they find themselves just offering directions to visiting adventurers. 


\columnbreak 


___
> ## Infiltrator <!-- https://wc5e-cr-calculator.frogvall.com/?0;15;88;5;13;35;0;35;;35;0;0;0;0;0;0;0;;;;1;2;;;;;;;;;;1;;;;;;;;10;;;;;;;;;;; -->
>*Medium humanoid (any race), any alignment*
> ___
> - **Armor Class** 15 (studded leather)
> - **Hit Points** 88 (16d8 + 16)
> - **Speed** 30 ft.
>___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |11 (+0)|16 (+3)|12 (+1)|13 (+1)|11 (+0)|15 (+2)|
>___
> - **Saving Throws** Dex +5, Int +3
> - **Skills** Deception +4, Perception +2, Sleight of Hand +5, Stealth +5
> - **Senses** passive Perception 12
> - **Languages** any two languages
> - **Challenge** 4 (1,100 XP)
> ___
>
> ***Cunning Action.*** On each of its turns, the infiltrator can use a bonus action to take the Dash, Disengage, or Hide action. 
>
> ***Sneak Attack (1/Turn).*** The infiltrator deals an extra 7 (2d6) damage when it hit s a target with a weapon attack and has advantage on the attack roll , or when the target is within 5 feet of an ally of the infiltrator that isn't incap&shy;acitated and the infiltrator doesn't have disadvantage on the attack roll.
>
> ***Shadowstep (1/Day).*** The infiltrator can use a bonus action to teleport up to 30 feet to an unoccupied space within 5 feet of
another creature that it can see. If the infiltrator hits the targeted creature with an attack, on the same turn, it is surrounded by entangling shadows and its movement speed is halved until the start of your next turn.
>
> ### Actions
> ***Multiattack.*** The infiltrator makes two melee attacks.
>
> ***Dagger.*** *Melee or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage, and the target must make a DC 13 Constitution saving throw, taking 10 (3d6) poison damage on a failed save, or half as much damage on a successful one.
>
> ***Smoke Bomb (2/Day).*** The infiltrator can throw a bomb at a point up to 60 feet away. When the smoke bomb lands, it emits a cloud of smoke that creates a heavily obscured area in a 20-foot radius. It lasts for 1 minute or until a strong wind disperses it.

Highly skilled **infiltrators** are sent into exceptional danger to gather the most vital of knowledge, often at the risk of death or torture. They have silver tongues and lightning reflexes, and will serve their commanders by all means and with every trick their sleeve.

> "And remember, agent. Should you be discovered, SI:7 will disavow all knowledge of your existence."
> 
> - Master Mathias Shaw, briefing an SI:7 infiltrator
>
> // Convert into paper note


<img src="https://i.imgur.com/BrDcy46.png" class="inkblot" style="left: -150px;bottom: -98px;width: 660px;transform: rotate(292deg) scaleX(-1);">
<img src="https://i.imgur.com/uOQOURz.png" class="inkblot" style="left: 430px;bottom: -540px;width: 600px;transform: rotate(-450deg);">
<img src='https://i.imgur.com/qg5tNJp.png' style='position:absolute; bottom:0px; left:-10px; width:430px;' />


<div class='footnote'>APPENDIX B: NONPLAYER CHARACTERS </div>

\pagebreakNum

<div style='margin-top:250px;'></div>

___
> ## Knight <!-- https://wc5e-cr-calculator.frogvall.com/?0;18;52;5;13;20;0;20;0;20;0;0;0;0;0;0;0;;;;1;2;;;;;;;;;;1;;;;1;;;;10;;;;;; -->
>*Medium humanoid (any race), any alignment*
> ___
> - **Armor Class** 18 (plate)
> - **Hit Points** 52 (8d8 + 16)
> - **Speed** 30 ft.
>___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |16 (+3)|11 (+0)|14 (+2)|11 (+0)|11 (+0)|15 (+2)|
>___
> - **Saving Throws** Con +4, Wis +2
> - **Senses** passive Perception 10
> - **Languages** any one language (usually Common)
> - **Challenge** 3 (700 XP)
> ___
>
> ***Brave.*** The knight has advantage on saving throws against being frightened.
>
> ### Actions
>
> ***Multiattack.*** The knight makes two melee attacks.
>
> ***Greatsword.*** *Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 10 (2d6 + 3) slashing damage.
>
> ***Heavy Crossbow.*** *Ranged Weapon Attack:* +2 to hit, range 100/400 ft., one target. *Hit:* 5 (ld10) piercing damage.
>
> ***Leadership (Recharges after a Short or Long Rest).*** For 1 minute, the knight can utter a special command or warning whenever a non hostile creature that it can see within 30 feet of it makes an attack roll or a saving throw. The creature can add a d4 to its roll provided it can hear and understand the knight. A creature can benefit from only one Leadership die at a time. This effect ends if the knight is incapacitated.
>
> ### Reactions
>
> ***Parry.*** The knight adds 2 to its AC against one melee attack that would hit it. To do so, the knight must see the attacker and be wielding a melee weapon.

The heroic **knights** of any culture will, first and foremost, represent the virtues of their home. They only ever turn from a battle ordered to do so by their commander.

\columnbreak


<div style='margin-top:214px;'></div>

___
> ## Mage <!-- https://wc5e-cr-calculator.frogvall.com/?1;15;126;6;14;50;0;37;0;37;0;0;0;0;0;0;0;;;;1;2;;;;;;;;;;1;;;;;;;;10;;;;;;;5;4;4;9;Arcane%20Barrage;Blizzard;Frostfire%20Bolt;Fire%20Bolt;Magic%20Missile;Scorching%20Ray -->
> *Medium humanoid (any race), any alignment*
> ___
> - **Armor Class** 12 (15 with *mage armor*)
> - **Hit Points** 126 (28d8)
> - **Speed** 30 ft.
>___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> | 9 (-1)|14 (+2)|11 (+0)|17 (+3)|12 (+1)|11 (+0)|
>___
> - **Saving Throws** Int +6, Wis +4
> - **Skills** Arcana +6, History +6
> - **Senses** passive Perception 11
> - **Languages** any four languages
> - **Challenge** 5 (1,800 XP)
> ___
>
> ***Deep Freeze (1/Day).*** When the mage deals cold damage to a creature, it can use its bonus action to freeze it. The target must succeed on a DC 14 Dexterity saving throw or be stunned until the end of the mage's next turn.
>
> ***Spellcasting.*** The mage is a 9th-level spellcaster. Its spellcasting ability is Intelligence (spell save DC 14, +6 to hit with spell attacks). The mage has following mage spells prepared:
>
> Cantrips (at will): *dancing lights*, *fire bolt*, *mage hand*, <br/>   *prestidigitation*
> <br/> 1st level (4 slots): *detect magic*, ✦ *frostfire bolt*, <br/>   *mage armor*, *magic missile*
> <br/> 2nd level (3 slots): *magic mouth*, *misty step*, <br/>   *scorching ray*
> <br/> 3rd level (3 slots): ✦ *blizzard*, *counterspell*, *slow*
> <br/> 4th level (3 slots): ✦ *arcane barrage*, *dimension door*, <br/>   *greater invisibility*
> <br/> 5th level (1 slot): *scrying*
>
> The mage cast *mage armor* on itself before combat.
>
> ### Actions
>
> ***Dagger.*** *Melee or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.


A **mage** is an arcanist has passed the trials of apprenticeship and begun the path of greater knowledge and power -- and will often be eager for opportunities to acquire both.



<div class='footnote'>APPENDIX B: NONPLAYER CHARACTERS </div>
<img src="https://i.imgur.com/tiU4RnD.png" class="inkblot" style="width:650px; top:-200px; right:110px; transform:rotate(90deg);" />
<img src="https://i.imgur.com/3NbU5os.png" style="position:absolute; top:-40px; right:-25px; width:680px;" />
    
\pagebreakNum


___
> ## Necromancer <!-- https://wc5e-cr-calculator.frogvall.com/?0;12;88;5;15;44;0;36;0;36;0;0;0;0;0;0;0;;;;1;2;;;;;;;;;;1;;;;;;;;10;;;;;;;4;3;3;7;Shadow%20Bolt;Dark%20Void;Chill%20Touch;Ray%20of%20Sickness;Shatter;Sickening%20Radiance;Vampiric%20Touch -->
> *Medium humanoid (any race), any alignment*
> ___
> - **Armor Class** 12
> - **Hit Points** 88 (16d8 + 16)
> - **Speed** 30 ft.
>___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |10 (+0)|15 (+2)|12 (+1)|17 (+3)|15 (+2)|13 (+1)|
>___
> - **Saving Throws** Int +5, Wis +4
> - **Skills** Arcana +5, History +5
> - **Senses** passive Perception 12
> - **Languages** any three languages
> - **Challenge** 4 (1,100 XP)
> ___
>
> ***Grim Harvest (1/Turn).*** Once per turn when, when the necromancer kill one or more creatures with a spell of 1st level or higher, he regains hit points equal to twice the spell‘s level. The necromancer does not gain this benefit for killing constructs or undead.
>
> ***Undead Thralls.*** When the necromancer casts *animate dead*, it can target one additional corpse or pile of bones, creating another zombie or skeleton, as appropriate. Undead created by the necromancer have an additional 6 hp and a +3 to their weapon damage rolls.
>
> ***Spellcasting.*** The necromancer is a 7th-level spellcaster. Its spellcasting ability is Intelligence (spell save DC 15, +5 to hit with spell attacks). The necromancer has following warlock and priest spells prepared:
>
> Cantrips (at will): *blade ward*, *chill touch*, ✦ *shadow <br/>   bolt*
> <br/> 1st level (4 slots): *cause fear* ^XGE^, ✦ *dark void*, *false <br/>   life*, *ray of sickness*
> <br/> 2nd level (3 slots): *darkness*, *ray of enfeeblement*, <br/>   *shatter*
> <br/> 3rd level (3 slots): *animate dead*, *bestow curse*,<br/>   *vampiric touch*
> <br/> 4th level (1 slot): *sickening radiance* ^XGE^
>
> ### Actions
> ***Dagger.*** *Melee or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range 20ft./60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.


**Necromancers** are powerful mages who delve into the shrouded mysteries of undeath, a practice that is consid&shy;ered taboo -- and typically outlawed. While some work to their own ends, most serve the Scourge, and they all show a sickening kind of brilliance.


\columnbreak


___
> ## Noble <!-- https://wc5e-cr-calculator.frogvall.com/?0;15;4;3;12;5;0;5;0;5;0;0;0;0;0;0;0;;;;;2;;;;;;;;;;1;;;;1;;;;10;;;;;; -->
>*Medium humanoid (any race), any alignment*
> ___
> - **Armor Class** 15 (breastplate)
> - **Hit Points** 4 (1d8)
> - **Speed** 30 ft.
>___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |11 (+0)|12 (+1)|11 (+0)|12 (+1)|14 (+2)|16 (+3)|
>___
> - **Skills** Deception +5, Insight +4, Persuasion +5
> - **Senses** passive Perception 12
> - **Languages** any two languages
> - **Challenge** 1/4 (50 XP)
> ___
>
> ### Actions
>
> ***Rapier.*** *Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 5 (1d8 + 1) piercing damage.
>
> ### Reactions
>
> ***Parry.*** The noble adds 2 to its AC against one melee attack that would hit it. To do so, the noble must see the attacker and be wielding a melee weapon.

The higher class of their culture, **nobles** have often been particularly susceptible to the corrupting forces of the world. Others in turn have chosen to use their influence to actively combat said corruption and evil. 


<img src="https://www.gmbinder.com/images/0hVRLNf.png" class="inkblot" style="width:690px;bottom: -60px;right: -160px;transform: rotate(221deg) scaleY(-1);">
<img src="https://www.gmbinder.com/images/0hVRLNf.png" class="inkblot" style="width:690px;bottom: -380px;right:190px;transform: rotate(85deg) scaleY(-1);">

<img src="https://www.gmbinder.com/images/xU5GXXN.png" style="position:absolute; bottom:-50px; right:-80px; width:530px;">
<img src="https://i.imgur.com/4Zw3ovg.png" style="position:absolute;bottom: 10px;left: 30px;width: 240px;transform:scaleX(-1);mix-blend-mode:multiply;">
<img src="https://i.imgur.com/XsyrOpt.jpg" style="position:absolute;bottom: 30px;left: 256px;width: 220px;mix-blend-mode:multiply;">


<div class='footnote'>APPENDIX B: NONPLAYER CHARACTERS </div>

\pagebreakNum


___
> ## Priest <!-- https://wc5e-cr-calculator.frogvall.com/?0;10;60;5;13;21;0;21;0;17;0;0;0;0;0;0;0;;;;;2;;;;;;;;;;1;;;;;;;;10;;;;;;;3;3;2;5;Sacred%20Flame;Word%20of%20Radiance;Guiding%20Bolt -->
>*Medium humanoid (any race), any alignment*
> ___
> - **Armor Class** 13
> - **Hit Points** 60 (11d8 + 11)
> - **Speed** 30 ft.
>___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |10 (+0)|10 (+0)|12 (+1)|13 (+1)|13 (+1)|16 (+3)|
>___
> - **Skills** Medicine +5, Persuasion +5, Religion +3
> - **Senses** passive Perception 13
> - **Languages** any two languages
> - **Challenge** 2 (450 XP)
> ___
> ***Echoes of Life.*** Whenever the priest uses a spell of 1st level or higher to restore hit points to a creature, the creature regains additional hit points equal to 2 + the spell's level.
>
> ***Inner Fire.*** While the priest is wearing no armor and wielding no shield, its AC includes its Charisma modifier.
>
> ***Spellcasting.*** The priest is a 5th-level spellcaster. Its spellcasting ability is Charisma (spell save DC 13, +5 to hit with spell attacks). The priest has the following cleric spells prepared:
>
> Cantrips (at will): *light*, *sacred flame*, *word of <br/>   radiance* ^XGE^
> <br/> 1st level (4 slots): *cure wounds*, *guiding bolt*, <br/>   *sanctuary*
> <br/> 2nd level (3 slots): *hold person*, *lesser restoration*
> <br/> 3rd level (2 slots): *dispel magic*, *revivify*
>
> ### Actions
> ***Quarterstaff.*** *Melee Weapon Attack:* +2 to hit, reach 5 ft., one target. *Hit:* 3 (1d6) bludgeoning damage.

The **priests** of the Holy Light display a mastery over spells that mend and protec. They are most often kind and acco&shy;mmodating, though religious doctrine can limit their ability or willingness to interact with certain people.


\columnbreak


___
> ## Ranger <!-- https://wc5e-cr-calculator.frogvall.com/?0;16;75;6;13;21;0;21;0;21;0;0;0;0;0;0;0;;;;;2;;;;;;;;;;1;;;;;;;;10;;;;;; -->
>*Medium humanoid (any race), any alignment*
> ___
> - **Armor Class** 16 (studded leather)
> - **Hit Points** 75 (10d8 + 30)
> - **Speed** 30 ft.
>___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |11 (+0)|18 (+4)|16 (+3)|11 (+0)|13 (+1)|10 (+0)|
>___
> - **Skills** Acrobatics +6, Animal Handling +4, Nature +3,  Survival +4, Perception +5
> - **Senses** passive Perception 15
> - **Languages** any one language (usually Common)
> - **Challenge** 3 (700 XP)
> ___
> ***Careful Aim (3/Day).***  As a bonus action, the ranger can add 5 (1d10) to its next attack or damage roll with a ranged weapon.
>
> ### Actions
>
> ***Multiattack.*** The ranger makes two attacks with its longbow.
>
> ***Shortsword.*** *Melee Weapon Attack:* +6 to hit, reach S ft., one target. *Hit:* 7 (1d6 + 4) piercing damage.
>
> ***Longbow.*** *Ranged Weapon Attack:* +6 to hit, range l50/600 ft., one target. *Hit:* 8 (1d8 + 4) piercing damage.

Among elves,  **rangers** are some of the most respected figures one can find, and any non-elf following the same path will often be treated to much of the same reverence. It is their charge to learn the lay of the land and guard it with utmost care.

<!-- TODO: When this is in the book, it needs to have page numbers -->

> ##### Variant: Beast Companions
> Rangers are often accompanied by beasts of the wild as partners in battle, which are added to an encoun&shy;ter as standalone creatures. This is usually a creature of CR 1 or below. Here are some examples of such tamed beasts (pages will be added later).
>
> Creature		            | Preferred By  | Page  
> --------------------------|---------------|----:
> Brown Bear                | Dwarves       | ###
> Dire Wolf                 | Humans, Orcs  | ###
> Giant Moth                | Draenei       | ###
> Raptor                    | Trolls        | ###
> Sabercat                  | Night elves   | ###
> Turtle                    | Pandaren      | ###
> Wind Serpent              | Tauren        | ###
> Young Dragonhawk          | Blood elves   | ###


<img src="https://www.gmbinder.com/images/AYuE5Qf.png" class="inkblot" style="width: 580px;bottom: -258px;right: -5px;transform: rotate(100deg) scaleY(-1);">
<img src="https://www.gmbinder.com/images/Vd3niEy.png" style="position:absolute;bottom: -10px;left: -25px;width: 480px;">

<div class='footnote'>APPENDIX B: NONPLAYER CHARACTERS </div>


\pagebreakNum


___
> ## Scout <!-- https://wc5e-cr-calculator.frogvall.com/?0;13;16;4;13;12;0;12;0;12;0;0;0;0;0;0;0;;;;;2;;;;;;;;;;1;;;;;;;;10;;;;;; -->
>*Medium humanoid (any race), any alignment*
> ___
> - **Armor Class** 13 (leather)
> - **Hit Points** 16 (3d8 + 3)
> - **Speed** 30 ft.
>___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |11 (+0)|14 (+2)|12 (+1)|11 (+0)|13 (+1)|11 (+0)|
>___
> - **Skills** Nature +4, Perception +5, Stealth +6, Survival +5
> - **Senses** passive Perception 15
> - **Languages** any one language (usually Common)
> - **Challenge** 1/2 (100 XP)
> ___
>
> ***Keen Hearing and Sight.*** The scout has advantage on Wisdom (Perception) checks that rely on hearing or sight.
>
> ### Actions
>
> ***Multiattack.*** The scout makes two melee attacks or two ranged attacks.
>
> ***Shortsword.*** *Melee Weapon Attack:* +4 to hit, reach S ft., one target. *Hit:* 5 (1d6 + 2) piercing damage.
>
> ***Longbow.*** *Ranged Weapon Attack:* +4 to hit, range l50/600 ft., one target. *Hit:* 6 (1d8 + 2) piercing damage.


As swift as they are agile, **scouts** excel as guides through the wilds, as well as reconnaissance workers and expedient messengers. Those embroiled in military service will keep themselves leaps ahead of their fellows, ever on guard for any encroaching threat. 

\columnbreak


___ 
> ## Soldier <!-- https://wc5e-cr-calculator.frogvall.com/?0;17;11;4;13;6;0;6;0;6;0;0;0;0;0;0;0;;;;;2;;;;;;;;;;1;;;;1;;;;10;;;;;;;;;;; -->
>*Medium humanoid (any race), any alignment*
> ___
> - **Armor Class** 17 (breastplate, shield)
> - **Hit Points** 11 (2d8 + 2)
> - **Speed** 30 ft.
>___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |14 (+2)|12 (+1)|12 (+1)|10 (+0)|10 (+0)| 9 (-1)|
>___
> - **Senses** passive Perception 10
> - **Languages** any one language (usually Common)
> - **Challenge** 1/2 (100 XP)
> ___
>
> ***Sure-Footed.*** The soldier has advantage on Strength and Dexterity saving throws made against effects that would knock it prone.
>
> ### Actions
> ***Longsword.*** *Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8 + 2) slashing damage, or 7 (1d10 + 2) slashing damage if used with two hands.
>
> ### Reaction
> ***Parry.*** The soldier adds 2 to its AC against one melee attack that would hit it. To do so, the soldier must see the attacker
and be wielding a shield.

Whether they are grunts, sentinels, or **soldiers**, the back&shy;bone of any army is its standing ranks. In some cultures, the common folk may find themselves drafted out of sheer necessity, while in other cultures it can be considered a matter of pride to partake.


<img src='https://i.imgur.com/moDxofj.png' style='position:absolute; bottom:-174px; right:0px; width:800px' />

<div class='footnote'>APPENDIX B: NONPLAYER CHARACTERS </div>

\pagebreakNum


___
> ## Spy <!-- https://wc5e-cr-calculator.frogvall.com/?0;12;54;4;13;15;0;15;0;15;0;0;0;0;0;0;0;;;;;2;;;;;;;;;;1;;;;;;;;10;;;;;;;;;;; -->
>*Medium humanoid (any race), any alignment*
> ___
> - **Armor Class** 12
> - **Hit Points** 54 (12d8)
> - **Speed** 30 ft.
>___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |10 (+0)|15 (+2)|10 (+0)|12 (+1)|14 (+2)|16 (+3)|
>___
> - **Skills** Deception +5, Insight +4, Investigation +5, Perception +6, Persuasion +5, Sleight of Hand +4, Stealth +4
> - **Senses** passive Perception 16
> - **Languages** any two languages
> - **Challenge** 2 (450 XP)
> ___
>
> ***Cunning Action.*** On each of its turns, the spy can use a bonus action to take the Dash, Disengage, or Hide action. 
>
> ***Sneak Attack (1/Turn).*** The spy deals an extra 5 (2d4) damage when it hit s a target with a weapon attack and has advantage on the attack roll, or when the target is within 5 feet of an ally of the spy that isn't incapacitated and the spy doesn't have disadvantage on the attack roll.
>
> ### Actions
> ***Multiattack.*** The spy makes two attacks with its shortsword.
>
> ***Shortsword.*** *Melee Weapon Attack:* +4 to hit, reach S ft., one target. *Hit:* 5 (1d6 + 2) piercing damage.
>
> ***Hand Crossbow.*** *Ranged Weapon Attack:* +4 to hit, range 30/120 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage.

In the hunt for vital information, employing a **spy** is always a sure-fire approach -- and in a world led by war, they can be rather commonplace. Two organizations particularly well known for the art are the *Shattered Hand* for the Horde and the *SI:7* for the Alliance. 


\columnbreak


___
> ## Thug <!-- https://wc5e-cr-calculator.frogvall.com/?0;12;13;4;12;8;0;8;0;8;0;0;0;0;0;0;0;;;;;2;;;;;;;;;;1;;;1;;;;;10;;;;;;;;;;; -->
>*Medium humanoid (any race), any non-good alignment*
> ___
> - **Armor Class** 12 (leather armor)
> - **Hit Points** 13 (2d8 + 4)
> - **Speed** 30 ft.
>___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |14 (+2)|13 (+1)|14 (+2)|10 (+0)|10 (+0)|11 (+0)|
>___
> - **Skills** Intimidation +2, Sleight of Hand +3
> - **Senses** passive Perception 10
> - **Languages** any one language (usually Common)
> - **Challenge** 1/2 (100 XP)
> ___
>
> ***Pack Tactics.*** The thug has advantage on an attack roll against a creature if at least one of the thug's allies is within 5 feet of the creature and the ally isn't incapacitated.
>
> ***Hit and Run.*** If the thug makes a melee attack against a creature, that creature can't make opportunity attacks against it for the rest of the thug's turn.
>
> ### Actions
> ***Multiattack.*** The thug makes two dagger attacks.
>
> ***Dagger.*** *Melee Weapon Attack:* +4 to hit, reach 5 ft, one creature. *Hit:* 4 (1d4 + 2) piercing damage.

Anyone looking to get ahead in the criminal underworld knows to pay for some muscle, as a deterrent against any would-be attackers. These **thugs** will thirst for action and spend little time bothering 
<br /> with niceties.


<img src="https://i.imgur.com/ZhrJawL.png" style="position:absolute;bottom: -45px;right: -10px;width: 810px;transform:scaleX(-1);">

<div class='footnote'>APPENDIX B: NONPLAYER CHARACTERS </div>

\pagebreakNum

<div style='margin-top:415px;'></div>

___ 
> ## Tribal Warrior <!-- https://wc5e-cr-calculator.frogvall.com/?0;14;11;4;12;5;0;5;0;5;0;0;0;0;0;0;0;;;;;2;;;;;;;;;;1;;;1;;;;;10;;;;;; -->
>*Medium humanoid (any race), any alignment*
> ___
> - **Armor Class** 14 (hide armor, shield)
> - **Hit Points** 11 (2d8 + 2)
> - **Speed** 30 ft.
>___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |14 (+2)|11 (+0)|12 (+1)| 8 (-1)|11 (+0)| 8 (-1)|
>___
> - **Senses** passive Perception 10
> - **Languages** any one language
> - **Challenge** 1/4 (50 XP)
> ___
>
> ***Pack Tactics.*** The warrior has advantage on an attack roll against a creature if at least one of the warrior's allies is within 5 feet of the creature and the ally isn't incapacitated.
>
> ***Charge (Recharges after a Short or Long Rest).*** The warrior takes the Dash action. If it moves at least 20 feet straight towards a target it can make one weapon attack against it with advantage.
>
> ### Actions
>
> ***Handaxe.*** *Melee or Ranged Weapon Attack:* +4 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 5 (1d6 + 2) slashing damage.


Tribal societies can be found far and wide across Azeroth -- trolls, tauren, ogres, naga, the humans of Arathi before they became an empire, and many more still. A common denom­inator among them are the brave and bold **tribal warriors** who patrol their borders. 


\columnbreak

<div style='margin-top:435px;'></div>

___
> ## Veteran <!-- https://wc5e-cr-calculator.frogvall.com/?0;17;78;5;12;20;0;20;0;20;0;0;0;0;0;0;0;;;;;2;;;;;;;;;;1;;;;;;;;10;;;;;;;;;;; -->
>*Medium humanoid (any race), any alignment*
> ___
> - **Armor Class** 17 (splint)
> - **Hit Points** 78 (12d8 + 24)
> - **Speed** 30 ft.
>___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |16 (+3)|13 (+1)|14 (+2)|10 (+0)|11 (+0)|10 (+0)|
>___
> - **Skills** Athletics +5, Perception +2
> - **Senses** passive Perception 12
> - **Languages** any one language (usually Common)
> - **Challenge** 3 (700 XP)
> ___
>
> ### Actions
>
> ***Multiattack.*** The veteran makes two longsword attacks. If it has a shortsword drawn, it can also make a shortsword attack.
>
> ***Longsword.*** *Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with two hands.
>
> ***Shortsword.*** *Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage.

Azeroth has seen countless wars, and a **veteran** of one is likely to be a veteran of many. Well-respected by their peers, it is not uncommon even for a long-retired veteran to still know their training by heart.


<img src="https://i.imgur.com/WRgZf6j.jpg" style="position:absolute;top: -50px;left: -30px;width: 940px;">
<img src="https://i.imgur.com/MVDaLa2.png" style="position:absolute;bottom:-120px;left:0px;width:830px;transform: rotate(180deg) scaleX(-1);">

<div class='footnote'>APPENDIX B: NONPLAYER CHARACTERS </div>

\pagebreakNum


___
> ## Warlock <!-- https://wc5e-cr-calculator.frogvall.com/?1;15;181;7;15;76;0;56;0;44;0;0;0;0;0;0;0;;;;;2;;;;;;;;;;1;;;;;;;;10;;;;;;;7;6;5;14;Fel%20Flame;Shadow%20Bolt;Fire%20and%20Brimstone;Chill%20Touch;Arms%20of%20Hadar;Circle%20of%20Death;Fire%20Storm;Immolation;Negative%20Energy%20Flood;Ray%20of%20Sickness;Sickening%20Radiance -->
> *Medium humanoid (any race), any alignment*
> ___
> - **Armor Class** 12 (15 with *demon skin*)
> - **Hit Points** 181 (32d8 + 37)
> - **Speed** 30 ft.
>___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> | 9 (-1)|14 (+2)|12 (+1)|17 (+3)|12 (+1)|11 (+0)|
>___
> - **Saving Throws** Int +7, Wis +5
> - **Skills** Arcana +7, History +7
> - **Damage Resistances** necrotic
> - **Senses** passive Perception 11
> - **Languages** any four languages
> - **Challenge** 9 (5,000 XP)
> ___
> ***Hellfire.*** Fire damage the warlock deals ignores fire resistance and treats immunity as resistance instead.
>
> ***Innate Spellcasting.*** The warlock's innate spellcasting ability is Intelligence (spell save DC 15). It can innately cast *circle of death* and *fire storm* each once per day, requiring no material components.
>
> ***Spellcasting.*** The warlock is a 14th-level spellcaster. Its spellcasting ability is Intelligence (spell save DC 15, +7 to hit with spell attacks). It regains its expended spell slots when it finishes a short or long rest. It knows the following warlock spells:
>
> Cantrips (at will): *blade ward*, *chill touch*, ✦ *fel flame*, <br/>   *mage hand*, ✦ *shadow bolt*
> <br/> 1st - 5th level (4 5th level slots): *arms of hadar*, <br/>   *bestow curse*, ✦ *demon skin*, *far step* ^XGE^, ✦ *fire and <br/>    brimstone*, *fear*, *immolation* ^XGE^, *negative energy <br/>   flood* ^XGE^, *ray of sickness*, *sickening radiance* ^XGE^
>
> The warlock cast *demon skin* on itself before combat. This adds 5 hit points to its max hp (included above).
>
> ### Actions
> ***Dagger.*** *Melee or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range 20ft./60 ft., one target. Hit: 4 (1d4 + 2) piercing damage plus 7 (2d6) fire damage.
>
> ***Drain Life.*** *Ranged Spell Attack:* +7 to hit, range 30 ft., one creature. *Hit:* The creature takes 9 (2d8) necrotic damage and the warlock regains a number of hit points equal to half the damage dealt. 
> <br/>   The creature must also make a DC 15 Constitution saving throw or have their maximum hit point total reduced by the amount of damage taken until their next long rest. This cannot reduce their maximum hit point total below 1.

Sharply intelligent, immensely powerful, and often sardonic in nature, a **warlock** would seldom bother with people they perceive as inferior -- which is often most of them. Their demonic powers have them often, though not always, keeping some semblance loyalty to the Burning Legion. 

\columnbreak


<img src="https://i.imgur.com/tiU4RnD.png" class="inkblot" style="width:760px; top:0px; right:-230px; transform: rotate(-20deg);" />
<img src="https://i.imgur.com/Wxj4KMG.png" style="position:absolute;bottom: -55px;right: -35px;width: 930px;">

<div class='footnote'>APPENDIX B: NONPLAYER CHARACTERS </div>


\pagebreakNum


<div style='margin-top:760px;'></div>

___
___
> ## War Mage <!-- https://wc5e-cr-calculator.frogvall.com/?2;15;234;9;17;108;13;98;13;90;8;0;0;0;0;0;0;;;;1;2;;;;;;;;;;1;;;;;;;;10;;;;;;;9;8;7;17;Arcane%20Explosion;Blizzard;Frostfire%20Bolt;Ice%20Nova;Fire%20Bolt;Ray%20of%20Frost;Burning%20Hands;Cone%20of%20Cold;Fire%20Storm;Ice%20Storm;Scorching%20Ray -->
>*Medium humanoid (any race), any alignment*
> ___
> - **Armor Class** 12 (15 with *mage armor*)
> - **Hit Points** 234 (36d8 + 72)
> - **Speed** 30 ft.
>___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |10 (+0)|14 (+2)|14 (+2)|18 (+4)|14 (+2)|16 (+3)|
>___
> - **Saving Throws** Int +9, Wis +7
> - **Skills** Arcana +9, Intimidation +8, Perception +7
> - **Senses** passive Perception 17
> - **Languages** any two languages
> - **Challenge** 14 (11,500 XP)
> ___
>
> ***Empowered Evocation.*** The mage can add its Intelligence modifier to damage rolls of any mage evocation spell it casts.
>
> ***Metamagic (2/Day).*** The mage can use metamagic to twist its spells with one of the following effects: 
>
> * ***Distant Spell.*** The mage can use its metamagic when it casts a spell that has a range of 5 feet or greater to double the range of the spell.
>
> * ***Empowered Spell.*** The mage can use its metamagic when it rolls damage for a spell to reroll up to 4 damage dice. It must then use the new damage rolls.
>
> <br/> ***Spellcasting.*** The mage is an 17th-level spellcaster. Its spellcasting ability is Intelligence (spell save DC 17, +9 to hit with spell attacks). The mage has the following mage spells prepared:
>
> Cantrips (at will): *blade ward*, *fire bolt*, *light*, *mage hand*, <br/>   *ray of frost*
> <br/> 1st level (4 slots): *burning hands*, *feather fall*, <br/>   ✦ *frostfire bolt*, *mage armor*
> <br/> 2nd level (3 slots): *hold person*, *misty step*, *scorching <br/>   ray*
> <br/> 3rd level (3 slots): ✦ *blizzard*, *counterspell*, *slow*
> <br/> 4th level (3 slots): ✦ *arcane explosion*, *fire shield*, *ice <br/>   storm*
> <br/> 5th level (2 slots): *cone of cold*, *wall of force*
> <br/> 6th level (1 slot): *globe of invulnerability*
> <br/> 7th level (1 slot): *fire storm*
> <br/> 8th level (1 slot): ✦ *ice nova*
> <br/> 9th level (1 slot): *imprisonment*
>
> The mage casts *mage armor* on itself before combat.
>
> ### Actions
>
> ***Multiattack.*** The mage makes two melee attacks.
>
> ***Scimitar.*** *Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 9 (2d6 + 2) slashing damage.
>
> ### Reactions
>
> ***Arcane Deflection.*** When the mage is attacked by a spell, it can use its reaction to gain +2 AC or +4 to saving throws against that spell. 

Some arcanists devote their life to the art of warfare, taking on the title of **war mages**. They keep a keen mind for tactical and scholarly matters alike, and are often among the most respected advisors to leaders. Some such mages are even charismatic leaders in their own right.

\columnbreak


<img src="https://i.imgur.com/PirsUGQ.jpg" style="position:absolute;top:-25px;left: -15px;width: 840px;">
<img src='https://i.imgur.com/C2bOp8u.png' style='position:absolute; top:350px; right:-10px; width:820px;' />
<img src="https://i.imgur.com/tiU4RnD.png" class="inkblot" style="width:700px; bottom:-540px; right:25px; transform:rotate(56deg);" />
 
<div class='footnote'>APPENDIX B: NONPLAYER CHARACTERS </div>
 

\pagebreakNum


<style>

/* BACK PAGE STYLES */

  /* Remove footer from back page, replace pX with last page number */
  .phb#p21:after { display:none; }

 -cover-content {
    padding-left: 4px;
    padding-right: 16px;
  }
  .phb .back-cover-right {
      padding-left: 40px;
  }
  .phb .back-cover-image {
    height: 1136px;
    left: -20px;
    top: -10px;
    width: 475px;
    background-size: 475px 1136px;
  }
  .phb .back-cover-header p {
    line-height: 76px;
  }
  .phb .back-cover-diamond {
    display: block;
    position: initial;
    left: initial;
    top: initial;
    margin: auto;
    margin-bottom: 35px;
    box-sizing: border-box;
    background-repeat: no-repeat;
  }
 .phb .back-cover-logo-container {
    position: absolute;
    bottom: 30px;
    left: 64px;
    width: 314px;
 }
 .phb .back-cover-logo,
 .phb .back-cover-logo-link {
     position: initial;
     margin: auto;
     margin-bottom: 8px;
     left: initial;
     bottom: initial;
     right: initial;
     background-repeat: no-repeat;
 }
 
 </style>
 
 <img src='https://www.gmbinder.com/images/4UrFsXk.jpg' style="position:absolute; right:-194px; bottom:0px; height:1160px;" />
 
 <div class='back-cover-image'></div>
 
 <div style='margin-top:20px;'></div>
 
 <div class='back-cover-header'>
 
 Warcraft
 
 5th Edition
 
 </div>
 
<div class='back-cover-text'>
 
  *Part of the WC5E Manual of Monsters v3*
 
  This document is a part of an upcoming update (as of writing this) to our *Warcraft 5th Edition Manual of Monsters*; a massive tome of creatures and NPCs adapted from the Warcraft universe to be used in Dungeons & Dragons. 

  We're a cozy little gang of people having fun writing this material in our spare time, and are always looking for people to join us, chat with us, and tell us what they think. If you'd like to do just that, this is where you can find us:
  
  [Our project on Github](https://github.com/WC5E/Warcraft-5e-Conversion/) <br />
  [Our community on Reddit](https://www.reddit.com/r/wc5e/) <br />
  [Our community on Discord](https://discord.com/invite/dKMJmmD)
  
</div>
 
<div class='back-cover-diamond' style='top: 679px;'></div>
 
<div style='margin-top:35px;'></div>
 
<div class='back-cover-close'>

  Big love from the team. ❤
   
</div>

<div class='back-cover-logo-container'>
 
  <div class='back-cover-logo'></div>
 
  <div class='back-cover-logo-link'>
 
  [WWW.GMBINDER.COM](https://www.gmbinder.com)
 
  </div>

</div>
 
 \columnbreak
 

<div class='back-cover-right'>

</div>
