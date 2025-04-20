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

</style>

<div style='margin-top:344px;'></div>

## Priest
*It is faith in ourselves that separates us from others, and with our powers, we will cause great change in all of Azeroth. The weak will come to lean on you. The lepers will call you Lord. And the ignorant will look to you for guidance.*
<div style="text-align:Right"> 

*— Dark Cleric Duesten*    </div>

Bent over her fallen ally, a dwarf clutches her holy symbol and begins to sing a slow melodic tune. Holy light shines from her hand, causing the limp body to breathe once more.

One hand firmly grasping a staff, the other filled with swirls of divine and profane energies, a human sends out a thick halo of energy. His allies gain new life, while his enemies feel their bodies begin to decay.

An undead surrounded pulls his holy symbol from his neck as his body fades into shadow. He cackles as feelings of primal terror cause nearby enemies to flee, scrambling over each other in a mad dash.

Powered by faith and conviction, priests can channel the energies of the Light or Void, diametrically opposed primal forces of the universe.

### Invokers of Light and Shadow
Two of the most fundamental forces in the universe are the Light and the Void. Existing beyond the barriers of reality, the two forces are both contradictory by their very nature and bound together on a cosmic scale, unable to exist without the other. Pure Light or Void cannot exist in the physical universe, but shades of it can exist in the form of "holy or divine" or "shadow or void" magic.

The Light is the source of all life in the cosmos, but is not necessarily "good;" it is a primal force whose morality is characterized by how it is wielded. Light magic is summoned by emotions, willpower, or one's faith in the ability to do so. Its powers can be used to heal, cleanse, protect, or harm.

The Void, like the Light, is not necessarily "evil." Yet its very nature is hostile to what mortals know as life and sanity, seeking to vampirically consume the Light. Shadow magic can be used to damage, corrupt, fear, or weaponize enemy's minds. Even those who wield this magic dare not delve too deep, lest they be consumed by madness.

<div style='margin-top:-20px;'></div>

\columnbreak

<div style='margin-top:514px;'></div>

### Devoted Acolytes
Priests channel their power through their conviction, not a direct connection to a religious patron. While priests sometimes worship a particular powerful being or deity, their power instead comes from their belief, from following a particular religious or moral philosophy; from this belief, power flows. A doubtful priest is a powerless priest.

Learning to wield these forces can take years of discipline and study. One must align themselves to become conduits of these higher powers. Not every acolyte in a temple is a proper priest. Neither does a wielder of the Light necessarily need to be good; using the Light merely requires a *belief* that one is doing the right thing, even if your actions are causing suffering in the name of some dubious "greater good."

While priests who wield void magic exist, they are significantly outnumbered in Azeroth by those who wield the Light. Most of those stem from races who are part of the Alliance, such as humans, elves, dwarves, and draenei. When a priest takes up an adventuring life, it less likely to be in order to proselytize and more often in pursuit of a goal: to right a wrong, to put down a threat to their people, or to ease the suffering of others.

Most adventuring priests maintain some connection to established temples and orders of their faiths. A temple might ask for a priest’s aid, or a high cleric might be in a position to demand it.

### Creating a Priest
The most important decision for a priest is which religion to follow. Becoming a priest requires a strong conviction in a set of beliefs. The Religions section lists important religions of the Warcraft universe.

<div class='footnote'>PART 1 | CLASSES</div>
<img src='https://www.gmbinder.com/images/ydhgeyS.jpg' style='position:absolute; top:0px; right:0px; width:800px' />
<img src='https://www.gmbinder.com/images/vn90cy3.png' style='position:absolute; top:0px; right:-100px; width:900px' />
<img src='https://www.gmbinder.com/images/lyv4YVJ.png' style='position:absolute; top:-130px; right:-100px; width:600px' />

\pagebreakNum

<div class='classTable wide'>

