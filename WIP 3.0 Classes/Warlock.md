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
    left      : 12px;
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
    opacity: 0.6;
  }

  .inkblot-blue {
    filter: hue-rotate(190deg) saturate(120%)
  }

  .inkblot-green {
    filter: hue-rotate(120deg)
  }

</style>

<div style='margin-top:500px'></div>

<div style='margin-top:500px'></div>

## Warlock
*Imagine what you could do if you led a group of shaman who controlled the source of their powers, instead of begging and scraping for it. Imagine if these shaman had servants who could also fight on your side. Servants who could send your enemies fleeing helplessly in terror. Suck their magic dry as the insects in the summer suck blood.*
<div style="text-align:Right"> 

*— Gul'dan*  </div>

An imp skitters behind her as a young human clad in robes smiles warmly, weaving magical charms into her honeyed words, bending the palace sentinels to her will.

A brutish orc waves his hand in the air, sparking flames of green and red, with a flash of his hand, he hurls a ball of fel infused fire against a night elf.

Shifting his gaze between a battered tome and the rough drawn glyphs made in the dirt. A wild eyed forsaken begins a slow chant, as a demonic gate erupts from the ground.

Warlocks and seekers of the knowledge that lies hidden in the fabric of the multiverse. Through their powerful fel magic and secret grimoire, warlocks unlock magical effects both subtle and spectacular. They draw on powers often forbidden throughout Azeroth to bolster their own power.

### Dark Arts, Dominance
In the face of demonic powers, most adventurers see death and destruction. Warlocks see only opportunity, dominance is their aim, and have found a path to it in their fel sorcery. These voracious spellcasters enslave demon as their minions to fight and protect besides them. The power of their enslaved demons strengthens as the warlock does, making them able to summon deadly demons to their aid.

<br>
<div style='margin-top:484px'></div>

### Wielders of Fel
Warlocks are the wielders of the destructive fel magic, a form of magic often used by demons and members of the Burning Legion. It is a form of magic that is demonic, entropic, and extremely chaotic. Its practice has been banned throughout most regions of Azeroth, and is not something even warlocks dare practice openly, yet it is still practiced by most warlocks in secrecy.

Whilst other forms of magic comes as a natural source from the wielder or is granted by the spirits, fel magic is a bargain, it corrupts the minds of those surrounded and affected by it, and desecrates the land it touches. If their demonic minion was not enough to frighten common folks of Azeroth, the knowledge of the fel powers they wield are enough to discourage service to them.

### Delvers of Secrets
Warlocks are the most volatile and insatiable of spell-casters. Though they often pledge themselves to the service of noble causes and are not innately evil, their desire to understand darker magics and exercise unwavering command over demonic forces breeds mistrust among even their closest allies. Warlocks peer into the Void without hesitation, leveraging the chaos they glimpse within to devastating ends in battle—their greatest abilities are fueled by the souls they’ve harvested from their victims. 

They exploit powerful shadow and fel magic to manipu-late and degrade the minds and bodies of their enemies. They employ hellish fires to rain from the skies, immolating their opponents, summoning and commanding indomitable demons from the Twisting Nether to do their bidding, or even to be sacrificed as the Warlock sees fit, empowering and protecting the dark caster from harm.

<div class='footnote'>PART 1 | CLASSES</div>
<img src='https://www.gmbinder.com/images/4LCuUb6.jpg' style='position:absolute; top:0px; right:-100px; width:900px;transform:scalex(-1)' />
<img src='https://www.gmbinder.com/images/76ytPWI.png' style='position:absolute; top:-470px; right:-200px; width:1500px;transform:rotate(-2deg)' />
<img src='https://www.gmbinder.com/images/kWRapfL.png' style='position:absolute; top:30px; right:260px; width:550px;transform:scalex(-1)' />

\pagebreakNum

<div class="classTable wide" />

##### Warlock

Level   |Proficiency<br>Bonus|Features          |Cantrips<br>Known|Spells<br>Known|Spell<br>Slots|Slot<br>Level
--------|:-:|---------------------------------------------------|:-:|:-----:|:-:|:-----:|:--:
1st     |+2 |Profane Knowledge, Fel Sorcery, Life Tap (1/day)   |2  |2      |1  |1st    |-
2nd     |+2 |Fel Study, Dark Knowledge                          |2  |3      |2  |1st    |-
3rd     |+2 |Soul Shards                                        |2  |4      |2  |2nd    |2
4th     |+2 |Ability Score Improvement                          |3  |5      |2  |2nd    |2
5th     |+3 |Soulforging, Additional Demon                      |3  |6      |2  |3rd    |3
6th     |+3 |Fel Study Feature                                  |3  |7      |2  |3rd    |3
7th     |+3 |Life Tap (2/day), Additional Demon                 |3  |8      |3  |4th    |4
8th     |+3 |Ability Score Improvement                          |3  |9      |3  |4th    |4
9th     |+4 |Soul Shards Improvement, Additional Demon          |3  |10     |3  |5th    |5
10th    |+4 |Fel Study Feature                                  |4  |10     |3  |5th    |5
11th    |+4 |Nethermancy (6th Level)                            |4  |11+1   |3  |5th    |5
12th    |+4 |Ability Score Improvement                          |4  |11+1   |4  |5th    |6
13th    |+5 |Nethermancy (7th Level)                            |4  |12+2   |4  |5th    |6
14th    |+5 |Fel Study Feature, Life Tap (3/day)                |4  |12+2   |4  |5th    |6
15th    |+5 |Nethermancy (8th Level)                            |4  |13+3   |4  |5th    |7
16th    |+5 |Ability Score Improvement                          |4  |13+3   |4  |5th    |7
17th    |+6 |Nethermancy (9th Level)                            |4  |14+4   |5  |5th    |7
18th    |+6 |Fel Study Feature                                  |4  |14+4   |5  |5th    |8
19th    |+6 |Ability Score Improvement                          |4  |15+4   |5  |5th    |8
20th    |+6 |Life Tap (at will)                                 |4  |15+4   |5  |5th    |8

**Note:** The "+X" represents Nethermancy spells.
</div>

<div style='margin-top:-5px'></div>

### Sworn and Beholden
Warlocks are defined by the powers they wield, the power-ful fel that the have studied, granting them knowledge of powers hidden to mages and arcanists. A warlock might be a new found member of one of Azeroth's many cults hidden in ruins no longer used, studying fel in secrecy, attempting to unlock devastating powers.

The boons bestowed upon a warlock through their studies ranges from minor but lasting alterations to the warlock's being, to access of powerful spells. Unlike bookish wizards, warlocks supplement their magic with some faciliy at hand-to-hand combat.

<div style='margin-top:-5px'></div>

### Creating a Warlock
As you make your warlock character, spend some time thinking about why you decided to delve into the secrets of fel, its impressive and destructive nature. Were you seduced by the powers it had? What the fel promised for you? Did you seek out a warlock yourself? or perhaps you became addicted to its powers. How your studies came to be is for you to decide.

<div style='margin-top:-3px'></div>

#### Quick Build
You can make a warlock quickly by following these sug-gestions. First, Intelligence should be your highest ability score, followed by Constitution.

\columnbreak

## Class Features
As a warlock, you have the following class features.

#### Hit Points
___
- **Hit Dice:** 1d8 per warlock level
- **Hit Points at 1st Level:** 8 + your Constitution modifier
- **Hit Points at Higher Levels:** 1d8 (or 5) + your Constitution modifier per warlock after 1st

#### Proficiencies
___
- **Armor:** None
- **Weapons:** Simple weapons
- **Tools:** None
___
- **Saving Throws:** Intelligence, Charisma 
- **Skills:** Choose two skills from Arcana, Deception, History, Insight, Intimidation, Perception, or Religion

#### Equipment
You start with the following equipment, in addition to the equipment granted by your background

- any simple weapon
- *(a)* a component pouch or *(b)* an arcane focus
- *(a)* a scholar's pack or *(b)* an explorer's pack
- two daggers and a belt pouch

<div class='footnote'>PART 1 | CLASSES</div>

\pagebreakNum

### Profane Knowledge
You have spent long hours researching and practicing forbidden knowledge. As a result, at 1st level you gain the following benefits:
- You can speak, read, and write Eredun.
- You have advantage on Intelligence checks made to recall information about aberrations, fiends, and undead.
- When you make a Charisma check while interacting with fiends, your proficiency bonus is doubled.

### Fel Sorcery
Your research into forbidden knowledge has given you facility with spells. See chapter 10 of the Player's Handbook for the general rules of spellcasting and chapter 6 for the warlock spell list.

#### Cantrips
You know two cantrips of your choice from the warlock spell list. You learn additional warlock cantrips of your choice at higher levels, as shown in the Cantrips Known column of the Warlock table.

#### Spell Slots
The Warlock table shows how many spell slots you have. The table also shows what the level of those slots is; all of your spell slots are the same level. To cast one of your warlock spells of 1st level or higher, you must expend a spell slot. You regain all expended Fel Sorcery spell slots when you finish a short or long rest.

For example, when you are 5th level, you have two 3rd-level spell slots. To cast the 1st-level spell *Witch Bolt*, you must spend one of those slots, and you cast it as a 3rd-level spell.

#### Spells Known of 1st Level and Higher
At 1st level, you know two 1st-level spells of your choice from the warlock spell list.

The Spells Known column of the Warlock table shows when you learn more warlock spells of your choice of 1st level or higher. A spell you choose must be of a level no higher than what's shown in the table's Slot Level column for your level. When you reach 6th level, for example, you learn a new warlock spell, which can be 1st, 2nd, or 3rd level.

Additionally, when you gain a level in this class, you can choose one of the warlock spells you know and replace it with another spell from the warlock spell list, which also must be of a level for which you have spell slots.

#### Spellcasting Ability
Intelligence is your spellcasting ability for your warlock spells, so you use your Intelligence whenever a spell refers to your spellcasting ability. In addition, you use your Intelligence modifier when setting the saving throw DC for a warlock spell you cast and when making an attack roll with one.

<div style="text-align: center">

**Spell save DC** = 8 + your proficiency bonus + <br> your Intelligence modifier

**Spell attack modifier** = your proficiency bonus + <br> your Intelligence modifier
</div>

#### Ritual Casting
You can cast a warlock spell as a ritual if that spell has the ritual tag and you know the spell.

\columnbreak
#### Spellcasting Focus
You can use an arcane focus as a spellcasting focus for your warlock spells.

### Life Tap
When you take your 1st level in this class, you learn to draw on your own life force to fuel your immense power. 

When you do not have any Fel Sorcery spell slots remaining, you can still cast a spell as though you do. As part of the action to cast the spell, you lose hit points equal to your level plus your Fel Sorcery slot level. For example, a 7th level warlock with 4th level spell slots would spend 11 hit points to cast a 4th level spell.

