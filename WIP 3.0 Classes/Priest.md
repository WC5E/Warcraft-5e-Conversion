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

<div style='margin-top:370px;'></div>

## Priest
*It is faith in ourselves that separates us from others, and with our powers, we will cause great change in all of Azeroth. The weak will come to lean on you. The lepers will call you Lord. And the ignorant will look to you for guidance.*
<div style="text-align:Right"> 

*— Dark Cleric Duesten*  </div>

Bend down over her falling ally, a dwarf clutches her holy symbol, and begins to sing a slow melodic tune, holy light shining from her hand, covering her allies limp body.

Kneeling on the ground, one hand firmly grasping a staff, the other filled with swirls of divine and necrotic energies. A human raises, and sends out a thick halo of light and dark energy out around him, his allies gaining new life, his enemies feeling the rush of necrotic through their bodies.

A forsaken, surrounded in void energy pulls his holy symbol from his neck as void covers his body. Tentacles sprouting from his back, as he sends out a laughter, spew-ing bolts of necrotic energy towards enemies and allies.

Priests are the bridge between light and dark, they are the wielders of the warmth holy light of the divine, and the dark magic granted by shadows. They serve as protectors, healers, and casters of the dark forces of the universe

### Invokers of Light and Darkness
Priests are devoted to the spiritual, and express their unwavering faith by serving the people. For millennia they have left behind the confines of their temples and the comfort of their shrines so they can support their allies in war-torn lands. In the midst of terrible conflict, no hero questions the value of the priestly orders. These masters of the healing arts keep their companions fighting far beyond their normal capacities with an array of restorative powers and blessings. The divine forces at the priest’s command can also be turned against foes.

As light cannot exist without darkness, and darkness without light, some priests tap into shadow to better understand their own abilities, as well as the abilities of those who threaten them.

\columnbreak

<div style='margin-top:522px;'></div>

### Devoted Acolytes
Priests practice a complex, organized form of spirituality built around moral philosophy, the worship of a particular deity (such as Elune) in some cases, and/or idol worship, rather than around the reverence of the elements that shamans practice, or the close divine connection with animals and the wilderness that druids maintain. Priests serve not only as influential religious figures in their respective societies, but also as powerful practitioners of divine magic, which they use to heal and protect, or harm and weaken.

Devotion to the faiths of Azeroth leads many priests to the paths of courage and heroism. In dark times, priests carry the Light of faith with them as a reminder of the powerful forces at work beyond the comprehension of the peoples who walk the land. Powerful healers with an intimate connection to the divine, priests are empowered with abilities that aid them in times of dire need.

### Creating a Priest
Are you a devoted servant of good, loyal to the holy light?, a disciplined priest, in beautiful robes, monitoring a sept? or are you an unholy priest of shadows, fallen either by choice or forcefully towards the necrotic arts?

How did you enter priesthood? Were you raised in a mo-nastery? Did you hear a whisper from the light itself telling you to serve it? Or did a terrible war force you to take up the warmth of the holy light to assist your allies? Perhaps you might have known from your earliest memories that the priest's life was your calling, almost as if you had been sent into the world with that purpose stamped on your soul.

<div class='footnote'>PART 1 | CLASSES</div>
<img src='https://www.gmbinder.com/images/ydhgeyS.jpg' style='position:absolute; top:0px; right:0px; width:800px' />
<img src='https://www.gmbinder.com/images/vn90cy3.png' style='position:absolute; top:0px; right:-100px; width:900px' />
<img src='https://www.gmbinder.com/images/lyv4YVJ.png' style='position:absolute; top:-130px; right:-100px; width:600px' />

\pagebreakNum

<div class='classTable wide'>

##### The Priest 
|Level|Proficiency<br>Bonus|Devotions||Features|Cantrips<br>Known||1st||2nd||3rd||4th||5th||6th||7th||8th||9th <div style="position: absolute; top:100px; right:81px; width:200px; height:25px">—Spell Slots per Spell Level—</div>|
|:---:|:--:|:-:|-|:----------|:-:|-|:-:|-|:-:|-|:-:|-|:-:|-|:-:|-|:-:|-|:-:|-|:-:|-|:-:|
| 1st | +2 | —|| Divine Calling, Spellcasting                       |3||2||—||—||—||—||—||—||—||—|
| 2nd | +2 | 2|| Devotion, Divine Word, Divine Calling feature      |3||3||—||—||—||—||—||—||—||—|
| 3rd | +2 | 2|| —                                                  |3||4||2||—||—||—||—||—||—||—|
| 4th | +2 | 2|| Ability Score Improvement                          |4||4||3||—||—||—||—||—||—||—|
| 5th | +3 | 3|| Divine Word                                        |4||4||3||2||—||—||—||—||—||—|
| 6th | +3 | 3|| Divine Calling feature                             |4||4||3||3||—||—||—||—||—||—|
| 7th | +3 | 3|| —                                                  |4||4||3||3||1||—||—||—||—||—|
| 8th | +3 | 3|| Ability Score Improvement, Empowered Faith         |4||4||3||3||2||—||—||—||—||—|
| 9th | +4 | 4|| —                                                  |4||4||3||3||3||1||—||—||—||—|
| 10th| +4 | 4|| Divine Calling feature, Divine Word                |5||4||3||3||3||2||—||—||—||—|
| 11th| +4 | 4|| —                                                  |5||4||3||3||3||2||1||—||—||—|
| 12th| +4 | 4|| Ability Score Improvement                          |5||4||3||3||3||2||1||—||—||—|
| 13th| +5 | 5|| —                                                  |5||4||3||3||3||2||1||1||—||—|
| 14th| +5 | 5|| Divine Word                                        |5||4||3||3||3||2||1||1||—||—|
| 15th| +5 | 5|| —                                                  |5||4||3||3||3||2||1||1||1||—|
| 16th| +5 | 5|| Ability Score Improvement                          |5||4||3||3||3||2||1||1||1||—|
| 17th| +6 | 6|| Prodigy of Faith                                   |5||4||3||3||3||2||1||1||1||1|
| 18th| +6 | 6|| Divine Calling feature                             |5||4||3||3||3||3||1||1||1||1|
| 19th| +6 | 6|| Ability Score Improvement                          |5||4||3||3||3||3||2||1||1||1|
| 20th| +6 | 6|| Embrace Calling                                    |5||4||3||3||3||3||2||2||1||1|