##### The Priest 
|Level|Proficiency<br>Bonus|Features|Cantrips<br>Known||1st||2nd||3rd||4th||5th||6th||7th||8th||9th <div style="position: absolute; top:100px; right:81px; width:200px; height:25px">—Spell Slots per Spell Level—</div>|
|:---:|:--:|:----------|:-:|-|:-:|-|:-:|-|:-:|-|:-:|-|:-:|-|:-:|-|:-:|-|:-:|-|:-:|
| 1st | +2 | Spellcasting, Divine Calling                       |3||2||—||—||—||—||—||—||—||—|
| 2nd | +2 | Devotion (x2), Divine Calling feature              |3||3||—||—||—||—||—||—||—||—|
| 3rd | +2 | —                                                  |3||4||2||—||—||—||—||—||—||—|
| 4th | +2 | Ability Score Improvement                          |4||4||3||—||—||—||—||—||—||—|
| 5th | +3 | Devotion (x3), Divine Word (2)                     |4||4||3||2||—||—||—||—||—||—|
| 6th | +3 | Divine Calling feature                             |4||4||3||3||—||—||—||—||—||—|
| 7th | +3 | —                                                  |4||4||3||3||1||—||—||—||—||—|
| 8th | +3 | Ability Score Improvement, Empowered Faith         |4||4||3||3||2||—||—||—||—||—|
| 9th | +4 | Devotion (x4)                                      |4||4||3||3||3||1||—||—||—||—|
| 10th| +4 | Divine Calling feature, Divine Word (3)            |5||4||3||3||3||2||—||—||—||—|
| 11th| +4 | —                                                  |5||4||3||3||3||2||1||—||—||—|
| 12th| +4 | Ability Score Improvement                          |5||4||3||3||3||2||1||—||—||—|
| 13th| +5 | Devotion (x5)                                      |5||4||3||3||3||2||1||1||—||—|
| 14th| +5 | Divine Word (4)                                    |5||4||3||3||3||2||1||1||—||—|
| 15th| +5 | —                                                  |5||4||3||3||3||2||1||1||1||—|
| 16th| +5 | Ability Score Improvement                          |5||4||3||3||3||2||1||1||1||—|
| 17th| +6 | Prodigy of Faith, Devotion (x6)                    |5||4||3||3||3||2||1||1||1||1|
| 18th| +6 | Divine Calling feature                             |5||4||3||3||3||3||1||1||1||1|
| 19th| +6 | Ability Score Improvement                          |5||4||3||3||3||3||2||1||1||1|
| 20th| +6 | Embrace Calling                                    |5||4||3||3||3||3||2||2||1||1|

</div>

Once you've chosen a religion, consider your priest's relationship with that religion. Were you introduced to it at a young age? Or did you come to follow it later in life? Are you part of that religion's organized priesthood, or do you practice independently? What led you to become an adventurer? Are you on a task given to you by a higher-up? Or do you have some other ultimate goal in mind?

#### Quick Build
You can make a priest quickly by following these sugges­tions. First, Charisma should be your highest ability score, followed by Constitution. Second, choose the acolyte background.

#### Optional Rule: Multiclassing
If your group uses the optional rule on multiclassing in the *Player's Handbook*, here's what you need to know if you choose priest as one of your classes.

***Ability Score Minimum.*** As a multiclass character, you must have at least a Charisma score of 13 to take a level in this class, or to take a level in another class if you are already a priest.

***Proficiencies Gained.*** If priest isn't your initial class, here are the proficiencies you gain when you take your first level as a priest: one skill from the class's skill list.

***Spell Slots.*** Add your levels in the priest class to the appropriate levels from other class to determine your available spell slots.

\columnbreak

## Class Features
As a priest, you gain the following class features.
<div style='margin-top:-2px;'></div>

#### Hit Points
___
- **Hit Dice:** 1d6 per priest level
- **Hit Points at 1st Level:**  6 + your Constitution modifier
- **Hit Points at Higher Levels:** 1d6 (or 4) + your Constitution modifier per priest level after 1st

#### Proficiencies
___
- **Armor:** None
- **Weapons:** All simple weapons
- **Tools:** None
___
- **Saving Throws:** Wisdom, Charisma
- **Skills:** Choose two from History, Insight, Medicine, Persuasion, and Religion

#### Equipment
You start with the following equipment, in addition to the equipment granted by your background:
- *(a)* a club or *(b)* a quarterstaff
- *(a)* a priest's pack or *(b)* an explorer's pack
- *(a)* a light crossbow and 20 bolts or *(b)* any simple weapon
- a holy symbol, healer's kit, and a dagger

<div class='footnote'>PART 1 | CLASSES</div>

\pagebreakNum

### Spellcasting
*1st-level priest feature*<br/>
<div style='margin-top:-4px;'></div>

As a conduit for divine or shadowy power, you can cast priest spells. See chapter 10 of the Player's Handbook for the general rules of spellcasting and chapter 6 of this book for the priest spell list.

#### Cantrips
At 1st level, you know three cantrips of your choice from the priest spell list. You learn additional priest cantrips of your choice at higher levels, as shown in the Cantrips Known column of the Priest table.

#### Preparing and Casting Spells
The Priest table shows how many spell slots you have to cast your spells of 1st level and higher. To cast one of these spells, you must expend a slot of the spell's level or higher. You regain expended all spell slots when you finish a long rest.

You prepare the list of priest spells that are available for you to cast, choosing from the priest spell list. When you do so, choose a number of priest spells equal to your Charisma modifier + your priest level (minimum of one spell). The spells must be of a level for which you have spell slots.

For example, if you are a 3rd-level priest, you have four 1st-level and two 2nd-level spell slots. With a Charisma of 16, your list of prepared spells can include six spells of 1st or 2nd level, in any combination. If you prepare the 1st-level spell *cure wounds*, you can cast it using a 1st-level or 2nd-level slot. Casting the spell doesn't remove it from your list of prepared spells.

