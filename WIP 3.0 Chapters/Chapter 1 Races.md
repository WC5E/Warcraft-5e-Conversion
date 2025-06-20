<style>
/* GLOBAL FORMATTING  */

  /* Resize page to international A4 */
  .phb {
    width: 210mm;
    height: 297mm;
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
  .phb:nth-child(odd):not(:last-child):after { 
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
  .phb:nth-child(even):not(:last-child):after { 
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
  .phb:first-child:after {
    display: none;
  }
  .phb:last-child:after {
    display: none;
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

<div class='partpage'>

# Part I 
##### Creating a Hero
</div>

<style> .phb#p4:after { display:none; } </style>
<img src='https://www.gmbinder.com/images/174aZQG.jpg' style='position:absolute; top:0px; right:-980px; width:2800px' />

\pagebreak

# Chapter 1: Races
Armies and factions have always defined the Warcraft world, and two of the most powerful factions on Azeroth today are the Alliance and Horde. Most players belong to one faction or the other, although anomalies do exist.

## Choosing a Side
At character creation, every player must choose their character’s faction. It is as much a part of the hero as their class or background. All characters in a party are usually of the same faction.

Although every race has an affiliation, there are excep&shy;tions. Creating a character outside their normal affiliation is challenging, but offers a great roleplay opportunities for the player. Some suggestions are listed below.

 - The character was born into the faction.
 - The character was saved or befriended by <br> members of the faction.
 - The character fled from their faction.
 - The character witnessed members of their faction <br> doing something they found reprehensible.

### The Alliance
The Alliance have proven themselves to be fierce comba&shy;tants, often giving their lives when called for. The faction is not a uniform governmental body, but is a coalition of mutual military and economic aid. Diplomacy is key within the Alliance and decisions are traditionally made by being voted on by the Alliance's most influential members. Storm&shy;wind is described as the most powerful force in the now multiracial Alliance. With it becoming the de facto leader of the remaining human kingdoms and entering a powerful alliance with the strongest dwarven kingdom, Ironforge, Stormwind has thus been shown to be the most influential kingdom and therefore the de facto driving force of Alliance politics. Therefore, Stormwind is undisputedly looked to for maintaining the Alliance and its policies. Stormwind is where the main superpowers of the Alliance conference to discuss world issues and mutual defense. The majority of Alliance citizens also recognize Stormwind City as the heart of the Alliance. The High King coordinates the workings of the Alliance's armies in order to safeguard the Alliance's interests and defense. 

Even now, as always, humans are the glue that hold the Alliance together, being the most numerous and diplomatic of the member races. The armies of Stormwind are primarily stationed in the southern Eastern Kingdoms, securing regions such as Elwynn Forest, Duskwood, Westfall, and the Redridge Mountains, as well as having outposts and bases stationed at key points in Lordaeron, Northrend, and Kalimdor. The armies of Ironforge are mainly stationed in Khaz Modan along with their gnome allies, and the night elven armies are mainly defending 
<br> <span style="margin-left:30px"></span> northern Kalimdor from the Horde's deforestation 
<br> <span style="margin-left:75px"></span> of Ashenvale. The remaining draenei forces 
<br> <span style="margin-left:85px"></span> are still trying to secure their new home on
<br> <span style="margin-left:90px"></span> Azuremyst Isle, and are also stationed in
<br> <span style="margin-left:105px"></span> Outland. The recently brought in
<br> <span style="margin-left:110px"></span> Gilnean armies are defending them-
<br> <span style="margin-left:120px"></span> selves from the endless Forsaken.

\columnbreak

<div style='margin-top:233px;'></div>

### The Horde 
The Horde makes no compromises when it comes to excellence, and the power and ferocity of their warriors is legendary. Misunderstood by many as evil, the Horde possesses a strong code of honor and strict laws for disobedience. All members of the Horde have to swear a blood oath to join  the faction and are thus obligated to follow the warchief's commands and support the warchief in war if the warchief calls upon them for aid. The position of warchief can be attained by having the previous warchief choose a succes&shy;sor or challenging the current warchief to a Mak'gora: a prearranged duel with deadly weapons between two people following a formal procedure in the presence of witnesses and traditionally fought until one party yields or is killed, usually to settle a quarrel involving a point of honor. Above all else, the title warchief is granted to those who display strength and decisive action.

The warchief may accept ambassadors and advisors from all the different tribes and members of the Horde to makes sure their voice is heard in the running of the fledg&shy;ling hegemony but ultimately, only the warchief may have the final say in matters concerning the entire Horde. Each race within the Horde choose a single leader to govern their people and their people's kingdoms and also to repre&shy;sent their people in the high Horde echelon.

Despite their somewhat monstrous appearance, the majority of the Horde is not evil, much like the Alliance, it is comprised of diverse factions and individuals who possess a wide range of values and virtues. Even so, there is one expectation that must be met when joining the Horde: regardless of gender or station, all are expected to pull their own weight and give their talents for the betterment of the Horde. When weakness is a liability to the of the Horde, it is the duty of the strong to usurp control from the incom&shy;petent and redeem the Horde. 

*Lok'tar ogar! Victory or death*—These words bind one to the Horde. For they are the most sacred and fundamental of truths to any warrior of the Horde, for the Horde, failure is not an option.

Culturally, orcs and tauren believe in redemption more than most other races on Azeroth and are willing to give almost anyone a chance, regardless of reputation. The trolls seem to have even accepted, (if not at least 
<br>olerate) their ancient enemy the blood elves.
<br>Largely because of these beliefs, a number 
<br>of mortal races and many diverse factions 
<br>can be found in service to the Horde.

<img src='https://www.gmbinder.com/images/wl1T3Aj.jpg' style='position:absolute; top:0px; right:-50px; width:600px' />
<img src='https://www.gmbinder.com/images/huxbNse.png' style='position:absolute; top:-240px; right:0px; width:900px' />
<img src='https://www.gmbinder.com/images/huxbNse.png' style='position:absolute; top:0px; right:-30px; width:900px' />
<img src='https://www.gmbinder.com/images/5ItC6WX.png' style='position:absolute; top:955px; right:620px; width:230px; z-index:20' />
<img src='https://www.gmbinder.com/images/EK9lCTV.png' style='position:absolute; top:930px; right:-80px; width:240px; z-index:20' />

\pagebreak

## Choosing a Race
Not every intelligent race of the multiverse is appropriate for a player-controlled adventurer. The ones presented in this book are the races most well known to become adven&shy;turers and heroes, spread throughout every corner of Azeroth's continents.

Your choice of race affects many different aspects of your character. It establishes fundamental qualities that exist throughout your character's adventuring career. When making this decision, keep in mind the kind of character you want to play. For example, a gnome could be a good choice for a sneaky rogue, a dwarf makes a tough warrior, and an elf can be a master of arcane magic.

Your character race not only affects your ability scores and traits but also provides the cues for building your character's story. Each race's description in this chapter includes information to help you roleplay a character of that race, including personality, physical appearance, features of society, and racial alignment tendencies.

These details are suggestions to help you think about your character; adventurers can deviate widely from the norm for their race. It's worthwhile to consider why your character is different, as a helpful way to think about your character's background and personality.

### Racial Traits
The description of each race includes racial traits that are common to members of that race. The following entries appear among the traits of most races.

#### Ability Score Increase
Every race increases one or more of a character's
ability scores.

#### Age
The age entry notes the age when a member of the race is considered an adult, as well as the race's expected lifespan. This information can help you decide how old your character is at the start of the game.

#### Alignment
Most races have tendencies toward certain alignments, described in this entry. These are not binding for player characters, but considering why your dwarf is chaotic, for example, in defiance of lawful dwarf society can help you better define your character.

#### Size
Characters of most races are Medium, a size category including creatures that are roughly 4 to 8 feet tall. Members of a few races are Small (between 2 and 4 feet tall), which means that certain rules of the game affect them differently. The most important of these rules is that Small characters have trouble wielding heavy weapons.

#### Speed
Your speed determines how far you can move when traveling and fighting.

#### Languages
By virtue of your race, your character can speak, read, and write certain languages. Each race has their own language, with multiple dialects. as well as a 'common' language, that the majority of their faction speaks and understands. Chapter 4 lists languages commonly spoken on Azeroth.

\columnbreak

#### Subraces
Many races have subraces. Members of a subrace have the traits of the parent race in addition to the traits specified for their subrace. Relationships among the subraces vary significantly from race to race.

### Languages
Dozens of languages can be heard across Azeroth, and every tongue has dialects and regional variants. In order for its races to communicate intelligibly, the Common tongue is essential. But other languages remain widely used in homes and within the borders of certain regions.

##### Standard Languages
|&nbsp; Language   | Typical Speakers | Script |
|:------------------|:------------|:-----------|
|&nbsp; Common      | Humans      | Common     |
|&nbsp; Darnassian  | Night Elves | Darnassian |
|&nbsp; Draenei     | Draenei     | Eredun     |
|&nbsp; Dwarven     | Dwarves     | Dwarvish   |
|&nbsp; Goblin      | Goblins     | Common     |
|&nbsp; Gnomish     | Gnomes      | Common     |
|&nbsp; Gutterspeak | Forsaken    | —          |
|&nbsp; Orcish      | Orcs        | Orcish     |
|&nbsp; Pandaren    | Pandaren    | Mogu       |
|&nbsp; Shalassian  | Nightborne  | Darnassian |
|&nbsp; Taur-ahe    | Tauren      | Taur-ahe   |
|&nbsp; Thalassian  | High Elves  | Darnassian |
|&nbsp; Zandali     | Trolls      | Zandali    |

##### Exotic Languages
|&nbsp; Language    | Typical Speakers | Script        |
|:------------------|:-----------------|:--------------|
|&nbsp; Draconic    | Dragons          | Draconic      |
|&nbsp; Eredun      | Demons           | Eredun        |
|&nbsp; Kalimag     | Elementals       | Kalimag       |
|&nbsp; Low Common  | Monstrous Races  | Common        |
|&nbsp; Ogre        | Ogres            | Ogre          |
|&nbsp; Shath'Yar   | Old Gods         | Shath'Yar     |
|&nbsp; Titan       | Titan-forged     | Titan         |

<img src='https://www.gmbinder.com/images/1Hhc7zP.jpg' style='position:absolute; top:700px; right:-80px; width:500px' />
<img src='https://www.gmbinder.com/images/huxbNse.png' style='position:absolute; top:200px; right:0px; width:900px; transform:scaley(-1)' />
<img src='https://www.gmbinder.com/images/huxbNse.png' style='position:absolute; top:0px; right:-30px; width:900px; transform:scaley(-1)' />

\pagebreak

<div class='cover-header'> <div style='margin-top:50px;'></div> Races of the Alliance </div>
<style> .phb#p7:after { display:none; } </style>
<img src='https://www.gmbinder.com/images/c1ja74s.jpg' style='position:absolute; top:0px; right:0px; width:800px' />

\pagebreak

<div style='margin-top:546px'></div>

## Human
*No one feels he deserves it. Because no one does. It's grace, pure and simple, we are inherently unworthy, simply because we're human. Aye the elves, dwarves, and all the other races are flawed. But the Light loves us anyway. It loves us for what we sometimes can rise to in rare moments. It loves us for what we can do to help others.*
<div style="text-align:Right"> 

*— Uther the Lightbringer* &nbsp;</div>
<div style='margin-top:-5px'></div>

Human kingdoms have existed for thousand of years, and humans themselves for thousands more. Their short lives in comparison to dwarves and elves pushes them to achieve as much as they can in the years they are given. Their valor, optimism, and stubbornness have led them to build some of the greatest kingdoms on Azeroth, some of which still stand a millennium later. Whatever have pushed them down, it has only strengthened the bond between those that still stand.

### A Broad Spectrum
With their penchant for migration and conquest, humans are more physically diverse than any other race. There is no typical human. An individual can stand from 5 feet to a little over 6 feet tall and weigh from 125 to 250 pounds. Human skin shades range from nearly black to very pale, and hair colors from black to blond (curly, kinky, or straight); males might sport facial hair that is sparse or thick. Humans reach adulthood in their late teens and rarely live even a single century.

\columnbreak

<br>
<div style='margin-top:448px'></div>

### Variety in All Things
Humans are the most adaptable and ambitious people among Azeroth's races. They have widely varying tastes, morals, and customs in the many different kingdoms where they have settled. When they settle though, they stay: they build cities to last for the ages, and great kingdoms that can persist for long centuries. They live fully in the present but also plan for the future, striving to leave a lasting legacy.

### Proudly Standing
Despite what atrocities have happened to them, humans remain hardy and brave, thoroughly committed to building strong societies, reinforcing their kingdoms, and reclaiming lost nations. Years of war have tempered their resolve, and they are more determined than ever before. Their value of virtue, honor and courage shine their ranks.

### Faithful
Among all human nations, the holy light is a central part of civilized society. By most it is considered the only religion and a staple of worship, respect, and honor. The religion is widely worshiped throughout Azeroth, yet humans were the first to utilize its powers in an offensive manner with the creation of paladins. Throughout their kingdoms, churches of the holy light can be found, an organization dedicated to creating a world of honor, and justice.

### Affiliation
Humans began the Alliance and it could not exist without them. Humans and orcs joined forces to face the Burning Legion years ago, but old habits returned once they dispatched the demon threat. Although the Alliance and Horde leaders bear a healthy respect for each another, old racial hatreds still stir within the hearts of their troops. 

They respect the races of their alliance, and carries no ill wish against any of them. They know they are the center stone of the alliance, and that a good relationship is key.

<div class='footnote'>PART 1 | RACES</div>
<img src='https://www.gmbinder.com/images/Ke9OOwE.png' style='position:absolute; top:0px; right:-30px; width:1000px' />
<img src='https://www.gmbinder.com/images/pbSeYXZ.png' style='position:absolute; top:50px; right:0px; width:800px; transform:scalex(-1)' />
<img src='https://www.gmbinder.com/images/x6YvTEU.png' style='position:absolute; top:20px; right:240px; width:650px;transform:scalex(-1)' />

\pagebreakNum

### Human Names and Ethnicities
Having so much more variety than other cultures, humans as a whole have no typical names. Some human parents give their children names from other languages, such as Dwarven or Darnassian, but most parents give names that are linked to their region's culture or to the naming traditions of their ancestors.

The material culture and physical characteristics of humans can change wildly from region to region. For example, the clothing, architecture, cuisine, music, and literature are different in the peninsula of Gilneas than in the southern kingdom of Stormwind. Human physical characteristics, though, vary according to the ancient migrations of the earliest humans, so that the humans of the Eastern Kingdoms have every possible variation of coloration and features.

Seven human kingdoms and ethnic groups are widely recognized. These groups, and the typical names of their members, can be used as inspiration no matter which kingdom your human is in.

#### Alterac
Found in the Alterac mountains, Alteracis are of moderate height and muscular built, with skin hues of pale and fair skin. Their hair is usually silver or blonde, and their eye color varies widely, though light colorations are common.
<div style='margin-top:-18px;'></div>

<br>**Alteraci Names:** Alteracis generally use names taken from <br>&nbsp;&nbsp;&nbsp; the humans of Stromgarde or Lordaeron, and have no <br>&nbsp;&nbsp;&nbsp; names specific to them.

#### Dalaran
Dalaranians are slender, fair-skinned folk with brown hair that ranges from blond to almost black. Most are of moderate height and have blue or green eyes. But these traits are hardly universal. Humans of Dalaran come from far and wide across the Eastern Kingdoms to study or seek refuge within the floating city.
<div style='margin-top:-18px;'></div>

<br>**Dalaranian Names:** Dalaranians have no names specific <br>&nbsp;&nbsp;&nbsp; to them, the ethnicity of their people vary beyond mere <br>&nbsp;&nbsp;&nbsp; humans and names are used from a variety of races.

#### Gilneas
Gilneans are tall, fair to amber-skinned folk with blue or steely gray eyes. Most have hair ranging from wine-red or light brown to raven-black.
<div style='margin-top:-18px;'></div>

<br>**Gilnean Names:** (Male) Blake, Chris, Fenegan, Gerard, <br>&nbsp;&nbsp;&nbsp; James, Sean, Sebastian, Vincent; (female) Amelia, <br>&nbsp;&nbsp;&nbsp; Ashley, Celestine, Loren, Mary, Melinda, Mia, Tess; <br>&nbsp;&nbsp;&nbsp; (surnames) Broderick, Cleese, Crowly, Godfrey, Walden

#### Kul Tiras
Native to the Kul Tiran isles, Kul Tirans are generally tall and muscular, with fair to amber skin similar to that of gilneans, brown to black hair, and light colored eyes.<div style='margin-top:-18px;'></div>

<br>**Kul Tiran Names:** (Male) Cyrus, Denzel, Elijah, Herold, <br>&nbsp;&nbsp;&nbsp; Patrick, Ron, Wesley, Will; (female) Fray, Helena, Jess, <br>&nbsp;&nbsp;&nbsp; Joan, Kate, Leila, Louisa, Taylor; (surnames) Clark, <br>&nbsp;&nbsp;&nbsp; Ledger, Mueller, Page, Wellard

#### Lordaeron
Widespread along the Eastern Kingdoms northern realm, Lordaeronians are of medium height and slender built, with pale skin. Their hair and eye color varies widely, but silver or light colored hair and blue eyes are common.

<div style='margin-top:-18px;'></div>

<br>**Lordaeronian Names:** (Male) Alexi, Aurius, Gannon, <br>&nbsp;&nbsp;&nbsp; Menard, Norwyn, Othmar, Urias, Wallace; (female) <br>&nbsp;&nbsp;&nbsp; Arenya, Diahann, Ellaine, Illucia, Jandice, Lydie, Malina, <br>&nbsp;&nbsp;&nbsp; Merla; (surnames) Barton, Camden, Godwin, Hayden

#### Stormwind
Found within the southern region of the Eastern King-doms, Stormwindians are of moderate height and build, with skin hues ranging from tawny to fair. Their hair varies widely from blonde to brown, as does their eyes, though brown is most common.
<div style='margin-top:-18px;'></div>

<br>**Stormwindian Names:** (Male) Ander, Dungar, Harlan, <br>&nbsp;&nbsp;&nbsp; Jesper, Jocryn, Maginor, Osric, Renato; (female) Dalga, <br>&nbsp;&nbsp;&nbsp; Einris, Ilsa, Jalane, Karrina, Laurena,  Maris, Sarisse; <br>&nbsp;&nbsp;&nbsp; (surnames) Ayrole, Bolero, Cordell, Leifeld, Stanford

#### Stromgarde
Shorter in build than most other humans, Stromics have generally pale skin contrasted by brown or black hair, and dark colored eyes.
<div style='margin-top:-18px;'></div>

<br>**Stromic Names:** (Male) Adrien, Emmir, Galen, Ganar, <br>&nbsp;&nbsp;&nbsp; Thoras, Tyrreth, Urnor, Wyenas; (female) Amina, Céline, <br>&nbsp;&nbsp;&nbsp; Clarisse, Ella, Emeline, Iris, Mara, Marine; (surnames) <br>&nbsp;&nbsp;&nbsp; Brewston, Farthing, Gilbreath, Swale, Tubal

### Human Traits
It's hard to make generalizations about humans, no matter where you were born your character has these traits.

***Ability Score Increase.*** One ability score of your choice increases by 2, and another ability score of your choice increases by 1.

***Age.*** Humans reach adulthood in their late teens and live less than a century.

***Alignment.*** Humans tend toward no particular alignment. The best and the worst are found among them.

***Size.*** Humans range from barely 5 to well over 6 feet tall and weigh an average of 175 pounds. Your size is Medium. To set your height and weight randomly, start with rolling the size modifier:
<div style="margin-top: -20px; font-family: ScalySans, sans-serif">

<br>&nbsp;&nbsp;&nbsp; ***Size Modifier:*** 2d10
<br>&nbsp;&nbsp;&nbsp; ***Height:*** 4 feet + 8 inches + your size modifier in inches
<br>&nbsp;&nbsp;&nbsp; ***Weight in Pounds:*** 110 + (2d4 x your size modifier)
</div>

<div style='margin-top:-3px;'></div>

&nbsp;&nbsp;&nbsp; ***Speed.*** Your base walking speed is 30 feet. 

***Determination.*** When you make an attack roll, an ability check, or a saving throw, you can do so with advantage. You can't do so again until you finish a short or long rest.

***Human Spirit.*** When you roll a 1 on an attack roll, ability check, or saving throw, you can reroll the die. You must use the new result, even if it is a 1.

***Skill Versatility.*** You gain proficiency in two skills or tools of your choice.

***Languages.*** You can speak, read, and write Common and one extra language of your choice. Humans typically learn the languages of other peoples they deal with, including obscure dialects. They are fond of sprinkling their speech with words borrowed from other languages: Dwarven curses, Darnassian musical expressions, Gnomish tongue twisters, and so on.

<div class='footnote'>PART 1 | RACES</div>

\pagebreakNum

<div style='margin-top:227px;'></div>

## Dwarf
*And here are the why and the how, to again become 
<br>one with the mountain. For behold, we are the earthen, 
<br>of the land, and its soul is ours, its pain is ours, its heartbeat is ours. We sing its song and weep for its 
<br>beauty. For who would not wish to return home? 
<br>That is the why, O children of the earth.*
<div style="text-align:Left"> 

*— Earthen tablet, as read by King Magni* &nbsp;</div>
<div style='margin-top:-5px'></div>

Their kingdom rich in ancient grandeur, halls carved into the roots of mountains, the echoing of picks and hammers in deep mines and roaring forges, a commitment to clan and tradition, these common threads unite all dwarves. Within the mountains of Khaz Modan, they continue their ancient ways, extending the depth of their halls, and con-structing marvels of architecture,

### A Reclaimed Legacy
The undiscovered fragments of their past 
<br>have led the dwarves on an unprecedented 
<br>exodus of exploration to seek out their 
<br>origins. Seeking out their origins, the 
<br>dwarves have dispatched prospectors 
<br>across all of Lordaeron in order to seek out 
<br>signs of the Titans, the supposed creators of the 
<br>dwarves. The dwarves have embraced the idea that it is their purpose to search the world for more signs of proof of their heritage. Dwarven outposts exist in the most desolate of places on Azeroth. 

Here, the dwarves spend their time seeking out the secrets of ancient times, or simply use their outposts as staging grounds for expeditions to clear out their enemies so that they may continue their quest.

### Short and Stout
Bold and hardy, dwarves are known as skilled warriors, miners, and workers of stone and metal. Though they stand well under 5 feet tall, dwarves are so broad and compact that they can weigh as much as a human standing nearly two feet taller. Their courage and endurance are also easily a match for any of the larger folk.

Dwarves skin ranges from deep brown to a paler hue tinged with red, but the most common shades are light brown or deep tan, like certain tones of earth. With their dark iron kin having notably darker skin of gray to coal-black. Their hair, worn long but in simple styles, is usually black, gray, or brown, though wildhammer dwarves often have red hair. Male dwarves value their beards highly and groom them carefully.

\columnbreak

<div style='margin-top:800px;'></div>

### Innovative
Dwarves are a proud, stern and determined people with streaks of kindness hidden under the gruff exteriors of their sturdy frames. Their love for battle, invention and exploration impels them ever forward to discover and unearth the mysteries of their heritage, educating them further about those who first created the dwarven race.

Still, they keep to the forges and workshops, ever inno-vating and creating new and more effective ways of warfare. Steam powered technology and firearms originate from dwarven inventiveness and creativity. The stout race is renowned for its skills at battle and also as cunning engineers and crafters. 

<div class='footnote'>PART 1 | RACES</div>
<img src='https://www.gmbinder.com/images/v7DFZZS.jpg' style='position:absolute; top:-40px; right:-350px; width:1150px' />
<img src='https://www.gmbinder.com/images/4eD5Yy6.png' style='position:absolute; top:0px; right:0px; width:900px; transform:scalex(-1)' />
<img src='https://www.gmbinder.com/images/l2uyR4M.png' style='position:absolute; top:335px; right:-55px; width:550px; transform:scalex(-1); z-index:20' />

\pagebreakNum

### Affiliation
Dwarves are members of the Alliance and staunch allies of its human founders, having fought side-by-side with their armies in more than one war. Although the night elves may share the same allegiances, most dwarves looks at "pointy eared humans" with suspicion and trepidation, preferring to keep them at an arm's distance.

***Ironforge Dwarves.*** These dwarves have been part of the Alliance since its founding in Lordaeron and continue to be a steadfast ally to its cause. 

***Wildhammer Dwarves.*** These dwarves never pledged their allegiance to the Alliance and have instead put their trust in their ironforge kin. They remain an isolated clan of dwarves that choose their own battles, but are often found among ironforge soldiers.

***Dark Iron Dwarves.*** These dwarves fought against the Alliance for many years as they served the deceased Fire&shy;lord Ragnaros. His death split the united clan and forced them to find new allies, many proclaimed Moira their new queen and have since joined the Alliance. However, there are still many who distrust the cunning dark iron dwarves and their pledged allegiance to the Alliance is newfound.

### Names
Every proper dwarven name has been used and reused down through the generations. A dwarf's name belongs to the clan, not the individual. A dwarf may earn a name and place it above that of its clan, although such occurrences are rare as many dwarves takes pride in their clan.
<div style='margin-top:-18px;'></div>

<br>**Male Names:** Barab, Aradun, Thorin, Magni, Garrim, <br>&nbsp;&nbsp;&nbsp; Wendel, Thurimar, Irmirn, Bhaduk, Gengur
<br>**Female Names:** Chise, Helge, Ferya, Furga, Krona, Imli, <br>&nbsp;&nbsp;&nbsp; Gwamde, Illia, Somdunn, Thanmu, Eniss, Nanla
<br>**Clan Names:** Thunderforge, Bronzebeard, Thornsteel, <br>&nbsp;&nbsp;&nbsp; Hammergrim, Chunderstout, Broadmail, Madpride

### Dwarf Traits
Your dwarf character has the following racial traits.

***Ability Score Increase.*** Your Constitution score <br> increases by 2.

***Age.*** Dwarves mature at the same rate as humans, but they're considered young until they reach the age of 40. On average, they live about 320 years.

***Alignment.*** Most dwarves are lawful, believing firmly in the benefits of a well-ordered society. They tend toward good as well, with a strong sense of fair play and a belief that all deserve to share in the benefits of a just order.

***Size.*** Dwarves stand between 4 and 5 feet tall and average about 150 pounds. Your size is Medium. To set your height and weight randomly, start with rolling the size modifier:
<div style="margin-top: -20px; font-family: ScalySans, sans-serif">

<br>&nbsp;&nbsp;&nbsp; ***Size Modifier:*** 2d4
<br>&nbsp;&nbsp;&nbsp; ***Height:*** 3 feet + 8 inches + your size modifier in inches
<br>&nbsp;&nbsp;&nbsp; ***Weight in Pounds:*** 120 + (2d6 x your size modifier)
</div>

<div style='margin-top:-3px;'></div>

&nbsp;&nbsp;&nbsp; ***Speed.*** Your base walking speed is 25 feet. Your speed is not reduced by wearing heavy armor.

***Darkvision.*** Accustomed to life underground, you have superior vision in dark and dim conditions. You can see in dim light within 60 feet of you as if it were bright light, and in darkness as if it were dim light. You can't discern color in darkness, only shades of gray.

\columnbreak

&nbsp;&nbsp;&nbsp; ***Dwarven Combat Training.*** You have proficiency with the battleaxe, handaxe, warhammer, pistol and rifle.

***Stonecunning.*** Whenever you make an Intelligence (History) check related to the origin of stonework, you are considered proficient in the History skill and add double your proficiency bonus to the check, instead of your normal proficiency bonus.

***Languages.*** You can speak, read, and write Common and Dwarven. Dwarven is full of hard consonants and guttural sounds, and those characteristics spill over into whatever other language a dwarf might speak.

***Subrace.*** Ancient divides among dwarves have resulted in three main subraces: ironforge dwarves, wildhammer dwarves, dark iron dwarves. Choose one of these subraces.

#### Ironforge Dwarf
As an ironforge dwarf, you are strong and hardy, capable of enduring the cold of Dun Morogh and blows of battle. Iron&shy;forge dwarves are known for their military expertise and rarely back down from a fight, or a brawl.

***Ability Score Increase.*** Your Strength score <br> increases by 1.

***Dwarven Toughness.*** Your hit point maximum increases by 1, and it increases by 1 every time you gain a level.

***Stoneform.*** You can use your reaction when you are hit by a melee attack you can see to give yourself resistance towards bludge&shy;oning, piercing, and slashing damage until the end of the next turn. You can't use this feature again until you finish a long rest.

#### Wildhammer Dwarf
As a wildhammer dwarf, you have a free spirit and will to live life as you please. Wildhammer dwarves are untamed in comparison to the rest of their kin, often feeling more at home in the air than on the ground.

***Ability Score Increase.*** Your Wisdom score <br> increases by 1.

***Aerie Dwelling.*** You're acclimated to high altitude, in&shy;cluding elevations above 20,000 feet. You're also naturally adapted to cold climates, as described in chapter 5 of the *Dungeon Master's Guide.*

***Brave Beyond Reason.*** You have advantage on saving throws against being frightened.

***Natural Handler.*** You gain proficiency with the Animal Handling skill, and have advantage on Wisdom (animal handling) checks made towards gryphons.

#### Dark Iron Dwarf
As a dark iron dwarf, you have a fiery temper and a fierce determination. Dark iron dwarves worshiped the firelord Ragnaros and gained an affinity for fire and flames. 

***Ability Score Increase.*** Your Intelligence score <br> increases by 1.

***Fireblood.*** You can cast the *lesser restoration* spell on yourself once with this trait, and you regain the ability to cast it this way when you finish a long rest.

***Forged in Flames.*** You have resistance to fire damage.

***Superior Darkvision.*** Your darkvision has a <br> radius of 120 feet.

<div class='footnote'>PART 1 | RACES</div>

\pagebreakNum

<div style='margin-top:286px'></div>

## Night Elf
*Darkness covered us in the beginning, and we could not see. We cried for guidance and the moon shone down bright upon us. Her soft light not only illuminated the night for us but also gave comfort.
<br>Her light touched us from within, enabling us to see even when the moon was not visible...*
<div style="text-align:Right"> 

*— Tyrande Whisperwind* &nbsp;</div>
<div style='margin-top:-5px'></div>

Proud and ancient, the kaldorei once ruled Azeroth as one powerful nation. They were the first to study magic <br>and let it loose throughout the world during the War of the Ancients. Since then most night elves have abandoned arcane, remembering the chaos it brought, turning their attention to raw strength, or the powers of nature.

### Graceful Nature
Imposing in stature, night elves stand as one of the highest race of elves and on Azeroth, with their muscular bodies and slender builds, and long narrow ears. Their skin range in hues of blue, from a light blue sky to the deep blue of the water. With hair varying from a lush green, to blue, to dark purple. It is customary among night elves to paint tattoos across their faces, generally depicting an animal or leaf like design, often done as a rite of passage to adulthood. 

Their eyes shine with a dim golden or silver glow, since the Sundering the golden glow has become ever more common amongst the night elves, a sign of their connection to nature and druidsm. Night elves who's eyes shine silver have left their kins ways for the arcane, and is seen as an outcast by most night elves.

### Belief in the Ancients
Night elves have made close ties to the ancients beings of Azeroth. They have a strong connection to the goddess Elune and have built temples and organizations in her name to carry on her message. The sisters of Elune have long since been the leaders of the night elven military, and official head of their civilization as a whole.

Although Elune stands above all else, the night elves also carry a deep respect and gratitude to the ancient guardians of Azeroth, also know as wild gods, many of whom have not been seen since the blessing of Nordrassil. Was it not for their aid during the War of the Ancients, the night elves would have perished from the surface of Azeroth.

\columnbreak

<div style='margin-top:570px;'></div>

### A Timeless Perspective
Night Elves can live to become thousands of years of age, giving them a broad perspective on events that might trouble the shorter-lived races more deeply. They are often more amused than excited, and more likely to be curious than greedy. They tend to remain aloof and unfazed by petty happenstance. When pursuing a goal, whether adven-turing on a mission or learning a new skill or art, elves can be focused and relentless. They are slow to make friends and enemies, and even slower to forget them.

Like the branches of a young tree, elves are flexible in the face of danger. They trust in diplomacy and compro-mise to resolve differences before they escalate to violence. They have been known to retreat from intrusions into their woodland homes, confident that they can simply wait the invaders out. But when the need arises, elves reveal a stern martial side, demonstrating skill with sword, bow, strategy, and the foces of nature.

### Affiliation
Night elves are members of the Alliance, they pledged their allegiance after the Reign of Chaos, a long fought war that would have dire consequences for the elves and their homeland. Although all members of the Alliance are against the orcs and their Horde, few harbour as much hatred for the orcs as the night elves. They blame the green-skinned brutes for the destruction of their forests and the taint of fel that now protrudes through the Felwoods.

<div class='footnote'>PART 1 | RACES</div>
<img src='https://www.gmbinder.com/images/zD8Zxsp.jpg' style='position:absolute; top:-100px; right:0px; width:800px' />
<img src='https://www.gmbinder.com/images/L60ii4e.png' style='position:absolute; top:-40px; right:0px; width:900px; transform:scaleY(-1)' />
<img src='https://www.gmbinder.com/images/LkQ3kXH.png' style='position:absolute; top:40px; right:-75px; width:500px' />

\pagebreakNum

#### An Ancient Hatred
Many night elves still remember the atrocities brought upon their kin by the highborne elves during the War of the Ancient and show a weariness towards arcane magic and its users. They look down upon their ancient brethren, the high elves—also known as blood elves—with disgust and suspicion. However, despite their grudge, they have been able to work together in the past when deemed a necessity for survival.

### Night Elf Names
Night elven names commonly carry a hidden meaning and are often derived from Darnassian words or phrases. Few night elves keep track of family names and surnames are derived from feats done by the night elf's ancestors, it is rare for a night elf to take a new surname as many takes pride in their forefather's achievements.
<div style='margin-top:-5px;'></div>

**Male Names:** Alegorn, Daros, Eiron, Mathrengyl, Mardant, <br>&nbsp;&nbsp;&nbsp; Gasul, Lanoth, Khardona, Andissiel, Sillarn
<br>**Female Names:** Astaia, Saelienne, Jeen'ra, Lelanai, Keina, <br>&nbsp;&nbsp;&nbsp; Alathea, Lotherias, Cordessa, Aquinne
<br>**Family Names:** Moonlance, Shadewhisper, Nightrunner, <br>&nbsp;&nbsp;&nbsp; Bearwalker, Briarbow, Moonblade, Proudstrider

### Night Elf Traits
Your night elf character has the following racial traits.

***Ability Score Increase.*** Your Dexterity score increases by 2, and your Wisdom score increases by 1.

***Age.*** Night elves reach physical maturity at the pace of humans, but the night elven understanding of adulthood goes beyond physical growth. Night elves typically claim adulthood and an adult name around the age of 100, and can live to become thousands of years old. 

***Alignment.*** Night elves live in close ties with the natural world, they have an unprecedented connection to nature and protect it fiercely, pulling many night elves towards good. They love freedom and variety, making most lean toward the gentler aspects of chaos as well.

***Size.*** Night elves are between 7 and 8 feet tall and weigh between 200 and 240 pounds. Your size is medium. To set your height and weight randomly, start with rolling the size modifier:
<div style="margin-top: -20px; font-family: ScalySans, sans-serif">

<br>&nbsp;&nbsp;&nbsp; ***Size Modifier:*** 2d8
<br>&nbsp;&nbsp;&nbsp; ***Height:*** 6 feet + 7 inches + your size modifier in inches
<br>&nbsp;&nbsp;&nbsp; ***Weight in Pounds:*** 140 + (2d6 x your size modifier)
</div>

<div style='margin-top:-3px;'></div>

&nbsp;&nbsp;&nbsp; ***Speed.*** Your base walking speed is 35 feet.

***Superior Darkvision.*** Accustomed to twilit forests <br> and the night sky, you have superior vision in dark and dim conditions. You can see in dim light within 120 feet of you as if it were bright light, and in darkness as if it were dim light. Your night elven heritage makes your darkvision un&shy;usual: everything you see in darkness is in a shade of violet.

***Kaldorei Weapon Training.*** You have proficiency with the longbow, moon sword, moonglaive, and warglaive.

***Keen Senses.*** You are proficient in the Perception skill.

***Mask of the Wild.*** You can attempt to hide even when you are only lightly obscured by foliage, heavy rain, falling snow, mist, and other natural phenomena.

***Shadowmeld.*** You have advantage on Dexterity (Stealth) checks made while you are heavily obscured by darkness.

***Languages.*** You can speak, read, and write Common and Darnassian. Darnassian is fluid, with subtle intonations and intricate grammar. Its literature is rich and varied, and their songs and poems are famous among other races.

<img src='https://www.gmbinder.com/images/CmjXePR.jpg' style='position:absolute; top:-20px; right:-230px; width:785px' />
<img src='https://www.gmbinder.com/images/E8GrMME.png' style='position:absolute; top:0px; right:-20px; width:900px' />

\pagebreak

<div style='margin-top:340px'></div>

## Gnome
*You never really understood, did you? 
<br> It is our loyalty to our friends that 
<br> provides our truest, greatest strength... <br> My friends. It is a power that numbers 
<br> cannot match.*
<div style="text-align:Right"> 

*— Gelbin Mekkatorque*<span style="margin-right:100px"></span></div>
<div style='margin-top:-5px'></div>

Gnomes are a diminutive, wiry race of tinkers who live underground. In the Second War, they built vehicles and gadgets for the Alliance, submarines and flying machines, to combat the Horde. They are great mechanics and inven&shy;tors, and are renowned for their knowledge and eccentric natures. The gnomes had a city, Gnomeregan, built into Ironforge Mountain. But invading troggs destroyed it and slaughtered its citizens.

Many survivors moved into Khaz Modan and now live with the Dun Morogh dwarves, and a few traveled with their dwarven friends to Kalimdor. 

The gnomes are still reeling from the destruction of their home city and are loath to leave the safety of the dwarven tunnels. Most gnomes on Kalimdor remain secluded in Bael Modan.

### Cheerful Expression
Even after the decimation of their race and the destruction of their city, gnomes are an amiable and kind hearted lot. They make and keep friends easily; others find disliking a gnome to be difficult. A gnome's energy and enthusiasm for living shines through every inch of his or her tiny body. Gnomes average slightly over 3 feet tall and weigh 40 to 45 pounds. Their tan or brown faces are usually adorned with broad smiles (beneath their prodigious noses), and their bright eyes shine with excitement. Their fair hair has a tendency to stick out in every direction, as if expressing the gnome's insatiable interest in everything around.

A gnome's personality is writ large in his or her appearance. A male gnome's beard, in contrast to his wild hair, is kept carefully trimmed but often styled into curious forks or neat points. A gnome's clothing, though usually made in modest earth tones, is elaborately decorated with embroidery, embossing, or gleaming jewels.

\columnbreak

<div style='margin-top:525px'></div>

### Exceptional Tinkers
Gnomes tend to design complicated devices that are relatively safe. Gnomes are in many ways commensurate organizers: a gnome can spend as much time organizing and planning a project as they do actually working on it. If the design fails, they try to learn why, and fix it if they can. 

If they meet with success, they will continue to tinker with it and improve the design, often for years afterward. Thus, many gnomish designs feature a high degree of complexity and a low chance of failure, the exceptions being those that dabble with chaos energy — but even then, they take steps to ensure the worst that could happen is a brief, non-fatal failure.

While a goblin would scream and flee at the mere thought of a cost overrun, a gnome simply shrugs and presses on. If a project fails to work correctly the first time, a gnome will continue to tinker with it, while a goblin would usually give up and move to something else. Thus, gnomish items have very low failure rates compared to goblin items.

### Affiliation
Gnomes are members of the Alliance, their shared origin and close proximity to the ironforge dwarves have forged a great friendship between the two races. They battled the Horde during the Second War and bear a grudge towards the orcs, however, their kind and forgiving nature makes them willing to look past old hatred.

They carry little ill or favor towards the races native to Kalimdor, having yet to spend enough time on the continent to form a proper opinion about its denizens.

<div class='footnote'>PART 1 | RACES</div>
<img src='https://www.gmbinder.com/images/8cYzWBs.jpg' style='position:absolute; top:0px; right:0px; width:1000px; transform:scalex(-1)' />
<img src='https://www.gmbinder.com/images/L60ii4e.png' style='position:absolute; top:50px; right:0px; width:800px; transform:scaley(-1)' />
<img src='https://www.gmbinder.com/images/Vsq5oIs.png' style='position:absolute; top:-160px; right:-100px; width:650px' />

\pagebreakNum

&nbsp;&nbsp;&nbsp; ***Gnomeregan Gnomes.*** These gnomes have considered themselves part of the Alliance since the First War, having joined the cause alongside their dwarven allies.

***Mechagnomes.*** These gnomes have been isolated from the rest of their gnomish kin for centuries. They sought the help of the Alliance to end the world-shattering planes of King Mechagon and re-joined Gnomeregan once his rule over the mechagnomes had ended.

#### Gnomes and Goblins
Gnomes bear a grudge towards goblins, seeing them not as an enemy, but a rival. It has driven the gnomes into friendly and brutal contests with goblins to determine which of the two races are superior.

### Names
Gnomes are given names at birth and rarely change names throughout their life. Although a gnome is born with the family name of their ancestors, gnomish society expects for each gnome to make accomplishments of their own and many gnomes replace their family name with one of their own that portrays their personal accomplishments.
<div style='margin-top:-18px;'></div>

<br>**Male Names:** Grobnick, Kazbo, Hagin, Snoonose, Mikosh, <br>&nbsp;&nbsp;&nbsp; Kebos, Otlak, Ciklin, Therlick, Finlis, Iklirn
<br>**Female Names:** Beggra, Nefti, Sorassa, Gamash, Biskil, <br>&nbsp;&nbsp;&nbsp; Munkull, Inku, Fixi, Mekin, Mitkla, Dapeek
<br>**Family Names:** Spinpistol, Airslicer, Bombtosser, <br>&nbsp;&nbsp;&nbsp; Greatgear, Togglefield, Luyckbreak, Stormhammer

### Gnome Traits
Your gnome character has the following racial traits.

***Ability Score Increase.*** Your Intelligence score increases by 2

***Age.*** Gnomes mature at the same rate humans do, and most are expected to settle down into an adult life by around age 40. They can live 350 to almost 500 years.

***Alignment.*** Gnomes are good-hearted, and even the tricksters amongst them are more playful than vicious. Those of evil alignment are often the result of madness. An innovative idea that consumed them.

***Size.*** Gnomes are between 3 and 4 feet tall and average about 40 pounds. Your size is Small. To set your height and weight randomly, start with rolling the size modifier:
<div style="margin-top: -20px; font-family: ScalySans, sans-serif">

<br>&nbsp;&nbsp;&nbsp; ***Size Modifier:*** 2d4
<br>&nbsp;&nbsp;&nbsp; ***Height:*** 2 feet + 11 inches + your size modifier in inches
<br>&nbsp;&nbsp;&nbsp; ***Weight in Pounds:*** 35 + (1 x your size modifier)
</div>

<div style='margin-top:-3px;'></div>

&nbsp;&nbsp;&nbsp; ***Speed.*** Your base walking speed is 25 feet.

***Artificer's Lore.*** Whenever you make an Intelligence (History) check related to magic items, alchemical <br> objects, or technological devices, you can add twice your proficiency bonus, instead of any proficiency bonus you normally apply.

***Escape Artist.*** You can take the Disengage action as a bonus action on each of your turns. In addition, you gain advantage on ability checks and saving throws to end early and avoid the grappled condition. 

***Languages.*** You can speak, read, and write Common and Gnomish. Gnomish in many ways look like dwarven, it uses the same script, and is renowned for its technical treatises and its catalogs of knowledge about the natural world.

***Subrace.*** Two subraces of gnomes exst in the Alliance: gnomeregan gnomes and mechagnomes. Choose one of these subraces.

\columnbreak

#### Gnomeregan Gnome
As a gnome, you are born with a brilliant mind and cheerful disposition. However, these gnome have suffered treachery, displacement, and near-genocide. It is their remarkable optimism in the face of such calmity that symbolizes their truly unshakable spirit. 

***Ability Score Increase.*** Your Charisma score <br> increases by 1.

***Expansive Mind.*** You can add half your proficiency bonus to any Intelligence ability check you make that doesn't already include your proficiency bonus.

***Gnomish Tinkering.*** You have proficiency with the artisan's tools (tinker's tools). Using those tools, you can spend 1 hour and 10 gp worth of materials to construct a Tiny device (AC 5, 1 HP). The device ceases to function after 24 hours (unless you spend 1 hour maintaining it. This can be done as part of a short or long rest), or when you use your action to dismantle it; at that time, you can reclaim the materials used to create it. You can maintain up to three such devices. 

When you create a device, choose an effect from the *druidcraft, prestidigitation*, or *thaumaturgy* cantrips (for example, increase the volume of your voice or clean an object). A character can use their Action to activate a device and produce the effect chosen for it.

#### Mechagnome
As a mechagnome, you come from a branch of the gnomish race that have lived in isolation for years, tirelessly enhan&shy;cing their own bodies and minds. These gnomes share a lot of qualities with their gnomish cousins, however, they are more cautious in their tinkering, knowing the ruin it brings.

***Ability Score Increase.*** Your Constitution score increases by 1.

***Mechanical Improvements.*** Your body has been altered and enhanced with mechanical marvels. You choose one improvement now and a second improvement at 5th level.
<div style='margin-top:-5px;'></div>

**Emergency Failsafe.** You can use your action to restore a 
<br><span style="margin-left:11px"></span> number of hit points to yourself equal to your level + your 
<br><span style="margin-left:11px"></span> Constitution modifier. You can also use this feature at the 
<br><span style="margin-left:11px"></span> beginning of your turn if you are unconscious (no action 
<br><span style="margin-left:11px"></span> required). Once you use this feature, you can't use it 
<br><span style="margin-left:11px"></span> again until you finish a long rest.
<br>**Enhanced Vision.** Your eyes have been replaced by lenses. 
<br><span style="margin-left:11px"></span> You can see in dim light within 60 feet of you as if it were 
<br><span style="margin-left:11px"></span> bright light, and in darkness as if it were dim light. You 
<br><span style="margin-left:11px"></span> can't discern color in darkness, only shades of gray.
<br> **Mechanical Legs.** Your legs have been replaced by mecha-
<br><span style="margin-left:11px"></span> nical contraptions. Your base movement speed increases 
<br><span style="margin-left:11px"></span> to 30 feet. When you move on your turn, you can double 
<br><span style="margin-left:11px"></span> your speed until the end of the turn. Once you use this 
<br><span style="margin-left:11px"></span> trait, you can't use it again until you move 0 feet on one 
<br><span style="margin-left:11px"></span> of your turns.
<br> **Mecha-arms** Your arms have been replaced by sturdier 
<br><span style="margin-left:11px"></span> limbs and hands. Your unarmed strike deals 1d6 bludge-
<br><span style="margin-left:11px"></span> oning damage. In addition, you gain proficiency with one 
<br><span style="margin-left:11px"></span> artisan's tools of your choice and have incorporated its 
<br><span style="margin-left:11px"></span> necessary tools into your mechanical arms, allowing you 
<br><span style="margin-left:11px"></span> to don or doff the artisan's tool as an action.
<br>**Metallurgic Resilience.** Your torso, arms, and legs have 
<br><span style="margin-left:11px"></span> been replaced with simple and functional mechanical 
<br><span style="margin-left:11px"></span> counterparts. When you aren't wearing armor, your AC 
<br><span style="margin-left:11px"></span> is 13 + your Dexterity modifier. You can use your natural 
<br><span style="margin-left:11px"></span> armor to determine your AC if the armor you wear would 
<br><span style="margin-left:11px"></span> leave you with a lower AC. A shield's benefits apply as 
<br><span style="margin-left:11px"></span> normal while you use your natural armor.

<div class='footnote'>PART 1 | RACES</div>

\pagebreakNum

<div style='margin-top:700px'></div>

## Draenei
*In moments of great strife, I gaze into the heavens and <br> see just how far we have already come.*
<div style="text-align:Right"> 

*— Prophet Velen* &nbsp;</div>
<div style='margin-top:-5px'></div>

Thousands of years ago, the titan Sargeras shattered the tranquility of Argus by offering the eredar immeasurable knowledge and power. The eredar were a knowledge-seeking race and accepted his offer. He bathed them in his fel might, turning them into demonic beings of the burning legion called Man'ari. The prophet Velen got a troubling vision of what his race would become, and fled Argus with his followers by the help of the divine Naaru, who renamed them draenei, or "Exiled Ones" in the common tongue.

The draenei refer to their corrupted brethren as man'ari, meaning "Unnatural Being". Although both originate from the eredar race, neither the draenei or man'ari consider themselves eredars anymore.

\columnbreak

<div style='margin-top:517px'></div>

### Alien Appearance
While they stand tall and proud, they resemble no other race on Azeroth. Their skin ranges from rose white, to dark violet colors. They stand slightly taller than humans on average, ranging from well over 6 feet tall to just over 8 feet. They are generally more muscular than other races, with double jointed legs ending in hooves, weighing 250 pounds or more. Males and females are about the same height, and male are only marginally heavier than females.

Both genders have tendrils in their head as part of their hair or beard, and both have horns, it is common though for females to have drastically larger horns than males. They also have slender tails, males being considerably longer and thicker than females.

Broken draenei, although having many of their pure kins features have noticeable differences, their faces are less structured, and appear more flat than their kins beautiful features. They stand shorter than exodar draenei, their skin hard and cracked like stone, appearing more human than exodar draenei with single jointed legs.

### The Divine Naaru
During the draenei's journey, the enigmatic naaru race taught them the ways of the light, though they already had <br> a certain experience with it through Velen and T'uure. The naaru explained that there were other forces in the cosmos that would stand against the Burning Legion.

The naaru bestowed a blessing, the Gift of the Naaru, upon the draenei to signify their new connection the light. Deeply affected by the naaru's words, the draenei vowed to honor the light and uphold the naaru's ideals.

<div class='footnote'>PART 1 | RACES</div>
<img src='https://www.gmbinder.com/images/zjpuVPM.jpg' style='position:absolute; top:0px; right:0px; width:1090px;transform:scalex(-1)' />
<img src='https://www.gmbinder.com/images/bNHsRrG.png' style='position:absolute; top:90px; right:0px; width:800px; transform:scaleY(-1)' />
<img src='https://www.gmbinder.com/images/m97J1Oq.png' style='position:absolute; top:140px; right:360px; width:500px' />

\pagebreakNum

### Affiliation
Draenei are members of the Alliance, having encountered the noble night elves shortly after their crash landing on Azeroth. Inspired by heroic tales of the Alliance and its vic&shy;tories, the draenei sought out and pledged their loyalty to the Alliance. due to their friendly and honorable attitude, they tend to get along well with races of both the Alliance and Horde, so long as personal grudges aren't included.

***Exodar Draenei.*** These draenei pledged their allegiance to the Alliance shortly after they crash landed on the Azure&shy;must isles. Although their newfound home lies distant from the Eastern Kingdoms and much of the Alliance, they have become a valuable addition to its cause.

***Lightforged Draenei.*** These draenei emerged from the twisting nether to aid in the far against the Burning Legion during the Third Invasion of Azeroth. These draenei were welcomed into the Alliance as they re-joined their exodar kin found on Azeroth.

***Broken Draenei.*** These draenei are outcasts that have never pledged allegiance to any faction on Azeroth. They inhabit the broken planet of Draenor and are as likely to work together with members of the Alliance as they are members of the Horde.

<div style='margin-top:-5px;'></div>

#### Distrust of the Orcs
Although draenei are friendly and honorable towards other races, that attitude is quickly dissolved when confonrted by an orc. They remember the atrocities done to their race by the hands of orcs on Draenor and won't leave bygones of the past to be forgotten. Draenei carry a deep distrust and in some cases hate for the orcs.

<div style='margin-top:-5px;'></div>

### Names
Draenei have two names, a birthname and an name taken upon reaching adulthood. There is no direct separate with&shy;in draenei culture that separate birthnames from a name taken later in a draenei's life. Draenei have lost too much <br> too much to still keep family names.
<div style='margin-top:-18px;'></div>

<br>**Male Names:** Meolphi, Bimerd, Hiktin, Ocdam, Nosmas, <br>&nbsp;&nbsp;&nbsp; Ondut, Broruk, Oter, Lacasik, Midirgerd, Drocran
<br>**Female Names:** Eshaatt, Ize, Ruka, Nalre, Hahse, Efae, <br>&nbsp;&nbsp;&nbsp; Nerii, Asara, Velbus, Fuma, Oren, Suhe, Vumo

### Draenei Traits
Your draenei character has the following racial traits.
 
***Ability Score Increase.*** Your Charisma score <br> increases by 2.
 
***Age.*** Draenei mature slightly slower than humans, reach&shy;ing adulthood around age 20 and they can live thousands of year, exceeding the ancient ages of the night elves.

***Alignment.*** Draenei are mostly good. Those who strive towards law are sages, priests, paladins, vindicators, or scholars. Those who tend toward chaos are warriors, rangers, or in other ways people more fond of pure fighting.
 
***Size.*** Draenei are between 7 and 8 feet tall and weigh between 240 and 300 pounds. Your size is Medium. To set your height and weight randomly, start with rolling the size modifier:
<div style="margin-top: -20px; font-family: ScalySans, sans-serif">

<br>&nbsp;&nbsp;&nbsp; ***Size Modifier:*** 2d6
<br>&nbsp;&nbsp;&nbsp; ***Height:*** 6 feet + 5 inches + your size modifier in inches
<br>&nbsp;&nbsp;&nbsp; ***Weight in Pounds:*** 150 + (2d8 x your size modifier)
</div>

<div style='margin-top:-3px;'></div>

&nbsp;&nbsp;&nbsp; ***Speed.*** Your base walking speed is 30 feet.
 
***Shadow Resistance.*** You have resistance against <br>necrotic damage.

&nbsp;&nbsp;&nbsp; ***Languages.*** You can speak, read, and write Common and Draenei. The Draenei language, is a strange and compli-cated language for other races to learn. Seemingly having no resemblance with any Azerothian languages.

***Subrace.*** Three subraces of draenei exist: exodar draenei, lightforged draenei, and broken draenei. Choose one of these subraces.

<div style='margin-top:-5px;'></div>

#### Exodar Draenei
As an exodar draenei, you have a natural connection with the Naaru, strengthening your bond to the light. You have fled your home planet of Argus from the Burning Legion's crusade, forced into exile for centuries before crash land&shy;ing on Azeroth's Azuremyst Isles.

***Ability Score Increase.*** Your Strength score <br> increases by 1.
 
***Gemcutting.*** You are proficient with the jeweler's tools.
 
***Gift of the Naaru.*** As an action, you can touch a creature and cause it to regain a number of hit points equal to your character level. Once you use this trait, you can’t use it again until you finish a long rest.
 
***Heroic Presence.*** You can cast *heroism* and *divine favor* with this trait, using Wisdom as your spellcasting ability for them. Once you cast either spell, you can’t cast it again with this trait until you finish a long rest.

<div style='margin-top:-5px;'></div>

#### Lightforged Draenei
As a lightforged draenei, you have committed yourself to a crusade against the burning legion, infusing your body with the holy light. You are part of the Army of the Light, a force of draenei that took the fight with the Burning Legion into the Twisting Nether and more recently, Azeroth.

***Ability Score Increase.*** Your Constitution score increases by 1.

***Forged of Light.*** The holy light's warmth envelopes you. When you aren't wearing armor, your AC is 12 + your Dexterity modifier. You can use your natural armor to determine your AC if the armor you wear would leave you with a lower AC. A shield's benefits apply as normal while you use natural armor.

***Holy Resistance.*** You have resistance to radiant damage.
 
***Light's Judgement.*** You know the *light* cantrip. When you reach 3rd level, you can cast the *guiding bolt* spell once per long rest. When you reach 5th level, you can cast the *branding smite* spell once per long rest. Wisdom is your spellcasting ability for these spells.

<div style='margin-top:-5px;'></div>

#### Broken Draenei
As a broken draenei, you were left on Draenor as the legion invaded, your connection to the Naaru have been severed, leaving you an empty shell of your kin. The severance has disfigured your form, making you a outcast amongst the exodar and lightforged draenei.

***Ability Score Increase.*** Your Wisdom score <br> increases by 1.

***Darkvision.*** Accustomed to the unlit sky of Outland, you have superior vision in dark and dim conditions. You can see in dim light within 60 feet of you as if it were bright light, and in darkness as if it were dim light. You can't discern color in darkness, only shades of gray.

***Elemental Bond.*** You know the *frostbite* cantrip. When you reach 3rd level, you can cast the *earth tremor* spell once per long rest. When you reach 5th level, you can also cast the *gust of wind* spell once per long rest. Wisdom is your spellcasting ability for these spells.

***Outcast.*** You are proficient in the Survival skill.

<div class='footnote'>PART 1 | RACES</div>

\pagebreakNum

<div style='margin-top:540px'></div>

## Worgen
*When I told you that I wanted to retake Gilneas City from these Forsaken. There were those who said that it was impossible. I say that we no longer let our fears control us! For too long it has controlled me, fear that if all of you knew the whole truth, you would reject me. I give in no longer. Look at me... Now that you know the truth, I ask of you, who will stand with me, who will fight by my side?*
<div style="text-align:Right"> 

*— Genn Greymane* &nbsp;</div>
<div style='margin-top:-5px'></div>

Worgens are vicious humanoid wolves, a curse thrown upon them by careless druids mingling in powers that were beyond them. The druids turned into the first worgen, feral and uncontrollable, they were sealed away for countless years when night elves realized that their bite was able to transfer the curse to others.

When the forsaken sieged the kingdom of Gilneas, the worgens were released from their imprisonment to fight the undead. The feral worgens were effective, but did not differentiate undead from human. The feral worgens never entered Gilneas, but the humans did. Spreading the curse through the kingdom like wildfire. Realizing their mistake, the night elves came to gilneas rescue to offer their aid, they evacuated as many people as they could, and sailed them to their homeland in Teldrassil. There, night elven druids taught the gilnean people how to control the feral curse that lingered in their veins. Some gilneas were so fascinated by the elves magic and connection to druidism, that they were taught their ways.

\columnbreak

<div style='margin-top:365px'></div>

### Fierce and Vicious
With their massive shapes of a cross between a human and wolf, and the razor sharp claws, worgens appear like evil of a children's tale to those unaware of their existence. They loom over the heads of humans, ranging well over 6 feet to just under 8 feet. Their furry bodies often make them seem much larger than they are, yet with their massive bodies they weigh between 220 to 310 pounds. Males and females are about the same height and build, with the only distinct difference being a males mane.

Worgen fur varies widely in coloration, with shades of black, gray, and brown being the most common amongst the worgen kin, even if the worgen had light colorations in skin or hair as a human. Worgen eyes vary like humans, from a light blue to a deep brown.

### More than just Ferocious
With their wild appearance it is easy to think of a worgen as a vicious beast. Yet most still carries the properties they had in their human life. The curse will always linger in their blood, giving many worgen's a shorter temper than they might've had before. Yet they carry the same compas-sion and determination as humans do, pushing themselves forward to achieve ever greater things for themselves, their newfound kin and that of the human.

### Affiliation
Worgens are members of the Alliance, although the curse of the worgen altered them physically, they are still humans at their core and the founding race of the Alliance. Worgens are respectful and trusts the races that have affiliated them&shy;selves with the Alliance. However, the gratitude and respect they carry for night elves is hard to match and without their aid the worgen race would still be feral and hostile to all.

#### Forsaken Hatred
Although no race, Alliance or Horde, trusts or truly likes the forsaken, the gilnean hatred for the undead race goes deeper than most. They have caused much harm to the gil&shy;nean people and lead to the demise of Kingdom of Gilneas, a fact that worgens have and will never forget.

<div class='footnote'>PART 1 | RACES</div>
<img src='https://www.gmbinder.com/images/hc81G0c.jpg' style='position:absolute; top:-250px; right:-50px; width:1200px' />
<img src='https://www.gmbinder.com/images/L60ii4e.png' style='position:absolute; top:0px; right:0px; width:900px; transform:rotate(180deg)' />
<img src='https://www.gmbinder.com/images/nV6NTzk.png' style='position:absolute; top:120px; right:170px; width:750px; transform:scalex(-1)' />

\pagebreakNum

---

\columnbreak

### Worgen Names
Most worgens were gilnean humans and follow the naming conventions of humans. However, when the worgen curse turned them feral, it made some worgens forget their past names and lives. These worgens choose a new gilnean first name and a last name based on feats of strengths done during their cursed worgen life.
<div style='margin-top:-5px;'></div>

**Male Names:** Blake, Chris, Fenegan, Gerard, James, Sean, <br>&nbsp;&nbsp;&nbsp;Sebastian, Vincent, Slain, Tobias, Vitus
<br> **Female Names:** Amelia, Ashley, Celestine, Loren, Mary, <br>&nbsp;&nbsp;&nbsp; Melinda, Mia, Tess, Almyra
<br> **Gilnean Surnames:** Broderick, Cleese, Crowly, Godfrey, <br>&nbsp;&nbsp;&nbsp;  Walden, Whitewall, Hammond, Hayward
<br> **Worgen Surnames:** Greymane, Moonfang, Mistmantle, <br>&nbsp;&nbsp;&nbsp; Bloodfang, Darkwalker

<div style='margin-top:-5x;'></div>

### Worgen Traits
Your worgen character has the following racial traits.

***Ability Score Increase.*** Your Strength score increases by 2, and your Dexterity score increases by 1.

***Age.*** Worgen age like humans, but even though their bodies continue to age, they never feel the strain of old age, and continue to fight as if they were a young human. 

***Alignment.*** Worgen tend to become chaotic, while originating from humans, the infection of their blood with the wolves has made them more unpredictable.

***Size.*** Like humans, they vary widely in height and build, most standing well over 6 feet tall, and weigh around 250 pounds. Your size is Medium. To set your height and weight randomly, start with rolling the size modifier:
<div style="margin-top: -20px; font-family: ScalySans, sans-serif">

<br>&nbsp;&nbsp;&nbsp; ***Size Modifier:*** 2d10
<br>&nbsp;&nbsp;&nbsp; ***Height:*** 6 feet + 2 inches + your size modifier in inches
<br>&nbsp;&nbsp;&nbsp; ***Weight in Pounds:*** 155 + (2d8 x your size modifier)
</div>

<div style='margin-top:-3px;'></div>

&nbsp;&nbsp;&nbsp; ***Speed.*** Your base walking speed is 30 feet. Your worgen claws gives you a climbing speed of 20 feet.

***Darkvision.*** Accustomed to the black nights, you have superior vision in dark and dim conditions. You can see in dim light within 60 feet of you as if it were bright light, and in darkness as if it were dim light. You can't discern color in darkness, only shades of gray.

***Bite.*** Your ranged maw is a natural weapon, which you can use to make unarmed strikes. If you hit with it, you deal piercing damage equal to 1d6 + your Strength modifier.

***Keen Hearing and Smell:*** You have advantage on Wisdom (Perception) checks that rely on hearing or smell.

***Hunter's Lore.*** You gain proficiency with one of the following skills of your choice: Animal Handling, Nature, Perception, Stealth, or Survival.

***Standing Leap.*** Your long jump is up to 30 feet and your high jump is up to 20 feet, with or without a running start.

***Two Forms.*** Using 1 minute, you can transform yourself into a human. While human, you appear as you did before getting affected by the worgen curse. You always appear as the same human when you transform. You can transform back into a worgen as a free action on your turn, and you immediately revert to your worgen form if you make an attack or casts a spell that affects an enemy creature.

***Languages.*** You can speak, read, and write Common and one extra language of your choice. Humans typically learn the languages of other peoples they deal with, including obscure dialects. They are fond of sprinkling their speech with words borrowed from other languages: Dwarven curses, Darnassian musical expressions, Gnomish tongue twisters, and so on.

<div class='footnote'>PART 1 | RACES</div>
<img src='https://www.gmbinder.com/images/ymeA1sL.jpg' style='position:absolute; top:-70px; right:200px; width:800px' />
<img src='https://www.gmbinder.com/images/Npi5n8k.png' style='position:absolute; top:0px; right:-10px; width:900px' />

\pagebreakNum

<style> .phb#p20:after { display:none; } </style>
<div class='cover-header'> <div style='margin-top:50px;'></div> Races of the Horde </div>
<img src='https://www.gmbinder.com/images/yymWGtB.jpg' style='position:absolute; top:0px; right:0px; width:800px' />

\pagebreak

<div style='margin-top:350px;'></div>

## Orc
*To pretend the demonic corruption did not exist is to forget how dreadful the impact was. To make ourselves into victims, rather than claiming our participation in our own destruction. We chose this path, we orcs. We chose it right up until it was too late to turn back. And having made that choice, we can, with the knowledge that we have of the end of that dark and shameful road, choose not to take it.*
<div style="text-align:Right"> 

*— Warchief Thrall* &nbsp;</div>
<div style='margin-top:-5px'></div>

When the orcs were freed from the Burning Legion, they experienced a spiritual revolution as the unnatural blood&shy;lust left their bodies, connecting them with states of heart and mind that were common to their ancestors. This new generation of orcs for the most part followed Thrall as he forged the Horde through shamanism and tribal traditions.

Though prone to fits of rage in warfare, orcs tend to display a curious feral grace that can rival even the finest fencing of an elven noble. The orcs of today continue to stand in drastic contrast to those that were enslaved by the Burning Legion, who embodied a bestial and diabolical force which was barely being controlled by warlock magic.

### Mindful Individuals
To orcs, prowess in battle bestows great personal honor on an individual. This notion of honor pervades every echelon of orcish culture, and the loss or gain of honor has equal consequence to all orcs regardless of their stature. 

Even the naming of orcs is temporary until they have performed rites of passage; only when orcs bring honor to themselves and thus to their clan do elders grant them adult names based upon their deeds. Orcs may appear quick to anger but they are tempered by the wisdom of <br> the shamans, who are revered across Horde society.

While many in the Alliance still perceive the orcs as brutish or even mindless, they have forged a complex culture embracing many occupations and many different races. No doubt Thrall's leadership aided in bringing this about, yet it is apparent that the Alliance has underesti&shy;mated the orcs' ability to construct a society that is highly influential in world affairs.

\columnbreak

<div style='margin-top:595px;'></div>

### A Spiritual Connection
As far back as orcish history has been recorded, shaman have been mentioned, and learning to speak with the elemental spirits of Draenor was a pivotal achievement in destiny for the orc clans. The first orcs to learn the ways of shamanism hailed from the Shadowmoon clan, but many clans claim the mythical "First Shaman" arose from their ranks, even though the truth is that no one is sure of his or her allegiance.

Several orc shaman worship or at least acknowledge <br> the Earth Mother, the benevolent creator deity primarily worshipped by the tauren.

### Frightful Appearance
Orc males are massive and brutish looking creatures. Weighing in at 250 to 350 pounds and standing from 6 to 7 feet in height, they are not a small race. Even orc women tend to be only a half-foot or so shorter than most males, having broad shoulders and muscular, powerful bodies.

Orcs tend to have bristly hair and beards, often black or brown in color. Their skin ranges from a light green to a dark drab olive. Eyes range in color from a fierce red to a pale blue. Orcs have broad, flat noses, tusk-like teeth jutting from their lower and sometimes upper jaws, and large, pointed ears. They favor clothes of hide, and armor and arm themselves with a variety of gear.

<div class='footnote'>PART 1 | RACES</div>
<img src='https://www.gmbinder.com/images/E086d0Y.jpg' style='position:absolute; top:-50px; right:0px; width:800px' />
<img src='https://www.gmbinder.com/images/L60ii4e.png' style='position:absolute; top:0px; right:0px; width:900px; transform:scaley(-1)' />
<img src='https://www.gmbinder.com/images/tPFTqoe.png' style='position:absolute; top:100px; right:0px; width:400px' />

\pagebreakNum

### Affiliation
Orcs are members of the Horde and it would not exist with&shy;out them. They forged the Orcish Horde prior to the First War and the New Horde—also known as the Horde—during the Third War as the orcs made a lasting bond with races native to the continent of Kalimdor. Much of the Horde continues to be influenced by orcish culture and laws.

Although most orcs are members of the Horde, there are those who chose to isolate themselves from its influence and affiliated races. These clans are rarely friendly towards the Horde or its races and some show open hostility.

### Names
Most orcish names derive from words in their language that have some complex meaning or hidden significance to their families. Typically, this is the name of a favorite thing or relative. Family names don’t exist; most orcs have last names related to some great deed of heroism or honor. 
<div style='margin-top:-18px;'></div>

<br>**Male Names:** Grom, Thrum, Drog, Gorrum, Harg, Thurg, <br>&nbsp;&nbsp;&nbsp; Karg, Regg, Kavenk, Uketel, Thrarturg, Crurn
<br>**Female Names:** Groma, Hargu, Igrim, Agra, Dragga, <br>&nbsp;&nbsp;&nbsp; Grima, Fehmo, Mohma, Sherge, Zuri, Orgis
<br>**Deed Names:** Cravensmile, Steelflame, Twinthunder, <br>&nbsp;&nbsp;&nbsp; Gravepride, Aridfire, Coldbrass, Foebinder, Elfkiller

### Orc Traits
Your orc character has the following racial traits.

***Ability Score Increase.*** Your Strength score increases by 1, and your Constitution score increases by 1.

***Age.*** Orcs mature a little faster than humans, reaching adulthood around age 14. They age noticeably faster and rarely live longer than 75 years.

***Alignment.*** Orcs might not have an innate tendency toward evil, but many end up there. Evil or not, many orcs lean toward a chaotic alignment.

***Size.*** Orcs are between 6 and 7 feet tall and muscularly built, averaging around 300 pounds. Your size is Medium. To set your height and weight randomly, start with rolling the size modifier:
<div style="margin-top: -20px; font-family: ScalySans, sans-serif">

<br>&nbsp;&nbsp;&nbsp; ***Size Modifier:*** 2d8
<br>&nbsp;&nbsp;&nbsp; ***Height:*** 5 feet + 10 inches + your size modifier in inches
<br>&nbsp;&nbsp;&nbsp; ***Weight in Pounds:*** 200 + (2d6 x your size modifier)
</div>

<div style='margin-top:-3px;'></div>

&nbsp;&nbsp;&nbsp; ***Speed.*** Your base walking speed is 30 feet. 

***Menacing.*** You gain proficiency in the Intimidation skill.

***Orcish Weapon Training.*** You have proficiency with the handaxe, battleaxe, and warclaw.

***Relentless Endurance.*** When you are reduced to 0 hit points but not killed, you can drop to 1 hit point instead. You must then finish a long rest to use this feature again.

\columnbreak

&nbsp;&nbsp;&nbsp; ***Languages.*** You can speak, read, and write Common and Orcish. Orcish is a harsh, grating language with hard consonants. It has no script of its own but is written in a mix of dwarven runes and common.

***Subrace.*** Orcs are taught different skills depending on their clan. Orcish clans are categorized into three: hunter clans, mystic clans, and warrior clans. Choose one of these clans and work with your DM to determine the significance of your chosen clan.

#### Hunter Clans
Some orc clans prefer a more stealth approach to things, hiding and waiting for the perfect time to ambush, such as the Shattered Hand clan, and the Bleeding Hollow clan. 

***Ability Score Increase.*** Your Dexterity score <br> increases by 1.

***Ambusher.*** You gain proficiency in the Stealth skill.

***Surprise Attack.*** If you surprise a creature and hit it with an attack on your first turn in combat, the attack deals an extra 1d6 damage to it. The damage increases to 2d6 at 6th level, 3d6 at 11th level, and 4d6 at 16th level. You can use this trait only once per combat.

#### Mystic Clans
Not many orc clans go in for the use of magic, and those that do are usually more secretive than the rest. Generally less keen on working with other clans are spend their time as a nomadic folk rather than settling in a certain area. Such clans include The Shadowmoon, and Stormreaver. 

***Ability Score Increase.*** Your choice of your Intelligence or Wisdom score increases by 1.

***Ancestral Call.*** You can cast the *augury* spell once with this trait, requiring no material components, and you regain the ability to cast it this way when you finish a long rest. Wisdom is your spellcasting ability for this spell.

***Mystic Lore.*** You are proficient with one of the following skills of your choice: Arcane, History, Nature, or Religion.

#### Warrior Clans
Most known orc clans go for the brute forced approach, entering combat gladly with raised weapons, hammering down everything in their way. Some of the larger clans include Warsong, Burning Blade, and the Frostwolves. 

***Ability Score Increase.*** Your Strength score <br> increases by 1.

***Aggressive.*** As a bonus action, you can move up to <br> your speed toward an enemy of your choice that you can see or hear. You must end this move closer to the enemy than you started.

***Savage Attacks.*** When you score a critical hit with a melee weapon attack, you can roll one of the weapon's damage dice one additional time and add it to the extra damage of the critical hit.

<img src='https://www.gmbinder.com/images/BiY1eMt.jpg' style='position:absolute; top:820px; right:0px; width:800px' />
<img src='https://www.gmbinder.com/images/3e9S91s.png' style='position:absolute; top:0px; right:0px; width:800px' />

\pagebreak

<div style='margin-top:357px'></div>

## Forsaken
*Death offered no escape for the scores of humans killed during the Lich King’s campaign to scour the living from Lordaeron. Instead, the kingdom’s fallen were risen into undeath as Scourge minions and forced to wage an unholy war against everything. . . and everyone. . . that they once held dear.*
<div style='margin-top:0px'></div>

Humans and elves freed from the control of the Lich King who raised them. The forsaken are a strange and dark force, hailing from the twisted, skittering darkness of Undercity, they are nominally allied with the Horde but serve only their own cause.

Under the Lich Kings crusade, the elven Ranger General Sylvanas Windrunner fell in combat. Prince Arthas raised her as a banshee and compelled her to follow his will and command. When the Lich King’s power waned in the inci&shy;dents surrounding the Frozen Throne, Sylvanas harnessed her fury and tore herself free from his skeletal grasp. She freed many other undead as well, and recruited powerful allies from the Burning Legion and the surrounding ogre clans. Sylvanas dubbed her new force the Forsaken, and the undead established their capital in the labyrinthine crypts beneath Lordaeron’s capital city. Their sprawling, subterranean realm now called Undercity.

### A Necessary Alliance
The Forsaken originally became allies of the Horde out of necessity and convenience. They have no love for orcs, tauren or any other living creature, but they need time to strike against the Scourge and allies to help them do it. The Forsaken claim that they joined the Horde to prove their desire to leave their evil ways behind, but no one really believes this. The Horde accepts the forsaken’s help, as they do indeed have a common enemy: the Scourge. The Horde is leery of the forsaken’s tactics, however, and keeps watchful eyes on them.

Though initially the Forsaken alliance with the Horde was one of pure convenience, in recent times it appears that their position in the faction has begun to solidify and many, though not all, of the Forsaken appear to be more or less loyal to the Horde now. 

<div style='margin-top:-5px;'></div>

\columnbreak

<div style='margin-top:690px;'></div>

### Strange Behaviors
Forsaken culture is strange, a perverse combination of the lives they once knew as mortals and the mindless slavery they experienced in the Scourge, colored by white-hot rage toward the Lich King and an almost equally intense devotion to their queen. 

Some Forsaken attempt to reclaim their humanity by acting in kind and helpful ways. Others allow hatred to fester into cruelty and rage.

### Extreme Alchemists
Never sleeping, eating or falling ill, abandoned by those they once loved, the Forsaken have a brutal set of priorities. 

A great portion of their efforts focus on dark alchemy, and the Royal Apothecary Society commands great power in Undercity’s oily tunnels. The apothecaries constantly send Forsaken on missions to gather odd materials for their twisted experiments. Rumors tell that the undead creatures are working to create a plague that will exterminate the Scourge and every living being on Azeroth.

<div class='footnote'>PART 1 | RACES</div>
<img src='https://www.gmbinder.com/images/suFd7Ev.jpg' style='position:absolute; top:0px; right:0px; width:850px' />
<img src='https://www.gmbinder.com/images/L60ii4e.png' style='position:absolute; top:70px; right:0px; width:800px; transform:scaley(-1)' />
<img src='https://www.gmbinder.com/images/68gnFHN.png' style='position:absolute; top:150px; right:-70px; width:700px' />

\pagebreakNum

### Dreadful Looks
Forsaken, unsurprisingly, look like dead people who've been dug up from their graves. Their skin has turned gray and rotting, with bone peeking through the rotted flesh. Their resurrection have given their pupil-less eyes a dim glow of white ghostlight. Most of their muscle have rotted away, giving them a scrawny appearance with jagged move&shy;ments. Their dark resurrection have kept them preserved, but natural decay still proceeds, just at an extremely slow rate compared to normal.

### Affiliation
Forsaken are members of the Horde. Though they do not trust the Horde, nor does most members of the Horde trust them. Their alliance was one of necessity more than desire and the forsaken do their best to help and placate ambassa&shy;dors sent by the Horde. Although some forsaken remember their old life and wishes to be reunited with their family, few families have accepted what has become of their loved ones who've been brought into undeath.

### Names
Forsaken have no naming conventions of their own, most keep the names they were given in life. Forsaken who can't remember their name, or simply desires a new one, often make up a suitable name of their own or pick one they saw on a headstone.

### Forsaken Traits
Your forsaken character has the following racial traits.

***Ability Score Increase.*** Your Constitution score increases by 2.

***Age.*** Forsaken do not age, as the undeath ends this process when they are brought back. However, decay and rot can affect the forsaken's mind, and as time goes on they experience issues similar to those of aging.

***Alignment.*** When brought back to undeath, forsaken keep the alignment they had in life. However, most tend to become more chaotic and very few keep a good alignment after decades of being an undead.

***Size.*** Forsaken stand as tall as they did in life and weigh between half as much to as much as they did in life. Your size is Medium. To set your height and weight randomly, refer to the Human and Blood Elf race.

***Speed.*** Your base walking speed is 30 feet.

***Darkvision.*** Born into undeath by unholy magic, you can see normal in dark and dim conditiions. You can see in dim light within 60 feet of you as if it were bright light, and in darkness as if it were dim light. You can't discern color in darkness, only shades of gray.

\columnbreak

&nbsp;&nbsp;&nbsp; ***Grave's Rest.*** When you take a long rest, instead of rest&shy;ing, you must spend at least six hours performing light activities to gain the benefits of a Long Rest.

***Undead Nature.*** Your creature type is undead, rather than humanoid. You also gain the following benefits:
<div style='margin-top:-5px;'></div>

- You count as a humanoid for the purpose of attacks, spells, and features that have no effect on undead.
- You have advantage on saving throws against being poisoned, and you have resistance to poison damage.
- You don't need to eat, drink, or breathe.
- You don't need to sleep, and magic can't put you to sleep
<div style='margin-top:-5px;'></div>

&nbsp;&nbsp;&nbsp; ***Will of the Forsaken.*** You have advantage on saving throws against being charmed and effects that turn undead.

***Languages.*** You can speak, read, and write Common and Gutterspeak. Gutterspeak is a lower form of Common used by shady underground markets and rogues' guilds as a tongue of ill-repute.

***Subrace.*** Two subraces of forsakens are found among the undeads of Lordaeron: forsaken humans and forsaken elves. Choose one of these subraces.

#### Forsaken Human
As a forsaken human, you were once a human of the proud nation of Lordaeron. Raised as a minion to the Scourge as it passed through and leveled the kingdom with the ground. These forsaken make up the majority of their race, filling the roles of great commanders and simple merchants for the growing forsakens.

***Ability Score Increase.*** One other ability scores of your choice increases by 1.

***Determination.*** When you make an attack roll, an ability check, or a saving throw, you can do so with advantage. You can't do so again until you finish a short or long rest.

***Skill Versatility.*** You gain proficiency in one skill of <br>your choice.

#### Forsaken Elf
As a forsaken elf, you were once a high elf of Quel'thalas who died to the Scourge as it crawled through the land on its journey towards the Sunwell. The tenacity of the elves have made you rise above the common humans that fill out the forsaken nation. These forsaken are often found in high places and positions of power.

***Ability Score Increase.*** Your Intelligence score increases by 1.

***Arcane Knowledge.*** You are proficient in the Arcana skill, and you can cast *detect magic* with this trait, using Intelligence as your spellcasting ability for it. Once you cast detect magic, you can't cast it again until you finish a short or long rest.

***Extra Language.*** You can speak, read, and write Thalassian.

<img src='https://www.gmbinder.com/images/M8d875w.jpg' style='position:absolute; top:400px; right:0px; width:800px' />
<img src='https://www.gmbinder.com/images/3e9S91s.png' style='position:absolute; top:-40px; right:0px; width:800px' />

\pagebreak

<div style='margin-top:120px;'></div>

## Tauren
*Our people have walked this land for many, many years, and in that time have learned much about the world. Our allies will need to look to us for wisdom and guidance. My father once made a promise to the Horde, to repay a debt we owed them for their service to our race. I, for one, intend to deliver on that promise.*
<div style="text-align:Right"> 

*— High Chieftain Baine Bloodhoof* &nbsp;</div>
<div style='margin-top:-5px'></div>

The plains of Kalimdor have long been a home to these gargantuan nomads. The tauren are a race of spiritual shamans, hunters, and fighters, who long ago developed a complex culture and system of living without the aid of stonework, steel or conquest. This is not to say that the tauren are a race of pacifists, when they are angered they are capable of retaliating with swift and decisive brutality. 

The tauren are a noble race that embrace the natural world. They have shed their nomadic roots and united in their ancestral lands. Their race may be one of spirituality, reverence for nature, and respect for elders, but it also possesses powerful warriors that willingly fight when the situation demands it. Although strong and capable warriors when roused in battle, most tauren reserve combat for when all other options are exhausted. 

They prefer course of wise discussion and careful rumination before embarking on any great endeavor,
<br> and they have great respect for the wise, spiritual and elderly among their people. The tauren are not wrathful 
<br> by nature, but sometimes a thirst for justice causes them 
<br> to take up arms in anger. 

### Peaceful Race
Tauren have no love for bloodshed, as their deep spiritual beliefs do not have a place for warfare. The elders of a tribe solve most issues, or two tauren might resolve a conflict with a ritual challenge resembling a duel. 

Having become members of the Horde, the introspective race has been involved in more and more conflict, creating a demand for tauren warriors and healers. Many must spend time putting great thought into the actions they perform on the field of battle. Taking another life, whether it is man or beast, is an act filled with great significance and responsibility to the tauren.

### Majestic Appearance
Tauren are large, and muscular with bull-like heads. Males average 10 feet tall and 500 pounds, while females are usually a bit shorter and lighter. Tauren are mostly muscle, having incredibly developed physiques and brawny frames most suitable for combat. Soft, downy fur covers the tauren body, with manes growing along head and neck, the lengths of the arms, and the shins.

Their coloration can range from solid black to blond and even white, to mottled pelts of multiple colors. Although all tauren have horns, they are considerably more prominent on males than females.

<div class='footnote'>PART 1 | RACES</div>
<img src='https://www.gmbinder.com/images/tr3MMTm.jpg' style='position:absolute; top:0px; right:0px; width:1000px' />
<img src='https://www.gmbinder.com/images/E8GrMME.png' style='position:absolute; top:0px; right:0px; width:900px' />
<img src='https://www.gmbinder.com/images/kxJtn7u.png' style='position:absolute; top:450px; right:-128px; width:700px' />
<img src='https://www.gmbinder.com/images/2k2FW0N.jpg' style='position:absolute; top:-70px; right:570px; width:350px; mix-blend-mode:multiply' />

\pagebreakNum

### Affiliation
Tauren are members of the Horde. When they first met the orcs after their arrival on Kalimdor, they recognized them as spiritual brethrens for their connection to the elements. Tauren pledged their allegiance to the Horde and see both the orcs and trolls as brothers. Like all, they tolerate the forsaken but never rely or trust them and give blood elves a similar treatment for their taint with magic.

Tauren bear no personal ill will towards the Alliance and view night elves with awe and fear. The two races have co&shy;existed on Kalimdor for centuries and Tauren have long seen the night elves as a mythical race steeped in natural powers and wielders of great magic.

***Mulgore Tauren.*** These tauren pledged their allegiance to Thrall's Horde when it first arrived on Kalimdor and are steadfast allies to its cause.

***Highmountain Tauren.*** These tauren lived isolated from the rest of their kin upon the Broken Isles until the Burning Legion's Third Invasion of Azeroth. Once the legion and its forces had been pushed back into the Twisting Nether, they received an invitation into the Horde by Baine Bloodhoof.

***Taunka.*** These tauren pledged their allegiance to the Horde as they were forced to migrate across North&shy;red as the Scourge encroached on their homes. Although they are members of the Horde, few taunka leave the comforts and cold of Northrend and ventures beyond.

### Names 
The language of the tauren is often harsh and low sounding, which is reflected in the names of their children. The last name of a tauren is usually a family name, handed down through the generations. If the tauren has performed some act that has made an impression on the elders of his tribe, however, he may choose to take on his own last name to commemorate that act.

<div style='margin-top:-18px;'></div>

<br>**Male Names:** Azok, Bron, Turok, Garaddon, Hruon, Etu, <br>&nbsp;&nbsp;&nbsp; Jeddek, Mechi, Cochu, Huslu, Idra, Naalnish
<br>**Female Names:** Argo, Serga, Grenda, Beruna, Halfa, <br>&nbsp;&nbsp;&nbsp; Atepa, Chepi, Mabu, Foston, Pakuna, Halona
<br>**Family Names:** Darkthorn, Thunderhoof, Stormhorn, <br>&nbsp;&nbsp;&nbsp; Quillsplitter, Stonebreaker, Plainstalker, Spiritwalker

### Tauren Traits
Your tauren character has the following racial traits.

***Ability Score Increase.*** Your Strength increases by 2.

***Age.*** Tauren reaches adulthood in their mid teens, and most grow to be 95 years old, few live beyond a century. 

***Alignment.*** Most tauren are lawful, keeping to their tribal code. Those who are evil are shunned upon, most either outlaws or corrupted in some form.

***Size.*** Tauren are between 8 and 10 feet tall and weigh between 400 and 600 pounds. Your size is Medium, yet you tower over most other humanoids. To set your height and weight randomly, start with rolling the size modifier:
<div style="margin-top: -20px; font-family: ScalySans, sans-serif">

<br>&nbsp;&nbsp;&nbsp; ***Size Modifier:*** 2d12
<br>&nbsp;&nbsp;&nbsp; ***Height:*** 7 feet + 11 inches + your size modifier in inches
<br>&nbsp;&nbsp;&nbsp; ***Weight in Pounds:*** 320 + (2d10 x your size modifier)
</div>

<div style='margin-top:-3px;'></div>

&nbsp;&nbsp;&nbsp; ***Speed.*** Your base walking speed is 30 feet.

***Horns.*** Your horns are natural melee weapons, which you can use to make unarmed strikes. If you hit with them, you deal piercing damage equal to 1d6 + your Strength modifier, instead of the bludgeoning damage normal for an unarmed strike.

&nbsp;&nbsp;&nbsp; ***Powerful Build.*** You count as one size larger when determining your carrying capacity and the weight you can push, drag, or lift.

***Tauren Weapon Training.*** You have proficiency with the halberd, battle totem, pistol and rifle.

***Languages.*** You can speak, read, and write Common and Taur-ahe. Taur-ahe is a harsh, and low sounding language, without a proper alphabet, their written language is made of elaborate pictograms and pictoforms.

***Subrace.*** Three subraces of tauren populate Azeroth: mulgore tauren, highmountain tauren, and taunka. Choose one of these subraces.

#### Mulgore Tauren
As a mulgore tauren, you are among the most common of the tauren kin's. Mulgore tauren have lived on Kalimdor for countless years. These taurens are calm and honorable when met, and fierce fighters when fought. These tauren have a deep respect for nature and the Earth Mother, only taking what they need from the land to survive.

***Ability Score Increase.*** Your Wisdom score <br> increases by 1.

***Endurance.*** Your hit point maximum increases by 1, and it increases by 1 every time you gain a level.

***War Stomp.*** You can cast the *earth tremor* spell once with this trait, by stomping your hoof into the ground, and regain the ability to do so when you finish a long rest. Strength is your spellcasting ability for this spell.

#### Highmountain Tauren
As a highmountain tauren, you hail from the Broken Isles. Highmountain taurens have secluded themselves in the isle's mountains for generations. They harbour no hatred towards other races and are generally peaceful and kind hearted. These tauren does not have horns like the rest of their kin, instead they grow large antlers.

***Ability Score Increase.*** Your Wisdom score <br> increases by 1.

***Mountaineer.*** You're acclimated to high altitude, includ&shy;ing elevations above 20,000 feet. You're also naturally adapted to cold climates, as described in chapter 5 of the *Dungeon Master's Guide*.

***Rugged Tenacity.*** You can use your reaction when you take damage to reduce the damage taken by 1d12 + half your level (rounded up). After you use this trait, you can't use it again until you finish a short or long rest.

#### Taunka
As a taunka, you are considered a relative to the tauren race and a branch of the tauren race that adapted to the harsh environment found in Northrend. These tauren have endured much and don't harbor the same respect for nature as is prominent in other subraces of the tauren race.

***Ability Score Increase.*** Your Constitution score increases by 1.

***Cold Resistance.*** You have resistance to cold damage.

***Natural Athlete.*** You are proficient in the Athletics skill.

***Tundra Walker.*** You can move across difficult terrain made of ice or snow without expending extra movement.

<div class='footnote'>PART 1 | RACES</div>
<img src='https://www.gmbinder.com/images/WxaNruu.png' style='position:absolute; top:945px; right:40px; width:350px' />

\pagebreakNum

<div style='margin-top:340px'></div>

## Troll
*Your ancestry dates back to the dawn of the world. Great were the ancient empires of the trolls. I see a spark in your eyes, a powerful will - you wish to be great again, yes?* 
<div style="text-align:Right"> 

*— Lorewalker Cho* &nbsp;</div>

The jungle trolls are sometimes referred to as Gurubashi trolls, after the ancient empire of the same name. Their capital, Zul'Gurub, is located in Stranglethorn Vale, along with many smaller towns, cities, and villages, many of which are in a state of ruin or disrepair. The largest jungle troll settlement outside Stranglethorn is Sen'jin Village founded by the Darkspear tribe, who had been displaced from their exile on the Broken Isles and Echo Isles.

Forest trolls hold all other races in contempt — especially blood elves, whom they consider the despoilers of their ancient homeland. They will only work with others if it means the elimination of an even more hated enemy. Forest troll culture is tribal and primitive. Though not as violent as their ice troll cousins, forest trolls nonetheless have a fearsome reputation in battle.

Ice trolls are a subspecies of troll that lives in cold climates. They have angular features, bright blue eyes, and mottled blue-white skin covered in hides and pelts. This troll has blue-white skin under grayish leather armor, and he sports a red mohawk. 

Ice trolls are generally evil and like most trolls, they are fierce protectors of their homes and may attack travelers to gain weapons, materials, clothing and food. They practice cannibalism and sometimes eat their slain enemies raw.

### Cannibalists and Voodooism
Cannibalism was a relatively common practice amongst trolls, although through the decades, and with their integration into the horde, their cannibalism had been frowned upon by most, and has since been made a forbidding practice by the horde, some still practice it, but non do so openly.

Not all trolls practice voodoo, but it is widespread. It was given to the trolls by their worshiped gods the Loa, and the exact emergence of voodoo among the trolls is unknown, for most tribes that possess such knowledge are unwilling to share it with outsiders.

<div style='margin-top:-5px;'></div>

\columnbreak

<div style='margin-top:594px'></div>

### Tall and Muscular
Trolls are often tall, lanky, and muscular. They have both elven and orcish characteristics with their fierce fangs and long ears. Their long arms, strong legs and quick reflexes make them adept hunters. 

Trolls have only two fingers and a thumb on their hands, and they have only two toes on each foot. Some trolls have a toenail on their heels, and they do not wear standard shoes or boots due to their unusual foot shape and comfort in wading barefooted within different terrains.

### Affiliation
Trolls are members of the Horde. Although they practice voodoo and often have to retain from their savage nature, they are respected within the Horde, especially by the orcs. They feel a great debt to the horde and their time fighting alongside alongside its members have sprouted new friendships. Most tribes doesn't really hate the Alliance or its members, but their loyalty to the Horde and their blood&shy;thirsty nature makes the Alliance a great target. However, their respect for the Horde's warchief prevents them from waging private wars.

***Jungle Troll.*** These trolls are among those that pledged their allegiance to the Horde when they landed on the isles of the Darkspear tribe. However, many jungle trolls belong to the Gurubashi tribe, a tribe that shows open hostility towards all outsiders.

<div class='footnote'>PART 1 | RACES</div>
<img src='https://www.gmbinder.com/images/uUHrf4n.jpg' style='position:absolute; top:0px; right:0px; width:1000px' />
<img src='https://www.gmbinder.com/images/bNHsRrG.png' style='position:absolute; top:0px; right:0px; width:850px; transform:rotate(180deg)' />
<img src='https://www.gmbinder.com/images/xc8uKId.png' style='position:absolute; top:160px; right:-150px; width:650px; transform:scalex(-1)' />

\pagebreakNum

&nbsp;&nbsp;&nbsp; ***Zandalari Troll.*** These trolls allied with and later joined the Horde during the fourth war as their home on Zandalar was besieged by members of the Alliance.

***Forest Troll.*** These trolls have never pledged their alle&shy;giance to the Horde and although they have been willing to fight alongside it to defeat a common enemy, many forest trolls continue to live in isolation among their own kin.

***Ice Troll.*** These trolls are not part of the Horde, and ice trolls continue to show defiance against the Horde and its cause, preferring to continue their brutal way of life than adjusting to the demands of the Horde.

### Names 
Trolls are not given names at birth, instead a troll have to earn a name within their tribe. A troll's first name usually contains just one syllable, but as they prove themselves again and again, more syllables are added before or after their earned name.

No family or surnames exist within troll culture, although some choose to use their tribes name as a surname, a show of loyalty and pride. Some trolls use their position within a tribe as a surname, like Shadowhunter or Witch Doctor.
<div style='margin-top:-18px;'></div>

<br>**Male Names:** Vol, Ros, Mig, Gal, Traxe, Maaho, Tuben, Ju, <br>&nbsp;&nbsp;&nbsp; Goz, Akash, Vithek, Tian, Vazkono, Rhas, Vog
<br>**Female Names:** Shi, Mith, Hai, So, Ozdun, Imo, Aju, <br>&nbsp;&nbsp;&nbsp; Zhokre, Xullah, Joz, Fahze, Zil, Ruso, Mooh

### Troll Traits
Your troll character has the following racial traits.

***Ability Score Increase.*** Your Constitution score increases by 1.

***Age.*** Trolls mature a little faster than humans, reaching adulthood around age 16. Although they age at the same rate as humans, trolls aren't weakened by old age and can live well over a century.

***Alignment.*** Trolls are a neutral race and their alignment can vary drastically between subraces. Most trolls tend to be lawful, with each tribe often having particular customs and rules for tribesmen to abide by.

***Size.*** Trolls are between 7 and 8 feet tall and weigh between 200 and 300 pounds. Your size is Medium. To set your height and weight randomly, start with rolling the size modifier:
<div style="margin-top: -20px; font-family: ScalySans, sans-serif">

<br>&nbsp;&nbsp;&nbsp; ***Size Modifier:*** 2d10
<br>&nbsp;&nbsp;&nbsp; ***Height:*** 5 feet + 8 inches + your size modifier in inches
<br>&nbsp;&nbsp;&nbsp; ***Weight in Pounds:*** 130 + (2d6 x your size modifier)
</div>

<div style='margin-top:-3px;'></div>

&nbsp;&nbsp;&nbsp; ***Speed.*** Your base walking speed is 30 feet. 

***Darkvision.*** Trolls retain their vision in dark and dim conditions. You can see in dim light within 60 feet of you as if it were bright light, and in darkness as if it were dim light. You can't discern color in darkness, only shades of gray.

***Regeneration.*** Whenever you expend a Hit Die to regain hit points, you regain hit points equal to the number rolled plus  twice your Constitution modifier.

As an action, you can expend a number of Hit Dice up to half your level, as if you have finished a short rest. You must then finish a long rest to use this feature again.

***Languages.*** You can speak, read, and write Common and Zandali. Zandali is the tongue of all trolls. It is a largely syllabic language and taught down through generations.

***Subrace*** Four main subraces of trolls can be found on Azeroth: jungle trolls, zandalari trolls, forest trolls, and ice trolls. Choose one of these subraces.

\columnbreak

#### Jungle Troll
As a jungle troll, you have a knowledge of voodoo and a ferocity that is unmatched by most of your kin. These trolls are superstitious and believe that their way is guided by the spirits of the world. Their fierce determination is matched only by their wits and prowess. Many would consider jungle trolls to be the most dangerous and brutal troll-kin for their influence and power in the Eastern Kingdoms.

***Ability Score Increase.*** Your Constitution score increases by 1, and your Wisdom score increases by 1.

***Berserk.*** You may make one weapon attack or cast a cantrip with a casting time of an action as a bonus action on your turn. You can't use this feature again until you finish a short or long rest.

***Da Voodoo Shuffle.*** You can move across nonmagical difficult terrain without expending extra movement.

***Troll Weapon Training.*** You have proficiency with handaxes, battleaxes, daggers, and javelins.

#### Zandalari Troll
As a zandalari troll, you have an unparalleled connection to the loas and ancient traditions older than most races. They are the ancestral race of all trolls and sit at the center of the troll union in their temple city of Zuldazar on Zandalar. These trolls are more powerful than the rest of their race and carry immense influence and respect among its tribes.

***Ability Score Increase.*** Your Wisdom score <br> increases by 2.

***Ancient Lore.*** You have proficiency in the History skill.

***Embrace of the Loa.*** You know the *guidance* cantrip. When you reach at 3rd level, you can cast the *enhance ability* spell once per day. Wisdom is your spellcasting ability for these spells.

***Zandalar Weapon Training.*** You have proficiency with handaxes, battleaxes, longswords, and greatswords.

#### Forest Troll
As a forest troll, you have a keen knowledge of the natural world, a cunning for warfare, and an ancient hatred of men and elf. These trolls are among those who remain from the Amani Empire, an empire that has fallen by the hands of the Alliance and Horde. 

***Ability Score Increase.*** Your Dexterity score increases by 1, and your Constitution score increases by 1.

***Amani Instincts.*** You gain proficiency with one of the following skills of your choice: Nature, Stealth, or Survival.

***Mask of the Wild.*** You can attempt to hide even when you are only lightly obscured by foliage, heavy rain, falling snow, mist, and other natural phenomena.

***Troll Weapon Training.*** You have proficiency with handaxes, battleaxes, daggers, and javelins.

#### Ice Troll
As an ice troll, you are hardy and strong, accustomed to <br> the cold climates. These trolls are barbaric and brutal, even when compared to other troll-kins. Ice trolls live in harsh conditions where life is dominated by survival, and where the strongest is meant to rule.

***Ability Score Increase.*** Your Strength increases by 2.

***Frostborn Skin.*** You have resistance to cold damage.

***Powerful Build.*** You count as one size larger when determining your carrying capacity and the weight you can push, drag, or lift.

***Troll Weapon Training.*** You have proficiency with handaxes, battleaxes, daggers, and javelins.

<div class='footnote'>PART 1 | RACES</div>

\pagebreakNum

<div style='margin-top:425px'></div>

## Blood Elf
*We must put this misery behind us. We must enter a new chapter! And so I say to you that, as of this day, we are no longer high elves! In honor of the sacrifices of our brothers and sisters, our parents, and our children, as of this day we will take the name of our royal lineage! As of this day, we are sin'dorei! For Quel'Thalas!*

<div style="text-align:Right"> 

*— Kael'thas Sunstrider* &nbsp;</div>
<div style='margin-top:-5px'></div>

Nourished and strengthened by the Sunwell’s potent energies, the high elves’ enchanted kingdom of Quel'Thalas prospered within the verdant forests north of Lordaeron. 

During the Third War, the high elves were nearly scoured from Azeroth. Led by the death knight Arthas, the scourge army slaughtered almost all of the kingdom’s population. In the slaughter, Arthas tainted the sunwell, reanimating a lost necromancer. Prince Kael'thas rushed to his homeland's aid, and the survivors of the onslaught were renamed 'blood elves' in honor of their fallen kin. The blood elves grew addicted to the sunwells tainted energies. Kael'thas desperately searching for a cure for his kin, traveling the world to avenge his people and find a way to sate their hunger for magic.

Kael'thas assured his people he would return to Quel'Thalas and lead them to paradise, yet on Outland, the prince became twisted with the corrupting essence wielded by the demonic Burning Legion. Getting under the sway of the Legion's commander. The prince was later killed on his return to Quel'Thalas for his treachery, and with the aid of the draenei prophet, Velen, the magic taint lingering on the sunwell was vanquished, restore it as a fount of both arcane and holy energy.

Inspired by the Sunwell's rebirth, the blood elves have since entered into a shining new era in their ancient race's history. Although some elves remain hesitant to abandon their dependence on arcane magic, others have embraced change for the betterment of Quel'Thalas. 

\columnbreak

<div style='margin-top:664px'></div>

### A Crimson Appearance
As a culture, the sin'dorei have retained the look and feel of their fallen high elven kingdom, though have developed a greater penchant for the colour of crimson: the colour of their namesake. Crimson-red robes, decor and armour have become far more commonplace within blood elven society prior to the fall of the high elven people, a reference to the blood of their many brethren who had perished in the Third War. The iconic and traditional blood elven colours are red, gold, and to a lesser extent, blue – all of which can be seen on their racial crest, the Icon of Blood.

### Proud Society
In general, the blood elves are a proud, pragmatic, and somewhat jingoistic people; they place great emphasis on their love for their homeland, and are ruthless to their enemies. Their reputation for isolationism is well-earned, and they prefer to keep to their own kind, although excep-tions to this stereotype exist. Blood elves are a resilient race of survivors, and their most prominent figures stand as beacons of courage, tenacity, and the strength to fight on, regardless of what foes stand in their way.

<div class='footnote'>PART 1 | RACES</div>
<img src='https://www.gmbinder.com/images/yEfh2ws.jpg' style='position:absolute; top:0px; right:0px; width:850px' />
<img src='https://www.gmbinder.com/images/bNHsRrG.png' style='position:absolute; top:100px; right:0px; width:800px; transform:rotate(180deg)' />
<img src='https://www.gmbinder.com/images/YsQdgdF.png' style='position:absolute; top:0px; right:-50px; width:500px; transform:scalex(-1)' />

\pagebreakNum

### Beautiful and Graceful
Blood elves are both biologically and physically high elves, with the largest difference being the blood elves emerald glowing eyes, compared to the high elves blue glow. They are slenderly built, with an average height of 6 feet tall and a weight averaging at 150 pounds. They have long pointy ears, high cheekbones, and are generally considered to be highly attractive humans. Blood elves tend towards lighter colorations, with hair of blond or light brown. Both males and females often grow their hair long. Male blood elves ability to grow facial hair is limited, resulting in very few blood elves having beards beyond an inch.

### Affiliation
Blood elves are—for the most part—members of the Horde. Even though the elven race could be split into those that consider themselves blood elves and those that consider themselves high elves, the vast majority of these elves have pledged their allegiance to the Horde and chosen to honor their fallen by renaming themselves the sin'dorei.

Although blood elves have no hate towards the Alliance as a whole, the atrocities dealt to their kin by xenophobic humans have harbored a deep distrust of the Alliance and its human leaders.

***Blood Elf.*** These elves have pledged their allegiance to the Horde, having been convinced by the former Ranger General Sylvanas Windrunner and with her speaking on their behalf to the leaders of its cause.

***High Elf.*** These elves never pledged their allegiance to either faction, and even though they've worked alongside the Alliance in the past, they never trusted it enough to leave behind their isolated comfort and join its cause. The high elves have no love for the Horde and see blood elves as traitors, tainted by fel.

### Blood Elf Names
Most blood elves who survived the Third Ward have chosen to retain their high elven names. As such most blood elves continue to be given high elven names as birth, born into proud families with names of their own to carry forward. These elves share a connection with the sun that is quite prevalent in their choice of family names, with blood elven family names often being more aggreesive than those taken by most high elves.
<div style='margin-top:-18px;'></div>

<br>**Male Names:** Mariel, Athaniar, Anador, Tharama, Viridiel, <br>&nbsp;&nbsp;&nbsp; Malanior, Eraeth, Ulorath, Yehru, Kithadre
<br>**Female Names:** Anarial, Freja, Driana, Coria, Alanassori, <br>&nbsp;&nbsp;&nbsp; Melanion, Azshara, Curlih, Setori, Amorly, Zama
<br>**Family Names:** Coldtrail, Nightfeast, Darkgift, Glowvein, <br>&nbsp;&nbsp;&nbsp; Warmblood, Dawntrick, Solarmind, Phoenixdreamer

\columnbreak

### Blood Elf Traits
Your blood elf character has the following racial traits.

***Ability Score Increase.*** Your Dexterity score increases by 2, and your Intelligence score increases by 1.

***Age.*** Blood elves reach adulthood at the rate of humans, but aren't considered to have entered adulthood until they reach age 60, and can live to become many hundred years old with ease. That being said, many blood elves have lived for thousands of years due to the power of the Sunwell extending their lifespan indefinitely.

***Alignment.*** Blood elves live in a society where ranks and titles carry tremendous weight and where strict laws have been put in place for them to follow, pushing them towards lawful alignments. Personal desires varies drastically, and both those of good and evil alignment exist.

***Size.*** Blood elves are between 5 and 6 feet tall and weigh between 125 and 175 pounds. Your size is Medium. To set your height and weight randomly, start with rolling the size modifier:
<div style="margin-top: -20px; font-family: ScalySans, sans-serif">

<br>&nbsp;&nbsp;&nbsp; ***Size Modifier:*** 2d10
<br>&nbsp;&nbsp;&nbsp; ***Height:*** 4 feet + 9 inches + your size modifier in inches
<br>&nbsp;&nbsp;&nbsp; ***Weight in Pounds:*** 100 + (2d4 x your size modifier)
</div>

<div style='margin-top:-3px;'></div>

&nbsp;&nbsp;&nbsp; ***Speed.*** Your base walking speed is 30 feet.

***Darkvision.*** Due to your elven heritage, you have superior vision in dark and dim conditions. You can see in dim light within 60 feet of you as if it were bright light, and in darkness as if it were dim light. You can’t discern color in darkness, only shades of gray.

***Arcane Knowledge.*** You are proficient in the Arcana skill, and you can cast *detect magic* with this trait, using Intelligence as your spellcasting ability for it. Once you cast detect magic, you can't cast it again until you finish a short or long rest.

***Keen Senses.*** You are proficient in the Perception skill.

***Spell Turning.*** When you fail a saving throw against a spell or spell-like effect, you can reroll the die and must use the new roll. You can't use this feature again until you finish a short or long rest.

***Thalassian Legacy.*** You gain one of the following features of your choice:
<div style='margin-top:-5px;'></div>

- You know one cantrip of your choice from the mage spell list. Intelligence is your spellcasting ability for it.
- You have proficiency with the twinblade, warglaive, shortbow, and longbow.
<div style='margin-top:-5px;'></div>

&nbsp;&nbsp;&nbsp; ***Languages.*** You can speak, read, and write Common and Thalassian. Thalassian derives from the Darnassian tongue of night elves, and in many cases sound the same to an inexperienced ear.

> ##### Creating a High Elf
> Few high elves remain on Azeroth, as the quel'dorei renamed themselves sin'dorei, blood elves, upon retaking much of their homeland from the Scourge. You can create a high elf by using the racial traits of a blood elf, as the two races are indistinguishable.

<img src='https://www.gmbinder.com/images/vDsOBWh.jpg' style='position:absolute; top:720px; right:0px; width:800px' />
<img src='https://www.gmbinder.com/images/qV5FBIk.png' style='position:absolute; top:-50px; right:-0px; width:800px; transform:scaley(-1)' />

\pagebreak

---

\columnbreak

## Goblin
*I never cover up the things I'm proud of. If the world was gonna split in half tomorrow, I’d buy the Dark Portal, slap a toll booth on it, and charge refugees the last of their pocket change, the rings off their fingers, a bite of their meal, and a contractual obligation to build me a rocket palace in the skies of Nagrand. It’s the goblin way! Supply and demand! Deal with it!*
<div style="text-align:Right"> 

*— Trade Prince Jastor Gallywix* &nbsp;</div>
<div style='margin-top:-5px'></div>

Slaves of the jungle trolls on their home isle, forced to mine kaja'mite ore out of the volcanic bowels of Mount Kajaro. The ore had an unexpected effect on the goblins, granting them cunning intelligence. They began to rebel in secret, engineering artifacts, and brewing alchemical substances to successfully overthrow their oppressors and claim Kezan their homeland.

<span style="margin-left:10px"></span> Their prior prison become an expanding empire in the
<span style="margin-left:30px"></span> mines they had dugged. To their dismay, the effects of 
<span style="margin-left:35px"></span> the kaja'mite ore wore off, and their increased intelli-
<span style="margin-left:35px"></span> gence waned, as the ore itself became scarce and 
<span style="margin-left:34px"></span> dwindled. Their brilliant engineering dwindled in 
<span style="margin-left:30px"></span> ingenuity, looking haphazardly put together. Their 
<span style="margin-left:27px"></span> remaining craftiness and greed soon took its place, 
<span style="margin-left:23px"></span> lifting the race to preeminence as masters of mercan-
<span style="margin-left:20px"></span> tilism. Great fortunes were amassed, and the isle
<br><span style="margin-left:15px"></span> became a hub for goblin traders.

### Technology
Goblins love of mechanics often places them into direct competition with gnomes who enjoy similar devices. The competition between goblins and gnomes seems to be friendly. Whether clockwork shredders that allow a single goblin to do as much harvesting as 10 field hands or zeppelin-like airships that can ferry troops over otherwise impassable terrain, the goblins' inventions have become legendary. Such technological ingenuity is as central to the goblins' rise among the races as any trading prowess.

Even with the malfunctions and explosions that occur, goblin technology is proving to be of a quality that rivals the dwarves and their firearms. While other races often try to build reliable machines that would stay for grandchildren, goblin aims for device of the marginally bearable reliability that should only last enough to make its construction reasonable. Weird as it is, this approach allows to build more machines, or to build a more complex and powerful machine using the same time and resources.

### Born Traders
Goblins have taken to the role of merchants, and it's hard to travel for more than a week or two without stumbling across a goblin shop of some size. Goblin shops can be found nearly anywhere on Azeroth, seemingly regardless of whether or not there are towns nearby and heedless of dangers such as the Scourge. The goblins will sell anything to anyone, at only slightly inflated prices.

Though many shops remain independent, a growing number of them have signs declaring that they are owned and operated by the Venture Company, which the proprietors claim is headquartered in a faraway city ruled by goblins where the streets are paved with gold.

The goblins are also legendary for the sheer variety of trade in which they are willing to indulge and for their tenacity in bargaining. 

<div class='footnote'>PART 1 | RACES</div>
<img src='https://www.gmbinder.com/images/grtcWyc.jpg' style='position:absolute; top:00px; right:100px; width:1995px' />
<img src='https://www.gmbinder.com/images/Npi5n8k.png' style='position:absolute; top:0px; right:-20px; width:900px' />
<img src='https://www.gmbinder.com/images/tdgTze8.png' style='position:absolute; top:440px; right:352px; width:450px; transform:scalex(-1)' />

\pagebreakNum

### Small But Standing Tall
Goblins are slight and wiry, averaging just under 4 feet in height and an average weight of 50 pounds, with female goblins being slightly taller than males. Their green skin is reminiscent to the orcs, although goblins skin can tan in the sun to create rich and dull shades of green. Longside their large ears, goblin noses continue to grow throughout their life and can reach multiple inches.

### Affiliation
Goblins are members of the Horde. Even though goblins worked and traded with members of the Horde, it wasn't until the Cataclysm that the Bilgewater Cartel pledged their allegiance to the growing Horde. Although many goblins have allied themselves with the Horde, some continue to tread on neutral ground, trading with members of both factions who are willing to buy.

Few goblins openly show a hate or distrust for the other members of the Horde, enjoying the security and profitable positions they have earned within its ranks.

#### Goblins and Gnomes
Goblins bear a grudge towards gnomes, seeing them not as an enemy, but a rival. It has driven goblins into friendly and brutal contests with gnomes to determine which of the two races are superior.

### Names
Goblins are named at birth and keep their given name until they die. Although, some goblins take on nicknames fitting of their personality and put them before thier given name, like 'Haughty Modiste'. 

Goblins have large elaborate families with names <br>that depict some ancestor's achievements. A goblin whose own achievements out&shy;strip that of their forebears often replace their old family name with a new one depicting their own achievements.
<div style='margin-top:-18px;'></div>

<br>**Male Names:** Nees, Ford, Joxdeld, Zatval, Fivinkle, Bova, <br>&nbsp;&nbsp;&nbsp; Geevegbix, Rolaz, Ixa, Saz, Menzen, Gilmaxle
<br>**Female Names:** Trutte, Meez, Kleqe, Suva, Tweedo, <br>&nbsp;&nbsp;&nbsp; Cynmee, Twinkle, Klasi, Teexma, Ninzi
<br>**Family Names:** Brokenblast, Shifttale, Saltsnipe, <br>&nbsp;&nbsp;&nbsp; Deadknob, Nifttweak, Cogbeast, Slyfire, Manbelt

### Goblin Traits
Your goblin character has the following racial traits.

***Ability Score Increase.*** Your Intelligence score increases by 1, and your Charisma score increases by 2.

***Age.*** Goblins mature slightly slower than humans and reach adulthood in their early 20s. Most goblins die within a century, but a goblin can live into the middle of his or her second century.

***Alignment.*** Most goblins lean towards chaotic neutral. They rarely show a sense of moral or consideration for the consequences of their actions, preferring to live in the moment and leave the troubles to tomorrow.

***Size.*** Goblins are between 3 and 4 feet and weigh between 40 and 80 pounds. Your size is Small. To set your height and weight randomly, start with rolling the size modifier:
<div style="margin-top: -20px; font-family: ScalySans, sans-serif">

<br>&nbsp;&nbsp;&nbsp; ***Size Modifier:*** 2d4
<br>&nbsp;&nbsp;&nbsp; ***Height:*** 2 feet + 12 inches + your size modifier in inches
<br>&nbsp;&nbsp;&nbsp; ***Weight in Pounds:*** 40 + (1 x your size modifier)
</div>

&nbsp;&nbsp;&nbsp; ***Speed.*** Your base walking speed is 25 feet.

***Best Deals Anywhere.*** Whenever you make a Charisma (Persuasion) check related to haggling, you are considered proficient in the Persuasion skill and add double your proficiency bonus to the check, instead of your normal proficiency bonus.

***DODGE.*** You may give yourself advantage on a Dexterity saving throw against an effect that you can see, such as a trap or a spell. You can choose to do so before or after the roll, but before any effects of the roll are applied. You can't use this feature again until you finish a short or long rest.

***Goblin Engineering.*** You have proficiency with the artisan's tools (tinker's tools). Using those tools, you can spend 1 hour and 25 gp worth of materials to construct a Tiny device (AC 5, 1 HP). The device ceases to function after 24 hours (unless you spend 1 hour maintaining it. This can be done as part of a short or long rest), or after it has been activated, at which point the device breaks; at that time, you can reclaim 5 gp worth of materials used to create it. You can only make one device between long rests and can never maintain more than one device at a time.

When you create this device, choose one of the following spells: *burning hands, catapult, earth tremor, feather fall, grease, jump,* and *thunderwave*. A creature can use its Action to activate the device and produce the effects of the chosen spell without providing material components. Each device uses your Intelligence as its spellcasting ability.

***Mechanical Familiarity.*** You are proficient in firearms and the artisan's tools (gunsmith's tools).

***Languages.*** You can speak, read, and write Common, Goblin and one extra language of your choice. Goblins are born merchants and trade with any race willing to buy from them, picking up the languages of those they trade with.

<div class='footnote'>PART 1 | RACES</div>
<img src='https://www.gmbinder.com/images/VaHU2Gc.jpg' style='position:absolute; top:490px; right:-150px; width:600px' />
<img src='https://www.gmbinder.com/images/wvTUmvu.png' style='position:absolute; top:50px; right:0px; width:800px' />
<img src='https://www.gmbinder.com/images/E8GrMME.png' style='position:absolute; top:0px; right:0px; width:900px' />

\pagebreakNum

<style> .phb#p33:after { display:none; } </style>
<div class='cover-header'> <div style='margin-top:50px;'></div> Allied Races </div>
<img src='https://www.gmbinder.com/images/kkjaoG4.jpg' style='position:absolute; top:0px; right:-65px; width:900px' />

\pagebreak

<div style='margin-top:147px;'></div>

## Nightborne
An impenetrable barrier was placed around 
<br> their capital city Suramar, shielding the high- 
<br> borne from the Sundering. This shield would
<br> keep the highborne isolated from the rest of 
<br> Azeroth's new continents for thousands of years. 
<br> Forcing the highbornes to rely on their Nightwell 
<br> for their magical powers. The highbornes evolved 
<br> over the ages, and they called themselves the 
<br> shal'dorei or nightborne.

When Suramar run out of food, the shal'dorei began to utilize the substance of their Nightwell as nourishment and was thus spared an untimely death, however, this soon caused them to be unable to survive without drawing magic from the Nightwell. Crime was punished by exile. Cutting them off from the Nightwell, the exiled would diminish into husks of their former selves, and eventually irreversible into mindless withered, waiting for death.

Ten thousand years later the nightborne lowered their shield and surrender to the Burning Legion by orders from their leader, Grand Magistrix Elisande. Many nightborne did not agree with her decision, but none dared speak against her newfound forces of demons. Through the aid of a nightborne resistance, and the forces of the Alliance and Horde. The Grand Magistrix and her demon allies were pushed back into the Twisting Nether.

### Born in the Darkness
Sealed off within their capital of Suramar, the nightborne physique in many ways resemble that of their night elven kin, with tall slender bodies and muscular builds. The ever darkened sky of their city have changed their skin to be a dark blue or purple, rather than the more vibrant colors of the night elves. The Shal'dorei still practice arcane magic, giving their eyes a dim blue or purple glow, instead of the golden glow of the night elves.

The nightborne are fiercely proud of the arcane ways, and proudly shows off shimmering tattoos of arcane energy that has been placed upon their body. The tattoos have no known impact on the nightborne capabilities, yet it stands as a show of a nightbornes comprehension of the arcane.

### Highborne Civilization
The Shal'dorei have an air of superiority that often comes across as pompous. They revel in their unequalled magical civilization but having no exposure to the current races of Azeroth until the rebellion led an invading force to free Suramar, many still regard outside races and the world as it was back then, full of the unworthy, the uncultured, and low born far beneath the standards and levels of the nightborne civilization.

These were the less admirable qualities of night elven civilization back then, and the shal'dorei continue in them as if nothing has changed and as if they still remain the center of the world.

<div style='margin-top:-5px;'></div>

\columnbreak

<div style='margin-top:650px;'></div>

### Affiliation
Nightborne's have been severed from the rest of the world for thousands of years within their capitol city of Suramar. Derived from the highborne night elves, many nightborne have shown a desire for returning to their ancient kin once the barrier around their capital city was eliminated. How&shy;ever, nightborne also show an affecting towards the blood elves and their similar addiction to a well of power.

Few nightborne have maintained a neutral stance as the Third Invasion of the Burning Legion have pushed them to seek new allies. 

&nbsp;&nbsp;&nbsp; ***Alliance.*** Few nightborne's have chosen to pledge their allegiance to the Alliance, feeling that the organization is too walled off and cloistered for a race that has spent the last ten-thousand years in isolation. The caution and mis&shy;trust voiced by their night elven kin has also pushed many nightborne away from the Alliance.

***Horde.*** Many nightborne have been able to find common ground with the blood elves of the Horde, who've expressed a similar relationship with the night elves, and are bound by a similar addiction to a well of power. The blood elves have showed themselves to be a great ally of the nightborne people and opened the door for them to join the Horde.

<div class='footnote'>PART 1 | RACES</div>
<img src='https://www.gmbinder.com/images/Lru8laS.jpg' style='position:absolute; top:0px; right:-100px; width:1050px; transform:scalex(-1)' />
<img src='https://www.gmbinder.com/images/eHNEyoC.png' style='position:absolute; top:0px; right:0px; width:900px' />
<img src='https://www.gmbinder.com/images/3JjxENt.png' style='position:absolute; top:-40px; right:-30px; width:500px' />

\pagebreakNum

### Nightborne Names
Nightborne names resemble those of night elves and often carry a hidden meaning. Few nightbornes keep track of family names and surnames are derived from feats done by the nightborne's ancestors, it is rare for a nightborne to take a new surname as many take pride in their forefeather's achievements.

**Male Names:** Absolon, Astoril, Oculeth, Lespin, Silgryn, <br>&nbsp;&nbsp;&nbsp; Almon, Ailen, Vanthir, Sylverin, Rosaine
<br>**Female Names:** Valtrois, Iadreth, Anastae, Ly'leth, Theryn, <br>&nbsp;&nbsp;&nbsp; Ambrena, Anaryys, Naran, Ke'lorin, Arluelle, Noressa
<br>**Surnames Names:** Luneastre, Astravar, Swiftmeadow, <br>&nbsp;&nbsp;&nbsp; Moonblade, Silverleaf

### Nightborne Traits
Your nightborne character has the following racial traits.

***Ability Score Increase.*** Your Dexterity score increases by 1, and your Intelligence score increases by 2.

***Age.*** Nightborne reach physical maturity at the pace of humans, but the nightborne understanding of adulthood goes beyond physical growth. Nightbornes typically claim adulthood and an adult name around the age of 100, and can live to become thousands of years old. 

***Alignment.*** Order and structure are key to nightborne societies, they believe that reputation and status are of the utmost concern and that mortality and principles of right and wrong are viewed too often in that light. Most night&shy;borne are lawful.

***Size.*** Nightborne are between 7 and 8 feet tall and weigh between 180 and 220 pounds. Your size is Medium. To set your height and weight randomly, start with rolling the size modifier:
<div style="margin-top: -20px; font-family: ScalySans, sans-serif">

<br>&nbsp;&nbsp;&nbsp; ***Size Modifier:*** 2d8
<br>&nbsp;&nbsp;&nbsp; ***Height:*** 6 feet + 8 inches + your size modifier in inches
<br>&nbsp;&nbsp;&nbsp; ***Weight in Pounds:*** 130 + (2d6 x your size modifier)
</div>

<div style='margin-top:-3px;'></div>

&nbsp;&nbsp;&nbsp; ***Speed.*** Your base walking speed is 30 feet.

***Superior Darkvision.*** Accustomed to twilit forests <br> and the night sky, you have superior vision in dark and dim conditions. You can see in dim light within 120 feet of you as if it were bright light, and in darkness as if it were dim light. Your nightborne heritage makes your darkvision un&shy;usual: everything you see in darkness is in a shade of violet.

***Sunlight Sensitivity.*** You have disadvantage on attack rolls and on Wisdom (Perception) checks that rely on sight when you, the target of your attack, or whatever you are trying to perceive is in direct sunlight.

***Arcane Knowledge.*** You are proficient in <br> the Arcana skill.

***Keen Senses.*** You are proficient in the Perception skill.

***Mental Warding.*** You have advantage on all Intelligence, Wisdom, and Charisma saving throws against magic.

***Nightborne Magic.*** You know the *mage hand* cantrip. When you reach 3rd level, you can cast the *detect magic* spell once per day. When you reach 5th level, you can also cast the *blur* spell once per day. Intelligence is your spell&shy;casting ability for these spells.

***Languages.*** You can speak, read, and write Common and Shalassian. Shalassian, like Thalassian, originates from the Darnassian language. Its dialect has been scrutinized through the ages, making it nearly impossible for members outside of the Nightborne to read or write.

<div class='footnote'>PART 1 | RACES</div>
<img src='https://www.gmbinder.com/images/UWr8pFE.jpg' style='position:absolute; top:0px; right:-400px; width:1910px' />
<img src='https://www.gmbinder.com/images/E8GrMME.png' style='position:absolute; top:0px; right:0px; width:900px' />

\pagebreakNum

<div style='margin-top:400px;'></div>

## Pandaren
The pandaren have long 
<br> been a mystery to other races 
<br> of Azeroth, their history stretch-
<br> ing back thousands of years, to 
<br> before the raise of the kaldorei. 
<br> Denizens of a wondrous and fertile 
<br> land, the pandaren were slaves to the 
<br> ancient titan-forged mogu. Through 
<br> tenacity, diplomacy, and a unique 
<br> form of unarmed combat, they 
<br> staged a successful revolution that 
<br> deposed the mogu, and established the foundation of the pandaren empire that prospered for thousands of years.

As the sundering took place, Pandaria was shrouded in a magical mist that would last for thousand of years. As the years came to an end, the mist around Pandaria unveiled. Drawing the attention of both factions, wishing to claim this 'unexplored' land, and learn of what lied on its surface.

### Harmony in All Things
Pandarens are slow to anger and prefer to take measures solutions to problems. On Pandaria, negative emotions are harnessed and take physical form to wreak havoc on the isle. They emphasize and cultivate a quiet life of inner harmony and focus. Conflicts, no matter how bitter, are quickly forgotten over cold drinks once the matter at hand has been resolved.

### A Spiritual Race
Pandaren have a fierce and deep belief in the connection of the material and spiritual world. They are a society that reacts, rather than being the ones to act first. Many claim to be the water that flows around a rock -- it never pushes the rocks out of its way, but merely goes around it. This stands as the core of their society, a simple means of everyday life. If they set their mind to a task and fail, then they believe they went about it the wrong way, and try again.

\columnbreak

<div style='margin-top:758px;'></div>

### Covered in Fur
Covered in colorful fur from head to toe, pandaren appear like massive humanoid bears towering above the heads of most of Azeroth's inhabitants. They stand far over the head of humans, ranging from just under 6 feet to a few inches short of 7 feet. Pandarens are naturally curvy, only made larger in size by their thick fur, weighing between 250 to 400 pounds. Males stand slightly taller than females, and males are often much heavier than females.

Pandaren colorations varies widely, from a dark brown to a golden yellow, one thing that is consistent throughout all pandarens are their white markings, all pandarens have these upon their face, and many also have patches of white on their paws of torso. Pandarens don't have hair, but many stylize their fur on top of their head, letting it grow longer to resemble hair.

<img src='https://www.gmbinder.com/images/6XAsG6F.jpg' style='position:absolute; top:0px; right:0px; width:800px' />
<img src='https://www.gmbinder.com/images/kDzvP48.png' style='position:absolute; top:-170px; right:0px; width:1000px' />
<img src='https://www.gmbinder.com/images/6aiPMLT.png' style='position:absolute; top:75px; right:-180px; width:750px; transform:scalex(-1); z-index:10' />
<div class='footnote'>PART 1 | RACES</div>

\pagebreakNum

### Affiliation
Pandarens are an independent race that have been hidden from the world since the days of the War of the Ancients. Their homeland of Pandaria lies far beyond the borders of the Horde and Alliance, and most pandarens have taken a neutral stance on the factions and their causes. However, some among the pandaren have pledged their allegiance to one of the factions, pledging their allegiance to the faction whose ideals and beliefs align with the pandaren.

The world and people of Azeroth is new to the pandaren  and few among the harmonious race show distrust, anger, or hate towards its other races. No matter their faction.

***Alliance.*** These pandaren are commonly known as tus&shy;hui pandaren, pandarens whose teachings encourage living a venerable life through meditation, rigorous training, and moral conviction. Pandaren who upheld the tenets of Tus&shy;hui are drawn to the Alliance and their similar philosophy.

***Horde.*** These pandaren are commonly known as houjin pandaren, pandarens who firmly believe that injustice must be met with a swift and decisive response, though this response should be flexible and calculated for the situation at hand; to the Huojin, the end will always ultimately justify the means. Pandaren who upload the tenets of Houjin are drawn to the scrappy practicality of the Horde.

### Names
Pandaren naming practices are similar to those of humans, each pandaren are given a name at birth, and carries on the family name of their parents. Some pandaren are known to take a new family name reflecting their own achievements in life, yet such practices are uncommon.
<div style='margin-top:-18px;'></div>

<br> **Male Names:** Fan Su, Tan Delan, Tian Fu, Fan-Su, Zi Ling, <br>&nbsp;&nbsp;&nbsp; Gao, Bai, Wei He, Xun Ming, Dong-Gun
<br> **Female Names:** Sujin, Zemin, Seul-Gi, Heng Lei, Sun-Mi, <br>&nbsp;&nbsp;&nbsp; Zheng, Yan, Wei Zhelan, Xuefeng, Li, Liuxian
<br> **Family Names:** Caskriver, Drumfriends, Wisespear, Keen- <br>&nbsp;&nbsp;&nbsp; walker, Calmbrow, Mellowcoil, Ironshadow, Wildfur

\columnbreak

### Pandaren Traits
Your pandaren character has the following racial traits.

***Ability Score Increase.*** Your Constitution score increases by 1, and your Wisdom score increases by 2.

***Age.*** Pandarne age at the same rate as humans, reaching adulthood in their late teens, and  generally die before they reach their first century.

***Alignment.*** Pandaren are a peaceful and sociable race that for the most parts tend to their own, making most pandarens neutral or good aligned. Pandarens are rare of an evil alignment and finding an evil pandaren is often the product of foul magic influencing its mind.

***Size.*** Pandaren are between 5 and 7 feet tall and weigh between 250 and 400 pounds. Your size is Medium. To set your height and weight randomly, start with rolling the size modifier:
<div style="margin-top: -20px; font-family: ScalySans, sans-serif">

<br>&nbsp;&nbsp;&nbsp; ***Size Modifier:*** 2d10
<br>&nbsp;&nbsp;&nbsp; ***Height:*** 5 feet + 2 inches + your size modifier in inches
<br>&nbsp;&nbsp;&nbsp; ***Weight in Pounds:*** 150 + (2d6 x your size modifier)
</div>

<div style='margin-top:-3px;'></div>

&nbsp;&nbsp;&nbsp; ***Speed.*** Your base walking speed is 30 feet.

***Gourmand.*** You gain proficiency with the artisan's tools (cook's utensils) and artisan's tools (brewer's supplies).

