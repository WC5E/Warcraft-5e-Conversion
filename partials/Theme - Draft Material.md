<style>

/* background image*/
.phb {
  background: white;
}

/* Text */
.phb h1+p::first-letter {
  float: none;
  font-family: BookSanity;
  font-size: 9.84pt;
  color: #000;
  line-height: 1.3em;
  font-weight: normal;
}

.phb h4,
.phb h3,
.phb h2,
.phb h1 {
  font-family: BookSanity;
  font-weight: normal;
}

.phb h1 {
  font-size: 30pt;
}

.phb h2 {
  font-size: 21, 84pt;
}

.phb h3 {
  font-size: 18pt;
  border-bottom: 1pt solid #000
}

.phb h4 {
  font-size: 14, 88pt;
}

.phb h5 {
  color: #000;
}

/* Tables */
.phb table {
  font-size: 9.84pt;
}

.phb table tbody tr:nth-child(odd) {
  background-color: #f2f2f2;
}

/*change backing of rows*/
/* Class Table */
.phb .classTable {
  border-image-source: none;
  border: none;
}

.phb .classTable h5 {
  font-family: Calibri;
  font-weight: bold;
}

.phb .classTable table tbody tr:nth-child(odd) {
  background-color: #FFF;
}

/* Description block */
.phb .descriptive {
  padding-left: 3px;
  background-color: #e6e6e6;
  border-image: none;
  border: none;
}

.phb .descriptive p {
  font-size: 9.84pt;
}

/* Note */
.phb blockquote {
  font-size:
    9.84pt;
  background-color: #e6e6e6;
  border-width: 5px;
  border-image-outset: 5px 0px;
  box-shadow: 0px 1px 5px;
}

/* Stat Block */
.phb hr+section blockquote {
  background: white;
  border: 3px solid #e6e6e6;
  box-shadow: none;
}

.phb hr+section blockquote h3 {
  font-family: Calibri;
  border-bottom: 1px solid #000;
}

.phb hr+section blockquote hr+ul {
  color: #000;
}

.phb hr+section blockquote table {
  color: #000;
}

.phb hr+section blockquote hr {
  background-image: url(https://gmbinder.com/images/MS0gM8Z.png)
}

/* footer */
.phb:after {
  display: none;
}

.phb .pageNumber {
  color: #000;
  font-size: 9.84pt;
  bottom: 14mm;
  right: 1.7cm
}

.phb .footnote {
  color: #000;
  font-size: 9.84pt;
  bottom: 14mm;
  left: 1.7cm;
  text-align: left;
  width: 600px;
}

.phb:nth-child(even) .pageNumber {
  left: 18.19cm;
}

.phb:nth-child(even) .footnote {
  left: 1.7cm;
}

.phb a {
  color: black;
}

</style>