</div>

    As guardians against forces of wickedness and evil, priests are rarely of any evil alignment. Most of them walk the paths of charity and soothing, or did you never feel the warmth of the holy light, and instead felt the calling of the old gods? their voidic magic wrapping around you, making your actions chaotic?


#### Quick Build
You can make a priest quickly by following these sugges­tions. First, Charisma should be your highest ability score, followed by Constitution.

#### Optional Rule: Multiclassing
If your group uses the optional rule on multiclassing in the *Player's Handbook*, here's what you need to know if you choose priest as one of your classes.

***Ability Score Minimum.*** As a multiclass character, you must have at least a Charisma score of 13 to take a level in this class, or to take a level in another class if you are already a priest.

***Proficiencies Gained.*** If priest isn't your initial class, here are the proficiencies you gain when you take your first level as a priest: one skill from the class's skill list.

***Spell Slots.*** Add your levels in the priest class to the appropriate levels from other class to determine your available spell slots.

## Class Features
As a priest, you gain the following class features
#### Hit Points
___
- **Hit Dice:** 1d6 per priest level
- **Hit Points at 1st Level:**  6 + your Constitution modifier
- **Hit Points at Higher Levels:** 1d6 (or 4) + your Constitution modifier per priest level after 1st
#### Proficiencies
___
- **Armor:** None
- **Weapons:** All simple weapons
- **Tools:** Herbalism kit

___
- **Saving Throws:** Wisdom, Charisma
- **Skills:** Choose two from History, Insight, Medicine, Persuasion, and Religion

#### Equipment
You start with the following equipment, in addition to the equipment granted by your background:
- *(a)* a mace or *(b)* a quarterstaff
- *(a)* a priest's pack or *(b)* an explorer's pack
- a holy symbol, herbalism kit, and two daggers

\pagebreakNum

<div style='margin-top:160px;'></div>

### Divine Calling
*1st-level priest feature*<br/>
<div style='margin-top:-4px;'></div>

Choose a divine calling, a path of priesthood that you have devoted yourself to: Discipline, Holy or Shadow, each calling is detailed at the end of the class description. Your choice grants you features when you choose it at 1st level and again at 2nd, 6th, 10th, and 18th level.

#### Calling Spells
Each calling has a list of associated spells. You gain access to these spells at the levels specified in the calling description. Once you gain access to a calling spell, you always have it prepared, and it doesn't count against the number of spells you can prepare each day.

If you gain a calling spell that doesn't appear on the priest spell list, the spell is considered a priest spell for you.

### Spellcasting
*1st-level priest feature*<br/>
<div style='margin-top:-4px;'></div>

As a conduit for divine power. you can cast priest spells. See chapter 10 of the Player's Handbook for the general rules of spellcasting and chapter 6 of this book for the priest spell list.

#### Cantrips
At 1st level, you know three cantrips of your choice from the priest spell list. You learn additional priest cantrips of your choice at higher levels, as shown in the Cantrips Known column of the Priest table.

#### Preparing and Casting Spells
The Priest table shows how many spell slots you have to cast your spells of 1st level and higher. To cast one of these spells, you must expend a slot of the spell's level or higher. You regain expended spell slots when you finish a long rest.

You prepare the list of priest spells that are available for you to cast, choosing from the priest spell list. When you do so choose a number of priest spells equal to your Charisma modifier + your priest level (minimum of one spell). The spells must be of a level for which you have spell slots.

For example, if you are a 3rd-level priest, you have four 1st-level and two 2nd-level spell slots. With a Charisma of 16, your list of prepared spells can include six spells of 1st or 2nd level, in any combination. If you prepare the 1st-level spell flash heal, you can cast it using a 1st-level or 2nd-level slot. Casting the spell doesn't remove it from your list of prepared spells.

You can change your list of prepared spells when you finish a long rest. Preparing a new list of priest spells requires time spent in prayer and meditation: at least 1 minute per spell level for each spell on your list.

\columnbreak

<div style='margin-top:160px;'></div>

#### Spellcasting Ability
Charisma is your spellcasting ability for your priest spells, since the power of your magic relies on your ability to project your will into the world. You use your Charisma whenever a priest spell refers to your spellcasting ability. In addition, you use your Charisma modifier when setting the saving throw DC for a priest spell you cast and when making an attack roll with one.

<div style="text-align: Center">

**Spell save DC** = 8 + your proficiency bonus + your Charisma modifier

**Spell attack modifier** = your proficiency bonus + your Charisma modifier

</div>

#### Ritual Casting
You can cast a priest spell as a ritual if that spell has the ritual tag and you have the spell prepared.

#### Spellcasting Focus
You can use a holy symbol as a spellcasting focus for your priest spells.

### Devotion
*2nd-level priest feature*<br/>
<div style='margin-top:-4px;'></div>

You can channel pure energy from your source of power, using that energy to fuel magical effects. You start with two such effects: a Divine Word of your choice and an effect determined by your calling. You learn an additional Divine Word at 5th, 10th, and 14th levels.

When you use your Devotion, you brandish your holy symbol and choose which effect, and can only use one Devotion option per turn. In addition, some Devotion effects require saving throws. When you use such an effect from this class, the DC equals your priest spell save DC.

You have two uses of Devotion, and regain all expended uses upon finishing a short or long rest. You gain additional uses of Devotion as you gain priest levels, as shown in the Devotions column of the Priest table.

#### Divine Words
The words are presented in alphabetical order.

***Barrier.*** When a creature within 60 feet of you that you can see is targeted for an attack, you may expend one use of Devotion as a reaction to impose disadvantage on the triggering attack, and all attack rolls against that creature till the start of their next turn. <!-- Also called Deflect --> 

***Beckon.*** When a creature would fail a saving throw to half damage from an area of effect, you can beckon them to you using your reaction, pulling them to a space 5 feet from you, and causing them to succeed on the save instead of fail it. 

***Chastise.*** As an action, you can spend one use of Devotion to chastise a creature you can see within 60 feet. That creature must succeed on a Wisdom saving throw or be incapacitated until the end of your next turn. <!-- Also called Bind --> 

<img src='https://wallpapercave.com/wp/wp3333372.jpg' style='position:absolute; top:-50px; right:0px; width:800px' />
<img src='https://www.gmbinder.com/images/3e9S91s.png' style='position:absolute; top:20px; right:0px; width:900px; transform:scaley(-1)' />

