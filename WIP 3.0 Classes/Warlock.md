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

<div style='margin-top:500px'></div>

<div style='margin-top:500px'></div>

## Warlock
*Imagine what you could do if you led a group of shaman who controlled the source of their powers, instead of begging and scraping for it. Imagine if these shaman had servants who could also fight on your side. Servants who could send your enemies fleeing helplessly in terror. Suck their magic dry as the insects in the summer suck blood.*
<div style="text-align:Right"> 

<div style='margin-top:-4px;'></div>

*— Gul'dan*  </div>

<div style='margin-top:0px;'></div>

An imp skitters behind her as a young human clad in robes smiles warmly, weaving magical charms into her honeyed words, bending the palace sentinels to her will.

A brutish orc waves his hand in the air, sparking flames of green and red, with a flash of his hand, he hurls a ball of fel infused fire against a night elf.

Shifting his gaze between a battered tome and the rough drawn glyphs made in the dirt. A wild eyed forsaken begins a slow chant, as a demonic gate erupts from the ground.

Warlocks and seekers of the knowledge that lies hidden in the fabric of the multiverse. Through their powerful fel magic and secret grimoires, warlocks delve deep into forbidden magic both subtle and spectacular.

### Dark Arts, Dominance
In the face of demonic powers, most adventurers see death and destruction. Warlocks see opportunity, dominance, and a clear power to it through their dark sorcery. They are voracious spellcasters who enslave demons into doing their bidding. Some hide away in plain sight, presenting as forward-thinking arcanists while secretly dabbling in dark practices. Others practice their arts openly, in sects that quickly grow notorious both far and wide.

\columnbreak

<div style='margin-top:363px'></div>

### Wielders of Fel
Warlocks are the wielders of the destructive fel, a form of magic most associated with demons and the Burning Legion. It is well known for being entropic and extremely chaotic, leading its practice to have been banned in most societies and for its practitioners to work in secrecy. 

Whilst other forms of magic have a natural source, from the wielder or granted to the wielder, fel magic is a bargain. It corrupts the minds of those involved and desecrates the land around them. If their subdued demons were not enough to frighten the common folk, the fear for what these powers can bring would certainly do the trick.

### Delvers of Secrets
Though warlocks are not innately evil, often pledging them&shy;selves to noble causes, their desire to understand these dark powers and hold command over demonic forces does breed mistrust among even their closest allies. 

Warlocks peer into the Void without hesitation, leverag&shy;ing the chaos they glimpse within to devastating ends in battle—some of their abilities are even fueled by the souls they’ve harvested from their victims. 

They exploit powerful shadow and fel magic to manipu-late and degrade the minds and bodies of their enemies. They employ hellish fires to rain from the skies, immolating their opponents, summoning and commanding indomitable demons from the Twisting Nether to wreak havoc.

### Creating a Warlock
As you create your warlock, think about how and why you decided to delve into the secrets of fel sorcery, one of the greatest and most volatile powers known among mortals. What made you see potential where others would only see death? Were you seduced by the powers promised? Was a deal struck with a demon, or a denizen of the void? 

Perhaps you are part of a sect to whom fel and shadow are but the means to an end, or perhaps a taste was all it took to hurl you into a magical addiction that you are now fighting to overcome. How your dark studies came to be is for you to decide.

<div class='footnote'>PART 1 | CLASSES</div>
<img src='https://www.gmbinder.com/images/dvMcsXD.jpg' style='position:absolute; top:-0px; right:-100px; width:1100px;transform:scalex(-1)' />
<img src='https://www.gmbinder.com/images/vn90cy3.png' style='position:absolute; top:-10px; right:0px; width:800px; transform:scaleX(-1);' />
<img src='https://www.gmbinder.com/images/nZZkz5p.png' style='position:absolute; bottom:0px; right:0px; width:800px;' />
<img src='https://www.gmbinder.com/images/kWRapfL.png' style='position:absolute; top:24px; right:260px; width:550px;transform:scalex(-1)' />

\pagebreakNum

<div class="classTable wide" />

##### Warlock

Level   |Proficiency<br/>Bonus|Features          |Cantrips<br/>Known|Spells<br/>Known|Spell<br/>Slots|Slot<br/>Level
--------|:-:|---------------------------------------------------|:-:|:-----:|:-:|:-----:|:--:|
1st     |+2 |Profane Secrets, Fel Sorcery, Life Tap             |4  |2      |1  |1st
2nd     |+2 |Fel Study, Soul Shards                             |4  |3      |2  |1st
3rd     |+2 |Demonic Minion                                     |4  |4      |2  |2nd
4th     |+2 |Ability Score Improvement                          |5  |5      |2  |2nd
5th     |+3 |—                                                  |5  |6      |2  |3rd
6th     |+3 |Fel Study Feature                                  |5  |7      |2  |3rd
7th     |+3 |—                                                  |5  |8      |2  |4th
8th     |+3 |Ability Score Improvement                          |5  |9      |2  |4th
9th     |+4 |—                                                  |5  |10     |2  |5th
10th    |+4 |Fel Study Feature                                  |6  |10     |2  |5th
11th    |+4 |Nethermancy (6th Level)                            |6  |11+1   |3  |5th
12th    |+4 |Ability Score Improvement                          |6  |11+1   |3  |5th
13th    |+5 |Nethermancy (7th Level)                            |6  |12+2   |3  |5th
14th    |+5 |Fel Study Feature                                  |6  |12+2   |3  |5th
15th    |+5 |Nethermancy (8th Level)                            |6  |13+3   |3  |5th
16th    |+5 |Ability Score Improvement                          |6  |13+3   |3  |5th
17th    |+6 |Nethermancy (9th Level)                            |6  |14+4   |4  |5th
18th    |+6 |Fel Study Feature                                  |6  |14+4   |4  |5th
19th    |+6 |Ability Score Improvement                          |6  |15+4   |4  |5th
20th    |+6 |Black Harvest                                      |6  |15+4   |4  |5th

**Note:** The "+X" represents Nethermancy spells.
</div>

#### Optional Rule: Multiclassing
If your group uses the optional rule on multiclassing in the *Player's Handbook*, here's what you need to know if you choose warlock as one of your classes.

***Ability Score Minimum.*** As a multiclass character, you must have at least an Intelligence score of 13 to take a level in this class, or to take a level in another class if you are already a warlock.

***Proficiencies Gained.*** If warlock isn't your initial class, you gain skill of your choice from the warlock skill proficiencies when you take your first level of warlock.

***Fel Sorcery.*** You can cast spells known or prepared from the Spellcasting class feature using Fel Sorcery spell slots, and vice versa.

#### Quick Build
You can make a warlock quickly by following these sugges&shy;tions. First, Intelligence should be your highest ability score, followed by Constitution. Second, choose the charlatan background. 

Third, choose the *shadow bolt* and *mage hand* cantrips, along with the 1st level spell *demon skin* and either of the 1st-level spells *drain life* or *witch bolt*.

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
- **Saving Throws:** Constitution, Intelligence
- **Skills:** Choose two skills from Arcana, Deception, History, Insight, Intimidation, Perception, or Religion

#### Equipment
You start with the following equipment, in addition to the equipment granted by your background

- any simple weapon
- *(a)* a component pouch or *(b)* an arcane focus
- *(a)* a scholar's pack or *(b)* an explorer's pack
- a dagger and a belt pouch

<div class='footnote'>PART 1 | CLASSES</div>

\pagebreakNum

### Profane Secrets
*1st-level warlock feature*

<div style='margin-top:-4px'></div>

You have spent long hours researching and practicing forbidden knowledge, gaining the following benefits:
- You can speak, read, and write Eredun.
- You have advantage on Intelligence checks made to recall information about aberrations, fiends, and undead.
- You apply your proficiency bonus when you make a Charisma check while interacting with fiends, or twice your proficiency bonus if you are proficient in the skill.

<div style='margin-top:-4px'></div>

### Fel Sorcery
*1st-level warlock feature*

<div style='margin-top:-4px'></div>

Your research into forbidden knowledge has given you facility with dark magic. See chapter 10 of the Player's Handbook for the general rules of spellcasting and chapter 6 for the warlock spell list.

<div style='margin-top:-4px'></div>

#### Cantrips
You know two cantrips of your choice from the warlock spell list. You learn additional warlock cantrips of your choice at higher levels, as shown in the Cantrips Known column of the Warlock table.

<div style='margin-top:-4px'></div>

