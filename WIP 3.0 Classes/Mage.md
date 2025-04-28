<style>
/* GLOBAL FORMATTING  */

  /* Resize page to international A4 */
  .phb {
    width: 210mm;
    height: 296.8mm;
  }
  .phb:after { content: ""; }

/* Temporary Fix for heading issues */
    .phb p{ line-height: 15px; } 
    .phb blockquote p{ line-height: 14px; } 
    .phb h2{ line-height: 26px; } 
    .phb h3{ line-height: 19px; } 
    .phb h4{ line-height: 15px; padding-bottom: 3px; } 
    .phb h5{ line-height: 17px; } 
    th, td { line-height: 14px; }

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
  one of the ink blotstyle classes below. Essentially:
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
  
  /* Bottom metalwork art */
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
  /* Bottom metalwork art */
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

  /* Footer with white text against dark backgrounds */
  .phb .footnote.footnote-white,
  .phb .footnote.footnote-white + .pageNumber,
  .phb .footnote.footnote-white + section .pageNumber {
    color: rgba(255,255,255,0.8);
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
    left      : 12px;
}
.phb:nth-child(odd) .pageNumber.auto{
    right      : 12px;
}

/* Use black tones for statblock backgrounds */
.phb blockquote {
  box-shadow: 1px 4px 14px rgba(0,0,0,0.42);
}

</style>

<div style='margin-top:552px'></div>

## Mage
*Always remember that power is a double-edged blade. One side light, the other dark. It calls to you, where you are most desperate; when victory seems worth any sacrifice. There is a price to be paid for such a gift, and many eagerly accept the bargain. Power alone is not to be feared. <br>Fear, instead, those who wield it.*
<div style="text-align:Right">

*— Jaina Proudmoore* <br/>  </div> 

Clad in a golden robe, a blood elf closes her eyes to shut out the distractions of the battlefields and begins her quiet chant. Fingers weaving in front of her, she completes her spell and launches a bead of fire toward the enemy ranks, where it erupts into an engulfing conflagration.

The air shimmers as a draenei lifts his hands above his head to twist the air around him into. A barrier of force engulfs him, blocking a barrage of attacks against him

Golden eyes flashing, a human stomps his foot into the ground as a crippling fire sets him ablaze, as swords clash against him. An inferno of fire spews out at the attackers, engulfing them in hellfire.

Mages are supreme magic-users, defined and united as a class by the spells they cast. Drawing on the leylines of magic that permeates Azeroth, mages cast spells of explo-sive fire, arcing lightning, and subtle deception. Their magic can conjure monsters from other planes of exis-tence, or catch a glimpse the future. Their mightiest spells change one substance into another, call meteors down from the sky, or open portals across continents.

\columnbreak

<div style='margin-top:317px'></div>

### Masters of Time and Space
Students gifted with a keen intellect and unwavering discipline may walk the path of the mage. The arcane magic available to magi is both great and dangerous, and thus is revealed only to the most devoted practitioners. 

To avoid interference with their spellcasting, mages wear only cloth armor, but arcane shields and enchantments give them additional protection. From afar, they summon bursts of fire that can set entire fields ablaze, and conjure forth blizzard strong enough to shatter bones. 

The most powerful among them can even generate enhancements and portals, assisting allies by sharpening their minds and transporting them instantly across the world.


### Scholars of the Arcane
Wild and enigmatic, varied in form and function, the power of magic draws students who seek to master its mysteries. Some aspire to become like the titans, shaping reality itself. Though the casting of a typical spell requires merely the utterance of a few strange words, fleeting gestures, and sometimes a pinch or clump of exotic materials, these surface components barely hint at the expertise attained after years of apprenticeship and countless hours of study.

### The Lure of Knowledge
Mages' lives are seldom mundane. The closest a mage is likely to come to an ordinary life is working as a sage or lecturer in a library or university, teaching others the secrets of the multiverse. But the lure of knowledge and power calls even the most unadventurous mages out of the safety of their libraries and laboratories and into crumbling ruins and lost cities.

### Creating a Mage
Creating a mage character demands a backstory dominat­ed by at least one extraordinary event. How did you first discover your aptitude for magic? Did you have a natural talent, or were you the studious apprentice of another mage? Or perhaps you encountered a magical creature, or an old tome rich in arcane secrets?