\pagebreakNum

    ***Control.*** As an action, you can spend one use of Devotion and target a creature you can see within 60 feet. The creature must succeed on a Wisdom saving throw or be charmed by you for 1 minute. If you or your companions do anything harmful to it, the effect ends. Once the effect ends, the creature doesn't knows it was charmed by you.

***Fortitude.*** When a creature you can see within 30 feet makes a saving throw against an effect, you can spend one use of Devotion as a reaction to give it advantage on the saving throw. If the triggering effect affects multiple creatures, you can give advantage to a number of them up to your Charisma modifier (minimum of one) with the same Devotion. <!-- Also called Protect --> 

***Pain.*** When a creature takes damage from one of your priest spell, or fails a saving throw against one of your priest spells, you may spend one use of Devotion as a bonus action to impose disadvantage on all the creature's attack rolls until the beginning of your next turn.

***Purify.*** As an action, you can spend one use of Devotion and target a creature you can see within 60 feet. If the creature is affected by a spell or condition that allows a saving throw to end its effects, they make another save, adding your proficiency bonus to the save.

***Rebuke.*** When a creature you can see within 60 feet hits you with an attack or harmful spell, you can spend a use of Devotion as a reaction to rebuke it. Before the end of your next turn, you have advantage on your next attack roll against the creature or give it disadvantage on the next saving throw it makes against a spell you cast.

***Sanctuary.*** As an action, you can spend one use of Devotion and target a creature you can see within 60 feet to ward them from harm. For 1 minute, all attacks against the target have disadvantage and the creature has advantage on saving throws against harmful spells. If the warded creature makes an attack or casts a spell that affects an enemy creature, this effect ends. <!-- Also called Fade --> 

***Shield.*** As an action, you can spend one use of Devotion to give one creature within 60 feet of you temporary hit points equal to your priest level plus your Charisma modifier. The temporary hit point last for 1 minute.

### Empowering Faith
*8th-level priest feature*<br/>
<div style='margin-top:-4px;'></div> 

Your faith further empowers your abilities. You choose one of the following benefits:

#### Unwavering Faith
When you make a concentration check, you can use your reaction to add your Charisma modifier to it. 

#### Power Infusion
You add your Charisma modifier to damage you deal with cantrips.

#### Divine Strike
You gain the ability to infuse your weapon strikes with divine energy. Once on each of your turns when you hit a creature with a weapon attack, you can cause the attack to deal an extra 1d8 radiant damage to the target. When you reach 14th level, the extra damage increases to 2d8.

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
Some priests pride themselves on pragmatism. They understand that light casts a shadow, that darkness is defined by light, and that true discipline stems from one’s ability to balance these opposing powers in services of a greater cause. While these priests possess many holy virtues to aid their allies, they also dabble in the dark art to debilitate their enemies.

##### Discipline Calling Spells
Priest Level| Spells
------------|-----------
1st |*cure wounds*, *inflict wounds*
3rd |*zone of truth*, *silence*
5th |*✦ divine star*, *vampiric touch*
7th |*mordekainen's private sanctum,* *otiluke's resilient sphere* 
9th |*dispel evil and good*, *wall of force*

#### Atonement
*1st-level priest feature*<br/>
<div style='margin-top:-4px;'></div>

Whenever you cast a spell of 1st level or higher that deals damage, you choose one creature you can see within 30 feet of you. That creature gains regain hit points equal to twice the spell's level. 

In addition, whenever you cast a spell of 1st level or higher that restores hit points, you choose one creature you can see within 30 feet of you. That creature takes radiant or necrotic damage (your choice) equal to twice the spell's level

You can use either effect of Atonement only once per casting of a spell. 

#### Twist of Fate
*1st-level priest feature*<br/>
<div style='margin-top:-4px;'></div>

As a reaction, when you or another creature you can see within 60 feet of you makes an ability check, attack roll, or saving throw is made, you can change the value rolled to a 10, this can be declared after the roll, but before success is determined.

\pagebreakNum

You can use this reaction a number of times equal to your proficiency bonus, and regain all expended uses upon finishing a long rest. 

#### Devotion: Pain Suppression
*2nd-level priest feature*<br/>
<div style='margin-top:-4px;'></div>

As an action, you expend a use of Devotion to grant a barrier to a friendly creature you can see within 60 feet of you. The barrier is invisible, and any bludgeoning, piercing, and slashing damage the target takes is reduced by 2 + your proficiency bonus. This effect last for 1 minute or until you are incapacitated or die. 

After you use this Devotion option, you cannot use it again until you finish a short or long rest, or unless you expend two uses of Devotion to use it again.

#### Spirit Shield
*6th-level priest feature*<br/>
<div style='margin-top:-4px;'></div>

Whenever a creature regains hit points from one of your priest spells or Atonement, they also gain a number of temporary hit points equal to your proficiency bonus. 

#### Rapture
*10th-level priest feature*<br/>
<div style='margin-top:-4px;'></div>

When you use a Devotion as an action, you can cast one of your Discipline Calling spells with a casting time of action as a bonus action that turn. In addition, for this casting of the spell, any Atonement damage or healing increases by an amount equal to half your priest level. 

#### Clarity of Will 
*18th-level priest feature*<br/>
<div style='margin-top:-4px;'></div>

When a creature gains the benefit of your Devotion: Pain Suppression, the creature now takes reduced damage from all sources. 

In addition, whenever a creature has temporary hit points granted from your priest class abilities or Spirit Shield, that creature gains advantage on saving throws against the charmed and frightened conditions and Wisdom saving throws. 

### Holy
The most adept priests leave their houses of worship to serve on the battlefield as shepherds to flock. There, they use their holy powers to bless allies and mend wounds. And while most stay behind the frontlines to aid their comrades, these holy champions are also capable of smiting foes and carrying out sacred justice. 

<img src='https://www.gmbinder.com/images/Jeyz36q.jpg' style='position:absolute; top:0px; right:-150px; width:700px; transform:scalex(-1)' />
<img src='https://www.gmbinder.com/images/E8GrMME.png' style='position:absolute; top:0px; right:-20px; width:900px' />

##### Holy Calling Spells
Priest Level| Spells
------------|-----------
1st |*bless*, *cure wounds*
3rd |*lesser restoration*, *✦ shining force*
5th |*beacon of hope*, *revivify*
7th |*death ward*, *aura of life*
9th |*mass cure wounds*, *raise dead*

\pagebreakNum

#### Echo of Light 
*1st-level priest feature*<br/>
<div style='margin-top:-4px;'></div>