***Inner Peace.*** You have advantage on saving throws against being charmed or frightened.

***Martial Adept.*** Fighting to protect home and family, your unarmed attacks deal 1d4 + your Strength modifier bludge&shy;oning damage on a hit. In addition, you gain a +1 bonus to your Armor Class. To use this bonus, you can't be wearing medium or heavy armor, or wield a shield.

***Quaking Palm.*** You are able to target focal points on a target. As a bonus action, you can make a special unarmed attack. If the attack hits, it deals its normal damage and the target must succeed on a Constitution saving throw (DC 8 + your Wisdom modifier + your proficiency bonus). The target is stunned until the end of your next turn on a failed saving throw.

After you use your quaking palm, you can't use it again until you finish a short or long rest.

***Languages.*** You can speak, read, and write Common and Pandaren. Pandaren is the language of Pandaria, a descendant of the Mogu language forced upon the inhabitants of Pandaria by the mogu empire. It is a strange and unfamiliar language to the rest of Azeroth, with a multitude of words meaning one common thing.

<img src='https://www.gmbinder.com/images/SvYw20C.jpg' style='position:absolute; top:700px; right:0px; width:800px' />
<img src='https://www.gmbinder.com/images/L60ii4e.png' style='position:absolute; top:0px; right:0px; width:850px; transform:scalex(-1)' />
<div class='footnote footnote-white'>PART 1 | RACES</div>

