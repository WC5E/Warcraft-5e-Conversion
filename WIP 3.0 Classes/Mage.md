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

<div style='margin-top:555px'></div>

## Mage
*Always remember that power is a double-edged blade. One side light, the other dark. It calls to you, where you are most desperate; when victory seems worth any sacrifice. There is a price to be paid for such a gift, and many eagerly accept the bargain. Power alone is not to be feared. <br>Fear, instead, those who wield it.*
<div style="text-align:Right">

*— Jaina Proudmoore* <br/> &nbsp;</div> 

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
Creating a mage character demands a backstory dominat&shy;ed by at least one extraordinary event. How did you first discover your aptitude for magic? Did you have a natural talent, or were you the studious apprentice of another mage? Or perhaps you encountered a magical creature, or an old tome rich in arcane secrets?

What then drew you forth to adventure? Did you learn of a secret trove of spells and power lost to the ages, or are you seeking knowledge that no book can teach?


<div class='footnote'>PART 1 | CLASSES</div>
<img src='https://www.gmbinder.com/images/4bKo7jE.jpg' style='position:absolute; top:-200px; right:-150px; width:1000px' />
<img src='https://www.gmbinder.com/images/vn90cy3.png' style='position:absolute; top:-300px; right:0px; width:1100px' />
<img src='https://www.gmbinder.com/images/dYHZ0Ix.png' style='position:absolute; top:30px; right:325px; width:650px' />

\pagebreakNum

<div class='classTable wide'>

##### The Mage
| Level | Proficiency<br/>Bonus | Sorcery<br/>Points | | Features | Cantrips<br/>Known |&nbsp;|1st|&nbsp;|2nd|&nbsp;|3rd|&nbsp;|4th|&nbsp;|5th|&nbsp;| 6th|&nbsp;|7th|&nbsp;|8th|&nbsp;|9th <div style="position: absolute; top:100px; right:113px; width:200px; height:25px">—Spell Slots per Spell Level—</div>|
|:---:|:--:|:-:|-|:----------|:-:|-|:-:|-|:-:|-|:-:|-|:-:|-|:-:|-|:-:|-|:-:|-|:-:|-|:-:|
| 1st | +2 | —|| Spellcasting, Magic Sense                              |3||2||—||—||—||—||—||—||—||—|
| 2nd | +2 | 2|| Font of Magic, Magical Study                           |3||3||—||—||—||—||—||—||—||—|
| 3rd | +2 | 3|| Metamagic                                              |3||4||2||—||—||—||—||—||—||—|
| 4th | +2 | 4|| Ability Score Improvement                              |4||4||3||—||—||—||—||—||—||—|
| 5th | +3 | 5|| —                                                      |4||4||3||2||—||—||—||—||—||—|
| 6th | +3 | 6|| Magical Study feature                                  |4||4||3||3||—||—||—||—||—||—|
| 7th | +3 | 7|| —                                                      |4||4||3||3||1||—||—||—||—||—|
| 8th | +3 | 8|| Ability Score Improvement                              |4||4||3||3||2||—||—||—||—||—|
| 9th | +4 | 9|| —                                                      |4||4||3||3||3||1||—||—||—||—|
| 10th| +4 |10|| Magical Study feature, Meta Magic                      |4||4||3||3||3||2||—||—||—||—|
| 11th| +4 |11|| —                                                      |5||4||3||3||3||2||1||—||—||—|
| 12th| +4 |12|| Ability Score Improvement                              |5||4||3||3||3||2||1||—||—||—|
| 13th| +5 |13|| —                                                      |5||4||3||3||3||2||1||1||—||—|
| 14th| +5 |14|| Magical Study feature                                  |5||4||3||3||3||2||1||1||—||—|
| 15th| +5 |15|| —                                                      |5||4||3||3||3||2||1||1||1||—|
| 16th| +5 |16|| Ability Score Improvement                              |5||4||3||3||3||2||1||1||1||—|
| 17th| +6 |17|| Meta Magic                                             |5||4||3||3||3||2||1||1||1||1|
| 18th| +6 |18|| Spell Mastery                                          |5||4||3||3||3||3||1||1||1||1|
| 19th| +6 |19|| Ability Score Improvement                              |5||4||3||3||3||3||2||1||1||1|
| 20th| +6 |20|| Signature Spell                                        |5||4||3||3||3||3||2||2||1||1|
</div>



#### Optional Rule: Multiclassing
If your group uses the optional rule on multiclassing in the *Player's Handbook*, here's what you need to know if you choose mage as one of your classes.

***Ability Score Minimum.*** As a multiclass character, you must have at least an Intelligence score of 13 to take a level in this class, or to take a level in another class if you are already a mage.

***Proficiencies Gained.*** If mage isn't your initial class, here are the proficiencies you gain when you take your first level as a mage: arcane skill.

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
 - *(a)* quarterstaff or *(b)* a dagger
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
> ***Replacing the Book.*** You can copy a spell from your own spellbook into another book — for example, if you want to make a backup copy of your spellbook. This is just like copying a new spell into your spell&shy;book, but faster and easier, since you understand your own notation and already know how to cast the spell. You need spend only 1 hour and 10 gp for each level of the copied spell.
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