Whenever you use a spell slot of 1st level or higher to restore hit points or to cast a beneficial spell onto a creature, that creature regains hit points at the start of your next turn equal to your proficiency bonus. 

#### Renew Faith 
*1st-level priest feature*<br/>
<div style='margin-top:-4px;'></div>

You learn the *calm emotions* spell and always have it prepared. In addition, you can cast this spell without expending a spell slot. When you do so, you can only target one creature with it, and in addition to the other effects of the spell, when a creature fails the saving throw, you can choose to learn one of the following things about the creature:
* One bond
* One value
* One hope
* One flaw

The creature does not become aware that you learn this information from them.

Once you cast *calm emotions* in this way, you cannot do so again until you finish a short or long rest. 

#### Devotion: Prayer of Mending
*2nd-level priest feature*<br/>
<div style='margin-top:-4px;'></div>

As an action, you can expend a use of Devotion to place a ward of mending onto a creature you can see within 30 feet of you for 1 minute. When that creature takes damage, they regain a number of hit points equal to 2d10 plus your priest level, and gain resistance to damage for the rest of that turn, including the triggering damage. In addition, The ward then immediately jumps to a friendly creature of your choice you can see within 30 feet of the first creature. If the second creature takes damage, they regain hit points equal 1d10 plus half your priest level. After the ward has restored hit points a second time, it disappears.

If the ward last for its full duration without restoring hit points, it restores hit points to the current creature by the amount it would as if it jumped (2d10 plus your priest level the first time, 1d10 plus half your priest level the second time)

At any time while the ward is up, you can use your bonus action to move the ward to another creature you can see within 30 feet of the warded creature. This does not trigger the healing or count as it jumping.

After you use this Devotion option, you cannot use it again until you finish a short or long rest, or unless you expend two uses of Devotion to use it again.

#### Holy Fire
*6th-level priest feature*<br/>
<div style='margin-top:-4px;'></div>

Whenever you restore hit points to a creature or cast a beneficial spell onto a creature, that creature is imbued with radiant power for 1 minute. The next attack that creature lands deals additional radiant damage equal to your Charisma modifier plus your proficiency bonus. 

\columnbreak

#### Symbol of Hope
*10th-level priest feature*<br/>
<div style='margin-top:-4px;'></div>

When you cast a Holy Calling spell that requires concentration, you can choose to cast another spell that also requires concentration, as long as that second spell is also a Holy Calling spell, concentrating on both spell as normal. When you make a concentration check while doing so, you do so with disadvantage, and if you lose concentration, you lose it for both spells. 

Once you do so, you cannot do so again until you finish a long rest. 

#### Guardian Spirit 
*18th-level priest feature*<br/>
<div style='margin-top:-4px;'></div>

A guardian spirit watches over your allies. When a creature within 60 feet of you and is friendly to you drops to 0 hit points, or is subjected to an effect that would make them die outright, such as the *power word kill* spell, you can use your reaction to summon a guardian spirit to them. The target is immediately returned to life and healed for half its hit point maximum. The target also gains immunity to all damage until the start of its next turn.

Once you use this feature, you can't use it again until you finish a long rest.

### Shadow
The brightest light casts the darkest shadow -- and from within this blackness, a rival power dwells. Shadow priests fully embrace this opposing polarity, their faith equally resolute as their holy counterparts. Like all priests, they dedicate much of their lives to worship - However, they dedicate it to Shadow magic and the void, setting themselves around the doctrines of decay and madness. 

##### Shadow Calling Spells
Priest Level| Spells
------------|-----------
1st |*cause fear*, *✦ dark void*
3rd |*mind flay*, *phantasmal force*
5th |*✦ void shift*, *vampiric touch*
7th |*evard's black tentacles* *✦ schism*
9th |*enervation ^XGE^*, *contagion*

#### Psychic Voice 
*1st-level priest feature*<br/>
<div style='margin-top:-4px;'></div>

You can form a telepathic connection between creatures of your choice you can see within 30 feet of you. Choose a number of creature you can see (including yourself), up to your proficiency bonus. The chosen creatures can speak telepathically with each other as long as they are on the same plane. To understand each other, the creatures must speak mentally in a language the other creature knows. 

The telepathic connection last for a number of minutes equal to your priest level, and once used, cannot be used again until you finish a short or long rest, or unless you expend a spell slot of 1st level or higher to use it again. 

\pagebreakNum

#### Mind Sear 
*1st-level priest feature*<br/>
<div style='margin-top:-4px;'></div>

Once on one of your turns as a bonus action, you can choose one creature affected by one of your priest spells or abilities. That creature, and all creatures of your choice within 5 feet of them must succeed on a Intelligence saving throw or take psychic damage equal to half your priest level. Any charmed or frightened creatures who take this damage takes an additional 1d6 psychic damage.

You can use this bonus action a number of times equal to your proficiency bonus, and regain all expended uses when you finish a long rest. 

#### Devotion: Shadowform 
*2nd-level priest feature*<br/>
<div style='margin-top:-4px;'></div>

You can expend one use of Devotion and enshroud your body in shadow energy as a bonus action. For one minute, you gain the following benefits: 
* You can't cast spells that restore hit points, unless it is one of your Shadow Calling spells. 
* You have advantage on Charisma (Intimidation) and Dexterity (Stealth) checks, but disadvantage on all other Charisma checks. 
* Once per turn, when you hit a creature with an attack, or a creature fails a saving throw from one of your priest spells, you can force them to succeed on a Charisma saving throw against your priest spell DC, or be frightened of you for 1 minute. They can reroll this saving throw at the end of each of their turns, ending this effect on a success. 

After you use this Devotion option, you cannot use it again until you finish a short or long rest, or unless you expend two uses of Devotion to use it again. 

#### Dark Thoughts
*6th-level priest feature*<br/>
<div style='margin-top:-4px;'></div>

Your mind is more riddled with shadowy thoughts. You gain resistance to psychic damage, and if you have your Shadowform active, you have advantage on saving throws you make to avoid or end early the charmed or frightened condition on yourself.

\columnbreak

#### Fortress of the Mind
*6th-level priest feature*<br/>
<div style='margin-top:-4px;'></div>

Your mind is more guarded to outside forces. You are immune to any magical effect that would read your thoughts or intentions, such as the *detect thoughts* spell, and Wisdom (Insight) check against you are made with disadvantage.  