\pagebreakNum

<div style='margin-top:121px;'></div>

## Void Elf
Infused by the void itself, the Ren'dorei--children of the void--are a group of blood elves exiled from their homeland of Quel'Thalas. Cast out for their teachings at the hand of the elven magister Umbric, the elves have embraced their newfound powers, though the inner turmoil it has caused may well follow them through their lives as they fight to maintain control over it.

### Shaped by the Void
While they are of the same blood as their elven siblings, void elves are best recognized for their pale or vibrant, blue-tinged skin and eyes. As well as the deep shades of blue and purple in their shadow-infused hair. For some void elves, their dark powers can be seen manifesting in their hair, leaving the tips shimmering with void energy.

Most who have tried to harness the corruptive powers of the void have fallen into madness. Among mortals, former ranger-general Alleria Windrunner stands as the first to properly wield it -- the elf now using her powers to guide her elven kin alongside the magister Umbric. The void elves aim, above all, to use their dangerous powers to defend both the Alliance and Azeroth itself. In doing so, they seek to prove wrong any who would doubt or judge their abilities.

### Exiled From Home
Originally, the void elves were the pupils and followers of Umbric -- a magister at the court of Silvermoon, who thought the void to be the key to the survival of Quel'Thalas after its destruction at the hands of the undead Scourge.

