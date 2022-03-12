<style>.phb{width : 210mm;height : 296.8mm;} .phb:after {content: "";} </style>
<style>.phb hr+section blockquote { padding-left: 0px; padding-right: 0px; }</style>
<style>.phb blockquote { padding-left: 0px; padding-right: 0px; }</style>
<style> .phb blockquote { margin-top: 1em; } </style>


<style>

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
  don't show a background. Used for the appendix creatures */
  .phb:nth-of-type(n+0):nth-of-type(-n+100) hr+section blockquote {
    background: none;
    border: none;
    box-shadow: none;
    margin-top: 12px;
    margin-bottom: 12px;
    padding-top: 6px;
    padding-bottom: 6px;
  }
  
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

/* BACK PAGE STYLES */

  /* Remove footer from back page, replace pX with last page num */
  .phb#p19:after { display:none; }

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

lore texts

https://docs.google.com/document/d/1rNnevflfdwQoteEfr1rf26ngk_JOIbaLgabbzq4jK5U/edit

___
> ## Bone Golem <!-- https://wc5e-cr-calculator.frogvall.com/?1;16;75;8;12;28;7;0;0;0;0;0;0;0;0;0;0;1;;;;3;;;;;;;;;;1;;;;;;;;10;;;;;;;2;2;1;3; -->
> *Medium construct (undead), neutral evil*
> ___
> - **Armor Class** 16 (natural armor)
> - **Hit Points** 75 (10d8 + 30)
> - **Speed** 30 ft.
> ___
> STR | DEX | CON | INT | WIS | CHA
>|:---:|:---:|:---:|:---:|:---:|:---:|
> 21 (+5)|11 (+0)|17 (+3)|2 (-4)|8 (-1)|5 (-3)|
> ___
> - **Damage Resistances** bludgeoning, piercing, and slashing from nonmagical attacks that aren't adamantine
> - **Damage Immunities** necrotic, poison
> - **Condition Immunities** charmed, exhaustion, frightened, poisoned
> - **Senses** darkvision 60 ft., passive Perception 9
> - **Languages** understands the languages of its creator but can't speak
> - **Challenge** 5 (1,800 XP) <!-- Proficiency Bonus +3 -->
> ___
>
> ***Immutable Form.*** The bone golem is immune to any spell or effect that would alter its form.
>	
> ### Actions
> ***Multiattack.*** The bone golem makes two melee attacks, or three melee attacks if it has half of its hit points or fewer.
>
> ***Bone Scythe.*** *Melee Weapon Attack:* +8 to hit, reach 5ft., one target. *Hit:* 14 (2d8 + 5) slashing damage.
>
> ***Bone Spike.*** *Ranged Weapon Attack:* +8 to hit, range 20/60 ft, one target. *Hit:* 22 (5d6 + 5) piercing damage.

<img src='https://static.wikia.nocookie.net/wowpedia/images/7/72/Skeletal_Flayer.jpg' style='position:absolute; top:00px; right:00px; width:200px;' />

Nothing is left to waste in the Scourge. A creation from the dark Scholomance, the bone golems are pieced together from remnants of skeletons too misshapen to use elsewhere, grafted with a pair of immense metal scythes. They are built solely to kill, and are deployed sparingly by their masters, perhaps owing to their unreliability, or tendency to rust.

\columnbreak

https://wow.gamepedia.com/Bone_golem#/media/File:Skeletal_Flayer.jpg

\pagebreakNum

<br/>

\columnbreak

Among the most distressing and intimidating of the Lich King’s minions is the gigantic bone wraith, a skeletal guard of immense size and haunting appearance. Looking almost angelic with wings of bone, it is crafted from the much-suffering remnants of many bodies, all pushed together into a shape not remotely humanoid. They drift legless above the ground, with four skulls at the centre of a torso, and freakish arms wielding an axe made of yet more bone. The souls of these dead have been amalgamated together into something far lesser than the sum of its parts, able only to proclaim loyal battlecries in the name of its master.

**Bone Storm!** The signature strength of these creatures is their ability to spin their many-limbed bodies at extreme, rapid speed, flailing their spiny wing-like protrusions out alongside their bony weapon. A guttural call will invariably accompany this assault, placing the bone storm into a legend among those who survive it.

<img>https://wow.gamepedia.com/Bone_wraith#/media/File:Bone_Guard_Boss_Concept.jpg</img>

<img src='https://static.wikia.nocookie.net/wowpedia/images/9/97/Bone_wraith.png' style='position:absolute; top:100px; left:50px; width:200px;' />


<div class='statblock-bottom-wide'>

___
___
> ## Bone Wraith <!-- https://wc5e-cr-calculator.frogvall.com/?3;17;188;13;12;112;56;63;56;72;56;0;0;0;0;0;0;1;;;1;4;;;;;;;;;1;3;1;;;;;;;10;;;;;;;2;2;1;3; -->
> *Huge construct (undead), chaotic evil*
> ___
> - **Armor Class** 17 (natural armor)
> - **Hit Points** 188 (13d12 + 104)
> - **Speed** 30 ft.
> ___
> STR | DEX | CON | INT | WIS | CHA
>|:---:|:---:|:---:|:---:|:---:|:---:|
> 26 (+7)|14 (+2)|27 (+8)|8 (-1)|13 (+1)|7 (-2)|
> ___
> - **Saving Throws** Str +13, Con +14, Wis +7, Cha +4
> - **Skills** Insight +7, Intimidation +10, Perception +7
> - **Damage Resistances** bludgeoning, piercing, and slashing from nonmagical attacks that aren't adamantine
> - **Damage Immunities** necrotic, poison;
> - **Condition Immunities** charmed, exhaustion, frightened, poisoned
> - **Senses** darkvision 90 ft., passive Perception 22
> - **Languages** the languages of its creator
> - **Challenge** 18 (20,000 XP) <!-- Proficiency Bonus +6 -->
> ___
>	
> ***Bone Storm.*** At the start of each of the bone wraith's turns, each creature within 10 feet of it takes 7 (2d6) slashing and 7 (2d6) necrotic damage.
>
> ***Legendary Resistance (3/Day).*** If the bone wraith fails a saving throw, it can choose to succeed instead.
>
> ***Magic Resistance.*** The bone wraith has advantage on saving throws against spells and other magical effects.
>
> ***Magic Weapons.*** The bone wraith's weapon attacks are magical.
>
> ***Three Heads.*** The bone wraiths has advantage on Wisdom (Perception) checks and on saving throws against being blinded, charmed, deafened, frightened, stunned, and knocked unconscious.
>
> ### Actions
> ***Multiattack.*** The bone wraith uses its Graveyard Spike and then makes two melee weapon attacks.
>
> ***Bone Axe.*** *Melee Weapon Attack:* +13 to hit, reach 15ft., one target. *Hit:* 26 (3d12 + 7) slashing damage.
>
> ***Bone Slice.*** *Melee Weapon Attack:* +13 to hit, reach 10ft., up to three targets. *Hit:* 13 (1d12 + 7) slashing damage.
>
> ***Graveyard Spike.*** A medium sized spike of bone raises from the ground within 60 ft. of the bone wraith. A creature in the same space must make a DC 19 Dexterity save or take 11 (2d8 + 2) piercing damage and be restrained. A restrained creature can use an action to try to break free by succeeding on a DC 19 Strength (Athletics) or Dexterity (Acrobatics) check. While restrained in this way, a creature takes 9 (2d8) piercing damage at the start of each of the bone wraith's turns. On a successful save the creature takes half damage and is not restrained.
>
> ***Coldflame (Recharge 5-6).*** The bone wraith exhales an icy blast in a 90-foot line that is 5 feet wide. Each creature in that area must make a DC 19 Constitution saving throw, taking 56 (12d8) cold damage on a failed save, or half as much damage on a successful one.
>
> ### Legendary Actions
> The bone wraith can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature’s turn. The bone wraith regains spent legendary actions at the start of its turn.
>
> ***Bone Storm.*** Any creature within the bone wraith's bone storm aura must make a DC 19 Dexterity saving throw or take 7 (2d6) slashing and 7 (2d6) necrotic damage.
>
> ***Detect.*** The bone wraith makes a Wisdom (Perception) check.
> 
> ***Spine Attack (Costs 2 Actions).*** The bone wraith strikes its spinal wing towards a creature. Melee Weapon Attack: +13 to hit, reach 15 ft., one target. Hit: 23 (3d10 + 7) piercing damage and the target must succeed on a DC 19 Strength check or be grappled (escape DC 19). Until this grapple ends, the target is restrained. The bone wraith can have maximum two creatures grappled this way.