#### Spell Slots
The Warlock table shows how many spell slots you have. The table also shows what the level of those slots is; all of your spell slots are the same level. To cast one of your warlock spells of 1st level or higher, you must expend a spell slot. You regain all expended Fel Sorcery spell slots when you finish a short or long rest.

For example, when you are 5th level, you have two 3rd-level spell slots. To cast the 1st-level spell *Witch Bolt*, you must spend one of those slots, and you cast it as a 3rd-level spell.

<div style='margin-top:-4px'></div>

#### Spells Known of 1st Level and Higher
At 1st level, you know two 1st-level spells of your choice from the warlock spell list.

The Spells Known column of the Warlock table shows when you learn more warlock spells of your choice of 1st level or higher. A spell you choose must be of a level no higher than what's shown in the table's Slot Level column for your level. When you reach 6th level, for example, you learn a new warlock spell, which can be 1st, 2nd, or 3rd level.

Additionally, when you gain a level in this class, you can choose one of the warlock spells you know and replace it with another spell from the warlock spell list, which also must be of a level for which you have spell slots.

<div style='margin-top:-4px'></div>

> ##### Creature Soul Shards
> Soul shards are only useful if they are created from sufficiently dense spirit energy or complex souls. While some exceptions exist, the following guidelines typically hold true:
> - All humanoids can produce soul shards.
> - Most undead and almost all constructs cannot produce soul shards.
> - All other creature types typically only produce soul shards if their souls are sufficiently complex: i.e., their CRs are 1/8 and above.

\columnbreak

#### Spellcasting Ability
Intelligence is your spellcasting ability for your warlock spells, so you use your Intelligence whenever a spell refers to your spellcasting ability. In addition, you use your Intelligence modifier when setting the saving throw DC for a warlock spell you cast and when making an attack roll with one.

<div style="text-align: center">

**Spell save DC** = 8 + your proficiency bonus + <br/> your Intelligence modifier

**Spell attack modifier** = your proficiency bonus + <br/> your Intelligence modifier
</div>

#### Ritual Casting
You can cast a warlock spell as a ritual if that spell has the ritual tag and you know the spell.

#### Spellcasting Focus
You can use an arcane focus as a spellcasting focus for your warlock spells.

### Life Tap
*1st-level warlock feature*

<div style='margin-top:-4px'></div>

When you do not have any Fel Sorcery spell slots remain&shy;ing, you can still cast a spell as though you do. As part of the action to cast the spell, your current and maximum hit points are reduced by an amount equal to three times your Fel Sorcery slot level.

This damage cannot be resisted or ignored, and you cannot use this feature if doing so would reduce you to 0 hit points. Your maximum hit point total is restored when you finish a long rest.

### Fel Study
*2nd-level warlock feature*

<div style='margin-top:-4px'></div>

Choose your field of study: Study of Affliction, Study of Demonology, or Study of Destruction, each of which is detailed after the class's description. Your choice grants you features at 6th level and again at 10th, 14th, and 18th level.

### Soul Shards
*2nd-level warlock feature*

<div style='margin-top:-4px'></div>

You can create soul shards: small crystals formed from fragments of souls and spirits. You can expend a soul shard to empower your warlock spells and abilities. You start knowing the abilities listed below and learn more as you gain more levels in the warlock class. 

You can have a number of soul shards up to your proficiency bonus at any given time; attempting to create an additional soul shard results in a useless dull gemstone. Soul shards last until used, at which point they disappear. If a soul shard leaves your possession for at least 8 hours, it disappears. Soul shards you create can only be used by you; soul shards created by other warlocks are useless.

Over the course of a rest, you can gather fragments of wandering souls to create soul shards. You can create a single soul shard over the span of a short rest, or any number over a long rest.

Additionally, you can capture part of the escaping souls of nearby dying creatures in the form of soul shards. When an appropriate creature within 60 feet of you dies, you can use your reaction to create a single soul shard. 

What constitutes an appropriate creature is up to a DM's discretion, but a guideline is listed in the **Creature Soul Shards** sidebar. 

<div class='footnote'>PART 1 | CLASSES</div>

\pagebreakNum

You can expend a soul shard within 5 feet of you to create one of the following effects:

***Bolster Life.*** You can expend a soul shard as a bonus action to grant yourself temporary hit points equal to your Intelligence modifier + your warlock level.

***Borrow Experience.*** You can use a bonus action to expend a soul shard, bolstering yourself with the soul's life experience and making your next attack roll, ability check, or saving throw with advantage. If you don't use this benefit before the start of your next turn, it is lost.

***Casting Circle.*** You can expend a soul shard as a bonus action to create a 5-foot radius circle of demonic runes to appear on the ground. As long as you remain in this circle, you have advantage on concentration checks. The circle fades after 1 minute.

***Soul Rites.*** You can expend a soul shard to cast any warlock spell with the 'ritual' tag, so long as you are capable of casting spells of the same level. You do not have to know the spell to cast it as a ritual, so long as it is on the warlock spell list.

### Dark Grimoires
*3rd-level warlock feature* 

<div style='margin-top:-4px'></div> 

You gain one of the following features of your choice.

#### Grimoire of Infusion 
You infuse your body with a protective shell of energy that hungers for lifeforce. When unarmored, your AC is 13 + your Dexterity modifier.

Additionally, whenever you regain hit points, you can gain temporary hit points equal to your proficiency bonus. These temporary hit points last until you finish a long rest. While you have any temporary hit points, you gain a +2 bonus to AC. You cannot use a shield and gain this effect.

#### Grimoire of Knowledge
You add the spells on your Expanded Spell List to your warlock spells known, provided that you are able to cast warlock spells of that level. These do not count against the number of spells known, as shown on the Warlock table, and cannot be replaced.

Additionally, choose two of your skill proficiencies. Your proficiency bonus is doubled for any ability check you make that uses either of the chosen proficiencies.

\columnbreak

#### Grimoire of Servitude
You can summon a demonic minion at the end of a long rest. Your minion acts independently of you, but it always obeys your commands. You initially know how to summon one type of minion, selected from the list at the end of the class description. You learn how to summon an additional type of minion at 5th, 11th, and 17th level.

Once summoned, a demonic minion remains until it is slain or dismissed. You can temporarily dismiss your minion as an action. It disappears into a pocket dimension where it awaits your summons. Alternatively, you can dismiss it forever. As an action while it is temporarily dismissed, you can cause it to reappear in any unoccupied space within 30 feet of you.

When the minion drops to 0 hit points, it disappears, leaving behind no physical form. If the demon has died within the last hour, you can expend a soul shard as an action to revive it, provided you are within 5 feet of the location of its death. The demon returns to life after 1 minute with all its hit points restored.

In combat, it shares your initiative and takes its turn immediately after yours. It can move and use its reaction on it's own, but the only action it takes on its turn is the Dodge action, unless you take a bonus action on your turn to command it to take one of the actions in its stat block or the Dash, Disengage, Help, Hide or Search action.

### Ability Score Improvement
*4th-level warlock feature*

<div style='margin-top:-4px'></div>

When you reach 4th level, and again at 8th, 12th, 16th, and 19th level, you can increase one ability score of your choice by 2, or you can increase two ability scores of your choice by 1. As normal, you can't increase an ability score above 20 using this feature.

#### Fel Versatility (Optional)
Whenever you reach a level in this class that grants the Ability Score Improvement feature, you can do one of the following, representing a change of focus:
- Replace one cantrip you learned from this class's Fel Sorcery feature with another cantrip from the warlock spell list.
- Replace the option you chose for the Dark Grimoires feature with one of that feature's other options.

### Nethermancy
*11th-level warlock feature*

<div style='margin-top:-4px'></div>

You can push yourself to cast more powerful spells a certain number of times per day. You gain a single spell slot of 6th level. This spell slot can be expended to cast any warlock spell you know. You regain any expended Nethermancy spell slots when you finish a long rest.

<img src='https://www.gmbinder.com/images/8GHYm5P.jpg' style='position:absolute; top:745px; right:0px; width:800px' />
<img src='https://www.gmbinder.com/images/3e9S91s.png' style='position:absolute; top:-55px; right:-15px; width:825px' />
<img src='https://www.gmbinder.com/images/pZ94Ass.png' style='position:absolute; top:683px; right:400px; width:350px' />

<div class='footnote footnote-white'>PART 1 | CLASSES</div>

\pagebreakNum

Whenever you gain a spell slot through Nethermancy, you also learn a single warlock spell of a level that you can cast. These are counted separately from your normal spells, as shown on the Spells Known column of the Warlock table.

At higher levels you earn more spell slots: one 7th level spell slot at 13th level, one 8th level slot at 15th level, and one 9th level slot at 17th level.

