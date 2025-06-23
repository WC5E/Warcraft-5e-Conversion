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
  .phb:last-child:after {
    display: none;
  }
  .phb#p1:after {
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

<!-- SPLASH IMAGE -->
<img src='https://www.gmbinder.com/images/0PdNsAt.jpg' style='position:absolute; top:-80px; right:-500px; width:2000px' />

<!-- LOGO IMAGE -->
<img src='https://www.gmbinder.com/images/0fKd9bC.png' style='position:absolute; top:80px; right:40px; width:700px' />

<!-- RED DIVIDER LINE -->
<img src='https://www.gmbinder.com/images/SGYtcP2.png' style='position:absolute; top:190px; right:90px; width:580px' />

<!-- HEADER TEXT -->
<div class='cover-header'> <div style='margin-top:115px;'></div> Heroes Handbook </div>

<!-- HOMEBREW FLAG -->
<div class='cover-splotch'></div>

<!-- FOOTER TEXT -->
<img src='https://www.gmbinder.com/images/KXbAfyN.png' style='position:absolute; top:980px; right:56px; width:700px' />

\pagebreak

## Credits
*Contributors listed by community usernames.*
<div style='margin-top:-20px;'></div>

<br> **Original Creators:** Jih, TangerineThunder

<br> **Current Contributors:** Ace Azzermeen, Geamros, 
<br><span style="margin-left:12px"></span> Lorestalker Nemzal, MagusRogue, MythMaker, Nagash, 
<br><span style="margin-left:12px"></span> Llamadom, Tangerine, Tyloris

<br> **Former Contributors:** 123jrf, ApolloLumina, Artipo, 
<br><span style="margin-left:12px"></span> Auvreannia, Christinekn, ClockWorkTank, Elenus, Jih,
<br><span style="margin-left:12px"></span> Prometheus, Reiga, Silverblade, Tseims, Wyken

<br> **WIth Big Thanks To:** Our Discord community ♥

<br> **Cover Illustrator:** Kan Liu
<br> **Interior Illustrators:** Aaron Lovett, Adel Khanov, Alex 
<br><span style="margin-left:12px"></span> Garner, Anastasiya Gafron, Anna Pazyniuk, Anthony 
<br><span style="margin-left:12px"></span> Avon, Artlon, Astri Lohne, Bren Rodri, Brian Huang,
<br><span style="margin-left:12px"></span> Conner Sheehan, Dan Scott, Dariia Kasimova, Dmitry 
<br><span style="margin-left:12px"></span> Vernygor, Frenone, Glenn Rane, Grace Liu, Howard Pak,
<br><span style="margin-left:12px"></span> Ina Wong, James Ryman, Jason Wang, Jerry Mascho, 
<br><span style="margin-left:12px"></span> Jimmy Lo, Jojo So, Jorge Jacinto, Juhani Jokinen, 
<br><span style="margin-left:12px"></span> LieSetiawanKatrina Toxicpanda, Krysdecker, Liuhao, 
<br><span style="margin-left:12px"></span> Lowly Owly, Matthew Mckeown, Nagli, Nina Ikävalko, 
<br><span style="margin-left:12px"></span> Nosfer, PersonalAmi, Peet Cooper, Peter Lee, Phillip
<br><span style="margin-left:12px"></span> Zhang, Richard Suwono, Robin Olausson, Rogier van de 
<br><span style="margin-left:12px"></span> Beek, Ryan Metcalf, Tim Gou, Tyler Justice Shamanguli, 
<br><span style="margin-left:12px"></span> Shanton Feng, Shuzong, Syncmax, Tyson Murphy, 
<br><span style="margin-left:12px"></span> Unidcolor, Wei Wang

<br> **Based on the original D&D game created by**
<br><span style="margin-left:12px"></span> E. Gary Gygax and Dave Arneson, as well as Brian
<br><span style="margin-left:12px"></span> Blume, Rob Kuntz, James Ward and Don Kaye.

<br> **Based on the Warcraft franchise by**
<br><span style="margin-left:12px"></span> © Blizzard Entertainment

