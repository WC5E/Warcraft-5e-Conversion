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
  
  /* PAGE STYLE */
  
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
  
  /* FRONT PAGE STYLES */
  
    .cover-header-container {
      display: block;
      position: absolute;
      width: 100%;
      top: 80px;
      left: 0;
      right: 0;
      clear: both;
    }
  
    .cover-header-logo {
      display: block;
      width: 700px;
      margin: auto;
    }
  
    .cover-header-divider {
      display: block;
      width: 580px;
      margin: -12px auto -6px;
    }
  
    .cover-header-title {
      display: block;
      width: 700px;
      margin: auto;
      color: white;
      font-family: NodestoCaps,nodesto,sans-serif;
      font-weight: normal;
      font-size: 72px;
      line-height: 72px;
      text-align: center;
      text-shadow: 2px 2px 4px #000, -2px 2px 4px #000, 2px -2px 4px #000, -2px -2px 4px #000;
    }
  
    .cover-footer-container {
      display: block;
      position: absolute;
      width: 100%;
      bottom: 28px;
      left: 0;
      right: 0;
      clear: both;
    }
  
    .cover-footer-subtitle,
    .cover-footer-version {
      display: block;
      width: 500px;
      margin: auto;
      color: white;
      font-family: NodestoCaps,nodesto,sans-serif;
      font-weight: normal;
      text-align: center;
      text-shadow: 1px 1px 2px #000, -1px 1px 2px #000, 0px 0px 2px #000;
    }
    .cover-footer-subtitle {
      font-size: 28px;
      line-height: 28px;
    }
    .cover-footer-version {
      margin-top: 16px;
      font-size: 20px;
      line-height: 20px;
    }
  
  /* STAT BLOCKS */
    /* For creature statblocks within range (start and end must be specified),
       don't show a background. Used for the appendix creatures */
    .phb:nth-of-type(n+140):nth-of-type(-n+200) hr+section blockquote {
      background: none;
      border: none;
      box-shadow: none;
      margin-top: 12px;
      margin-bottom: 12px;
      padding-top: 6px;
      padding-bottom: 6px;
    }
  
  </style>
  
  # Chapter 6: Spells
  This chapter describes the most common spells on Azeroth. The chapter begins with the spell lists of the spellcasting classes. The remainder contains spell descriptions, pre-sented in alphabetical order by the name of the spell. 
  
  While most spell descriptions are located in the Player's Handbook, some spells are described in other locations, as indicated by the table below.
  
  Symbol|Spell Location
  ------|--------------------------
  ✦ |In this chapter, under Spell Descriptions
  ^EGW^ | Explorer's Guide to Wildemount
  ^ID:RotF^ | Icewind Dale: Rime of the Frostmaiden
  ^LLK^ | Lost Laboratory of Kwalish
  ^SCAG^ |Sword Coast Adventurer's Guide
  ^TCE^ | Tasha's Cauldron of Everything
  ^XGE^ |Xanathar's Guide to Everything
  
  <div style='margin-top:25px;'></div>
  
  > ##### Variant Rule: On a Pale Horse
  > GMs might consider making the creatures summoned by a death knight with *find steed* and *find greater steed* undead, rather than one of the creature types listed in those spells.
  
  \columnbreak
  
  ### Death Knight Spells
  
  <div style='column-count:2'>
  
  ##### 1st Level
  Absorb Elements ^XGE^
  <br> Bane
  <br> Cause Fear ^XGE^
  <br> ✦ Chains of Ice
  <br> Command
  <br> Compelled Duel
  <br> ✦ Corpse Explosion
  <br> ✦ Death Grip
  <br> Detect Evil and Good
  <br> Detect Magic
  <br> Detect Poison and Disease
  <br> ✦ Dread Favor
  <br> Fog Cloud
  <br> Heroism
  <br> Ice Knife ^XGE^
  <br> ✦ Icy Touch
  <br> Prot. from Evil and Good
  <br> Ray of Sickness
  <br> Thunderous Smite
  <br> Wrathful Smite
  
  ##### 2nd Level
  ✦ Anti-Magic Shell
  <br> Augury
  <br> Blindness/Deafness
  <br> ✦ Blood Boil
  <br> Calm Emotions
  <br> Crown of Madness
  <br> Darkvision
  <br> Find Steed
  <br> Gentle Repose
  <br> Hold Person
  <br> ✦ Howling Blast
  <br> ✦ Icebound Fortitude
  <br> Ray of Enfeeblement
  <br> Silence
  <br> Snilloc's Snowball <br>&nbsp;&nbsp;&nbsp; Swarm ^XGE^
  <br> Zone of Truth
  
  ##### 3rd Level
  Animate Dead
  <br> ✦ Asphyxiate
  <br> Bestow Curse
  <br> Clairvoyance
  <br> Dispel Magic
  <br> Enemies Abound ^XGE^
  <br> Fear
  <br> Feign Death
  <br> Gaseous Form
  <br> Life Transference ^XGE^
  <br> ✦ Mantle of the <br>&nbsp;&nbsp;&nbsp; Fallen Crusader
  <br> Phantom Steed
  <br> Sleet Storm
  <br> Speak with Dead
  <br> Vampiric Touch
  <br> Water Walk
  
  \columnbreak
  
  ##### 4th Level
  Arcane Eye
  <br> Banishment
  <br> Blight
  <br> ✦ Conjure Undead
  <br> ✦ Death and Decay
  <br> Death Ward
  <br> Divination
  <br> ✦ Dominate Undead
  <br> Find Greater Steed ^XGE^
  <br> Ice Storm
  <br> Phantasmal Killer
  <br> Sickening Radiance ^XGE^
  <br> Staggering Smite
  <br> Stoneskin
  <br> Vitriolic Sphere ^XGE^
  
  ##### 5th Level
  Antilife Shell
  <br> ✦ Army of the Dead
  <br> Banishing Smite
  <br> Circle of Power
  <br> Danse Macabre ^XGE^
  <br> ✦ Death Chain
  <br> ✦ Deathwyrm's Fury
  <br> Dispel Evil and Good
  <br> Enervation ^XGE^
  <br> Hallow
  <br> Hold Monster
  <br> Negative Energy Flood ^XGE^
  <br> ✦ Unholy Weapon
  
  </div>
  
  <div class='footnote'>PART 2 | SPELLS </div>
  
  \pagebreakNum
  
  ### Druid Spells
   
  <div style='column-count:2'>
  
  ##### Cantrips (0 Level)
  Dancing Lights
  <br> Druidcraft
  <br> Guidance
  <br> ✦ Lunar Strike
  <br> Primal Savagery ^XGE^
  <br> Resistance
  <br> Shape Water ^XGE^
  <br> Shillelagh
  <br> ✦ Solar Wrath
  <br> Thorn Whip
  
  ##### 1st Level
  Animal Friendship
  <br> Beast Bond ^XGE^
  <br> Cure Wounds
  <br> Detect Magic
  <br> Detect Poison and Disease
  <br> Earth Tremor ^XGE^
  <br> Entangle
  <br> Expeditious Retreat
  <br> Faerie Fire
  <br> Fog Cloud
  <br> Goodberry
  <br> Healing Word
  <br> Jump
  <br> Longstrider
  <br> Purify Food and Drink
  <br> Sleep
  <br> Snare ^XGE^
  <br> Speak with Animals
  <br> ✦ Starfire
  
  ##### 2nd Level
  Animal Messenger
  <br> Barkskin
  <br> Beast Sense
  <br> ✦ Cyclone
  <br> Darkvision
  <br> Dust Devil ^XGE^
  <br> Enhance Ability
  <br> Gust of Wind
  <br> Hold Person
  <br> Lesser Restoration
  <br> Locate Animals or Plants
  <br> Moonbeam
  <br> Pass without Trace
  <br> Protection from Poison
  <br> Skywrite ^XGE^
  <br> Spike Growth
  <br> Warding Wind ^XGE^
 
  \columnbreak
  
  ##### 3rd Level
  Catnap ^XGE^
  <br> Conjure Animals
  <br> Daylight
  <br> Dispel Magic
  <br> Feign Death
  <br> Magic Circle
  <br> Mass Healing Word
  <br> Plant Growth
  <br> Protection from Energy
  <br> Revivify
  <br> Speak with Plants
  <br> ✦ Starsurge
  <br> Water Breathing
  <br> Wind Wall
  
  ##### 4th Level
  Blight
  <br> Charm Monster ^XGE^
  <br> Confusion
  <br> Conjure Woodland Beings
  <br> Dominate Beast
  <br> Freedom of Movement
  <br> Grasping Vine
  <br> Guardian of Nature
  <br> Hallucinatory Terrain
  <br> Locate Creature
  <br> ✦ Ursol's Vortex
  <br> Watery Sphere ^XGE^
  
  ##### 5th Level
  Awaken
  <br> Commune with Nature
  <br> Control Winds ^XGE^
  <br> Dawn ^XGE^
  <br> Dream 
  <br> Geas
  <br> Greater Restoration
  <br> Mass Cure Wounds
  <br> Scrying
  <br> Tree Stride
  <br> Wrath of Nature ^XGE^
  
  ##### 6th Level
  Conjure Fey
  <br> Druid Grove ^XGE^
  <br> ✦ Eclipse
  <br> Find the Path
  <br> Heal
  <br> Investiture of Wind ^XGE^
  <br> ✦ Starfall
  <br> Sunbeam
  <br> Transport via Plants
  <br> Wall of Thorns
  <br> Wind walk
  
  </div>
  
  \columnbreak
  
  <div style="height:27px"></div>
  
  <div style='column-count:2'>
  
  ##### 7th Level
  Crown of Stars ^XGE^
  <br> Mirage Arcane
  <br> Regenerate
  <br> Reverse Gravity
  <br> Whirlwind ^XGE^
  
  ##### 8th Level
  Animal Shapes
  <br> Control Weather
  <br> Feeblemind
  <br> Sunburst
  
  ##### 9th Level
  Foresight
  <br> Mass Heal
  <br> Shapechange
  <br> Storm of Vengeance
  <br> True Resurrection
  
  \columnbreak
  
  </div>
  
  <div class='footnote'>PART 2 | SPELLS </div>
  
  \pagebreakNum
  
  ### Mage Spells
  
  <div style='column-count:2'>
  
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
  <br/> Shape Water ^XGE^
  
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
  <br/> Frost Fingers ^IDRotF^
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
  <br/> Cloud of Daggers
  <br/> Continual Flame
  <br/> Darkness
  <br/> Darkvision
  <br/> Detect Thoughts
  <br/> Dragon's Breath ^XGE^
  <br/> Enlarge/Reduce
  <br/> Flame Arrows
  <br/> Flame Blade
  
  \columnbreak
  
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
  
  </div>
  
  \columnbreak
  
  <div style="height:27px"></div>
  
  <div style='column-count:2'>
  
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

  \columnbreak

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
  
  > ##### Variant Rule: Wizardry
  > This list holds spells that are not in line with the Warcraft fantasy for mages, but a Dungeon Master could still allow a mage to learn.
  >
  > Some deal in necromancy or demonology, magic forbidden by most conclaves of magi, while others are powerful Wizard spells with no real equivalent in the Warcraft universe. 
  > <br/> 
  > <br/> 
  >##### Cantrips (0 Level) 
  > Chill Touch
  > <br/> ✦ Decompose
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
  > Create Magen ^IDRotF^
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
  
  ### Paladin Spells
  
  <div style='column-count:2'>
  
  ##### 1st Level
  Bane
  <br> Bless
  <br> Ceremony ^XGE^
  <br> Command
  <br> Compelled Duel
  <br> Cure Wounds
  <br> Detect Evil and Good
  <br> Divine Favor
  <br> Healing Word
  <br> Heroism
  <br> Prot. from Evil and Good
  <br> ✦ Repentance
  <br> Sanctuary
  <br> Searing Smite
  <br> Shield of Faith
  <br> Thunderous Smite
  <br> Wrathful Smite
  
  ##### 2nd Level
  Aid
  <br> Branding Smite
  <br> Enhance Ability
  <br> Find Steed
  <br> Flame Blade
  <br> ✦ Guardian of the King
  <br> ✦ Holy Prism
  <br> Lesser Restoration
  <br> Magic Weapon
  <br> Prayer of Healing
  <br> Protection from Poison
  <br> ✦ Righteous Smite
  <br> Warding Bond
  <br> Zone of Truth
  
  ##### 3rd Level
  Aura of Vitality
  <br> Beacon of Hope
  <br> ✦ Beacon of Light
  <br> ✦ Blinding Light
  <br> Blinding Smite
  <br> Crusader's Mantle
  <br> Daylight
  <br> Dispel Magic
  <br> ✦ Holy Wrath
  <br> Life Transference ^XGE^
  <br> Magic Circle
  <br> Mass Healing Word
  <br> Phantom Steed
  <br> Protection from Energy
  <br> Remove Curse
  <br> Revivify
  
  \columnbreak
  
  ##### 4th Level
  Aura of Life
  <br> Aura of Purity
  <br> Death Ward
  <br> ✦ Divine Shield
  <br> Find Greater Steed ^XGE^
  <br> Guardian of Faith
  <br> Locate Creature
  <br> Staggering Smite
  
  ##### 5th Level
  Banishing Smite
  <br> Circle of Power
  <br> Destructive Wave
  <br> Dispel Evil and Good
  <br> Hallow
  <br> Holy Weapon ^XGE^
  <br> ✦ Light of the Protector
  <br> Mass Cure Wounds
  <br> Raise Dead
  <br> Scrying
  <br> Wall of Light ^XGE^
  
  </div>
  
  <div class='footnote'>PART 2 | SPELLS </div>
  
  \pagebreakNum
  
  ### Priest Spells
  
  <div style='column-count:2'>
  
  ##### Cantrips (0 Level)
  Guidance 
  <br> Light 
  <br> Mending 
  <br> ✦ Mind Blast 
  <br> Resistance 
  <br> Sacred Flame 
  <br> Spare the Dying 
  <br> Thaumaturgy 
  <br> Toll the Dead ^XGE^
  <br> Word of Radiance ^XGE^
  
  ##### 1st Level
  ✦ Angelic Feather 
  <br> Arms of Hadar 
  <br> Bless 
  <br> Cause Fear ^XGE^
  <br> Ceremony ^XGE^
  <br> Charm Person 
  <br> Cure Wounds 
  <br> ✦ Dark Void 
  <br> Detect Evil and Good 
  <br> Detect Magic 
  <br> Detect Poison and Disease 
  <br> Guiding Bolt 
  <br> Healing Word 
  <br> Heroism 
  <br> ✦ Inner Fire 
  <br> Inflict Wounds 
  <br> ✦ Mind Vision 
  <br> Prot. from Evil and Good 
  <br> Purify Food and Drink 
  <br> Sanctuary 
  <br> Shield 
  <br> Shield of Faith 
  
  ##### 2nd Level
  Aid 
  <br> Blindness/Deafness 
  <br> Calm Emotions 
  <br> Crown of Madness 
  <br> ✦ Exorcism 
  <br> ✦ Fade 
  <br> Gentle Repose 
  <br> Gift of Gab ^AI^
  <br> Healing Spirit ^XGE^
  <br> Hold Person 
  <br> Invisibility 
  <br> ✦ Inner Focus 
  <br> ✦ Inner Will 
  <br> Lesser Restoration 
  <br> Levitate
  <br> ✦ Mind Flay 
  <br> Mind Spike ^XGE^
  <br> Prayer of Healing 
  <br> Protection from Poison 
  <br> ✦ Shackle Undead 
  <br> ✦ Shining Force 
  <br> Silence 
  <br> Suggestion 
  <br> Tasha's Mind Whip ^TCE^
  
  \columnbreak
  
  ##### 3rd Level
  Animate Dead 
  <br> Aura of Vitality 
  <br> Beacon of Hope 
  <br> Bestow Curse 
  <br> Daylight 
  <br> Dispel Magic 
  <br> ✦ Divine Star 
  <br> Enemies Abound ^XGE^
  <br> Fast Friends ^AI^
  <br> Fear 
  <br> Feign Death 
  <br> Gaseous Form 
  <br> Glyph of Warding 
  <br> Hunger of Hadar 
  <br> ✦ Holy Nova 
  <br> Intellect Fortress ^TCE^
  <br> Life Transference ^XGE^
  <br> Magic Circle 
  <br> Mass Healing Word 
  <br> Motivational Speech ^AI^
  <br> Protection from Energy 
  <br> ✦ Psychic Horror 
  <br> Remove Curse 
  <br> Revivify 
  <br> Speak with Dead 
  <br> Spirit Guardians 
  <br> Tongues 
  <br> Vampiric Touch 
  <br> ✦ Void Shift 
  
  ##### 4th Level
  Aura of Purity 
  <br> Banishment 
  <br> Charm Monster ^XGE^
  <br> Death Ward 
  <br> ✦ Devouring Plague 
  <br> Divination 
  <br> Freedom of Movement 
  <br> Greater Invisibility
  <br> Guardian of Faith 
  <br> Locate Creature 
  <br> ✦ Luminous Barrier 
  <br> Phantasmal Killer 
  <br> Raulothim's Psychic Lance ^FTD^
  <br> Shadow of Moil ^XGE^
  <br> Sickening Radiance ^XGE^
  <br> ✦ Shadowy Apparitions 
  <br> ✦ Summon Void Being 
  
  </div>
  
  \columnbreak
  
  <div style="height:27px"></div>
  
  <div style='column-count:2'>
  
  ##### 5th Level
  Dawn ^XGE^
  <br> Dispel Evil and Good 
  <br> Dominate Person 
  <br> Geas 
  <br> Greater Restoration 
  <br> Hallow 
  <br> Legend Lore 
  <br> Mass Cure Wounds 
  <br> Modify Memory
  <br> Negative Energy Flood ^XGE^
  <br> Raise Dead
  <br> Rary's Telepathic Bond
  <br> Scrying
  <br> ✦ Shadow Crash
  <br> Skill Empowerment ^XGE^
  <br> Synaptic Static ^XGE^
  <br> Wall of Light ^XGE^
  
  ##### 6th Level
  ✦ Archangel 
  <br> Eyebite 
  <br> Find the Path 
  <br> Harm 
  <br> Heal 
  <br> ✦ Mass Dispel 
  <br> Mass Suggestion 
  <br> Mental Prison ^XGE^
  <br> ✦ Schism 
  <br> True Seeing 
  <br> Word of Recall 
  
  ##### 7th Level
  Divine Word 
  <br> Etherealness 
  <br> ✦ Halo 
  <br> Regenerate 
  <br> Resurrection 
  <br> Symbol 
  <br> Temple of the Gods ^XGE^
  <br> Tether Essence ^EGW^
  
  ##### 8th Level
  Abi-Dalzim's <br>&nbsp;&nbsp;&nbsp; Horrid Wilting ^XGE^
  <br> Antimagic Field 
  <br> Dark Star ^EGW^
  <br> Dominate Monster 
  <br> Feeblemind 
  <br> Holy Aura 
  <br> Maddening Darkness ^XGE^
  <br> Mind Blank 
  <br> Power Word Stun 
  
  ##### 9th Level
  ✦ Apotheosis 
  <br> Foresight 
  <br> Mass Heal 
  <br> Power Word Heal 
  <br> Power Word Kill 
  <br> Psychic Scream ^XGE^
  <br> ✦ Salvation 
  <br> True Resurrection 
  
  \columnbreak
  
  </div>
  
  <div class='footnote'>PART 2 | SPELLS </div>
  
  \pagebreakNum
  
  ### Shaman Spells
  
  <div style='column-count:2'>
  
  ##### Cantrips (0 Level)
  Booming Blade ^SCAG^
  <br> Control Flames ^XGE^
  <br> Create Bonfire ^XGE^
  <br> Fire Bolt
  <br> Frostbite ^XGE^
  <br> Gust ^XGE^
  <br> ✦ Invoke Elements
  <br> ✦ Lightning Blast
  <br> Lightning Lure ^SCAG^
  <br> Mending
  <br> Mold Earth ^XGE^
  <br> Produce Flame
  <br> Shape Water ^XGE^
  <br> Shocking Grasp
  <br> Thunderclap ^XGE^
  
  ##### 1st Level
  Absorb Elements ^XGE^
  <br> Create or Destroy Water
  <br> Cure Wounds
  <br> Detect Magic
  <br> Detect Poison and Disease
  <br> Earth Tremor ^XGE^
  <br> ✦ Elemental Shock
  <br> Fog Cloud
  <br> ✦ Lightning Shield
  <br> Searing Smite
  <br> Thunderous Smite
  <br> Thunderwave
  
  ##### 2nd Level
  Augury
  <br> Continual Flame
  <br> Dust Devil ^XGE^
  <br> Gust of Wind
  <br> Healing Spirit ^XGE^
  <br> Heat Metal
  <br> ✦ Lava Burst
  <br> Lesser Restoration
  <br> Maximilian's <br>&nbsp;&nbsp;&nbsp; Earthen Grasp ^XGE^
  <br> Protection from Poison
  <br> Shatter
  <br> Skywrite ^XGE^
  <br> Warding Wind ^XGE^

  ##### 3rd Level
  Call Lightning
  <br> ✦ Chain Heal
  <br> Counterspell
  <br> Dispel Magic
  <br> ✦ Earthen Spike
  <br> Erupting Earth ^XGE^
  <br> Lightning Bolt
  <br> Magic Circle
  <br> Meld Into Stone
  <br> Protection from Energy
  <br> Revivify
  <br> Spirit Guardians
  <br> Thunder Step ^XGE
  <br> Tidal Wave ^XGE^
  
  \columnbreak
  
  <br> Wall of Water ^XGE^
  <br> Water Breathing
  <br> Water Walk
  <br> Wind Wall
  
  ##### 4th Level
  Conjure Minor Elementals
  <br> Control Water
  <br> Elemental Bane ^XGE^
  <br> Freedom of Movement
  <br> Locate Creature
  <br> Polymorph
  <br> Stone Shape
  <br> Stoneskin
  <br> Storm Sphere ^XGE^
  <br> Wall of Fire
  <br> Watery Sphere ^XGE^
  
  ##### 5th Level
  ✦ Bloodlust and Heroism
  <br> Commune with Nature
  <br> Conjure Elemental
  <br> Control Winds ^XGE^
  <br> Greater Restoration
  <br> ✦ Healing Rain
  <br> Legend Lore
  <br> Maelstrom ^XGE^
  <br> Mass Cure Wounds
  <br> ✦ Reincarnation
  <br> Scrying
  <br> Steel Wind Strike ^XGE^
  <br> Wall of Stone
  
  ##### 6th Level
  Bones of the Earth ^XGE^
  <br> Chain Lightning
  <br> Flesh to Stone
  <br> Investiture of Stone ^XGE^
  <br> Investiture of Wind ^XGE^
  <br> Move Earth
  <br> Primordial Ward ^XGE^
  <br> Wind Walk
  
  ##### 7th Level
  Etherealness
  <br> Prismatic Spray
  <br> Regenerate
  <br> Whirlwind ^XGE^
  
  ##### 8th Level
  Antimagic Field
  <br> ✦ Cataclysm
  <br> Control Weather
  <br> Earthquake
  <br> Tsunami
  
  ##### 9th Level
  Foresight
  <br> Imprisonment
  <br> Mass Heal
  <br> Storm of Vengeance
  <br> True Resurrection
  
  </div>
  
  \columnbreak
  
  ### Warlock Spells
  
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
  
  \columnbreak
  
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
  
  </div>
  
  <div class='footnote'>PART 2 | SPELLS </div>
  
  \pagebreakNum
  
  <div style='column-count:2'>
  
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
  
  \columnbreak
  
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
  
  \columnbreak
    
  > ##### Variant Rule: Xorothian Steed
  > Dungeon Masters might prefer making the creatures summoned by a warlock with the *find steed* and *find greater steed* fiends instead of the other creature types listed in those spells. Additionally, the *find greater steed* spell can summon a felsteed in addition to the other creatures listed.
  
  <div class='footnote'>PART 2 | SPELLS </div>
  
  \pagebreakNum
  
  > #### New Spells By Level
  >
  > These are all the new spells whose descriptions are found in the next section, across all classes in this book.
  >
  > <div style='column-count:2'>
  > 
  > ##### Cantrips (0 Level)
  > Arcane Blast
  > <br/> Decompose
  > <br/> Diabolism
  > <br/> Fel Flame
  > <br/> Flurry
  > <br/> Invoke Elements
  > <br/> Lightning Blast
  > <br/> Lunar Strike
  > <br/> Mind Blast
  > <br/> Shadow Bolt
  > <br/> Shadow Glide
  > <br/> Solar Wrath
  > <br/> Touch of Chaos
  >
  > <br/><div style='margin-top:-15px;'></div>
  > 
  > ##### 1st Level
  > Angelic Feather
  > <br/> Chains of Ice
  > <br/> Corpse Explosion
  > <br/> Dark Void
  > <br/> Death Grip
  > <br/> Demon Skin
  > <br/> Drain Life
  > <br/> Dread Favor
  > <br/> Elemental Shock
  > <br/> Frostfire Bolt
  > <br/> Icy Touch
  > <br/> Lightning Shield
  > <br/> Mind Vision
  > <br/> Repentance
  > <br/> Starfire
  >
  > <br/><div style='margin-top:-15px;'></div>
  > 
  > ##### 2nd Level
  > Anti-Magic Shell
  > <br/> Blood Boil
  > <br/> Create Healthstone
  > <br/> Cyclone
  > <br/> Freezing Touch
  > <br/> Living Bomb
  > <br/> Guardian of the King
  > <br/> Holy Prism
  > <br/> Howling Blast
  > <br/> Icebound Fortitude
  > <br/> Lava Burst
  > <br/> Mind Flay
  > <br/> Righteous Smite
  > <br/> Shackle Undead
  > <br/> Shining Force
  >
  > <br/><div style='margin-top:-15px;'></div>
  > 
  > ##### 3rd Level
  > Arcane Explosion
  > <br/> Asphyxiate
  > <br/> Beacon of Light
  > <br/> Blinding Light
  > <br/> Blizzard
  > <br/> Chain Heal
  > <br/> Divine Star
  >
  > <br/><div style='margin-top:-19px;'></div>
  > 
  > <br/> Earthen Spike
  > <br/> Holy Wrath
  > <br/> Mantle of the Fallen 
  > <br/>&nbsp; Crusader
  > <br/> Spellsteal
  > <br/> Starsurge
  >
  > <br/><div style='margin-top:-15px;'></div>
  > 
  > ##### 4th Level
  > Amplify or Dampen Magic
  > <br/> Arcane Barrage
  > <br/> Conjure Undead
  > <br/> Death and Decay
  > <br/> Divine Shield
  > <br/> Dominate Undead
  > <br/> Fire and Brimstone
  > <br/> Ice Block
  > <br/> Ursol's Vortex
  > <br/> Void Shift
  >
  > <br/><div style='margin-top:-15px;'></div>
  > 
  > ##### 5th Level
  > Army of the Dead
  > <br/> Bloodlust and Heroism
  > <br/> Create Soulstone
  > <br/> Death Chain
  > <br/> Deathwyrm's Fury
  > <br/> Healing Rain
  > <br/> Light of the Protector
  > <br/> Rain of Fire
  > <br/> Reincarnation
  > <br/> Ritual of Summoning
  > <br/> Shackle Undead
  > <br/> Shadow Crash
  > <br/> Shining Force
  > <br/> Unholy Weapon
  > 
  > <br/><div style='margin-top:-15px;'></div>
  > 
  > ##### 6th Level
  > Create Soulwell
  > <br/> Eclipse
  > <br/> Shadowfury
  > <br/> Starfall
  > 
  > <br/><div style='margin-top:-15px;'></div>
  > 
  > ##### 7th Level
  > Glacial Spike
  > <br/> Pyroblast
  > 
  > <br/><div style='margin-top:-15px;'></div>
  > 
  > ##### 8th Level
  > Alexstraza's Fury
  > <br/> Cataclysm
  > <br/> Ice Nova
  > 
  > <br/><div style='margin-top:-15px;'></div>
  > 
  > ##### 9th Level
  > Jaina's Flying Ship
  > 
  > </div>
  
  <img src='https://www.gmbinder.com/images/72nPPab.jpg' style='position:absolute; top:0px; right:-250px; height:100%' />
  <img src='https://www.gmbinder.com/images/9wnUwNO.png' style='position:absolute; top:0px; left:-300px; height:100%; transform:scaleX(-1)' />
  
  <div class='footnote'>PART 2 | SPELLS </div>
  
  \pagebreakNum
  
  ## Spell Descriptions
  The new spells are presented in alphabetical order.
  
  #### Alextrasza’s Fury
  *8th-level evocation*
  ___
  - **Casting Time:** 1 action
  - **Range:** Self (60-foot cone)
  - **Components:** V, S
  - **Duration:** Instantaneous
  ___
  Your hands burst into flames as you push a roaring wave of fire outward from yourself. Each creature in a 60-foot cone must make a Constitution saving throw. On a failed save, a target takes 12d6 fire damage and is stunned until the end of their next turn. On a successful save, a target takes half as much damage and isn't stunned. The fire spreads around corners. It ignites flammable objects in the area that aren’t being worn or carried. A creature killed by this spell is reduced to ash.
  
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
  
  #### Angelic Feather
  *2nd-level enchantment*
  ___
  - **Casting Time:** 1 action
  - **Range:** Touch
  - **Components:** V, S, M (a feather)
  - **Duration:** Concentration, up to 1 minute
  ___
  You touch one creature within reach, granting it the swiftness of an angelic being. For the duration of the spell, the creature can take the Dash and Disengage action as a bonus action on its turn, and gains resistance to fall damage.
  
  \columnbreak
  
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
  You draw from the fluctuating arcane near you and burst with a wave of arcane power. Each other creature within range must make a Dexterity saving throw. On a failed save, a target takes 6d8 force damage and can't take reactions until the start of its next turn. On a successful save, a target takes half as much damage and can use its reactions as normal.
  
  ***At Higher Levels.*** When you cast this spell using a spell slot of 4th level or higher, the damage increases by 1d8 for each slot level above 3rd.
  
  \columnbreak
  
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
  
  ___
  ___
  > ## Shambling Horde
  >*Gargantuan horde of Medium undead, chaotic evil*
  > ___
  > - **Armor Class** 8
  > - **Hit Points** 145 (10d20 + 40)
  > - **Speed** 20 ft.
  >___
  >|STR|DEX|CON|INT|WIS|CHA|
  >|:---:|:---:|:---:|:---:|:---:|:---:|
  >|25 (+7)|6 (-2)|18 (+4)|3 (-4)|6 (-2)|5 (-3)|
  >___
  > - **Saving Throws** Wis +2
  > - **Damage Immunities**  poison
  > - **Condition Immunities** blinded, charmed, deafened, exhaustion, frightened, grappled, incapacitated, paralyzed, petrified, poisoned, prone, restrained, stunned, unconscious
  > - **Senses** darkvision 60 ft., passive perception 8
  > - **Languages** —
  > - **Challenge** 8 (3,900 XP)
  > ___
  > ***Flesh-Eating Compulsion.*** The horde can share a space with another creature. If a creature that is not an un&shy;dead or a construct share a space with the horde at the beginning of the horde's turn, the horde is incapa&shy;citated (ignoring its incapacitated immunity) and the creature is engulfed. While engulfed, the creature is restrained, and it takes 21 (6d6) piercing damage at the start of each of the horde's turns, or 10 (3d6) piercing damage if the horde has half of its hit points or fewer, and the creature must succeed on a DC 15 Constitution saving throw or become infected with the shambling death disease. 
  >
  > \columnbreak
  >
  > <br>&nbsp;&nbsp; A diseased creature can't regain hit points until the disease is cured. For every 24 hours that elapse, the target must repeat the saving throw, reducing its hit point maximum by 10 (3d6) on a failure. The target dies if the disease reduces its hit point maximum to 0. This reduction to the target's hit point maximum lasts until the disease is cured.
  <br>&nbsp;&nbsp; Engulfed creatures can try to escape by making a DC 18 Strength check as an action. On a success, the creature escapes and enters a space of its choice within 5 feet of the shambling horde.
  >
  > ***Horde.*** The horde can occupy the space of a Large or smaller creature and vice versa, and the horde can move through any opening large enough for a Medium zombie. The horde can’t regain hit points or gain temporary hit points.
  >
  > ***Undead Fortitude.*** If the horde takes damage, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the horde takes no damage instead.
  >
  > ### Actions
  > ***Multiattack.*** The shambling horde can make up to three Slams attacks, and each attack must be against a different target.
  >
  > ***Slams.*** *Melee Weapon Attack:* +10 to hit, reach 5 ft., one target. *Hit:* 21 (6d6) bludgeoning damage, or 10 (3d6) bludgeoning damage if the horde has half of its hit points or fewer. If the target is Large or smaller, it is also grappled (escape DC 18).
  
  <div class='footnote'>PART 2 | SPELLS </div>
  
  \pagebreakNum
  
  #### Army of the Dead
  *5th-level necromancy*
  ___
  - **Casting Time:** 1 action
  - **Range:** Self
  - **Components:** V, S, M (brain matter from a humanoid killed within the past 24 hours)
  - **Duration:** Concentration, up to 1 minute
  ___
  You voice profane words, and summon an army of the dead to kill and consume everything in its path. A horde of sham&shy;bling corpses appears around you, and disappears when it drops to 0 hit points or when the spell ends.
  
  Roll initiative for the horde, which has its own turns. You cannot control the horde. It spends its turns pursing and attacking the nearest nonundead to the best of its ability. <br> It will use its Slams action to attack and grapple creatures before moving to occupy its victims’ spaces and engulf them on the next turn with its Flesh-Eating Compulsion feature. If no creatures are within its reach, the horde will use its full movement to approach any nonundead crea&shy;tures it can see or hear. If no such creatures are evident, it will mindlessly follow you until targets present themselves.
  
  When you first cast this spell, you can designate any number of creatures that you can see to be ignored by the shambling horde, and which will be unaffected by its Flesh-Eating Compulsion feature. If you stop concentrating on the spell before it reaches its full duration, the horde remains for 1d6 rounds if it still has hit points, and no longer ignores these creatures.
  
  #### Asphyxiate
  *3rd-level necromancy*
  ___
  - **Casting Time:** 1 action
  - **Range:** 30 feet
  - **Components:** S
  - **Duration:** Concentration, up to 1 minute
  ___
  Shadowy tendrils extend from you and swirl around the throat of a creature you can see within range. The target must make a successful Constitution saving throw or be restrained and incapacitated for the spells duration. While restrained in this way, the target is unable to speak. At the end of each of its turns, the target can make another Constitution saving throw. On a success, the spell ends on the target.
  
  #### Beacon of Light
  *3rd-level evocation*
  ___
  - **Casting Time:** 1 bonus action
  - **Range:** 60 feet
  - **Components:** V, S
  - **Duration:** Concentration, up to 10 minutes
  ___
  You extend your hand a place a holy mark on a creature within range. Whenever you restore hit points to a target with a spell slot, the marked creature regains a number of hit points equal to your spellcasting modifier. The spell ends if the creature is ever outside the spell's range.
  
  \columnbreak
  
  #### Blinding Light
  *3rd-level evocation*
  ___
  - **Casting Time:** 1 action
  - **Range:** Self (30-foot-radius)
  - **Components:** V, S
  - **Duration:** Instantaneous
  ___
  You cause dazzling light to burst forth around you. Each creature within a 30-foot-radius of you must succeed on a Constitution saving throw, or be blinded for 1 minute or until it takes damage. 
  
  A creature blinded by this spell can make another Constitution saving throw at the end of each of its turns. On a successful save, it is no longer blinded.
  
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
  
  
  #### Blood Boil
  *2nd-level necromancy*
  ___
  - **Casting Time:** 1 bonus action
  - **Range:** Self (15-foot radius)
  - **Components:** V, S
  - **Duration:** Instantaneous
  ___
  You reach out with unholy power, causing the blood in the veins of nearby creatures to boil. Each creature you choose within 15 feet of you must succeed on a Constitution saving throw or take 2d4 fire damage plus 2d4 necrotic damage. <br> A creature that succeeds on its saving throw takes half as much damage. Creatures that have no blood or vital fluids are immune to the effects of this spell.
  
  ***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, the fire and necrotic damage each increase by 1d4 for each slot level above 2nd.
  
  <div class='footnote'>PART 2 | SPELLS </div>
  
  \pagebreakNum
  
  #### Bloodlust and Heroism
  *5th-level enchantment*
  ___
  - **Casting Time:** 1 action
  - **Range:** self (30-feet radius)
  - **Components:** V, S
  - **Duration:**  Concentration, up to 1 minute
  ___
  You imbue creatures of your choice within range with the will and determination to fight harder. Each target gains the following benefits for the duration of the spell.
  
  - The target is immune to being frightened and any frightened condition on the target is surpressed for the spell's duration.
  - Whenever the target makes an attack roll or a saving throw before the spell ends, the target can roll a d4 and add the number rolled to the attack roll or saving throw.
  - The target gains temporary hit points equal to your spellcasting ability modifier at the start of each of its turns. When the spell ends, the target loses any remaining temporary hit points from this spell. 
  
  #### Cataclysm
  *8th-level conjuration*
  ___
  - **Casting Time:** 1 action
  - **Range:** 150 feet
  - **Components:** V, S, M (a piece of charcoal)
  - **Duration:** Instantaneous
  ___
  You cause the ground to crack and split, with molten magma and fire spitting up out in a 60-foot radius centered on a point within range. Each creature in the area must make a Dexterity saving throw or take 10d6 fire damage, taking half damage on a success.
  
  A creature who takes fire damage from the initial damage of this spell is set aflame, taking an additional 2d6 fire damage at the beginning of each of their turns. They or another adjacent creature can use their action to put out the flames, taking 1d6 fire damage in the process.
  
  The ground in the area of this spell remains damaged, turning into difficult terrain. It remains hot for 1 minute, and any creature who enters the area for the first time on their turn or starts their turn there takes 1d6 fire damage.
  
  #### Chain Heal
  *3rd-level evocation*
  ___
  - **Casting Time:** 1 action
  - **Range:** 30 feet (15-feet between targets)
  - **Components:** V, S
  - **Duration:** Instantaneous
  ___
  A beam of restorative energies surges through a friendly creatures. Choose a target you can see within range, then choose a target you can see within range of it, and another within range of the second target. You can't choose the same target more than once. Each target chosen by this spell regains a number of hit points equal to 2d4 + your spellcasting ability modifier. This spell has no effect on undead or constructs.
  
  ***At Higher Levels.*** When you cast this spell using a spell slot of 4th level or higher, the chain heal surges through one additional target for each slot level above 3rd.
  
  \columnbreak
  
  #### Chains of Ice
  *1st-level evocaation*
  ___
  - **Casting Time:** 1 action
  - **Range:** 60 feet
  - **Components:** V
  - **Duration:** 1 minute
  ___
  Frost ridden chains erupt from the ground beneath a target that you can see within range. The target must succeed on a Strength saving throw, or have their movement speed halved for the spell’s duration.
  
  The chained target must make a Strength saving throw at the end of each of its turns. On a successful save, the chains break and the spell ends on the target.
  
  ***At Higher Levels.*** When you cast this spell using a spell slot of 2nd level or higher, you can target one additional creature for each slot level above 2nd.
  
  #### Conjure Undead
  *4th-level conjuration*
  ___
  - **Casting Time:** 1 action
  - **Range:** 60 feet
  - **Components:** V, S, M (viscera from a creature killed <br> within the past 24 hours)
  - **Duration:** Concentration, up to 1 hour
  ___
  You summon a powerful undead being from the crypts and slaughterhouses of Northrend. You choose the undead’s type, which must be one of challenge rating 5 or lower, such as a revenant or wraith. The undead appears in an unoccupied space you can see within range, and the undead disappears when it drops to 0 hit points or when the spell ends.
  
  Roll initiative for the undead, which has its own turns. When you summon it and on each of your turns thereafter, you can issue a verbal command to it (requiring no action on your part), telling it what it must do on its next turn. If you issue no command, it spends its turn attacking any creature within reach that has attacked it.
  
  If you stop concentrating on the spell before it reaches its full duration, the undead spends the rest of the spell’s duration pursuing and attacking the nearest non-undead to the best of its ability.
  
  ***At Higher Levels.*** When you cast this spell using a spell slot of 5th level or higher, the challenge rating increases by 1 for each slot level above 4th.
  
  <div class='footnote'>PART 2 | SPELLS </div>
  
  \pagebreakNum
  
  #### Corpse Explosion
  *1st-level necromancy*
  ___
  - **Casting Time:** 1 action
  - **Range:** 120 feet
  - **Components:** S, M (a corpse, which the spell destroys)
  - **Duration:** Instantaneous
  ___
  The corpse of a recently deceased creature rapidly bloats at your command and erupts in a gruesome explosion. You target the corpse of a creature that's been dead for no longer than 1 minute that you can see within range. Each creature within 5 feet of that corpse must make a Dexterity saving throw. A target takes 2d6 necrotic damage on a failed save, or half as much damage on a successful one. The radius of the explosion increases by 5 feet for every size category of the corpse above Medium.
  
  A corpse detonated in this way is destroyed and cannot be raised or resurrected by any ability that requires a com&shy;plete corpse. Not all creatures leave a corpse; construts and oozes almost never do, neither do incorporeal undead. 
  
  ***At Higher Levels.*** When you cast this spell using a spell slot of 2nd level or higher, the damage increases by 2d6 for each slot level above 1st.
  
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
  
  \columnbreak
  
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
  
  #### Cyclone
  *2nd-level conjuration*
  ___
  - **Casting Time:** 1 action
  - **Range:** 60 feet
  - **Components:** V, S
  - **Duration:** Concentration, up to 1 minute
  ___
  A whirl of wind forms around a Large or smaller creature that you can see within range. The target must make a Strength saving throw. On a failed save, the target is lifted off the ground and is restrained for the spell's duration.
  
  As an action, you can cause the cyclone to move up to 20 feet in a direction of your choice. A creature restrained by the cyclone moves with it. If the cyclone moves through a space too narrow for its restrained creature, the creature breaks out and the spell ends.
  
  To break out, the restrained target can use its action to make a Strength check against your spell save DC. On a success, the target escapes and is no longer restrained by the hand. The cyclone then vanishes.
  
  #### Dark Void
  *1st-level evocation*
  ___
  - **Casting Time:** 1 action
  - **Range:** 30 feet
  - **Components:** V, S, M (a holy symbol)
  - **Duration:** Instantaneous
  ___
  You pull on the veil separating reality and the void realm, creating small fissures where its maddening energies leak through. A creature within range and creatures of your choice within 5 feet of it, must succeed on a Wisdom saving throw or take 2d4 psychic damage on a failed save, or half as much damage on a successful one. A creature who fails this saving throw also can’t regain hit points for 1 round. 
  
  ***At Higher Levels.*** When you cast this spell using a spell slot of 2nd level or higher, the damage increases by 1d4 for each slot level above 1st.
  
  <div class='footnote'>PART 2 | SPELLS </div>
  
  \pagebreakNum
  
  #### Death and Decay
  *4th-level necromancy*
  ___
  - **Casting Time:** 1 action
  - **Range:** 60 feet
  - **Components:** V, S
  - **Duration:** Concentration, up to 1 minute
  ___
  You reach out towards a point you can see within range, creating a 20-foot radius sphere filled with festering, necro&shy;tic energy that withers and decays everything within it. When a creature enters the blighted area for the first time on a turn or starts its turn there, it must make a Constitu&shy;tion saving throw. On a failed save, the creature takes 4d8 necrotic damage. In addition, until the beginning of its next turn, the creature subtracts 1d4 from all of its attack rolls and saving throws, as if under the effect of the bane spell. On a successful save, the creature takes half as much damage, and suffers no additional effects.
  
  Undead creatures in the spell’s area take no damage, and are bolstered by its necrotic power. While standing in the spell’s area, undead creatures add 1d4 to their attack rolls and saving throws, as if under the effect of a bless spell.
  
  ***At Higher Levels.*** When you cast this spell using a spell slot of 5th level or higher, the damage increases by 1d8 for each slot level above 4th.
  
  #### Death Chain
  *5th-level necromancy*
  ___
  - **Casting Time:** 1 action
  - **Range:** Self (20-foot radius)
  - **Components:** V, S
  - **Duration:** Concentration, up to 1 minute
  ___
  Ghastly chains erupt from you towards up to three different creatures you can see within range. Make a ranged spell attack against each target. On a hit, a target takes 4d8 necrotic damage and becomes chained together with you and any other target hit for the spell's duration.
  
  Chained creatures must succeed on a Strength saving throw to move more than 20 feet away from you. On a successful save, the target breaks the chain, ending the spell’s effect on them. Whenever you or another chained creature takes damage from a weapon attack or spell, each other creature chained together (including you) takes psychic damage equal to half the damage taken.
  
  Damage you take through this spell does not prompt a Constitution saving throw to maintain concentration on it.
  #### Death Grip
  *1st-level evocation*
  ___
  - **Casting Time:** 1 bonus action
  - **Range:** 60 feet
  - **Components:** V, S
  - **Duration:** Instantaneous
  ___
  Necrotic energy grasps around a Huge or smaller creature you can see that is currently at least 10 feet away from you, and within the spell’s range. The creature must make a successful Strength saving throw or be moved to an empty space within 5 feet of you, and your next attack roll against them this turn is made with advantage.
  
  \columnbreak
  
  #### Deathwyrm's Fury
  *5th-level conjuration*
  ___
  - **Casting Time:** 1 action
  - **Range:** Self
  - **Components:** V, S, M (a scale from a slain dragon)
  - **Duration:** Instantaneous
  ___
  You summon a mighty undead dragon to breath destruction on your enemies. You choose where to summon an ember&shy;wyrm, frostwyrm, or vilewyrm. It appears hovering above you and unleashes its breath weapon, tainted by necrotic power, before vanishing.
  
  The spell fails if there is insufficient room for the dragon to appear (for example, you are in a narrow tunnel). Any living dragons that witness you cast this spell will almost surely view you as a sworn enemy, if they didn’t already.
  
  ***Emberwyrm.*** The dragon exhales fire in a 60-foot cone. Each creature in that area must make a Dexterity saving throw, taking 5d8 fire damage and 5d8 necrotic damage on a failed save, or half as much damage on a successful one.
  
  ***Frostwyrm.*** The dragon exhales an icy blast at a point within 120 feet. Each creature within 20 feet of that point must make a Dexterity saving throw, taking 5d8 cold damage and 5d8 necrotic damage on a failed save, or half as much damage on a successful one.
  
  ***Vilewyrm*** The dragon exhales acid in a 120-foot line <br>that is 10 feet wide. Each creature in that line must make a Dexterity saving throw, taking 5d8 acid damage and 5d8 necrotic damage on a failed save, or half as much damage on a successful one.
  
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
  
  
  <div class='footnote'>PART 2 | SPELLS </div>
  
  \pagebreakNum
  
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
  
  \columnbreak
  
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
  
  #### Divine Shield
  *4th-level abjuration*
  ___
  - **Casting Time:** 1 action
  - **Range:** Self
  - **Components:** V, S, M (a small silver mirror)
  - **Duration:** Concentration, up to 1 minute
  ___
  A ward of divine energy surrounds your body, warding you against attacks. For the duration, you are considered to be immune to damage dealt by weapon attacks, spells, and spell-like effects. The spell does not protect you against natural sources of damage, such as molten lava or falling.
  
  If you make an attack or cast a spell that affects an enemy creature, this spell ends.
  
  #### Dominate Undead
  *4th-level enchantment*
  ___
  - **Casting Time:** 1 action
  - **Range:** 60 feet
  - **Components:** V, S
  - **Duration:** Concentration, up to 1 minute
  ___
  You attempt to beguile an undead that you can see within range. It must succeed on a Wisdom saving throw or be charmed by you for the duration. If you or creatures that are friendly to you are fighting it, it has advantage on the saving throw.
  
  While the undead is charmed, you have a telepathic link with it as long as the two of you are on the same plane of existence. You can use this telepathic link to issue com&shy;mands to the creature while you are conscious (no action required), which it does its best to obey. You can specify a simple and general course of action, such as “Attack that creature,” “Run over there,” or “Fetch that object.” If the creature completes the order and doesn’t receive further direction from you, it defends and preserves itself to the best of its ability.
  
  You can use your action to take total and precise control of the target. Until the end of your next turn, the creature takes only the actions you choose, and doesn’t do anything that you don’t allow it to do. During this time, you can also cause the creature to use a reaction, but this requires you to use your own reaction as well.
  
  Each time the target takes damage, it makes a new Wisdom saving throw against the spell. If the saving throw succeeds, the spell ends.
  
  ***At Higher Levels.*** When you cast this spell with a <br> 5th-level spell slot, the duration is concentration, up to 10 minutes. When you use a 6th-level spell slot, the duration is concentration, up to 1 hour. When you use a 7th level or higher, the duration is concentration, up to 8 hours.
  
  <div class='footnote'>PART 2 | SPELLS </div>
  
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
  
  Make a ranged spell attack against that creature. On a hit, the target takes 1d8 necrotic damage, and on each of your subsequent turns for the duration, you can use your bonus action to deal 1d8 necrotic damage to the target automatically. Each time the target takes damage from this spell, you regain a number of hit points equal to half the damage dealt and their maximum hit point total is reduced by the same amount. This reduction lasts until they finish a long rest.
  
  On a miss, you can spend your action on subsequent turns within the spell’s duration to make another ranged spell attack against the same creature. The spell ends if you use your action to do anything else. 
  
  The spell ends if your target is more than 30 feet away from you or has total cover from you at the end of your turn. This spell has no effect on the creature if they are a construct or undead.
  
  ***At Higher Levels:*** When you cast this spell using a spell slot of 2nd level or higher, the initial damage increases by 1d8 for each slot level above 1st. The damage dealt as a bonus action also increases by 1d8 for every two slot levels above 1st.
  
  #### Dread Favor
  *1st-level necromancy*
  ___
  - **Casting Time:** 1 bonus action
  - **Range:** Self
  - **Components:** V, S 
  - **Duration:** Concentration, up to 1 minute
  ___
  You are empowered by the suffering of your victims. Until the spell ends, your weapon attacks deal an extra 1d4 necrotic damage on a hit.
  
  #### Earthen Spike
  *3rd-level transmutation*
  ___
  - **Casting Time:** 1 action
  - **Range:** 60 feet
  - **Components:** V, S, M (a granite pebble)
  - **Duration:** Concentration, up to 1 hour
  ___
  You place your hand on the ground and evoke the element of earth, erupting a spike of earth at a point within range. A 5-foot radius, 15-foot high spike of earth erupts from that point. Each creature within that area must make a Dexterity saving throw. On a failed save, a creature takes 6d8 bludgeoning damage, or half as much damage on a success. Each creature affected by this spike is pushed away from the point of the spell to the nearest empty space. A creature who failed the saving throw falls prone.
  
  The earthen spike remains for the duration of the spell or until your concentration is broken at which point it crumbles, leaving its area as difficult terrain. When it crumbles, each creature within 5 feet of it must succeed on a Dexterity saving throw or take 1d6 bludgeoning damage. 
  
  ***At Higher Levels.*** When you cast this spell using a spell slot of 4th level or higher, the damage increases by 1d8 for each slot level above 3rd.
  
  #### Eclipse
  *6th-level transmutation*
  ___
  - **Casting Time:** 1 minute
  - **Range:** Self (5-mile radius)
  - **Components:** V, S, M (a vial of water from a moonwell)
  - **Duration:** Up to 1 hour
  ___
  You evoke the goddess Elune to block out the rays of An'she within 5 miles of you for the duration. You must be in an outdoor area to cast this spell.
  
  When you cast this spell, an eclipse gradually blocks out any natural light over 1 minute, bathing any outdoor area in complete darkness. The eclipse also affects any light source with a clear path to the sky, changing bright light to dim light and dim light to darkness. When the spell ends, the eclipse gradually vanishes over the cause of 1 minute as natural light returns.
  
  #### Elemental Shock
  *1st-level evocation*
  ___
  - **Casting Time:** 1 action
  - **Range:** 60 feet
  - **Components:** V, S, M (a piece of brimstone, granite, glass, and a feather)
  - **Duration:** Instantaneous
  ___
  You manifest a burst of elemental force around a creature within range. You choose acid, cold, fire, lightning, or thunder for the shock you make, the creature must then make a Dexterity saving throw. Taking 3d8 of the chosen damage type on a failed save, or half as much on a success.
  
  ***At Higher Levels.*** When you cast this spell using a spell slot of 2nd level or higher, the damage increases by 1d8 for each slot level above 1st.
  
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
  
  <div class='footnote'>PART 2 | SPELLS </div>
  
  \pagebreakNum
  
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
  - **Components:** V, S, M (a humanoid skull blackened by fire)
  - **Duration:** Instantaneous
  ___
  An eruption of fiery doom blasts out from a point you choose within range, sending six streaks of flames slithering towards targets within 30 feet of it. You can direct the snaking fires to hit one target or several. A target takes 1d10 fire damage for each flame that strikes it, and can attempt a Dexterity saving throw to take half as much damage. Each target only makes one saving throw, regardless of how many flames it is struck by.
  
  ***At Higher Levels.*** When you cast this spell using a spell slot of 5th level or higher, the spell creates one more streak of flame for each spell level above 4th.
  
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
  
  #### Freezing Touch
  *2nd-level evocation*
  ___
  - **Casting Time:** 1 action
  - **Range:** Touch
  - **Components:** V, S, M (a shard of glass or ice)
  - **Duration:** 1 minute
  ___
  Your fingers become cold to the touch as frost manifests on their surface. Make a melee spell attack against a creature within range. On a hit, the creature is incapacitated and restrained until the spell ends as ice encap&shy;sulates their body. The spell ends for an affected creature if it takes any damage or if someone else uses an action to break the creature out of the ice.
  
  \columnbreak
  
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
  
  #### Guardian of the King
  *2nd-level abjuration*
  ___
  - **Casting Time:** 1 reaction, which you take when a creature is hit by an attack or spell
  - **Range:** 30 feet
  - **Components:** V, S
  - **Duration:** 1 round
  ___
  A barrier of holy light shields the triggering creature. Until the start of your next turn, the creature gains resistance to all damage dealt by weapon attacks, spells, and spell-like effects, including against the triggering attack. The spell does not protect you against natural sources of damage, such as molten lava or falling.
  
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
  
  <div class='footnote'>PART 2 | SPELLS </div>
  
  \pagebreakNum
  
  #### Healing Rain
  *5th-level transmutation*
  ___
  - **Casting Time:** 1 action
  - **Range:** 120 feet
  - **Components:** V, S, M (a vial of rain water)
  - **Duration:** Concentration, up to 1 minute
  ___
  You summon a cloud at a point within range, blanketing a 15-foot radius area around it in rain. Each friendly creature enters the rain for the first time on their turn, or starts their turn within the rain regains 2d6 hit points. The healing rain extinguishes nonmagical fires within its area of effect.
  
  ***At Higher Levels.*** When you cast this spell using a spell slot of 7th level or higher, the healing increases by 1d6 for every two slot levels above 5th.
  
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
  
  #### Holy Prism
  *2nd-level evocation*
  ___
  - **Casting Time:** 1 action
  - **Range:** 60 feet
  - **Components:** S
  - **Duration:** Instantaneous
  ___
  A streak of light surges from you to one creature within range and scatters on impact, touching three additional creatures of your choice within 5 feet of the target. Each creature gains one of the following effects of your choice.
  
  **Harm.** The creature must succeed on a Dexterity saving throw, taking 2d4 radiant damage on a failed save, or half as much damage on a successful one.
  
  **Heal.** The creature regains a number of hit points equal to 1d4 + your spellcasting ability.
  
  ***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, you may increase the damage and healing by 1d4 for each slot level above 2nd, or choose one additional creature within 5 feet of the target for each slot level above 2nd.
  
  \columnbreak
  
  #### Holy Wrath
  *3rd-level evocation*
  ___
  - **Casting Time:** 1 action
  - **Range:** Self (15-foot-radius)
  - **Components:** V, S
  - **Duration:** Instantaneous
  ___
  You release a burst of radiant energy in a blast. Each creature of your choice within a 20-foot-radius of you must make a Wisdom saving throw. A target takes 6d6 radiant damage on a failed save, or half as much damage on a successful one. The blast spreads around corners.
  
  ***At Higher Levels.*** When you cast this spell using a spell slot of 4th level or higher, the damage increases by 1d6 for each slot level above 3rd.
  
  #### Howling Blast
  *2nd-level evocation*
  ___
  - **Casting Time:** 1 action
  - **Range:** 60 feet
  - **Components:** V, S
  - **Duration:** 1 round
  ___
  An icy gale suddenly erupts around a point of your choice within range. Each creature in a 15-foot-radius sphere centered on that point must make a Constitution saving throw. A creature takes 3d8 cold damage on a failed save, or half as much damage on a successful one. A cold fog hangs in the air afterwards, making the area heavily obscured. It lasts for the duration or until a wind of moderate or greater speed (at least 10 miles per hour) disperses it.
  
  ***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, the damage increases by 1d8 for each slot level above 2nd.
  
  #### Ice Block
  *4th-level abjuration*
  ___
  - **Casting Time:** 1 reaction, when you take damage
  - **Range:** Self
  - **Components:** V, S
  - **Duration:**  Concentration, up to 1 minute
  ___
  Ice rapidly materializes around you, protecting you from harm. You gain 40 temporary hit points and immunity to cold damage for the spells duration. While the spell is active you can't move and take any actions or reactions. The spell remains until the temporary hit points have been expended or for the spell's duration.
  
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
  
  <div class='footnote'>PART 2 | SPELLS </div>
  
  \pagebreakNum
  
  #### Icebound Fortitude
  *2nd-level transmutation*
  ___
  - **Casting Time:** 1 reaction, which you take when you are dealt bludgeoning, piercing, or slashing damage
  - **Range:** Self
  - **Components:** V, S
  - **Duration:** 1 round
  ___
  You temporarily freeze your own blood and make your skin as hard as ice. Until the start of your next turn, you have resistance to bludgeoning, piercing, and slashing damage, including against the triggering damage.
  
  #### Icy Touch
  *1st-level necromancy*
  ___
  - **Casting Time:** 1 action
  - **Range:** 60 feet
  - **Components:** V, S
  - **Duration:** 1 round
  ___
  You summon icy energy to strike against a creature you can see within range, freezing them with the chill of the grave. Make a ranged spell attack against the creature to assail it with the chill of the grave. On a hit, the target takes 3d8 cold damage, and it can't regain hit points until the start of your next turn. Until then, the target’s skin grows as pale as ice. If you hit a celestial target, it also has disadvantage on attack rolls against you until the end of your next turn. 
  
  ***At Higher Levels.*** When you cast this spell using a spell slot of 2nd level or higher, the damage increases by 1d8 for each slot level above 1st. 
  
  #### Inner Fire
  *1st-level abjuration*
  ___
  - **Casting Time:** 1 action
  - **Range:** Self
  - **Components:** V,S
  - **Duration:** 8 hour
  ___ 
  You are protected by your faith and convictions. While unarmored, your base AC becomes 11 + your spellcasting modifier, and you gain advantage on saving throws you make to avoid or end the frightened condition on yourself. The spell ends early if you don armor.
  
  #### Inner Focus 
  *2nd-level abjuration*
  ___
  - **Casting Time:** 1 action
  - **Range:** Touch
  - **Components:** V,S
  - **Duration:** 1 hour
  ___
  You touch a willing creature and amplify their focus through their convictions. The next ability check the creature makes while affected by this spell is empowered, adding your spellcasting modifier to it, upon which this spell ends. 
  
  \columnbreak
  
  #### Inner Will
  *2nd-level abjuration*
  ___
  - **Casting Time:** 1 action
  - **Range:** Touch
  - **Components:** V,S
  - **Duration:** 1 hour
  ___ 
  You touch a willing creature and bolster their will through their convictions. The target adds your spellcasting modifier to its own while making Wisdom saving throws. This effect lasts for duration or until the target passes a Wisdom saving throw it would have otherwise failed.
  
  #### Invoke Elements
  *Transmutation cantrip*
  ___
  - **Casting Time:** 1 action
  - **Range:** 30 feet
  - **Components:** V, S
  - **Duration:** Up to 1 minute
  ___
  You invoke a minor portion of the elements. You create one of the following magical effects within range:
  
   - You create a harmless sensory effect that predicts what the weather will be for the next 24 hours. This effect persists for 1 round.
   - You light or put out a small flame.
   - You cause flames to flicker, brighten, drim, or change color for 1 minute.
   - You cause harmless tremors in the ground for 1 minute.
   - You cool or heat up a small amount of liquid.
  
  If you cast this spell multiple times, you can have up to three of its 1-minute effects active at a time, and you can dismiss such an effect as an action.
  
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
  
  <div class='footnote'>PART 2 | SPELLS </div>
  
  \pagebreakNum
  
  #### Lava Burst
  *2nd-level evocation*
  ___
  - **Casting Time:** 1 action
  - **Range:** 60 feet
  - **Components:** V, S
  - **Duration:** Instantaneous
  ___
  You manifest molten stone and magma into a ferocious ball, and hurl it at a target within range. The target must make a Dexterity saving throw. On a failed save, it takes 3d6 fire damage and 3d6 bludgeoning damage, or half as much on a successful one.
  
  ***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, the damage increases by 1d6 fire and bludgeoning damage for each slot above 2nd.
  
  #### Light of the Protector
  *5th-level evocation*
  ___
  - **Casting Time:** 1 action
  - **Range:** Self
  - **Components:** V, S
  - **Duration:** Instantaneous
  ___
  You feel the warmth of the light within you as a surge of positive energy washes through you, restoring a number of hit points equal to 5d12 + 30. This spell also ends blindness, deafness, and any diseases affecting you.
  
  #### Lightning Blast
  *Evocation cantrip*
  ___
  - **Casting Time:** 1 action
  - **Range:** 60 feet
  - **Components:** S
  - **Duration:** Instantaneous
  ___
  An arc of lightning streaks from your palms towards a creature within range. Make a ranged spell attack. On a hit, the target takes 1d8 lightning damage. If the target is wearing armor made of metal, it instead takes 1d12 lightning damage.
  
  This spell's damage increases by 1d8 when you reach 5th level (2d8 or 2d12), 11th level (3d8 or 3d12), and 17th level (4d8 or 4d12).
  
  #### Lightning Shield
  *1st-level abjuration*
  ___
  - **Casting Time:** 1 bonus action
  - **Range:** 60 feet
  - **Components:** S
  - **Duration:** Concentration, up to 10 minutes
  ___
  You call upon the element of air and surround a friendly target within range with a field of crackling electricity. Until the spell ends, the target gains a +1 bonus to AC and when a creature hits it with a melee attack, that creature takes 1d4 lightning damage.
  
  ***At Higher Levels.*** When you cast this spell using a spell slot of 2nd level or higher, the damage increases by 1d4 for each slot level above 1st.
  
  \columnbreak
  
  #### Living Bomb
  *2nd-level evocation*
  ___
  - **Casting Time:** 1 action
  - **Range:** 60 feet
  - **Components:** V, S, M (a flammable liquid)
  - **Duration:**  Concentration, up to 1 minute
  ___
  You manipulate the mana flowing through a creature within range, making it burn from the inside with a roaring fire. The target must make a Constitution saving throw, taking 1d10 fire damage on a failed save. On a successful saving throw, the target takes half as much damage and the spell ends. At the start of each of your turns for as long as the the spell persists, the target must repeat the saving throw, with the same effects for success or failure.
  
  When the spell ends the target and each creature within 10 feet of it must succeed on a Dexterity saving throw, taking 2d6 fire damage on a failed save or half as much on a successful one.
  
  ***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, the damage of the explosion increases by 1d6 for each slot level above 2nd.
  
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
  
  #### Lunar Strike
  *Evocation cantrip*
  ___
  - **Casting Time:** 1 action
  - **Range:** 60 feet
  - **Components:** V, S
  - **Duration:** Instantaneous
  ___
  A streak of lunar energy flares through the air. Choose <br> one creature within range, or choose two creatures within range that are within 5 feet of each other. A target must succeed on a Dexterity save or take 1d6 force damage. 
  
  If cast while outdoors with a clear view of the moon, the spell instead deals 1d8 force damage.
  
  ***At Higher Levels.*** The spell's damage increases by one die when you reach 5th level (2d6 or 2d8), 11th level (3d6 or 3d8), and 17th level (4d6 or 4d8).
  
  <div class='footnote'>PART 2 | SPELLS </div>
  
  \pagebreakNum
  
  #### Mantle of the Fallen Crusader
  *3rd-level evocation*
  ___
  - **Casting Time:** 1 action
  - **Range:** Self (30-foot radius)
  - **Components:** V
  - **Duration:** Concentration, up to 1 minute
  ___
  Unholy power radiates from you in an aura with a 30-foot radius, awakening bloodlust in friendly creatures. Until the spell ends, the aura moves with you, centered on you. While in the aura, each nonhostile creature in the aura (including you) deals an extra 1d4 necrotic damage when it hits with a weapon attack.
  
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
  
  \columnbreak
  
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
  
  <div class='footnote'>PART 2 | SPELLS </div>
  
  \pagebreakNum
  
  #### Rain of Fire
  *5th-level evocation*
  ___
  - **Casting Time:** 1 action
  - **Range:** 120 feet
  - **Components:** V, S. M (a chunk of sulfur and a chunk of iron)
  - **Duration:** Concentration, up to 1 minute
  ___
  A rain of small meteorites fall from the sky, exploding on impact. You cause them to fall in a cylinder 30-foot-tall cylinder with a 15-foot radius centered on a point within range. Each creature entering the area for the first time on their turn, or who starts their turn there, must make a Dexterity saving throw, taking 3d6 bludgeoning damage and 3d6 fire damage on a failed save, or half as much on a success.
  
  As a bonus action you can move the cylinder up to 15 feet to a point you can see. Unattended flammable objects in the area are ignited, and metals begin to melt.
  
  ***At Higher Levels.*** When you cast this spell using a spell slot of 6th level or higher, the damage increases by 2d6 fire damage per spell level above 5th.
  
  #### Reincarnation
  *5th-level necromancy*
  ___
  - **Casting Time:** 10 minutes
  - **Range:** Self
  - **Components:** V, S, M (a bejeweled ankh worth 500 gp)
  - **Duration:** 10 days
  ___
  You protect your soul with the power of the elements. If you die during the spell's duration, you are instantly returned to life with half your hit points and the material component is consumed. 
  
  This spell neutralizes any poisons and cures normal diseases afflicting you when you died. It doesn't, however, remove magical diseases, curses, and the like; if such effects aren't removed prior to dying, they still afflict you. 
  
  This spell closes all mortal wounds and restores any missing body parts.
  
  Coming back from the dead is an ordeal. You take a −4 penalty to all attack rolls, saving throws, and ability checks. Every time you finish a long rest, the penalty is reduced by 1 until it disappears.
  
  If you cast this spell again, the effect of any previously cast reincarnation spell ends. The spell ends prematurely <br> if its material component is ever not on your person.
  
  #### Repentance
  *1st-level enchantment*
  ___
  - **Casting Time:** 1 reaction, which you take when you are targeted by a weapon or spell attack
  - **Range:** 30 feet
  - **Components:** V
  - **Duration:** 1 round
  ___
  A sense of remorse rushes over the triggering creature. The creature must first make a Wisdom saving throw. On a failed save, the creature must choose a new target or lose the attack or spell. 
  
  
  
  #### Righteous Smite
  *2nd-level evocation*
  ___
  - **Casting Time:** 1 bonus action
  - **Range:** Self
  - **Components:** V
  - **Duration:** Concentration, up to 1 minute
  ___
  The next time you hit with a melee weapon attack during this spell's duration, your attack deals an extra 2d6 radiant damage, and the next attack roll mde against this target before the end of your next turn has advantage.
  
  ***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, the extra damage increases by 1d6 for each slot level above 2nd.
  
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
  
  <div class='footnote'>PART 2 | SPELLS </div>
  
  \pagebreakNum
  
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
  
  #### Shadow Glide
  *Conjuration cantrip*
  ___
  - **Casting Time:** 1 bonus action
  - **Range:** Self (5 feet)
  - **Components:** V
  - **Duration:** Instantaneous
  ___
  Obscured by shadows, you teleport to an unoccupied space within 5 feet.
  
  \columnbreak
  
  #### Shadow fury
  *6th-level enchantment*
  ___
  - **Casting Time:** 1 action
  - **Range:** 60 feet
  - **Components:** V, S
  - **Duration:** Concentration, up to 1 minute
  ___
  You extend your arm and draw shadow energy down upon creatures within a 10-foot radius of a point within range. Each creature takes 5d8 psychic damage and must succeed on a Wisdom saving throw or be stunned for the duration of the spell. 
  
  A stunned creature must make a Constitution saving throw at the end of each of its turns. On a successful save, this stunning effect ends.
  
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
  
  <div class='footnote'>PART 2 | SPELLS </div>
  
  \pagebreakNum
  
  #### Solar Wrath
  *Evocation cantrip*
  ___
  - **Casting Time:** 1 action
  - **Range:** 60 feet
  - **Components:** V, S
  - **Duration:** Instantaneous
  ___
  You release a blast of the sun's wrath against a creature within range. Make a ranged spell attack against the creature. On a hit, the target takes 1d8 radiant damage and, until the end of your next turn, they radiate bright light in a 10 foot radius and dim light for an additional 10 feet.
  
  This spell's damage increases by 1d8 when you reach 5th level (2d8), 11th level (3d8), and 17th level (4d8).
  
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
  
  #### Starfall
  *6th-level evocation*
  ___
  - **Casting Time:** 1 action
  - **Range:** 300 feet
  - **Components:** V, S, M (a pinch of powdered glass)
  - **Duration:** 1 round
  ___
  Countless flashes of pure moonlight fall to the ground in a 20-foot-radius, 40-foot-high cylinder centered on a point within range. Each creature in the cylinder must make a Dexterity saving throw. A creature takes 10d6 radiant damage on a failed save, or half as much damage on a successful one. A creature who failed the saving throw is also blinded until the end of your next turn. 
  
  If cast while outdoors with a clear view of the moon, the spell deals an additional 2d6 radiant damage.
  
  ***At Higher Levels.*** When you cast this spell using a spell slot of 7th level or higher, the damage increases by 1d6 for each slot level above 6th.
  
  \columnbreak
  
  #### Starfire
  *1st-level evocation*
  ___
  - **Casting Time:** 1 action
  - **Range:** 120 feet
  - **Components:** V, S
  - **Duration:** Instantaneous
  ___
  A flash of light streaks down upon a creature of your choice within range. Make a ranged spell attack against the target. On a hit, the target takes 3d6 radiant damage, and is blinded until the end of your next turn. The blindness ends early if the target takes damage from a weapon attack or spell, as the stardust blocking its eyes is swept away. 
  
  If cast while outdoors with a clear view of the moon, the spell deals an additional 1d6 radiant damage.
  
  ***At Higher Levels.*** When you cast this spell using a spell slot of 2nd level or higher, the damage increases by 1d6 for every spell level above 1st.
  
  #### Starsurge
  *3rd-level evocation*
  ___
  - **Casting Time:** 1 action
  - **Range:** Self (100-foot line)
  - **Components:** V, S, M (a rod of glass and a vial of water from a moonwell)
  - **Duration:** Instantaneous
  ___
  A blast of intense moonlight bursts forward in a line 100 feet long and 5 feet wide out from you in a direction you choose. Each creature in the burst's path must make a Dexterity saving throw; creatures sensitive to sunlight have disadvantage on their save. A creature takes 6d6 radiant damage on a failed save, or half as much damage on a successful one. 
  
  If cast while outdoors with a clear view of the moon, the spell deals an additional 2d6 radiant damage.
  
  ***At Higher Levels.*** When you cast this spell using a spell slot of 4th level or higher, the damage increases by 1d6 for each slot level above 3rd.
  
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
  
  <div class='footnote'>PART 2 | SPELLS </div>
  
  \pagebreakNum
  
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
  
  #### Unholy Weapon
  *5th-level evocation*
  ___
  - **Casting Time:** 1 bonus action
  - **Range:** Touch
  - **Components:** V, S
  - **Duration:** Concentration, up to 1 hour
  ___
  You imbue a weapon you touch with unholy power. Until the spell ends, the weapon creates an area of darkness <br> in a 30-foot radius and dim light for an additional 30 feet. The bearer of the unholy weapon is immune to this effect. In addition, weapon attacks made with it deal an extra 2d8 necrotic damage on a hit. If the weapon isn’t already a magic weapon, it becomes one for the duration.
  
  As a bonus action on your turn, you can dismiss this <br> spell and cause the weapon to emit a torrent of corrupting shadows. Each creature of your choice that you can see within 30 feet of the weapon must make a Constitution saving throw. On a failed save, a creature takes 4d8 necro&shy;tic damage, and it is blinded for 1 minute. On a successful save, a creature takes half as much damage and isn’t blinded. At the end of each Of its turns, a blinded creature can make a Constitution saving throw, ending the effect on itself on a success.
  
  #### Ursol's Vortex
  *4th-level conjuration*
  ___
  - **Casting Time:** 1 action
  - **Range:** 60 feet
  - **Components:** V, S
  - **Duration:** Concentration, up to 1 minute
  ___
  Choose a point that you can see within range. An elemental force that resembles a swirling vortex extends in a 10-foot radius from the point and lasts for the spell's duration.
  
  The area is considered to be difficult terrain and any creature who enters or starts their turn in the vortex must make a Strength saving throw. On failed save, the creature takes 2d6 bludgeoning damage and is pulled to an empty space nearest the vortex's center. On a successful save, the creature takes half as much damage and isn't pulled towards the center of the vortex.
  
  As a bonus action, you can move the vortex up to 30 feet in any direction.
  
  ***At Higher Levels.*** When you cast this spell using a spell slot of 5th level or higher, the damage increases by 1d6 for each slot level above 4th.
  
  <div class='footnote'>PART 2 | SPELLS </div>
  
  \pagebreakNum
  
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
  
  \pagebreakNum
  
  ## Changelog 3.1
  - Asphyxiate and Freezing Touch no longer suffocate targets.
  - Changed/Rebalanced: Cataclysm, Drain Life, Lunar Strike, Rain of Fire, Starfall, Starfire, Starsurge
  - Summon Undead renamed to Conjure Undead, to avoid confusion with the version from TCE
  - Added: Create Healthstone, Create Soulstone, Create Soulwell, Decompose (Credit Matt Mercer's Critical Role), Diabolism [(Original Idea Credit)](https://www.dndbeyond.com/spells/141243-diabolism), Fire and Brimstone, Shadow Glide, Touch of Chaos
  
  ## Changelog 3.1.1
  - Changed/Rebalanced: Rain of Fire, Fire and Brimstone, Starfire, Dark Void, Living Bomb, Cataclysm
  
  ## Changelog 3.1.2
  - Added/Updated priest spells