What then drew you forth to adventure? Did you learn of a secret trove of spells and power lost to the ages, or are you seeking knowledge that no book can teach?


<div class='footnote'>PART 1 | CLASSES</div>
<img src='https://www.gmbinder.com/images/4bKo7jE.jpg' style='position:absolute; top:-200px; right:-150px; width:1000px' />
<img src='https://www.gmbinder.com/images/vn90cy3.png' style='position:absolute; top:-300px; right:0px; width:1100px' />
<img src='https://www.gmbinder.com/images/dYHZ0Ix.png' style='position:absolute; top:30px; right:325px; width:650px' />

\pagebreakNum

<div class='classTable wide'>

##### The Mage
| Level | Proficiency<br/>Bonus | Sorcery<br/>Points | | Features | Cantrips<br/>Known | |1st| |2nd| |3rd| |4th| |5th| | 6th| |7th| |8th| |9th <div style="position: absolute; top:100px; right:113px; width:200px; height:25px">—Spell Slots per Spell Level—</div>|
|:---:|:--:|:-:|-|:----------|:-:|-|:-:|-|:-:|-|:-:|-|:-:|-|:-:|-|:-:|-|:-:|-|:-:|-|:-:|
| 1st | +2 | —|| Spellcasting, Magic Sense                              |3||2||—||—||—||—||—||—||—||—|
| 2nd | +2 | 2|| Font of Magic, Magical Study                           |3||3||—||—||—||—||—||—||—||—|
| 3rd | +2 | 3|| Metamagic, Cantrip Formulas                                              |3||4||2||—||—||—||—||—||—||—|
| 4th | +2 | 4|| Ability Score Improvement                              |4||4||3||—||—||—||—||—||—||—|
| 5th | +3 | 5|| —                                                      |4||4||3||2||—||—||—||—||—||—|
| 6th | +3 | 6|| Magical Study feature                                  |4||4||3||3||—||—||—||—||—||—|
| 7th | +3 | 7|| —                                                      |4||4||3||3||1||—||—||—||—||—|
| 8th | +3 | 8|| Ability Score Improvement                              |4||4||3||3||2||—||—||—||—||—|
| 9th | +4 | 9|| —                                                      |4||4||3||3||3||1||—||—||—||—|
| 10th| +4 |10|| Magical Study feature, Metamagic                      |4||4||3||3||3||2||—||—||—||—|
| 11th| +4 |11|| —                                                      |5||4||3||3||3||2||1||—||—||—|
| 12th| +4 |12|| Ability Score Improvement                              |5||4||3||3||3||2||1||—||—||—|
| 13th| +5 |13|| —                                                      |5||4||3||3||3||2||1||1||—||—|
| 14th| +5 |14|| Magical Study feature                                  |5||4||3||3||3||2||1||1||—||—|
| 15th| +5 |15|| —                                                      |5||4||3||3||3||2||1||1||1||—|
| 16th| +5 |16|| Ability Score Improvement                              |5||4||3||3||3||2||1||1||1||—|
| 17th| +6 |17|| Metamagic                                             |5||4||3||3||3||2||1||1||1||1|
| 18th| +6 |18|| Spell Mastery                                          |5||4||3||3||3||3||1||1||1||1|
| 19th| +6 |19|| Ability Score Improvement                              |5||4||3||3||3||3||2||1||1||1|
| 20th| +6 |20|| Signature Spell                                        |5||4||3||3||3||3||2||2||1||1|
</div>



#### Optional Rule: Multiclassing
If your group uses the optional rule on multiclassing in the *Player's Handbook*, here's what you need to know if you choose mage as one of your classes.

***Ability Score Minimum.*** As a multiclass character, you must have at least an Intelligence score of 13 to take a level in this class, or to take a level in another class if you are already a mage.

***Proficiencies Gained.*** You do not receive any additional proficiencies when you take a level in mage if it isn't your initial class.

***Spell Slots.*** Add your levels in the mage class to the appropriate levels from other class to determine your available spell slots.

#### Quick Build
You can make a mage quickly by following these sugges-tions. First, lntelligence should be your highest ability score, followed by Constitution or Dexterity. Second, choose the sage background. 