For example. if you're a 3rd-level mage, you have four <br/> 1st-level and two 2nd-level spell slots. With an Intelligence of 16, your list of prepared spells can include six spells of 1st or 2nd level, in any combination, chosen from your spellbook. If you prepare the 1st-level spell magic missile, you can cast it using a 1st-level or a 2nd-level slot. Casting the spell doesn't remove it from your list of prepared.

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
You have 2 sorcery points, and you gain more as you reach higher levels, as shown in the Sorcery Points column of the Sorcerer table. You can never have more sorcery points than shown on the Mage table for your level. You regain all spent sorcery points when you finish a long rest.

#### Flexible Casting
You can use your sorcery points to gain additional spell slots, or sacrifice spell slots to gain additional sorcery points. You learn other ways to use your sorcery points as you reach higher levels.

#### Creating Spell Slots
You can transform unexpended sorcery points into one spell slot as a bonus action on your turn. The created spell slots vanish at the end of a long rest. The Creating Spell Slots table shows the cost of creating a spell slot of a given level. You can create spell slots no higher in level than 5th.

| Spell Slot Level  | Sorcery Point Cost |
|:-----:|:-----:|
|   1   |   2   |
|   2   |   3   |
|   3   |   5   |
|   4   |   6   |
|   5   |   7   |

### Magical Study
*2nd-level mage feature* 
<div style='margin-top:-4px'></div>

You choose a magical study, shaping your practice of magic through one of three areas: Arcane, Fire or Frost, all detailed at the end of the class description.

Your choice grants you features at 3rd level and again at 6th, 10th, and 14th level.

### Metamagic
*3rd-level mage feature* 
<div style='margin-top:-4px'></div>

At 3rd level, you gain the ability to twist your spells to suit your needs. You gain two of the following Metamagic options of your choice. You gain another one at 10th and 17th level. You can use only one Metamagic option on a spell when you cast it, unless otherwise noted.

#### Careful Spell
When you cast a spell that forces other creatures to make a saving throw, you can protect some of those creatures from the spell's full force. To do so, you spend 1 sorcery point and choose a number of those creatures up to your Intelligence modifier (minimum of one creature). 
A chosen creature automatically succeeds on its saving throw against the spell.

#### Distant Spell
When you cast a spell that has a range of 5 feet or greater, you can spend 1 sorcery point to double the spell's range.

When you cast a spell that has a range of touch, you can spend 1 sorcery point to have the spell's range be 30 feet.

#### Transmuted Spell
When you cast a spell that deals a type of damage from the following list, you can spend 1 sorcery point to change that damage type to one of the other listed types: acid, cold, fire, lightning, poison, thunder. 

#### Empowered Spell
When you roll damage for a spell, you can spend 1 sorcery point to reroll a number of the damage dice up to your Intelligence modifier (minimum of 1). You must then use the new damage rolls.
You can use Empowered Spell even if you have already used a different Metamagic option during the casting of the spell.

#### Extended Spell
When you cast a spell that has a duration of 1 minute or longer, you can spend 1 sorcery point to double its duration, to a maximum duration of 24 hours.

#### Heightened Spell
When you cast a spell that forces a creature to make a saving throw to resist its effects, you can spend 3 sorcery points to give one target of the spell disadvantage on its first saving throw made against the spell.

#### Quickened Spell
When you cast a spell that has a casting time of 1 action, you can spend 2 sorcery points to change the casting time to 1 bonus action for this casting.

#### Seeking Spell
When you make an attack roll for a spell and miss, you can spend 2 sorcery points to reroll the d20, though must use the new roll. You can use Seeking Spell even if you have already used a different Metamagic option during the casting of the spell. 

#### Subtle Spell
When you cast a spell, you can spend 1 sorcery point to cast it without any somatic or verbal components.

#### Twinned Spell
When you cast a spell that targets only one creature and doesn't have a range of self, you can spend a number of sorcery points equal to the spell's level to target a second creature in range with the same spell (1 sorcery point if the spell is a cantrip).
To be eligible, a spell must be incapable of targeting more than one creature at the spell's current level. For example, magic missile and scorching ray aren't eligible, but ray of frost and chromatic orb are.

### Ability Score Improvement
*4th-level mage feature* 
<div style='margin-top:-4px'></div>

When you reach 4th level, and again at 8th, 12th, 16th, and 19th level, you can increase one ability score of your choice by 2. or you can increase two ability scores of your choice by 1. As normal, you can't increase an ability score above 20 using this feature.

<div class='footnote'>PART 1 | CLASSES</div>

\pagebreakNum

### Spell Mastery
*18th-level mage feature* 
<div style='margin-top:-4px'></div>

You have achieved such mastery over certain spells that you can cast them at will. Choose a 1st-level mage spell and a 2nd-level mage spell that are in your spell&shy;book. 

You can cast those spells at their lowest level without expending a spell slot when you have them prepared. If you want to cast either spell at a higher level, you must expend a spell slot as normal.

You can spend 8 hours in study, and change one or both of the spells you chose for different spells of the same level.

### Signature Spells
*20th-level mage feature* 
<div style='margin-top:-4px'></div>

You gain mastery over two powerful spells and can cast them with little effort. Choose two 3rd-level mage spells in your spellbook as your signature spells. You always have these spells prepared, they don't count against the number of spells you have prepared, and you can cast each of them once at 3rd level without expending a spell slot. 

When you do so, you can't do so again until you finish a short or long rest. If you want to cast either spell at a higher level, you must expend a spell slot as normal.