This damage cannot be resisted, and you cannot use this feature if doing so would reduce you to 0 hit points. You can use this ability once at 1st level, twice at 7th level, three times at 14th level, and any number of times at 20th level. You regain all expended uses when you finish a long rest.

### Fel Study
When you reach 2nd level, you select a subclass. Three of these are the Study of Affliction, Study of Demonology, and Study of Destruction.

### Demonic Knowledge
At at 2nd level, your studies into grimoires of dark knowledge have given you the power to summon demons. You can call upon the principles of the Grimoire of Service to bind them as your **demonic minion** or you can follow the teachings of the Grimoire of Sacrifice to rip out their **demonic core**, which you can draw upon to power your own abilities.

Summoning a demon, either to bind it as your minion or to obtain its demonic core, can be done at the end of a long rest. You can only have one demonic minion or core at a time. 

#### Demons Known
You start by knowing how to summon one particular type of demon of your choice. You learn an additional demon type at levels 5, 7, 9, and 13. Whenever you gain a level in this class, you can choose to replace one demon you know. Demons and their cores are described in Appendix C. 

#### Grimoire of Sacrifice
Using the Grimoire of Sacrifice, you can destroy a demon when you summon it to obtain its demonic core, the source of its power. A demonic core differs from demon to demon. It could be something like a bit of horn, a still-beating heart, or a glowing green stone orb.

At 2nd level while carrying the core you have advantage on two skill checks. While holding the core, you gain an additional spell or cantrip known. You are able to cast this spell at will. 

As you increase in level, you are able to draw deeper upon the core to cast more powerful spells. At 5th and 9th levels you gain an additional spell known while holding the core. You can cast these spells once each without expending a spell slot and regain the ability to do so when you finish a long rest.

At level 13 you can consume the orb as an action to recharge your own powers, regaining all expended soul shards.

<div class='footnote'>PART 1 | CLASSES</div>

\pagebreakNum

#### Grimoire of Service
Using the Grimoire of Service, you can bind a demon into becoming your minion. Your minion acts independently of you, but it always obeys your commands. They have abilities and game statistics determined in part by your level. The demon uses your proficiency bonus rather than its own, and gains more abilities as you gain warlock levels. 

Once summoned, a demonic minion remains until it is slain or dismissed. You can temporarily dismiss your minion as an action. It disappears into a pocket dimension where it awaits your summons. Alternatively, you can dismiss it forever. As an action while it is temporarily dismissed, you can cause it to reappear in any unoccupied space within 30 feet of you.

When the minion drops to 0 hit points, it disappears, leaving behind no physical form. If the demon has died within the last hour, you can expend a soul shard as an action to revive it, provided you are within 5 feet of it. The demon returns to life after 1 minute with all its hit points restored. Otherwise, you can summon a new minion when you perform the ritual again.

In combat, it shares your initiative and takes its turn immediately after yours. A minion can't attack, but it can take other actions as normal. It can move and use its reaction on it's own, but the only action it takes on its turn is the Dodge action, unless you take a bonus action on your turn to command it to take the action in its stat block or the Dash, Disengage, Help, Hide or Search action.

### Soul Shards
Starting at 3rd level, you gain the ability to create soul shards: small crystals formed from fragments of souls and spirits. You can expend a soul shard to empower your warlock spells and abilities. You start knowing the abilities listed below and learn more as you gain more levels in the warlock class. 

You can have up to three soul shards at any given time; attempting to create an additional soul shard results in a useless dull gemstone. Soul shards last until used, at which point they disappear. If a soul shard leaves your possession for at least 8 hours, it disappears. Soul shards you create can only be used by you; soul shards created by other warlocks are useless.

Over the course of a rest, you can gather fragments of wandering souls to create soul shards. You can create a single soul shard over the span of a short rest, or any number over a long rest.

\columnbreak

> ##### Creature Soul Shards
> Soul shards are only useful if they are created from sufficiently dense spirit energy or complex souls. While some exceptions exist, the following guidelines typically hold true:
> - All humanoids can produce soul shards.
> - Most undead and almost all constructs cannot produce soul shards.
> - All other creature types typically only produce soul shards if their souls are sufficiently complex: i.e., their CRs are 1/8 and above.

Additionally, you can capture part of the escaping souls of nearby dying creatures in the form of soul shards. When an appropriate creature within 60 feet of you dies, you can use your reaction to create a single soul shard. 

When you reach 9th level, your maximum number of soul shards increases to five.

What constitutes an appropriate creature is up to a DM's discretion, but a guideline is listed in the **Creature Soul Shards** sidebar. 

You can expend a soul shard within 5 feet of you to create one of the following effects:

***Casting Circle.*** You can expend a soul shard as a bonus action to create a 5-foot radius circle of demonic runes to appear on the ground. As long as you remain in this circle, you have advantage on concentration checks. The circle fades after 1 minute.

***Soulburn: Extend.*** When you cast a spell that has a duration of 1 hour or more, you can expend a soul shard to extend the duration by a number of hours equal to your warlock level.

***Soulburn: Quicken.*** When you cast a spell that has a casting time of 10 minutes or less, you can expend a soul shard to cast it as an action instead.

***Soulburn: Rebound.*** When you cast a spell that affects a single target and it has no effect (either due to missing on the attack roll or the target succeeding on their saving throw), you may expend a soul shard as a reaction to redirect it to another target within range.

***Soul Rites.*** You can expend a soul shard to cast any warlock spell with a ritual tag as a ritual as long as you have Fel Sorcery or Nethermancy spell slots of the spell's given level. You do not have to know the spell to cast it as a ritual as long as it is on the warlock spell list.

### Ability Score Improvement
When you reach 4th level, and again at 8th, 12th, 16th, and 19th level, you can increase one ability score of your choice by 2, or you can increase two ability scores of your choice by 1. As normal, you can't increase an ability score above 20 using this feature.

<img src='https://www.gmbinder.com/images/8GHYm5P.jpg' style='position:absolute; top:770px; right:0px; width:800px' />
<img src='https://www.gmbinder.com/images/3e9S91s.png' style='position:absolute; top:-80px; right:0px; width:900px' />
<img src='https://www.gmbinder.com/images/pZ94Ass.png' style='position:absolute; top:730px; right:400px; width:350px' />

<div class='footnote'>PART 1 | CLASSES</div>

\pagebreakNum

### Soulforging
At 5th level, you learn to forge powerful, magical stones from your soul shards. You create a stone by expending a soul shard, which is done as an action. Once a stone has been created, it lasts until used, after which it crumbles to dust. You can only have a single stone of each type created at a time; creating an additional stone will cause the other stone to become inert.

***Firestone.*** You can expend this stone when casting a warlock spell to cause it to deal a critical hit on a roll of 19 or 20. If the spell does not use an attack roll, it instead deals damage as if it were one spell level higher.

***Healthstone.*** You or another creature can crush the healthstone as an action to regain a number of hit points equal to your Intelligence modifier + your warlock level.

***Soulstone.*** You can expend this stone to cast the *revivify* spell without expending a spell slot or providing material components. If you are reduced to 0 hit points and are carrying a soulstone, it is automatically expended and you are reduced to 1 hit point instead.

***Spellstone.*** You can expend this stone when casting a warlock spell, causing creatures to have disadvantage on saves versus that spell.

### Nethermancy
At 11th level, you gain the ability to push yourself to cast more powerful spells a certain number of times per day. You gain a single spell slot of 6th level. This spell slot can be expended to cast any warlock spell you know. You regain any expended Nethermancy spell slots when you finish a long rest.

Whenever you gain a spell slot through Nethermancy, you also learn a single warlock spell of a level that you can cast. These are counted separately from your normal spells, as shown on the Spells Known column of the Warlock table.

At higher levels you earn more spell slots: one 7th level spell slot at 13th level, one 8th level slot at 15th level, and one 9th level slot at 17th level.

When you gain a level in this class, you can choose one of the warlock spells gained through Nethermancy and replace it with another spell from the warlock spell list.  

## Fel Studies
Warlocks have come into contact with the powerful fel, studying its uncontrollable energy. Three such studies exist, each delving into a different aspect of the powers wielded by warlocks.

### Study of Affliction
Warlocks that study affliction become masters of shadow-touched powers, unlike priests of the shadow priesthood, warlocks delight in the use of fel as a force to cause pain and leaving their enemies in whirls of torment.

\columnbreak
#### Expanded Spell List
Your area of study lets you choose from an expanded list of spells when you learn a warlock spell. The following spells are added to the warlock spell list for you.

##### Affliction Expanded Spells
Spell<br>Level|Spells
--------------|------
1st|✦ *dark void*, *dissonant whispers*
2nd|*blindness/deafness*, ✦ *mind flay*
3rd|*slow*, *stinking cloud*
4th|*confusion*, *elemental bane ^XGE^*
5th|*cloudkill*, *contagion*

#### Corruption
Starting at 2nd level, you learn how to cast Banes, which are powerful curses that can be placed upon creatures. You learn one Bane of your choice, which are detailed under "Banes" below. You learn one additional Bane of your choice, and you can choose one of the Banes you know and replace it with another, at 6th, 10th, 14th, and 18th level.

When you use your Corruption, you choose which Bane to invoke. While invoking a Bane, but before it affects the target, you can choose to amplify the curse by expending a soul shard. An amplified curse gains an additional effect, noted in the curse’s description. If a Bane calls for a saving throw, it uses your warlock spell save DC.

You can use this feature once. Beginning at 6th level, you can use your Corruption feature twice, at 14th level you can use it three times between rests, and at 18th level, you can use it four times between rests. You regain all expended uses when you finish a short or long rest.

#### Haunt
At 2nd level, when a creature within 60 feet makes a skill check using Charisma, Intelligence, or Wisdom, you can use your reaction to manifest a demonic presence around it. The creature is haunted, its mind clouded by this presence.
    
The target must make a Wisdom saving throw against your warlock spell save DC. On a failed save, the skill check also fails. If the target makes another skill check using the same ability score, while haunted, it must repeat the saving throw.

On a successful save, the haunt ends and the skill check is made as normal. Once you use this ability, you can't do so again until you finish a short rest.

#### Curse Master
At 6th level, you learn the *bestow curse* and *remove curse* spells. These do not count against the number of spells known listed in the Warlock table.

Additionally, when you cast either of these spells you can target two creatures instead of one.

<div class='footnote'>PART 1 | CLASSES</div>
<img src='https://www.gmbinder.com/images/Narbe7i.jpg' style='position:absolute; bottom:-670px; right:0px; transform:rotate(0deg) scaleX(-1)' />
<img src='https://www.gmbinder.com/images/3e9S91s.png' style='position:absolute; top:-80px; left:0px; width:900px;' />