You can change your list of prepared spells when you finish a long rest. Preparing a new list of priest spells requires time spent in prayer and meditation: at least 1 minute per spell level for each spell on your list.

#### Spellcasting Ability
Charisma is your spellcasting ability for your priest spells, since the power of your magic relies on your ability to project your will into the world. You use your Charisma whenever a priest spell refers to your spellcasting ability. In addition, you use your Charisma modifier when setting the saving throw DC for a priest spell you cast and when making an attack roll with one.

<div style="text-align: Center">

**Spell save DC** = 8 + your proficiency bonus + <br/> your Charisma modifier

**Spell attack modifier** = your proficiency bonus + <br/> your Charisma modifier

</div>

#### Ritual Casting
You can cast a priest spell as a ritual if that spell has the ritual tag and you have the spell prepared.

#### Spellcasting Focus
You can use a holy symbol as a spellcasting focus for your priest spells.

### Divine Calling
*1st-level priest feature*<br/>
<div style='margin-top:-4px;'></div>

Choose a divine calling, a path of priesthood that you have devoted yourself to: Discipline, Holy, or Shadow. Each calling is detailed at the end of the class description. Your choice grants you features when you choose it at 1st level and again at 2nd, 6th, 10th, and 18th level.

\columnbreak

<div style='margin-top:220px;'></div>

#### Calling Spells
Each calling has a list of associated spells. You gain access to these spells at the levels specified in the calling description. Once you gain a calling spell, you always have it prepared, and it doesn't count against the number of spells you can prepare each day.

If you gain a calling spell that doesn't appear on the priest spell list, the spell is nonetheless a priest spell.

### Devotion
*2nd-level priest feature*<br/>
<div style='margin-top:-4px;'></div>

You can channel pure energy from your source of power, using that energy to fuel magical effects. You start with three such effects: Desperate Prayer, a Divine Word of your choice, and an effect determined by your calling. 

You learn an additional Divine Word at 5th, 10th, and 14th levels. Some callings may grant you additional effects as you advance in level, as noted in the domain description.

When you use your Devotion, you brandish your holy symbol and choose an effect, and can only use one Devotion option per turn. Some Devotion effects require saving throws. When you use such an effect from this class, the DC equals your priest spell save DC.

You have two uses of Devotion, and regain all expended uses upon finishing a short or long rest. You gain additional uses of Devotion as you gain priest levels, as shown in the Devotions column of the Priest table.

#### Desperate Prayer
As a bonus action, you can expend a use of your Devotion to fuel your spells. You regain one expended spell slot, the level of which can be no higher than half your proficiency bonus (rounded up). 

The number of times you can use this feature is based on the level you've reached in this class: 2nd level, once; 6th level, twice; and 18th level, thrice. You regain all expended uses when you finish a long rest.

#### Divine Words
The words are presented in alphabetical order.

***Barrier.*** When a creature within 60 feet that you can see is targeted for an attack, you may expend one use of Devotion as a reaction to impose disadvantage on the triggering attack, and on all attack rolls against that creature till the start of their next turn. <!-- Also called Deflect -->

***Beckon.*** When a creature you can see within 60 feet of you fails a saving throw against an effect that deals half damage on a successful save, you can spend one use of Devotion to beckon them to you as a reaction. They are pulled to an unoccupied space within 5 feet of you and add your Charisma modifier to their saving throw, potentially turning it into a success.

<div class='footnote'>PART 1 | CLASSES</div>
<img src='https://www.gmbinder.com/images/873nzvm.png' style='position:absolute; top:0px; right:75px; width:285px; z-index:1000' />

\pagebreakNum

<div style='margin-top:451px;'></div>

&nbsp;&nbsp;&nbsp; ***Chastise.*** As an action, you can spend one use of Devotion to chastise a creature you can see within 60 feet. That creature must succeed on a Wisdom saving throw or be incapacitated until the end of your next turn. <!-- Also called Bind --> 

***Control.*** As an action, you can spend one use of Devotion to target a creature you can see within 60 feet. The creature must succeed on a Wisdom saving throw or be charmed by you for 1 minute. If you or your companions do anything harmful to it, the effect ends. Once the effect ends, the creature doesn't knows it was charmed by you.

***Fortitude.*** WWhen a creature, or a number of creatures up to your Charisma modifier (minimum of one) make a saving throw, you can spend one use of Devotion as a reaction to give them advantage. The saving throws must be against the same effect. <!-- Also called Protect -->

***Pain.*** When a creature takes damage from or fails a saving throw against one of your priest spells, you may spend one use of Devotion as a reaction to impose disadvantage on all the creature's attack rolls until the beginning of your next turn.

***Purify.*** As an action, you can spend one use of Devotion to target a creature you can see within 60 feet that is affected by a spell or condition that allows a saving throw to end its effects. The creature can immediately make another save, adding your proficiency bonus to the roll.