However, the other magisters did not agree. Least of all the Grand Magister, who ultimately banished the elves from the land under fear that the void would pose great dangers to the kingdom and to the Sunwell. 

Now, emboldened by their newfound powers, the void elves have sworn to make their claim on the world, under the joint leadership of magister Umbric and Alleria Windrunner. 

### Ethereals, Friend and Foe
Beings of energy, Ethereals are extradimensional creatures that have travelled great distances across the Great Dark. Normally composed of arcane energies, it is a group of void-touched Ethereals that have turned the Ren'dorei into what they are today. Alleria Windrunner, co-leader to Magister Umbric, owed much of her power to the teachings of an Ethereal named Locus-Walker.

It was only thanks to the machinations of void ethereals hoping to turn Magister Umbric and his followers into true creatures of void along with the timely intervention of Alleria Windrunner that has turned these former denizens of Quel'thalas into something more. Now Locus-Walker along with other ethereals who's goals aligned with the Ren'dorei roam their base of Telogrus Rift, teaching and guiding all Children of Quel'thalas in the ways of the Void.

<div style='margin-top:-5px;'></div>

\columnbreak

<div style='margin-top:650px;'></div>

### Affiliation
Void elves are an independent subrace of blood elves that have been exiled from Quel'Thalas for their meddling with the void. The elves choose to embrace or try to forget their status as outcasts, for they will forever be unwelcome in the land they've left behind.