\pagebreakNum

#### Drain Soul
When you reach 10th level, your power over souls increases. When you deal psychic or necrotic damage to a creature, you can generate one soul shard. You can use this ability three times and regain any expended uses when you finish a long rest.

#### Unstable Afflictions
Starting at 14th level, your magic lashes out against those who try to avoid it. When a creature successfully makes a saving throw against one of your warlock spells or abilities, they take an amount of psychic damage equal to half your warlock level.

#### Potent Afflictions
When you reach 18th level, you learn a powerful curse. Choose one of the following options. Once you use either ability, you cannot do so again until you finish a long rest.

***Curse of Doom.*** You learn a curse of impending doom. As a bonus action, you place the curse on one creature you can see within 60 feet. At the end of each creature's turn, the target creature takes 1d4 psychic damage. This damage increases by 1 for each turn after the first.

After the target takes damage from this curse six times, or when the creature dies, the curse ends and a doomguard appears within 5 feet of the cursed target, or the nearest available space. 

The doomguard acts on the turn immediately after yours and obeys your commands (no action required) for 1 minute or until killed or dismissed as a bonus action, after which it disappears. 

***Seed of Corruption.*** You learn how to place a fragment of shadow energy inside a creature, that grows until detonated. As a bonus action, you can place the curse on a creature that you can see within 60 feet. 

The creature takes 1d6 points of psychic damage at the beginning of its turn. This damage increases by 1d6 each turn after the first. The creature can attempt a Wisdom save at the end of its turn, ending the effect when it makes two successful saves. 

<div style='margin-top:-5px'></div>

When the curse is ended, either by the creature dying or making its save, a number of creatures of your choice within 60 feet up to the number of dice of psychic damage last rolled for this curse must must make a Wisdom saving throw against your warlock spell save DC or gain one curse of your choice from the spell *bestow curse*. If the cursed target dies as a result of this ability's damage, the creatures have disadvantage on their saving throws.

The same curse must be applied to all affected creatures. This curse lasts for 24 hours unless removed. Attempting to do so requires an ability check against your warlock save spell DC to succeed. 

#### Banes
The banes are presented in alphabetical order.

<div style='margin-top:-5px'></div>

##### Bane of Agony
As a bonus action, you curse a creature you can see within 30 feet, dealing 1d4 points of psychic damage. During each of your turns for the next minute, you can use your bonus action to deal 1d4 psychic damage to the creature. This damage increases as you level: 2d4 at 5th level, 3d4 at 11th level, and 4d4 at 17th level. The creature can attempt a Wisdom save at the beginning of its turn, ending the effect on a success.

***Amplify.*** When the target is damaged by the Bane, it has disadvantage on the next attack roll it makes before the end of its next turn.

<div style='margin-top:-5px'></div>

##### Bane of the Elements
When a creature you can see within 30 feet is hit with an attack or spell, you can use your reaction to temporarily weaken their resilience against it. Until the end of the turn, the target loses their resistance to the damage types of the triggering attack or spell.

***Amplify.*** The target instead loses immunity to the damage types of the triggering attack or spell, having resistance to them until the end of the turn.

<div style='margin-top:-5px'></div>

##### Bane of Exhaustion
As a bonus action, you can attempt to exhaust a creature you can see within 30 feet of you. The target must succeed on a Constitution saving throw or have their speed be reduced to 0 and they can’t use reactions until the end of your next turn.

***Amplify.*** This curse lasts for 1 minute. At the end of each of its turns, the cursed creature can make another Constitution saving throw. On a success, this curse ends.

##### Bane of Fragility
As a bonus action, you can attempt to curse a creature you can see within 30 feet. The creature cannot regain hit points until the end of its next turn. Additionally, any temporary hit points it possesses are removed. When the effect ends, it regains any temporary hit points it possessed.

***Amplify.*** The curse lasts for 1 minute. At the end of each of its turns, the cursed creature can make a Wisdom saving throw. On a success, this curse ends.

##### Bane of Recklessness
When a creature you can see within 30 feet makes an attack roll, you can use your reaction to cause them to attack recklessly. Until the beginning of its next turn, attacks against the creature have advantage.

***Amplify.*** For 1 minute, the target cannot use the Disengage, Dodge, or Hide actions. The creature can attempt a Wisdom save at the end of each of its turns, ending the effect on a success.

##### Bane of Shadows
As a bonus action, you curse a creature you can see within 30 feet until the beginning of your next turn. The first time in a turn that the creature is damaged, it takes an additional 1d8 points of necrotic damage. When the creature takes this extra damage, it can can attempt a Wisdom saving throw against your warlock spell save DC, ending the effect on a success.

***Amplify.*** The curse lasts for 1 minute.

##### Bane of Tongues
When a creature you can see within 30 feet attempts to cast a spell with a vocal component, you can use your reaction to try to disrupt it with a curse. The creature must use its own reaction to succeed in casting the spell. Until the end of the creature's next turn, it is unable to speak any language it knows.

***Amplify.*** The curse lasts for 1 minute. The creature must use either a bonus action or reaction each time it attempts to cast a spell or the spell fails and is wasted. The creature can attempt an Intelligence saving throw at the end of each of its turns, ending the effect on a success.

<div class='footnote'>PART 1 | CLASSES</div>

\pagebreakNum
##### Bane of Weakness
As a bonus action, you curse a creature you can see within 30 feet until the beginning of your next turn. Whenever the creature hits with a weapon attack, it rolls twice for damage and takes the lower result.

***Amplify.*** The curse lasts for 1 minute. The creature can attempt an Constitution saving throw at the beginning of your turn, ending the effect on a success.

### Study of Demonology
Warlocks that study demonology harness the powers of the malefic demon beings of the twisting nether. Uncovering secrets unknown by residents of Azeroth, and twisting their magic with the aid of demonic powers from the great dark.

#### Expanded Spell List
Your area of study lets you choose from an expanded list of spells when you learn a warlock spell. The following spells are added to the warlock spell list for you.

<div style='margin-top:-5px'></div>

##### Demonology Expanded Spells
Spell<br>Level|Spells
--------------|------
1st|*command*, *protection from evil and good*
2nd|*augury*, *spiritual weapon*
3rd|*magic circle*, *spirit guardians*
4th|*dimension door*, *dominate beast*
5th|*infernal calling ^XGE^*, *planar binding*

#### Soul Conduit
Your studies into demonology at 2nd level allow you to form a stronger bond between you and your demonic minions. You can communicate telepathically with your minion as long as you are on the same plane of existence. 

If your minion has died in the last hour, you can expend a soul shard as an action to call it back to life provided that you are within 5 feet of the spot where it died. It returns to your side after 1 minute has passed.

Additionally, as an action, you can see through its eyes and hear what it hears until the start of your next turn, gaining the benefits of any special senses that the demon has. During this time, you are deaf and blind with regard to your own senses.

While perceiving through your minion's senses, you can also speak through your familiar in your own voice, even if your companion is normally incapable of speech.

Finally, when you cast a spell with a range of touch, your demon companion can deliver the spell as if it had cast the spell. Your companion must be within 100 feet of you, and it must use its reaction to deliver the spell when you cast it. If the spell requires an attack roll, you use your attack modifier for the roll.

#### Sense Demons
Also at 2nd level, you gain the ability to occasionally sense the presence of demons due to your sensitivity to demonic energies. As an action, you can open your awareness to magically detect demons. Until the end of your next turn, you know the location of any demon within 60 feet of you that isn't behind total cover and that isn't protected from divination magic. This sense doesn't tell you anything about a creature's capabilities or identity.

You can use this feature a number of times equal to your Intelligence modifier (minimum of once). You regain all expended uses when you finish a long rest.

#### Soul Link
At 6th level, while the demon is within 60 feet of you, half<br> of any damage you take (rounded up) is transferred to the demonic companion.

Additionally, your demon companion can use its reaction in place of yours to generate a soul shard.

#### Demonic Fury
Beginning at 10th level, you gain a pool of energy equal <br> to 1 + your Intelligence bonus you can use to empower your demon. You can use a single point of this energy to gain one of the following effects, and you regain any expended points when you finish a long rest:
- When you command your demon to take the Attack action, you can spend a point to give them advantage on the attack roll.
- When your demon is forced to make a saving throw, you can spend a point as a reaction to give them advantage on the roll.

#### Grimoire of Supremacy
At 14th level, you can call upon the knowledge of the Grimoire of Supremacy to permanently evolve your demonic minion into a more powerful form. It gains a number of benefits as mentioned in its entry in Appendix C. 

#### We Are Legion
When you reach 18th level, you have managed to apply the teachings of the Grimoire of Supremacy to yourself, permanently transforming you into a demon. You can gain two or more quirks from the Metamorphosis Quirks table (or come up with similar quirks) and the following abilities: 

- You sprout wings that grant you a fly speed equal to your movement speed. You can hide or unhide these wings as a bonus action.
- You gain resistance to fire and necrotic damage.
- You do not age, and you do not need to eat, drink, or sleep.
- Demons with an intelligence of 3 or lower will not attack you unless you attack them.

##### Metamorphosis Quirks
d8|Quirk
--|--
1|Your eyes turn green and glow in the dark.
2|Your skin turns green or red. 
3|Your teeth grow into fangs or tusks and your fingernails and toenails resemble black claws.
4|You sprout horns from your forehead.
5|Your skin sprouts spikes or becomes scale-like.
6|You appear to have aged by several decades, though this does not reduce your lifespan.
7|Your blood turns bright green and faintly glows.
8|Your body becomes twisted, giving you a hunched appearance and a limp.

<div class='footnote'>PART 1 | CLASSES</div>

\pagebreakNum

### Study of Destruction
Warlocks that study destruction meddle with the metaphysical concept of destruction, willing to suffer backlash if they are better able to wreak havoc upon their enemies. They are happy to revel in the destruction they cause, thrilled at any opportunity to watch the world erupt in discord.

#### Expanded Spell List
Your area of study lets you choose from an expanded list of spells when you learn a warlock spell. The following spells are added to the warlock spell list for you.

##### Destruction Expanded Spells
Spell<br>Level|Spells
--------------|------
1st|*burning hands*, *chaos bolt ^XGE^*
2nd|*flaming sphere*, *shatter*
3rd|*erupting earth ^XGE^*, *fireball*
4th|*fire shield*, *wall of fire*
5th|*destructive wave*, *flame strike*


<!-- <img src='https://www.gmbinder.com/images/PaN737V.jpg' style='position:absolute; right:-90px; top:-60px; width:570px; transform:rotate(10deg)' />
<img src='https://www.gmbinder.com/images/fnPL7gX.png' style='position:absolute; left:-100px; top:-170px; width:900px; transform:scaleY(-1) scaleX(-1);' />
<img src='https://www.gmbinder.com/images/vn90cy3.png' style='position:absolute; bottom:-30px; left:0px; width:1000px' /> -->