When you gain a level in this class, you can choose one of the warlock spells gained through Nethermancy and replace it with another spell from the warlock spell list.  

### Black Harvest
*20th-level warlock feature*

<div style='margin-top:-4px'></div>

When a creature that can produce soul shards dies within 60 feet of you, you can completely drain their fleeing soul to restore your own power. You regain all expended soul shards and restore your current and maximum hit point total by the amount that it has been lowered by your Life Tap feature. The trauma of this power results in the creature only being able to be restored to life by *true resurrection*. 

Once you use this feature you cannot use it again until you finish a long rest.

## Fel Studies
Warlocks have come into contact with the powerful fel, studying its uncontrollable energy. Three such studies exist, each delving into a different aspect of the powers wielded by warlocks.

### Study of Affliction
Warlocks that study affliction become masters of shadow-touched powers, unlike priests of the shadow priesthood, warlocks delight in the use of fel as a force to cause pain and leaving their enemies in whirls of torment.

#### Expanded Spell List
*2nd-level Study of Affliction feature*

<div style='margin-top:-4px'></div>

Your area of study lets you choose from an expanded list of spells when you learn a warlock spell. The following spells are added to the warlock spell list for you.

##### Affliction Expanded Spells
Spell<br/>Level|Spells
--------------|------
1st|✦ *dark void*, *dissonant whispers*
2nd|*blindness/deafness*, ✦ *mind flay*
3rd|*slow*, *stinking cloud*
4th|*confusion*, *elemental bane ^XGE^*
5th|*cloudkill*, *contagion*

#### Corruption
*2nd-level Study of Affliction feature*

<div style='margin-top:-4px'></div>

You can cast Banes, which are powerful curses that can be placed upon creatures. You learn one Bane of your choice, which are detailed under "Banes" below. You learn one additional Bane of your choice, and can choose one of the Banes you know and replace it with another, at 6th, 10th, 14th, and 18th level.

\columnbreak

When you use your Corruption, you choose which Bane to invoke. While invoking a Bane, but before it affects the target, you can choose to amplify the curse by expending a soul shard. An amplified curse gains an additional effect, noted in the curse’s description. If a Bane calls for a saving throw, it uses your warlock spell save DC.

You can use this feature once. Beginning at 6th level, you can use your Corruption feature twice, at 14th level you can use it three times between rests, and at 18th level, you can use it four times between rests. You regain all expended uses when you finish a short or long rest.

#### Haunt
*2nd-level Study of Affliction feature*

<div style='margin-top:-4px'></div>

When a creature within 60 feet makes a skill check using Charisma, Intelligence, or Wisdom, you can use your reaction to manifest a demonic presence around it. The creature is haunted, its mind clouded by this presence, though it does not become aware of this before the effect ends.
    
The target must make a Wisdom saving throw against your warlock spell save DC. On a failed save, the skill check also fails. If the target makes another skill check using the same ability score, while haunted, it must repeat the saving throw.

On a successful save, the haunt ends and the skill check is made as normal. Once you use this ability, you can't do so again until you finish a short rest.

#### Curse Master
*6th-level Study of Affliction feature*

<div style='margin-top:-4px'></div>

You have advantage on saving throws and ability checks versus curses. You also learn the *bestow curse* and *remove curse* spells, which you can cast with a range of 30 feet instead of touch. These do not count against the number of spells known listed in the Warlock table. You can cast each of them once at your Fel Sorcery slot level without expend&shy;ing a spell slot and regain the ability to do so when you finish a short or long rest.

#### Writhe in Agony
*10th-level Study of Affliction feature*

<div style='margin-top:-4px'></div>

When a target affected by your Corruption hits you with an attack roll, you can use your reaction to inflict pain upon them, potentially causing them to miss. Roll a d6. On a 4 or higher, the attack instead misses you, regardless of its roll.

#### Unstable Afflictions
*14th-level Study of Affliction feature*

<div style='margin-top:-4px'></div>

When a creature successfully makes a saving throw against one of your warlock spells or abilities, they take an amount of psychic damage equal to half your warlock level.

#### Soul Conduit
*18th-level Study of Affliction feature*

<div style='margin-top:-4px'></div>

Whenever you expend a soul shard, roll a d6. On a roll of 4 or higher, the shard is not expended. If a creature dies as a result of or while under the effect of one of your warlock spells or abilities, you regain an expended soul shard. 

<img src='https://www.gmbinder.com/images/p23X3P4.png' style='position:absolute; width:800px; bottom:-20px; right:0px; transform:scaleX(-1)' /> 

<div class='footnote footnote-white'>PART 1 | CLASSES</div>

\pagebreakNum

#### Banes
The banes are presented in alphabetical order.

<div style='margin-top:-5px'></div>

##### Bane of Agony
As a bonus action, you curse a creature you can see within 30 feet, dealing 1d4 points of psychic damage. During each of your turns for the next minute, you can use your bonus action to deal 1d4 psychic damage to the creature. This damage increases as you level: 2d4 at 5th level, 3d4 at 11th level, and 4d4 at 17th level. The creature can attempt a Wisdom save at the beginning of its turn, ending the effect on a success.

***Amplify.*** When the target is damaged by the Bane, it has disadvantage on the next attack roll it makes before the end of its next turn.

##### Bane of the Elements
When a creature you can see within 30 feet is hit with an attack or spell, you can use your reaction to temporarily weaken their resilience against it. Until the end of the turn, the target loses their resistance to the damage types of the triggering attack or spell.

***Amplify.*** The target instead loses immunity to the damage types of the triggering attack or spell, having resistance to them until the end of the turn.

##### Bane of Exhaustion
As a bonus action, you can attempt to exhaust a creature you can see within 30 feet of you. The target must succeed on a Constitution saving throw or have their speed be reduced to 0 and they can’t use reactions until the end of your next turn.

***Amplify.*** This curse lasts for 1 minute. At the end of each of its turns, the cursed creature can make another Constitution saving throw. On a success, this curse ends.

##### Bane of Fragility
As a bonus action, you can attempt to curse a creature you can see within 30 feet. The creature cannot regain hit points until the end of its next turn. Additionally, any temporary hit points it possesses are removed. When the effect ends, it regains any temporary hit points it possessed.

***Amplify.*** The curse lasts for 1 minute. At the end of each of its turns, the cursed creature can make a Wisdom saving throw. On a success, this curse ends.

##### Bane of Recklessness
When a creature you can see within 30 feet makes an attack roll, you can use your reaction to cause them to attack recklessly. Until the beginning of its next turn, attacks against the creature have advantage.

***Amplify.*** The curse lasts for 1 minute, causing attacks against the creature to have advantage if it attacked in its last turn. It also cannot use the Disengage, Dodge, or Hide actions. The creature can attempt a Wisdom save at the beginning of each of its turns, ending the effect on a success.

##### Bane of Shadows
As a bonus action, you curse a creature you can see within 30 feet until the beginning of your next turn. The first time in a turn that the creature is damaged, it takes an additional 1d8 points of necrotic damage. When the creature takes this extra damage, it can can attempt a Wisdom saving throw against your warlock spell save DC, ending the effect on a success.

***Amplify.*** The curse lasts for 1 minute.

\columnbreak

##### Bane of Tongues
When a creature you can see within 30 feet attempts to cast a spell with a vocal component, you can use your reaction to try to disrupt it with a curse. The creature must use its own reaction to succeed in casting the spell. Until the end of the creature's next turn, it is unable to speak any language it knows.

***Amplify.*** The curse lasts for 1 minute. The creature must use either a bonus action or reaction each time it attempts to cast a spell or the spell fails and is wasted. The creature can attempt an Intelligence saving throw at the end of each of its turns, ending the effect on a success.

##### Bane of Weakness
As a bonus action, you curse a creature you can see within 30 feet until the beginning of your next turn. Whenever the creature hits with a weapon attack, it rolls twice for damage and takes the lower result.

***Amplify.*** The curse lasts for 1 minute. The creature can attempt an Constitution saving throw at the beginning of your turn, ending the effect on a success.

### Study of Demonology
Warlocks that study demonology harness the powers of the malefic demon beings of the twisting nether. Uncovering secrets unknown by residents of Azeroth, and twisting their magic with the aid of demonic powers from the great dark.

#### Expanded Spell List
*2nd-level Study of Demonology feature*

<div style='margin-top:-4px'></div>

Your area of study lets you choose from an expanded list of spells when you learn a warlock spell. The following spells are added to the warlock spell list for you.