***Alliance.*** These elves have learned to control the void following the guidance of the ranger-general Alleria Wind&shy;runner and have sworn their service to her. With her as their leader, they pledged their allegiance to the Alliance after the Burning Legion's defeat on Argus.

***Horde.*** No void elves exist within the Horde, as those that learned to control the void swore to follow the ranger-general Alleria Windrunner and have joined the Alliance.

> ##### Emergence of the Void Elves
> The Ren'dorei are specific group of void elves that followed the teachings of magister Umbric, though he is not the first elf to have dabbled with the void. Talk with your DM if you want to play as a void elf before the Burning Legion's defeat on Argus.


<div class='footnote'>PART 1 | RACES</div>
<img src='https://www.gmbinder.com/images/JLhq6RD.jpg' style='position:absolute; top:-100px; right:0px; width:800px' />
<img src='https://www.gmbinder.com/images/H47MOpD.png' style='position:absolute; top:0px; right:0px; width:900px' />
<img src='https://www.gmbinder.com/images/kDzvP48.png' style='position:absolute; top:-80px; right:0px; width:1000px' />
<img src='https://www.gmbinder.com/images/hTLvvHS.png' style='position:absolute; top:-20px; right:-200px; width:800px' />

\pagebreakNum

### Names
Void elves continue to follow the naming conventions of blood elves and little discrepancy exists between the two. However, with their exile from Quel'Thalas, some void elves have chosen to change their family name for one that embraces their new powers.
<div style='margin-top:-18px;'></div>