</div>

\pagebreakNum



As the ruler of the damned, the Lich King naturally needed an elite caste of knights. These undead knights are granted immense power over death magic, cruel rune-inscribed blades that drain the lives of their foes, and command over appreciable portions of the Scourge’s armies. Intelligent and retaining their living personalities, albeit warped and broken into servitude, Death Knights became the feared top level of the Lich King’s armies, elites that acted as royal guard to the Lich King.

**Wartime Progenitors.** The creation of orcish Death Knights by the original Horde preceded the undead champions of the Scourge, but there is little relation. The Lich King took a particular effort to take the concept and work it further, changing them from a mismatching of orcish spirit to human corpse, into a powerful new brand of undead far greater than any before it.

**Faded Light.** The second generation of Death Knights were created during the fall of Lordaeron at the hands of the first in their ranks, Prince Arthas Menethil. Following him, others were raised from the corpses of previously pious and loyal paladins, their powers warped and reversed  - healing became harm, protection became degradation, and resurrection became the raising of loyal undead. Wielding cursed runeblades and riding the skeletal remains of their loyal steeds, these knights marked the new age of the modern Scourge.

**Fallen Heroes.** The third generation, spawned exclusively to destroy champions of the Light, were far more industrial; hordes of corpses were raised, placed in identical armour, and put through intense trials. Relatively few survived, and those left became a new army of lesser elites, less powerful but more reliable than the previous generation - at least, until thousands of them broke free from their master’s command, and swore to destroy him.
 
\columnbreak

https://wowpedia.fandom.com/wiki/Death_knight
something from the hearthstone section

<div class='statblock-bottom-wide'>

___
___
> ## Death Knight <!-- https://wc5e-cr-calculator.frogvall.com/?2;20;256;10;12;54;35;0;0;0;0;0;0;0;0;0;0;;;;1;3;;;;;;;;;;3;1;;;;;;;10;;;;;;;2;2;1;3; -->
> *Medium undead, chaotic evil*
> ___
> - **Armor Class** 20 (Plate, Shield)
> - **Hit Points** 256 (27d8 + 135)
> - **Speed** 30 ft.
> ___
> STR | DEX | CON | INT | WIS | CHA
>|:---:|:---:|:---:|:---:|:---:|:---:|
> 20 (+5)|11 (+0)|20 (+5)|12 (+1)|16 (+3)|18 (+4)|
> ___
> - **Saving Throws** Dex +5, Wis +8, Cha +9
> - **Skills** Intimidation +9
> - **Damage Immunities** necrotic, poison
> - **Condition Immunities** exhaustion, frightened, poisoned
> - **Senses** darkvision 120 ft., passive Perception 13
> - **Languages** the languages it knew in life.
> - **Challenge** 16 (15,000 XP) <!-- Proficiency Bonus +5 -->
> ___
>	
> ***Cursed air.*** Any creature that isn't undead or a construct within 10 feet of the death knight is unable to regain hit points.
>
> ***Magic Resistance.*** The death knight has advantage on saving throws against spells and other magical effects.
>
> ***Magic Weapons.*** The death knight's weapon attacks are magical.
>
> ### Actions 
> ***Multiattack.*** The death knight makes two longsword attacks and then uses *Death Coil*.
>
> ***Longsword.*** *Melee Weapon Attack*: +10 to hit, reach 5 ft., one target. *Hit:* 9 (1d8 + 5) slashing damage, or 10 (1d10 + 5) slashing damage if used with two hands, plus 18 (4d8) necrotic damage.
>
> ***Death Coil.*** The death knight fires a blast of unholy energy at a living or undead creature within 120 ft. A living creature has to make a DC 17 Constitution saving throw or take 35 (10d6) necrotic damage on a failed save, or half as much damage on a successful one. An undead creature don't get to save, but instead of taking damage it restores 35 (10d6) hit points.
>
> ***Intimidating Shout. (1/day)*** The death knight lets out a horrifying cry and all creatures withing 30 ft. have to make a DC 17 wisdom saving throw or be paralyzed as it can do nothing else but cowering in fear. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
>
> ***Raise Dead (recharge 5-6).*** The death knight animates a non-undead, non-construct, medium or larger corpse within 60 ft. A bone golem appears in the space of the corpse and the corpse is destroyed. The bone golem then rolls for initiative acting on its turn as normal.
>
> ### Reactions
> ***Hysteria.*** When an undead creature the deathknight can see makes an attack roll, the death knight can utter maddening words to it. The creature takes 7 (2d6) psychic damage and has advantage on all attack rolls it makes until the end of its turn.

</div>


\pagebreakNum

___
> ## Unforgiven <!-- https://wc5e-cr-calculator.frogvall.com/?1;16;110;8;12;22;21;0;0;0;0;0;0;0;0;0;0;1;;;;3;;;;;;;;;;1;;;;;;;;10;;1;;;;;2;2;1;3; -->
> *Large undead, chaotic evil*
> ___
> - **Armor Class** 16 (Scale mail)
> - **Hit Points** 110 (13d10 + 39)
> - **Speed** 30 ft.
> ___
> STR | DEX | CON | INT | WIS | CHA
>|:---:|:---:|:---:|:---:|:---:|:---:|
> 14 (+2)|20 (+5)|16 (+3)|7 (-2)|13 (+1)|6 (-2)|
> ___
> - **Skills** Intimidation +4
> - **Damage Resistances** necrotic, bludgeoning, piercing, and slashing from nonmagical weapons
> - **Damage Immunities** poison
> - **Condition Immunities** charmed, exhaustion, frightened, paralyzed, petrified, poisoned, prone, unconscious
> - **Senses** darkvision 60 ft., passive Perception 11
> - **Languages** understands common, but cannot speak
> - **Challenge** 8 (3,900 XP) <!-- Proficiency Bonus +3 -->
> ___
>	
> ***Darkness.*** Magical darkness spreads from the unforgiven in a 15-foot-radius sphere. The darkness spreads around corners. Nonmagical light can't illuminate it, but a creature with darkvision can see through it.
>
> ***Magic Weapons.*** The unforgiven's weapon attacks are magical.
>
> ***Telepathy.*** The unforgiven can magically transmit messages and images to any creature within 120 feet of it that can understand a language.
>
> ### Actions 
> ***Multiattack.*** The unforgiven makes a scythe attack and then uses *Death Coil*.
>
> ***Scythe.*** *Melee Weapon Attack*: +8 to hit, reach 10 ft., one target. *Hit:* 12 (2d6 + 5) slashing damage, plus 10 (3d6) necrotic damage.
>
> ***Death Coil.*** The unforgiven fires a blast of unholy energy at a living or undead creature. A living creature has to make a DC 15 Constitution saving throw or take 21 (6d6) necrotic damage on a failed save, or half as much damage on a successful one. An undead creature restores 21 (6d6) hit points instead.
>
> ***Raise Dead (recharge 5-6).*** The unforgiven animates a non-undead, non-construct corpse within 60 ft. A ghoul appears in the space of the corpse and the corpse is destroyed. The ghoul then rolls for initiative acting on its turn as normal.