## Magical Studies
Mages are spellcasters who favor magics involving the cardinal elements of the universe. Students gifted with a keen intellect and unwavering discipline may walk the path of the mage. The magic available to mages is both great and dangerous, and thus is revealed only to the most devoted practitioners.

### Study of Arcane
Mages of the arcane are diviners of secrets, balancing the ebb and flow of incredible mystic energies. These practi-tioners push their magical knowledge to its very limits. Those who master this craft are capable to manipulate spells on a much more primal level.

#### Bonus Cantrip
*2nd-level Study of Arcane feature* 
<div style='margin-top:-4px'></div>

When you choose this magical study at 2nd level, you learn the *prestidigitation* cantrip. If you already know this cantrip, you learn a different wizard cantrip of your choice. The cantrip doesn't count against your number of cantrips known.

#### Arcane Charges
*2nd-level Study of Arcane feature* 
<div style='margin-top:-4px'></div>

You gain the ability to conserve and enhance your mage abilities beyond the norm. Whenever you cast a mage spell of 1st level or higher, gain an arcane charge of the equivalent level up to 5th level. Spells slots higher than 5th give a 5th level arcane charge. These charges last until they are used, replaced by a higher level charge, or after 1 minute has passed.

You may expend an arcane charge to grant yourself one of the following effects. This effect lasts until the end of your next turn.

\columnbreak

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

You can exert your control over magic to warp time itself. When a creature you can see within 60 feet of you begins their turn, you can use your reaction to allow that creature to take another action during that turn. When you do so, you gain one level of exhaustion.


<img src='https://www.gmbinder.com/images/08NuEJc.png' style='position:absolute; right:0; bottom:0px; width:556px;' />

<div class='footnote footnote-white'>PART 1 | CLASSES</div>

\pagebreakNum

### Study of Fire
While any worthy mage is an unparalleled expert in the use of magic and heavily dedicated to their craft, those who master the forces of fire tend to be a little more audacious than their peers. These mages take pride, even pleasure, in igniting their enemies in wild bursts of flame.

#### Bonus Cantrip
*2nd-level Study of Fire feature* 
<div style='margin-top:-4px'></div>

When you choose this magical study at 2nd level, you learn the *control flames* cantrip. If you already know this cantrip, you learn a different wizard cantrip of your choice. The cantrip doesn't count against your number of cantrips known.

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

For example, when you cast Burning Hands and spend 2 points, you add an extra 2d6 to the spell's damage. When you cast a spell that makes multiple attack rolls, such as Scorching Ray, you must spend the points on each attack individually.

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

When you choose this magical study at 2nd level, you learn the *shape water* cantrip. If you already know this cantrip, you learn a different wizard cantrip of your choice. The cantrip doesn't count against your number of cantrips known.

#### Fingers of Frost
*2nd-level Study of Frost feature* 
<div style='margin-top:-4px'></div>

You gain one of the following features of your choice:

***Ice Barrier.*** You can weave the cold around yourself for protection. When you cast a spell of 1st level or higher that deals cold damage to a creature, you can simultaneously warp part of the spell's magic to create an icy barrier on yourself that lasts until you finish a long rest. The barrier has hit points equal to twice your mage level + your Intelligence modifier. Whenever you take damage, the barrier takes the damage instead. If the damage reduces the barrier to 0 hit points, you take any remaining damage.

When the barrier is reduced to 0 hit points, each creature within 10 feet of you has their speed reduced by 10 feet until the start of your next turn as the barrier bursts.

<img src='https://www.gmbinder.com/images/5eknUH4.png' style='position:absolute; left:0; bottom:-40px; width:430px;' />

<div class='footnote footnote-white'>PART 1 | CLASSES</div>

\pagebreakNum

While the barrier has 0 hit points, it can't absorb damage, but its magic remains. Whenever you cast a spell of 1st level or higher that deals cold damage, the barrier regains a number of hit points equal to twice the level of the spell.

Once you create the barrier, you can't create it again until you finish a long rest. <br/>
<br/>

***Water Elemental.*** You learn how to conjure a water elemental. It is friendly to you and your companions, and it obeys your commands. See the creature's game statistics in the water elemental stat block.

In combat, the water elemental shares your initiative count, but it takes its turn immediately after yours. It can move and use its reaction on its own, but the only action it takes on its turn is the Dodge action, unless you take a bonus action to command it to take one of the actions in its stat block or the Dash, Disengage, or Help action.

If you target the water elemental with a spell that deals cold damage, it is considered immune to the damage and regains a number of hit points equal to it. You don't need to roll to hit your elemental and it automatically fails any saving throw for it if you choose it.

At the end of a long rest, you can conjure a new water elemental. If you already have a water elemental from this feature, the first one immediately perishes.

#### Brain Freeze
*6th-level Study of Frost feature* 
<div style='margin-top:-4px'></div>

Whenever a creature would take cold damage from one of your mage spells, its movement speed is reduced by 10 feet until the end of your next turn.

When a creature has its speed reduced in this way, you can spend one sorcery point: that creature must succeed on a Strength saving throw against your spell save DC or be restrained for 1 minute.
If a creature makes a successful hit against the creature the conditions caused by Brain Freeze are removed.

Beginning at 14th level the creature becomes paralyzed instead of restrained.

#### Hands of Frost
*10th-level Study of Frost feature* 
<div style='margin-top:-4px'></div>

You gain one of the following features, depending on your choice at 2nd level.