<br>**Family Names:** Coldtrail, Nightfeast, Voidworn, Morn- <br>&nbsp;&nbsp;&nbsp; cloud, Duskblood, Darkvein, Gloomwalker, Voidheart

### Void Elf Traits
Your void elf character has the following racial traits.

***Ability Score Increase.*** Your Dexterity score increases by 2, and your Intelligence or Charisma score (your choice) increases by 1.

***Age.*** Void elves reach adulthood at the rate of humans, but aren't considered to have entered adulthood until they reach age 60, and can live to become many hundred years old with ease. That being said, many void elves have lived for thousands of years due to the power of the Sunwell extending their lifespan indefinitely.

***Alignment.*** Although chaos and unpredictability is pro&shy;minent in many void elves, they have maintained a lawful alignment similar to blood elves. Those that succumb to the void often turn chaotic in their alignment.

***Size.*** Void elves are between 5 and 6 feet tall and weigh between 125 and 175 pounds. Your size is Medium. To set your height and weight randomly, start with rolling the size modifier:
<div style="margin-top: -20px; font-family: ScalySans, sans-serif">

<br>&nbsp;&nbsp;&nbsp; ***Size Modifier:*** 2d10
<br>&nbsp;&nbsp;&nbsp; ***Height:*** 4 feet + 9 inches + your size modifier in inches
<br>&nbsp;&nbsp;&nbsp; ***Weight in Pounds:*** 100 + (2d4 x your size modifier)
</div>

