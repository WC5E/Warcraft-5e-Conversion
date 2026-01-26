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

# Chapter 4: Equipment

AZEROTH IS HOME TO A GREAT MANY intelligent races, each with their own unique set of cultures and craftsmen. From the great dwarven smiths of Ironforge to the brilliant gnomish engineers of Gadgetzan, from the bubbling cauldrons of the undead alchemists of Undercity to the durable leatherwork of the tauren of Mulgore, there are quality creations in every corner of the world.

Elven cities such as Silvermoon and Darnassus are renowned for their streetside displays and mystical enclaves, and the floating mage city of Dalaran is said to practically overflow with arcane power. Most other major cities share this phenomena, to some extent; playing host to guilds and orders that dedicate themselves to different magical arts.

Azeroth is also a world of gunpowder, steam engines, and clockwork devices. Some technological creations are so advanced that they blur the line between magic and the mundane. Gnomes and goblins search for oil and esoteric substances to power their sprawling tech-hub cities and settlements.

This chapter is dedicated to the mundane and magical equipment that adventurers can find useful in the face of the threats that Azeroth brings to bear.

## Starting Equipment
When you create your character, you receive the equipment provided by your choice of class and background. Alternatively, you can choose to forgo this equipment and instead start with a number of gold coins based on your class. You can then spend these coins on equipment from this chapter to determine your starting equipment. If you choose this alternate option, consult the Starting Wealth by Class table below.

It is your choice on how you came by this equipment. Were they an inheritance from your master or noble relative? A standard set of gear from your time in the military? Illegally obtained by your time as a sticky-fingered orphan? Is the axe you carry a family heirloom or merely a piece of lumberjack's equipment put towards alternate use?

##### Starting Wealth by Class
|  Class        | Funds       | Average|
|:-------------------|------------:|-------:|
|  Death Knight | 4d4 x 10 gp | 100 gp |
|  Demon Hunter | 2d4 x 10 gp |  50 gp |
|  Druid        | 2d4 x 10 gp |  50 gp |
|  Hunter       | 5d4 x 10 gp | 125 gp |
|  Mage         | 4d4 x 10 gp | 100 gp |
|  Monk         | 2d4 x 10 gp |  50 gp |
|  Paladin      | 5d4 x 10 gp | 125 gp |
|  Priest       | 4d4 x 10 gp | 100 gp |
|  Rogue        | 4d4 x 10 gp | 100 gp |
|  Shaman       | 5d4 x 10 gp | 125 gp |
|  Warlock      | 4d4 x 10 gp | 100 gp |
|  Warrior      | 5d4 x 10 gp | 125 gp |

<div style='margin-top:-10px;'></div>

\columnbreak

## Wealth
Wealth can take many forms in Azeroth. Coins may be common among "civilized" races from humans to orcs to goblins, but other societies may instead value other forms of currency, such as crystals or rune shards from fallen civilizations, tokens earned through glorious combat, or even stranger materials such as glowing mushrooms or coldwater clams.

### Coinage
Commonly, coins come in three denominations based on the worth of the metal from which they are made: gold pieces (gp), silver pieces (sp), and copper pieces (cp). Many societies mint their own coins, which have their own regional names, such Stormwind's coinage being the copper penny, the silver groat, and the gold sovereign.

A standard coin weighs about a third of an ounce, so fifty coins weigh a pound.

Coin          | cp        | sp        | gp        |
--------------|----------:|----------:|----------:|
Copper (cp)   | 1         | 1/100     | 1/10,000  |
Silver (sp)   | 100       | 1         | 1/100     |
Gold (gp)     | 10,000    | 100       | 1         |

\pagebreakNum
### Selling Treasure
Opportunities abound to find treasure, equipment, weapons, armor, and more in the battlefields of Azeroth. Normally, you can sell your treasures and trinkets when you return to a town or other settlement, provided that you can find buyers and merchants interested in your loot.

***Arms, Armor, and Other Equipment.*** As a general rule, undamaged weapons, armor, and other equipment fetch half their cost when sold in a market. Weapons and armor used by monsters are rarely in good enough condition to sell.

***Magic Items.*** Selling magic items is problematic. Finding someone to buy a potion of a scroll isn't too hard, but other items are out of the realm of most but the wealthiest nobles. Likewise, apart from a few common magic items, you won't normally come across magic items or spells to purchase. The value of magic is far beyond simple gold and should always be treated as such.

***Gems, Jewelry, and Art Objects.*** These items retain their full value in the marketplace, and you can either trade them in for coin or use them as currency for other transactions. For exceptionally valuable treasures, the DM might require you to find a buyer in a large town or larger community first.

***Trade Goods.*** On the borderlands, many people conduct transactions through barter. Like gems and art objects, trade goods--bars of iron, bags of salt, livestock, and so on--retain their full value in the market and can be used for currency.

## Armor
Azeroth is a complex world made of may different cultures, with sometimes wildly different technology levels. For this reason, adventurers have access to a variety of armor types, ranging from leather armor to chain mail to costly plate armor, with severl other kinds of armor in between. The Armor table collects the most commonly available types of armor found in the game and separates them into three categories: light armor, medium armor, and heavy armor. Many fighters supplement their armor with a shield.

The Armor table shows the cost, weight, and other properties of the most common types of armor worn in the setting of Azeroth.

***Armor Proficiency.*** Anyone can put on a suit of armor or strap a shield to an arm. Only those proficient in the armor's uses know how to wear it effectively, however. Your class gives you proficiency with certain types of armor. If you wear armor that you lack proficiency with, you have disadvantage on any ability check, saving throw, or attack roll that involves Strength or Dexterity, and you can't cast spells.

***Armor Class (AC).*** Armor protects its wearer from attacks. The armor (and shield) you wear determines your base Armor Class.

***Heavy Armor.*** Heavier armor interferes with the wearer's ability to move quickly, stealthily, and freely. If the Armor table shows "Str 13" or "Str 15" in the Strength column for an armor type, the armor reduces the wearer's speed by 10 feet unless the wearer has a Strength score equal to or higher than the listed score.

***Stealth.*** If the Armor table shows "Disadvantage" in the Stealth column, the wearer has disadvantage on Dexterity (Stealth) checks.

***Shields.*** A shield is made from wood or metal and is carried in one hand. Wielding a shield increases your Armor Class by 2. You can benefit from only one shield at a time.

### Light Armor
Made from supple and thin materials, light armor favors agile adventurers since it offers some protection without sacrificing mobility. If you wear light armor, you add your Dexterity modifier to the base number from your armor type to determine your Armor Class.

***Padded.*** Padded armor consists of quilted layers of cloth and batting.

***Leather.*** The breastplate and shoulder protectors of this armor are made of leather that has been stiffened by being boiled in oil. The rest of the armor is made of softer and more flexible materials.

***Studded Leather.*** Made from tough but flexible leather, studded leather is reinforced with close-in rivets or spikes.

### Medium Armor

Medium armor offers more protection than light armor, but it also impairs movement more. If you wear medium armor, you add your Dexterity modifier, to a maximum of +2, to the base number from your armor type to determine your Armor Class.

***Hide.*** This crude armor consists of thick furs and pelts. It is commonly worn by barbarian tribes, those who prefer a connection to the wild, and other folk who lack access to the tools and materials needed to create better armor.

***Chain Shirt.*** Made of interlocking metal rings, a chain shirt is worn between layers of clothing or leather. The armor offers modest protection to the wearer's upper body and allows the sound of the rings rubbing against one another to be muffled by outer layers.

***Scale Mail.*** This armor consists of a coat and leggings (and perhaps a separate skirt) of leather covered with overlapping pieces of metal, much like the scales of a fish. The suit includes gauntlets.

***Breastplate.*** This armor consists of a fitted metal chest piece worn with supple leather. Although it leaves the legs and arms relatively unprotected, this armor provides good protection for the wearer's vital organs while leaving the wearer relatively unencumbered.

\pagebreakNum

    ***Half Plate.*** Half plate consists of shaped metal plates that cover most of the wearer's body. It does not include leg protection beyond simple greaves that are attached with leather straps.

### Heavy Armor
Of all the armor categories, heavy armor offers the best protection. These suits of armor cover the entire body and are designed to stop a wide range of attacks. Only proficient fighters can manage their weight and bulk. 

Heavy armor doesn't let you add your Dexterity modifier to your Armor Class, but it also doesn't penalize you if your Dexterity modifier is negative.

***Ring Mail.*** This armor is leather armor with heavy rings sewn into it. The rings help reinforce the armor against blows from swords and axes. Ring mail is inferior to chain mail, and it's usually worn only by those who can't afford better armor.

***Chain Mail.*** Made of interlocking metal rings, chain mail includes a layer of quilted fabric worn underneath the mail to prevent chafing and to cushion the impact of blows. The suit includes gauntlets.

***Splint.*** This armor is made of narrow vertical strips of metal riveted to a backing of leather that is worn over cloth padding. Flexible chain mail protects the joints.

***Plate.*** Plate consists of shaped, interlocking metal plates to cover the entire body. A suit of plate includes gauntlets, heavy leather boots, a visored helmet, and thick layers of padding underneath the armor. Buckles and straps distribute the weight over the body.

\columnbreak

<div class='classTable wide' >

##### Armor and Shields
|  Armor                                         |     Cost |       | Armor Class (AC)          | Strength | Stealth    | Weight |
|:-----------------------------------------------|---------:|---|:--------------------------|:---------|:-----------|-------:|
| *Light Armor*                                  |          |   |                           |        |              |        |
|     Padded          |     5 gp |   | 11 + Dex Modifier         | —      | Disadvantage |  8 lb. |
|     Leather         |    10 gp |   | 11 + Dex Modifier         | —      | —            | 10 lb. |
|     Studded leather |    45 gp |   | 12 + Dex Modifier         | —      | —            | 13 lb. |
| *Medium Armor*                                 |          |   |                           |        |              |        |
|     Hide            |    10 gp |   | 12 + Dex Modifier (max 2) | —      | —            | 12 lb. |
|     Chain shirt     |    50 gp |   | 12 + Dex Modifier (max 2) | —      | —            | 20 lb. |
|     Scale mail      |    50 gp |   | 12 + Dex Modifier (max 2) | —      | Disadvantage | 45 lb. |
|     Breastplate     |   400 gp |   | 12 + Dex Modifier (max 2) | —      | —            | 20 lb. |
|     Half plate      |   750 gp |   | 12 + Dex Modifier (max 2) | —      | Disadvantage | 45 lb. |
| *Heavy Armor*                                  |          |   |                           |        |              |        |
|     Ring mail       |    30 gp |   | 14                        | —      | Disadvantage | 40 lb. |
|     Chain mail      |    75 gp |   | 16                        | Str 13 | Disadvantage | 55 lb. |
|     Splint          |   200 gp |   | 17                        | Str 15 | Disadvantage | 60 lb. |
|     Plate           | 1,500 gp |   | 18                        | Str 15 | Disadvantage | 65 lb. |
| *Shield*                                       |          |   |                           |        |              |        |
|     Shield          |    10 gp |   | +2                        | —      | —            |  6 lb. |

</div>

<img src='https://vignette.wikia.nocookie.net/moon-guard/images/b/b1/Stormwind_Soldier_B.jpg/revision/latest?cb=20190128023706' style='position:absolute; right:0px; top:0px; width:420px' />
<img src='https://www.gmbinder.com/images/huxbNse.png' style='position:absolute; left:-80px; top:0px; width:900px' />

\pagebreakNum

### Getting Into and Out of Armor

The time it takes to don or doff a type of armor or a shield is shown in the Donning and Doffing Armor table.

***Don.*** This is the time it takes to put on the item. You benefit from its AC only if you take the full time to don it.

***Doff.*** This is the time it takes to take off the item. If you have help removing the armor, reduce the time by half.

##### Donning and Doffing Armor

| Category     | Don        | Doff      |
| ------------ | ---------- | --------- |
| Light Armor  |  1 minute  | 1 minute  | 
| Medium Armor |  5 minutes | 1 minute  |
| Heavy Armor  | 10 minutes | 5 minutes |
| Shield       |  1 action  | 1 action  |

## Weapons
Your class grants proficiency in certain weapons, reflecting both the class's focus and the tools you are most likely to use. Whether you favor a longsword or a longbow, your weapon and your ability to wield it effectively can mean the difference between life and death while adventuring.