##### Demonology Expanded Spells
Spell<br/>Level|Spells
--------------|------
1st|*command*, *protection from evil and good*
2nd|*augury*, *spiritual weapon*
3rd|*magic circle*, *spirit guardians*
4th|*dimension door*, *dominate beast*
5th|*infernal calling ^XGE^*, *planar binding*

#### Dark Pact
*2nd-level Study of Demonology feature*

<div style='margin-top:-4px'></div>

You learn the *find familiar* spell, which does not count against the number of spells listed on the Warlock table. Whenever you cast the spell, the creature is either an aberration or fiend with the demon subtype instead of its normal types. 

While your familiar is on the same plane of existence to you, you can communicate with it telepathically. Additionally, as an action, you can see through your familiar's eyes and hear what it hears until the start of your next turn, gaining the benefits of any special senses that the familiar has. During this time, you are deaf and blind with regard to your own senses. While you are looking through your familiar's eyes, you can also speak through it using your own voice even if your familiar is normally incapable of speech.

<div class='footnote'>PART 1 | CLASSES</div>

\pagebreakNum

Finally, when you cast a spell with a range of touch, your familiar can deliver the spell as if it had cast the spell. Your familiar must be within 100 feet of you, and it must use its reaction to deliver the spell when you cast it. If the spell requires an attack roll, you use your attack modifier for the roll.

If you later gain the Grimoire of Servitude feature, these benefits extend to your demonic minion.

#### Sense Demons
*2nd-level Study of Demonology feature*

<div style='margin-top:-4px'></div>

You gain the ability to sense the presence of demons due to your sensitivity to demonic energies. As an action, you can open your awareness to magically detect demons. Until the end of your next turn, you know the location of any fiends, demons, or aberrations within 60 feet of you that aren't behind total cover and that isn't protected from divination magic. This sense doesn't tell you anything about a creature's capabilities or identity.

You can use this feature a number of times equal to your Intelligence modifier (minimum of once). You regain all expended uses when you finish a long rest.

#### Master Summoner
*6th-level Study of Demonology feature*

<div style='margin-top:-4px'></div>

Your expertise in summoning the creatures of the Twisting Nether provides you with a number of abilities.
- When you create a Casting Circle using soul shards, you can choose to add a ward against extraplanar creatures. Creatures within the circle will gain the benefit of the *sanctuary* spell (using your warlock spell save DC) against fiends, demons, and aberrations. If a creature within the circle makes an attack against or casts a spell on an enemy fiend, demon, or aberration, the circle immediately fades.
- When you cast a spell that summons a fiend, demon, or aberration, you can spend a soul shard to cast it as though it were one level higher.

If you possess the Grimoire of Servitude feature, your minion also gains the following benefits:
- The creature has five times your warlock level in hit points instead of twice.
- The damage from its attacks is considered magical for the purpose of overcoming immunity and resistance to nonmagical attacks and damage.

#### Soul Link
*10th-level Study of Demonology feature*

<div style='margin-top:-4px'></div>

As an action, you can bind your soul to that of another creature within 60 feet. The creature must be willing to accept the bond; summoned creatures under your control are automatically considered willing. If the creature ever becomes hostile, are reduced to 0 hit points, or they are more than 120 feet from you, then the bond breaks.

Whenever you take damage, you can use your reaction to gain resistance to all damage until the end of the current turn. When you do, the bonded creature takes an equal amount of damage to the amount you took. 

\columnbreak

#### We Are Legion
*14th-level Study of Demonology feature*

<div style='margin-top:-4px'></div>

You apply the fundamentals of demonology to your body and soul, permanently transforming yourself into a demon. Your body gains demonic features, such as glowing green eyes, great horns, or spikes and scales on your body. You also gain the following abilities:
- You sprout wings that grant you a fly speed equal to your movement speed. You can hide or unhide these wings as a bonus action.
- You gain resistance to fire and necrotic damage.
- You do not age, and you do not need to eat, drink, or sleep.
- Demons with an intelligence of 3 or lower will not attack you unless you attack them.

___
> ## Demon Lord
> *Large fiend (demon), chaotic evil*
> ___
> - **Armor Class** 20 (natural armor)
> - **Hit Points** five times your warlock level (the demon lord has a number of Hit Dice [d10s] equal to your warlock level)
> - **Speed** 40 ft., fly 60 ft.
> ___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |20 (+5)|16 (+3)|20 (+5)|16 (+3)|16 (+3)|16 (+3)|
> ___
> - **Saving Throws** equal to your spell attack modifier
> - **Damage Resistances** fire, necrotic; bludgeoning, piercing, and slashing from nonmagical weapons
> - **Senses** truesight 60 ft., passive Perception 19
> - **Languages** Eredun, understands the languages of its summoner
> ___
> ***Aggressive.*** As a bonus action, the demon lord can move up to its speed toward a hostile creature that it can see.
> 
> ***Death Throes.*** When the demon lord drops to 0 hit points or the it is dismissed, the demon lord explodes, and each creature within 10 feet of it must make a Dexterity saving throw against your spell save DC. A creature takes 3d10 fire damage on a failed save, or half as much damage on a successful one.  
> 
> ***Magic Resistance.*** The demon lord has advantage on saving throws against spells and other magical effects.
>
> ***Fel Weapons.*** The demon lord's weapon attacks are treated as if magical.
>
> ### Actions
> ***Multiattack.*** The demon lord makes four attacks.
> 
> ***Slash.*** *Melee Weapon Attack:* your spell attack modifier to hit, reach 5 ft., one target. *Hit:* 2d8 + 5 slashing damage.
>
> ***Shadowbolt.*** *Ranged Spell Attack:* your spell attack modifier to hit, range 150 ft., one target. *Hit:* 2d12 necrotic damage.

<img src='https://www.gmbinder.com/images/NXvX7mr.png' style='position:absolute; top:885px; right:300px; width:400px;transform:rotate(-20deg);z-index:1000' />

<div class='footnote'>PART 1 | CLASSES</div>

\pagebreakNum

<div style='margin-top:110px'></div>

#### Master Demonologist
*18th-level Study of Demonology feature*

<div style='margin-top:-4px'></div>

You gain one of the following features of your choice:

***Demonic Servant.*** You gain the benefits of the Grimoire of Servitude. If you chose another Dark Grimoire option at 3rd level, you gain the benefits of both that option and the Grimoire of Servitude. 

If instead you chose the Grimoire of Servitude option at 3rd level, you gain the benefits of it twice, being able to summon two demonic minions at once. You do so at the end of a long rest as normal and they can be the same type of demon or two different ones. You do not have to use different actions to control both at once: you can temporarily banish or summon one or both with the same action, and you can issue the same or different orders in combat to one or both as part of the same bonus action.

***Summon Demon Lord.*** As an action, you can call upon one of the most powerful demons you can control, summoning a demon lord to do your bidding. The creature appears an unoccupied space you can see within 60 feet and remains for up to 10 minutes or until it is reduced to 0 hit points, you dismiss it as a bonus action, or you are incapacitated.

The demon lord is an ally to you and your companions. In combat, it shares your initiative count, but it takes its turn immediately after yours. It obeys your verbal commands (no action required by you). If you don't issue any, it takes the Dodge action and uses its move to avoid danger. See the Demon Lord entry above for its statistics. 

Once you use this ability, you cannot do so again until you finish a long rest.

### Study of Destruction
Warlocks that study destruction share many similarities with fire mages, though they utilize magics that no sane mage would meddle with, willing to suffer backlash if they are better able to wreak havoc upon their enemies. They are happy to revel in the destruction they cause, thrilled at any opportunity to watch the world erupt in discord.

#### Expanded Spell List
*2nd-level Study of Destruction feature*

<div style='margin-top:-4px'></div>

Your area of study lets you choose from an expanded list of spells when you learn a warlock spell. The following spells are added to the warlock spell list for you.

##### Destruction Expanded Spells
Spell<br/>Level|Spells
--------------|------
1st|*burning hands*, *chaos bolt ^XGE^*
2nd|*flaming sphere*, *shatter*
3rd|*erupting earth ^XGE^*, *fireball*
4th|*fire shield*, *wall of fire*
5th|*destructive wave*, *flame strike*

\columnbreak

<div style='margin-top:110px'></div>

#### Channel Demonfire
*2nd-level Study of Destruction feature*

<div style='margin-top:-4px'></div>

You can channel the double-edged power of hellfire. When you deal damage, you can choose to take an amount of fire damage up to your warlock level (ignoring any fire damage resistance or immunity). One target takes twice as much fire damage as you took. 