<div style='margin-top:-3px;'></div>

&nbsp;&nbsp;&nbsp; ***Speed.*** Your base walking speed is 30 feet.

***Darkvision.*** Due to your elven heritage, you have superior vision in dark and dim conditions. You can see in dim light within 60 feet of you as if it were bright light, and in darkness as if it were dim light. You can’t discern color in darkness, only shades of gray.

***Keen Senses.*** You are proficient in the Perception skill.

***Chill of Night.*** You have resistance to Necrotic damage.

***Spatial Rift.*** As a bonus action, you open a rift in space and time and magically teleport up to 30 feet to an unoccupied space you can see. Once you use this trait, you can't do so again until you finish a short or long rest.

***Thalassian Legacy.*** You gain one of the following features of your choice:
<div style='margin-top:-5px;'></div>

- You know one cantrip of your choice from the mage spell list. Intelligence is your spellcasting ability for it.
- You have proficiency with the twinblade, warglaive, shortbow, and longbow.
<div style='margin-top:-5px;'></div>

&nbsp;&nbsp;&nbsp; ***Languages.*** You can speak, read, and write Common and Thalassian. Thalassian derives from the Darnassian tongue of night elves, and in many cases sound the same to an inexperienced ear.

\columnbreak

<div style='margin-top:500px;'></div>