Third, choose the *light* and *mage hand* cantrips, as well as one other cantrip, along with the following 1st-level spells for your spellbook: *burning hands*, *detect magic*, *feather fall*, *frostfire bolt*, *mage armor*, and *magic missile*.


\columnbreak

## Class Features
As a mage, you gain the following class features.

#### Hit Points
___
- **Hit Dice:** 1d6 per mage level
- **Hit Points at 1st Level:** 6 + your Constitution modifier
- **Hit Points at Higher Levels:** 1d6 (or 4) + your Constitution modifier per mage level after 1st

#### Proficiencies
___
- **Armor:** None
- **Weapons:** Simple weapons
- **Tools:** None
___
- **Saving Throws:** Intelligence, Wisdom
- **Skills:** Choose two from Arcana, History, Insight, Investigation, Medicine, and Religion

#### Equipment
You start with the following equipment, in addition to the equipment granted by your background:
 - *(a)* a quarterstaff or *(b)* a dagger
 - *(a)* a component pouch or *(b)* an arcane focus
 - *(a)* a scholar's pack or *(b)* an explorer's pack
 - A spellbook

<div class='footnote'>PART 1 | CLASSES</div>

\pagebreakNum

### Spellcasting
*1st-level mage feature* 
<div style='margin-top:-4px'></div>

As a student of arcane, you own a spellbook with spells that show the glimmerings of your true power. See chapter 10 of Player's Handbook for the general rules of spellcasting and chapter 6 of this book for the mage spell list.

#### Cantrips
At 1st level, you know three cantrips of your choice from the mage spell list. You learn additional mage cantrips of your choice at higher levels, as shown in the Cantrips Known column of the Mage table.

<div style='margin-top:30px;'></div>

> ##### Your Spellbook
> The spells that you add to your spellbook as you gain levels reflect the arcane research you conduct on your own, as well as intellectual breakthroughs you have had about the nature of the multiverse. You might find other spells during your adventures. You could discover a spell re-corded on a scroll in an evil sorcerer's chest, for example, or in a dusty tome in an ancient library.
>
> ***Copying a Spell into the Book.*** When you find a mage spell of 1st level or higher, you can add it to your spellbook if it is of a level for which you can prepare and if you can spare the time to decipher and copy it.
>
> Copying a spell into your spellbook involves reproducing the basic form of the spell, then deciphering the unique system of notation used by the mage who wrote it. You must practice the spell until you understand the sounds or gestures required, then transcribe it into your spellbook using your own notation.
>
> For each level of the spell, the process takes 2 hours and costs 50 gp. The cost represents material components you expend as you experiment with the spell to master it, as well as the fine inks you need to record it. Once you have spent this time and money, you can prepare the spell just like your other spells.
>
> ***Replacing the Book.*** You can copy a spell from your own spellbook into another book — for example, if you want to make a backup copy of your spellbook. This is just like copying a new spell into your spell­book, but faster and easier, since you understand your own notation and already know how to cast the spell. You need spend only 1 hour and 10 gp for each level of the copied spell.
>
> If you lose your spellbook, you can use the same procedure to transcribe the spells that you have prepared into a new spellbook. The remainder of your spellbook requires you to find new spells to do so, as normal. Many mages keep backup spellbooks in a safe place.
>
> ***The Book's Appearance.*** Your spellbook is a unique compilation of spells, with its own decorations and margin notes. It might be a plain, functional leather volume that you re-ceived as a gift, a finely bound gilt-edged tome you found in an ancient library, or even a loose collection of notes scrounged together after you lost your previous spellbook in a mishap.

\columnbreak

#### Spellbook
You have a spellbook containing six 1st-level mage spells of your choice. Your spellbook does not contain your known cantrips.

#### Preparing and Casting Spells
The Mage table shows how many spell slots you have to cast your spells of 1st level and higher. To cast one of these spells, you must expend a slot of the spell's level or higher. You regain expended spell slots when you finish a long rest.

You prepare the list of mage spells that are available for you to cast. To do so, choose a number of mage spells from your spellbook equal to your Intelligence modifier + your mage level (minimum of one spell). The spells must be of a level for which you have spell slots.