#### Pyrophile
When you choose this study at 2nd level, you learn the *produce flame* cantrip, which you treat as a warlock cantrip and does not count against your cantrips known. 

Additionally, you can magically ignite a flammable object you touch with your hand as an action.

#### Channel Demonfire
Also at 2nd level, you can channel the double-edged power of hellfire into your spells.

When you deal damage with a warlock spell of 1st level or higher, you can choose to take an amount of fire damage up to your warlock level. One target takes twice as much fire damage as you took. 

#### Havoc
Starting at 6th level, you can duplicate certain spell effects. When you cast a warlock spell with a Fel Sorcery spell slot that targets only one creature and doesn't have a range of self, you may expend a soul shard to cast the spell a second time without expending a spell slot, targeting a second creature in range of the spell.

#### Unending Resolve
At 10th level, when you reduce a hostile creature to 0 hit points, you gain temporary hit points equal to your Intelligence modifier + your warlock level (minimum of 1).

#### Flames of Xerrath
When you reach at 14th level, you can overcharge the power of your spells with the power of fel flames. When you deal damage with a warlock spell cast using a Fel Sorcery spell slot, you can deal maximum damage with that spell.

The first time you do so, you suffer no adverse effect. If you use this feature again before you finish a long rest, you take 5d12 fire damage at the end of the current turn. Each time you use this feature again before finishing a long rest, the fire damage increases by 1d12. This damage ignores resistance and immunity. 

\columnbreak
#### Inferno
When you reach 18th level, you gain the ability to conjure a meteor from the Twisting Nether. As an action, you can cause a meteor alight with green flame to appear in the air and crash down to a point you designate within 60 feet. 

Creatures in a 30 feet radius of that point take 2d8 points of bludgeoning damage and 2d6 points of fire damage and the ground becomes difficult terrain. You can then choose to either detonate the stone, dealing 13d10 fire damage to all creatures within 30 feet of the point (Dexterity save for half damage), or you can animate it as an infernal. 

The infernal rises from the crater at the end of your turn, following your commands (no action). It remains animated for 1 minute, or until killed or dismissed as a bonus action. When you dismiss the infernal, you can choose whether to merely dismiss it or force it to use its Death Burst ability. 

Once you have used this ability, you cannot do so again until you finish a long rest.

<div class='footnote'>PART 1 | CLASSES</div>
<img src='https://www.gmbinder.com/images/Zvvr01c.jpg' style='position:absolute; bottom:0px; right:-90px; width:550px '/>
<img src='https://www.gmbinder.com/images/i9dzMuI.png' style='position:absolute; bottom:-140px; right:-50px; width:900px;' />
<img src='https://www.gmbinder.com/images/i9dzMuI.png' style='position:absolute; top:0px; right:-50px; width:900px;' />
<!-- <img src='https://www.gmbinder.com/images/Zvvr01c.jpg' style='position:absolute; top:0px; right:180px; width:820px' />
<img src='https://www.gmbinder.com/images/Npi5n8k.png' style='position:absolute; top:0px; right:-20px; width:900px' /> -->

\pagebreakNum
# Chapter 6: Spells
While most spell descriptions are located in the Player's Handbook, some spells are described in other locations, as indicated by the table below.

Symbol|Spell Location
------|--------------------------
✦ |In this chapter, under Spell Descriptions
^EGW^ | Explorer's Guide to Wildemount
^IDRotF^ | Icewind Dale: Rime of the Frostmaiden
^SCAG^ |Sword Coast Adventurer's Guide
^TCE^ | Tasha's Cauldron of Everything
^XGE^ |Xanathar's Guide to Everything

> ##### Variant Rule: Xorothian Steed
> Dungeon Masters might prefer making the creatures summoned by a warlock with the *find steed* and *find greater steed* fiends instead of the other creature types listed in those spells. Additionally, the *find greater steed* spell can summon a felsteed in addition to the other creatures listed.

## Warlock Spell List
<div style='column-count:2'>

##### Cantrips (0 Level)
Acid Splash
<br> Blade Ward
<br> Chill Touch
<br> Create Bonfire ^XGE^
<br> ✦ Fel Flame
<br> Fire Bolt
<br> Green-Flame Blade ^SCAG^
<br> Mage Hand
<br> Produce Flame
<br> Sapping Sting ^EGW^
<br> ✦ Shadow Bolt
<br> Toll the Dead ^XGE^

##### 1st Level
Alarm
<br> Arms of Hadar
<br> Bane
<br> Cause Fear ^XGE^
<br> Chromatic Orb
<br> Comprehend Languages
<br> ✦ Demon Skin
<br> Detect Magic
<br> ✦ Drain Life
<br> Expeditious Retreat
<br> False Life
<br> Find Familiar
<br> Hellish Rebuke
<br> Hex
<br> Identify
<br> Illusory Script
<br> Jump
<br> Ray of Sickness

<br> Shield
<br> Sleep
<br> Tasha's Hideous Laughter
<br> Unseen Servant
<br> Witch Bolt

##### 2nd Level
Aganazzar's Scorcher ^XGE^
<br> Alter Self
<br> Arcane Lock
<br> Cloud of Daggers
<br> Continual Flame
<br> Crown of Madness
<br> Darkness
<br> Darkvision
<br> Dragon's Breath
<br> Enthrall
<br> † Find Steed
<br> Flame Blade
<br> Heat Metal
<br> Hold Person
<br> Invisibility
<br> Knock
<br> Levitate
<br> Locate Object
<br> Melf's Acid Arrow 
<br> Mind Spike ^XGE^
<br> Misty Step
<br> Phantasmal Force
<br> Pyrotechnics ^XGE^
<br> Ray of Enfeeblement
<br> Scorching Ray
<br> Shadow Blade ^XGE^

\columnbreak 

<div style='margin-top:17px;'></div>

<br> Spider Climb
<br> Suggestion
<br> Tasha's Mind Whip ^TCE^
<br> Web

##### 3rd Level
Bestow Curse
<br> Clairvoyance
<br> Counterspell
<br> Dispel Magic
<br> Elemental Weapon
<br> Enemies Abound ^XGE^
<br> Fear
<br> Fly
<br> Gaseous Form
<br> Haste
<br> Hunger of Hadar
<br> Hypnotic Pattern
<br> Life Transference ^XGE^
<br> Major Image
<br> Melf's Minute Meteors
<br> Phantom Steed
<br> Protection From Energy
<br> Remove Curse
<br> Sending
<br> Speak With Dead
<br> Summon Lesser <br>  Demons ^XGE^
<br> Tiny Servant ^XGE^
<br> Tongues
<br> Vampiric Touch
<br> Water Breathing
<br> Water Walk

##### 4th Level
Arcane Eye
<br> Banishment
<br> Blight
<br> Charm Monster ^XGE^
<br> Compulsion
<br> Death Ward
<br> ✦ Demonfire
<br> Evard's Black Tentacles
<br> † Find Greater Steed ^XGE^
<br> Greater Invisibility
<br> Hallucinatory Terrain
<br> Leomund's Secret Chest
<br> Locate Creature
<br> Mordenkainen's Faithful Hound
<br> Otiluke's Resilient Sphere
<br> Phantasmal Killer
<br> Shadow of Moil ^XGE^
<br> Sickening Radiance ^XGE^
<br> Summon Greater <br>  Demon ^XGE^
<br> Vitriolic Sphere ^XGE^

\columnbreak
##### 5th Level
Antilife Shell
<br> Danse Macabre ^XGE^
<br> Dispel Evil and Good
<br> Dominate Person
<br> Enervation ^XGE^
<br> Far Step ^XGE^
<br> Geas
<br> Hold Monster
<br> Immolation ^XGE^
<br> Insect Plague
<br> Modify Memory
<br> Negative Energy Flood ^XGE^
<br> ✦ Rain of Fire
<br> Rary's Telepathic Bond
<br> ✦ Ritual of Summoning
<br> Scrying
<br> Synaptic Static ^XGE^
<br> Teleportation Circle
<br> Wall of Force

##### 6th Level
Arcane Gate
<br> Circle of Death
<br> Contingency
<br> Create Undead
<br> Disintegrate
<br> Drawmij's Instant   Summons
<br> Eyebite
<br> Globe of Invulnerability
<br> Harm
<br> Investiture of Flame ^XGE^
<br> Magic Jar
<br> Mass Suggestion
<br> Mental Prison ^XGE^
<br> Otto's Irresistible Dance
<br> Planar Ally
<br> Scatter ^XGE^
<br> ✦ Shadowfury
<br> Soul Cage ^XGE^
<br> True Seeing
<br> Word of Recall

##### 7th Level
Delayed Blast Fireball
<br> Etherealness
<br> Finger of Death
<br> Fire Storm
<br> Forcecage
<br> Mordenkainen's Sword
<br> Sequester
<br> Teleport

</div>

<div class='footnote'>PART 2 | MAGIC</div>

\pagebreakNum
<div style='column-count:2'>

##### 8th Level
Abi-Dalzim's Horrid <br>  Wilting ^XGE^
<br> Antimagic Field
<br> ✦ Cataclysm
<br> Clone
<br> Demiplane
<br> Dominate Monster
<br> Feeblemind
<br> Glibness
<br> Maddening Darkness ^XGE^
<br> Reality Break ^EGW^
<br> Telepathy

##### 9th Level
Blade of Disaster ^IDRotF^
<br> Gate
<br> Imprisonment
<br> Meteor Swarm
<br> Psychic Scream ^XGE^
<br> Ravenous Void ^EGW^
<br> Weird

</div>

## Spell Descriptions

#### Cataclysm
**[Unchanged from the WHH version.]**
<br> *8th-level conjuration*
___
- **Casting Time:** 1 action
- **Range:** 150 feet
- **Components:** V, S, M (a piece of charcoal)
- **Duration:** Concentration, up to 10 minutes
___
The ground cracks as small fissures reveal molten magma beneath its surface in a 20-foot radius centered on a point within range. The fissures are harmless and too small to deal damage to any creature that moves over them.

While you are concentrating on the spell, you can use your action to rip open the fissured earth, bursting a torrent of flame 10-feet tall through the fissures. Once done, you can do so again and the spell lasts for its duration. When you rip open the ground, each creature in the area must make a Dexterity saving throw. A creature takes 10d8 fire damage on a failed save, or half as much damage on a successful one. A creature must also make this saving throw when it enters the spell's area for the first time on a turn or ends its turn there.

You can use a bonus action on your turn to end the spell, making the spells area natural difficult terrain.