Additionally, you can magically ignite a flammable object you touch with your hand as an action.

#### Chaotic Energies
*2nd-level Study of Destruction feature*

<div style='margin-top:-4px'></div>

When you deal damage with a warlock cantrip, it deals one additional die's worth of damage to one target.

#### Havoc
*6th-level Study of Destruction feature*

<div style='margin-top:-4px'></div>

When you cast a spell that deals damage, targets only one creature, and doesn't have a range of self, you can choose to target a second creature in range with the same spell. You can do so a number of times equal to your proficiency bonus and regain all expended uses of this ability when you finish a long rest.

#### Molten Skin
*10th-level Study of Destruction feature*

<div style='margin-top:-4px'></div>

The burning energies just under your skin empower you as much as they harm your enemies. You gain resistance to cold and fire damage and fire damage that you deal ignores resistance to fire damage.

Additionally, whenever you are hit my a melee attack, you can use your reaction to deal fire damage equal to your warlock level to the attacker.

#### Flames of Xerrath
*14th-level Study of Destruction feature*

<div style='margin-top:-4px'></div>

You can overcharge the power of your spells with the power of fel flames. When you deal damage with a warlock spell cast using a Fel Sorcery spell slot, you can deal maximum damage with that spell.

The first time you do so, you suffer no adverse effect. If you use this feature again before you finish a long rest, you take 5d12 fire damage at the end of the current turn. Each time you use this feature again before finishing a long rest, the fire damage increases by 1d12. This damage ignores resistance and immunity. 

#### Cremation
*18th-level Study of Destruction feature*

<div style='margin-top:-4px'></div>

Your inner fire supercharges, granting you gain immunity to fire damage. In addition, any spell or effect you create ignores resistance to fire damage and treats immunity to fire damage as resistance to fire damage.

Whenever you do fire damage and kill a creature, you can choose to disintegrate them. A disintegrated creature and everything it is wearing and carrying, except magic items, are reduced to a pile of fine gray dust. The creature can be restored to life only by means of *true resurrection*.

<img src='https://www.gmbinder.com/images/EsofAt2.jpg' style='position:absolute; top:-140px; right:0px; width:800px' />
<img src='https://www.gmbinder.com/images/3e9S91s.png' style='position:absolute; top:-30px; left:0px; height:110%; transform:scaleY(-1)' />

<div class='footnote'>PART 1 | CLASSES</div>

\pagebreakNum

<center> <h1>Demonic Minions</h1> </center>

<div style='margin-top:510px'></div>

If you selected the Grimoire of Servitude as your Dark Grimoire feature, you can summon any demonic minion you know from the below list at the end of a long rest. The minions are presented in alphabetical order.

### Felguard
As shock troops of the Legion, felguards are blindly obedient to the word of their master, acting with brute force to overcome all obstacles. Their total lack of imagination is seen as one of the benefits of summoning them, though the rituals involved have a tendency to drain the life from those too weak.

### Felhunter
Relentless hunters, these blind, magic-sniffing bloodhounds of the Legion are employed by their summoners as ruthless guard dogs, or hounds to track down and devour enemy spellcasters. The demons are loyal only to the strongest, and binding them to service is possible only through sheer force of will.

### Imp
Diminutive, inexpensive and high-strung, the fiery imp is the most easily summoned demon, and most often used by warlocks as everything from efficient long-range firepower, to lab assistants, to cannon fodder. Often summoned en masse, it is said by masters to their pupils, “There are always more imps.” Obedient and fearful, they are well aware of their expendable nature.

\columnbreak

<div style='margin-top:502px'></div>

<style>
.descriptive.box {
    padding: 8px;
    border: solid lightgray;
}
</style>

<div class='descriptive box'>

***Pictured above from left to right:*** <br/> *Felguard, Succubus, Felhunter, Imp, Voidwalker, Infernal*

</div>

### Infernal
The ultimate siege demon, infernals rain onto the planet as blazing meteorites wreathed in green fel flame, and then unfold into behemoth golems created only to destroy. Utterly mindless, their burning souls year for destruction. To summon one is a commitment to chaos, and banishing them is exceptionally difficult.

### Succubus
Spies and torturers of the demon world, succubi obey their summoners with enthusiasm and grace. Despite a tendency to grow protective or obsessive over their summoner, they are most often used as interrogators, spies and seductive distractions. Highly intelligent, succubi gain great pleasure through the misfortune of others.

### Voidwalker
Though not technically demons, voidwalkers can be bound by the same means by even young warlocks. Tiny fragments of the ever-hungering Void, voidwalkers are able to sustain extreme punishment before their discorporation, kept bound to the physical plane by their bracers. As simple-minded things of the void, they are ever seeking a chance to destroy those who dare bind them.

<img src="https://www.gmbinder.com/images/AYuE5Qf.png" class="inkblot inkblot-green" style="top:-120px; right:100px; height:1000px; transform: rotate(-90deg)">

<img src='https://www.gmbinder.com/images/1WjcEQ2.png' style='position:absolute; top:-70px; left:360px; height:650px' /> <!-- infernal -->
<img src='https://www.gmbinder.com/images/mn01Y17.png' style='position:absolute; top:190px; left:420px; height:400px; mix-blend-mode:darken' /> <!-- voidwalker  -->
<img src='https://www.gmbinder.com/images/DUNEQZA.png' style='position:absolute; top:-10px; left:-50px; height:540px; transform:scaleX(-1);'  /> <!-- felguard -->
<img src='https://www.gmbinder.com/images/t23Tf3H.png' style='position:absolute; top:290px; left:140px; height:285px; transform:scaleX(-1)' /> <!-- felhunter -->
<img src='https://www.gmbinder.com/images/jA343Jd.png' style='position:absolute; top:220px; left:30px; height:350px' /> <!-- succubus -->
<img src='https://www.gmbinder.com/images/qdDDkm1.png' style='position:absolute; top:420px; left:500px; height:150px; mix-blend-mode:darken' /> <!-- imp -->

<div class='footnote'>PART 1 | CLASSES</div>

\pagebreakNum

___
> ## Felguard Minion
> *Medium fiend (demon), lawful evil*
> ___
> - **Armor Class** 12 + PB
> - **Hit Points** 2 + your intelligence modifier + twice your warlock level (the felguard has a number of Hit Dice [d8s] equal to your warlock level)
> - **Speed** 30 ft.
> ___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |16 (+3)|12 (+1)|14 (+2)|10 (+0)|12 (+1)|12 (+1)|
> ___
> - **Saving Throws** Str +3 plus PB, Con +2 plus PB
> - **Skills** Athletics +3 plus PB, Intimidation +1 plus PB
> - **Senses** darkvision 60 ft., passive Perception 11
> - **Languages** Eredun, understands the languages of its summoner
> ___
> ***Heavy Strike.*** When the felguard hits a target, you can spend a soul shard to cast *earth tremor* ^XGE^ at a spell level equal to your PB centered on the target, without expending a spell slot. 
> 
> ***Legion Strike (3/day).*** When the felguard makes an attack, it can make another attack as a bonus action against a different creature within 5 feet of the first target.
>
> ### Actions
> ***Legion Axe.*** *Melee Weapon Attack:* Your spell attack modifier to hit, reach 5 ft., one target. *Hit:* 1d10 + PB slashing damage.
>
> ### Reactions
> ***Pursuit.*** When an enemy stops moving after leaving the felguard's reach, the felguard can move up to its speed towards the creature and make an attack against it. This movement does not provoke opportunity attacks. 

\columnbreak
___
> ## Felhunter Minion
> *Medium fiend (demon), neutral evil*
> ___
> - **Armor Class** 11 + PB
> - **Hit Points** 2 + your intelligence modifier + twice your warlock level (the minion has a number of Hit Dice [d8s] equal to your warlock level)
> - **Speed** 30 ft.
> ___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |17 (+3)|12 (+1)|14 (+2)| 6 (-2)|12 (+1)|12 (+1)|
> ___
> - **Skills** Perception +1 plus PB, Survival +1 plus PB
> - **Senses** blindsight 120 ft., passive Perception 11 + PB
> - **Languages** —
> ___
> ***Mage Slayer.*** A creature dealt damage by the felhunter has disadvantage on Constitution saving throws made to maintain concentration on a spell this turn.
>
> ***Magic Resistance.*** The felhunter has advantage on saving throws against spells and other magical effects.
>
> ***Sense Magic.*** The felhunter can sense magic within 120 feet of it at will. This feature works like the *detect magic* spell, but is itself not magical.
> 
> ### Actions
> ***Bite.*** *Melee Weapon Attack:* Your spell attack modifier to hit, reach 5 ft., one target. Hit: 1d6 + PB piercing damage.
>
> ### Reactions
> ***Devour Magic.*** When a creature casts a spell at the felhunter and misses or the felhunter makes its saving throw, the felhunter can use its reaction and you can spend a soul shard to deal 1d6 psychic damage per spell level of the spell to the caster, causing the felhunter to gain temporary hit points equal to the damage dealt.