The Weapons table shows the most common weapons used in Azeroth, their price and weight, the damage they deal when they hit, and any special properties they possess. Every weapon is classified as either melee or ranged. A **melee weapon** is used to attack a target within 5 feet of you, whereas a **ranged weapon** is used to attack a target from a distance. 

### Weapon Proficiency

Your race, class, and feats can grant you proficiency with certain weapons or categories of weapons. The two categories are **simple** and **martial** Most people can use simple weapons with proficiency. These weapons include clubs, maces, and other weapons often found in the hands of commoners. Martial weapons, including swords, axes, and polearms, require more specialized training to use efficiently. Most fighters use martial weapons because these weapons put their fighting style and training to best use.

Proficiency with a weapon allows you to add your proficiency bonus to the attack roll for any attack you make with that weapon. If you make an attack roll using a weapon with which you lack proficiency, you do not add your proficiency bonus to the attack roll. 

### Weapon Properties
Many weapons have special properties related to their use, as shown in the Weapons table.

***Ammunition.*** You can use a weapon that has the ammunition property to make a ranged attack only if you have ammunition to fire from the weapon. Each time you attack with the weapon, you expend one piece of ammunition. Drawing the ammunition from a quiver, case, or other container is part of the attack (you need a free hand to load a one-handed weapon). At the end of the battle, you can recover half your expended ammunition by taking a minute to search the battlefield.

\columnbreak

> ##### Azeroth's Guns: Primitive or Modern?
> In our world, firearms have gone through hundreds of years of development, starting from a curiosity so inaccurate, slow, and unreliable that it was only useful in massed numbers and eventually developing into the key component of modern combat. 
> 
> The setting of Azeroth on the other hand has a very loose definition on what level of firearms technology it utilizes. A blunderbuss can be seen alongside a sniper rifle, with the rare automatic rifles regulated to being belt-fed variants used on large siege vehicles. The setting runs on "rule of cool," with most firearms using a flintlock aesthetic with a focus on long guns over handguns (which are typically very rare).
>
> Following this pattern, the firearms depicted in this chapter are meant to be simplified represen­tations that can be used alongside other projectile weapons like bows, crossbows, and slings. More advanced versions than these do exist within the setting, but should be regarded as more like magic items than simple equipment.

If you use a weapon that has the ammunition property to make a melee attack, you treat the weapon as an improvised (see "Improvised Weapons" later in the section). A sling must be loaded to deal any damage when used in this way.

***Finesse.*** When making an attack with a finesse weapon, you use your choice of your Strength or Dexterity modifier for the attack and damage rolls. You must use the same modifier for both rolls.

***Firearm.*** You can use a weapon that has the firearm property to make a ranged attack only if you have ammunition to fire from the weapon. Each time you attack with the weapon, you expend one piece of ammunition. Drawing the ammunition from a bullet pouch is part of the attack (you need a free hand to load a one-handed weapon). When fired, this weapon creates a loud noise (easily heard up to 300 feet away), a small flash of light, and the smell of burnt explosives. Ammunition fired by this weapon is destroyed. If you use a weapon that has the firearm property to make a melee attack, you treat the weapon as an improvised weapon.

***Glove.*** A glove weapon is worn on your hand or forearm, and you cannot be disarmed of it. Your attacks with a glove weapon count as both an unarmed strike and a weapon attack. You can hold objects, wield weapons, and cast spells with a hand fitted with a glove weapon, but you can only attack with the glove weapon if that hand is unoccupied. It takes an action to don or doff a glove weapon.

***Heavy.*** Small creatures have disadvantage on attack rolls with heavy weapons. A heavy weapon's size and bulk make it too large for a Small creature to use effectively.

***Light.*** A light weapon is small and easy to handle, making it ideal for use when fighting with two weapons. See the rules for two-weapon fighting in chapter 9 of the Player's Handbook.

***Loading.*** Because of the time required to load this weapon, you can fire only one piece of ammunition from it when you use an action, bonus action, or reaction to fire it, regardless of the number of attacks you can normally make.

\pagebreakNum

<div class='classTable wide'>

##### Simple Weapons
| Name                                                  | Cost  | | Damage          | Weight | | Properties |
|-------------------------------------------------------|------:|-|-----------------|--------:|-|----------------------
| _Simple Melee Weapons_            |       | |                 |         | |
|     Bayonet        | 2 gp  | | 1d6 piercing    |  1 lb.  | | Special, versatile (1d8)
|     Club           | 1 sp  | | 1d4 bludgeoning |  2 lb.  | | Light
|     Dagger         | 2 gp  | | 1d4 piercing    |  1 lb.  | | Finesse, light, thrown (range 20/60)
|     Greatclub      | 2 sp  | | 1d8 bludgeoning | 10 lb.  | | Two-handed 
|     Handaxe        | 5 gp  | | 1d6 slashing    |  2 lb.  | | Light, thrown (range 20/60)
|     Javelin        | 5 sp  | | 1d6 piercing    |  2 lb.  | | Thrown (range 30/120)
|     Knuckledusters | 2 gp  | | 1d4 bludgeoning |  1 lb.  | | Glove, light
|     Light hammer   | 2 gp  | | 1d4 bludgeoning |  2 lb.  | | Light, thrown (range 20/60)
|     Mace           | 5 gp  | | 1d6 bludgeoning |  4 lb.  | | —
|     Quarterstaff   | 2 sp  | | 1d6 bludgeoning |  4 lb.  | | Versatile (1d8)
|     Scythe         | 5 gp  | | 1d8 slashing    |  5 lb.  | | Two-handed
|     Sickle         | 1 gp  | | 1d4 slashing    |  2 lb.  | | Light
|     Spear          | 1 gp  | | 1d6 piercing    |  3 lb.  | | Thrown (range 20/60), versatile (1d8)
|_Simple Ranged Weapons_            |       | |                 |        | | 
|     Crossbow, Light| 25 gp | | 1d8 piercing    |  5 lb. | | Ammunition (range 80/320), loading, two-handed
|     Dart           | 5 cp  | | 1d4 piercing    |1/4 lb. | | Finess, thrown (range 20/60)
|     Shortbow       | 25 gp | | 1d6 piercing    |  2 lb. | | Ammunition (range 80/320), two-handed
|     Sling          | 1 sp  | | 1d4 bludgeoning |  —     | | Ammunition (range 30/120)

</div>

***Range.*** A weapon that can be used to make a ranged attack has a range in parentheses after the ammunition of thrown property. The range lists two numbers. The first is the weapon's normal range in feet, and the second indicates the weapon's long range. When attacking a target beyond normal range, you have disadvantage on the attack roll. You can't attack a target beyond the weapon's long range. 