Additionally, if a creature attempts to charm or frighten you and you succeed on the saving throw, you can use your reaction to force the creature to make the same saving throw, becoming charmed or frightened of you until the end of your next turn if they fail instead.  

#### Horrific Visions
*10th-level priest feature*<br/>
<div style='margin-top:-4px;'></div>

You learn how to invoke creature's deepest, darkest fears. When a creature starts their turn frightened or charmed by you, or while under the effect of one of your Shadow Calling spells, You can choose to have their movement halved and can only take either their action or their bonus action on that turn. 

####  Dark Absolution 
*18th-level priest feature*<br/>
<div style='margin-top:-4px;'></div>

Your body becomes more one with shadowy magic. While you have Shadowform active, you can move through creatures and objects as though they were difficult terrain. If you end your turn inside a creature's space or an object, you take 5 force damage. 

In addition, you can manipulate even the strongest of minds. If you would inflict the frightened or charmed conditions on a creature who would be immune, the creature is treated as if it is frightened or charmed for the purpose of your priest abilities, and gains disadvantage on ability checks while you are in their line of sight. 

<img src='https://www.gmbinder.com/images/u6EMR90.jpg' style='position:absolute; top:680px; right:0px; width:800px' />
<img src='https://www.gmbinder.com/images/L60ii4e.png' style='position:absolute; top:-160px; right:0px; width:1000px' />

\pagebreakNum

## Priest Spells 

<div class='spellList'>

##### Cantrips (0 Level)
- Guidance
- Light
- Mending
- ✦ Mind Blast
- Resistance
- Sacred Flame
- Spare the Dying
- Thaumaturgy
- Toll the Dead
- Virtue
- Word of Radiance

##### 1st Level
- ✦ Angelic Feather
- Arms of Hadar
- Bless
- Cause Fear
- Ceremony
- Charm Person
- Cure Wounds
- ✦ Dark Void
- Detect Evil and Good
- Detect Magic
- Detect Poison and Disease
- Gift of Gab
- Guiding Bolt
- Healing Word
- Heroism 
- ✦ Inner Fire
- Inflict Wounds
- ✦ Mind Vision
- Prot. from Evil and Good
- Purify Food and Drink
- Sanctuary
- Shield 
- Shield of Faith

##### 2nd Level
- Aid 
- Blindness/Deafness 
- Calm Emotions 
- Crown of Madness
- ✦ Exorcism
- ✦ Fade
- Gentle Repose 
- Healing Spirit 
- Hold Person 
- Invisibility
- ✦ Inner Focus
- ✦ Inner Will
- Lesser Restoration 
- Levitate
- ✦ Mind Flay 
- Mind Spike 
- Prayer of Healing 
- Protection from Poison 
- ✦ Shackle Undead 
- ✦ Shining Force 

\columnbreak

- Silence 
- Suggestion
- Tasha's Mind Whip

##### 3rd Level
- Animate Dead 
- Aura of Vitality 
- Beacon of Hope 
- Bestow Curse 
- Daylight 
- Dispel Magic 
- ✦ Divine Star 
- Enemies Abound
- Fast Friends
- Fear 
- Feign Death 
- Gaseous Form
- Glyph of Warding 
- Hunger of Hadar 
- ✦ Holy Nova 
- Intellect Fortress 
- Life Transference 
- Magic Circle 
- Mass Healing Word
- Motivational Speech 
- Protection from Energy
- ✦ Psychic Horror
- Remove Curse 
- Revivify 
- Speak with Dead 
- Spirit Guardians 
- Tongues 
- Vampiric Touch
- ✦ Void Shift

##### 4th Level
- Aura of Purity 
- Banishment
- Charm Monster
- Death Ward
- ✦ Devouring Plague
- Divination
- Freedom of Movement
- Greater Invisibility
- Guardian of Faith
- Locate Creature
- ✦ Luminous Barrier
- Phantasmal Killer
- Raulothim's Psychic Lance
- Sickening Radiance
- Shadow of Moil
- ✦ Shadowy Apparitions
- ✦ Summon Void Being

##### 5th Level
- Dawn
- Dispel Evil and Good 
- Dominate Person
- Geas
- Greater Restoration
- Hallow
- Legend Lore
- Mass Cure Wounds
- Modify Memory
- Negative Energy Flood
- Raise Dead
- Rary's Telepathic Bond
- Scrying
- ✦ Shadow Crash
- Skill Empowerment 
- Synaptic Static
- Wall of Light 

##### 6th Level
- ✦ Archangel
- Eyebite
- Find the Path
- Harm
- Heal
- ✦ Mass Dispel
- Mass Suggestion
- Mental Prison
- ✦ Schism
- True Seeing
- Word of Recall

##### 7th Level
- Divine Word
- Etherealness
- ✦ Halo 
- Regenerate
- Resurrection
- Symbol
- Temple of the Gods
- Tether Essence

##### 8th Level
- Abi-Dalzim's Horrid Wilting
- Antimagic Field
- Dark Star 
- Dominate Monster
- Feeblemind
- Holy Aura
- Maddening Darkness
- Mind Blank
- Power Word Stun

##### 9th Level
- ✦ Apotheosis
- Foresight
- Mass Heal
- Power Word Heal
- Power Word Kill
- Psychic Scream
- ✦ Salvation
- True Resurrection

\columnbreak

##### Alternative Spell Names
| 5e Spell  | Wc5e Name  |
|:---:|:-----------:|
| Dominate Person | Mind Control | 
| Hallow | Sanctified Ground |
| Holy Aura | Dome of Light |
| Prot from Evil and Good  | Holy Ward  |
| Tether Essence | Psychic Link |
| Skill Empowerment  | Enlightenment |
| Synaptic Static  | Mind Bomb |
| Sacred Flame  | Smite |
| Arms of Hadar  | Shadow Nova |
| Healing Spirit  | Lightwell |
| Life Transference  | Dark Mending |
| Aura of Vitality  | Divine Hymn |
| Hunger of Hadar  | Searing Nightmare |
| Sickening Radiance  | Purge the Wicked |
| Shadow of Moil  | Shadow Covenant  |
| Raulothim's Psychic Lance | Void Bolt |
| Heroism | Fear Ward | 

</div>

<img src='https://www.gmbinder.com/images/uvgcKzs.jpg' style='position:absolute; top:750px; right:-250px; width:700px; transform:scalex(-1)' />
<img src='https://www.gmbinder.com/images/E8GrMME.png' style='position:absolute; top:50px; right:-100px; width:900px' />
<img src='https://www.gmbinder.com/images/L60ii4e.png' style='position:absolute; top:-100px; right:0px; width:1000px' />