***Rebuke.*** When a creature you can see within 60 feet hits you with an attack or harmful spell, you can spend a use of Devotion as a reaction to rebuke it. Until the end of your next turn, you can give yourself advantage on one attack roll against the creature or give it disadvantage on one saving throw it makes against a spell you cast.

***Sanctuary.*** As an action, you can spend one use of Devotion to target a creature you can see within 60 feet, warding them from harm. For 1 minute, all attacks against them have disadvantage and the creature has advantage on saving throws against harmful spells. If the warded creature makes an attack or casts a spell that affects an enemy creature, this effect ends. <!-- Also called Fade --> 

<div style='margin-top:-10px;'></div>

\columnbreak

<div style='margin-top:56px;'></div>

> ### The Light and the Void
> The two sources of power that a priest can draw upon--the Light and the Void--are diametrically opposed. In fact, it is believed by some that it was the mixing of the two energy sources which led to a series of cosmic-level explosions that gave birth to the physical universe. A devout Holy priest would not dare draw upon the power of the Void, nor could a powerful acolyte of Shadow draw deep upon the Light without being burned.
>
> As such, while mechanically there are few restrict&shy;ions in the priest's spells and abilities enforcing this divide, players are encouraged to pick either the Light or the Void as their source of power and stick to abilities that match as much as possible--with certain notable exceptions such as discipline priests. 
>
> Light-based spells are those that produce bright light, deal radiant damage, restore hit points or life to the dead, wound or destroy the undead, or inspire hope and positive emotions. Void-based spells create dark&shy;ness, deal necrotic or psychic damage, drain life, cause sickness, dominate the mind, or cause fear or other negative emotions. <!-- Additionally, unlike clerics who wield a god's power over the afterlife to turn, bind, or create undead, necromancy in Azeroth is generally the province of a completely separate branch of magic; though some approx&shy;imation of these powers can be achieved through Light or Shadow. -->

<div style='margin-top:30px;'></div>

***Shield.*** As an action, you can spend one use of Devotion to give one creature within 60 feet of you a number of temporary hit points equal to your priest level + your Charisma modifier. These temporary hit points last for <br/> 1 minute.

### Ability Score Improvement
*4th-level priest feature*
<div style='margin-top:-4px'></div>

When you reach 4th level, and again at 8th, 12th, 16th, and 19th level, you can increase one ability score of your choice by 2, or you can increase two ability scores of your choice by 1. As normal, you can't increase an ability score above 20 using this feature.

#### Divine Versatility (Optional)
Whenever you reach a level in this class that grants the Ability Score Improvement feature, you can do one of the following, representing a change of focus:
- Replace an option you chose for the Divine Words feature with one of that feature's other options.
- Replace one cantrip you learned from this class's Spellcasting feature with another cantrip from the warlock spell list.

### Empowering Faith
*8th-level priest feature*<br/>
<div style='margin-top:-4px;'></div> 

You gain one of the following features of your choice.

#### Divine Strike
You gain the ability to infuse your weapon strikes with divine energy. Choose either necrotic, psychic, or radiant damage. Once per turn when you hit a creature with a weapon attack, you can cause the attack to deal an extra 1d8 damage of the chosen type.

When you reach 14th level, the extra damage increases to 2d8.

<div class='footnote'>PART 1 | CLASSES</div>
<img src='https://www.gmbinder.com/images/J5lW3Tw.png' style='position:absolute; top:0px; right:170px; width:110%; ' />
<img src='https://www.gmbinder.com/images/E2VAlT7.png' style='position:absolute; bottom:-195px; right:-250px; height:100%px;' />

\pagebreakNum

#### Power Infusion
You add your Charisma modifier (with a minimum bonus of +1) to the damage you deal with any priest cantrip.

#### Unwavering Faith
When you make a concentration check, you can use your reaction to add your Charisma modifier to it (with a minimum bonus of +1).

### Prodigy of Faith
*17th-level priest feature*<br/>
<div style='margin-top:-4px;'></div>

When you roll initiative and have no uses of Devotion remaining, you regain one use. 

### Embrace Calling
*20th-level priest feature*<br/>
<div style='margin-top:-4px;'></div>

You can channel the power of your faith, allowing you to achieve incredible feats through sheer conviction alone. As an action, you attempt to bring forth a manifestation of power. The GM chooses the nature of the manifestation; the effect of any priest spell or priest calling spell would be appropriate. Once you use this feature, you can't do so again for 7 days.

## Divine Callings
Priests choose a divine calling, a path of priesthood that they follow. This calling could be the Church of the Holy Light, the goddess Elune, or a sect dedicated to the dark shadows and void. Your choice might correspond to a particular branch of the divine callings, it could simply be a matter of personal preference, following the purpose that appeals to you the most.

### Discipline
Some priests pride themselves on pragmatism. They understand that light casts a shadow, that darkness is defined by light, and that true discipline stems from one’s ability to balance these opposing powers in services of a greater cause. While these priests possess many holy virtues to aid their allies, they also dabble in the dark arts to debilitate their enemies.

