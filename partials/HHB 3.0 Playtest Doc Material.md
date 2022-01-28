<style>
/* GLOBAL FORMATTING  */

  /* Resize page to international A4 */
  .phb {
    width: 210mm;
    height: 296.8mm;
  }
  .phb:after { content: ""; }

  /* Workaround fix for the line height displacement that GM Binder is
  experiencing right now thanks to under the hood Chromium changes */
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

<!-- Main doc content starts here -->


<!-- Pagebreak followed by update page -->

\pagebreak

# Update 3.0-type-num

<br />

These are the changes made to the class since the last update this material (3.x.x)

## Category


## Category


## Category


## Credits

**Provide feedback for this document:** We'd really love your opinion on this material. You can do so by: 
- Joining the conversation on [Discord](https://discord.com/invite/dKMJmmD). <br /> (Or just messaging an active Contributor there.)
- Sharing your thoughts with us on [Reddit](https://www.reddit.com/r/wc5e/).
- Writing to us via this [Google Form](https://forms.gle/FSbyK7nBbquPNVf36).

<br />**Current core team:** Ace Azzermeen, Auvreannia, Geamros, Lorestalker Nemzal, MythMaker, Nagash, OmNomDom33887, Tangerine, Tyloris
<br />

<br />**Inactive & former team members:** 123jrf, ApolloLumina, Artipo, Christinekn, ClockWorkTank, Elenus, Jih, Prometheus, Reiga, Silverblade, Tseims, Wyken
<br />

<br />**Big thanks to:** Everyone at our community Discord. Link to join our communities are on the book's back page!
<br />

<br />**Projects we like and want to give thanks to:**
- [The WoW 5E Project](https://www.thepiazza.org.uk/bb/viewtopic.php?t=13979) by Arrius Nideal
- [This Warcraft project](https://drive.google.com/drive/folders/1f07sWuQJ_MBJxKbToalevudGQ8hjnma7) by Silverblade#9212
- [These WoW Dungeon modules](https://www.gmbinder.com/profile/wyken) by Wyken
- All of the awesome homebrew that has been shared within the community, it's super cool to see it all! You can see a lot of it on our Discord, and in this [Theme of the Month](https://drive.google.com/drive/folders/1_inQbI4jjd6WF3ghzhr_9RYBFygAkVK1) collection.

<br />**Page X Art:** 
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
 
  *Part of the WC5E Heroes Handbook v3*
 
  This document is a part of an upcoming update (as of writing this) to our *Warcraft 5th Edition Heroes Handbook*; a massive tome of player classes, races, and backgrounds to put a Warcraft spin on core Dungeons & Dragons material.

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