A mysterious rank of ghostly warriors, spawned from the corpses of those insolent few who managed to draw the particular ire of the Scourge’s dark masters. These densely armoured wraiths revive feeling only regret and horror at what they have become, and are commanded to express these regrets through might and magic, standing as commanders of lesser undead. Their curse lends them no rest, and not even the comfort of sunlight may reach them. 

<br/>

https://wow.gamepedia.com/Deathlord_(Warcraft_III)
either this https://static.wikia.nocookie.net/wowwiki/images/f/fe/Death_Revenant.jpg or a warcraft 3 render from the death revenant

___
> ## Deathcharger <!-- https://wc5e-cr-calculator.frogvall.com/?0;13;68;6;12;18;18;18;0;18;0;0;0;0;0;0;0;;;;;3;;;;;;;;;;1;;;;;;;;10;;;;;;;2;2;1;3; -->
> *Large undead, neutral evil*
> ___
> - **Armor Class** 13 (Natural Armor)
> - **Hit Points** 68 (8d10 + 24)
> - **Speed** 60 ft.
> ___
> STR | DEX | CON | INT | WIS | CHA
>|:---:|:---:|:---:|:---:|:---:|:---:|
> 18 (+4)|15 (+2)|16 (+3)|2 (-4)|13 (+1)|7 (-2)|
> ___
> - **Damage Immunities** necrotic, poison
> - **Condition Immunities** exhaustion, frightened, poisoned
> - **Senses** darkvision 60 ft., passive Perception 11
> - **Languages** understands the languages of its creator but can't speak
> - **Challenge** 3 (700 XP) <!-- Proficiency Bonus +2 -->
> ___
>
> ***Icy Hooves.*** The deathcharger freezes the ground where it touches it, allowing it to walk over any liquid surfaces.
>
> ***Trampling Charge.*** If the deathcharger moves at least 20 feet straight toward a creature and then hits it with a hooves attack on the same turn, that target must succeed on a DC 14 Strength saving throw or be knocked prone. If the target is prone, the deathcharger can make another attack with its hooves against it as a bonus action.
>
> ### Actions 
> ***Hooves.*** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 11 (2d6 + 4) bludgeoning damage plus 7 (2d6) necrotic damage.
>
> ***Wraith Walk.*** The Deathcharger and its rider magically enter the Ethereal Plane from the Material Plane, or vice versa.

> Greater Steed Variant: Deathknights can summon a deathcharger via the ***find greater steed*** spell. When a deathcharger is summoned through the spell it loses the extra attack from ***trampleing charge*** when a target is prone, also its ***wraith walk*** ability can only be used 3 times per long rest and only lasts until the start of its next turn.

A true Scourge invasion is headed by the iconic sight of a knight sat atop a skeletal horse, decked in armour and finery, mutated through dark magic to sport vicious horns and cruel, eyeless sockets. Expected to be as dangerous as they are unfalteringly obedient, these dread horses are an eternal symbol of the Scourge’s military might.

<br/>

maybe one of these
https://www.deviantart.com/lessanamidairo/art/Acherus-Deathcharger-628851381
https://wowpedia.fandom.com/wiki/Deathcharger?file=Deathcharger_TCG.jpg

\pagebreakNum

___
> ## Flesh Giant <!-- https://wc5e-cr-calculator.frogvall.com/?2;14;218;14;17;90;13;44;13;44;13;0;0;0;0;0;0;1;;;1;2;;;;;;;;;;1;;;;;;;;10;;;;;;;2;2;1;3; -->
> *Huge construct (undead), chaotic evil*
> ___
> - **Armor Class** 14 (natural armor)
> - **Hit Points** 218 (19d12 + 95)
> - **Speed** 30 ft.
> ___
> STR | DEX | CON | INT | WIS | CHA
>|:---:|:---:|:---:|:---:|:---:|:---:|
> 29 (+9)|14 (+2)|20 (+5)|7 (-2)|9 (-1)|6 (-2)|
> ___
> - **Saving Throws** Str +14, Con +10
> - **Skills** Athletics +14, Intimidation +8
> - **Damage Resistances** bludgeoning, piercing, and slashing from nonmagical attacks that aren't adamantine
> - **Damage Immunities** poison
> - **Condition Immunities** charmed, exhaustion, frightened, poisoned
> - **Senses** darkvision 60 ft., passive Perception 9
> - **Languages** understands the languages of its creator but can't speak
> - **Challenge** 13 (10,000 XP) <!-- Proficiency Bonus +5 -->
> ___
>
> ***Fear of Fire.*** When the flesh giant takes fire damage, it has to make a wisdom saving throw. The DC equals 10 or half the damage it takes, whichever number is higher. On a failure the flesh giant has disadvantage on ability checks and attack rolls until the end of its next turn.
>
> ***Immutable Form.*** The flesh giant is immune to any spell or effect that would alter its form.
>
> ### Actions 
> ***Multiattack.*** The flesh giant can use its Frightful Presence. It then makes two fist attacks.
>
> ***Fist.*** *Melee Weapon Attack*: +14 to hit, reach 10 ft., one target. *Hit:* 22 (3d8 + 9) bludgeoning damage.
>
> ***Frightful Presence.*** Each creature of the flesh giant's choice that is within 120 feet of the flesh giant and aware of it must succeed on a DC 17 Wisdom saving throw or become frightened for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature’s saving throw is successful or the effect ends for it, the creature is immune to the flesh giant's Frightful Presence for the next 24 hours.
>
> ***Stomp (Recharge 5-6)***  The flesh giant stomps the ground knocking any creature and unsecured object into the air. Each creature within 50 yards of the stone giant must make a DC 17 Strength saving throw or take 45 (10d8) bludgeoning damage and be hurled 20 feet into the air, immediately falling if it cannot hover. On a successful save, the target takes half damage and is not hurled into the air. Unsecure objects are automatically hurled into the air.
>
> ### Reactions
>
> ***Acid Spinal Fluid*** When hit by a melee attack that deals slashing or piercing damage to the flesh giant, it spews corrosive acid over its attacker. The attacker have to make a DC 17 dexterity saving throw or take 13 (3d8) acid damage.

\columnbreak

In the icy land of Northrend, undeath is the fate for all who fall under the gaze of the Lich King. No creature best demonstrates the Lich King’s dominion over the land than his transformation of the gods’ own creations, the giants. These honourable creatures have been broken down into their base parts, which are matched up and then re-attached to construct a parody of a giant, an abomination on a massive scale. Their blood replaced with ichor, their guts filled with the plague of undeath, and their very spinal fluid transforming into a vicious acid, these giants have been unmade as a symbol of the Lich King’s total disregard for the ancient powers that have ruled Northrend for aeons.

<br/>

https://wowpedia.fandom.com/wiki/Flesh_giant
<img src='https://static.wikia.nocookie.net/wowpedia/images/f/f5/Provoke.jpg' style='position:absolute; top:300px; right:00px; width:200px;' />



\pagebreakNum