\columnbreak

##### Discipline Calling Spells
Priest Level| Spells
------------|-----------
1st |*cure wounds*, *inflict wounds*
3rd |*silence*, *zone of truth*
5th |*✦ divine star*, *vampiric touch*
7th |*mordekainen's private sanctum,* *otiluke's resilient sphere* 
9th |*dispel evil and good*, *wall of force*

#### Atonement
*1st-level Discipline feature*<br/>
<div style='margin-top:-4px;'></div>

Whenever you cast a spell of 1st level or higher that deals damage, you can choose one creature you can see within 30 feet. That creature regains hit points equal to twice the spell's level.


In addition, whenever you cast a spell of 1st level or higher that restores hit points, you can choose one creature you can see within 30 feet. That creature takes an amount of necrotic, psychic, or radiant damage (your choice) equal to twice the spell's level.

You can use either effect of Atonement only once per casting of a spell. 

#### Twist of Fate
*1st-level Discipline feature*<br/>
<div style='margin-top:-4px;'></div>

As a reaction, when you or another creature you can see within 60 feet makes an ability check, attack roll, or saving throw, you can change the value rolled to a 10. This can be declared after the roll, but before failure or success is determined.

You can use this reaction a number of times equal to your proficiency bonus, and regain all expended uses upon finishing a long rest.

#### Devotion: Pain Suppression
*2nd-level Discipline feature*<br/>
<div style='margin-top:-4px;'></div>

As an action, you can expend a use of Devotion to grant a barrier to a creature you can see within 60 feet of you. The barrier is invisible, and any bludgeoning, piercing, and slashing damage the target takes is reduced by 2 + your proficiency bonus, to a minimum of 0. This effect lasts for 1 minute or until you are incapacitated or die. 

Once you use this feature, you can't do so again until you finish a long rest, unless you spend two uses of Devotion to use it again.

<div class='footnote footnote-white'>PART 1 | CLASSES</div>
<img src='https://www.gmbinder.com/images/WrVZQmR.png' style='position:absolute; bottom:-30px; right:-100px; width:900px; transform:scaleX(-1)' />
<img src='https://www.gmbinder.com/images/vn90cy3.png' style='position:absolute; top:-60px; right:-250px; width:1100px; transform:scale(-1)' />

\pagebreakNum

#### Spirit Shield
*6th-level Discipline feature*<br/>
<div style='margin-top:-4px;'></div>

Whenever a creature regains hit points from one of your priest spells or Atonement, they also gain a number of temporary hit points equal to your proficiency bonus. 

#### Rapture
*10th-level Discipline feature*<br/>
<div style='margin-top:-4px;'></div>

When you use a Devotion as an action, you can cast one of your Discipline Calling spells with a casting time of action as a bonus action that turn. Any Atonement damage or healing done by this spell increases by an amount equal to half your priest level. 

#### Clarity of Will 
*18th-level Discipline feature*<br/>
<div style='margin-top:-4px;'></div>

When a creature gains the benefit of your Devotion: Pain Suppression, the creature now takes reduced damage from all sources. 

In addition, whenever a creature has temporary hit points granted from your priest class abilities, that creature gains advantage on saving throws against the charmed and frightened conditions and on Wisdom saving throws. 

### Holy
The most adept priests leave their houses of worship to serve on the battlefield as shepherds to flock. There, they use their holy powers to bless allies and mend wounds. And while most stay behind the frontlines to aid their comrades, these holy champions are also capable of smiting foes and carrying out sacred justice. 

##### Holy Calling Spells
Priest Level| Spells
------------|-----------
1st |*bless*, *cure wounds*
3rd |*lesser restoration*, *✦ shining force*
5th |*beacon of hope*, *revivify*
7th |*aura of life*, *death ward*
9th |*mass cure wounds*, *raise dead*

#### Echo of Light 
*1st-level Holy feature*<br/>
<div style='margin-top:-4px;'></div>

Whenever you use a spell slot of 1st level or higher to restore hit points or give another beneficial effect to one or more creatures, a creature of your choice among them regains a number of hit points at the start of your next turn equal to your proficiency bonus. 

#### Renew Faith 
*1st-level Holy feature*<br/>
<div style='margin-top:-4px;'></div>

You learn the *calm emotions* spell and always have it prepared. In addition, you can cast this spell without expending a spell slot. When you do so, you can only target one creature with it, and in addition to the other effects of the spell, when a creature fails the saving throw, you can choose to learn one of the following things about the creature:
* One bond
* One value
* One hope
* One flaw

\columnbreak

&nbsp;&nbsp;&nbsp; The creature does not become aware that you learn this information from them.

Once you cast *calm emotions* in this way, you cannot do so again until you finish a short or long rest. 

#### Devotion: Prayer of Mending
*2nd-level Holy feature*<br/>
<div style='margin-top:-4px;'></div>