***Ice Barrier.*** When a creature that you can see within 30 feet of you takes damage, you can use your reaction to cause your Ice Barrier to manifest around it and absorb the damage. If this damage reduces the barrier to 0 hit points, the barricaded creature takes any remaining damage.

In addition, you can now spend sorcery points to cause the effect of Brain Freeze.

***Water Elemental.*** Your water elemental changes into an ice elemental and gains the following additional benefits:

- It gains immunity to cold damage.
- Brain Freeze now applies to cold damage caused by the elemental.
- It can cast the *sleet storm* spell once per long rest, using your spell save DC (requires your bonus action).

\columnbreak

#### Ring of Frost
*14th-level Study of Frost feature* 
<div style='margin-top:-4px'></div>

You can use your action to conjure up a ring of magical runes to invoke the deepest cold around a point you can choose within 60 feet. The ring has a 30-foot-radius and fills a 10-foot tall cylinder with frigid cold. 
Creatures inside the area must succeed on a strength saving throw against your spell save DC or become paralyzed for up to 1 minute or until they take damage. If a creature’s body is fully inside the area the save is made with disadvantage. On a successful save a creature isn't restrained.

Additionally creatures passing through the area with non-magical means have their movement speed halved until the end of their next turn after leaving the area. Additionally ranged attacks made through the area are made with disadvantage.

Once you use this feature, you can't use it again until you finish a long rest.

<div style='margin-top:-12px;'></div>

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

<div class='footnote footnote-white'>PART 1 | CLASSES</div>

<img src='https://www.gmbinder.com/images/4bKo7jE.jpg' style='position:absolute; bottom:-250px; right:-173px; width:1000px' />

<img src='https://www.gmbinder.com/images/L60ii4e.png' style='position:absolute; top:185px; left:0px; width:100%; height:100%' />

<img src='https://www.gmbinder.com/images/pbSeYXZ.png' style='position:absolute; top:0px; left:0px; transform:scaleY(-1); width:100%; height:100%' />



\pagebreakNum

Symbol|Spell Location
------|--------------------------
✦ |In this chapter, under Spell Descriptions
^EGW^ | Explorer's Guide to Wildemount
^IDRotF^ | Icewind Dale: Rime of the Frostmaiden
^LLK^ | Lost Laboratory of Kwalish
^TCE^ | Tasha's Cauldron of Everything
^XGE^ | Xanathar's Guide to Everything

<div style='column-count:2'>

### Mage Spells
##### Cantrips (0 Level)
✦ Arcane Blast
<br/> Blade Ward
<br/> Control Flames ^XGE^
<br/> Create Bonfire ^XGE^
<br/> Dancing Lights
<br/> Fire Bolt
<br/> ✦ Flurry
<br/> Frostbite ^XGE^
<br/> Light
<br/> Mage Hand
<br/> Mending
<br/> Message
<br/> Minor Illusion
<br/> Prestidigitation
<br/> Produce Flame
<br/> Ray of Frost
<br/> Shape Water

##### 1st Level
Alarm
<br/> Armor of Agathys
<br/> Burning Hands
<br/> Comprehend Languages
<br/> Create or Destroy Water
<br/> Detect Magic
<br/> Disguise Self
<br/> Expeditious Retreat
<br/> Feather Fall
<br/> Find Familiar
<br/> Frost Fingers ^ID:RotF^
<br/> ✦ Frostfire Bolt
<br/> Gift of Alacrity ^EGW^
<br/> Hellish Rebuke
<br/> Ice Knife ^XGE^
<br/> Identify
<br/> Illusory Script
<br/> Jump
<br/> Longstrider
<br/> Mage Armor
<br/> Magic Missile
<br/> Magnify Gravity ^EGW^
<br/> Shield
<br/> Silent Image
<br/> Snare ^XGE^
<br/> Tenser's Floating Disk
<br/> Unseen Servant

##### 2nd Level
Aganazzar's Scorcher ^XGE^
<br/> Alter Self
<br/> Arcane Lock
<br/> Blindness/Deafness
<br/> Blur

\columnbreak

<br/> Cloud of Daggers
<br/> Continual Flame
<br/> Darkness
<br/> Darkvision
<br/> Detect Thoughts
<br/> Dragon's Breath ^XGE^
<br/> Enlarge/Reduce
<br/> Flame Arrows
<br/> Flame Blade
<br/> Flaming Sphere
<br/> Flock of Familiars ^LLK^
<br/> Fortune's Favor ^EGW^
<br/> Gentle Repose
<br/> ✦ Freezing Touch
<br/> Heat Metal
<br/> Hold Person
<br/> Immovable Object ^EGW^
<br/> Invisibility
<br/> Knock
<br/> Levitate
<br/> ✦ Living Bomb
<br/> Locate Object
<br/> Magic Mouth
<br/> Magic Weapon
<br/> Mirror Image
<br/> Misty Step
<br/> Nystul's Magic Aura
<br/> Pass without Trace
<br/> Phantasmal Force
<br/> Pyrotechnics ^XGE^
<br/> Rope Trick
<br/> Scorching Ray
<br/> See Invisibility
<br/> Shatter
<br/> Silence
<br/> Skywrite
<br/> Snilloc's Snowball <br/>&nbsp;&nbsp;&nbsp; Swarm ^XGE^
<br/> Spider Climb
<br/> Suggestion
<br/> Wristpocket ^EGW^