<br> **Playtesting provided by**
<br> **Special thanks to** 
<br><span style="margin-left:12px"></span> This entire book was made using GM Binder. It is an
<br><span style="margin-left:12px"></span> amazing tool for creating authentic-looking homebrew
<br><span style="margin-left:12px"></span> material for 5th Edition Dungeons and Dragons. Without
<br><span style="margin-left:12px"></span> it, this project would've likely never been considered.

<div style='margin-top:14px'></div>
<div style="text-align:Center">

<img src='https://www.gmbinder.com/images/yiRpC5m.png' style='width:150px' />

##### [www.GmBinder.com](https://www.gmbinder.com/)
</div>

<div style='margin-top:1000px'></div>
<div style="text-align:Right"> 

## Foreword </div>
We've made this book in an attempt to bring the beloved Warcraft franchise into the 5th edition of D&D. It is a task that has taken us months to do, and it'll likely take many more still. Everyone involved are working this in their spare time, aiming to bring a genuine recreation of *Warcraft* as a D&D 5th Edition tabletop RPG.

This book is made to compliment official D&D 5th edition books, including the **Player's Handbook, Dungeon Master's Guide**, and **Monster Manual**. It has been built on the framework set by those books, and designed to be brought in as any supplement book would. Without any more work than to just use the material presented.

It has been written with the intention of always being a free resource for everyone to use. Never to be bought or paid for. We've made this because we want others to enjoy the Warcraft universe under D&D 5th Edition rules. Not for any monetary gain.

With each coming update, all changes will be noted in the Changelog — Link is provided below.
<div style='margin-top:-5px;'></div>
<div style="text-align:Center"> 

#### [ChangeLog](https://drive.google.com/open?id=1AtTF7o6sAZZLxA75oa-96ENNNBMAJ-z7m9Y93uk4b8A)
</div>

<br> **Our Other Projects**
<br><span style="margin-left:12px"></span> Did you know that we have a Manual of Monsters as well
<br><span style="margin-left:12px"></span> to go alongside the Heroes Handbook? A fully fleshed-out
<br><span style="margin-left:12px"></span> Dungeon Master's book, bringing many of monsters with
<br><span style="margin-left:12px"></span> it from the World of Warcraft! 
<div style='margin-top:-5px;'></div>
<div style="text-align:Center"> 

#### [Project Folder](https://drive.google.com/open?id=1kVoAMR8TiO3CXFYcigFN2B6zk62xcnv9)
</div>

<br> **Want to help grow a community?**
<br><span style="margin-left:12px"></span> We're a relatively small group working together on this, 
<br><span style="margin-left:12px"></span> and as such our ability to playtest all of it is limited. 
<br><span style="margin-left:12px"></span> If you want to help the project out and give feedback,
<br><span style="margin-left:12px"></span> suggest changes and new features for the books, or 
<br><span style="margin-left:12px"></span> simply just join our growing Warcraft RPG community, 
<br><span style="margin-left:12px"></span> we have both an active discord server and a subreddit 
<br><span style="margin-left:12px"></span> dedicated to this project! — Links below!
<div style='margin-top:-5px;'></div>
<div style="text-align:Center"> 

#### [Discord Server](https://discord.gg/dKMJmmD) <span style="margin-left:48px"></span> [Subreddit](https://old.reddit.com/r/wc5e/)
</div>

<div class='wide'> 
<div style='margin-top:-90px;'></div>

#### Legal Stuff
DUNGEONS & DRAGONS, D&D, Wizards of the Coast, Forgotten Realms, Ravenloft, Eberron, the dragon ampersand, Ravnica and all other Wizards of the Coast product names, and their respective logos are trademarks of Wizards of the Coast in the USA and other countries.

<br> 

</div>

\pagebreakNum

<div style="text-align: Center">

# Table of Contents
</div>

<div class='toc'>