<div class='footnote'>PART 1 | CLASSES</div>

\pagebreakNum

___
> ## Imp Minion
>*Small fiend (demon), chaotic evil*
> ___
> - **Armor Class** 10 + PB
> - **Hit Points** 1 + your Intelligence modifier + twice your warlock level (the minion has a number of Hit Dice [d6s] equal to your warlock level)
> - **Speed** 25 ft.
>___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> | 6 (-2)|15 (+2)|13 (+1)|15 (+2)| 9 (-1)|14 (+2)|
>___
> - **Saving Throws** Dex +2 plus PB, Wis -1 plus PB
> - **Skills** Acrobatics +2 plus PB, Deception +2 plus PB, Insight -1 plus PB, Stealth +2 plus PB
> - **Senses** darkvision 60 ft., passive Perception 9
> - **Languages** Eredun, understands the languages of its summoner 
> ___
> ***Explosive Step.*** You can spend a soul shard to allow your imp to use its bonus action to teleport up to 60 feet to an unoccupied space it can see. Each creature within 10 feet of the space it left takes fire damage equal to 1d10 times your PB, or half damage on a successful Dexterity saving throw.
> 
> ### Actions
> ***Fire Blast.*** *Ranged Weapon Attack:* Your spell attack modifier to hit, range 60 ft., one target. *Hit:* 1d6 + PB fire damage.
> 
> ### Reactions
> ***Phase Shift (3/day).*** When the imp is subjected to an effect that allows it to make a saving throw to take half damage, it can  automatically succeed. 

\columnbreak
___
> ## Infernal Minion
> *Large construct (fiend), chaotic evil*
> ___
> - **Armor Class** 12 + PB
> - **Hit Points** 3 + your Intelligence modifier + twice your warlock level (the minion has a number of Hit Dice [d10s] equal to your warlock level)
> - **Speed** 30 ft.
>___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |18 (+4)|10 (+0)|16 (+3)| 6 (-2)|10 (+0)| 6 (-2)|
>___
> - **Damage Resistances** psychic
> - **Damage Immunities** fire, poison
> - **Condition Immunities** charmed, exhausted, frightened, paralyzed, petrified, poisoned
> - **Senses** darkvision 60 ft., passive Perception 10
> - **Languages** understands the languages of its summoner but can't speak
> ___
> ***Fiery Skin.*** A creature that hits the infernal with a melee attack takes fire damage equal to your PB.
>
> ***Immolation Aura.*** You can spend a soul shard to cause the infernal to emit flames from its body for 1 minute. At the start of each of the infernal's turns for the duration, each creature within 5 feet of it takes fire damage equal to 1d6 plus PB, and flammable objects in the aura that aren't being worn or carried ignite.
> 
> ***Siege Monster.*** The infernal deals double damage to objects and structures.
> 
> ### Actions
> ***Slam.*** *Melee Weapon Attack:* Your spell attack modifier to hit, reach 5 ft., one target. *Hit:* 1d8 bludgeoning damage plus PB fire damage.

\pagebreakNum
___
> ## Succubus Minion
>*Medium fiend (demon), chaotic evil*
> ___
> - **Armor Class** 11 + PB
> - **Hit Points** 1 + your Intelligence modifier + twice your warlock level (the minion has a number of Hit Dice [d8s] equal to your warlock level)
> - **Speed** 30 ft., fly 50 ft.
> ___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> | 8 (-1)|16 (+3)|13 (+1)|15 (+2)|13 (+1)|20 (+5)|
>___
> - **Saving Throws** Cha +5 plus PB, Wis +1 plus PB 
> - **Skills** Deception +5 plus PB, Insight +1 plus PB, Persuasion +5 plus PB, Stealth +3 plus PB
> - **Senses** darkvision 60 feet, passive Perception 11
> - **Languages** Common, Eredun, understands the languages of its summoner, telepathy 60 ft.
> ___
> ***Innate Spellcasting.*** The succubus can cast the following spells at will: *friends*, *invisibility* (self only)
>
> ***Lash of Pain.*** When the succubus deals damage with its whip, you can spend a soul shard to cause the creature to become frightened of the succubus until the beginning of your minion's next turn.
> 
> ***Shapechanger.*** The succubus can use its action to polymorph into a Small or Medium humanoid, or back into its true form. Other than its size and speed, its statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies.
>
> ### Actions
> ***Whip.*** *Melee Weapon Attack:* Your spell attack modifier to hit, reach 10 ft., one target. *Hit:* 1d4 + PB slashing damage.

\columnbreak
___
> ## Voidwalker Minion
> *Medium aberration (void), neutral evil*
> ___
> - **Armor Class** 13 + PB
> - **Hit Points** 3 + your Intelligence modifier + twice your warlock level (the minion has a number of Hit Dice [d8s] equal to your warlock level)
> - **Speed** 30 ft.
> ___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |15 (+2)|10 (+0)|16 (+3)| 7 (-2)|14 (+2)| 7 (-2)|
>___
> - **Saving Throws** Con +3 plus PB, Wis +2 plus PB 
> - **Damage Resistances** cold, necrotic
> - **Damage Immunities** poison
> - **Condition Immunities** exhausted, grappled, poisoned
> - **Senses** darkvision 60 feet, passive Perception 12
> - **Languages** Understands the languages of its summoner, telepathy 60 ft.
> ___
> ***Innate Spellcasting.*** The voidwalker can cast *armor of agathys* on itself at will.
>
> ***Shadow Stealth.*** While in dim light or darkness, the voidwalker has advantage on Stealth checks and can take the Hide action as a bonus action.
>
> ### Actions
> ***Slam.*** *Melee Weapon Attack:* Your spell attack modifier to hit, reach 5 ft., one target. *Hit:* 1d8 + PB bludgeoning damage and the target has disadvantage on any attack roll it makes on a target other than the voidwalker until the beginning of the voidwalker's next turn.
>
> ***Consuming Shadows.*** You can spend a soul shard and choose up to 5 creatures with in 10 feet of the voidwalker to make a Constitution saving throw. The targets take damage equal to twice your PB, half in cold and half in necrotic, on a failed save, or half damage on a successful save. The voidwalker gains temporary hit points equal to the total amount of damage dealt.

<div class='footnote'>PART 1 | CLASSES</div>

\pagebreakNum

# Chapter 6: Spells
While most spell descriptions are located in the Player's Handbook, some spells are described in other locations, as indicated by the table below.

Symbol|Spell Location
------|--------------------------
✦ |In this chapter, under Spell Descriptions
^EGW^ | Explorer's Guide to Wildemount
^TCE^ | Tasha's Cauldron of Everything
^XGE^ |Xanathar's Guide to Everything

> ##### Variant Rule: Xorothian Steed
> Dungeon Masters might prefer making the creatures summoned by a warlock with the *find steed* and *find greater steed* fiends instead of the other creature types listed in those spells. Additionally, the *find greater steed* spell can summon a felsteed in addition to the other creatures listed.

## Warlock Spell List
<div style='column-count:2'>

##### Cantrips (0 Level)
Acid Splash
<br/> Blade Ward
<br/> Chill Touch
<br/> Create Bonfire ^XGE^
<br/> ✦ Decompose
<br/> ✦ Diabolism
<br/> ✦ Fel Flame
<br/> Friends
<br/> Fire Bolt
<br/> Green-Flame Blade ^TCE^
<br/> Mage Hand
<br/> Produce Flame
<br/> Sapping Sting ^EGW^
<br/> ✦ Shadow Bolt
<br/> ✦ Shadow Glide
<br/> Toll the Dead ^XGE^
<br/> ✦ Touch of Chaos

##### 1st Level
Alarm
<br/> Arms of Hadar
<br/> Bane
<br/> Cause Fear ^XGE^
<br/> Chromatic Orb
<br/> Comprehend Languages
<br/> ✦ Demon Skin
<br/> Detect Magic
<br/> ✦ Drain Life
<br/> Expeditious Retreat
<br/> False Life
<br/> Find Familiar
<br/> Hellish Rebuke
<br/> Hex
<br/> Identify
<br/> Illusory Script