For example. if you're a 3rd-level mage, you have four <br/> 1st-level and two 2nd-level spell slots. With an Intelligence of 16, your list of prepared spells can include six spells of 1st or 2nd level, in any combination, chosen from your spellbook. If you prepare the 1st-level spell *magic missile*, you can cast it using a 1st-level or a 2nd-level slot. Casting the spell doesn't remove it from your list of prepared.

You can change your list of prepared spells when you finish a long rest. Preparing a new list of mage spells requires time spent studying your spellbook and memori-zing the incantations and gestures you must make to cast the spell: 1 minute per spell level for each spell on your list.

#### Spellcasting Ability
Intelligence is your spellcasting ability for your mage spells, since you learn your spells through dedicated study and memorization. You use your Intelligence whenever a spell refers to your spellcasting ability. In addition, you use your Intelligence modifier when setting the saving throw DC for a mage spell you cast and when making an attack roll.

<div style="text-align: Center">

**Spell save DC** = 8 + your proficiency bonus + <br/> your Intelligence modifier

**Spell attack modifier** = your proficiency bonus + <br/> your Intelligence modifier
</div>

#### Ritual Casting
You can cast a mage spell as a ritual if that spell has the ritual tag and you have the spell in your spellbook. You don't need to have the spell prepared.

#### Spellcasting Focus
You can use an arcane focus as a spellcasting focus for your mage spells.

#### Learning Spells of 1st Level and Higher
Each time you gain a mage level, you add two mage spells of your choice to your spellbook. Each of these spells must be of a level for which you have spell slots, as shown on the Mage table. On your adventurers, you might find other spells that you can add to your spellbook (see the "Your Spellbook" sidebar).

### Magic Sense
*1st-level mage feature* 
<div style='margin-top:-4px'></div>

Your studies taught you how to sense residual magical energy. You can sense when a spell was cast within the last hour at your current location and see writing created or used by magic that is hidden to others. As long as you understand the language you can also decipher and read it.

<div class='footnote'>PART 1 | CLASSES</div>

\pagebreakNum

Additionally you can create hidden magical writing in any language you know.

Others spot the message's presence with a successful DC 15 Wisdom (Perception) check but can't decipher it without magic.

### Font of Magic
*2nd-level mage feature* 
<div style='margin-top:-4px'></div>

You tap into a deep wellspring of magic within yourself. This wellspring is represented by sorcery points, which allow you to create a variety of magical effects.

#### Sorcery Points
You have 2 sorcery points, and you gain more as you reach higher levels, as shown in the Sorcery Points column of the Mage table. You can never have more sorcery points than shown on the Mage table for your level. You regain all spent sorcery points when you finish a long rest.

#### Flexible Casting
You can use your sorcery points to gain additional spell slots, or sacrifice spell slots to gain additional sorcery points. You learn other ways to use your sorcery points as you reach higher levels.

***Creating Spell Slots***
You can transform unexpended sorcery points into one spell slot as a bonus action on your turn. The created spell slots vanish at the end of a long rest. The Creating Spell Slots table shows the cost of creating a spell slot of a given level. You can create spell slots no higher in level than 5th.

##### Creating Spell Slots
| Spell Slot Level  | Sorcery Point Cost |
|:-----:|:-----:|
| 1st   |   2   |
| 2nd   |   3   |
| 3rd   |   5   |
| 4th   |   6   |
| 5th   |   7   |

***Converting a Spell Slot to Sorcery Points.*** As a bonus action on your turn, you can expend one spell slot and gain a number of sorcery points equal to the slot's level.

### Magical Study
*2nd-level mage feature* 
<div style='margin-top:-4px'></div>

You choose a magical study, shaping your practice of magic through one of three areas: Arcane, Fire or Frost, all detailed at the end of the class description.

Your choice grants you features at 2nd level and again at 6th, 10th, and 14th level.

### Metamagic
*3rd-level mage feature* 
<div style='margin-top:-4px'></div>

At 3rd level, you gain the ability to twist your spells to suit your needs. You gain two of the following Metamagic options of your choice. You gain another one at 10th and 17th level. You can use only one Metamagic option on a spell when you cast it, unless otherwise noted.

\columnbreak

#### Careful Spell
When you cast a spell that forces other creatures to make a saving throw, you can protect some of those creatures from the spell's full force. To do so, you spend 1 sorcery point and choose a number of those creatures up to your Intelligence modifier (minimum of one creature). 