As an action, you can expend a use of Devotion to place a ward of mending onto a creature you can see within 30 feet of you for 1 minute. When that creature takes damage, they regain a number of hit points equal to 2d10 + your priest level, and gain resistance to damage for the rest of that turn, including the triggering damage. 

In addition, The ward then immediately moves to another friendly creature of your choice you can see within 30 feet of the first creature. If this creature takes damage, they only regain hit points equal to 1d10 plus half your priest level. After the ward has restored hit points this way, it disappears.

If the ward last for its full duration without restoring hit points, it restores hit points to the current creature by the amount it would as if it moved (2d10 plus your priest level the first time, 1d10 plus half your priest level the second time).

At any time while the ward is up, you can use your bonus action to move the ward to another creature you can see within 30 feet of the warded creature. This does not trigger the healing or count as it jumping.

Once you use this feature, you can't do so again until you finish a short of long rest, unless you spend two uses of Devotion to use it again.

#### Holy Fire
*6th-level Holy feature*<br/>
<div style='margin-top:-4px;'></div>

Whenever you restore hit points or cast a beneficial spell on a creature, they are imbued with radiant power for 1 minute. The next attack that creature lands deals additional radiant damage equal to your Charisma modifier plus your proficiency bonus. 

#### Symbol of Hope
*10th-level Holy feature*<br/>
<div style='margin-top:-4px;'></div>

When you cast a Holy Calling spell that requires concentration, you can choose to cast another spell that also requires concentration, as long as that second spell is also a Holy Calling spell, concentrating on both spells as normal. When you make a concentration check while doing so, you do so with disadvantage, and if you lose concentration, you lose it for both spells. 

Once you use this feature, you cannot do so again until you finish a long rest. 

#### Guardian Spirit 
*18th-level Holy feature*<br/>
<div style='margin-top:-4px;'></div>

A guardian spirit watches over your allies. When a creature within 60 feet of you and is friendly to you drops to 0 hit points or is subjected to an effect that would make them die outright, such as the *power word kill* spell, you can use your reaction to summon this guardian spirit to them. The target is immediately returned to life and healed for half its hit point maximum. The target then gains immunity to all damage until the start of its next turn.

Once you use this feature, you can't use it again until you finish a long rest.

<div class='footnote'>PART 1 | CLASSES</div>

\pagebreak

### Shadow
The brightest light casts the darkest shadow -- and from within this blackness, a rival power dwells. Shadow priests fully embrace this opposing polarity, their faith equally resolute as their holy counterparts. Like all priests, they dedicate much of their lives to worship - However, they dedicate it to Shadow magic and the void, setting themselves around the doctrines of decay and madness. 

##### Shadow Calling Spells
Priest Level| Spells
------------|-----------
1st |*cause fear* ^XGE^, *✦ dark void*
3rd |*✦ mind flay*, *phantasmal force*
5th |*✦ void shift*, *vampiric touch*
7th |*evard's black tentacles*, *✦ schism*
9th |*contagion*, *enervation* ^XGE^

#### Psychic Voice 
*1st-level Shadow feature*<br/>
<div style='margin-top:-4px;'></div>

You can form a telepathic connection between creatures of your choice you can see within 30 feet of you. Choose a number of creature you can see (including yourself), up to your proficiency bonus. The chosen creatures can speak telepathically with each other as long as they are on the same plane. To understand each other, the creatures must speak mentally in a language the other creature knows. 

The telepathic connection last for a number of minutes equal to your priest level, and once used, cannot be used again until you finish a short or long rest, unless you expend a spell slot of 1st level or higher to use it again. 

#### Mind Sear 
*1st-level Shadow feature*<br/>
<div style='margin-top:-4px;'></div>

As a bonus action, you can choose one creature affected by one of your priest spells or abilities. That creature, and all creatures of your choice within 5 feet of them, must succeed on a Intelligence saving throw or take psychic damage equal to half your priest level. Any charmed or frightened creatures who take this damage takes an additional 1d6 psychic damage.

You can use this bonus action a number of times equal to your proficiency bonus, and regain all expended uses when you finish a long rest. 

#### Devotion: Shadowform 
*2nd-level Shadow feature*<br/>
<div style='margin-top:-4px;'></div>

You can expend one use of Devotion and enshroud your body in shadow energy as a bonus action. For one minute, you gain the following effects:
* You can't cast spells that restore hit points, unless it is one of your Shadow Calling spells. 
* You have advantage on Charisma (Intimidation) and Dexterity (Stealth) checks, but disadvantage on all other Charisma checks. 
* Once per turn, when you hit a creature with an attack, or when a creature fails a saving throw from one of your priest spells, you can invoke primal fear in them. The target must succeed on a Charisma saving throw or become frightened of you for 1 minute. The frightened target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

Once you use this feature, you can't do so again until you finish a short of long rest, unless you spend two uses of Devotion to use it again.