#### Dark Void
**[Unchanged from the Priest version.]** <br>
*1st-level evocation*
___
- **Casting Time:** 1 action
- **Range:** 30 feet
- **Components:** V, S, M (a holy symbol)
- **Duration:** Instantaneous
___
You grasp the fabric around a target within range, pulling necromantic energies from it and creatures of your choice within 5 feet of it. A target must make a Constitution saving throw, taking 2d4 necrotic damage on a failed save, or half as much damage on a successful one.

***At Higher Levels.*** When you cast this spell using a spell slot of 2nd level or higher, the damage increases by 1d4 for each slot level above 1st

\columnbreak
#### Demon Skin
*1st-level transmutation*
___
- **Casting Time:** 1 action
- **Range:** Self
- **Components:** V, S, M (dried skin of a demon or fiend)
- **Duration:** 8 hours
___
Your skin becomes covered in a layer of fel energy, infusing you with fiendish vigor. Your minimum Armor Class becomes 8 + your spellcasting modifier. Your Armor Class cannot drop below 10 this way. Additionally, your current and maximum hit point totals increase by 1.

***At Higher Levels:*** When you cast this spell using a spell slot of 2nd level or higher, your minimum Armor Class and your current and maximum hit point totals increase by 1 for each slot level above 1st. 

#### Demonfire
**[Unchanged from the WHH version.]**
<br> *4th-level evocation*
___
- **Casting Time:** 1 action
- **Range:** 120 feet
- **Components:** V, S
- **Duration:** Instantaneous
___
You manifest five bolts of fel above your head, and direct to towards a creature you can see within range. The creature must make a Dexterity saving throw. On a failed save, the target takes 3d6 fire damage, or half as much on a success-ful one. The bolts all strike simultaneously, and you can direct them to hit one creature or several. A creature makes only one saving throw for all bolts striking it.

***At Higher Levels.*** When you cast this spell using a spell slot of 5th level or higher, the spell creates one more bolt for each spell level above 4th.

#### Diabolism
*Necromancy cantrip*
___
- **Casting Time:** 1 action
- **Range:** 5 feet
- **Componenets:** S
- **Duration:** 1 hour
___
This spell channels a small amount of dark energy. You create one of the following magical effects within range:
- Touch an object. Centering on that object, in a 20 foot radius, bright light becomes dim light, and dim light becomes darkness for 1 hour.
- An object you touch lightly decays. Wood rots, glass cracks, flowers wilt. This effect isn't strong enough to effect creatures, but it can effect the things they wear, such as causing a leather belt to rot and fall away.
- You can reanimate a Small or Tiny 0 CR creature for 1 hour. It is undead and obeys all of your commands to the best of it's abilities. You cannot use this effect again until the reanimated creature dies, or the effect ends.
- You instantaneously light a candle, torch, or small campfire.
- You make a glowing symbol or rune appear on an object or a surface for 1 hour.

If you cast this spell multiple times, you can have up to three of its non-instantaneous effects active at a time, and you can dismiss such an effect as an action.

<div class='footnote'>PART 2 | MAGIC</div>

\pagebreakNum
#### Drain Life
*1st-level necromancy*
___
- **Casting Time:** 1 Action
- **Range:** 30 feet
- **Components:** V, S
- **Duration:** Concentration, up to 1 minute
___
You cause a green stream of energy to trail from the target creature's eyes and mouth and into your hand, forming a continuous stream of energy to bind you two together.

Make a ranged spell attack against that creature. On a hit, the target takes 1d8 necrotic damage, and on each of your turns for the duration, you can use your action to deal 1d8 necrotic damage to the target automatically. Each time the target takes damage from this spell, you gain a number of hit points equal to half the damage dealt and their maximum hit point total is reduced by the same amount. This reduction lasts until they finish a long rest.

The spell ends if you use your action to do anything else. The spell also ends if the target is ever outside the spell’s range or if it has total cover from you. This spell has no effect on the creature if they are a construct or undead.

***At Higher Levels:*** When you cast this spell using a spell slot of 2nd level or higher, the initial damage increases by 1d8 for each slot level above 1st.

#### Fel Flame
**[Unchanged from the WHH version.]**
<br> *Evocation cantrip*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** Instantaneous
- ___
A green flame skitters across the ground towards a creature within range. Make a ranged spell attack against the target. On a hit, the target takes 1d8 fire damage. Fel flame ignores fire resistance, and creatures immune to fire damage are considered to be resistant.

This spell's damage increases by 1d8 when you reach 5th level (2d8), 11th level (3d8), and 17th level (4d8). 

#### Mind Flay
**[Unchanged from the Priest version.]** <br>
*2nd-level enchantment*
___
- **Casting Time:** 1 action
- **Range:** 120 feet
- **Components:** V
- **Duration:** Concentration, up to 1 minute
___
You wreathe the mind of a creature you can see within range. The target must make a Wisdom saving throw. On a failed save, the creature takes 2d6 psychic damage and has disadvantage on all attack rolls and ability checks for the spells duration, and on as successful save, the creature takes half damage but suffers no other effects of the spell.

At the end of each of its turns, the creature can make a Wisdom saving throw, ending the spell on a success.

***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, the damage increases by 1d6 for each slot level above 2nd.

\columnbreak
#### Rain of Fire
*5th-level evocation*
___
- **Casting Time:** 1 action
- **Range:** 120 feet
- **Components:** V, S
- **Duration:** Concentration, up to 1 minute
___
You summon a cloud at a point within range, causing flaming raindrops to blanket a 15-foot radius area around it. Each creature entering the area for the first time on their turn, or who starts their turn there, takes 3d12 points of fire damage or half on a successful Dexterity save. 
 
As a bonus action you can move the cloud up to 15 feet to a point you can see. Unattended flammable objects in the area are ignited. 

***At Higher Levels:*** When you cast this spell using a spell slot of 6th level or higher, it deals an additional 1d12 points of fire damage for each spell level above 5th.

#### Ritual of Summoning
**[Unchanged from the WHH version.]**
<br> *5th-level conjuration (ritual)*
___
- **Casting Time:** 10 minutes
- **Range:** 10 feet
- **Components:** V, S, M (a blood sapphire worth 100 gp)
- **Duration:** 1 hour
___
You call forth a summoning portal in an empty space within range. Appearing as a shadowy statue of a cloaked figure, holding open the cloak to reveal a gapping swirl into the twisting nether.

Using 1 minute, you can channel energy into the statue, and call forth the true name of a creature. If the creature is on your plane of existence, a shimmering mirror appears in front of it that only it can see, through the mirror the creature is able to perceive you and your surroundings, but you can not see it. 

A creature can choose to ignore the mirror, in which case it vanishes after 1 minute and a new mirror can't appear in front of that creature again for another 24 hours, or pass through it, in which case it is teleported to the space in front of the summoning stone. 

The ritual of summoning is only able to call creatures to it, a creature can't use the summoning stone to traverse back to their previous location.

#### Shadow Bolt
**[Range increased from the WHH version.]**
<br> *Necromancy cantrip*
___
- **Casting Time:** 1 action
- **Range:** 120 feet
- **Components:** V, S
- **Duration:** Instantaneous
___
A blast of necrotic energy at a creature within range. Make a ranged spell attack against the target. On a hit, the target takes 1d10 necrotic damage.

This spell's damage increases by 1d10 when you reach 5th level (2d10), 11th level (3d10), and 17th level (4d10).

<div class='footnote'>PART 2 | MAGIC</div>

\pagebreakNum
#### Shadowfury
**[Unchanged from the WHH version.]**
<br> *6th-level enchantment*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** Concentration, up to 1 minute
___
You extend your arm and draw crush energy down upon creatures within a 10-foot radius of a point within range. Each creature must succeed on a Wisdom saving throw, or be stunned for the duration of the spell. 

A stunned creature must make a Constitution saving throw at the end of each of its turns. On a successful save, this stunning effect ends.

<div class='footnote'>PART 2 | MAGIC</div>

\pagebreakNum

# Appendix C: Demonic minions

___
___
> ## Felguard Minion
>*Medium fiend (demon), lawful evil*
> ___
> - **Armor Class** 14 (natural armor)
> - **Hit Points** your Intelligence modifier plus the felguard's Constitution modifier plus five times your warlock level
> - **Speed** 30 feet 
>___
>|STR|DEX|CON|INT|WIS|CHA|
>|:---:|:---:|:---:|:---:|:---:|:---:|
>|16 (+3)|12 (+1)|14 (+2)|10 (+0)|12 (+1)|12 (+1)|
>___
> - **Saving Throws** Str + 5, Con + 4
> - **Skills** Athletics +5, Intimidation +3, Perception + 3
> - **Damage Resistance** bludgeoning, piercing, and slashing damage from nonmagical weapons  
> - **Senses** darkvision 60 feet, passive Perception 11
> - **Languages** Eredun, Common 
> ___
>
> ***Might of the Master.*** The following numbers increase by 1 when your proficiency bonus increases by 1: AC, the skill bonuses, and the bonus to its attack and damage rolls.
>
> ***Legion Strike.*** Once on each of its turns When the felguard make a Legion Axe attack, it can make another attack against a different creature that is within 5 feet of both the first creature and the felguard. 
>
> ### Actions
>
> ***Legion Axe.*** *Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 1d10 + 3 slashing damage.
> 
> ### Reactions
> ***Pursuit.*** When a creature attempts to move out of the felguard's weapon range, it can use its reaction to move up to its movement speed toward the creature and make a weapon attack. This movement doesn't provoke opportunity attacks. 
>
> \columnbreak
>
> #### Demonic Core
> The demonic core of a felguard is a heart that never seems to stop dripping blood. A warlock who carries it gains the following benefits:
>
> **2nd Level:** While carrying a felguard's core, the warlock has advantage on Strength (Athletics) and Wisdom (Survival) checks. While they hold the core, they can cast the *mage armor* spell at will.
>
> **5th Level:** While holding the core, the warlock knows the *magic weapon* spell and can cast it without expending a spell slot once per long rest.
>
> **9th Level:** While holding the core, the warlock knows the *bloodlust and heroism* spell and can cast it without expending a spell slot once per long rest.
> 
> #### Supremacy Evolution
> A felguard in service to a demonologist evolves into a fel lord at 14th level. Its skin turns gray and it increases in size, wielding a massively oversized axe. It gains the following benefits:
> - Its size increases to Large, causing its Legion Axe attack to deal an extra die of damage and have a range of 10 feet.
> - As an action it can slam its weapon into the ground, causing it to buckle. Treat this as though the felguard cast *earth tremor* as a 2nd level spell using your warlock spell save DC.
> - As an action, the felguard can make a single attack roll targeting any number of creatures within 10 feet. Roll damage for each creature that the attack roll would hit.

<img src='https://www.gmbinder.com/images/DCctq70.jpg' style='position:absolute; bottom:-200px; right:0px; width:800px' />
<img src='https://www.gmbinder.com/images/3e9S91s.png' style='position:absolute; top:-220px; right:0px; width:900px' />