___
> ## Doomskull <!-- https://wc5e-cr-calculator.frogvall.com/?0;15;54;5;13;16;0;38;13;31;13;0;0;0;0;0;0;;;;;3;;;;;;;;;;1;1;;;;;;;10;;;;;;;3;2;2;5;Shadow%20Bolt;Magic%20Missile;Scorching%20Ray -->
> *Tiny undead, chaotic evil*
> ___
> - **Armor Class** 15
> - **Hit Points** 54 (12d4 + 24)
> - **Speed** 0 ft., fly 40 ft. (hover)
> ___
> STR | DEX | CON | INT | WIS | CHA
>|:---:|:---:|:---:|:---:|:---:|:---:|
> 1 (-5)|17 (+3)|14 (+2)|16 (+3)|10 (+0)|11 (+0)|
> ___
> - **Skills** Arcana +5, Perception +2
> - **Damage Resistances** necrotic, piercing
> - **Damage Immunities** poison
> - **Condition Immunities** charmed, exhaustion, frightened, paralyzed, poisoned, prone
> - **Senses** darkvision 60 ft., passive Perception 12
> - **Languages** common
> - **Challenge** 4 (1,100 XP) <!-- Proficiency Bonus +2 -->
> ___
>
> ***Magic Resistance.*** The doomskull has advantage on saving throws against spells and other magical effects.
>
> ***Spellcasting.*** The doomskull is a 5th-level spellcaster. Its spellcasting ability is Intelligence (spell save DC 13, +5 to hit with spell attacks). It requires no somatic or material components to cast its spells. The doomskull has the following mage and warlock spells prepared:
>
> Cantrips (at will): *mage hand, ✦ shadow bolt*
> <br/> 1st level (3 slots): *hex, magic missile, shield*
> <br/> 2nd level (2 slots): *blur, phantasmal force, ray of enfeeblement*
> <br/> 3rd level (1 slot): *bestow curse, enemies abound*
>
> ***Swift caster.*** The doomskull can use a bonus action to cast a cantrip, even if it casts a spell using its action.
>
> ***Vacant Size.*** The doomskull can occupy another creature's space and vice versa.
>
> ### Actions 
> ***Bite.*** *Melee Weapon Attack*: +5 to hit, reach 0 ft., one target. *Hit:* 5 (1d4 + 3) bludgeoning damage.
>
> ### Reactions
> ***Curse of Doom.*** When the doomskull is reduced to 0 hit points from taking damage caused by another creature, it utters some incomprehensible words to curse the creature with doom. The creature has to make a DC 13 Wisdom saving throw or gain one level of exhaustion and become cursed. While cursed the creature cannot reduce its exhaustion level. Undead and constructs are immune to the curse.

Robbed of their bodies and their free will, but not their wit, a laughing doomskull is often what remains of necromancers who served the Scourge in life, but demonstrated no reason to be overly-rewarded upon their ascension into undeath. Perhaps transformed into mere skulls as punishment for hubris, or for insolence before their masters, doomskulls are nevertheless permitted to retain their significant magical power. Still intelligent and free-speaking, doomskulls miss no opportunity to make their displeasure heard, and though they lack any form of ambulation, they nevertheless endeavour to fill in as much space as they can through sheer force of personality.

\columnbreak

maybe this
<img src='https://p4.wallpaperbetter.com/wallpaper/397/957/220/adventure-dark-skull-soul-video-games-world-of-warcraft-hd-art-wallpaper-preview.jpg' style='position:absolute; top:00px; right:00px; width:200px;' />

\pagebreakNum

___
> ## Geist <!-- https://wc5e-cr-calculator.frogvall.com/?0;15;49;5;13;35;0;28;13;28;13;0;0;0;0;0;0;;;;;3;;;;;;;;;;1;1;;;;;;;10;;;;;;;3;2;2;5;Shadow%20Bolt;Magic%20Missile;Phantasmal%20Force -->
> *Medium undead, chaotic evil*
> ___
> - **Armor Class** 12
> - **Hit Points** 31 (7d8 + 0)
> - **Speed** 35 ft.
> ___
> STR | DEX | CON | INT | WIS | CHA
>|:---:|:---:|:---:|:---:|:---:|:---:|
> 10 (+0)|14 (+2)|10 (+0)|6 (-2)|10 (+0)|5 (-3)|
> ___
> - **Skills** Acrobatics +4
> - **Damage Immunities** poison
> - **Condition Immunities** poisoned
> - **Senses** darkvision 60 ft., passive Perception 10
> - **Languages** the languages it knew in life.
> - **Challenge** 1 (200 XP) <!-- Proficiency Bonus +2 -->
> ___
>
> ***Hangman's Rope.*** The geist has disadvantage on ability checks to contest or escape a grapple.
>
> ***One Eyed.*** The geist has disadvantage on perception checks that rely on sight.
>
> ***Standing Leap.*** The geist's long jump is up to 30 feet and its high jump is up to 15 feet, with or without a running start. If the geist jumps atleast 15 feet towards a creature, it has advantage on its next attack against the creature until the end of its turn.
>
> ### Actions 
> ***Multiattack.*** The geist makes three claw attacks.
>
> ***Claw.*** *Melee Weapon Attack*: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) slashing damage.

The abandoned corpses of punished criminals are a particularly replenishable source of corpses for the Scourge’s necromancers, who are always in need of new supply. The hooded corpses of hanged thieves in particular are flooded with such regret and vitriol that they are most easily raised as geists. Still tied to their nooses and gazing through their hoods with single, mutated eyes, geists scramble on all fours like animals, speaking an incomprehensible mumbling language and often travelling in groups. Their frail bodies hide surprising strength, able to leap great distances and claw at their targets in ambush. 

<br/>

https://wowpedia.fandom.com/wiki/Geist
https://gamepedia.cursecdn.com/wowpedia/9/9f/Runeforge_Haunter.jpg

___
> ## Necrolyte <!-- https://wc5e-cr-calculator.frogvall.com/?0;12;90;5;13;13;0;13;0;13;0;0;0;0;0;0;0;;;;;3;;;;;;;;;;1;;;;;;;;10;;;;;;;3;3;0;5;Mind%20Blast;Chill%20Touch;Sapping%20Sting;Toll%20the%20Dead;Dark%20Void;Drain%20Life -->
> *Medium humanoid (any), neutral evil*
> ___
> - **Armor Class** 12
> - **Hit Points** 82 (15d8 + 15) + 8 (1d4+4) from *false life*
> - **Speed** 30 ft.
> ___
> STR | DEX | CON | INT | WIS | CHA
>|:---:|:---:|:---:|:---:|:---:|:---:|
> 8 (-1)|14 (+2)|12 (+1)|16 (+3)|11 (+0)|13 (+1)|
> ___
> - **Skills** Arcana +5
> - **Senses** darkvision 60 ft., passive Perception 10
> - **Languages** common
> - **Challenge** 2 (450 XP) <!-- Proficiency Bonus +2 -->
> ___
>
> ***Focused Mind*** The necrolyte advantage on Constitution saving throws that it make to maintain its concentration on a spell.
>
> ***Innate Spellcasting.*** The necrolyte's innate spellcasting ability is Intelligence. It can innately cast the following spells (spell save DC 13), requiring no material components:
> <br/> At will: *disguise self, false life*
> <br/> 1/day: *animate dead*
>
> ***Spellcasting.*** The necrolyte is a 5th-level spellcaster. Its spellcasting ability is Intelligence (spell save DC 13, +5 to hit with spell attacks). The necrolyte regains its expended spell slots when it finishes a short or long rest, and knows the following priest and warlock spells:
>
> Cantrips (at will): *chill touch, ✦ diabolism, ✦ mind blast, resistance, sapping sting, toll the dead*
> <br/> 1st-3rd level (2 3rd-level slots): *blindness/deafness, ✦ dark void, ✦ drain life, fear, ray of enfeeblement, speak with dead*
> 
> <!---
> Cantrips (at will): chill touch, ✦ diabolism, ✦ mind blast, resistance, sapping sting, toll the dead
> <br/> 1st level: ✦ dark void, drain life
> <br/> 2nd level: blindness/deafness, ray of enfeeblement
> <br/> 3rd level: fear, speak with dead
> -->
>
> ### Actions 
> ***Dagger.*** *Melee Weapon Attack*: +4 to hit, reach 5 ft., one target. *Hit:*, 4 (1d4 + 2) slashing damage.

Following on from the very earliest known necromancers, necrolytes represent the low-tier clergy of the Cult of the Damned, or put another way, are the average working man’s necromancer. In any cloister of the Scourge’s armies, there must be many hands constantly shifting and raising the corpses of the dead, and taking on this vital, albeit menial, task are the necrolytes. Practitioners of the religions that have grown out of the Scourge, they decry the Light, the elements, the ancestors or whatever other beliefs they may have previously held, instead making sermons on their new lord, the Lich King, and his greater servants. 

