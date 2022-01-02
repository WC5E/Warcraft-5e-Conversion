<style>
/* GLOBAL FORMATTING  */

  /* Resize page to international A4 */
  .phb {
    width: 210mm;
    height: 296.8mm;
    background-image: url('https://www.gmbinder.com/images/RVaHjr8.png');
    background-size: cover;
  }
  .phb:after { 
    content: "";
  }
  /* Workaround fix for the line height displacement that GM Binder is
    experiencing right now thanks to under the hood Chromium changes */
  .phb p{ line-height: 15px; } 
  .phb blockquote p{ line-height: 14px; } 
  .phb h2{ line-height: 26px; } 
  .phb h3{ line-height: 19px; } 
  .phb h4{ line-height: 15px; padding-bottom: 3px; } 
  .phb h5{ line-height: 17px; } 
  th, td { line-height: 14px; }

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


/* TABLES AND BLOCKS */

  /* Adjust table colors */
  table tr:nth-child(odd) td { 
    background-color: #FFF0f5; 
  }
  .phb hr+section blockquote tr:nth-child(odd) td { 
    background-color: transparent;
  }
  /* Clear internal padding and add gap above for green note blocks*/
  .phb blockquote {
    padding-left: 0px;
    padding-right: 0px;
  }
  .phb blockquote { 
    margin-top: 1em;
  }
  /* Clear internal padding in creature statblocks */
  .phb hr+section blockquote {
    padding-left: 0px;
    padding-right: 0px;
  }  
  /* Use black tones for statblock backgrounds */
  .phb blockquote {
    box-shadow: 1px 4px 14px rgba(0,0,0,0.42);
  }
  /* Normalize space above Attributes */
  .phb hr+section blockquote hr+table {
    padding-top: 4px;
  }

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


/* DOUBLE WIDE STATBLOCKS */

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

/* FOOTER */

  /* Footnotes */
  .phb .pageNumber {
    color: #7e735c;
    z-index: 1000;
  }
  .phb .footnote { 
    color: #7e735c;
  }
  /* On odd pages before the bestiary, have just the page tear */
  .phb:nth-child(odd):nth-of-type(n+2):after {
    content: '';
    height: 125px;
    background-image: url(https://www.gmbinder.com/images/PB8On0U.png), url('https://gmbinder.com/images/YWardeu.png');
    background-size: 120px 120px, 816px 55px;
    background-repeat: no-repeat, no-repeat;
    background-position: bottom right -10px, bottom;
  }
  /* Reversed for alternating pages */
  .phb:nth-child(even):nth-of-type(n+2):after {
    content: '';
    height: 125px;
    background-image: url(https://www.gmbinder.com/images/PB8On0U.png), url('https://gmbinder.com/images/YWardeu.png');
    background-size: 120px 120px, 816px 55px;
    background-repeat: no-repeat, no-repeat;
    background-position: bottom right -10px, bottom;
    -webkit-transform: scaleX(-1);
    transform: scaleX(-1);
  }
  /* On odd bestiary pages, have the Monster Manual page tear and lettering */
  .phb:nth-child(odd):nth-of-type(n+10):nth-of-type(-n+115):after {
    content: '';
    height: 125px;
    background-image: url(https://gmbinder.com/images/lLWeevR.png), url('https://gmbinder.com/images/YWardeu.png');
    background-size: 120px 120px, 816px 55px;
    background-repeat: no-repeat, no-repeat;
    background-position: bottom right -10px, bottom;
  }
  /* Reversed for alternating pages */
  .phb:nth-child(even):nth-of-type(n+10):nth-of-type(-n+115):after {
    content: '';
    height: 125px;
    background-image: url(https://gmbinder.com/images/lLWeevR.png), url('https://gmbinder.com/images/YWardeu.png');
    background-size: 120px 120px, 816px 55px;
    background-repeat: no-repeat, no-repeat;
    background-position: bottom right -10px, bottom;
    -webkit-transform: scaleX(-1);
    transform: scaleX(-1);
  }
  /* The page number position */
  .phb .pageNumber {
    right: 0px;
  }
  /* The page number position for alternating pages */
  .phb:nth-child(even) .pageNumber {
    left: 0px;
  }
  /* The letter in the Monster Manual page tear */
  .pageLetter {
    position: absolute;
    right: 15px;
    bottom: 87.5px;
    color: #905727;
    z-index: 1000;
    font-size: 135%;
  }
  /* Reversed for alternating pages */
  .phb:nth-child(even) .pageLetter {
      left: 15px;
  }

/* MONSTER MANUAL SPECIFIC */

  /* Adds the surrounding framing for the big, bold monster letter headings */
  .letterheader {
    position: absolute;
    top: 30px;
    left: 0;
    right: 0;
    margin-left: auto;
    margin-right: auto;
    background-image: url(https://gmbinder.com/images/YH3aESG.png);
    background-size: cover;
    width: 775px;
    height: 133px;
  }

  /* Base component for the actual letter in the heading */
  .mmletter {
      position: absolute;
      top: 20px;
      left: 0;
      right: 0;
      margin-left: auto;
      margin-right: auto;
      background-size: cover;
      width: 163.2px;
      height: 163.2px;
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
 
/* APPENDIX STYLES */

  /* Avoid upscaling first letter on an appendix page */
  .phb:nth-of-type(n+0):nth-of-type(-n+100) h1+p::first-letter {
    font-family: BookSanity;
    font-size: .317cm;
    text-rendering: optimizeLegibility;
    float: initial;
  }  


</style>