<br/> Jump
<br/> Ray of Sickness
<br/> Shield
<br/> Sleep
<br/> Tasha's Caustic Brew ^TCE^
<br/> Tasha's Hideous Laughter
<br/> Unseen Servant
<br/> Witch Bolt

##### 2nd Level
Aganazzar's Scorcher ^XGE^
<br/> Alter Self
<br/> Arcane Lock
<br/> Cloud of Daggers
<br/> Continual Flame
<br/> ✦ Create Healthstone
<br/> Crown of Madness
<br/> Darkness
<br/> Darkvision
<br/> Dragon's Breath
<br/> Enthrall
<br/> Find Steed
<br/> Flame Blade
<br/> Heat Metal
<br/> Hold Person
<br/> Invisibility
<br/> Knock
<br/> Levitate
<br/> Locate Object
<br/> Melf's Acid Arrow 
<br/> Mind Spike ^XGE^
<br/> Misty Step
<br/> Phantasmal Force
<br/> Pyrotechnics ^XGE^
<br/> Ray of Enfeeblement

\columnbreak

<br/> Scorching Ray
<br/> Shadow Blade ^XGE^
<br/> Spider Climb
<br/> Suggestion
<br/> Tasha's Mind Whip ^TCE^
<br/> Web

##### 3rd Level
Bestow Curse
<br/> Clairvoyance
<br/> Counterspell
<br/> Dispel Magic
<br/> Elemental Weapon
<br/> Enemies Abound ^XGE^
<br/> Fear
<br/> Fly
<br/> Gaseous Form
<br/> Haste
<br/> Hunger of Hadar
<br/> Hypnotic Pattern
<br/> Life Transference ^XGE^
<br/> Major Image
<br/> Melf's Minute Meteors
<br/> Phantom Steed
<br/> Protection From Energy
<br/> Remove Curse
<br/> Sending
<br/> Speak With Dead
<br/> Summon Lesser <br/>&nbsp;&nbsp;Demons ^XGE^
<br/> Summon Shadow-<br/>&nbsp;&nbsp;spawn ^TCE^
<br/> Summon Undead ^TCE^
<br/> Tiny Servant ^XGE^
<br/> Tongues
<br/> Vampiric Touch
<br/> Water Breathing
<br/> Water Walk

##### 4th Level
Arcane Eye
<br/> Banishment
<br/> Blight
<br/> Charm Monster ^XGE^
<br/> Compulsion
<br/> Death Ward
<br/> Evard's Black Tentacles
<br/> Find Greater Steed ^XGE^
<br/> ✦ Fire and Brimstone
<br/> Greater Invisibility
<br/> Hallucinatory Terrain
<br/> Leomund's Secret Chest
<br/> Locate Creature
<br/> Mordenkainen's Faithful <br/>&nbsp;&nbsp; Hound
<br/> Otiluke's Resilient Sphere
<br/> Phantasmal Killer
<br/> Shadow of Moil ^XGE^
<br/> Sickening Radiance ^XGE^
<br/> Summon Aberration ^TCE^
<br/> Summon Greater <br/>&nbsp;&nbsp;Demon ^XGE^
<br/> Vitriolic Sphere ^XGE^

\columnbreak 

<div style='margin-top:-10px;'></div>

##### 5th Level
Antilife Shell
<br/> ✦ Create Soulstone
<br/> Danse Macabre ^XGE^
<br/> Dispel Evil and Good
<br/> Dominate Person
<br/> Enervation ^XGE^
<br/> Far Step ^XGE^
<br/> Geas
<br/> Hold Monster
<br/> Immolation ^XGE^
<br/> Insect Plague
<br/> Modify Memory
<br/> Negative Energy Flood ^XGE^
<br/> ✦ Rain of Fire
<br/> Rary's Telepathic Bond
<br/> ✦ Ritual of Summoning
<br/> Scrying
<br/> Synaptic Static ^XGE^
<br/> Teleportation Circle
<br/> Wall of Force

##### 6th Level
Arcane Gate
<br/> Circle of Death
<br/> Contingency
<br/> ✦ Create Soulwell
<br/> Create Undead
<br/> Disintegrate
<br/> Drawmij's Instant &nbsp;&nbsp;Summons
<br/> Eyebite
<br/> Globe of Invulnerability
<br/> Harm
<br/> Investiture of Flame ^XGE^
<br/> Magic Jar
<br/> Mass Suggestion
<br/> Mental Prison ^XGE^
<br/> Otto's Irresistible Dance
<br/> Planar Ally
<br/> Scatter ^XGE^
<br/> ✦ Shadowfury
<br/> Soul Cage ^XGE^
<br/> Summon Fiend ^TCE^
<br/> Tasha's Otherworldy <br/> &nbsp;&nbsp; Guise ^TCE^
<br/> True Seeing
<br/> Word of Recall

##### 7th Level
Delayed Blast Fireball
<br/> Etherealness
<br/> Finger of Death
<br/> Fire Storm
<br/> Forcecage
<br/> Mordenkainen's Sword
<br/> Sequester
<br/> Teleport

</div>

<div class='footnote'>PART 2 | MAGIC</div>

\pagebreakNum
<div style='column-count:2'>

<div style='margin-top:-10px;'></div>

##### 8th Level
Abi-Dalzim's Horrid <br/>&nbsp;&nbsp;Wilting ^XGE^
<br/> Antimagic Field
<br/> ✦ Cataclysm
<br/> Clone
<br/> Demiplane
<br/> Dominate Monster
<br/> Feeblemind
<br/> Glibness
<br/> Maddening Darkness ^XGE^
<br/> Reality Break ^EGW^
<br/> Telepathy

##### 9th Level
Blade of Disaster ^TCE^
<br/> Gate
<br/> Imprisonment
<br/> Meteor Swarm
<br/> Psychic Scream ^XGE^
<br/> Ravenous Void ^EGW^
<br/> Weird

</div>

## Spell Descriptions

#### Cataclysm
*8th-level conjuration*
___
- **Casting Time:** 1 action
- **Range:** 150 feet
- **Components:** V, S, M (a piece of charcoal)
- **Duration:** Instantaneous
___
You cause the ground to crack and split, with molten magma and fire spitting up out in a 60-foot radius centered on a point within range. Each creature in the area must make a Dexterity saving throw or take 10d6 fire damage, taking half damage on a success.

A creature who takes fire damage from this spell is set aflame, taking an additional 2d6 fire damage at the beginning of each of their turns. They or another adjacent creature can use their action to put out the flames, taking 1d4 fire damage in the process.

The ground in the area of this spell remains damaged, turning into difficult terrain. It remains hot for 1 minute, and any creature who enters the area for the first time on their turn or starts their turn there takes 1d4 fire damage.

#### Create Healthstone
*2nd level conjuration*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S
- **Duration:** Instantaneous
___
You create a fist-sized glowing green stone in your hand. A creature can use its action to crush the stone, destroying it and regaining hit points equal to 1d10 + your spellcasting modifier. The stone loses its abilities if not used within 24 hours.

**At Higher Levels:** When you cast this spell using a spell slot of 3rd level or higher, the healing increases by 1d10 for each slot level above 2nd.

\columnbreak

#### Create Soulstone
*5th level conjuration (ritual)*
___
- **Casting Time:** 10 minutes
- **Range:** Self (30 feet)
- **Components:** V, S, M (a crystal orb worth 50 gp)
- **Duration:** 10 days
___
You bind the souls of creatures to the world of the living, allowing them to come back from the brink of death. When you cast this spell, select up to six willing creatures within range. If any of the targets would be reduced to 0 hit points during the spell's duration, they are reduced to 1 hit point instead and the material component is consumed. When the spell ends, each creature that been targeted by the spell is alerted that the spell has ended and which creature had been saved. The spell cannot alert or save creatures on another plane of existence than the material component.

If you cast this spell again, the effect of any previously cast create soulstone spell ends. The spell ends prematurely if its material component is ever not on your person. A creature can only benefit from one soulstone at a time.

#### Create Soulwell
*6th level conjuration*
___
- **Casting Time:** 10 minutes
- **Range:** 5 feet
- **Components:** V, S
- **Duration:** 1 minute
___
You cause a runed stone altar to appear in an unoccupied space within range. An allied creature can use its action to reach into the liquid that fills the basin to withdraw a glowing green stone. When the spell ends, the altar disappears, but the stones remain until used or 24 hours pass, whichever is first. A creature can crush the stone as an action to regain hit points equal to 4d10 + your spellcasting modifier.

**At Higher Levels:** When you cast this spell using a spell slot of 7th level or higher, the healing increases by 1d10 for each slot level above 6th.