##### 3rd Level
✦ Arcane Explosion
<br/> Blink
<br/> ✦ Blizzard
<br/> Catnap ^XGE^
<br/> Clairvoyance
<br/> Counterspell
<br/> Create food and Water
<br/> Dispel Magic
<br/> Feign Death
<br/> Fireball
<br/> Fly
<br/> Galder's Tower ^LLK^
<br/> Glyph of Warding

\columnbreak

<br/> Haste
<br/> Hypnotic Pattern
<br/> Intellect Fortress ^TCE^
<br/> Magic Circle
<br/> Major Image
<br/> Nondetection
<br/> Protection from Energy
<br/> Pulse Wave ^EGW^
<br/> Remove Curse
<br/> Sending
<br/> Sleet Storm
<br/> Slow
<br/> ✦ Spellsteal
<br/> Tidal Wave ^XGE^
<br/> Tiny Servant ^XGE^
<br/> Tongues

##### 4th Level
Arcane Eye
<br/> ✦ Amplify or <br/>&nbsp;&nbsp;&nbsp; Dampen Magic
<br/> ✦ Arcane Barrage
<br/> Banishment
<br/> Charm Monster ^XGE^
<br/> Confusion
<br/> Conjure Minor Elementals
<br/> Dimension Door
<br/> Fire Shield
<br/> Galder's <br/>&nbsp;&nbsp;&nbsp; Speedy Courier ^LLK^
<br/> Gravity Sinkhole ^EGW^
<br/> Greater Invisibility
<br/> Hallucinatory Terrain
<br/> ✦ Ice Block
<br/> Ice Storm
<br/> Leomund's Secret Chest
<br/> Locate Creature
<br/> Mordenkainen's <br/>&nbsp;&nbsp;&nbsp; Private Sanctum
<br/> Otiluke's Resilient Sphere
<br/> Polymorph
<br/> Summon Elemental ^TCE^
<br/> Wall of Fire

##### 5th Level
Animate Objects
<br/> Bigby's Hand
<br/> Cone of Cold
<br/> Conjure Elemental
<br/> Creation
<br/> Dominate Person
<br/> Far Step  ^XGE^
<br/> Flame Strike
<br/> Hold Monster
<br/> Immolation ^XGE^
<br/> Mislead
<br/> Passwall
<br/> Planar Binding
<br/> Scrying
<br/> Seeming
<br/> Skill Empowerment ^XGE^
<br/> Synaptic Static ^XGE^
<br/> Teleportation Circle
<br/> Wall of Force

\columnbreak

##### 6th Level
Arcane Gate
<br/> Contingency
<br/> Disintegrate
<br/> Globe of Invulnerability
<br/> Gravity Fissure ^EGW^
<br/> Guards and Wards
<br/> Heroes' Feast
<br/> Investiture of Flame ^XGE^
<br/> Investiture of Ice ^XGE^
<br/> Mass Suggestion
<br/> Mental Prison ^XGE^
<br/> Otiluke's Freezing Sphere
<br/> Programmed Illusion
<br/> Scatter ^XGE^
<br/> True Seeing
<br/> Wall of Ice
<br/> Word of Recall

##### 7th Level
Delayed Blast Fireball
<br/> Etherealness
<br/> Fire Storm
<br/> Forcecage
<br/> Mirage Arcane
<br/> ✦ Glacial Spike
<br/> Mordenkainen's <br/>&nbsp;&nbsp;&nbsp; Magnificent Mansion
<br/> Reverse Gravity
<br/> Project Image
<br/> ✦ Pyroblast
<br/> Sequester
<br/> Teleport

##### 8th Level
✦ Alextrasza’s Fury
<br/> Antimagic Field
<br/> Clone
<br/> Demiplane
<br/> ✦ Ice Nova
<br/> Illusory Dragon ^XGE^
<br/> Incendiary Cloud
<br/> Mind Blank
<br/> Reality Break ^EGW^
<br/> Tsunami

##### 9th Level
Blade of Disaster ^TCE^
<br/> Foresight
<br/> Gate
<br/> Imprisonment
<br/> Invulnerability ^XGE^
<br/> ✦ Jaina's Flying Ship
<br/> Mass Polymorph ^XGE^
<br/> Prismatic Wall
<br/> Meteor Swarm
<br/> Ravenous Void ^EGW^
<br/> Time Ravage ^EGW^
<br/> Time Stop
<br/> True Polymorph

</div>

<div class='footnote'>PART 2 | SPELLS </div>

\pagebreakNum

> ##### Extended spell list 
> This list holds spells that are not in line with the Warcraft fantasy for mages, but a Dungeon Master could still allow a mage to learn. Many of these spells deal with necromancy or demonology, both of which are forbidden by most conclaves of magi. Others are powerful Wizard with no real equivalent in the Warcraft universe. 
> <br/> 
> <br/> 
>##### Cantrips (0 Level) 
> Chill Touch
> <br/> Sapping Sting ^EGW^
> <br/> <br/>
>##### 1st Level
> Cause Fear ^XGE^
> <br/> False Life
> <br/> Ray of Sickness
> <br/> Sleep
> <br/> <br/>
>##### 2nd Level
> Ray of Enfeeblement
> <br/> <br/>
>##### 3rd Level
> Animate Dead
> <br/> Bestow Curse
> <br/> Enemies Abound ^XGE^
> <br/> Fear
> <br/> Life Transference ^XGE^
> <br/> Speak with Dead
> <br/> Summon Lesser Demons ^XGE^
> <br/> Summon Undead ^TCE^
> <br/> Summon Shadowspawn ^TCE^
> <br/> Vampiric Touch
> <br/> <br/>
>##### 4th Level
> Summon Greater Demon ^XGE^
> <br/> Vitriolic Sphere ^XGE^
> <br/> <br/>
>##### 5th Level
> Danse Macabre ^XGE^
> <br/> <br/>
>##### 6th Level
> Circle of Death
> <br/> Create Undead ^XGE^
> <br/> Forbiddance
> <br/> <br/>
>##### 7th Level
> Create Magen ^ID:RotF^
> <br/> Finger of Death
> <br/> Plane Shift
> <br/> <br/>
>##### 8th Level
>Feeblemind
> <br/> Mighty Fortress ^XGE^
> <br/> <br/>
>##### 9th Level
> Wish
> <br/> Dream of the Blue Veil ^TCE^