<br/>

https://gamepedia.cursecdn.com/wowpedia/e/ed/Drom%27kor.jpg

<img src='https://gamepedia.cursecdn.com/wowpedia/e/ed/Drom%27kor.jpg' style='position:absolute; top:900px; right:00px; width:200px;' />

>ADD SIDEBAR ABOUT NON-ORC NECROLYTES REPLACING RELENTLESS ENDURANCE WITH ANOTHER RACIAL

\pagebreakNum

___
> ## Grand Necrolyte <!-- aka necrolord https://wc5e-cr-calculator.frogvall.com/?1;15;118;8;16;40;0;40;0;40;0;0;0;0;0;0;0;1;;;1;2;;;;;;;;;;1;;;;;;;;10;;;;;;;5;5;5;11;Mind%20Blast;Chill%20Touch;Sapping%20Sting;Toll%20the%20Dead;Dark%20Void;Drain%20Life;Guiding%20Bolt;Hunger%20of%20Hadar;Vampiric%20Touch;Blight;Enervation -->
> *Medium humanoid (any), neutral evil*
> ___
> - **Armor Class** 12 (15 with *mage armor*)
> - **Hit Points** 110 (17d8 + 34) + 8 (1d4+4) from *false life*
> - **Speed** 30 ft.
> ___
> STR | DEX | CON | INT | WIS | CHA
>|:---:|:---:|:---:|:---:|:---:|:---:|
> 8 (-1)|14 (+2)|14 (+2)|20 (+5)|13 (+1)|13 (+1)|
> ___
> - **Saving Throws** Int +8, Wis +4, Cha +4
> - **Skills** Arcana +8
> - **Damage Resistances** necrotic, poison
> - **Senses** darkvision 60 ft., passive Perception 11
> - **Languages** common
> - **Challenge** 8 (3,900 XP) <!-- Proficiency Bonus +3 -->
> ___
>
> ***Corpse Shield*** As long as there is a undead creature under the command of the necrolyte within 60 feet of it that it can see, it can split up to half of the damage it takes among its undead minions.  
>
> ***Focused Mind*** The necrolyte advantage on Constitution saving throws that it make to maintain its concentration on a spell.
> 
> ***Innate Spellcasting.*** The necrolyte's innate spellcasting ability is Intelligence. It can innately cast the following spells (spell save DC 16), requiring no material components:
> <br/> At will: *disguise self, false life, mage armor (self only)*
> <br/> 1/day: *animate dead*
> 
>
> ***Spellcasting.*** The necrolyte is a 11th-level spellcaster. Its spellcasting ability is Intelligence (spell save DC 16, +8 to hit with spell attacks). The necrolyte regains its expended spell slots when it finishes a short or long rest, and knows the following priest and warlock spells:
>
> <br/> 1/day *create Undead*
>
> Cantrips (at will): *chill touch, ✦ diabolism, ✦ mind blast, resistance, sapping sting, toll the dead*
> <br/> 1st-5th level (3 5th-level slots): *blight, blindness/deafness, ✦ dark void, danse macabre, ✦ drain life, enervation, fear, guiding bolt (necrotic damage), hunger of hadar, ray of enfeeblement, speak with dead, vampiric touch, ✦ voidshift\**
> 
> <!---
> Cantrips (at will): chill touch, ✦ diabolism, ✦ mind blast, resistance, sapping sting, toll the dead
> <br/> 1st level: ✦ dark void, guiding bolt (necrotic damage)
> <br/> 2nd level: blindness/deafness, ray of enfeeblement
> <br/> 3rd level: hunger of hadar, fear, speak with dead, vampiric touch
> <br/> 4th level: ✦ voidshift\*, blight
> <br/> 5th level: danse macabre, enervation
> -->
> 
> \*creatures under the necrolyte's command don't have to be willing.
>
> ### Actions 
> ***Dagger.*** *Melee Weapon Attack*: +5 to hit, reach 5 ft., one target. *Hit:*, 4 (1d4 + 2) slashing damage. 


Greater necromancers occupying a far higher rank in their cults, grand necrolytes act as spiritual leaders among the still-livin worshippers of the Scourge’s decree. They experience no doubts and have no questions about their chosen path, showing a piety that might make a paladin blush. Granted powers over life and death that dwarf those of other necromancers, these dark clerics often lead or perform the most skilful of rituals to create the more powerful creatures.


___
> ## Plague Eruptor <!-- https://wc5e-cr-calculator.frogvall.com/?1;16;102;7;16;36;10;36;10;36;45;0;0;0;0;0;0;;;;;3;;;;;;;;;;1;;;;;;;;10;;;1;;;;2;2;1;3; -->
> *Large undead, neutral evil*
> ___
> - **Armor Class** 16 (natural armor)
> - **Hit Points**  102 (12d10 + 24)
> - **Speed** 30 ft.
> ___
> STR | DEX | CON | INT | WIS | CHA
>|:---:|:---:|:---:|:---:|:---:|:---:|
> 17 (+3)|14 (+2)|16 (+3)|6 (-2)|10 (+0)|5 (-3)|
> ___
> - **Skills** 
> - **Damage Immunities** poison
> - **Condition Immunities** poisoned
> - **Senses** darkvision 60 ft., passive Perception 10
> - **Languages** the languages it knew in life but can't speak.
> - **Challenge** 7 (2,900 XP) <!-- Proficiency Bonus +3 --> <!-- +4 cause of offesive cr 9 -->
> ___
>
> ***Leaking Pustules.*** A creature that touches the plague eruptor or hits it with a melee attack while within 5 feet of it takes 10 (3d6) poison damage.
>
> ***Deadly Plague.*** Poison damage that the plague eruptor deals ignores resistance and immunity to poison damage. It can inflict the poisoned condition even on creatures normally immune to it. When it deals a critical hit, the target is infected with the plague of undeath.
>
> ***Plague Eruption.*** When the plague eruptor dies, it explodes, and each creature within 15 feet of it must make a DC 16 Constitution saving throw, taking 35 (10d6) poison damage and become infected with the plague of undeath on a failed save. A successful save results in half damage and no other effect. A humanoid creature killed by this damage rises as a zombie after 1 minute.
>
> ### Actions 
> ***Multiattack.*** The plague eruptor makes two slam attacks and uses its vile gas ability.
>
> ***Slam.*** *Melee Weapon Attack*: +7 to hit, reach 5 ft., one target. *Hit:* 12 (2d8 + 3) bludgeoning damage.
>
> ***Vile Gas.*** The plague eruptor expels a poisonous cloud in 10-feet radius around it. Each creature in the area must make a DC 15 Constitution saving throw. On a failed save, a creature takes 12 (2d8+3) poison damage. On a successful save, the creature takes half as much damage.
>
> ***Vile Gas Eruption (Recharge 6).*** One of the plague eruptors pustules explodes into a cloud of poison that covers a 15-foot cube. Each creature in the area must make a DC 16 Constitution saving throw. On a failed save, a creature takes 18 (4d8) poison damage and is poisoned for 1 minute. On a successful save, the creature takes half as much damage and isn't poisoned. A poisoned creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

\pagebreakNum

<div class='statblock-wide'>