***Reach.*** This weapon adds 5 feet to your reach when you attack with it, as well as determining your reach for opportunity attacks (see chapter 9 of the Player's Handbook).

***Returning.*** When you throw this weapon and miss, it returns to your hand when the attack resolves.

***Special.*** A weapon with the special property has unusual rules governing its use, explained in the weapon's description (see "Special Weapons" later in this section).

***Thrown.*** If a weapon has the thrown property, you can throw the weapon to make a ranged attack. If the weapon is a melee weapon, you use the same ability modifier for that attack roll and damage roll that you would use for a melee attack with the weapon. For example, if you throw a handaxe, you use your Strength, but if you throw a dagger, you can either use your Strength or your Dexterity, since the dagger has the finesse property. 

***Two-Handed.*** This weapon requires two hands when you attack with it.

***Versatile.*** This weapon can be used with one or two hands. A damage value in parentheses appears with the property--the damage when the weapon is used with two hands to make a melee attack.

#### Improvised Weapons
Sometimes characters don't have their weapons and have to attack with whatever is at hand. An improvised weapon includes any object you can wield in one or two hands, such as broken glass, a table leg, a frying pan, a wagon wheel, or a dead murloc.

Often, an improvised weapon is similar to an actual weapon and can be treated as such. For example, a table leg is akin to a club. At the DM's option, a character proficient with a weapon can use a similar object as if it were that weapon and use his or her proficiency bonus.

An object that bears no resemblance to a weapon deals 1d4 damage (the DM assigns a damage type appropriate to the object). If a character uses a ranged weapon to make a melee attack, or throws a melee weapon that does not have the thrown property, it also deals 1d4 damage. An improvised thrown weapon has a normal range of 20 feet and a long range of 60 feet.

\pagebreakNum

<div class='classTable wide'>

##### Martial Weapons
| Name                              | Cost  | | Damage          | Weight | | Properties |
|-----------------------------------|------:|-|-----------------|-------:|-|----------------------
|_Martial Melee Weapons_            |       | |                 |         | |
|    Battle totem    | 35 gp | | 1d12 bludgeoning| 35 lb.  | | Heavy, two-handed
|    Battleaxe       | 10 gp | | 1d6 slashing    | 4 lb.   | | Versatile (1d10)
|    Boomerang       | 25 gp | | 1d6 bludgeoning |  2 lb.  | | Finesse, returning, thrown (range 30/120)
|    Chakram         | 25 gp | | 1d6 slashing    |  2 lb.  | | Finesse, returning, thrown (range 30/120)
|    Flail           | 10 gp | | 1d8 bludgeoning | 2 lb.   | | —
|    Glaive          | 20 gp | | 1d10 slashing   | 6 lb.   | | Heavy, reach, two-handed
|    Greataxe        | 30 gp | | 1d12 slashing   | 7 lb.   | | Heavy, two-handed
|    Greatspear      | 40 gp | | 2d6 piercing    | 12 lb.  | | Heavy, two-handed
|    Greatsword      | 50 gp | | 2d6 slashing    | 6 lb.   | | Heavy, two-handed 
|    Halberd         | 20 gp | | 1d10 slashing   | 6 lb.   | | Heavy, reach, two-handed
|    Harpoon spear   |  2 gp | | 1d6 piercing    | 3 lb.   | | Special, thrown (range 20/60), versatile (1d8)
|    Lance           | 10 gp | | 1d12 piercing   | 6 lb.   | | Reach, special
|    Longsword       | 15 gp | | 1d8 slashing    | 3 lb.   | | Versatile (1d10)
|    Maul            | 10 gp | | 2d6 bludgeoning | 10 lb.  | | Heavy, two-handed
|    Morningstar     | 15 gp | | 1d8 piercing    | 4 lb.   | | —
|    Pike            | 5 gp  | | 1d10 piercing   | 18 lb.  | | Heavy, reach, two-handed 
|    Rapier          | 25 gp | | 1d8 piercing    | 2 lb.   | | Finesse
|    Scimitar        | 25 gp | | 1d6 slashing    | 3 lb.   | | Finesse, light
|    Shortsword      | 10 gp | | 1d6 piercing    | 2 lb.   | | Finesse, light
|    Spiked Chain    | 15 gp | | 1d6 slashing    |  5 lb.  | | Finesse, reach, two-handed
|    Trident         | 5 gp  | | 1d6 piercing    | 4 lb.   | | Thrown (range 20/60), versatile (1d8)
|    Twinblade       | 50 gp | | 1d8 slashing    |  5 lb.  | | Special, two-handed 
|    Warclaw         | 12 gp | | 1d6 slashing    |  2 lb.  | | Glove, light
|    Warglaive       | 25 gp | | 1d6 slashing    |  2 lb.  | | Light, thrown (range 20/60)
|    War pick        | 5 gp  | | 1d8 piercing    | 2 lb.   | | Versatile (1d10) 
|    Warhammer       | 15 gp | | 1d8 bludgeoning | 2 lb.   | | Versatile (1d10) 
|    Whip            | 2 gp  | | 1d4 slashing    | 3 lb.   | | Finesse, reach
|_Martial Ranged Weapons_           |       | |                 |        | | 
|    Blowgun         | 10 gp | | 1 piercing      |  1 lb. | | Ammunition (range 25/100), loading
|    Blunderbuss     | 85 gp | | 2d6 piercing    | 10 lb. | | Firearm (range 20/60), loading, two-handed  |
|    Bolas           | 5 gp  | | —               |  1 lb. | | Special, thrown (range 20/60)
|    Crossbow, hand  | 75 gp | | 1d6 piercing    |  3 lb. | | Ammunition (range 30/120), light, loading
|    Crossbow, heavy | 50 gp | | 1d10 piercing   | 18 lb. | | Ammunition (range 100/400), heavy, loading, two-handed
|    Harpoon Launcher| 90 gp | | 1d6 piercing    |  4 lb. | | Ammunition (range 30/120), loading, special
|    Longbow         | 50 gp | | 1d8 piercing    |  2 lb. | | Ammunition (range 150/600), heavy, two-handed
|    Musket          | 75 gp | | 1d12 piercing   | 10 lb. | | Firearm (range 60/240), loading, two-handed |
|    Net             | 1 gp  | | —               |  3 lb. | | Special, thrown (range 5/15)
|    Net Launcher    | 90 gp | | —               |  4 lb. | | Ammunition (range 30/120), loading, special |
|    Pistol          | 75 gp | | 1d8 piercing    |  3 lb. | | Firearm (range 30/120), loading, light      |

</div>

\pagebreakNum

#### Silvered Weapons
Some monsters that have immunity or resistance to nonmagical weapons are susceptible to silver weapons, so cautious adventurers invest extra coin to plate their weapons with silver. You can silver a single weapon or ten pieces of ammunition for 100 gp. This cost represents not only the price of the silver, but the time and expertise needed to add silver to the weapon without making it less effective.

#### Special Weapons
Weapons with special rules are described here.

***Bayonet.*** This blade can be attached or removed from the end of a crossbow or firearm as an action, allowing it to be used it to be used as a melee weapon instead of an improvised one. In order to use the bayonet's versatile property, the attached weapon must have the two-handed property. While the most common form of bayonet is a slim blade for piercing, other forms of bayonet exist such as those that appear as axe blades or hammer heads, dealing slashing or bludgeoning damage as appropriate.

***Bolas.*** A Large or smaller creature hit by a bolas is grappled until it is freed. A bolas has no effect on creatures that are formless, who are Huge or larger, or do not have limbs such as legs or wings that can be bound to immobilize them. A creature can use its action to make a DC 10 Strength check, freeing itself or another creature within its reach on a success. Dealing 5 slashing damage to the bolas (AC 10) also frees the creature without harming it, ending the effect and destroying the bolas.

[***Harpoon.***](https://www.reddit.com/r/UnearthedArcana/comments/xb29g3/harpoons_a_nautical_35e_weapon_converted_to_5e/) 

<!-- You can choose to tether yourself with a rope to a creature or object you hit with the harpoon; otherwise, you can pull the object back to yourself as an object interaction. If you choose to tether yourself, the hand you used to make the attack becomes occupied maintaining the tether. You cannot maintain multiple tethers in one hand.

Once per turn, you can make an opposed Strength check against a creature you have tethered (no action required). On a success, you can pull the tethered creature towards you as though you are grappling it. A tethered creature can attempt to do the same to you on its turn, though if you fail the opposed Strength check, you can choose to drop the tether rather than be dragged by it. Any time an opposed Strength check is made between you and a tethered creature, if both of you roll a 10 or higher on this check, the tether snaps.

Any creature within 5 feet of a tethered creature (included the tethered creature) can use an action to remove the harpoon. Doing so deals an additional 1d6 weapon damage to the creature as the harpoon is removed. Dealing 5 slashing damage to the tether (AC 10) also snaps it.

If you recover a harpoon spear or a harpoon gun bolt with a snapped rope, you can replace the rope over 10 minutes, using 1 gp worth of rope and other supplies. This can be done over the course of a short or long rest. -->

***Lance.*** You have disadvantage when you use a lance to attack a target within 5 feet of you. Also, a lance requires two hands to wield when you aren't mounted.

***Launcher.*** A launcher is a mechanical device that uses another weapon as ammunition, allowing it 

allows you to make an attack with a net at a greater distance (see chapter 5 of the Player's Handbook for more rules on the net). A net must be folded before it can be used as ammunition; folding a net takes 1 minute, after which it can be used as ammunition instead of a weapon.

***Net.*** A Large or smaller creature hit by a net is restrained until it is freed. A net has no effect on creatures that are formless, or creatures that are Huge or larger. A creature can use its action to make a DC 10 Strength check, freeing itself or another creature within its reach on a success. Dealing 5 slashing damage to the net (AC 10) also frees the creature without harming it, ending the effect and destroying the net.

When you use an action, bonus action, or reaction to attack with a net, you can make only one attack regardless of the number of attacks you can normally make.

***Twinblade.*** This weapon has a set of twin blades on either side of its hilt. If you make an attack with it as part of the Attack action on your turn, you can use a bonus action imme­diately after to make another melee attack with it. This extra attack deals 1d4 slashing damage on a hit.

\pagebreakNum

##### Adventuring Gear
Item                        | Cost  | Weight
----------------------------|-------|-----------
Acid (vial)                 |
Air tank                    |
*Ammunition*                |
    Arrows (20)          |
    Blowgun needles (50) |
    Crossbow bolts (20)  |
    Firearm bullets (40) |
    Sling bullets (20)   |
Animal call                 |
Animal collar               |
Animal treats               |
Antitoxin                   |
*Arcane focus*              |
    Athame   |
    Crystal  |
    Demonic Figurine? |
    Orb      |
    Rod      |
    Staff    |
    Wand     |
Arclight spanner            |
Armor maintenance kit       |
Army knife                  |

\pagebreakNum

Item                        | Cost  | Weight
----------------------------|-------|-----------
Backpack                    |
Ball bearings (bag of 1,000)|
Bandolier                   |
Banner/standard             |
Barbed wire (100 feet)      |
Barrel                      |
Battery/fuel/phlogiston     |
Basket                      |
Bedroll                     |
Binoculars                  |
Bipod                       |
Blanket                     |
Block and tackle            |
Bolt cutters                |
Bomb                        |
Bomb, stink                 |
Bonesaw                     |
Book                        |
Book, false                 |
Boots, smuggler's           |
Bottle, glass               |
Brewmaker, adventurer's     |
Briefcase                   |
Butterfly net               |
Bucket                      |

Item                        | Cost  | Weight
----------------------------|-------|-----------
Cage                        |
Calculator                  |
Caltrops (bag of 20)        |
Camera                      |
Candle                      |
Case, crossbow bolt         |
Case, map or scroll         |
Chain (10 feet)             |
Chalk (1 piece)             |
Cigar                       | <!-- Ironforge Rifleman, from Hearthstone -->
Clay mold                   |
Climber's kit               |
Climbing ascender           |
Clockwork Rocket Bot        |
*Clothes*                   |
    Cold weather       |
    Common             |
    Costume            |
    Fine               |
    Fire Resistant     |
    Hot weather        |
Coffin                      |
Component pouch             |
Crane, portable             |
Crowbar                     |

\pagebreakNum

Item                        | Cost  | Weight
----------------------------|-------|-----------
Dice, loaded                |
Diving suit                 |
*Druidic focus*             |
    Sprig of mistletoe   |
    Totem                |
    Wooden staff         |
    Yew wand             |
Dynamite                    |
Earplugs                    |
Fire extinguisher           |
Fire oil                    |
Firework                    |
First aid kit               |
Fishing tackle              |
Flare                       |
Flask or tankard            |
Flashlight                  |
Frost oil                   |
Fuse (100 feet)             |

\columnbreak

Item                        | Cost  | Weight
----------------------------|-------|-----------
Gas mask                    |
Glass cutter                |
Glowstick                   |
Glue                        |
Goggles                     |
Goggles, dark vision        |
Goggles, night vision       |
Goggles, snow               |
Grappling hook              |
Grappling hook launcher     |
Grease                      |
*Grenade*                   |
    Fragmentation|
    Incendiary   |
    Smoke        |

\pagebreakNum

Item                        | Cost  | Weight
----------------------------|-------|-----------
Hacksaw                     |
Hammer                      |
Hammer, sledge              |
Hammock                     |
Helmet, miner's             |
*Holy symbol*               |
    Amulet   |
    Emblem   |
    Libram   |
    Reliquary|
Holy water (flask)          |
Hourglass                   |
Hunting trap                |
Ice axe                     |
Ink (1 ounce bottle)        |
Ink pen                     |
Insect netting              |
Insect repellent            |
Jug or pitcher              |
Kite                        |
Knife, skinning             |
Ladder (10-foot)            |
Lamp                        |
Lantern, bullseye           |
Lantern, electric           |
Lantern, hooded             |
Laser sight                 |
Leash and muzzle            |
Listening cone              |
Lock                        |
Lockbox                     |

\columnbreak

Item                        | Cost  | Weight
----------------------------|-------|-----------
Magnet, small               |
Magnifying glass            |
Manacles                    |
Map                         |
Matches (box of 40)         |
Mess kit                    |
Microscope                  |
Mirror, steel               |
Oil, lantern (flask)        |
Paint (1 UNIT)              |
Paper (1 sheet)             |
Parachute                   |
Parchment (1 sheet)         |
Perfume (vial)              |
Periscope                   |
Pick, miner's               |
Piton                       |
Pocketwatch                 |
Poison, basic (vial)        |
Portable glider             |
Pole, collapsible (10-foot) |
Pot, iron                   |
*Potion of Healing*         |
Pouch                       |
Preserved organ or body part|
Punchcard                   |
Quiver                      |
Radio, one-way              |
Radio, two-way              |
Rations, animal (1 day)     |   
Rations, trail (1 day)      |
Robes                       |
Rope, hempen (50 ft.)       |
Rope, silk (50 ft.)         |

\pagebreak

Item                        | Cost  | Weight
----------------------------|-------|-----------
Safe                        |
Scale, merchant             |
Shadow oil                  |
Skis and poles              |
Slate board                 |
Smelling salts              |
Snorkel                     |
Snowshoes                   |
Spellbook                   |
Sprayer                     |
Spyglass                    |
Steam Tonk                  |
Stilts                      |
Suit, diving                |
Suit, fire resistant        |
Suit, ghillie               |
Suturing kit                |
Syringe                     |
Tabard                      |
Table case, folding         |
Tape (60 feet)              |
Tarp                        |
Tea set                     |
*Tent*                      |
    One-person   |
    Two-person   |
    Four-person  |
    Pavilion     |
Teepee                      |
Tool belt                   |
Torch                       |
Torch, signal               |
Twine (100-foot roll)       |
Whetstone                   |
Wrist sheath, spring-loaded |
Wok, iron                   |

\pagebreak

## Adventuring Gear (SRD)
This section describes items that have special rules or require further explanation.

***Acid.*** As an action, you can splash the contents of this vial onto a creature within 5 feet of you or throw the vial up to 20 feet, shattering it on impact. In either case, make a ranged attack against a creature or object, treating the acid as an improvised weapon. On a hit, the target takes 2d6 acid damage.

***Antitoxin.*** A creature that drinks this vial of liquid gains advantage on saving throws against poison for 1 hour. It confers no benefit to undead or constructs.

***Arcane Focus.*** *An arcane focus is a special item—an orb, a crystal, a rod, a specially constructed staff, a wand-like length of wood, or some similar item— designed to channel the power of arcane spells.* **A mage or warlock can use such an item as a spellcasting focus.**

***Ball Bearings.*** As an action, you can spill these tiny metal balls from their pouch to cover a level area 10 feet square. A creature moving across the covered area must succeed on a DC 10 Dexterity saving throw or fall prone. A creature moving through the area at half speed doesn't need to make the saving throw.

***Block and Tackle.*** A set of pulleys with a cable threaded through them and a hook to attach to objects, a block and tackle allows you to hoist up to four times the weight you can normally lift.

***Book.*** A book might contain poetry, historical accounts, information pertaining to a particular field of lore, diagrams and notes on gnomish contraptions, or just about anything else that can be represented using text or pictures. A book of spells is a spellbook (described later in this section).

***Caltrops.*** As an action, you can spread a single bag of caltrops to cover a 5-foot-square area. Any creature that enters the area must succeed on a DC 15 Dexterity saving throw or stop moving and take 1 piercing damage. Until the creature regains at least 1 hit point, its walking speed is reduced by 10 feet. A creature moving through the area at half speed doesn't need to make the saving throw.

***Candle.*** For 1 hour, a candle sheds bright light in a 5-foot radius and dim light for an additional 5 feet. Multiple candles together (such as held in a candelabra or grouped together on a table) increase this radius: four candles increase the radius of light to 10 feet, eight candles to 15 feet, and sixteen candles to 20 feet.

***Case, Crossbow Bolts.*** This wooden case can hold up to twenty crossbow bolts.

***Case, Map or Scroll.*** This cylindrical leather case can hold up to ten rolled-up sheets of paper or five rolled-up sheets of parchment.

***Chain.*** A chain has 10 hit points. It can be burst with a successful DC 20 Strength check.

***Climber's Kit.*** A climber's kit includes special pitons, boot tips, gloves, and a harness. You can use the climber's kit as an action to anchor yourself; when you do, you can't fall more than 25 feet from the point where you anchored yourself, and you can't climb more than 25 feet away from that point without undoing the anchor.

***Component Pouch.*** A component pouch is a small, watertight leather belt pouch that has compartments to hold all the material components and other special items you need to cast your spells, except for those components that have a specific cost (as indicated in a spell's description).

***Crowbar.*** Using a crowbar grants advantage to Strength checks where the crowbar's leverage can be applied.

***Druidic Focus.*** *A druidic focus might be a sprig of mistletoe or holly, a wand or scepter made of yew or another special kind of wood, a staff drawn whole out of a living tree, or a totem incorporating feathers, fur, bones, and teeth from sacred animals.* **A druid or shaman can use such an object as a spellcasting focus.**

***Fishing Tackle.*** This kit includes a wooden rod, silken line, corkwood bobbers, steel hooks, lead sinkers, velvet lures, and narrow netting.

***Healer's Kit.*** This kit is a leather pouch containing bandages, salves, and splints. The kit has ten uses. As an action, you can expend one use of the kit to stabilize a creature that has 0 hit points, without needing to make a Wisdom (Medicine) check.

***Holy Symbol.*** *A holy symbol is a representation of a god or pantheon. It might be an amulet depicting a symbol representing a deity, the same symbol carefully engraved or inlaid as an emblem on a shield, or a tiny box holding a fragment of a sacred relic. APPENDIX B LISTS THE SYMBOLS COMMONLY ASSOCIATED WITH MANY GODS IN THE MULTIVERSE.* **A paladin or priest can use a holy symbol as a spellcasting focus.** To use the symbol in this way, the caste must hold it in hand, wear it visibly, or bear it on a shield.

***Holy Water.*** As an action, you can splash the contents of this flask onto a creature within 5 feet of you or throw it up to 20 feet, shattering it on impact. In either case, make a ranged attack against a target creature, treating the holy water as an improvised weapon. If the target is a fiend or undead, it takes 2d6 radiant damage.

A paladin or priest may create holy water by performing a special ritual. The ritual takes 1 hour to perform, uses 25 gp worth of powdered silver, and requires the caster to expend a 1st-level spell slot.

***Hunting Trap.*** When you use your action to set it, this trap forms a saw-toothed steel ring that snaps shut when a creature steps on a pressure plate in the center. The trap is affixed by a heavy chain to an immobile object, such as a tree or a spike driven into the ground. A creature that steps on the plate must succeed on a DC 13 Dexterity saving throw or take 1d4 piercing damage and stop moving. Thereafter, until the creature breaks free of the trap, its movement is limited by the length of the chain (typically 3 feet long). A creature can use its action to make a DC 13 Strength check, freeing itself or another creature within its reach on a success. Each failed check deals 1 piercing damage to the trapped creature.

***Lamp.*** A lamp casts bright light in a 15-foot radius and dim light for an additional 30 feet. Once lit, it burns for 6 hours on a flask (1 pint) of oil.

***Lantern, Bullseye.*** A bullseye lantern casts bright light in a 60-foot cone and dim light for an additional 60 feet. Once lit, it burns for 6 hours on a flask (1 pint) of oil.

***Lantern, Hooded.*** A hooded lantern casts bright light in a 30-foot radius and dim light for an additional 30 feet. Once lit, it burns for 6 hours on a flask (1 pint) of oil. As an action, you can lower the hood, reducing the light to dim light in a 5-foot radius.

***Lock.*** A key is provided with the lock. Without the key, a creature proficient with thieves' tools can pick this lock with a successful DC 15 Dexterity check. Your DM may decide that better locks are available for higher prices.

\pagebreakNum

***Magnifying Glass.*** This lens allows a closer look at small objects. It is also useful as a substitute for flint and steel when starting fires. Lighting a fire with a magnifying glass requires light as bright as sunlight to focus, tinder to ignite, and about 5 minutes for the fire to ignite. A magnifying glass grants advantage on any ability check made to appraise or inspect an item that is small or highly detailed.

***Manacles.*** These metal restraints can bind a Small or Medium creature. Escaping the manacles requires a successful DC 20 Dexterity check. Breaking them requires a successful DC 20 Strength check. Each set of manacles comes with one key. Without the key, a creature proficient with thieves' tools can pick the manacles' lock with a successful DC 15 Dexterity check. Manacles have 15 hit points.

***Mess Kit.*** This tin box contains a cup and simple cutlery. The box clamps together, and one side can be used as a cooking pan and the other as a plate or shallow bowl.

***Oil.*** Oil usually comes in a clay flask that holds 1 pint. As an action, you can splash the oil in this flask onto a creature within 5 feet of you or throw it up to 20 feet, shattering it on impact. Make a ranged attack against a target creature or object, treating the oil as an improvised weapon. On a hit, the target is covered in oil. If the target takes any fire damage before the oil dries (after 1 minute), the target takes an additional 5 fire damage from the burning oil. You can also pour a flask of oil on the ground to cover a 5-foot-square area, provided that the surface is level. If lit, the oil burns for 2 rounds and deals 5 fire damage to any creature that enters the area or ends its turn in the area. A creature can take this damage only once per turn.

***Poison, Basic.*** You can use the poison in this vial to coat one slashing or piercing weapon or up to three pieces of ammunition. Applying the poison takes an action. A creature hit by the poisoned weapon or ammunition must make a DC 10 Constitution saving throw or take 1d4 poison damage. Once applied, the poison retains potency for 1 minute before drying.

***Potion of Healing.*** A character who drinks the red fluid in this vial regains 2d4 + 2 hit points. Drinking or administering a potion takes an action.

***Pouch.*** A cloth or leather pouch can hold up to 20 sling bullets, **40 firearm bullets**, or 50 blowgun needles, among other things. A compartmentalized pouch for holding spell components is called a component pouch. A pouch can hold up to ⅕ cubic foot or 6 pounds of gear.

***Quiver.*** A quiver can hold up to 20 arrows.

***Ram, Portable.*** You can use a portable ram to break down doors. When doing so, you gain a +4 bonus on the Strength check. One other character can help you use the ram, giving you advantage on this check.

***Rations.*** Rations consist of dry foods suitable for extended travel, including jerky, dried fruit, hardtack, and nuts.

***Rope.*** Rope, whether made of hemp or silk, has 2 hit points and can be burst with a DC 17 Strength check.

***Scale, Merchant's.*** A scale includes a small balance, pans, and a suitable assortment of weights up to 2 pounds. With it, you can measure the exact weight of small objects, such as raw precious metals or trade goods, to help determine their worth.

***Spellbook.*** Essential for mages and warlocks, a spellbook is a leather-bound tome with 100 blank vellum pages suitable for recording spells.

***Spyglass.*** Objects viewed through a spyglass are magnified to twice their size.

***Tent.*** A simple and portable canvas shelter, a tent sleeps two.

***Tinderbox.*** This small container holds flint, fire steel, and tinder (usually dry cloth soaked in light oil) used to kindle a fire. Using it to light a torch—or anything else with abundant, exposed fuel—takes an action. Lighting any other fire takes 1 minute.

***Torch.*** A torch burns for 1 hour, providing bright light in a 20-foot radius and dim light for an additional 20 feet. If you make a melee attack with a burning torch and hit, it deals 1 fire damage.


<!-- 

<div class='classTable'>

##### Container Capacity
Container           |Capacity
--------------------|-----------------------------
Backpack*           |1 cubic foot/30 pounds of gear
Barrel              |40 gallons liquid, 4 cubic feet solid
Basket              |2 cubic feet/40 pounds of gear
Bottle              |1.5 pints liquid
Bucket              |3 gallons liquid, 1/2 cubic foot solid
Chest               |12 cubic feet/300 pounds of gear
Flask or tankard    |1 pint liquid
Jug or pitcher      |1 gallon liquid
Pot, iron           |1 gallon liquid
Pouch               |1/5 cubic foot/6 pounds of gear
Sack                |1 cubic foot/30 pounds of gear
Vial                |4 ounces liquid
Waterskin           |4 pints liquid

*You can also strap items, such as a bedroll or a coil of rope, to the outside of a backpack.
</div>

-->

> ##### Equipment Packs
> The starting equipment you get from your class includes a collection of useful adventuring gear, put together in a pack. The contents of these packs are listed here. If you are buying your starting equipment, you can purchase a pack for the price shown, which might be cheaper than buying the items individually.
> 
> ***Burglar's Pack (16 gp).*** Includes a backpack, a bag of 1,000 ball bearings, 10 feet of string, a bell, 5 candles, a crowbar, a hammer, 10 pitons, a hooded lantern, 2 flasks of oil, 5 days rations, a tinderbox, and a waterskin. The pack also has 50 feet of hempen rope strapped to the side of it.
> 
> ***Diplomat's Pack (33 gp).*** Includes a chest, 2 cases for maps and scrolls, a set of fine clothes, a bottle of ink, an ink pen, a lamp, 2 flasks of oil, 5 sheets of paper, a vial of perfume, sealing wax, and soap.
> 
> ***Dungeoneer's Pack (12 gp).*** Includes a backpack, a crowbar, a hammer, 10 pitons, 10 torches, a tinderbox, 10 days of rations, and a waterskin. The pack also has 50 feet of hempen rope strapped to the side of it.
> 
> ***Entertainer's Pack (40 gp).*** Includes a backpack, a bedroll, 2 costumes, 5 candles, 5 days of rations, a waterskin, and a disguise kit.
> 
> ***Explorer's Pack (10 gp).*** Includes a backpack, a bedroll, a mess kit, a tinderbox, 10 torches, 10 days of rations, and a waterskin. The pack also has 50 feet of hempen rope strapped to the side of it.
>
> ***Priest's Pack (19 gp).*** Includes a backpack, a blanket, 10 candles, a tinderbox, an alms box, 2 blocks of incense, a censer, vestments, 2 days of rations, and a waterskin.
> 
> ***Scholar's Pack (19 gp).*** Includes a backpack, a book of lore, a bottle of ink, an ink pen, 10 sheets of parchment, a little bag of sand, and a small knife.


\pagebreakNum

## Adventuring Gear (New/Alternate)

***Air Tank.*** For diving, or other pressurized air uses

***Animal Call.*** Specific to each animal

***Animal Collar.*** For identifying owned animals

***Animal Treats.***

***Arclight Spanner.*** Not sure if this needs an entry

***Armor Maintenance Kit.*** Whetstone equivalent

***Army Knife.*** Popular among both goblins and gnomes, this compact device has many uses. Can be used as one of: Back scratcher, Block and tackle, crowbar, fishing rod, hammer, firestarter, magnifying glass, mirror, five-foot pole (alternate use of fishing rod), 25 feet silk rope and a grappling hook, saw, sewing needle, three kinds of signal whistles, shovel, a 1-person tent, whetstone, a whirly thing. Also cuts things as a small knife. Accessing any of these functions requires manipulating the device for 3 rounds.

***Bandolier.***

***Banner/Standard.***

***Barbed Wire.*** Lets you make barriers that deal 1d6 slashing damage to those who try to force their way through

***Battery/fuel/phlogiston.*** Used to power mechanical devices.

***Binoculars.*** Makes things closer. Eliminates disadvantage on distant perception checks, but takes five times as long to do so.

***Bipod.*** Lets you ignore disadvantage on ranged attack rolls when prone, when you brace the crossbow/firearm

***Bolt Cutters.*** Requires a Strength check to use

***Bomb.***

***Bomb, Stink.*** Troglodyte stink ability at point

***Bonesaw.*** Let you cut through limbs

***Book, False.*** Hollow interior

***Boots, Smuggler's.*** Empty space in the heel

***Brewmaker, Adventurer's.*** Pressurized container for brewing crappy alcohol on the go. Better than nothing

***Briefcase.*** Just a new container

***Butterfly Net.*** Make it easier to catch small critters like bugs, birds, squirrels, etc.

***Cage.*** For capturing/carrying small animals, or larger varieties if needed

***Calculator.*** Small mechanical calculator that prints out the results

***Camera.*** A mix between a flash-bulb old timey camera and a Polaroid instant-print camera

***Cigar.*** I saw an image of a dwarf smoking one in Hearthstone and thought I'd include it. Also need a tauren peace pipe

***Clay Mold.*** Lets you make quick copies of things like keys

***Climbing Ascender.*** Ratcheting rope attachment, allowing for easier climbing or descent

***Clockwork Rocket Bot.*** Small fighting robot. Useful as a distraction or to fight other robots.

***Clothes, Cold Weather.*** Thicker clothes designed to protect from the cold

***Clothes, Hot Weather.*** Thinner clothes designed to help with desert weather

***Coffin.*** For forsaken, death knights, or just in preparation for dead fellows. I once had a character who used one as his backpack

***Crane, portable.*** Gnomes/goblins work smarter, not harder.

***Dice, Loaded.***

***Diving Suit.*** Wear over clothes/armor

***Dynamite.*** 

***Earplugs.*** Adv on saves versus being deafened, but disadv on hearing checks

***Fire Extinguisher.*** Essential for any goblin engineer

***Fire Oil.*** Apply to weapon, deal fire damage

***Firework.*** Basic rocket explosive

***First Aid Kit.*** Medicine kit renamed?

***Flare.*** Road Flare.

***Flare Gun.*** 

***Flashlight.***

***Frost Oil.*** Apply to weapon, deal cold damage

***Fuse.*** For detonating dynamite

***Gas Mask.*** Adv/immunity on saves to inhaled poisons, but disadv on perception checks

***Glass Cutter.*** Cut a circular hole in glass

***Glowstick.***

***Glue.*** 

***Goggles.***

***Goggles, dark vision.*** For those with light blindness. Basically sunglasses.

***Goggles, Night Vision.*** Gives darkvision, but disadvantage on peripheral vision.

***Goggles, snow.*** Goggles with narrow slits, to help prevent snow blindness

***Grappling Hook Launcher.*** A modified crossbow

***Grease.*** Small can, for getting something unstuck

***Grenade, Fragmentation.***

***Grenade, Incendiary.***

***Grenade, Smoke.***

***Hacksaw.*** Let you cut through metal

***Hammock.***

***Helmet, Miner's.*** Protects from small falling rocks, has a candle or electric light on top.

***Ice Axe.***

***Insect Netting.***

***Insect Repellent.***

***Kite.*** A smaller kite, not the riding kind

***Lantern, Electric.*** The new name for beacon

***Laser Sight.*** Not sure what it does mechanically, but it exists in game

***Leash and Muzzle.***

***Listening Cone.*** Lets you listen through a wall

***Lockbox.*** The one you get from pickpocketing

***Map.*** Cost varies, based on detail and rarity

***Matches.*** Firestarter equivalent, for a small box of 100 

***Microscope.***

\pagebreakNum

***Paint.*** Body paint, normal paint, etc.

***Parachute.*** A humanoid wearing this piece of gear can deploy the parachute as a reaction while falling, or as an action otherwise. The parachute requires at least a 10-foot cube of unoccupied space in which to deploy, and it doesn't open fast enough to slow a fall of less than 60 feet. If it has sufficient time and space to deploy properly, the parachute allows its wearer to land without taking falling damage. Once it has been used, the parachute takes 10 minutes to repack.

***Periscope.*** Lets you peer around corners

***Pocketwatch.***

***Portable Glider.*** Breaks down for easier carrying. A vehicle instead?

***Pole, Collapsible.*** You ever try carry around a 10 foot pole? I have, when I've worked with PVC pipes. That's not something you just carry around in your backpack, and good luck trying to get anywhere without constantly smacking it into stuff

***Preserved Organ.*** Useful to Forsaken as replacement parts or a snack.

***Punchcard.*** 

***Radio.*** Not sure what level to put here. Ham radios with large broadcasting antennas? Walkie-talkies?

***Rations, Animal.*** Herbivore and carnivore varieties?

***Safe.*** A lockbox too heavy to easily move or be stolen.

***Shadow oil.*** Apply to weapons, deal necrotic damage on a hit

***Slate Board.*** Small chalkboard

***Smelling Salts.*** Wakes up nonmagically asleep creatures

***Snorkel.*** Lets you stay submerged just under the surface of the water

***Snowshoes.*** 

***Sprayer.*** Lets you spray acid/holy water in a mist

***Steam Tonk.*** Little controllable toy car. Useful distraction, or fighting other steam tonks. [Source.](https://warcraft.wiki.gg/wiki/Steam_tonk)

***Stilts.*** Sometimes goblins like to feel tall, okay?

***Suit, Fire Resistant.*** This bulky, silver-coated suit provides resistance to fire damage. As it only protects what is underneath the suit when sealed, it must be worn over any other armor or equipment to protect it.

***Suit, Ghillie.*** Adv on stealth checks in specific area and time of year, but disadvantage on other Dex checks and all melee attack rolls. Camouflague can be changed

***Suturing Kit.*** A suturing kit is a small collection of needles and threads of quasi-magical origin. A forsaken can use it to reattach severed body parts or repair damages to its body. They can also use the kit to attach body parts from other corpses to themselves, provided that the body part matches a missing part on their own body. Use of this kit usually requires a successful Wisdom (Medicine) check and takes anywhere from a couple minutes to a few hours, depending on the extent of the procedure.

***Syringe.*** Allows for applying potions or poisons to others, or more quickly.

***Tabard.***

***Table Case, Folding.*** A briefcase/small trunk that has extendable legs that you can use to make a quick little market display, for hucksters or merchants

***Tape.*** Duct tape

***Tarp.*** Endless uses

***Tea Set.***

***Tent.*** Larger/smaller varieties

***Teepee.*** Large Tauren tent.

***Tool Belt.***

***Torch, Signal.*** Burns special colors.

***Wrist Sheath, Spring-Loaded.*** Able to bring out a hidden weapon as a free action.

***Wok, Iron.*** Cooking pot for pandaren

<!-- 

\pagebreakNum


##### Container Capacity
Container               | Capacity
------------------------|-------------
Backpack                |
Barrel                  |
Basket                  |
Bottle                  |
Briefcase?              |
Bucket                  |
Chest                   |
Coffin                  |
Flask or tankard        |
Jug or pitcher          |
Pot, iron               |
Pouch                   |
Sack                    |
Vial                    |
Waterskin or canteen    |

-->

\pagebreakNum

<div class='classTable wide' >

##### Explosives and Splash Weapons
Weapon                  | Cost  | Damage        | Burst <br/> Radius  | Save DC | Range   | Weight    |
------------------------|-------|---------------|---------|---------|---------|-----------|
Bomb                    |
Dynamite                |
Fragmentation grenade   |

Weapon                  | Cost  | Direct Hit <br/> Damage | Splash <br/> Damage | Damage    | Range | Weight
------------------------|-------|-------------------------|---------------------|-----------|-------|--------
Acid        | 
Holy Water  |

</div>

#### Note
Going to move the relevant items from adventuring gear to this new section. I'm planning on bringing back some of the old rules for grenadelike weapons, such as making an attack roll against a square (AC 10), with a miss landing in an adjacent square.

<!-- 

\pagebreakNum

##### Food, Drink, and Lodging
Item                            | Cost
--------------------------------|------
Bread, half-pound loaf          | 5 cp
Farmer income, per year (grain) | 21000 cp


##### Trade Goods
Cost    | Goods
--------|-----------
5 cp | 1 lb. of flour

Farmer income

\pagebreakNum

\pagebreakNum

-->

#### Tools
Not sure how to handle these. I added in a bunch of others, like barber's and tattooist's and brewer's, but the lack of focus on the normal primary profession tools felt wrong. Primary/secondary categories? Just include the in-game profession kits?

***Hearthstone set.*** Lore idea: Developed among Dalaran apprentices. Explains the magicalness of them (built in illusions), and the centralized location would allow for tournament rules to ensure that there wouldn't be counterfeit cards that are drastically overpowered.

***[Hearthstation.](https://warcraft.wiki.gg/wiki/Hearthstation)*** A magical version of the board upon which Hearthstone is played, with built in illusions.

> ##### Equipment Packs
> We can also redesign these if needed. For example, a *dead man's pack* would be for Forsaken or death knights, who don't need to sleep or eat and thus wouldn't need rations or a bedroll. Or a pack for hunters, with treats, animal rations, and so on.

\columnbreak

##### Tools
Item                        |Cost   |Weight
----------------------------|-------|----
*Artisan's tools*       |       |
    Alchemist's supplies     | 50 gp  | 8 lb.
    Archaeology              |        |      
    Blacksmith's tools       |        |      
    Cooking                  |        |      
    Enchanting tools         |        |      
    Engineer's toolbox       |        |      
    Fishing                  |        |      
    Inscription              |        |      
    Jewelcrafting            |        |      
    Leatherworking           |        |      
    Tailoring                |        |      
Disguise kit                |25 gp  |3 lb.
Forgery kit                 |15 gp  |5 lb.
*Gaming set*                |       |
    Dice set                  |1 sp   |--
    Playing card set          |5 sp   |--
Herbalism kit               |5 gp   |3 lb.
*Musical instrument*        |       |
    Horn                      |3 gp   |2 lb.
Navigator's tools           |25 gp  |2 lb.
Poisoner's kit              |50 gp  |2 lb.
Thieves' tools              |25 gp  |1 lb.
✢ Vehicles (air, land, or water)|*    |*

<!-- 

    Archaeologist's tools    |
    Barber's tools           |
    Brewer's supplies        |
    Cook's utensils          |
    Dyer's tools             |
    Enchanter's tools        |
    Engineer's toolbox       |
    Jewelcrafter's supplies  |
    Leatherworker's tools    |
    Mason's tools            |
    Painter's supplies       |
    Smith's tools            |
    Surveyor's tools         |
    Tailor's supplies        |
    Tattooist's tools        |


\pagebreakNum


\columnbreak

\pagebreakNum

\pagebreakNum

## Tools

A tool helps you to do something you couldn't otherwise do, such as craft or repair an item, forge a document, or pick a lock. Your race, class, background, or feats give you proficiency with certain tools. Proficiency with a tool allows you to add your proficiency bonus to any ability check you make using that tool. Tool use is not tied to a single ability, since proficiency with a tool represents broader knowledge of its use. For example, the GM might ask you to make a Dexterity check to carve a fine detail with your woodcarver’s tools, or a Strength check to make something out of particularly hard wood.

***Artisan’s Tools.*** These special tools include the items needed to pursue a craft or trade. The table shows examples of the most common types of tools, each providing items related to a single craft. Proficiency with a set of artisan’s tools lets you add your proficiency bonus to any ability checks you make using the tools in your craft. Each type of artisan’s tools requires a separate proficiency.

***Disguise Kit.*** This pouch of cosmetics, hair dye, and small props lets you create disguises that change your physical appearance. Proficiency with this kit lets you add your proficiency bonus to any ability checks you make to create a visual disguise.

***Forgery Kit.*** This small box contains a variety of papers and parchments, pens and inks, seals and sealing wax, gold and silver leaf, and other supplies necessary to create convincing forgeries of physical documents. Proficiency with this kit lets you add your proficiency bonus to any ability checks you make to create a physical forgery of a document.

***Gaming Set.*** This item encompasses a wide range of game pieces, including dice and decks of cards (for games such as Hearthstone). A few common examples appear on the Tools table, but other kinds of gaming sets exist. If you are proficient with a gaming set, you can add your proficiency bonus to ability checks you make to play a game with that set. Each type of gaming set requires a separate proficiency.

***Herbalism Kit.*** This kit contains a variety of instruments such as clippers, mortar and pestle, and pouches and vials used by herbalists to create remedies and potions. Proficiency with this kit lets you add your proficiency bonus to any ability checks you make to identify or apply herbs. Also, proficiency with this kit is required to create antitoxin and potions of healing.

***Musical Instrument.*** Several of the most common types of musical instruments are shown on the table as examples. If you have proficiency with a given musical instrument, you can add your proficiency bonus to any ability checks you make to play music with the instrument. Each type of musical instrument requires a separate proficiency.

***Navigator’s Tools.*** This set of instruments is used for navigation at sea. Proficiency with navigator's tools lets you chart a ship's course and follow navigation charts. In addition, these tools allow you to add your proficiency bonus to any ability check you make to avoid getting lost at sea.

***Poisoner’s Kit.*** A poisoner’s kit includes the vials, chemicals, and other equipment necessary for the creation of poisons. Proficiency with this kit lets you add your proficiency bonus to any ability checks you make to craft or use poisons.

***Thieves’ Tools.*** This set of tools includes a small file, a set of lock picks, a small mirror mounted on a metal handle, a set of narrow-bladed scissors, and a pair of pliers. Proficiency with these tools lets you add your proficiency bonus to any ability checks you make to disarm traps or open locks.

<div class='classTable' >

##### Artisan's Tools
 
Item                        |Cost   |Weight
----------------------------|-------|----
*Artisan's tools*       |       |
    Alchemist's supplies      |50 gp  |8 lb.
    Brewer's supplies         |20 gp  |9 lb.
    Calligrapher's supplies   |10 gp  |5 lb.
    Carpenter's tools         |8 gp   |6 lb.
    Cartographer's tools      |15 gp  |6 lb.
    Cobbler's tools           |5 gp   |5 lb.
    Cook's utensils           |1 gp   |8 lb.
    Glassblower's tools       |30 gp  |5 lb.
    Jeweler's tools           |25 gp  |2 lb.
    Leatherworker's tools     |5 gp   |5 lb.
    Mason's tools             |10 gp  |8 lb.
    Painter's supplies        |10 gp  |5 lb.
    Potter's tools            |10 gp  |3 lb.
    Prospector's tools        |20 gp  |8 lb.
    Smith's tools             |20 gp  |8 lb.
    Tinker's tools            |50 gp  |10 lb.
    Weaver's tools            |1 gp   |5 lb.
    Woodcarver's tools        |1 gp   |5 lb.
Disguise kit                |25 gp  |3 lb.
Forgery kit                 |15 gp  |5 lb.
*Gaming set*                |       |
    Chess set                 |1 sp   |--
    Dice set                  |1 sp   |--
    Hearthstone set           |1 sp   |--
    Playing card set          |5 sp   |--
Herbalism kit               |5 gp   |3 lb.
*Musical instrument*        |       |
    Bagpipes                  |30 gp  |6 lb.
    Drum                      |6 gp   |3 lb.
    Dulcimer                  |25 gp  |10 lb.
    Flute                     |2 gp   |1 lb.
    Lute                      |35 gp  |2 lb.
    Lyre                      |30 gp  |2 lb.
    Horn                      |3 gp   |2 lb.
    Pan flute                 |12 gp  |2 lb.
    Shawm                     |2 gp   |1 lb.
    Viol                      |30 gp  |1 lb.
Navigator's tools           |25 gp  |2 lb.
Poisoner's kit              |50 gp  |2 lb.
Thieves' tools              |25 gp  |1 lb.
✢ Vehicles (air, land, or water)|*    |*

</div>

\pagebreakNum

## Mounts and Vehicles
A good mount can help you move more quickly through the wilderness, but its primary purpose is to carry the gear that would otherwise slow you down. The Mounts and Other Animals table shows each animal’s speed and base carrying capacity.

An animal pulling a carriage, cart, chariot, sled, or wagon can move weight up to five times its base carrying capacity, including the weight of the vehicle. If multiple animals pull the same vehicle, they can add their carrying capacity together.

Mounts other than those listed here are available in fantasy gaming worlds, but they are rare and not normally available for purchase. These include flying mounts (pegasi, griffons, hippogriffs, and similar animals) and even aquatic mounts (giant sea horses, for example). Acquiring such a mount often means securing an egg and raising the creature yourself, making a bargain with a powerful entity, or negotiating with the mount itself.

***Barding.*** Barding is armor designed to protect an animal’s head, neck, chest, and body. Any type of armor shown on the Armor table can be purchased as barding. The cost is four times the equivalent armor made for humanoids, and it weighs twice as much.

***Saddles.*** A military saddle braces the rider, helping you keep your seat on an active mount in battle. It gives you advantage on any check you make to remain mounted. An exotic saddle is required for riding any aquatic or flying mount.

***Vehicle Proficiency.*** If you have proficiency with a certain kind of vehicle (land or water), you can add your proficiency bonus to any check you make to control that kind of vehicle in difficult circumstances.

***Rowed Vessels.*** Keelboats and rowboats are used on lakes and rivers. If going downstream, add the speed of the current (typically 3 miles per hour) to the speed of the vehicle. These vehicles can’t be rowed against any significant current, but they can be pulled upstream by draft animals on the shores. A rowboat weighs 100 pounds, in case adventurers carry it over land.

##### Mounts and Other Animals
Item            | Cost  | Speed | Carrying<br>Capacity
----------------|------:|:-----:|---------:
Camel               |50 gp  |50 ft. |480 lb.
Donkey or Mule      |8 gp   |40 ft. |420 lb.
Elephant            |200 gp |40 ft. |1,320 lb.
Horse, draft        |50 gp  |40 ft. |540 lb.
Horse, riding       |75 gp  |60 ft. |480 lb.
Mastiff             |25 gp  |40 ft. |195 lb.
Pony                |30 gp  |40 ft. |225 lb.
Warhorse            |400 gp |60 ft. |540 lb.

##### Tack, Harness, and Drawn Vehicles
Item            | Cost  | Weight
----------------|------:|----------:
Barding         |x4     |x2
Bit and Bridle  |2 gp   |1 lb.
Carriage        |100 gp |600 lb.
Cart            |15 gp  |200 lb.
Chariot         |250 gp |100 lb.
Feed (per day)  |5 cp   |10 lb.
*Saddle*        |       |
    Exotic        |60 gp  |40 lb.
    Military      |20 gp  |30 lb.
    Pack          |5 gp   |15 lb.
    Riding        |10 gp  |25 lb.
Saddlebags      |4 gp   |8 lb.
Sled            |20 gp  |300 lb.
Stabling (per day)|5 sp |--
Wagon           |35 gp  |400 lb.

##### Waterborne Vehicles
Item            | Cost      | Speed
----------------|----------:|-----:
Galley          |30,000 gp  |4 mph
Keelboat        |3,000 gp   |1 mph
Longship        |10,000 gp  |3 mph
Rowboat         |50 gp      |1.5 mph
Sailing ship    |10,000 gp  |2 mph
Warship         |25,000 gp  |2.5 mph


\pagebreakNum

## Trade Goods
Most wealth is not in coins. It is measured in livestock, grain, land, rights to collect taxes, or rights to resources (such as a mine or a forest).

Guilds, nobles, and royalty regulate trade. Chartered companies are granted rights to conduct trade along certain routes, to send merchant ships to various ports, or to buy or sell specific goods. Guilds set prices for the goods or services that they control, and determine who may or may not offer those goods and services. Merchants commonly exchange trade goods without using currency. The Trade Goods table shows the value of commonly exchanged goods.

##### Trade Goods
| Cost   | Goods                                        |
|--------|----------------------------------------------|
| 1 cp   | 1 lb. of wheat                               |
| 2 cp   | 1 lb. of flour or one chicken                |
| 5 cp   | 1 lb. of salt                                |
| 1 sp   | 1 lb. of iron or 1 sq. yd. of canvas         |
| 5 sp   | 1 lb. of copper or 1 sq. yd. of cotton cloth |
| 1 gp   | 1 lb. of ginger or one goat                  |
| 2 gp   | 1 lb. of cinnamon or pepper, or one sheep    |
| 3 gp   | 1 lb. of cloves or one pig                   |
| 5 gp   | 1 lb. of silver or 1 sq. yd. of linen        |
| 10 gp  | 1 sq. yd. of silk or one cow                 |
| 15 gp  | 1 lb. of saffron or one ox                   |
| 50 gp  | 1 lb. of gold                                |
| 500 gp | 1 lb. of platinum                            |

## Expenses
When not descending into the depths of the earth, exploring ruins for lost treasures, or waging war against the encroaching darkness, adventurers face more mundane realities. Even in a fantastical world, people require basic necessities such as shelter, sustenance, and clothing. These things cost money, although some lifestyles cost more than others.

### Lifestyle Expenses
Lifestyle expenses provide you with a simple way to account for the cost of living in a fantasy world. They cover your accommodations, food and drink, and all your other necessities. Furthermore, expenses cover the cost of maintaining your equipment so you can be ready when adventure next calls.

At the start of each week or month (your choice), choose a lifestyle from the Expenses table and pay the price to sustain that lifestyle. The prices listed are per day, so if you wish to calculate the cost of your chosen lifestyle over a thirty-day period, multiply the listed price by 30. Your lifestyle might change from one period to the next, based on the funds you have at your disposal, or you might maintain the same lifestyle throughout your character’s career.

Your lifestyle choice can have consequences. Maintaining a wealthy lifestyle might help you make contacts with the rich and powerful, though you run the risk of attracting thieves. Likewise, living frugally might help you avoid criminals, but you are unlikely to make powerful connections.

\columnbreak

##### Lifestyle Expenses

| Lifestyle    | Price/Day     |
|--------------|---------------|
| Wretched     | —             |
| Squalid      | 1 sp          |
| Poor         | 2 sp          |
| Modest       | 1 gp          |
| Comfortable  | 2 gp          |
| Wealthy      | 4 gp          |
| Aristocratic | 10 gp minimum |

***Wretched.*** You live in inhumane conditions. With no place to call home, you shelter wherever you can, sneaking into barns, huddling in old crates, and relying on the good graces of people better off than you. A wretched lifestyle presents abundant dangers. Violence, disease, and hunger follow you wherever you go. Other wretched people covet your armor, weapons, and adventuring gear, which represent a fortune by their standards. You are beneath the notice of most people.

***Squalid.*** You live in a leaky stable, a mud-floored hut just outside town, or a vermin-infested boarding house in the worst part of town. You have shelter from the elements, but you live in a desperate and often violent environment, in places rife with disease, hunger, and misfortune. You are beneath the notice of most people, and you have few legal protections. Most people at this lifestyle level have suffered some terrible setback. They might be disturbed, marked as exiles, or suffer from disease.

***Poor.*** A poor lifestyle means going without the comforts available in a stable community. Simple food and lodgings, threadbare clothing, and unpredictable conditions result in a sufficient, though probably unpleasant, experience. Your accommodations might be a room in a flophouse or in the common room above a tavern. You benefit from some legal protections, but you still have to contend with violence, crime, and disease. People at this lifestyle level tend to be unskilled laborers, costermongers, peddlers, thieves, mercenaries, and other disreputable types.

***Modest.*** A modest lifestyle keeps you out of the slums and ensures that you can maintain your equipment. You live in an older part of town, renting a room in a boarding house, inn, or temple. You don’t go hungry or thirsty, and your living conditions are clean, if simple. Ordinary people living modest lifestyles include soldiers with families, laborers, students, priests, hedge wizards, and the like.

***Comfortable.*** Choosing a comfortable lifestyle means that you can afford nicer clothing and can easily maintain your equipment. You live in a small cottage in a middle-class neighborhood or in a private room at a fine inn. You associate with merchants, skilled tradespeople, and military officers.

***Wealthy.*** Choosing a wealthy lifestyle means living a life of luxury, though you might not have achieved the social status associated with the old money of nobility or royalty. You live a lifestyle comparable to that of a highly successful merchant, a favored servant of the royalty, or the owner of a few small businesses. You have respectable lodgings, usually a spacious home in a good part of town or a comfortable suite at a fine inn. You likely have a small staff of servants.

\pagebreakNum

***Aristocratic.*** You live a life of plenty and comfort. You move in circles populated by the most powerful people in the community. You have excellent lodgings, perhaps a townhouse in the nicest part of town or rooms in the finest inn. You dine at the best restaurants, retain the most skilled and fashionable tailor, and have servants attending to your every need. You receive invitations to the social gatherings of the rich and powerful, and spend evenings in the company of politicians, guild leaders, high priests, and nobility. You must also contend with the highest levels of deceit and treachery. The wealthier you are, the greater the chance you will be drawn into political intrigue as a pawn or participant.

### Food, Drink, and Lodging

The Food, Drink, and Lodging table gives prices for individual food items and a single night’s lodging. These prices are included in your total lifestyle expenses.

##### Food, Drink, and Lodging

| Item                 | Cost  |
|----------------------|-------|
| *Ale*                |       |
|     Gallon           | 2 sp  |
|     Mug              | 4 cp  |
| Banquet (per person) | 10 gp |
| Bread, loaf          | 2 cp  |
| Cheese, hunk         | 1 sp  |
| *Inn stay (per day)* |       |
|     Squalid          | 7 cp  |
|     Poor             | 1 sp  |
|     Modest           | 5 sp  |
|     Comfortable      | 8 sp  |
|     Wealthy          | 2 gp  |
|     Aristocratic     | 4 gp  |
| *Meals (per day)*    |       |
|     Squalid          | 3 cp  |
|     Poor             | 6 cp  |
|     Modest           | 3 sp  |
|     Comfortable      | 5 sp  |
|     Wealthy          | 8 sp  |
|     Aristocratic     | 2 gp  |
| Meat, chunk          | 3 sp  |
| *Wine*               |       |
|     Common (pitcher) | 2 sp  |
|     Fine (bottle)    | 10 gp |

\columnbreak

> ##### Self-Sufficiency
> 
> The expenses and lifestyles described here assume that you are spending your time between adventures in town, availing yourself of whatever services you can afford—paying for food and shelter, paying townspeople to sharpen your sword and repair your armor, and so on. Some characters, though, might prefer to spend their time away from civilization, sustaining themselves in the wild by hunting, foraging, and repairing their own gear.
> 
> Maintaining this kind of lifestyle doesn’t require you to spend any coin, but it is time-consuming. If you spend your time between adventures practicing a profession, you can eke out the equivalent of a poor lifestyle. Proficiency in the Survival skill lets you live at the equivalent of a comfortable lifestyle.

### Services

Adventurers can pay nonplayer characters to assist them or act on their behalf in a variety of circumstances. Most such hirelings have fairly ordinary skills, while others are masters of a craft or art, and a few are experts with specialized adventuring skills.

Some of the most basic types of hirelings appear on the Services table. Other common hirelings include any of the wide variety of people who inhabit a typical town or city, when the adventurers pay them to perform a specific task. For example, a mage might pay a carpenter to construct an elaborate chest (and its miniature replica) for use in the *secret chest* spell. A warrior might commission a blacksmith to forge a special sword. A rogue might pay a tailor to make exquisite clothing for an infiltration of a fancy party.

Other hirelings provide more expert or dangerous services. Mercenary soldiers paid to help the adventurers take on a gnoll army are hirelings, as are sages hired to research ancient or esoteric lore. If a high-level adventurer establishes a stronghold of some kind, he or she might hire a whole staff of servants and agents to run the place, from a castellan or steward to menial laborers to keep the stables clean. These hirelings often enjoy a long-term contract that includes a place to live within the stronghold as part of the offered compensation.

Skilled hirelings include anyone hired to perform a service that involves a proficiency (including weapon, tool, or skill): a mercenary, artisan, scribe, and so on. The pay shown is a minimum; some expert hirelings require more pay. Untrained hirelings are hired for menial work that requires no particular skill and can include laborers, porters, maids, and similar workers.

\pagebreakNum
##### Services

| Service Pay       |               |
|-------------------|---------------|
| *Coach cab*       |               |
|     Between towns | 3 cp per mile |
|     Within a city | 1 cp          |
| *Hireling*        |               |
|     Skilled       | 2 gp per day  |
|     Untrained     | 2 sp per day  |
| Messenger         | 2 cp per mile |
| Road or gate toll | 1 cp          |
| Ship’s passage    | 1 sp per mile |

### Spellcasting Services

People who are able to cast spells don’t fall into the category of ordinary hirelings. It might be possible to find someone willing to cast a spell in exchange for coin or favors, but it is rarely easy and no established pay rates exist. As a rule, the higher the level of the desired spell, the harder it is to find someone who can cast it and the more it costs.

Hiring someone to cast a relatively common spell of 1st or 2nd level, such as *cure wounds* or *identify*, is easy enough in a city or town, and might cost 10 to 50 gold pieces (plus the cost of any expensive material components). Finding someone able and willing to cast a higher-level spell might involve traveling to a large city, perhaps one with a university or prominent temple. Once found, the spellcaster might ask for a service instead of payment—the kind of service that only adventurers can provide, such as retrieving a rare item from a dangerous locale or traversing a monster-infested wilderness to deliver something important to a distant settlement.


\pagebreakNum


#### d20 Modern Stuff

> Walkie-Talkie
> This hand-held radio transceiver communicates with any similar device operating on the same frequency and within range.
> 
> Basic: This dime-store variety has only a few channels. Anyone else using a similar walkie-talkie within range can listen in on the character’s conversations. It has a range of 2 miles.
> 
> Professional: This high-end civilian model allows a character to program in twenty different frequencies from thousands of choices—making it likely that the character can find a frequency that’s not being used by anyone else within range. The device can be used with or without a voice-activated headset (included). It has a range of 15 miles.

> Night Vision Goggles
> Night vision goggles use passive light gathering to improve vision in near-dark conditions. They grant the user the ability to see in darkness, also called darkvision (range 120 ft.)—but because of the restricted field of view and lack of depth perception these goggles provide, they impose a –4 penalty on all Spot and Search checks made by someone wearing them.
> 
> Night vision goggles must have at least a little light to operate. A cloudy night provides sufficient ambient light, but a pitch-black cave or a sealed room doesn’t. For situations of total darkness, the goggles come with an infrared illuminator that, when switched on, operates like a standard flashlight whose light is visible only to the wearer (or anyone else wearing night vision goggles).

> Concertina Wire
> So named because it folds up like a squeezebox, concertina wire is the latest generation of barbed wire. It comes in 20-foot-long rolls that are stretch across the surface or fence to be protected. For each 2-foot section that a person tries to cross, he or she must make a Reflex save (DC 15) or take 1d6 points of damage (save for half). Concertina wire has hardness 2, 5 hp, and can only be damaged by slashing weapons or cut with a tool like boltcutters.

> Duct Tape
> The usefulness of duct tape is limited only by a character’s imagination. Duct tape can support up to 200 pounds indefinitely, or up to 300 pounds for 1d6 rounds. Characters bound with duct tape must make a Strength or Escape Artist check (DC 20) to free themselves.
> 
> A roll provides 70 feet of tape, 2 inches wide.

> Glasscutter, Circular
> This special device allows a person to cut through glass panes without cracking or shattering them in the process. It fits onto the glass with a suction cup and has a rotating arm that cuts a hole from 3 to 12 inches in diameter. Once the hole is cut, the suction cup is tugged, pulling out the circle of glass. The user makes a Dexterity check (DC 10) to create a hole without shattering the glass. If the check fails, the glass shatters with a loud crash.

> Road Flare
> Road flares are small chemical sticks that produce a brilliant red light. They are lit by striking the cap against the stick. A road flare lasts for an hour before being completely consumed and fills a 5-foot square with flickering red light. Anyone struck with a road flare takes 1d6 points of fire damage. Road flares are sold in packs of three.

> Skis and Snowboards
> For game purposes, skis and snowboards operate the same way. When moving downhill on snow or icy terrain, the character’s speed increases by an additional 30 feet per move action (20 feet when using cross-country skis on more-or-less level terrain). A person can only move at half speed while using skis up a slope. Any time the character performs some sort of fancy maneuver, he must make a Balance check (DC 15). The DC can increase based on how difficult a maneuver he is attempting. A failed check means that he falls, taking damage as if he fell 10 feet vertically for every 20 feet of movement. If the character is skiing on fresh snow, this damage is reduced by one die. Ski poles can be used as impromptu weapons.

> Binoculars
> Binoculars are useful for watching opponents, wild game, and sporting events from a long distance.
> 
> Standard: Standard binoculars reduce the range penalty for Spot checks to –1 for every 50 feet (instead of –1 for every 10 feet). Using binoculars for Spot checks takes five times as long as making the check unaided.
> 
> Rangefinding: In addition to the benefit of standard binoculars, rangefinding binoculars include a digital readout that indicates the exact distance to the object on which they are focused.
> 
> Electro-Optical: Electro-optical binoculars function the same as standard binoculars in normal light. In darkness, however, users looking through them see as if they had the darkvision ability granted by night vision goggles.

\pagebreakNum

> Chemical Light Stick
> This disposable plastic stick, when activated, uses a chemical reaction to create light for 6 hours. It illuminates an area only 5 feet in radius. Once activated, it can’t be turned off or reused. The listed purchase DC is for a pack of 5 sticks.

> Fire Extinguisher
> This portable apparatus uses a chemical spray to extinguish small fires. The typical fire extinguisher ejects enough extinguishing chemicals to put out a fire in a 10-foot-by-10-foot area as a move action. It contains enough material for two such uses.

> Flash Goggles
> These eye coverings provide total protection against blinding light.

> Flashlight
> Flashlights come in a wide variety of sizes and quality levels. Those covered here are professional, heavy-duty models, rugged enough to withstand the rigors of modern adventuring. Flashlights negate penalties for darkness within their illuminated areas.
> 
> Penlight: This small flashlight can be carried on a key ring. It projects a beam of light 10 feet long and 5 feet wide at its end.
> 
> Standard: This heavy metal flashlight projects a beam 30 feet long and 15 feet across at its end.
> 
> Battery Flood: Practically a handheld spotlight, this item projects a bright beam 100 feet long and 50 feet across at its end.

> Gas Mask
> This apparatus covers the face and connects to a chemical air filter canister to protect the lungs and eyes from toxic gases. It provides total protection from eye and lung irritants. The filter canister lasts for 12 hours of use. Changing a filter is a move action. The purchase DC for one extra filter canister is 6.

> Portable Stove
> This small stove works on kerosene or white gasoline, and can easily be broken down and carried for backpacking.

> Detonator
A detonator activates an explosive, causing it to explode. The device consists of an electrically activated blasting cap and some sort of device that delivers the electrical charge to set off the blasting cap. Connecting a detonator to an explosive requires a Demolitions check (DC 15). Failure means that the explosive fails to go off as planned. Failure by 10 or more means the explosive goes off as the detonator is being installed.
> 
> Blasting Cap: This is a detonator without a built-in controller. It can be wired into any electrical device, such as a light switch or a car’s ignition switch, with a Demolitions check (DC 10). When the electrical device is activated, the detonator goes off.
> 
> Radio Control: This device consists of two parts: the detonator itself and the activation device. The activation device is an electronic item about the size of a deck of cards, with an antenna, a safety, and an activation switch. When the switch is toggled, the activation device sends a signal to the detonator by radio, setting it off. It has a range of 500 feet.
> 
> Timed: This is an electronic timer connected to the detonator. Like an alarm clock, it can be set to go off at a particular time.
> 
> Wired: This is the simplest form of detonator. The blasting cap connects by a wire to an activation device, usually a small pistol-grip device that the user squeezes. The detonator comes with 100 feet of wire, but longer lengths can be spliced in with a Demolitions check (DC 10).

> Holster
> Holsters are generally available for all Medium-size or smaller firearms.
> 
> Hip: This holster holds the weapon in an easily accessed—and easily seen—location.
> 
> Concealed Carry: A concealed carry holster is designed to help keep a weapon out of sight (see Concealed Weapons and Objects). In most cases, this is a shoulder holster (the weapon fits under the wearer’s armpit, presumably beneath a jacket). Small or Tiny weapons can be carried in waistband holsters (often placed inside the wearer’s waistband against his or her back). Tiny weapons can also be carried in ankle or boot holsters.

> Illuminator
> An illuminator is a small flashlight that mounts to a firearm, freeing up one of the user’s hands. It functions as a standard flashlight.

> Laser Sight
> This small laser mounts on a firearm, and projects a tiny red dot on the weapon’s target. A laser sight grants a +1 equipment bonus on all attack rolls made against targets no farther than 30 feet away. However, a laser sight can’t be used outdoors during the daytime.

\pagebreakNum

> Scope
> A scope is a sighting device that makes it easier to hit targets at long range. However, although a scope magnifies the image of the target, it has a very limited field of view, making it difficult to use.
> 
> Standard: A standard scope increases the range increment for a ranged weapon by one-half (multiply by 1.5). However, to use a scope a character must spend an attack action acquiring his or her target. If the character changes targets or otherwise lose sight of the target, he or she must reacquire the target to gain the benefit of the scope.
> 
> Electro-Optical: An electro-optical scope functions the same as a standard scope in normal light. In darkness, however, the user sees through it as if he or she had the darkvision ability granted by night vision goggles.

> Speed Loader
> A speed loader holds a number of bullets in a ring, in a position that mirrors the chambers in a revolver cylinder. Using a speed loader saves time in reloading a revolver, since a character can insert all the bullets at once.

> Suppressor
> A suppressor fits on the end of a firearm, capturing the gases traveling at supersonic speed that propel a bullet as it is fired. This eliminates the noise from the bullet’s firing, dramatically reducing the sound the weapon makes when it is used. For handguns, the only sound is the mechanical action of the weapon (Listen check, DC 15, to notice). For longarms, the supersonic speed of the bullet itself still makes noise. However, it’s difficult to tell where the sound is coming from, requiring a Listen check (DC 15) to locate the source of the gunfire.
> 
> Modifying a weapon to accept a suppressor requires a Repair check (DC 15). Once a weapon has been modified in this manner, a suppressor can be attached or removed as a move action.
> 
> Suppressors cannot be used on revolvers or shotguns. A suppressor purchased for one weapon can be used for any other weapon that fires the same caliber of ammunition.

> Flamethrower
> A flamethrower consists of a pressurized backpack containing fuel, connected to a tube with a nozzle. It shoots a 5-foot-wide, 30-foot-long line of flame that deals 3d6 points of fire damage to all creatures and objects in its path. No attack roll is necessary, and thus no feat is needed to operate the weapon effectively. Any creature caught in the line of flame can make a Reflex save (DC 15) to take half damage. Creatures with cover get a bonus on their Reflex save.
> 
> A flamethrower’s backpack has hardness 5 and 5 hit points. When worn, the backpack has a Defense equal to 9 + the wearer’s Dexterity modifier + the wearer’s class bonus. A backpack reduced to 0 hit points ruptures and explodes, dealing 6d6 points of fire damage to the wearer (no save allowed) and 3d6 points of splash damage to creatures and objects in adjacent 5-foot squares (Reflex save, DC 15, for half damage).
> 
> Any creature or flammable object that takes damage from a flamethrower catches on fire, taking 1d6 points of fire damage each subsequent round until the flames are extinguished. A fire engulfing a single creature or object can be doused or smothered as a full-round action. Discharging a fire extinguisher is a move action and instantly smothers flames in a 10-foot-by-10-foot area.
> 
> A flamethrower can shoot 10 times before the fuel supply is depleted. Refilling or replacing a fuel pack has a purchase DC of 13.

> Bolas
> A bolas consists of two or more wooden spheres connected by lengths of cord. The bolas is a ranged weapon that can be used to entangle a Small or larger opponent. First, you make a ranged touch attack against the target. The target must be at least 10 feet away, as the bolas cannot be used against adjacent opponents. If the attack roll succeeds, the target is entangled. A target can free itself from the bolas as a full-round action or make an Escape Artist check (DC 15) on its turn to escape from the bolas as an attack action. The bolas has 5 hit points and can be broken with a successful Strength check (DC 20) as a full-round action.
> 
> If you entangle a creature with the bolas, you may attempt to trip it on your next attack. A failed trip with bolas does not allow the target to make a trip attack against you.

\pagebreakNum

> Crossbow, Grapple-Firing
> This device helps heroes scale unclimbable walls, bridge chasms, escape down buildings, and the like. A grapplefiring crossbow is a heavy crossbow modified to fire a special, grapple-headed metal bolt attached to 100 feet of thin, light line.
> 
> A successful shot at an appropriate target indicates that the grapple has hooked onto something, anchoring the rope firmly enough for a character to ascend it with a successful Climb check (DC 15). Failure brings one of three results: the grapple simply failed to snag anything, it has lodged but is not secure enough to support a character’s weight, or there’s simply nothing up there for it to catch onto. In the first case, the user can simply recoil the rope and try again. In the second case, a successful Intelligence check (DC 10) made before anyone tries to climb reveals the instability. The user cannot free that grapple but may try to fire another. (Should anyone try to climb the unstable rope, the grapple gives way after the climber has progressed 2d10 feet. Determine damage normally for the resulting fall.) In the third case, retries automatically fail.
> 
> A character can easily anchor a grapple-bolt by hand in a niche or use pitons to secure it on smooth stone. This provides the same aid for descent without the need to fire the weapon.

> Flare Gun
> Normally used as a signaling device, a flare gun can be used as a weapon in a pinch. If fired in the air, it releases a brightly colored flame that can be seen for miles, depending on surrounding terrain. A flare gun automatically ignites flammable items.

> Net Launcher
> This is a bulky, compressed air rifle with a conical muzzle that throws a weighted net when fired. Police and animal control personnel use net launchers, as well as big game hunters and the occasional field researcher hoping to bag a live Shadow creature.
> 
> Net launchers have a much greater range than a regular thrown net. It takes 10 minutes to reset a net that was previously fired or 1 minute to set the net launcher with a prepackaged net (purchase DC 6, 2 lb. per package).

> Speargun
> A speargun uses a powerful set of bands to propel a stainless steel shaft at the target. Most speargun shafts are tied to a thin, strong line (DC 20 Strength check to break). This line is attached to a reel, allowing the shooter to draw the shaft back.
> 
> If you deal damage to your opponent, the shaft may lodge in the victim if the victim fails a Reflex saving throw against a DC equal to 10 + the damage dealt. The creature moves at only half speed and cannot charge or run while a spear is lodged in its body. If you control the trailing rope by succeeding at an opposed Strength check while holding it, the harpooned creature can only move within the limits that the rope allows (the trailing rope is 30 feet long). If the speared creature attempts to cast a spell, it must succeed at a Concentration check (DC 15) or the spell fails.
> 
> The speared creature can pull the shaft from its wound if it takes a full-round action, but in so doing it deals 2d6 points of damage to itself. Reloading a speargun is a full-round action.

> Acid, Mild
> A character can throw a flask of acid as a grenadelike weapon. A flask is made of ceramic, metal, or glass (depending on the substance it has to hold), with a tight stopper, and holds about 1 pint of liquid. This entry represents any mild caustic substance. Acid may be purchased in many places, including hardware stores.

> Molotov Cocktail
> A Molotov cocktail is a flask containing a flammable liquid, plugged with a rag. A Molotov cocktail is easily made by hand (Craft [chemical] check DC 10 or Intelligence check DC 15). The purchase DC given is for the components. To use it, the rag must first be lit, requiring a move action (and a lighter or other source of flame). The cocktail detonates in 2 rounds or on impact with a solid object, whichever comes first. A target that takes a direct hit is dealt an additional 1d6 points of fire damage in the following round and risks catching on fire.

\pagebreakNum

> ARCANOBOTS Action Figure
> ARCANOBOTS action figures are durable, articulated, collectible robots powered by magic (though to most of the world, this is just marketing hyperbole). When powered by magic batteries (as opposed to normal batteries), they respond to the verbal commands of their owners. They come equipped with pop-out jet wings and miniature “death ray” guns that deal light sonic/ concussion damage (unless powered by normal batteries, in which case they fire harmless beams of light).
> 
> An ARCANOBOT filled with magic batteries operates for 24 hours, at which point it becomes an inanimate, normal toy.
> 
> Magic batteries can be obtained from the manufacturer’s web site (purchase DC 36); most visitors to the web site (who don’t recognize the arcanobots’ true magical nature) assume that the high-cost “magic” batteries are a joke or publicity stunt. Only those with a true understanding of Shadow are likely to pay the price to unlock the Arcanobots actual potential. An ARCANOBOT action figure has the following statistics:
> 
> Arcanobot: CR 1/4; Diminutive construct; HD 1/8d10; hp 1; Mas —; Init +3; Spd 10 ft., fly 30 ft. (good); Defense 17, touch 17, flat-footed 14 (+3 Dex, +4 size); BAB +0; Grap –16; Atk +0 melee (1d2–4 nonlethal, unarmed strike) or +3 ranged touch (1d3 sonic/concussion, “death ray”); Full Atk +0 melee (1d2–4 nonlethal, unarmed strike) or +3 ranged touch (1d3 sonic/concussion, “death ray”); FS 1 ft. by 1 ft.; Reach 0 ft.; SQ darkvision 60 ft., construct immunities; AL creator or owner; SV Fort +0, Ref +3, Will –5; AP 0; Rep +0; Str 3, Dex 16, Con —, Int —, Wis 1, Cha 1.
> 
> Type:Wondrous Item (magic); Caster Level: 10th; Purchase DC: 5 (does not include magic batteries); Weight: 1 lb.

> Fuel Tablets
These amber-colored tablets come in bottles of ten. Each fuel tablet transforms into liquid or gaseous fuel (gasoline, diesel, kerosine, jet fuel, or propane) when dropped into the fuel tank of a vehicle or other machine. The fuel completely fills the tank, but is otherwise like regular fuel and is destroyed once used.
> 
> Type: Wondrous Item (magic); Caster Level: 3rd; Purchase DC: 29 (per bottle); Weight: —.

> Instant Ice Box
> This item looks like an ordinary 1-foot-wide, 3-foot-long, and 1.5-foot-deep picnic cooler with a 2-inch-thick plastic cover. The only apparent difference are the three buttons on the hasp. When the lid is closed and one or more of the buttons are pressed, the instant ice box will magically cool any materials placed inside for as long as the lid remains closed. If the lid is opened, the effect ends. The cooler has a total of 50 charges that can be spent in three different ways.
> 
> Chill (uses 1 charge): If any one of the buttons is pressed, the box chills all the contents to a temperature of 40°F (4.5°C), as though placed in a domestic refrigerator.
> 
> Preserve (uses 2 charges): If any two of the buttons are pressed, the box chills all the contents to a temperature of 0°F (–18°C), as though placed in a domestic freezer.
> 
> Freeze (uses 3 charges): If all three buttons are pressed, the box chills all the contents to a temperature of –27°F (–32.75°C), about the temperature used for storing freeze-dried medical supplies.
> 
> An instant ice box drained of all charges functions as an ordinary cooler.
> 
> Type: Wondrous Item (magic); Caster Level: 7th; Purchase DC: 33; Weight: 5 lb.

> Magic Billiard-Ball
> Once per day, this otherwise normal looking toy Magic Billiard-ball can be used to cast augury (as by a 5th-level Acolyte). To activate this ability, the user must state the question out loud and shake the Magic Billiard-ball. It provides no answers whatsoever if used more than once in a 24-hour period.
> 
> Type: Wondrous Item (magic); Caster Level: 3rd; Purchase DC: 30; Weight: —.

> Pen of Invisible Ink
> This pen looks like an old-fashioned calligraphy stylus, but contains its own magical supply of black ink. Any letter printed with this pen appears normal until the user speaks a name and blows upon the paper. Once spoken, the ink fades and can only be viewed by the person who was stated at the time of writing. If the name is not specific, then anyone with the same name will be able to read the message as normal.
> 
> A read magic spell will indicate that invisible ink has been used, but will not reveal the message. It is possible to create a nonmagical chemical compound (Craft [chemical] check, DC 25) that, when spread over the surface of the paper, reveals the message written in invisible ink.
> 
> A pen of invisible ink holds enough ink for 50 messages.
> 
> Type: Wondrous Item (magic); Caster Level: 3rd; Purchase DC: 29; Weight: —.

> Six-Demon Bag
> So long as the bag remains bound, the possessor gains a +1 luck bonus on all saves. Opening or sealing the bag is a move action that provokes attacks of opportunity.
> 
> Inside the bag are six small stones. Each stone can be hurled up to 60 feet, exploding at any point within range as designated by the possessor. Each stone releases a 15-foot-radius burst of energy or shrapnel that deals 5d6 points of damage, or half damage if a Reflex save (DC 15) succeeds.
> 
> Stone of Acid Rain: This stone releases a burst of acid.
> Stone of Earth: This stone releases a burst of stony shards that deals slashing damage.
> Stone of Fire: This stone releases a burst of fire.
> Stone of Hail: This stone releases a burst of cold.
> Stone of Lightning: This stone releases a burst of electricity.
> Stone of Thunder: This stone releases a burst of sonic/concussion energy.
> Once all six stones are thrown, the six-demon bag loses all of its magic properties.
> 
> Type: Wondrous Item (magic); Caster Level: 5th; Purchase DC: 34; Weight: —.


https://www.dandwiki.com/wiki/Athame_(5e_Equipment)

Weapon (dagger), common

A knife made from materials of symbolic importance, and frequently engraved with mystical artwork. Used in ceremonial magic to draw circles or prepare ritual ingredients

You may use this dagger as a spell focus.

Ritual Offering. When you cast a spell as a ritual, you may draw an insignificant quantity of your own blood and spread it across the blade. Doing so allows you to use the spell's normal casting time, rather than adding 10 minutes to it. Once you use this benefit, you can't do so again until you finish a long rest. 

-->