## Vulpera
The vulpera have lived in Vol'dun as free traders and mer&shy;chants for countless generations. For much of that time, they have been oppressed by the Faithless sethrak, who have enslaved countless vulpera over the years and forced them to work and fight for them. The vulpera are mostly a passive people and as such never found the ability to stop the sethrak. At least one caravan tried to fight back, but they met only with defeat.

### Scavengers and Survivors
The vulpera are a keen and intelligent race of nomadic scavengers. They are capable of turning what they find into opportunities to thrive and are skilled at solving problems, no matter their size. Despite their small stature, vulpera are fierce and cunning in battle, bringing down any enemy foolish enough to underestimate them. While they have permanent settlements in burrows, their caravans mostly travel from hideaway to hideaway, scavenging for supplies, trading them where they can, and spreading information they pick up along the way. Their scavenging often takes the form of looting artifacts and treasure from ancient ruins and selling them to the highest bidder.

### Resourceful Gatherers
Dwelling in Vol'dun, the vulpera can't afford to waste re&shy;sources. Over time, they have learned to take anything that looks even remotely useful and be creative using what they have, and they have learned to recognize value wherever it hides in the desert. When warned that gold from the Port of Zem'lan was cursed, Norah replied that "A little curse never kept the vulpera from a worthy treasure".

<div class='footnote'>PART 1 | RACES</div>
<img src='https://www.gmbinder.com/images/qX8jehA.png' style='position:absolute; top:-40px; right:-120px; width:550px; transform:scalex(-1)' />

\pagebreakNum

### Affiliation
Vulpera are an independent race native to the warm desert of Vul'dun. Although some among the race continue a free nomadic lifestyle, many vulpera have chosen to joined the larger factions of Azeroth and shown a desire to explore the world found beyond Vol'dun's warm climate.

***Alliance.*** No vulpera exist within the Alliance, although the race has no hatred towards its members, many vulpera have followed the caravan leader Kiro and pledged their allegiance to the Horde.

***Horde.*** These vulpera have felt the harshness of Vol'dun and its inhabitants, indebted and grateful to the Horde for its aid they followed the caravan leader Kiro and joined the Horde to return a favor, and explore the world beyond.

### Names
Vulpera are given a name shortly after birth by the nomadic caravan they travel with, rather than their parents. Those a vulpera travel with are considered family and no voice rings louder than others. Vulperan names are short, made up of two or three syllables at most. They do not keep family or surnames, and few choose to do so.
<div style='margin-top:-18px;'></div>

<br> **Male Names:** Deelni, Jaamre, Jenoh, Keerin, Kenzou, Kiro, <br>&nbsp;&nbsp;&nbsp; Nemru, Rikati, Shalku, Unjun
<br> **Female Names:** Erri, Eudora, Jena, Kova, Meerah, Nisha, <br>&nbsp;&nbsp;&nbsp; Norah, Rehea, Saiva, Venah

### Vulpera Traits
Your vulpera character has the following racial traits.

***Ability Score Increase.*** Your Dexterity score increases by 2, and your Intelligence score increases by 1.

***Age.*** Vulperas mature significantly faster than humans, reaching physical adulthood at the age of 5. However, a vul&shy;pera isn't considered an adult until they are ready to take on the responsibilities of their kin and caravan. They age noticeably faster and rarely live longer than 75 years.

\columnbreak

&nbsp;&nbsp;&nbsp; ***Alignment.*** Most vulpera lean towards true neutral, they keep to themselves and care for the wellbeing of their own. However, their affection for other beings can often be inter&shy;preted as acts of kindness, even if it is not done out of the kindness of their hearts. 

***Size.*** Vulpera are between 3 and 4 feet and average about 50 pounds. Your size is Small. To set your height and weight randomly, start with rolling the size modifier:
<div style="margin-top: -20px; font-family: ScalySans, sans-serif">

<br>&nbsp;&nbsp;&nbsp; ***Size Modifier:*** 2d4
<br>&nbsp;&nbsp;&nbsp; ***Height:*** 2 feet + 8 inches + your size modifier in inches
<br>&nbsp;&nbsp;&nbsp; ***Weight in Pounds:*** 35 + (1 x your size modifier)
</div>

<div style='margin-top:-3px;'></div>

&nbsp;&nbsp;&nbsp; ***Speed.*** Your base walking speed is 30 feet.

***Desert Born.*** You're naturally adapted to hot climates, as described in chapter 5 of the *Dungeon Master's Guide*.

***Fury of the Small.*** When you damage a creature with an attack or a spell and the creature's size is larger than yours, you can cause the attack or spell to deal extra damage to the creature. The extra damage equals your level. 

Once you use this trait, you can't use it again until you finish a short or long rest.

***Keen Hearing.*** You have advantage on Wisdom (Perception) checks that rely on hearing.

***Nomad's Knowledge.*** You gain proficiency with one of the following skills of your choice: Animal Handling, Na&shy;ture, Stealth, or Survival.

***Nose for Trouble.*** You can take the Disengage or Dodge action as a bonus action during your first turn of each combat. If you are surprised at the beginning of combat and aren't incapacitated, you can still take the Dodge action during your first turn.

***Pathfinder.*** Whenever you make a Wisdom (Survival) check related to navigating, you are considered proficient in the Survival skill and add double your proficiency bonus to the check, instead of your normal proficiency bonus.

***Languages.*** You can speak, read, and write Common 
<br> and two other languages of your choice. Vulpera are a nomadic race that picks up the languages of those
<br> they travel among.

<img src='https://www.gmbinder.com/images/ji0HTvu.jpg' style='position:absolute; top:660px; right:0px; width:1000px' />
<img src='https://www.gmbinder.com/images/wvTUmvu.png' style='position:absolute; top:35px; right:0px; width:1000px' />

\pagebreak

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