A chosen creature automatically succeeds on its saving throw against the spell.

#### Distant Spell
When you cast a spell that has a range of 5 feet or greater, you can spend 1 sorcery point to double the spell's range.

When you cast a spell that has a range of touch, you can spend 1 sorcery point to have the spell's range be 30 feet.

#### Empowered Spell
When you roll damage for a spell, you can spend 1 sorcery point to reroll a number of the damage dice up to your Intelligence modifier (minimum of 1). You must then use the new damage rolls.

You can use Empowered Spell even if you have already used a different Metamagic option during the casting of the spell.

#### Extended Spell
When you cast a spell that has a duration of 1 minute or longer, you can spend 1 sorcery point to double its duration, to a maximum duration of 24 hours.

#### Heightened Spell
When you cast a spell that forces a creature to make a saving throw to resist its effects, you can spend 3 sorcery points to give one target of the spell disadvantage on its first saving throw made against the spell.

#### Quickened Spell
When you cast a spell that has a casting time of 1 action, you can spend 2 sorcery points to change the casting time to 1 bonus action for this casting.

#### Subtle Spell
When you cast a spell, you can spend 1 sorcery point to cast it without any somatic or verbal components.

#### Twinned Spell
When you cast a spell that targets only one creature and doesn't have a range of self, you can spend a number of sorcery points equal to the spell's level to target a second creature in range with the same spell (1 sorcery point if the spell is a cantrip).

To be eligible, a spell must be incapable of targeting more than one creature at the spell's current level. For example, *magic missile* and *scorching ray* aren't eligible, but *ray of frost* and *chromatic orb* are.

<br/>

> #### Optional Class Features
> Additional Metamagic options can been seen on page 65 of Tasha's Cauldron of Everything.

<div class='footnote'>PART 1 | CLASSES</div>

\pagebreakNum

### Cantrip Formulas
*3rd-level mage feature* 
<div style='margin-top:-4px'></div>

You have scribed a set of arcane formulas in your spellbook that you can use to formulate a cantrip in your mind. Whenever you finish a long rest and consult those formulas in your spellbook, you can replace one mage cantrip you know with another cantrip from the mage spell list.

### Ability Score Improvement
*4th-level mage feature* 
<div style='margin-top:-4px'></div>

When you reach 4th level, and again at 8th, 12th, 16th, and 19th level, you can increase one ability score of your choice by 2. or you can increase two ability scores of your choice by 1. As normal, you can't increase an ability score above 20 using this feature.

<div class='footnote'>PART 1 | CLASSES</div>

### Spell Mastery
*18th-level mage feature* 
<div style='margin-top:-4px'></div>

You have achieved such mastery over certain spells that you can cast them at will. Choose a 1st-level mage spell and a 2nd-level mage spell that are in your spell­book. 

You can cast those spells at their lowest level without expending a spell slot when you have them prepared. If you want to cast either spell at a higher level, you must expend a spell slot as normal.

You can spend 8 hours in study, and change one or both of the spells you chose for different spells of the same level.

### Signature Spells
*20th-level mage feature* 
<div style='margin-top:-4px'></div>

You gain mastery over two powerful spells and can cast them with little effort. Choose two 3rd-level mage spells in your spellbook as your signature spells. You always have these spells prepared, they don't count against the number of spells you have prepared, and you can cast each of them once at 3rd level without expending a spell slot. 

When you do so, you can't do so again until you finish a short or long rest. If you want to cast either spell at a higher level, you must expend a spell slot as normal.

## Magical Studies
Mages are spellcasters who favor magics involving the cardinal elements of the universe. Students gifted with a keen intellect and unwavering discipline may walk the path of the mage. The magic available to mages is both great and dangerous, and thus is revealed only to the most devoted practitioners.

\columnbreak

### Study of Arcane
Mages of the arcane are diviners of secrets, balancing the ebb and flow of incredible mystic energies. These practi-tioners push their magical knowledge to its very limits. Those who master this craft are capable to manipulate spells on a much more primal level.

#### Bonus Cantrip
*2nd-level Study of Arcane feature* 
<div style='margin-top:-4px'></div>