#### Dark Thoughts
*6th-level Shadow feature*<br/>
<div style='margin-top:-4px;'></div>

Your mind is more riddled with shadowy thoughts. You gain resistance to psychic damage, and if you have your Shadowform active, you have advantage on saving throws you make to avoid or end early the charmed or frightened condition on yourself.

#### Fortress of the Mind
*6th-level Shadow feature*<br/>
<div style='margin-top:-4px;'></div>

Your mind is more guarded to outside forces. You are immune to any magical effect that would read your thoughts or intentions, such as the *detect thoughts* spell, and Wisdom (Insight) check against you are made with disadvantage.  

Additionally, if a creature attempts to charm or frighten you and you succeed on the saving throw, you can use your reaction to force the creature to make the same saving throw against your priest spell save DC, becoming charmed or frightened of you until the end of your next turn if they fail instead.

#### Horrific Visions
*10th-level Shadow feature*<br/>
<div style='margin-top:-4px;'></div>

You learn how to invoke creature's deepest, darkest fears. When a creature starts their turn frightened or charmed by you, or while under the effect of one of your Shadow Calling spells, you can choose to have their movement halved and on its turn, it can use either an action or a bonus action, not both.

#### Dark Absolution 
*18th-level Shadow feature*<br/>
<div style='margin-top:-4px;'></div>

Your body becomes one with shadowy magic. While you have Shadowform active, you can move through creatures and objects as though they were difficult terrain. If you end your turn inside an object, you take 1d10 force damage. 

In addition, you can manipulate even the strongest of minds. After trying to inflict the frightened or charmed conditions on a creature that is immune to them, until the end of your next turn the creature is treated as if it is frightened or charmed for the purpose of your priest abilities, and gains disadvantage on ability checks while you are in their line of sight for this duration. 

<div class='footnote footnote-white'>PART 1 | CLASSES</div>
<img src='https://www.gmbinder.com/images/AqgsnIF.jpg' style='position:absolute; top:700px; left:80px; width:800px; ' />
<img src='https://www.gmbinder.com/images/VxBG78d.png' style='position:absolute; top:-50px; left:-100px; width:131%; transform:scaleX(-1)' />

\pagebreakNum

## Changelog

### 7/1/2022 - Priest v3.1.3
- Added Art!
- Devotions: Added this "When you use your Devotion, *you brandish your holy symbol and choose which effect*" 
- Devotion Dispel: renamed to Purify, moved to appropriate spot
- Unwavering Faith: may replaced to can
- Subclass Devotions: final sentence changed to "After you use this Devotion option, you cannot use it again until you finish a short or long rest, or unless you expend two uses of Devotion to use it again."
- Discipline Subclass:
    - Calling spells: 4th level spells changed to Mordekainen's Private Sanctum and Otiluke's Resilient Sphere
    - Twist of Fate: Changed the first "after" to "when"
    - Pain Suppression: Added "until your incapacitated *or die* "
    - Rapture: Last sentence changed to "any Atonement damage or healing increases by an amount equal to half your priest level. "
- Holy Subclass:
    - Clarified wording on Prayer of Mending, changed the ability to move it from a reaction to a bonus action.
- Shadow Subclass:
    - Mind Sear: Changed to work on even non-frightened and charmed targets, but now does bonus damage to these creatures.   
- Spell List:
    - Added Alternative Spell Name Table  
    - 5e Spells Added:
        - Charm Person, Enemies Abound, Fast Friends, Gift of Gab, Tasha's Mind Whip, Intellect Fortress, Rary's Telepathic Bond, Tether Essence 
    - New Priest Spells Made:
        - Apotheosis, Archangel, Devouring Plague, Halo, Holy Nova, Luminous Barrier, Mass Dispel, Salvation, Schism, Shadowy Apparitions, Summon Void Being     
    - Priest Spell Changes:
        - Dark Void: Fixed scaling damage from 1d4 to 1d6 
        -Divine Star: Healing boosted from 1d8 to 2d8 
        - Exorcism: base damage lowered from 4d8 to 3d8 
        - Fade: Added "from an attack" to its trigger        
        - Inner Will: Changed spell from "The target creature can use your spellcasting modifier in place of its Wisdom for Wisdom saving throws made to resist or end early effects from aberrations, fiends, and undead," to " The target adds your Wisdom modifier to its own while making Wisdom saving throws. This effect lasts for duration or until the target passes a Wisdom Saving throw it would have otherwise failed."
        - Luminous Barrier: Added "Until the spell ends, the aura moves with you, centered on you." to spell.  
        