<div class='footnote'>APPENDIX C | DEMON COMPANIONS</div>

\pagebreakNum
___
___
> ## Felhunter Minion
>*Medium fiend (demon), neutral evil*
> ___
> - **Armor Class** 13 (natural armor)
> - **Hit Points** your Intelligence modifier plus the felhunter's Constitution modifier plus five times your warlock level
> - **Speed** 40 feet 
>___
>|STR|DEX|CON|INT|WIS|CHA|
>|:---:|:---:|:---:|:---:|:---:|:---:|
>|17 (+3)|12 (+1)|14 (+2)|6 (-3)|13 (+1)|14 (+2)|
>___ 
> - **Saving Throws** Dex +3 , Con +4 
> - **Skills** Perception +3, Stealth +3, Survival +3
> - **Senses** blindsight 60 feet, passive Perception 13
> - **Languages** understand Eredun and the languages you know, but cannot speak 
> ___
>
> ***Might of the Master.*** The following numbers increase by 1 when your proficiency bonus increases by 1: AC, the skill bonuses, and the bonus to its attack and damage rolls.
>
> ***Disrupt Magic.*** If the felhunter damages a creature that then has to make a Constitution saving throw to maintain concentration on a spell, that saving throw is made with disadvantage.
>
> ***Magic Resistance.*** The felhunter has advantage on saving throws against spells and other magical effects.
>
> ***Sense Magic.*** The felhunter can sense magic within 60 feet of it at will. This trait otherwise work like the *detect magic* spell but isn't itself magical
>
> ### Actions
>
> ***Shadow Bite.*** *Melee Weapon Attack:* +5 to hit, range 5 ft., one target. *Hit:* 1d6 + 3 necrotic damage
>
> ***Maul.*** *Melee Weapon Attack:* +5 to hit, range 5 ft., one target. *Hit:* 1d8 + 3 piercing damage 
>
> \columnbreak
>
> #### Demonic Core
> The demonic core of a felhunter is a squirming tentacle. A warlock who carries it gains the following benefits:
>
> **2nd Level:** While carrying a felhunter's core, the warlock has advantage on Intelligence (Investigation) and Wisdom (Perception) checks. While they hold the core, they can cast the *detect magic* spell at will.
>
> **5th Level:** While holding the core, the warlock knows the *counterspell* spell and can cast it without expending a spell slot once per long rest.
>
> **9th Level:** While holding the core, the warlock knows the *locate creature* spell and can cast it without expending a spell slot once per long rest.
> 
> #### Supremacy Evolution
> A felhunter in service to a demonologist evolves into a felstalker at 14th level. Its skin turns red and its outline seems to flicker in and out of reality. It gains the following benefits:
> - It can take the Dash action as a bonus action.
> - When it successfully saves against a spell, it regains hit points equal to twice the spell's level.
> - Its body shifts in and out of reality, causing attack rolls against it to have disadvantage. If it is hit by an attack, this trait is disrupted until the end of its next turn. This trait is also disrupted while the felhunter is incapacitated or has a speed of 0.

<img src='https://www.gmbinder.com/images/moaDsD1.jpg' style='position:absolute; bottom:-80px; left:0px; width:800px' />
<img src='https://www.gmbinder.com/images/bNHsRrG.png' style='position:absolute; bottom:0px; left:0px; width:900px;' />

<div class='footnote'>APPENDIX C | DEMON COMPANIONS</div>

\pagebreakNum
___
___
> ## Imp Minion
>*Small fiend (demon), chaotic evil*
> ___
> - **Armor Class** 13
> - **Hit Points** your Intelligence modifier plus the imp's Constitution modifier plus five times your warlock level
> - **Speed** 25 feet 
>___
>|STR|DEX|CON|INT|WIS|CHA|
>|:---:|:---:|:---:|:---:|:---:|:---:|
>|6 (-2)|16 (+3)|13 (+1)|16 (+3) |8 (-1)|14 (+2)|
>___
> - **Saving Throws** Dex +5, Wis +1
> - **Skills** Deception +4, Sleight of Hand +5, Stealth +5
> - **Senses** darkvision 60 feet, passive Perception 11
> - **Languages** Eredun, Common 
> ___
>
> ***Might of the Master.*** The following numbers increase by 1 when your proficiency bonus increases by 1: AC, the skill bonuses, and the bonus to its attack and damage rolls.
>
> ### Actions
>
> ***Claw.*** *Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 1d4 + 3 slashing damage.
>
> ***Fire Bolt.*** *Ranged Spell Attack:* +4 to hit, range 60 ft., one target. *Hit:* 1d8 + 3 fire damage
>
> ***Etherealness.*** The imp magically enters the Ethereal Plane from The Material Plane, or vice versa. The imp can also bring you with it to the Ethereal Plane, but must be within 5 feet of you to do so. 
>
> \columnbreak
>
> #### Demonic Core
> The demonic core of an imp resembles a broken piece of horn, hot to the touch. A warlock who carries the demonic core of an imp gains the following benefits:
> 
> **2nd Level:** While carrying an imp's core, the warlock has advantage on Dexterity (Sleight of Hand) and Dexterity (Stealth) checks. While they hold the core, they can cast the *vicious mockery* cantrip.
> 
> **5th Level:** While holding the core, the warlock knows the *blink* spell and can cast it without expending a warlock spell slot once per long rest.
>
> **9th Level:** While holding the core, the warlock knows the *rain of fire* spell and can cast it without expending a warlock spell slot once per long rest.
>
> #### Demonic Empowerment
> An imp in service to a demonologist evolves into a fel imp at 14th level. The imp increases in size, gaining massive horns and a pair of wings. It gains the following benefits:
> - It has a fly speed of 25 feet.
> - When it makes a Fire Bolt attack, it attacks three times.
> - Up to three times per day, a target hit by its Fire Bolt is affected by *dispel magic*.

<img src='https://www.gmbinder.com/images/z08oeTn.jpg' style='position:absolute; bottom:-100px; left:0px; width:800px' />
<img src='https://www.gmbinder.com/images/wvTUmvu.png' style='position:absolute; bottom:-20px; left:0px; width:800px' />

<div class='footnote'>APPENDIX C | DEMON COMPANIONS</div>

\pagebreakNum
___
___
> ## Succubus Minion
>*Medium fiend (demon), chaotic evil*
> ___
> - **Armor Class** 13
> - **Hit Points** your Intelligence modifier plus the succubus's Constitution modifier plus five times your warlock level
> - **Speed** 30 feet, fly 15 feet
>___
>|STR|DEX|CON|INT|WIS|CHA|
>|:---:|:---:|:---:|:---:|:---:|:---:|
>|8 (-1)|16 (+3)|13 (+1)|10 (+0)|12 (+1)|16 (+3)|
>___
> - **Saving Throws** Cha + 5, Wis + 3 
> - **Skills** Deception +5, Persuasion +5, Stealth +5
> - **Senses** darkvision 60 feet, passive Perception 11
> - **Languages** Eredun, Common, Orcish telepathy 60 feet 
> ___
>
> ***Might of the Master.*** The following numbers increase by 1 when your proficiency bonus increases by 1: AC, the skill bonuses, and the bonus to its attack and damage rolls.
>
> ***Shapechanger.*** The succubus can use its action to polymorph into a Small or Medium humanoid, or back into its true form. Other than its size and speed, its statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies.
>
> ***Whip Master.*** When the succubus hits a creature with its Lash of Pain, the target can be moved up to 10 feet closer to or away from the succubus.
>
> ### Actions
>
> ***Lash of Pain.*** *Melee Weapon Attack:* +5 to hit, reach 10 ft., one target. *Hit:* 1d6 + 3 necrotic damage, and a creature must succeed on a Constitution saving throw versus its master's spell DC, or have its movement speed reducd by 10 feet till the start of the succubus' next turn.
>
> ***Invisibility.*** The succubus magically turns invisible until it attacks, or until its concentration ends (as if concentrating on a spell). Any equipment the succubus wears or carries is invisible with it.
>
> \columnbreak
> 
> #### Demonic Core
> The demonic core of a succubus resembles...a tube of lipstick? A warlock who carries the demonic core of a succubus gains the following benefits:
> 
> **2nd Level:** While carrying a succubus's core, the warlock has advantage on Charisma (Deception) and Charisma (Persuasion) checks. While they hold the core, they can cast the *charm person* spell at will.
> 
> **5th Level:** While holding the core, the warlock knows the *suggestion* spell and can cast it without expending a warlock spell slot once per long rest.
>
> **9th Level:** While holding the core, the warlock knows the *dominate person* spell and can cast it without expending a warlock spell slot once per long rest.
>
> #### Demonic Empowerment
> A succubus in service to a demonologist evolves into a fel succubus at 14th level. The succubus's skin turns red, its horns become more pronounced, and its eyes take on a green glow. It gains the following benefits:
> - When it makes a Lash of Pain attack, it can hit up to two targets.
> - The range on its Lash of Pain increases to 20 feet.
> - As an action, it can seduce a humanoid within 60 feet. If the target fails its Charisma save against your spell save DC, it is incapacitated for 1 minute. It can repeat its save at the beginning of its turn or when it takes damage, ending the effect on a success. While a creature is seduced, the succubus cannot seduce another creature.

<img src='https://www.gmbinder.com/images/lc9zJNs.jpg' style='position:absolute; bottom:-250px; left:0px; width:800px' />
<img src='https://www.gmbinder.com/images/3e9S91s.png' style='position:absolute; top:-130px; left:0px; width:800px' />

<div class='footnote'>APPENDIX C | DEMON COMPANIONS</div>