___
___
> ## Lich <!-- based on Devkarin Lich --> 
> <!-- no cropse explosion https://wc5e-cr-calculator.frogvall.com/?2;15;144;7;18;90;0;80;0;72;0;0;0;0;0;0;0;;;;1;3;;;;;;;;;1;3;;;;;;;1;12;;;;;;;7;6;5;14;Drain%20Life;Blizzard;Death%20and%20Decay;Blight;Army%20of%20the%20Dead;Cone%20of%20Cold;Enervation;Circle%20of%20Death;Investiture%20of%20Ice;Wall%20of%20Ice;Glacial%20Spike;Finger%20of%20Death -->
> *Large undead, neutral evil*
> ___
> - **Armor Class** 15 (natural armor)
> - **Hit Points**  97 (13d10 + 26)
> - **Speed** 30 ft.
> ___
> STR | DEX | CON | INT | WIS | CHA
>|:---:|:---:|:---:|:---:|:---:|:---:|
> 11 (+0)|14 (+2)|14 (+2)|20 (+5)|16 (+3)|15 (+2)|
> ___
> - **Saving Throws** Con +7, Int +9, Wis +8
> - **Skills** Arcana +14, Insight +8, Perception +8
> - **Damage Resistances** cold, necrotic; bludgeoning, piercing, and slashing from nonmagical attacks
> - **Damage Immunities** poison
> - **Condition Immunities** charmed, exhaustion, frightened, paralyzed,petrified, poisoned, prone
> - **Senses** truesight 120 ft., passive Perception 18
> - **Languages** the languages it knew in life.
> - **Challenge** 14 (11,500 XP) <!-- Proficiency Bonus +5 -->
> ___
>
> ***Innate Levitation*** The lich hovers above any surface but doesn't fly. It isn't affected by difficult terrain and can move over liquids turning them solid along its path. 
>
> ***Ice Shield.*** The lich has a magical ward that has 48 (half its hp) hit points. Whenever the lich takes damage, the ward takes the damage instead. If the ward is reduced to 0 hit points, the lich takes any remaining damage. When the lich casts spell that deals cold damage of 1st level or higher, the ward regains a number of hit points equal to twice the level of the spell. Additionally a creature that touches the ice shield takes 11 (2d10) cold damage.
>
> ***Immutable Form.*** The lich is immune to any spell or effect that would alter its form. 
>
> ***Legendary Resistance (3/Day).*** If the lich fails a saving throw, it can choose to succeed instead.
>
> ***Master of Undeath.*** The lich has control over any undead created by the scourge within 500 feet that aren't under the command of someone else.
>
> ***Rejuvenation.*** If it has a phylactery, a destroyed lich gains a new body in 1d10 days, regaining all its hit points and becoming active again. The new body appears within 5 feet of the phylactery.
>
> ***Spellcasting.*** The lich is a 14th-level spellcaster. Its spellcasting ability is Intelligence (spell save DC 18, +10 to hit with spell attacks). The lich has the following death knight and mage spells prepared:
>
> Cantrips (at will): *chill touch, sapping sting, frostbite, flurry, prestidigitation*
> <br/> 1st level (4 slots): *cause fear, ✦ corpse explosion, ✦ drain life, false life*
> <br/> 2nd level (3 slots): *blindness/deafness, crown of madness, ray of enfeeblement*
> <br/> 3rd level (3 slot): *animate dead, ✦ asphyxiate, ✦ blizzard, counterspell, speak with dead, summon undead*
> <br/> 4th level (3 slot): *✦ ice block, ✦ death and decay, blight*
> <br/> 5th level (2 slot): *✦ army of the Dead, cone of cold, danse macabre, enervation*
> <br/> 6th level (1 slot): *circle of death, create undead, investiture of ice, wall of ice
> <br/> 7th level (1 slot): *finger of death, ✦ glacial spike*
>
> ***Turn Resistance.*** The lich has advantage on saving throws against any effect that turns undead.
>
> ### Actions 
> ***Multiattack.*** The lich makes one attack with its claws and one with its chains.
>
> ***Claw.*** *Melee Weapon Attack*: +7 to hit, reach 5 ft., one target. *Hit:* 12 (2d8 + 3) piercing and 2d8 (9) cold damage.
>
> ***Undying Chains.*** Melee Spell Attack. +10 to hit, reach 15 ft., one creature. Hit: 13 (3d8) cold damage, and the target is grappled (escape DC 18). Until this grapple ends, the target is restrained and has disadvantage on all saving throws, and the lich can't chain another target.
>
> ### Legendary Actions
> The lich can take 3 legendary actions, choosing from the options below. Only one legendary action can be used at a time and only at the end of another creature's turn. The devkarin lich regains spent legendary actions at the start of its turn.
>
> ***Cantrip.*** The lich casts one of its cantrips.
> ***Claw (Costs 2 Actions).*** The lich makes a Claw attack.
> ***Disrupt Life (Costs 3 Actions).*** Each creature within 30 feet of the lich must make a DC 18 Constitution saving throw, taking 21 (6d6) necrotic damage on a failed save, or half as much damage on a successful one.


</div>

\pagebreakNum

___
> ## Plague-dog <!-- https://wc5e-cr-calculator.frogvall.com/?1;13;105;10;17;53;0;53;21;53;21;0;0;0;0;0;0;1;;;;3;;;;;;;;;;1;;;;;;;;10;;;;;;;2;2;1;3; -->
> *Huge construct (undead), neutral evil*
> ___
> - **Armor Class** 13 (natural armor)
> - **Hit Points** 105 (10d12 + 40)
> - **Speed** 50 ft.
>___
>|STR|DEX|CON|INT|WIS|CHA|
>|:---:|:---:|:---:|:---:|:---:|:---:|
>|25 (+7)|10 (+0)|19 (+4)|2 (-4)|12 (+1)|9 (-1)|
>___
> - **Skills** Perception +4
> - **Resistances** bludgeoning, piercing, and slashing from non magical attacks
> - **Damage Immunities** poison
> - **Condition Immunities** exhaustion, frightened, petrified, poisoned
> - **Senses** darkvision 60 ft., passive Perception 14
> - **Languages** understands the languages of its creator but can't speak
> - **Challenge** 8 (3,900 XP) <!-- Proficiency Bonus +3 -->
> ___
> 
> ***Deadly Plague.*** Poison damage that the plague-dog deals ignores resistance and immunity to poison damage. It can inflict the poisoned condition even on creatures normally immune to it. When it deals a critical hit, the target is infected with the plague of undeath.
>
> ***Immutable Form.*** The abomination is immune to any spell or effect that would alter its form.
> 
> ### Actions
> ***Multiattack.*** The plague-dog makes two attacks: one bite or chomp and one claw attack.
>
> ***Bite.*** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 20 (2d12 + 7) piercing and 13 (2d12) poison damage. If the target is a Large or smaller creature, it must succeed on a DC 17 Dexterity saving throw or be swallowed ny the plague-dog. A swallowed creature is blinded and restrained, has total cover against attacks and other effects outside the worm, and takes 21 (6d6) poison damage at the start of each of the plague dog's turns. A plague dog can have only one creature swallowed at a time.
> If the plague dog takes 30 damage or more on a single turn from the swallowed creature, the plague-dog must succeed on a DC 14 Constitution saving throw or the creature successfully cuts its way through the dog and falls prone in a space within 5 feet of the plague-dog. If the plague-dog dies, a swallowed creature is no longer restrained by it and can escape from the corpse by using 15 feet of movement, exiting prone.
>
> ***Claw.*** *Melee Weapon Attack:* +10 to hit, reach 5 ft., one target. *Hit:* 20 (3d8 + 7) slashing damage.

## Frost Wyrms

Creatures killed by a frostbrood dragon's cold become a frozen statue until they thaw.

Ice made by frost wyrms is magical and will not melt without magical assistance.