- ### [<span>4</span><span>Part I: Heroes                                    </span>](#p4)
  - #### [<span>5</span><span>Chapter 1: Races                               </span>](#p5)
     - [<span>5</span><span>Choosing a Side                                  </span>](#p5)
     - [<span>6</span><span>Choosing a Race                                  </span>](#p6)
     - [<span>6</span><span>Languages                                        </span>](#p6)
     - [<span>7</span><span>*Races of the Alliance*                          </span>](#p7)
       - [<span>8</span><span>Human                                          </span>](#p8)
       - [<span>10</span><span>Dwarf                                         </span>](#p10)
       - [<span>12</span><span>Night Elf                                     </span>](#p12)
       - [<span>15</span><span>Gnome                                         </span>](#p14)
       - [<span>16</span><span>Draenei                                       </span>](#p16)
       - [<span>18</span><span>Worgen                                        </span>](#p18)
     - [<span>20</span><span>*Races of the Horde*                            </span>](#p20)
       - [<span>21</span><span>Orc                                           </span>](#p21)
       - [<span>23</span><span>Forsaken                                      </span>](#p23)
       - [<span>25</span><span>Tauren                                        </span>](#p25)
       - [<span>37</span><span>Troll                                         </span>](#p27)
       - [<span>39</span><span>Blood Elf                                     </span>](#p29)
       - [<span>31</span><span>Goblin                                        </span>](#p31)
     - [<span>33</span><span>*Allied Races*                                  </span>](#p33)
       - [<span>34</span><span>Nightborne                                    </span>](#p34)
       - [<span>36</span><span>Pandaren                                      </span>](#p36)
       - [<span>38</span><span>Void Elf                                      </span>](#p38)
       - [<span>39</span><span>Vulpera                                       </span>](#p39)
  - #### [<span>##</span><span>Chapter 2: Classes                            </span>](#p##)
     - [<span>##</span><span>Death Knight                                    </span>](#p##)
     - [<span>##</span><span>Demon Hunter                                    </span>](#p##)
     - [<span>##</span><span>Druid                                           </span>](#p##)
     - [<span>##</span><span>Hunter                                          </span>](#p##)
     - [<span>##</span><span>Mage                                            </span>](#p##)
     - [<span>##</span><span>Monk                                            </span>](#p##)
     - [<span>##</span><span>Paladin                                         </span>](#p##)
     - [<span>##</span><span>Priest                                          </span>](#p##)
     - [<span>##</span><span>Rogue                                           </span>](#p##)
     - [<span>##</span><span>Shaman                                          </span>](#p##)
     - [<span>##</span><span>Warlock                                         </span>](#p##)
     - [<span>##</span><span>Warrior                                         </span>](#p##)
  - #### [<span>##</span><span>Chapter 3: New Backgrounds                    </span>](#p##)
     - [<span>##</span><span>Dark Apothecary                                 </span>](#p##)
     - [<span>##</span><span>Double Agent                                    </span>](#p##)
     - [<span>##</span><span>Faction Fostered                                </span>](#p##)
     - [<span>##</span><span>Kirin Tor Apprentice                            </span>](#p##)
  - #### [<span>##</span><span>Chapter 4: New Equipment                      </span>](#p##)
     - [<span>##</span><span>Starting Equipment                              </span>](#p##)
     - [<span>##</span><span>Exotic Weapons                                  </span>](#p##)
     - [<span>##</span><span>New Adventuring Gear and Tools                  </span>](#p##)
  - #### [<span>##</span><span>Chapter 5: Customization Options              </span>](#p##)
     - [<span>##</span><span>New Feats                                       </span>](#p##)
     - [<span>##</span><span>Racial Feats                                    </span>](#p##)

\columnbreak

- ### [<span>##</span><span>Part II: Magic                                  </span>](#p##)
  - #### [<span>##</span><span>Chapter 6: Spells                            </span>](#p##)
     - [<span>##</span><span>Spell Lists                                    </span>](#p##)
     - [<span>##</span><span>Spell Descriptions                             </span>](#p##)
- ### [<span>##</span><span>Part III: Variant Rules                         </span>](#p##)
 - [<span>##</span><span>Hero Points                                        </span>](#p##)
 - [<span>##</span><span>Mana                                               </span>](#p##)
- ### [<span>##</span><span>Appendix A: Shapeshifts                         </span>](#p##)
- ### [<span>##</span><span>Appendix B: Demon Companions                    </span>](#p##)
- ### [<span>##</span><span>Appendix C: World Map                           </span>](#p##)
</div>

<style> .phb#p3:after { display:none; } </style>