\pagebreak
___
___
> ## Voidwalker Minion
>*Medium fiend (demon), neutral evil*
> ___
> - **Armor Class** 16 (natural armor)
> - **Hit Points** your Intelligence modifier plus the voidwalker's Constitution modifier plus five times your warlock level
> - **Speed** 30 feet 
>___
>|STR|DEX|CON|INT|WIS|CHA|
>|:---:|:---:|:---:|:---:|:---:|:---:|
>|16 (+3)|8 (-1)|16 (+3)|8 (-1)|14 (+2)|10 (+0)|
>___
> - **Saving Throws** Dex +1, Wis +4
> - **Skills** Athletics +5, Intimidation +2, Perception +4
> - **Damage Vulnerabilities** radiant 
> - **Damage Resistances** bludgeoning, piercing, and slashing damage from nonmagical weapons 
> - **Condition Immunity** exhausted, grappled
> - **Senses** darkvision 60 feet, passive Perception 14
> - **Languages** understands Eredun, Common and Orcish but can't speak, telepathy 60 feet. 
> ___
>
> ***Might of the Master.*** The following numbers increase by 1 when your proficiency bonus increases by 1: AC, skill bonuses, and the bonus to its attack and damage rolls.
>
> ***Threatening Presence.*** Any creature damaged by the voidwalker has disadvantage on any attack roll it makes on a target other than the voidwalker, until the end of the voidwalker's next turn.
>
> ### Actions
>
>  ***Slam.*** *Melee Weapon Attack:* +5 to hit, reach 10 ft., one target. *Hit:* 1d6 + 3 bludgeoning damage.
>
> ***Suffering.*** *Melee Weapon Attack:* +5 to hit, reach 10 ft., one target. *Hit:* 1d6 + 3 necrotic damage.
>
> ***Shadow Bulwark (1/day).*** the voidwalker gains a number of temporary hit points equal to its master's level. 
>
> \columnbreak
> 
> #### Demonic Core
> The demonic core of a voidwalker resembles an orb of pure shadow. A warlock who carries the demonic core of a voidwalker gains the following benefits:
> 
> **2nd Level:** While carrying a voidwalker's core, the warlock has advantage on Wisdom (Insight) and Charisma (Intimidation) checks. While they hold the core, they can cast the *armor of agathys* spell at will.
> 
> **5th Level:** While holding the core, the warlock knows the *hunger of hadar* spell and can cast it without expending a warlock spell slot once per long rest.
>
> **9th Level:** While holding the core, the warlock knows the *enervation* spell and can cast it without expending a warlock spell slot once per long rest.
>
> #### Demonic Empowerment
> A voidwalker in service to a demonologist evolves into a voidlord at 14th level. The voidwalker's body becomes darker and takes on a blue sheen and it sprouts black armor plating. It gains the following benefits:
> - It gains a +1 bonus to armor class.
> - Creatures that hit the voidwalker with a melee attack take 5 (1d10) necrotic damage.
> - As an action, the voidwalker can instill fear of the void in each creature of your choice that is within 60 feet of the voidwalker and aware of it. Creatures must succeed on a Wisdom saving throw against your spell save DC or become frightened for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the voidwalker's fear effect for the next 24 hours.

<img src='https://www.gmbinder.com/images/dPcFWbx.jpg' style='position:absolute; bottom:-150px; left:0px; width:800px' />
<img src='https://www.gmbinder.com/images/L60ii4e.png' style='position:absolute; top:-0px; left:0px; width:800px' />


<div class='footnote'>APPENDIX C | DEMON COMPANIONS</div>

\pagebreakNum

# Appendix F: Summoned Creatures
___
> ## Doomguard <!-- https://wc5e-cr-calculator.frogvall.com/?1;16;85;6;17;42;0;0;0;0;0;0;0;0;0;0;0;1;;1;;3;;;;;;;1;;;1;;;;;;;;10;;;;;; --> 
> *Large fiend (demon), chaotic evil*
> ___
> - **Armor Class** 16 (breastplate)
> - **Hit Points** 85 (9d10 + 36)
> - **Speed** 30 ft., fly 50 ft.
> ___
>|  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
>|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
>|17 (+3)|15 (+2)|19 (+4)|13 (+1)|15 (+2)|22 (+6)|
>___
> - **Skills** Deception +9, Intimidation +9
> - **Damage Resistances** bludgeoning, piercing, and slashing from nonmagical weapons
> - **Damage Immunities** fire, poison
> - **Condition Immunities** poisoned
> - **Senses** darkvision 60 ft., passive Perception 12
> - **Languages** Eredun, Common
> - **Challenge** 7 (2,900 XP)
> ___
> ***Pain Master.*** When the doomguard hits a creature with its whip attack for the first time in a round, the creature must make a DC 14 Constitution saving throw or be struck with crippling pain until the beginning of its next turn. 
<br>    Its speed is reduced to 10 feet and it has disadvantage on attack rolls. If it attempts to cast a spell, it must make a DC 14 Constitution saving throw or the casting fails and the spell is wasted.
>
> ### Actions
> ***Multiattack.*** The doomguard uses Frightful Presence. It then makes two attacks, either with its whip or its doom bolt.
>
> ***Whip.*** *Melee Weapon Attack:* +6 to hit, reach 15 ft., one target. *Hit:* 8 (2d4 + 3) slashing damage plus 13 (3d8) psychic damage. 
> 
> ***Doom Bolt.*** *Ranged Spell Attack:* +9 to hit, range 120 ft., one target. *Hit:* 18 (4d8) necrotic damage.
> 
> ***Frightful Presence.*** Each creature of the doomguard's choice that is within 120 feet of the demon and aware of it must succeed on a DC 17 Wisdom saving throw or become frightened for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the doomguard's Frightful Presence for the next 24 hours.

\columnbreak
___
> ## Infernal <!-- https://wc5e-cr-calculator.frogvall.com/?1;17;73;7;15;34;11;34;11;34;21;0;0;0;0;0;0;1;1;;;3;;;;;;;;;;1;;;;;;;;10;;;;;; -->
> *Large construct, chaotic evil*
> ___
> - **Armor Class** 17 (natural armor)
> - **Hit Points** 73 (7d10 + 35)
> - **Speed** 30 ft.
> ___
>|  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
>|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
>|20 (+5)| 8 (-1)|20 (+5)|12 (+1)|14 (+2)|11 (+0)|
> ___
> - **Damage Resistances** bludgeoning, piercing, and slashing from nonmagical weapons that aren't adamantine
> - **Damage Immunities** fire, poison, psychic
> - **Condition Immunities** charmed, exhaustion, frightened, paralyzed, petrified, poisoned
> - **Senses** darkvision 120 ft., passive Perception 12
> - **Languages** understands Eredun but can't speak
> - **Challenge** 7 (2,900 XP)
> ___
> ***Death Throes.*** When the infernal dies, it explodes, and each creature within 30 feet of it must make a DC 15 Dexterity saving throw, taking 10 (3d6) fire damage on a failed save, or half as much damage on a successful one. The explosion ignites flammable objects in that area that aren't being worn or carried. 
> 
> ***Fire Aura.*** At the start of each of the infernal's turns, each creature within 5 feet of it takes 3 (1d6) fire damage, and flammable objects in the aura that aren't being worn or carried ignite. A creature that touches the infernal or hits it with a melee attack while within 5 feet of it takes 3 (1d6) fire damage.
> 
> ***Illumination.***  The infernal sheds bright light in a 30-foot radius and dim light in an additional 30 feet.
>
> ***Immutable Form.*** The infernal is immune to any spell or effect that would alter its form.
> 
> ***Siege Monster.*** The infernal deals double damage to objects and structures.
> 
> ### Actions
> ***Multiattack.*** The infernal makes two slam attacks.
> 
> ***Slam.*** *Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 14 (2d8 + 5) bludgeoning damage plus 3 (1d6) fire. If the target is a creature or a flammable object, it ignites. Until a creature takes an action to douse the fire, the target takes 5 (1d10) fire damage at the start of each of its turns.

<div class='footnote'>APPENDIX F | SUMMONED CREATURES</div>

\pagebreakNum
## Changelog
<!-- 
#### V 0.1.0 (Aug. 15, 2020)
- Initial release.

#### V 0.2.0 (Sept. 10, 2020)
- Changed the *find familiar* spell provided in Profane Knowledge to be simply known and able to cast without expending a spell slot. Essentially the same thing, now it just takes the normal 10 minutes instead of an additional 10 due to being a ritual, while also qualifying it for Soulburn: Quicken. Also removed the material component requirement.
- Life Tap's second use was moved to 7th level to even out progression of the table.
- How many soul shards you have and how they are generated were reworked. Now you get a flat amount of 3, you can generate them over SRs and LRs as well as from creatures, and the onus of who generates them was placed on DMs rather than rulings.
- Renamed the Soul Shard abilities [Extend], [Quicken], and [Ritual] to Soulburn: Extend, Soulburn: Quicken, and Soul Rites. 
- The Soulburn: Rebound ability was added.
- The Enslave Demon soul stone ability was removed, to be added the Demonology subclass.
- A different outline was made for Demon Companion. Not much was added, just better reading and some clarifications.
- Created a new ability at 5th level: Soulforging. Add this to the Warlock table. The former soul shard abilities Create Firestone, Create Healthstone, Create Soulstone, and Create Spellstone were moved to this section. Each now has a max amount limitation. More work is needed on these, what with the updated soul shard method.
- A placeholder ability was added to level 9, to ensure that the table is neater. 
- Updated Nethermancy with an actual description. Now it is essentially a set of recharge on LR, higher level spell slots. This provides the class with some flexibility.
- Scrapped the old subclasses. Affliction was too much about damage and not enough about curses, Demonology was unfinished anyway, and Destruction was too focused on the burning embers mechanic. Additionally, I forgot that the study-provided spells weren't automatically known, just added to the warlock spell list, so those had to be redone. A rough outline for ideas on the updated subclasses was added.
- Some spells and all demon creatures were hidden, to be worked on later.

#### V 0.2.1 (Sept. 11, 2020)
- Soulforging was changed to be 1 of any type of stone at a time. Firestone, Soulstone, and Spellstone were changed to be more powerful and hopefully competitive.
- The *find familiar* spell was removed from Profane Knowledge. It is now a generic ritual that summons and binds fiends of CR 1/8 or below.
- Demon Companions was updated with actual mechanics.
- Corruption was added as an ability at level 9.
- The nebulous [Capstone] ability was removed, in favor of being able to use Life Tap at will.
- Find Steed and Find Greater Steed were removed from the warlock spell list, as they clash with the Demon Companions mechanic.