\columnbreak

#### Amplify or Dampen Magic
*4th-level abjuration*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** S, M (something of value to the creature)
- **Duration:** Concentration, up to 1 minute
___
You manipulate the flow of mana rushing through a creature, if the creature is unwilling you must succeed on a melee spell attack before you can manipulate their flow. When you touch a creature with this spell, you choose which effect you want to affect the creature with for the spells duration.

***Amplify.*** You amplify a creatures magical prowess. The creature takes additional damage when hit by a spell, deals additional damage when casting a spell, and restores additional hit points to a creature with a spell by an amount equal to your spellcasting modifier.

***Dampen.*** You dampen a creatures magical prowess. The creature reduces damage taken by spells, damage dealt by spells, and the number of hit points restored to it by a spell by an amount equal to your spellcasting modifier.

#### Arcane Barrage
*4th-level evocation*
___
- **Casting Time:** 1 action
- **Range:** 120 feet
- **Components:** V, S
- **Duration:** Instantaneous
___
You manifest three bolts of raw force and launch them at a target within range. Make a ranged spell attack for each bolt. On a hit, a target takes 5d4 force damage and is pushed 10 feet directly away from you.

***At Higher Levels.*** When you cast this spell using a <br> spell slot of 5th level or higher, the spell creates one more bolt for each slot level above 4th.

#### Arcane Blast
*Evocation cantrip*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** Instantaneous
___
You extend your hand and make a burst of arcane energy erupt from a target within range. If the target is a creature it must succeed on a Dexterity saving throw or take 1d8 force damage. A creature forced to make a Constitution saving throw to maintain concentration because of this spell, makes the saving throw with disadvantage.

This spell’s damage increases by 1d8 when you reach 5th level (2d8), 11th level (3d8), 17th level (4d8).

<div class='footnote'>PART 2 | SPELLS </div>

\pagebreakNum

#### Arcane Explosion
*3rd-level evocation*
___
- **Casting Time:** 1 action
- **Range:** Self (10-foot-radius sphere)
- **Components:** V, S
- **Duration:** Instantaneous
___
You draw from the fluctuating arcane near you and burst with a wave of arcane power. Each other creature within range must make a Dexterity saving throw. A target takes 6d8 force damage and can't take reactions until the start of its next turn on a failed saving throw, or half as much damage on a successful one.

***At Higher Levels.*** When you cast this spell using a spell slot of 4th level or higher, the damage increases by 1d8 for each slot level above 3rd.


#### Alextrasza’s Fury
*8th-level evocation*
___
- **Casting Time:** 1 action
- **Range:** Self (60-foot cone)
- **Components:** V, S
- **Duration:** Instantaneous
___
Your hands burst into flames as you push a roaring wave of fire outward from yourself. Each creature in a 60-foot cone must make a Constitution saving throw. A target takes 12d6 fire damage and is stunned until the end of their next turn on a failed save, or half as much damage on a successful one. The fire spreads around corners. It ignites flammable objects in the area that aren’t being worn or carried. A creature killed by this spell is reduced to ash.

#### Blizzard
*3rd-level evocation*
___
- **Casting Time:** 1 action
- **Range:** 120 feet
- **Components:** V, S, M (shards of glass)
- **Duration:** Concentration, up to 1 minute
___
A cold light flashes from your hand into the sky as blue shards hurl down in a 20-foot-radius, 40-foot-high cylinder centered on a point within range. Until the spell ends, shards of freezing ice rain down upon the area. 
When a creature enters the spell's area for the first time on a turn or starts its turn there, it must make a Dexterity saving throw. A target takes 3d6 cold damage on a failed save, or half as much damage on a successful one.

***At Higher Levels.*** When you cast this spell using a spell slot of 4th level or higher, the damage increases by 1d6 for each slot level above 3rd.

#### Flurry
*Evocation cantrip*
___
- **Casting Time:** 1 action
- **Range:** 30 feet
- **Components:** V, S
- **Duration:** Instantaneous
___
Three shards of ice streaks out toward one or more creatures within range. Make a ranged spell attack for each shard. You can direct the shards at the same target or at different ones, but they all strike simultaneously. Each shard deals 1d4 cold damage on a hit.

This spell's damage increases by 1d4 per shard when you reach 5th level (2d4), 11th level (3d4), and 17th level (4d4).

\columnbreak

#### Freezing Touch
*2nd-level evocation*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S, M (a shard of glass or ice)
- **Duration:** 1 minute
___
Your fingers become cold to the touch as frost manifests on their surface. Make a melee spell attack against a creature within range. On a hit, the creature is incapacitated and restrained until the spell ends as ice encap&shy;sulates their body. A target who hits the creature with an attack breaks the ice and ends the spell.


