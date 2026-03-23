/*
    styles.css
    IT 3203 Web Servers Research Site
    one css file for all pages
*/


/* ==========================
   general reset stuff
   ========================== */

* {
    box-sizing: border-box;
}

body {
    margin: 0;
    padding: 0;
    background-color: #ddeeff;
    font-family: Georgia, serif;
    color: #111111;
    font-size: 16px;
}

html {
    scroll-behavior: smooth;
}


/* ==========================
   headings
   ========================== */

h1 {
    color: #ffffff;
    font-size: 2.1em;
    margin: 0;
    padding: 0;
}

h2 {
    color: #14456e;
    font-size: 1.45em;
    margin-top: 26px;
    margin-bottom: 10px;
    padding-bottom: 6px;
    border-bottom: 2px solid #2471a3;
}

h3 {
    color: #1a5276;
    font-size: 1.12em;
    margin-top: 18px;
    margin-bottom: 7px;
}

h4 {
    color: #1a5276;
    margin-top: 14px;
    margin-bottom: 5px;
}


/* ==========================
   paragraphs and text
   ========================== */

p {
    line-height: 1.8;
    margin-top: 0;
    margin-bottom: 14px;
}

strong {
    color: #14456e;
}

em {
    color: #333333;
}


/* ==========================
   lists
   ========================== */

ul {
    margin-bottom: 14px;
    margin-top: 4px;
    padding-left: 20px;
}

ol {
    margin-bottom: 14px;
    margin-top: 4px;
    padding-left: 20px;
}

li {
    line-height: 1.75;
    margin-bottom: 6px;
}


/* ==========================
   links
   ========================== */

a {
    color: #1a5276;
}

a:hover {
    color: #b03a2e;
    text-decoration: underline;
}


/* ==========================
   images
   ========================== */

img {
    border: 2px solid #2471a3;
    border-radius: 4px;
    display: block;
    margin-bottom: 12px;
    margin-top: 6px;
    max-width: 100%;
    width: 100%;
}


/* ==========================
   tables
   ========================== */

table {
    border-collapse: collapse;
    font-size: 0.93em;
    margin-bottom: 16px;
    margin-top: 16px;
    width: 100%;
}

th {
    background-color: #1a5276;
    color: #ffffff;
    padding: 10px 14px;
    text-align: left;
}

td {
    border: 1px solid #aed6f1;
    padding: 9px 13px;
    vertical-align: top;
}

tr:nth-child(even) td {
    background-color: #d6eaf8;
}

tr:hover td {
    background-color: #aed6f1;
}


/* ==========================
   page header banner
   ========================== */

.page-header {
    background-color: #14456e;
    border-bottom: 4px solid #2471a3;
    padding: 26px 0 18px 0;
}

.page-header p {
    color: #aed6f1;
    font-size: 0.92em;
    margin: 5px 0 0 0;
    padding: 0;
}


/* ==========================
   nav bar -- uses flexbox
   ========================== */

nav.nav-bar {
    background-color: #1a5276;
    padding: 0;
}

nav.nav-bar ul {
    display: flex;
    flex-wrap: wrap;
    list-style: none;
    margin: 0;
    padding: 0 12px;
}

nav.nav-bar ul li {
    margin: 0;
    padding: 0;
}

nav.nav-bar ul li a {
    color: #ffffff;
    display: block;
    font-family: Arial, sans-serif;
    font-size: 0.88em;
    padding: 12px 14px;
    text-decoration: none;
}

nav.nav-bar ul li a:hover {
    background-color: #2471a3;
    color: #ffffff;
    text-decoration: none;
}


/* ==========================
   main content wrapper
   ========================== */

.wrapper {
    margin-left: auto;
    margin-right: auto;
    max-width: 940px;
    padding: 20px 26px 30px 26px;
}


/* ==========================
   white content boxes
   ========================== */

.content-box {
    background-color: #ffffff;
    border: 1px solid #aed6f1;
    border-radius: 5px;
    margin-bottom: 20px;
    margin-top: 0;
    padding: 20px 24px;
}

.content-box:first-of-type {
    margin-top: 22px;
}


/* ==========================
   two column grid layout
   ========================== */

.two-col {
    display: grid;
    gap: 20px;
    grid-template-columns: 1fr 1fr;
    margin-bottom: 20px;
    margin-top: 4px;
}

.two-col .content-box {
    margin-bottom: 0;
    margin-top: 0;
}


/* ==========================
   blue highlight callout box
   ========================== */

.highlight-box {
    background-color: #1a5276;
    border-radius: 5px;
    margin-bottom: 16px;
    margin-top: 16px;
    padding: 15px 20px;
}

.highlight-box p {
    color: #ffffff;
    margin: 0;
}


/* ==========================
   image placeholder box
   ========================== */

.image-placeholder {
    background-color: #d6eaf8;
    border: 2px dashed #2471a3;
    border-radius: 4px;
    color: #1a5276;
    font-style: italic;
    margin-bottom: 14px;
    margin-top: 12px;
    padding: 30px 18px;
    text-align: center;
}


/* ==========================
   key terms shaded area
   ========================== */

.key-terms-list {
    background-color: #d6eaf8;
    border-left: 4px solid #1a5276;
    border-radius: 0 4px 4px 0;
    margin-bottom: 14px;
    margin-top: 14px;
    padding: 14px 18px;
}


/* ==========================
   table of contents list
   ========================== */

ul.toc-list {
    list-style: none;
    margin: 0;
    padding: 0;
}

ul.toc-list li {
    border-bottom: 1px solid #aed6f1;
    margin-bottom: 0;
    padding: 9px 2px;
}

ul.toc-list li a {
    font-size: 1.02em;
}


/* ==========================
   concept cards
   ========================== */

.concept-card {
    background-color: #ffffff;
    border: 1px solid #aed6f1;
    border-radius: 4px;
    border-top: 4px solid #1a5276;
    margin-bottom: 20px;
    padding: 18px 22px;
}

.concept-card h3 {
    margin-top: 6px;
}


/* ==========================
   small label tags
   ========================== */

.tag {
    background-color: #1a5276;
    border-radius: 3px;
    color: #ffffff;
    display: inline-block;
    font-family: Arial, sans-serif;
    font-size: 0.76em;
    margin-bottom: 7px;
    padding: 3px 8px;
}


/* ==========================
   id selectors for specific sections
   ========================== */

#homepage-intro {
    border-left: 4px solid #2471a3;
    color: #1a1a1a;
    font-size: 1.05em;
    margin: 16px 0;
    padding-left: 14px;
}

#about-section {
    background-color: #d6eaf8;
    border-radius: 6px;
    margin-bottom: 20px;
    margin-top: 22px;
    padding: 20px 24px;
}

#comparison-table-section {
    overflow-x: auto;
}


/* ==========================
   footer
   ========================== */

footer {
    background-color: #14456e;
    color: #aed6f1;
    font-family: Arial, sans-serif;
    font-size: 0.86em;
    margin-top: 36px;
    padding: 16px 20px;
    text-align: center;
}

footer a {
    color: #aed6f1;
    text-decoration: underline;
}

footer a:hover {
    color: #ffffff;
}


/* ==========================
   responsive for small screens
   ========================== */

@media screen and (max-width: 600px) {

    .two-col {
        grid-template-columns: 1fr;
    }

    nav.nav-bar ul {
        flex-direction: column;
    }

    .wrapper {
        padding: 12px 13px 20px 13px;
    }

    h1 {
        font-size: 1.6em;
    }

}