\columnbreak
- Priest Spell Changes (continued): 
    - Mind Blast: Fixed scaling damage from 1d10 to 1d8, replaced last sentence with "If this damage would prompt a concentration check, that check is made with disadvantage." 
    - Psychic Horror: Added this line to the end- "If the creature was already frightened and failed the save, they are also stunned while they remained frightened, or until the take damage.
    - Shadowy Apparitions: Added this line "A creature who fails this saving throw also has their movement speed reduced to 0 till the start of their next turn, " and changed the beginning on how the apparitions are made. Also, damage per apparitions is decreased from 8d6 to 3d6. 
    - Summon Void Being: Added following line to Mindbender Tentalce attack: "However, the target's speed is not reduced to 0." 
    - Void Shift: Moved from 4th level to 3rd level. 

### 6/6/2022 - Priest v3.1.2

- Shadow Subclass Reworked from the ground up 
- Typos fixed all around

### 2/17/2022 - Priest v3.1.1
- Core Class Changes:
    - Fixed some typos all around
    - Devotion Beckon: changed effect to give a success on a save in addition to the movement
    - Removed Inner Fire, and Inner Will in the core class
    - Inner Focus changed name to Unwavering Faith, cost a reaction, and moved to 8th level
    - Moved Prodigy of Faith to 17th level
    - Added 10th level subclass levels, moved capstone from 17th to 18th level
- Discipline Subclass:
    - Disc Calling spells: Darkness is replaced with Zone of Truth 
    - Atonement: Changed scaling to two times spell level, and specified can only happen once per casting of a spell
    - Twist of Fate: Added “when you or a creature you can see within 60 feet” to the beginning of the text.
    - Spirit Shield: Removed resistance to physical damage, temp HP dropped to PB.
    - Added Rapture
- Holy Subclass:  
    - Calling Spells: Divination changed to Aura of Life   
    - Prayer of Mending: Added some clarification text all around
    - Holy Fire: Changed “the next weapon attack” to “The next attack the creature lands”
    - Added Symbol of Hope
- Shadow Subclass: 
    - Shadow Calling spells: Shadow Crash is replaced with Contagion
    - Fortress of the Mind: Changed prof of Intimidation to adv on Char checks for 24 hrs, and removed the 1 creature limitation, moved to 10th level.
    - Shadowform: Added "and becomes frightened of you until the start of your next turn" to the reaction
    
\pagebreakNum
- Shadow Subclass (continued):
    - Shadow Orbs: Now are created on inflicting a condition, not from damage rolls. Also, added and removed some effects
- Spells:
    - Added: Levitate, Invisibility, Greater Invisibility, Heroism, Detect Poison And Disease,  Aura of Vitality, Motivational Speech, Raulothim’s Psychic Lance, Skill Empowerment
    - Angelic Feather: Moved to 2nd level, removed Dodge and changed to either resistance to fall damage 
    - Dark Void: Upped damage from 2d4 to 2d6, added “a creature who fails the saving throw can’t regain hit points until the start of your next turn”.
    - Divine Star: Upped dice to d8s, and damage is 3d8
    - Mind Blast: Lowered damage from 1d10 to 1d8, and added a disadvantage effect on concentration effects.
    - Mind Flay: Clarified some language
    - Shadow Crash: Changed damage from 8d8 necrotic to 4d8 necrotic and 4d8 psychic
    - Void Shift: Added “ This spell has no effect on a creature who is incapacitated or at 0 hit points.”
    - Exorcism: Fixed scaling damage, and specified that attacking a charmed or possessed creature only does damage to its charmer or possesser in range.
    - Fade: Changed it to 2nd level instead of 3rd.
    - Inner Fire: Added Self only, Duration 8 hrs, Replaced the last sentence with “gains advantage on saving throws against and to end early the frightened condition”

### 2/13/2022 - Priest v3.1 released

### 7/25/2023 - Tyloris Edit
- Overall formatting fixes.
- Many small grammar and spelling checks.
- Completely revised the introduction.
- Added footnote to each page.
- Rearranged the priest class table, removing the Devotion column.
- Added suggested background to quick build section.
- Removed herbalism kit from starting proficiencies. Priests are not known for their skills with herbs.
- Replaced mace with club for starting equipmen, as priests are less martial than clerics. Removed one of the two daggers and herbalism kit from starting equipment and replaced with healer's kit. Added crossbow or simple weapon option, for consistency.
- Switched order of Spellcasting and Divine Calling, following the cleric's example.
- Reverted example spell in Spellcasting from Flash Heal (which is no longer a spell) to Cure Wounds.
- Added an equivalent ability to Harness Divine Power from Tasha's Cauldron of Everything to Devotion.
- Added missing Ability Score Improvement feature, as well as Divine Versatility.
- Added a range to the Divine Word: Beckon.
- Language clarification of Divine Word: Fortitude.
- Changed Divine Word: Pain to a reaction.
- Added Light vs Shadow sidebar.
- Rearranged Unwavering Faith's features into alphabetical order.
- Clarified that Divine Strike's damage type is chosen at selection.
- Restricted Power Infusion to priest cantrips.
- Added "(with a minimum bonus of +1)" to the Power Infusion and Unwavering Faith abilities.