#### Frostfire Bolt
*1st-level evocation*
___
- **Casting Time:** 1 action
- **Range:** 120 feet
- **Components:** V, S, M (a piece of glass and sulfur)
- **Duration:**  Instantaneous
___
You hurl a bolt of blue flames at a creature within range. Make a ranged spell attack against the creature. On a hit, the target takes 2d6 fire damage and 2d6 cold damage.

***At Higher Levels.*** When you cast this spell using a spell slot of 2nd level or higher, the fire and cold damage increases by 1d6 for each slot level above 1st.

#### Glacial Spike
*7th-level evocation*
___
- **Casting Time:** 1 action
- **Range:** 120 feet
- **Components:** V, S
- **Duration:** Instantaneous
___
You form a large spike of ice above your head, and launch it at a creature that you can see within range, causing it to shatter across their body. The target must make a Dexterity saving throw. It takes 8d8 + 40 cold damage on a failed save, or half as much damage on a successful one. 

If this damage reduces a creature to 0 hit points, it is reduced to shards of ice, leaving behind everything it was wearing and carrying. The creature can be restored to life only by means of a true resurrection or a wish spell.

#### Ice Block
*4th-level abjuration*
___
- **Casting Time:** 1 reaction, when you take damage
- **Range:** Self
- **Components:** V, S
- **Duration:**  Concentration, up to 1 minute
___
Ice rapidly materializes around you, protecting you from harm. You gain 40 temporary hit points and immunity to cold damage for the spells duration. While the spell is active you can't move and take any actions or reactions. The spell remains until the temporary hit points have been expended or for the spell's duration.

<div class='footnote'>PART 2 | SPELLS </div>

\pagebreakNum

#### Ice Nova
*8th-level evocation*
___
- **Casting Time:** 1 action
- **Range:** 120 feet
- **Components:** V, S, M (glass dust and water)
- **Duration:** Instantaneous
___
Frigid cold rapidly expands in a 15-foot-radius centered on a point you you can see within range. Each creature in the cold must succeed on a Dexterity saving throw. On a failed save, a creature takes 10d6 cold damage and is restrained for 1 minute as ice encases the lower part of their legs. On a successful save, it takes half as much damage and isn't restrained by this spell.

A creature restrained by the ice can use its action to make a Strength check against your spell save DC. On a success, it frees itself. Alternatively, the ice can be broken by dealing a total of 40 hit points worth of damage to it. It has an armor class of 10. 

#### Jaina's Flying Ship
*9th-level transmutation*
___
- **Casting Time:** 1 minute
- **Range:** Touch
- **Components:** V, S
- **Duration:** 24 hours
___
You channel your powers into a nonmagical ship within range, the ship can be no larger than 100 feet long, and 30 feet wide. For the spell's duration, the ship gains a flying speed of 60 feet, the ship changes direction and altitude at your command, continuing its course until a new command is given or the spells duration ends.

The flying ship has an Armor Class of 15, and 300 hit points; immunity to poison and psychic damage, and immunity to all conditions.

It has a maximum carrying capacity of 50 tons (limited by the size of the ship itself). It is not slowed by any weight until its maximum capacity is reached, at which point the ship loses its flying property and falls at a rate of 60 feet per round until it hits the ground. It takes no falling damage from the fall, and its passengers are unharmed

You can make this effect permanent by casting this spell on the same ship once per week for one year.

#### Living Bomb
*2nd-level evocation*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S, M (a flammable liquid)
- **Duration:**  Concentration, up to 1 minute
___
You manipulate the mana flowing through a creature within range, making it burn from the inside with a roaring fire. The target must make a Constitution saving throw. On a failed save it takes 1d10 fire damage, or half as much on a successful one. At the start of each of your turns for the spells duration, the target must make another Constitution saving throw as it takes the damage again

When the spell ends the target and each creature within 10 feet of it must succeed on a Dexterity saving throw or take 2d6 fire damage.

***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, the damage of the explosion increases by 1d6 for each slot level above 2nd.

\columnbreak

#### Pyroblast
*7th-level evocation*
___
- **Casting Time:** 1 action
- **Range:** 120 feet
- **Components:** V, S, M (a piece of brimstone)
- **Duration:**  Instantaneous
___
You clasp your hands together, conjuring a ball of dripping magma, launching it at a creature or object within range. Make a ranged spell attack against the target. On a hit, the target takes 13d10 fire damage and ignites. Until a creature takes an action to douse the fire, the target takes 1d10 fire damage at the start of each of its turns.

***At Higher Levels.*** When you cast this spell using a spell slot of 8th level or higher, the initial damage increases by 1d10 for each slot level above 7th.

#### Spellsteal
*3rd-level abjuration*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** Instantaneous
___
Choose a creature that you can see within range. A 1st level spell effect of your choosing that affects the target is transferred to you. For its remaining duration, the spell's effect is applied to you as if you had cast it yourself. 

If the stolen spell requires concentration, you need to concentrate on it. You do not need to provide any additional spellcasting components, if any were required by the stolen spell. Spellsteal has no effect on spells that create or summon creatures, or on spell effects that can’t be removed by *dispel magic*. 

You cannot change the stolen spell from how it was originally cast, unless its description explicitly allows it to be changed after being cast. 