\pagebreakNum

## Spells  

#### Angelic Feather
*2nd-level enchantment*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S, M (a feather)
- **Duration:** Concentration, up to 1 minute
___
You touch one creature within reach, granting it the swiftness of an angelic being. For the duration of the spell, the creature can take the Dash and Disengage action as a bonus action on its turn, and gains resistance to fall damage.

#### Apotheosis
*9th-level transmutation*
___
- **Casting Time:** 1 action
- **Range:** Self
- **Components:** V, S
- **Duration:** Concentration, up to 10 minutes
___
You enter a pure Holy form, shining bright light in a 40-foot radius and dim light for an additional 40 feet for the spell’s duration. Until the spell ends, you gain the following benefits:

* You are immune to radiant damage and have resistance to necrotic damage.
* Aberrations, elementals, fey, fiends, and undead have disadvantage on attack rolls against you.
* You gain a flying speed of 60 feet as spectral wings appear on your back.
* Any creature that moves within 10 feet of you for the first time on a turn or ends its turn there takes 2d10 radiant damage, and must succeed on a Constitution saving throw or be blinded until the end of your next turn.
* You can use your action to create a line of holy radiance 30 feet long and 10 feet wide extending from you in a direction you choose. Each creature in the line must make a Constitution saving throw. A creature takes 8d8 radiant damage and is blinded until the end of your next turn on a failed save, or half as much damage and suffering no additional effects on a successful one.
* You can use an action to touch a creature with healing light. The creature regains 8d8 hit points.

#### Archangel
*6th-level transmutation*
___
- **Casting Time:** 1 bonus action
- **Range:** Self
- **Components:** V, S, M (an object engraved with a a symbol of the Light or Void, worth at least 500 gp)
- **Duration:** Concentration, up to 1 minute
___
You mutter a prayer invoking the powers of the Light or Shadow to aid your cause. You gain the following benefits until the spell ends: 
* You are immune to fire and radiant damage (Light) or psychic and necrotic damage (Shadow)
* You are immuned to the charmed condition (Light) or the frightened condition (Shadow)
* You grow spectral wings, gaining a fly speed of 40 feet. 
* You can add your spellcasting modifier to spells that restore hit points (Light) or spells that deal damage (Shadow). The priest also regains hit points equal to half the healing or damage done on one target of the spell's casting. 
* You can cast cantrips with a casting time of 1 action as a bonus action instead. 

#### Dark Void
*1st-level evocation*
___
- **Casting Time:** 1 action
- **Range:** 30 feet
- **Components:** V, S, M (a holy symbol)
- **Duration:** Instantaneous
___
You grasp the fabric around a target within range, pulling necromantic energies from it and creatures of your choice within 5 feet of it. A target must make a Constitution saving throw, taking 2d6 necrotic damage on a failed save, or half as much damage on a successful one. A creature who fails this saving throw also can’t regain hit points for 1 round. 

**At Higher Levels.** When you cast this spell using a spell slot of 2nd level or higher, the damage increases by 1d6 for each slot level above 1st.

#### Devouring Plague
*4th-level necromancy*
___
- **Casting Time:** 1 Action
- **Range:** 60 feet
- **Components:** V, S, M (a drop of bone marrow)
- **Duration:** 1 minute
___
Choose a creature that you can see within range. The target must succeed on a Constitution saving throw or be affected by a horrible disease for the spell's duration. Until the spell ends, whenever the affected creature is hit by you, or fails a saving throw against your spell, it takes 2d8 necrotic damage.

Additionally, if the affected creature is reduced to 0 hit points, you can spend and roll two of your unspent Hit Dice and regain a number of hit points equal to the roll plus your spellcasting ability modifier.

Since this spell induces a natural disease in its target, any effect that removes a disease or otherwise ameliorates a disease's effects apply to it. 

**At Higher Levels.**  When cast with a spell slot of 3rd level or higher, the necrotic damage increases by 1d8, and The number of Hit Dice that can be spent and added to the healing roll increases by one for each slot above 2nd. 

#### Divine Star
*3rd-level evocation*
___
- **Casting Time:** 1 action
- **Range:** self (30-foot line)
- **Components:** V, S
- **Duration:** Instantaneous
___
A star of divine energy streaks forward in a 30 feet long and 5 feet wide line from you in a direction you choose. Each friendly creature in the stars path regains 2d8 hit points, and each hostile creature must make a Dexterity saving throw, taking 3d8 radiant damage on a failed save, or half as much damage on a successful one.

**At Higher Levels.** When you cast this spell using a spell slot of 4th level or higher, the spells healing and damage increases by 1d8 for each slot level above 3rd.

\pagebreakNum

#### Exorcism
*2nd-level evocation*
___
- **Casting Time:** 1 action
- **Range:** 30 feet
- **Components:** V,S,M (a flask of holy water, which this spell consumes)
- **Duration:** Instantaneous 
___
You call upon holy forces to harm unholy creatures. Make a ranged spell attack against a creature in range, and on a hit, they take 3d8 radiant damage. Additionally, if that creature is an aberration, fiend, or undead, they take 2d8 additional radiant damage.

If the target is possessed or charmed by an aberration, fiend, or undead, only the possessing or charming creature takes the damage if they are in range of the spell, and the target can reroll against possession or charmed effect with advantage.

**At Higher Levels.** When you cast this spell using a spell slot of 3rd level or higher, you deal an additional 1d8 radiant damage, for each slot level above 2nd.

#### Fade 
*2nd-level illusion*
___
- **Casting Time:** 1 reaction, upon taking a hit from an attack
- **Range:** self
- **Components:** V,S
- **Duration:** 1 round
___
You fade from people's views, becoming invisible until the end of your next turn. This invisibility ends early if you attack, cast a spell, or force a creature to make a saving throw. 

#### Halo
*7th-level evocation*
___
- **Casting Time:** 1 action
- **Range:** Self (60-foot radius)
- **Components:** V, S
- **Duration:** Instantaneous
___
You spread your hands, creating a burst of divine energy that ripples outward from you. You choose to create either Light or Shadow halo.

**Light.** Each creature within 60 feet of you are washed over by wave of holy energy. Hostile creatures must succeed on a Constitution saving throw or take 6d6 radiant damage, and allied creatures regain 6d6 hit points. A creature that succeeds on its saving throw takes half as much damage.