#### Dark Void
*1st-level evocation*
___
- **Casting Time:** 1 action
- **Range:** 30 feet
- **Components:** V, S, M (a holy symbol)
- **Duration:** Instantaneous
___
You grasp the fabric around a target within range, pulling necromantic energies from it and creatures of your choice within 5 feet of it. A target must make a Constitution saving throw, taking 2d4 necrotic damage on a failed save, or half as much damage on a successful one.

***At Higher Levels.*** When you cast this spell using a spell slot of 2nd level or higher, the damage increases by 1d4 for each slot level above 1st

<div class='footnote'>PART 2 | MAGIC</div>

\pagebreakNum

#### Decompose
*Necromancy cantrip*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S
- **Duration:** 1 minute
___
You reach out and touch the corpse of a creature. Over the next minute, the corpse begins to rapidly decompose, sprouting fungus and moss as it begins to degrade into compost and mulch. An odd-colored flower or two may also spring from the corpse in this time. Applicable requirements for resurrection are unaffected by this decomposition.

#### Demon Skin
*1st-level transmutation*
___
- **Casting Time:** 1 action
- **Range:** Self
- **Components:** V, S, M (dried skin of a demon or fiend)
- **Duration:** 8 hours
___
Your skin becomes covered in a layer of fel energy, infusing you with fiendish vigor. Your base Armor Class becomes 8 + your spellcasting ability modifier (minimum AC 10). 

Additionally, your current hit points and hit point maximum each increase by 2. If ending the spell would cause your current hit point total to drop to 0 or lower, it drops to 1 instead.

***At Higher Levels:*** When you cast this spell using a spell slot of 2nd level or higher, the Armor Class granted by the spell increases by 1 and your current hit point total and hit point maximum each increase by 2 for each slot level above 1st.

\columnbreak
#### Diabolism
*Necromancy cantrip*
___
- **Casting Time:** 1 action
- **Range:** Self
- **Components:** S
- **Duration:** Up to 1 hour
___
This spell channels a small amount of dark energy. You create one of the following magical effects within range:
- Choose a point within 30 feet. In a 5-foot radius of that point, bright light becomes dim light, and dim light becomes darkness for 1 hour. Any light sources within the area have the light they produce suppressed for the duration.
- An object up to 1 cubic foot in size or an area up to 1 square foot that you touch lightly decays. Wood rots, glass cracks, flowers wilt. Casting the spell and then continuing to touch the target advances the decay; after 1 minute, the target is destroyed. This spell cannot affect creatures, magical objects, or sturdy materials like metal and stone.
- You can reanimate a Tiny 0 CR beast for 1 hour. It is undead and obeys all of your commands to the best of it's abilities, though it cannot attack. You cannot use this effect again until the reanimated creature dies, or the effect ends.
- You instantaneously light a candle, torch, or small campfire. The fire glows your choice of a smoldering red, bright green, or shadowy purple until extinguished.
- Your fingertip glows green or purple for up to 1 minute. While it glows, you can use your finger to draw glowing lines of the same color on a solid surface that last for 1 hour.

If you cast this spell multiple times, you can have up to three of its non-instantaneous effects active at a time, and you can dismiss such an effect as an action.

#### Drain Life
*1st-level necromancy*
___
- **Casting Time:** 1 Action
- **Range:** 30 feet
- **Components:** V, S
- **Duration:** Concentration, up to 1 minute
___
You cause a green stream of energy to trail from the target creature's eyes and mouth and into your hand, forming a continuous stream of energy to bind you two together.

Make a ranged spell attack against that creature. On a hit, the target takes 1d8 necrotic damage, and on each of your subsequent turns for the duration, you can use your bonus action to deal 1d8 necrotic damage to the target automatically. Each time the target takes damage from this spell, you regain a number of hit points equal to half the damage dealt and their maximum hit point total is reduced by the same amount. This reduction lasts until they finish a long rest.

On a miss, you can spend your action on subsequent turns within the spell’s duration to make another ranged spell attack against the same creature. The spell ends if you use your action to do anything else. 

The spell ends if your target is more than 30 feet away from you or has total cover from you at the end of your turn. This spell has no effect on the creature if they are a construct or undead.


<div class='footnote'>PART 2 | MAGIC</div>

\pagebreakNum

***At Higher Levels:*** When you cast this spell using a spell slot of 2nd level or higher, the initial damage increases by 1d8 for each slot level above 1st. The damage dealt as a bonus action also increases by 1d8 for every two slot levels above 1st.

#### Fel Flame
*Evocation cantrip*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** Instantaneous
___
A green flame skitters across the ground towards a creature within range. Make a ranged spell attack against the target. On a hit, the target takes 1d8 fire damage. Fel flame ignores fire resistance, and creatures immune to fire damage are considered to be resistant.

This spell's damage increases by 1d8 when you reach 5th level (2d8), 11th level (3d8), and 17th level (4d8). 

#### Fire and Brimstone
*4th-level evocation*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** Instantaneous
___
You form six orbs of fire above your head, which you launch at targets within 20 feet of a point you choose within range. You can direct the orbs to hit one target or several. A target takes 1d10 fire damage for each orb that strikes it, and can attempt a Dexterity saving throw to take half as much damage. Each target only makes one saving throw, regardless of how many orbs it is struck by.

***At Higher Levels.*** When you cast this spell using a spell slot of 5th level or higher, the spell creates one more orb for each spell level above 4th.

#### Mind Flay
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

#### Rain of Fire
*5th-level evocation*
___
- **Casting Time:** 1 action
- **Range:** 120 feet
- **Components:** V, S
- **Duration:** Concentration, up to 1 minute
___
You summon a cloud at a point within range, causing flaming raindrops to blanket a 15-foot radius area around it. Each creature entering the area for the first time on their turn, or who starts their turn there, must make a Dexterity saving throw, taking 3d12 fire damage on a failed save, or half as much on a success.

As a bonus action you can move the cloud up to 15 feet to a point you can see. Unattended flammable objects in the area are ignited. 

***At Higher Levels:*** When you cast this spell using a spell slot of 6th level or higher, it deals an additional 1d12 points of fire damage for each spell level above 5th.

#### Ritual of Summoning
*5th-level conjuration (ritual)*
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
*Necromancy cantrip*
___
- **Casting Time:** 1 action
- **Range:** 120 feet
- **Components:** V, S
- **Duration:** Instantaneous
___
You fire a blast of necrotic energy at a creature within range. Make a ranged spell attack against the target. On a hit, the target takes 1d8 necrotic damage. 

When the spell hits, you can choose to take 1 point of psychic damage to increase the damage dealt to 1d12 necrotic damage.

The spell’s damage dealt increases by one die when you reach 5th level (2d8 or 2d12), 11th level (3d8 or 3d12), and 17th level (4d8 or 4d12). The optional damage taken increases by 2 when you reach 5th level (3), 11th level (5), and 17th level (7).

#### Shadow Glide
*Conjuration cantrip*
___
- **Casting Time:** 1 bonus action
- **Range:** Self (5 feet)
- **Components:** V
- **Duration:** Instantaneous
___
Obscured by shadows, you teleport to an unoccupied space within 5 feet.

<div class='footnote'>PART 2 | MAGIC</div>

\pagebreakNum

#### Shadowfury
*6th-level enchantment*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** Concentration, up to 1 minute
___
You extend your arm and draw shadow energy down upon creatures within a 10-foot radius of a point within range. Each creature takes 5d8 psychic damage and must succeed on a Wisdom saving throw or be stunned for the duration of the spell. 

A stunned creature must make a Constitution saving throw at the end of each of its turns. On a successful save, this stunning effect ends.

#### Touch of Chaos
*Evocation cantrip*
___
- **Casting time:** 1 action
- **Range:** 120 feet
- **Components:** V, S
- **Duration:** Instantaneous
___
You launch a beam of raw chaos energy at a creature or object within range. Make a ranged spell attack against the target. On a hit, roll a d8 to determine the damage type it deals on the table below. Then roll 1d8 for damage.

d8 |Damage Type |d8 |Damage Type
---|------------|---|-----------
1  | Acid		| 5  | Lightning
2  | Cold		| 6 | Poison
3  | Fire		| 7 | Psychic
4  | Force		| 8 | Thunder

The spell creates more than one beam when you reach higher levels: two beams at 5th level, three beams at 11th level, and four beams at 17th level. You can direct the beams at the same target or at different ones. Make a separate attack roll and damage type roll for each beam.

<div class='footnote'>PART 2 | MAGIC</div>