___
> ## Frostbrood Whelp <!-- https://wc5e-cr-calculator.frogvall.com/?0;15;31;4;13;36;8;11;8;11;8;0;0;0;0;0;0;;;;1;4;;;;;;;;;;1;;;;;;;;10;;;;;;;;;;; -->
> *Small undead, lawful evil*
> ___
> - **Armor Class** 15 (natural armor)
> - **Hit Points** 31 (7d6 + 7)
> - **Speed** 30 ft., fly 60 ft.
> ___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |14 (+2)|11 (+0)|13 (+1)|14 (+2)|11 (+0)|14 (+2)|
>___
> - **Saving Throws** Dex +2, Con +3, Int +4, Cha +4
> - **Skills** Arcana +6, Perception +2
> - **Damage Resistances** necrotic
> - **Damage Immunities** cold, force, poison
> - **Condition Immunities** charmed, exhaustion, frightened, paralyzed, poisoned
> - **Senses** blindsight 10 ft., darkvision 60 ft., passive Perception 12
> - **Languages** Common, Draconic
> - **Challenge** 3 (700 XP)                   **Proficiency Bonus** +2
> ___
> ***Frost Aura.*** A creature who ends their turn within 5 feet of the whelp or strikes it with a melee attack takes 4 (1d8) cold damage.
>
> ***Ice Walk.*** The whelp can move across and climb icy surfaces without needing to make an ability check. Additionally, difficult terrain composed of ice or snow doesn't cost it extra moment.
>
> ### Actions
> ***Bite.*** *Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 7 (1d10 + 2) piercing damage plus 4 (1d8) cold damage.
>
> ***Frost Breath (Recharge 5-6).*** The whelp exhales an icy blast in a 15-foot cone. Each creature in that area must make a DC 13 Dexterity saving throw, taking 18 (4d8) cold damage on a failed save, or half as much damage on a successful one. A creature who fails their saving throw has their movement speed halved and can't take reactions for 1 minute. 

\columnbreak
___
> ## Frostbrood Drake <!-- https://wc5e-cr-calculator.frogvall.com/?1;16;127;8;16;62;36;35;36;35;18;0;0;0;0;0;0;;;;1;4;;;;;;;;;;1;;;;;;;;10;;;;;;1;3;3;3;9;Flurry;Blizzard -->
> *Large dragon, lawful evil*
> ___
> - **Armor Class** 16 (natural armor)
> - **Hit Points** 127 (15d10 + 45)
> - **Speed** 40 ft., fly 80 ft.
> ___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |18 (+4)|11 (+0)|17 (+3)|18 (+4)|13 (+1)|16 (+3)|
> ___
> - **Saving Throws** Dex +4, Con +7, Int +8, Cha +7
> - **Skills** Arcana +11, Perception +5
> - **Damage Resistances** necrotic
> - **Damage Immunities** cold, force, poison
> - **Condition Immunities** charmed, exhaustion, frightened, paralyzed, poisoned
> - **Senses** blindsight 10 ft., darkvision 60 ft., passive Perception 15
> - **Languages** Common, Draconic
> - **Challenge** 9 (5,000 XP)                 **Proficiency Bonus** +4
> ___
> ***Frost Aura.*** A creature who ends their turn within 10 feet of the drake or strikes it with a melee attack takes 9 (2d8) cold damage.
>
> ***Ice Walk.*** The drake can move across and climb icy surfaces without needing to make an ability check. Additionally, difficult terrain composed of ice or snow doesn't cost it extra moment.
>
> ***Innate Spellcasting.*** The drake's innate spellcasting ability is Intelligence (spell save DC 16, +8 to hit with spell attacks). It can innately cast the following spells, requiring no material components:
> 
> At will: ✦ *diabolism*, ✦ *flurry*, *shape water* ^XGE^
> <br/> 3/day each: ✦ *blizzard*, *dispel magic*, *fog cloud*, <br/>     *ray of enfeeblement*, *sleet storm*
>
> ### Actions
> ***Multiattack.*** The drake makes two attacks: one with its bite and one with its claws.
>
> ***Bite.*** *Melee Weapon Attack:* +8 to hit, reach 10 ft., one target. *Hit:* 15 (2d10 + 4) piercing damage plus 9 (2d8) cold damage.
>
> ***Claw.*** *Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) slashing damage.
>
> ***Frost Breath (Recharge 5-6).*** The drake exhales an icy blast in a 30-foot cone. Each creature in that area must make a DC 16 Dexterity saving throw, taking 31 (7d8) cold damage on a failed save, or half as much damage on a successful one. A creature who fails their saving throw has their movement speed halved and can't take reactions for 1 minute. If they fail their save by 5 or more, they are also entombed in ice.
> <br/>     While entombed, they have total cover and are restrained and incapacitated. At the beginning of their turn, they take 9 (2d8) cold damage and can attempt a DC 16 Strength check, breaking free from the ice on a success. The ice can be attacked and destroyed (AC 10; hp equal to cold damage taken by the breath weapon; vulnerability to fire damage; immunity to cold, poison, and psychic damage).

<div class="pageLetter">D</div>
<div class='footnote'>DRAGONS | Blue Dragonflight</div>

\pagebreakNum

___
___
> ## Frostbrood Dragon <!-- https://wc5e-cr-calculator.frogvall.com/?3;17;172;12;19;72;78;43;78;43;52;0;0;0;0;0;0;;;;1;4;;;;;;;1;;1;3;;;;;;;;15;;;;;;1;3;3;3;16;Flurry;Blizzard -->
> *Huge dragon, lawful evil*
> ___
> - **Armor Class** 17 (natural armor)
> - **Hit Points** 172 (15d12 + 75)
> - **Speed** 40 ft., fly 80 ft.
>___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |22 (+6)|11 (+0)|21 (+5)|22 (+6)|15 (+2)|18 (+4)|
>___
> - **Saving Throws** Dex +6, Con +11, Int +12, Cha +10
> - **Skills** Arcana +17, Perception +8
> - **Damage Resistances** necrotic
> - **Damage Immunities** cold, force, poison
> - **Condition Immunities** charmed, exhaustion, frightened, paralyzed, poisoned
> - **Senses** blindsight 10 ft., darkvision 60 ft., passive Perception 18
> - **Languages** Common, Draconic
> - **Challenge** 17 (18,000 XP)              **Proficiency Bonus** +6
> ___
> ***Frost Aura.*** A creature who ends their turn within 15 feet of the dragon or strikes it with a melee attack takes 13 (3d8) cold damage.
>
> ***Ice Walk.*** The dragon can move across and climb icy surfaces without needing to make an ability check. Additionally, difficult terrain composed of ice or snow doesn't cost it extra moment.
>
> ***Innate Spellcasting.*** The dragon's innate spellcasting ability is Intelligence (spell save DC 20, +12 to hit with spell attacks). It can innately cast the following spells, requiring no material components:
> 
> At will: ✦ *diabolism*, ✦ *flurry*, *shape water* ^XGE^, <br/>     *sleet storm*
> <br/> 3/day each: ✦ *blizzard*, *dispel magic*, *fog cloud*, <br/>     *ray of enfeeblement*
> <br/> 1/day each: *shadow of moil* ^XGE^, *wall of ice*
> 
> ***Legendary Resistance (3/Day).*** If the dragon fails a saving throw, it can choose to succeed instead.
>
> ### Actions
> ***Multiattack.*** The dragon can use its Frightful Presence. It then makes two attacks: one with its bite and one with its claws.
>
> ***Bite.*** *Melee Weapon Attack:* +12 to hit, reach 10 ft., one target. *Hit:* 17 (2d10 + 6) piercing damage plus 13 (3d8) cold damage.
>
> ***Claw.*** *Melee Weapon Attack:* +12 to hit, reach 5 ft., one target. *Hit:* 13 (2d6 + 6) slashing damage.
>
> ***Tail Sweep.*** *Melee Weapon Attack:* +12 to hit, reach <br/> 15 ft., all targets in reach. *Hit:* 15 (2d8 + 6) bludgeoning damage.
>
> ***Frightful Presence.*** Each creature of the dragon's choice that is within 120 feet of the dragon and aware of it must succeed on a DC 18 Wisdom saving throw or become frightened for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dragon's Frightful Presence for the next 24 hours.
>
> ***Frost Breath (Recharge 5-6).*** The dragon exhales an icy blast in a 60-foot cone. Each creature in that area must make a DC 18 Dexterity saving throw, taking 36 (8d8) cold damage on a failed save, or half as much damage on a successful one. A creature who fails their saving throw has their movement speed halved and can't take reactions for 1 minute. If they fail their save by 5 or more, they are also entombed in ice.
> <br/>     While entombed, they have total cover and are restrained and incapacitated. At the beginning of their turn, they take 13 (3d8) cold damage and can attempt a DC 18 Strength check, breaking free from the ice on a success. The ice can be attacked and destroyed (AC 10; hp equal to cold damage taken by the breath weapon; vulnerability to fire damage; immunity to cold, poison, and psychic damage).
>
> ### Legendary Actions
> The dragon can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature's turn. The dragon regains spent legendary actions at the start of its turn.
>
> **Icy Grip.** Each creature within 40 feet of the dragon 
<br/>    must make a DC 20 Strength saving throw or be 
<br/>    pulled to the closest unoccupied space next to the 
<br/>    dragon.
> <br/> **Sleet Storm.** The dragon casts *sleet storm*.
> <br/> **Ice Tomb (Costs 2 Actions).** A creature the dragon can 
<br/>    see within 60 feet must make a DC 20 Dexterity 
<br/>    saving throw or become entombed in ice, as if they 
<br/>    were affected by Frost Breath (30 hit points). On a 
<br/>    successful save, they instead have their speed halved 
<br/>    and cannot take reactions until the dragon's next 
<br/>    turn.
> <br/> **Wing Attack (Costs 2 Actions).** The dragon beats its 
<br/>    wings. Each creature within 10 feet of the dragon 
<br/>    must succeed on a DC 20 Dexterity saving throw or 
<br/>    take 13 (2d6 + 6) bludgeoning damage and be 
<br/>    knocked prone. The dragon can then fly up to half its 
<br/>    flying speed.