\columnbreak
#### V 0.3.0 (Sept. 13, 2020)
- First draft of the subclasses. 
- The chaos blast spell was added. [Credit.](https://www.dndbeyond.com/spells/280893-chaos-blast)
- The Demons section was added, to give an idea for what can be possible with Demon Summoning and whatnot.

#### V 0.3.1 (Sept. 13, 2020)
- Clarified that Potent Affliction's effects only last one round before the secondary effect triggers.
- Added missing 1/SR usage restriction on Hand of Gul'dan.
- Havoc is now a soul shard ability.
- Added some demons: Aranasi Spiderling, Bilescourge (and larva), Darkhound (from the MM), Doomguard, Dreadsteed, Eye of the Legion, Felbat Pup, Felsteed, Infernal, and Swarm of Felbat Pups.

#### V 0.3.2 (Sept. 13, 2020)
- Changed Shadow Magic to Fel Sorcery.
- Reduced demon summoning's ritual cast time from 1 hour to 10 minutes.
- Demon Summoning now reduces your total number of soul shards you can use, as well as costing some.
- Corruption was removed. Malediction was renamed Corruption.
- Harvest Life was removed, replaced with Unstable Afflictions.
- Curse of Doom now triggers after six turns, rather than scaling along with the number of turns.
- Seed of Corruption now triggers only on the creature's turn. It has a wider area of effect, but can affect less targets, deals less damage, and can be ended early with two saves.
- Metamorphosis was changed to We Are Legion. Now it's a permanent transformation instead of a temporary shadowform.
- Decimation was renamed to Flames of Xoroth, deals fire damage, and gets one free use.
- The initial damage of Inferno was changed, and the explosion's damage now has a saving throw.
- Marked the spells that are located in other books as such, as well as added a table referencing where they are.
- Added some art.

#### V 0.3.3 (Sept. 14, 2020)
- Channel Demonfire got a "1st spell level or higher" restriction.
- Reverse Entropy was renamed Unending Resolve.
- Flames of Xoroth now deals damage at the end of current turn, to allow Unending Resolve to trigger before Flames of Xoroth does.

#### V 0.3.4 (Oct. 15, 2020)
- Demon Companion was renamed to Dark Pact, to avoid naming confusion.
- The relevant portions of the *find familiar* spell were reprinted into a sidebar to clarify the demon companion's abilities and to avoid having to look in multiple places for rulings.
- Curse of Shadows had its save to end the curse effect moved from the amplified version of the curse to the normal version.
- Soul Link's damage resistance was redone so that the warlock uses their reaction, not the demon.

\pagebreakNum

#### V 0.4.0 (Oct. 23, 2020)
- Added some art.
- Removed the "seeing through familiar's senses" and "deliver touch spells" portions of Demon Companion. 
- Demon Companions now follow your initiative count.
- The demon companion ritual is given a proper name: Ritual of Binding.
- Soul shards now require a reaction to obtain.
- Removed Soulburn: Extend and Quicken.
- Using Dark Pact no longer costs soul shards, but can only be done at the end of a long rest.
- Attempted to clean up language of Nethermancy. A little bit, at least.
- Unstable Affliction now deals half your warlock level in damage, for both spells and abilities.
- Channel Demonfire no longer deals irresistable fire damage. It can now only affect a single target.
- Clarified that Havoc only works with Fel Sorcery spells. Also ended the Havoc + Flames of Xoroth combo.
- Clarified that Soul Link increases max hit points. Also added in a bonus to Armor Class.
- Enslave Demon is now mutually exclusive with Demon Companions.

#### V 0.4.1 (Oct. 26, 2020)
- Starting equipment's weapon is now any simple weapon.
- Brought back the number of spell slots progression from the 2.1 warlock.
- Some changes to how demons are handled via the Ritual of Binding. Now it is closer to how the 2.1 warlock could summon demons.
- Added Soulburn: Sorcery.
- Altered Soul Rites. Same effect, different calculation.
- Changed Affliction's bane bonus spell to dark void.
- Added Haunt.
- Curse Master now provides bestow curse and remove curse, instead of bestow curse and hex.
- Reworked demonology, adding Unbound Will, Eyes of Kilrogg, and Fell Guard.
- Removed the Destruction-only chaos damage spells, replacing them with fireball and destructive wave.
- Added Pyrophile. 
- Renamed Flames of Xoroth to Flames of Xerrath, after the green-fire codex.
- Removed Eldritch Blast cantrip.
- Removed the Puppet spell, as it was UA.
- Added Find Steed and Find Greater Steed back to spell list. They always summon fiends and Find Greater Steed can summon felsteeds.
- Added Delayed Blast Fireball.
- Added in demonic minions
- Removed Demons, other than those summoned by class abilities.

\columnbreak
#### V 0.4.2 (Oct. 29, 2020)
- Reworked the Demons. Now separated into demonic minions and demonic cores. They use the ability names Grimoire of Sacrifice and Grimoire of Service.
- Removed the Soulburn: Sorcery ability.
- Demonology has been heavily redone. 
- Demons added. 

##### Added Spells:
- Cantrips: Acid Splash, Produce Flame, Sapping Sting
- 1st Level: Alarm, Bane, Chromatic Orb, Detect Magic, Dissonant Whispers, Find Familiar, Identify, Jump, Shield, Sleep
- 2nd Level: Aganazzar's Scorcher, Alter Self, Arcane Lock, Continual Flame, Darkvision, Dragon's Breath, Flame Blade, Flaming Sphere, Heat Metal, Knock, Levitate, Locate Object, Melf's Acid Arrow, Pyrotechnics, Spider Climb, Suggestion, Tasha's Mind Whip, Web
- 3rd Level: Animate Dead, Elemental Weapon, Gaseous Form, Haste, Life Transference, Protection From Energy, Sending, Speak With Dead, Stinking Cloud, Water Walk
- 4th Level: Blight, Compulsion, Confusion, Death Ward, Dimension Door, Dominate Beast, Fire Shield, Greater Invisibility, Leomund's Secret Chest, Locate Creature, Mordenkainen's Faithful Hound, Otiluke's Resilient Sphere, Phantasmal Killer, Vitriolic Sphere, Wall of Fire
- 5th Level: Antilife Shell, Contagion, Dispel Evil and Good, Geas, Insect Plague, Modify Memory, Rary's Telepathic Bond, Teleportation Circle, Wall of Force
- 6th Level: Disintigrate, Globe of Invulnerability, Harm, Investiture of Flame, Magic Jar, Mass Suggestion, Planar Ally, Word of Recall
- 7th Level: Forcecage, Mordenkainen's Sword, Teleport
- 8th Level: Antimagic Field, Clone, Reality Break, Telepathy
- 9th Level: Blade of Disaster, Ravenous Void -->

### Class Features 
- Armour proficiency removed, weapon proficiencies reduced
- Starting equipment has been changed accordingly
- New feature Profane Knowledge at 1st level
- Shadow Magic has been renamed to Fel Sorcery. Functionally it acts the same, but ritual casting has been added. 
- The number of cantrips has reduced from 5 to 4, aligning with the PHB warlock, druid, and bard
- Life Tap now starts at 1st level. It no longer reduces maximum hit points, but instead deals unresisted damage with a limited number of uses.
- Fel Study choice delayed to 2nd level.
- Shadow Embrace has been removed, and split into Demonic Knowledge and Soul Shards. 
- Demonic Knowledge allows you to build a growing number of known demon types. It is split into two parts; Grimoire of Service and Grimoire of Sacrifice, the former for summoning demons and the latter for draining their powers instead. 
- Soul Shards function similar, but the number of ways they can be used has been increased.
- New feature Soulforging at 5th level, adding more ways to use soul shards. 
- Fel Arcanum has been renamed to Nethermancy. Instead of adding a 1/LR spell of 6th - 9th level, the warlock gains one spell known from each level and one LR spell slot of each level. These spell slots can be used to cast any spell the warlock knows.

### Subclasses
- Subclasses have been completely redesigned. 
- Expanded spell lists have been rearranged.

### Affliction
- 2st level: Curse of Agony has been changed to Corruption, which lets the warlock cast Banes with different effects. 
- 2nd level: New feature Haunt. 
- 6th level: Nether Ward has been replaced with Curse Master. 
- 10th level: Unstable Affliction has been folded into Corruption, and replaced with Drain Soul. 
- 14th level: Seed of Corruption has been replaced with Unstable Afflictions. 
- 18th level: New feature Potent Affliction. It is split into two parts; Curse of Doom and Seed of Corruption.

### Demonology
- 2nd level: Fiendish Influence has been replaced with Soul Conduit, which empowers demons from Demonic Knowledge.
- 2nd level: New feature Sense Demons.
- 6th level: Wild Imps has been replaced with Soul Link. 
- 10th level: Demonic Resilience has been replaced with Demonic Fury. 
- 14th level: Mark of Service has been replaced with Grimoire of Supremacy. 
- 18th level: New feature We are Legion.

\columnbreak
### Destruction 
- 2nd level: Ignite has been stepped up and renamed Pyrophile. 
- 2nd level: New feature Channel Demonfire.
- 6th level: Havoc has changed its resource mechanics, but is otherwise largely the same. 
- 10th level: Soul Fire has been replaced with Unending Resolve. 
- 14th level: Chaos Bolt has been replaced with Flames of Xerrath. 
- 18th level: New feature Inferno. It's time to crash down some infernals.

### New and Changed Spells
- Demon Skin has been reworked and is now a 1st level spell to fill the class' Mage Armor niche.
- Shadow Bolt now has a longer range.
- Diabolism added to the list, credited from [DDB.](https://www.dndbeyond.com/spells/141243-diabolism)
- Drain Life is now a spell. 
- Rain of Fire is now a spell.

### Removed Spells
- Eldritch Blast (Shadow Bolt takes its place)
- Puppet (UA spell)
- Power Word Pain
- Power Word Kill
- Soulwell

### Added Spells 
- Cantrips: Acid Splash, Produce Flame, Sapping Sting
- 1st Level: Alarm, Bane, Chromatic Orb, Detect Magic, Dissonant Whispers, Find Familiar, Identify, Jump, Shield, Sleep
- 2nd Level: Aganazzar's Scorcher, Alter Self, Arcane Lock, Continual Flame, Darkvision, Dragon's Breath, Flame Blade, Flaming Sphere, Heat Metal, Knock, Levitate, Locate Object, Melf's Acid Arrow, Pyrotechnics, Spider Climb, Suggestion, Tasha's Mind Whip, Web
- 3rd Level: Animate Dead, Elemental Weapon, Gaseous Form, Haste, Life Transference, Protection From Energy, Sending, Speak With Dead, Stinking Cloud, Water Walk
- 4th Level: Blight, Compulsion, Confusion, Death Ward, Dimension Door, Dominate Beast, Fire Shield, Greater Invisibility, Leomund's Secret Chest, Locate Creature, Mordenkainen's Faithful Hound, Otiluke's Resilient Sphere, Phantasmal Killer, Vitriolic Sphere, Wall of Fire
- 5th Level: Antilife Shell, Contagion, Dispel Evil and Good, Geas, Insect Plague, Modify Memory, Rary's Telepathic Bond, Teleportation Circle, Wall of Force
- 6th Level: Disintigrate, Globe of Invulnerability, Harm, Investiture of Flame, Magic Jar, Mass Suggestion, Planar Ally, Word of Recall
- 7th Level: Forcecage, Mordenkainen's Sword, Teleport
- 8th Level: Antimagic Field, Clone, Reality Break, Telepathy
- 9th Level: Blade of Disaster, Ravenous Void

\pagebreakNum
### Appendix: Demon Companions
- Demon companions / minions have been rewritten, and now follow the same Might of the Master structure as companions in other classes do. 
- Many features have been changed. 
- The Felguard has been added. 
- All statblocks also have a Demonic Core (for Grimoire of Sacrifice) and a Supremacy Evolution (for Grimoire of Supremacy). 