When you choose this magical study at 2nd level, you learn the *prestidigitation* cantrip. If you already know this cantrip, you learn a different mage cantrip of your choice. The cantrip doesn't count against your number of cantrips known.

#### Arcane Charges
*2nd-level Study of Arcane feature* 
<div style='margin-top:-4px'></div>

You gain the ability to conserve and enhance your mage abilities beyond the norm. Whenever you cast a mage spell of 1st level or higher, gain an arcane charge of the equivalent level up to 5th level. Spells slots higher than 5th give a 5th level arcane charge. These charges last until they are used, replaced by a higher level charge, or after 1 minute has passed.

You may expend an arcane charge to grant yourself one of the following effects. This effect lasts until the end of your next turn.

- As a bonus action, you can add a bonus equal to the arcane charge's level to Attack and Damage rolls for your next Mage Spell.
- As a bonus action or reaction, you can add a bonus equal to the arcane charge's level to Saving Throws against Magic or Magical Effects.

#### Chrono Shift
*2nd-level Study of Arcane feature* 
<div style='margin-top:-4px'></div>

After rolling initiative, but before the first creature takes its turn, you can switch your result with the result of another creature that you can see. Once you've done so you can't use this feature again until you finish a long rest.

#### Arcane Brilliance
*6th-level Study of Arcane feature* 
<div style='margin-top:-4px'></div>

You gain proficiency in the Arcana skill if you don't already have it. Your proficiency bonus is doubled for any ability check you make with it.

Additionally, you are always under the effects of a *comprehend languages* spell.

<img src='https://www.gmbinder.com/images/8W9yFbL.jpg' style='position:absolute; bottom:-250px; right:-173px; width:1000px' />

<img src='https://www.gmbinder.com/images/L60ii4e.png' style='position:absolute; top:105px; left:0px; width:100%; height:100%' />

<img src='https://www.gmbinder.com/images/pbSeYXZ.png' style='position:absolute; top:0px; left:0px; transform:scaleY(-1); width:100%; height:100%' />

<img src='https://www.gmbinder.com/images/e4yq01U.png' style='position:absolute; bottom:40px; left:70px; width:285px' />

<div class='footnote footnote-white'>PART 1 | CLASSES</div>

\pagebreakNum

#### Presence of Mind
*10th-level Study of Arcane feature* 
<div style='margin-top:-4px'></div>

Whenever you create a spell slot from sorcery points you also gain an arcane charge of equivalent level and you can expend the charge as part of the same bonus action.

#### Savant
*10th-level Study of Arcane feature* 
___
<div style='margin-top:-6px'></div>

You can change your list of prepared mage spells when you finish a short or a long rest.

#### Time Warp
*14th-level Study of Arcane feature* 
___
<div style='margin-top:-6px'></div>

You can exert your control over magic to warp time itself. When a creature you can see within 60 feet of you begins their turn, you can use your reaction to allow that creature to take one additional action during its turn. When you do so, you gain one level of exhaustion.

### Study of Fire
While any worthy mage is an unparalleled expert in the use of magic and heavily dedicated to their craft, those who master the forces of fire tend to be a little more audacious than their peers. These mages take pride, even pleasure, in igniting their enemies in wild bursts of flame.

#### Bonus Cantrip
*2nd-level Study of Fire feature* 
<div style='margin-top:-4px'></div>

When you choose this magical study at 2nd level, you learn the *control flames* cantrip. If you already know this cantrip, you learn a different mage cantrip of your choice. The cantrip doesn't count against your number of cantrips known.

#### Hot Streak
*2nd-level Study of Fire feature* 
<div style='margin-top:-4px'></div>

The blazing energy of your spells intensifies. When you roll damage for a spell and roll the highest number possible on any of the dice, choose one of those dice, roll it again and add that roll to the damage. You can use the feature only once per turn.

At 10th level, you may choose any number of dice that rolled the highest number possible, you can only reroll each dice once.

#### Cauterize
*6th-level Study of Fire feature*
<div style='margin-top:-4px'></div>

If you are reduced to 0 hit points, you can use your reaction to draw on the fiery energy that burns within you. You are instead reduced to 1 hit point, and each creature within 10 feet of you takes fire damage equal to half your mage level + your Intelligence modifier.