**Shadow.** Each creature you choose within 60 feet of you are struck by wave of shadow energy. They must succeed on a Constitution saving throw or take 6d6 necrotic damage, as well as 6d6 psychic damage. A creature that succeeds on its saving throw takes half as much damage.

If there is 50 feet or more between you and a creature when you cast this spell, that creature makes the saving throw with disadvantage.

\columnbreak

#### Holy Nova
*3rd-level evocation*
___
- **Casting Time:** 1 action
- **Range:** Self (15-foot radius)
- **Components:** V,S
- **Duration:** Instantaneous
___
You release a burst of holy energy in a 15-foot radius circle around you. All friendly creature regain 3d6 hit points, while all hostile creatures must make a Constitution saving throw, taking 4d6 radiant damage on a failed save or half as much on a success. Aberrations, fiends, undead make this saving throw with disadvantage. 

**At Higher Level.** When you cast this spell with a spell slot of 4th level or higher, The healing and damage done increases by 1d6 for each slot level above 3rd. 

#### Inner Fire
*1st-level abjuration*
___
- **Casting Time:** 1 action
- **Range:** Self
- **Components:** V,S
- **Duration:** 8 hour
___ 
You are protected by your faith and convictions. While unarmored, your base AC becomes 11 + your spellcasting modifier, and you gains advantage on saving throws against and to end early the frightened condition. The spell ends early if you don armor. 

#### Inner Focus 
*2nd-level abjuration*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V,S
- **Duration:** 1 hour
___
You touch a willing creature and amplify their focus through their convictions. The next ability check the creature makes while affected by this spell is empowered, adding your spellcasting modifier to it, upon which this spell ends. 

#### Inner Will
*2nd-level abjuration*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V,S
- **Duration:** 1 hour
___ 
You touch a willing creature and bolster their will through their convictions. The target adds your Wisdom modifier to its own while making Wisdom saving throws. This effect lasts for duration or until the target passes a Wisdom Saving throw it would have otherwise failed.

\pagebreakNum

#### Luminous Barrier
*4th-level abjuration*
___
- **Casting Time:** 1 action
- **Range:** self (15-foot radius)
- **Components:** V, S
- **Duration:** Concentration, up to 1 minute
___
You manifest a dome of brilliant light around you to protect your allies and hinder your foes. Until the spell ends, the dome moves with you, centered on you. Any friendly creature within this dome gain a +2 bonus to AC from spell attacks, spell attack rolls made against them that originate from outside the dome are made with disadvantage, and if the creature would take damage from a weapon attack, they take 3 less damage. 

**At Higher Levels:** When you cast this spell using a spell slot of 5th level or higher, the damage reduction increases by 1 for each slot level above 4th. 

#### Mind Blast
*Evocation cantrip*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** Instantaneous
___
You attempt to pierce through the mental defenses of a creature you can see within range. The target must succeed on a Wisdom saving throw or take 1d8 psychic damage. If this damage would prompt a concentration check, that check is made with disadvantage.

This spell's damage increases by 1d8 when you reach 5th level (2d8), 11th level (3d8), and 17th level (4d8).

#### Mass Dispel
*6th-level abjuration*
___
- **Casting Time:** 1 action
- **Range:** 90 feet
- **Components:** V, S
- **Duration:** Instantaneous
___
Choose a 15-foot radius sphere within range. Any spell of 3rd level or lower on the target ends. For each spell of 4th level or higher on the target, make an ability check using your spellcasting ability. The DC equals 10 + the spell’s level. On a successful check, the spell ends.

***At Higher Levels:*** When you cast this spell using a spell slot of 7th level or higher, you automatically end the effects of a spell on the target if the spell's level is equal to or less than the level of the spell slot you used minus 3.

\columnbreak

#### Mind Flay
*2nd-level enchantment*
___
- **Casting Time:** 1 action
- **Range:** 120 feet
- **Components:** V
- **Duration:** Concentration, up to 1 minute
___
You wreathe the mind of a creature you can see within range. The target must make a Wisdom saving throw. On a failed save, the creature takes 2d6 psychic damage or half as much on a successful one. 

In addition to the damage, a creature who failed the saving throw has disadvantage on all attack rolls and ability checks for the spells duration. At the end of each of its turns, the creature can reroll the Wisdom saving throw, ending this effect on a success.

***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, the damage increases by 1d6 for each slot level above 2nd.

#### Mind Vision
*1st-level divination*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S
- **Duration:** Concentration, up to 1 hour
___
You extend your arm and touch a willing creature within reach. For the duration of the spell, you see through the creatures eyes and hear what it hears. During this time, you lose of your own senses and are considered blinded, deafened, and stunned. You can end your mind vision as a free action on your turn.

#### Psychic Horror 
*3rd-level illusion*
___
- **Casting Time:** 1 action
- **Range:** Self
- **Components:** V, S
- **Duration:** Concentration, up to 1 minute
___
You project a phantasmal current of fear all around you, creating a blast of mental energy. Each creature within a 15-foot radius sphere centered on you must succeed on a Wisdom saving throw or drop whatever they are holding and become frightened for the duration. While frightened, the creature can only use the Dash action to move away from you by the safest route available to it unless there is nowhere to move. If the creature ends its turn in a location where it does not have line of sight to you, they can make a Wisdom saving throw. On a successful save, the spell ends for that creature.

If the creature was already frightened and failed the save, they are also stunned while they remained frightened, or until the take damage. 

<img src='https://www.gmbinder.com/images/dlh3o9V.jpg' style='position:absolute; top:800px; right:0px; width:800px' />
<img src='https://www.gmbinder.com/images/L60ii4e.png' style='position:absolute; top:0px; right:0px; width:1000px' />

\pagebreakNum

#### Salvation
*9th-level abjuration*
___
- **Casting Time:** 1 action
- **Range:** Self (60-foot radius)
- **Components:** V, S, M (a teardrop of desperation)
- **Duration:** 1 round
___
You emit holy radiance in a 60-foot radius. Each creature of your choice within range is immune to all damage until the spell ends. Creatures targeted by this spell are also cured of any effect making them incapacitated, stunned, paralyzed or petrified. 


#### Schism 
*6th-level enchantment*
___
- **Casting time:** 1 action
- **Range:** 30 feet
- **Components:** V, S
- **Duration:** 1 round
___
You attack a creature's soul with dark energy. Choose a creature within range. The target must make a Charisma saving throw, taking 8d6 psychic damage on a failed save, or half as much on a successful save. On a failed save, the creature is cursed for the duration. The next time you or an ally of yours hits the cursed creature with an attack, the creature has vulnerability to all of that attack's damage, and then the curse ends.