To steal a spell effect of 2nd level or higher, make an ability check using your spellcasting ability. The DC equals 10 + the spell's level. On a successful check, you successfully steal the spell. 

***At Higher Levels.*** When you cast this spell using a spell slot of 4th level or higher, the spell level where you automatically succeed the check increases by one for each slot level above 3rd.
<div class='footnote'>PART 2 | SPELLS </div>

\pagebreak

# Update 3.0-preview-2

<br />

These are the changes made to the class since the last update released for the class (3.0.0).

## General
- Initial page has been rewritten a bit, "Creating a Mage" has been moved up there.
- Quick creation pointers have been fleshed out.
- Added full functionality of Sorcery Points and Meta Magic.
- Removed Arcane Recovery, due to the change above.
- Additional ribbon feature for first level.
- 18th and 20th level unchanged (Spell Mastery, Signature Spell)

## Spells 
- The spell list was revisited and expanded. 
- The WC5e spells got some updates!
- Arcane Barrage had its mechanic changed to be more like a big magic missile.
- Arcane Explosion got a neat extra mechanic preventing affected targets from taking their reaction.
- Blast Wave was renamed Alextrasza’s Fury and had change to its damage and now stuns affected creatures until the end of their next turn.
- Blizzard had its action cost for subsequent turns removed.
- Flurry got a mechanical change, putting it more in line with how it works in World of Warcraft.
- Freezing Touch now applies "incapacitated and restrained" instead of "incapacitated, can't move, and can't breathe".<br/> Turns out not being able to breathe without being able to hold your breath is very deadly.
- Glacial Spike had its save changed to DEX.
- Jaina's Flying Ship can now become a permanent effect.
- Pyroblast had its damage increased.
- Spellsteal got reworked ... again.

## Arcane
- Completely reworked!
- Arcane focuses more on combat and off combat utility with a combination of time manipulation, general mastery over spell usage.
- Arcane Charges got reworked into a buff mechanic.
- Rune of Power was replaced with Time Warp. Provides a action surge like reaction ... for a price.

\columnbreak

<br />

## Fire
- Empowered Evocation has been replaced. 
The intention is to capitalize more on crits instead of guaranteed damage and to provide some synergy with Hot Streak of the subclass.

## Frost
- Reworked Brain Freeze feature. The movement speed reduction now happens automatically. The restrain is coupled to sorcery points and a single saving throw.
This should make the feature more reliable and less time consuming.
- Replaced Spell Sculptor with Ring of Frost. 
A big AoE to slow down a big area and potentially freezing creatures within.


## Credits

**Provide feedback for this document:** We'd really love your opinion on this material. You can do so by: 
- Joining the conversation on [Discord](https://discord.com/invite/dKMJmmD). <br /> (Or just messaging an active Contributor there.)
- Sharing your thoughts with us on [Reddit](https://www.reddit.com/r/wc5e/).
- Writing to us via this [Google Form](https://forms.gle/FSbyK7nBbquPNVf36).

<br />**Current core team:** Ace Azzermeen, Auvreannia, Geamros, Lorestalker Nemzal, MythMaker, Nagash, OmNomDom33887, Tangerine, Tyloris
<br />

<br />**Big thanks to:** Everyone at our community Discord. Link to join our communities are on the book's back page!
<br />

<br />**Projects we like and want to give thanks to:**
- [The WoW 5E Project](https://www.thepiazza.org.uk/bb/viewtopic.php?t=13979) by Arrius Nideal
- [This Warcraft project](https://drive.google.com/drive/folders/1f07sWuQJ_MBJxKbToalevudGQ8hjnma7) by Silverblade#9212
- [These WoW Dungeon modules](https://www.gmbinder.com/profile/wyken) by Wyken
- All of the awesome homebrew that has been shared within the community, it's super cool to see it all! You can see a lot of it on our Discord, and in this [Theme of the Month](https://drive.google.com/drive/folders/1_inQbI4jjd6WF3ghzhr_9RYBFygAkVK1) collection.

<br />**Page 1 Art:** "Human Mage" by [Glenn Rane](https://wow.gamepedia.com/File:ArtHumanMage.jpg)
<br /> **Page 1 Art:** [Hall of the Guardian loading screen](https://wow.gamepedia.com/File:Hall_of_the_Guardian_loading_screen.jpg)
<br /> **Page 5 Art:** "Arcane" by [Michael Roberts](https://www.artstation.com/artwork/vvJ5O)
<br /> **Page 6 Art:** "Lyris, the Wild Mage" by [Will Murai](https://willmurai.artstation.com/projects/Qybxd)
<br /> **Page 7 Art:** [Hall of the Guardian loading screen](https://wow.gamepedia.com/File:Hall_of_the_Guardian_loading_screen.jpg)
<br /> **Backpage Art:** "Wardens of Nordrassil" by [Kan Liu](https://666kart.artstation.com/projects/6qo6)

\pagebreakNum

<style>

/* BACK PAGE STYLES */

  /* Remove footer from back page, replace pX with last page number */
  .phb#p13:after { display:none; }

  .phb .back-cover-content {
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
 
  *Part of the WC5E Heroes Handbook v3*
 
  This document is a part-piece of an upcoming update (as of writing this) to our *Warcraft 5th Edition Heroes Handbook*; a massive tome of player classes, races, and backgrounds to put a Warcraft spin on core Dungeons & Dragons material.

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