Once you use this feature, you can’t use it again until you finish a long rest.

\columnbreak

#### Ignite
*10th-level Study of Fire feature* 
<div style='margin-top:-4px'></div>

When you deal fire damage with a spell using a spell slot, up to 5th level, you can spend up to 3 sorcery points to empower it. For each sorcery point spent, add an extra die to  the damage dealt by the spell.

For example, when you cast *burning hands* and spend 2 points, you add an extra 2d6 to the spell's damage. When you cast a spell that makes multiple attack rolls, such as *scorching ray*, you must spend the points on each attack individually.

#### Combustion
*14th-level Study of Fire feature*
<div style='margin-top:-4px'></div>

You can unleash the flames that blaze within you. As an action, you wreathing yourself in swirling fire.
For 1 minute, you gain the following benefits:

- You shed bright light in a 30-foot radius and dim light for an additional 30 feet.
- Any creature takes fire damage equal to half your mage level if it hits you with a melee attack.
- Any spell or effect you create ignores resistance to fire damage and treats immunity to fire damage as resistance to fire damage.
- You are immune to fire damage and have resistance to cold damage.
- Your spell attacks score a critical hit on a roll of 19 or 20 on the d20.

Once you use this feature, you can't use it again until you finish a long rest, unless you expend 5 sorcery points to use it again.

### Study of Frost
Frost mages stand apart from their colleagues, in that their chosen school of magic focuses on maintaining supreme control over the capabilities of their enemies. Mages who command frost perform chilling displays on the battlefield, rendering foes immobile as they bombard them with ice.

#### Bonus Cantrip
*2nd-level Study of Frost feature* 
<div style='margin-top:-4px'></div>

When you choose this magical study at 2nd level, you learn the *shape water* cantrip. If you already know this cantrip, you learn a different mage cantrip of your choice. The cantrip doesn't count against your number of cantrips known.

#### Fingers of Frost
*2nd-level Study of Frost feature* 
<div style='margin-top:-4px'></div>

You gain one of the following features of your choice:

***Ice Barrier.*** You can weave the cold around yourself for protection. When you cast a spell of 1st level or higher that deals cold damage to a creature, you can simultaneously warp part of the spell's magic to create an icy barrier on yourself that lasts until you finish a long rest. The barrier has hit points equal to twice your mage level + your Intelligence modifier. Whenever you take damage, the barrier takes the damage instead. If the damage reduces the barrier to 0 hit points, you take any remaining damage.

When the barrier is reduced to 0 hit points, each creature within 10 feet of you has their speed reduced by 10 feet until the start of your next turn as the barrier bursts.

<div class='footnote'>PART 1 | CLASSES</div>

\pagebreakNum

While the barrier has 0 hit points, it can't absorb damage, but its magic remains. Whenever you cast a spell of 1st level or higher that deals cold damage, the barrier regains a number of hit points equal to twice the level of the spell.

Once you create the barrier, you can't create it again until you finish a long rest.

***Water Elemental.*** You learn how to conjure a water elemental. It is friendly to you and your companions, and it obeys your commands. See the creature's game statistics in the water elemental stat block.

In combat, the water elemental shares your initiative count, but it takes its turn immediately after yours. It can move and use its reaction on its own, but the only action it takes on its turn is the Dodge action, unless you take a bonus action to command it to take one of the actions in its stat block or the Dash, Disengage, or Help action.

If you target the water elemental with a spell that deals cold damage, it is considered immune to the damage and regains a number of hit points equal to it. You don't need to roll to hit your elemental and it automatically fails any saving throw for it if you choose it.

At the end of a long rest, you can conjure a new water elemental. If you already have a water elemental from this feature, the first one immediately perishes.

#### Brain Freeze
*6th-level Study of Frost feature* 
<div style='margin-top:-4px'></div>

Whenever a creature takes cold damage from one of your mage spells, its movement speed is reduced by 10 feet until the end of your next turn.

When a creature has its speed reduced in this way, you can spend one sorcery point to force that creature to make a Strength saving throw against your spell save DC. On a failure, that creature is restrained for 1 minute or until a creature lands a hit against it. 

Beginning at 14th level, a creature who fails the saving throw is paralyzed instead of restrained.

#### Hands of Frost
*10th-level Study of Frost feature* 
<div style='margin-top:-4px'></div>