#### Shackle Undead
*2nd-level enchantment*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S, M (a short piece of chain)
- **Duration:** 1 minute
___
Choose an undead creature that you can see within range. The target must succeed on a Wisdom saving throw or be stunned for the duration or until it takes damage. At the end of each of its turns, the target can make a new Wisdom saving throw. On a success, the spell ends on the target.

***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, you can target on additional creature for each slot level above 2nd. The creatures must be within 30 feet of each other when you target them.

#### Shadow Crash
*5th-level necromancy*
___
- **Casting Time:** 1 action
- **Range:** 120 feet
- **Components:** V, S
- **Duration:** Instantaneous
___
Shadow energy drips from your palm as you pull it towards the ground and blanket a point that you can see within range in darkness. Each creature in a 20-foot-radius sphere centered on that point must make a Constitution saving throw. A creature takes 4d8 necrotic damage and 4d8 psychic damage on a failed save, or half as much damage on a successful one. The darkness spreads around corner and the area of the spell is heavily obscured by magical darkness until the end of your next turn.

***At Higher Levels.*** When you cast this spell using a spell slot of 6th level or higher, the damage increases by 1d8 for each slot level above 5th.

\columnbreak

#### Shadowy Apparitions 
*4th-level conjuration*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** Concentration, up to 1 minute
___
You manipulate the shadows around you, sending apparition to haunt your enemy. You create three Medium shadowy apparitions to an unoccupied spaces within 10 feet of you. Choose a target within range for each apparition. Each apparition can have the same or different target. At the end of each of your turns, your shadowy apparitions move 20 feet towards the target, moving through creatures and obstacles, and ignoring any difficult terrain.

Whenever an apparition is in the same space as another creature, it explodes, forcing that creature to make an Intelligence saving throw, taking 8d6 psychic damage on a failed save, or half as much on a successful one. A creature who fails this saving throw also has their movement speed reduced to 0 till the start of their next turn. 

After losing concentration on this spell, all apparitions still present last for 1 round. 

**At Higher Levels:** When you cast this spell using a spell slot of 5th level or higher, the apparitions do an additional 1d6 psychic damage for each slot level above 4th. 


#### Shining Force
*2nd-level abjuration*
___
- **Casting Time:** 1 action
- **Range:** 30 feet
- **Components:** V, S
- **Duration:** Concentration, up to 1 minute
___
Bright light bursts out from a creature you can see within range, pushing away hostile creatures. Each creature of your choice within a 10-foot-radius of the target must succeed a Dexterity saving throw, or be pushed 10 feet away from the target and be knocked prone. For the duration of the spell, you can use your action to burst the shining force from the chosen creature again.

\pagebreakNum

#### Summon Void Being
*4th-level conjuration*
___
- **Casting Time:** 1 action
- **Range:** 90 feet
- **Components:** V, S, M (an eyeball contained in a vial worth at least 400 gp)
- **Duration:** Concentration, up to 1 hour 
___
You call forth a creature from the Void. It manifests physically in an unoccupied space that you can see within range. This corporeal form uses the Void Spirit stat block. When you cast the spell, choose  Mindbender, Psyfiend, or Shadowfiend. The creature resembles the creature of your choice and determines certain traits in its stat block. The creature disappears when it drop to 0 hit points or when the spell ends.

The creature is an ally to you and your companions. In combat, the creature shares your initiative count, but it takes its turn immediately after your. It obeys your verbal commands (no action required by you). If you don’t issue any, it takes the Dodge action and it uses its move to avoid danger.

**At Higher Levels.** When you cast the spell using a spell slot of 5th level or higher, use the higher level wherever the spell’s level appears on the stat block.

#### Void Shift
*3rd-level necromancy*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** Instantaneous
___
You call upon the void to shift the health of you and another creature. Choose a willing creature within range, you and the chosen creature exchange your current hit points, to a maximum of 40 hit points from each creature. This spell has no effect on a creature who is incapacitated or at 0 hit points.

***At Higher Levels.*** When you cast this spell using a spell slot of 5th level or higher, the maximum hit points you can exchange increases by 10 for each slot level above 4th.
___
> ## Void Being
>*Medium Aberration*
> ___
> - **Armor Class** 11 + the spell's level
> - **Hit Points** 40 + 10 for each spell level above 3rd
> - **Speed** 30 ft.. fly 40 ft.(Mindbender only; hover)
>___
>|STR|DEX|CON|INT|WIS|CHA|
>|:---:|:---:|:---:|:---:|:---:|:---:|
>|14(+2)|11(+0)|13(+1)|4(-3)|14(+2)|16(+3)|
>___
> - **Damage Resistances** necrotic, psychic
> - **Condition Immunities** charmed, frightened  
> - **Senses** darkvision 120 ft. , passive Perception 
> - **Languages** understands the language you speak
> - **Proficiency Bonus:** Your proficiency bonus
>
> - **Challenge** -
> ___
> ### Actions
> ***Multiattack.*** The aberration makes a number of attacks equal to half this spell's level, 
>
> ***Bite (Shadowfiend Only).*** *Melee Weapon Attack:* your spell attack modifier to hit, reach 5 ft., one creature. *Hit:* 1d8 + 3 + the spell's level piercing damage, and if the target is a creature, it must succeed on a Constituation saving throw against your spell DC or be poisoned till the start of the aberration's next turn. 
>
>
> ***Tentacle (Mindbender Only).*** *Melee Weapon Attack:* your spell attack modifier to hit, reach 5 ft., one creature. *Hit:* 1d8 + 3 + the spell's level bludgeoning damage. If the target is a Large creature or smaller, it is grappled (escape DC 16); however, the target's speed is not reduced to 0. Until the grapple ends, the aberration shares space with it, the target is blinded, and the aberration can't use its tentacles on another target without ending the grapple. 
>
> ***Psyflay (Psyfiend Only).*** *Ranged Spell Attack:* your spell attack modifier to hit, range 30 ft., one creature. *Hit:* 1d8 + 3 + The spell's level psychic damage. If the target is a creature, it can't regain hit points until the start of the aberration's next turn. 

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

\columnbreak 

## Art Credit 

Page 1 
Page 1 
Page 3 
Page 5 
Page 7 
Page 8 
Page 11