<div class="pageLetter">D</div>
<div class='footnote'>DRAGONS | Blue Dragonflight</div>

\pagebreakNum

___
___
> ## Frostbrood Wyrm <!-- https://wc5e-cr-calculator.frogvall.com/?3;18;350;15;22;108;102;70;102;52;66;0;0;0;0;0;0;;;;1;4;;;;;;;1;;1;3;;;;;;;;15;;;;;;1;8;3;3;16;Flurry;Blizzard;Ice%20Nova -->
> *Gargantuan dragon, lawful neutral*
> ___
> - **Armor Class** 18 (natural armor)
> - **Hit Points** 350 (20d20 + 140)
> - **Speed** 40 ft., fly 80 ft.
> ___
> |  STR  |  DEX  |  CON  |  INT  |  WIS  |  CHA  |
> |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
> |26 (+8)|11 (+0)|25 (+7)|26 (+8)|17 (+3)|20 (+5)|
> ___
> - **Saving Throws** Dex +7, Con +14, Int +15, Cha +12
> - **Skills** Arcana +22, Perception +10
> - **Damage Resistances** necrotic
> - **Damage Immunities** cold, force, poison
> - **Condition Immunities** charmed, exhaustion, frightened, paralyzed, poisoned
> - **Senses** blindsight 10 ft., darkvision 60 ft., passive Perception 20
> - **Languages** Common, Draconic
> - **Challenge** 23 (50,000 XP)              **Proficiency Bonus** +7
> ___
> ***Frost Aura.*** A creature who ends their turn within 20 feet of the wyrm or strikes it with a melee attack takes 18 (4d8) cold damage.
>
> ***Ice Walk.*** The wyrm can move across and climb icy surfaces without needing to make an ability check. Additionally, difficult terrain composed of ice or snow doesn't cost it extra moment.
>
> ***Innate Spellcasting.*** The wyrm's innate spellcasting ability is Intelligence (spell save DC 23, +15 to hit with spell attacks). It can innately cast the following spells, requiring no material components:
> 
> At will: ✦ *diabolism*, ✦ *flurry*, *shape water* ^XGE^, <br/>     *sleet storm*
> <br/> 3/day each: ✦ *blizzard*, *dispel magic*, *fog cloud*, <br/>     *ray of enfeeblement*, *wall of ice*
> <br/> 1/day each: *antimagic field*, *shadow of moil* ^XGE^, <br/>     ✦ *ice nova*
> 
> ***Legendary Resistance (3/Day).*** If the wyrm fails a saving throw, it can choose to succeed instead.
>
> ### Actions
> ***Multiattack.*** The wyrm can use its Frightful Presence. It then makes two attacks: one with its bite and one with its claws.
>
> ***Bite.*** *Melee Weapon Attack:* +15 to hit, reach 15 ft., one target. *Hit:* 19 (2d10 + 8) piercing damage plus 18 (4d8) cold damage.
>
> ***Claw.*** *Melee Weapon Attack:* +15 to hit, reach 10 ft., one target. *Hit:* 15 (2d6 + 8) slashing damage.
>
> ***Tail Sweep.*** *Melee Weapon Attack:* +15 to hit, reach <br/> 20 ft., all targets in reach. *Hit:* 17 (2d8 + 8) bludgeoning damage.
>
> ***Frightful Presence.*** Each creature of the wyrm's choice that is within 120 feet of the wyrm and aware of it must succeed on a DC 20 Wisdom saving throw or become frightened for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the wyrm's Frightful Presence for the next 24 hours.
>
> ***Frost Breath (Recharge 5-6).*** The wyrm exhales an icy blast in a 90-foot cone. Each creature in that area must make a DC 22 Dexterity saving throw, taking 52 (12d8) cold damage on a failed save, or half as much damage on a successful one. A creature who fails their saving throw has their movement speed halved and can't take reactions for 1 minute. If they fail their save by 5 or more, they are also entombed in ice.
> <br/>     While entombed, they have total cover and are restrained and incapacitated. At the beginning of their turn, they take 18 (4d8) cold damage and can attempt a DC 22 Strength check, breaking free from the ice on a success. The ice can be attacked and destroyed (AC 10; hp equal to cold damage taken by the breath weapon; vulnerability to fire damage; immunity to cold, poison, and psychic damage).
>
> ### Legendary Actions
> The wyrm can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature's turn. The wyrm regains spent legendary actions at the start of its turn.
>
> **Icy Grip.** Each creature within 60 feet of the wyrm 
<br/>    must make a DC 23 Strength saving throw or be 
<br/>    pulled to the closest unoccupied space next to the 
<br/>    dragon.
> <br/> **Sleet Storm.** The wyrm casts *sleet storm*.
> <br/> **Ice Tomb (Costs 2 Actions).** A creature the wyrm can 
<br/>    see within 60 feet must make a DC 23 Dexterity 
<br/>    saving throw or become entombed in ice, as if they 
<br/>    were affected by Frost Breath (50 hit points). On a 
<br/>    successful save, they instead have their speed halved 
<br/>    and cannot take reactions until the dragon's next 
<br/>    turn.
> <br/> **Wing Attack (Costs 2 Actions).** The wyrm beats its 
<br/>    wings. Each creature within 15 feet of the wyrm 
<br/>    must succeed on a DC 23 Dexterity saving throw or 
<br/>    take 15 (2d6 + 8) bludgeoning damage and be 
<br/>    knocked prone. The wyrm can then fly up to half its 
<br/>    flying speed.
> <br/> **Breath Weapon (Costs 3 Actions).** The wyrm uses its 
<br/>    breath weapon, if it is available.

<!-- 
Bone Golem		5	Medium
Bone Wraith		17	Huge
Death Knight		16	Medium	Draws inspiration from Death Knights.
Death Revenant		8	Large
Deathcharger		3	Large	Draws inspiration from Nightmares.
Flesh Giant		13	Huge    
Floating Skull		4	Tiny	Draws inspiration from Flameskulls.
Geist		1	Medium
Necrolord		8	Medium
Plague Eruptor		7	medium
-->