You gain one of the following features, depending on your choice at 2nd level.

***Ice Barrier.*** When a creature that you can see within 30 feet of you takes damage, you can use your reaction to cause your Ice Barrier to manifest around it and absorb the damage. If this damage reduces the barrier to 0 hit points, the barricaded creature takes any remaining damage.

In addition, you can now spend sorcery points to cause the effect of Brain Freeze.

***Water Elemental.*** Your water elemental changes into an ice elemental and gains the following additional benefits:

- It gains immunity to cold damage.
- Any cold damage caused by your Water elemental gains the benefits of your Brain Freeze feature.
- It can cast the *sleet storm* spell once per long rest, using your spell save DC. You still concentrate on this casting of the spell. 

#### Ring of Frost
*14th-level Study of Frost feature* 
<div style='margin-top:-4px'></div>

You can use your action to conjure up a ring of magical runes to invoke the deepest cold around a point you can see within 60 feet. The ring has a 15-foot-radius and fills a 10-foot tall cylinder with frigid cold. 

\columnbreak

<div style='margin-top:183px'></div>

___
> ## Water Elemental
>*Medium elemental, neutral*
> ___
> - **Armor Class** 13 + PB (natural armor)
> - **Hit Points** 2 + your Intelligence modifier + equal to five times your mage level (the water elemental has a number of Hit Dice [d8] equal to your mage level)
> - **Speed** 30 ft., swim 40 ft.
>___
>|STR|DEX|CON|INT|WIS|CHA|
>|:---:|:---:|:---:|:---:|:---:|:---:|
>|14 (+2)|12 (+1)|14 (+2)|4 (-3)|10 (+0)|6 (-2)|
>___
> - **Skills** Perception +2 + PB
> - **Damage Immunities** poison
> - **Condition Immunities** exhaustion, petrified, poisoned
> - **Senses** darkvision 60 ft., passive Perception 12
> - **Languages** understands the languages of its creator but can't speak
> - **Proficiency Bonus** (PB) equals your proficiency bonus
> ___
>
> #### Actions (Requires your Bonus Action) <div style='margin-top:-0px;'></div>
> ###
>
> ***Slam.*** *Melee Weapon Attack:* your spell attack modifier to hit, reach 5 ft., one target. <br/> 
*Hit:* 1d8 + 2 + PB bludgeoning damage.
>
> ***Frost Bolt.*** *Ranged Spell Attack:* your spell attack modifier to hit, range 30/60 ft., one target. <br/>
*Hit:* 1d6 + 2 + PB cold damage.
>
> ***Restore (3/day).*** The magics inside the water elemental restores 2d8 + PB hit points to itself.
>
> ### Reactions
> ***Freeze.*** When a creature within reach hits the water elemental with a melee attack, the water elemental can attempt to grapple it.

This area counts as difficult terrain for any creature other than you, and any ranged attacks made in or through it are made with disadvantage.  

Creatures who start their turn, or enters the area for the first time on a turn must succeed on a Strength saving throw against your spell save DC or become restrained for 1 minute or until they take damage. A creature fully inside this area makes the save with disadvantage. On a success, a creature still feels the effect of the cold, having their movement speed halved upon leaving the area until the end of their next turn. 

Once you use this feature, you can't use it again until you finish a long rest.

<img src='https://www.gmbinder.com/images/jIlkFOD.png' style='position:absolute; top:0px; right:0px; width:400px' />
<img src='https://www.gmbinder.com/images/huxbNse.png' style='position:absolute; top:0px; right:-25px; height:100%' />

<div class='footnote'>PART 1 | CLASSES</div>

\pagebreakNum

<style>

/* BACK PAGE STYLES */

  /* Remove footer from back page, replace pX with last page number */
  .phb#pX:after { display:none; }

  .phb .back-cover-content {
    padding-left: 4px;
    padding-right: 16px;
  }
  .phb .back-cover-header p {
    line-height: 76px;
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
 
  *WC5E Heroes Handbook v3*
 
  This document is part of the third major revision of our *Warcraft 5th Edition* project; a collection of player classes, races, backgrou&shy;nds, creature statblocks, and more to put a Warcraft spin on core Dungeons & Dragons material.

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
