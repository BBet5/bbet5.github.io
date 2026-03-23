/* stylingg

body {
    font-family: Georgia, serif;
    background-color: #e8f1f8;
    color: #222222;
    margin: 0;
    padding: 0;
}

h1 {
    color: #1a3a5c;
    font-size: 2.2em;
    margin-bottom: 10px;
    text-align: center;
}

h2 {
    color: #1a3a5c;
    border-bottom: 2px solid #2980b9;
    padding-bottom: 5px;
    margin-top: 30px;
    text-align: center;
}

h3 {
    color: #1f618d;
    text-align: center;
}

h4 {
    color: #1a5276;
    text-align: center;
}

p {
    line-height: 1.8;
    margin-bottom: 14px;
    font-size: 1em;
}

a {
    color: #1f618d;
    text-decoration: none;
}

/* hover effect on links */
a:hover {
    color: #e74c3c;
    text-decoration: underline;
}

ul {
    margin: 10px 0 10px 20px;
    padding-left: 20px;
}

ol {
    margin: 10px 0 10px 20px;
    padding-left: 20px;
}

li {
    margin-bottom: 10px;
    line-height: 1.7;
}

table {
    width: 100%;
    border-collapse: collapse;
    margin: 20px 0;
    font-size: 0.95em;
}

th {
    background-color: #1a3a5c;
    color: white;
    padding: 10px 14px;
    text-align: left;
}

td {
    padding: 9px 14px;
    border: 1px solid #aed6f1;
}

tr:nth-child(even) {
    background-color: #d6eaf8;
}

tr:hover {
    background-color: #aed6f1;
}

img {
    max-width: 100%;
    border: 2px solid #2980b9;
    border-radius: 4px;
    margin: 10px 0;
}

footer {
    background-color: #1a3a5c;
    color: #aed6f1;
    text-align: center;
    padding: 18px;
    margin-top: 40px;
    font-size: 0.88em;
}

footer a {
    color: #aed6f1;
    text-decoration: underline;
}

footer a:hover {
    color: white;
}


/* class selectors */

.wrapper {
    max-width: 960px;
    margin: 0 auto;
    padding: 20px 30px;
}

.page-header {
    background-color: #1a3a5c;
    color: white;
    padding: 30px 30px 20px 30px;
    border-bottom: 4px solid #2980b9;
    text-align: center;
}

.page-header h1 {
    color: white;
    margin: 0;
    text-align: center;
}

.page-header p {
    color: #aed6f1;
    margin: 6px 0 0 0;
    font-size: 0.95em;
    text-align: center;
}

.nav-bar {
    background-color: #1f618d;
    padding: 0;
}

/* flex layout for the nav */
.nav-bar ul {
    display: flex;
    flex-wrap: wrap;
    list-style: none;
    margin: 0;
    padding: 0 20px;
    justify-content: center;
}

.nav-bar ul li {
    margin: 0;
}

.nav-bar ul li a {
    display: block;
    color: white;
    padding: 13px 16px;
    font-family: Arial, sans-serif;
    font-size: 0.92em;
    text-decoration: none;
}

.nav-bar ul li a:hover {
    background-color: #2980b9;
    color: white;
    text-decoration: none;
}

.content-box {
    background-color: white;
    border: 1px solid #aed6f1;
    border-top: 3px solid #2980b9;
    border-radius: 6px;
    padding: 24px 28px;
    margin-bottom: 24px;
}

.key-terms-list {
    background-color: #d6eaf8;
    border-left: 4px solid #1f618d;
    padding: 16px 20px;
    border-radius: 0 6px 6px 0;
    margin: 20px 0;
}

.highlight-box {
    background-color: #1f618d;
    color: white;
    padding: 16px 20px;
    border-radius: 6px;
    margin: 20px 0;
}

.highlight-box p {
    color: white;
    margin: 0;
}

.image-placeholder {
    background-color: #d6eaf8;
    border: 2px dashed #2980b9;
    color: #1a5276;
    text-align: center;
    padding: 30px 20px;
    margin: 16px 0;
    border-radius: 6px;
    font-style: italic;
}

/* grid layout for two column sections */
.two-col {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 24px;
    margin: 20px 0;
}

.toc-list {
    list-style: none;
    padding: 0;
    margin: 0;
}

.toc-list li {
    border-bottom: 1px solid #aed6f1;
    padding: 8px 0;
}

.toc-list li a {
    font-size: 1.05em;
}

.concept-card {
    background: white;
    border: 1px solid #aed6f1;
    border-top: 4px solid #1f618d;
    padding: 20px;
    margin-bottom: 20px;
    border-radius: 4px;
}

.concept-card h3 {
    margin-top: 0;
}

.tag {
    display: inline-block;
    background-color: #1f618d;
    color: white;
    font-size: 0.78em;
    padding: 3px 9px;
    border-radius: 3px;
    margin-right: 6px;
    margin-bottom: 6px;
    font-family: Arial, sans-serif;
}


/* id selectors */

#homepage-intro {
    font-size: 1.08em;
    color: #1a3a5c;
    border-left: 4px solid #2980b9;
    padding-left: 16px;
    margin: 20px 0;
    background-color: #eaf4fb;
    padding: 14px 16px;
    border-radius: 0 6px 6px 0;
}

#about-section {
    background-color: #d6eaf8;
    padding: 24px;
    border-radius: 8px;
    margin-bottom: 20px;
    border: 1px solid #aed6f1;
}

#comparison-table-section {
    overflow-x: auto;
}


/* responsive for small screens, added this later */
@media (max-width: 640px) {
    .two-col {
        grid-template-columns: 1fr;
    }

    .nav-bar ul {
        flex-direction: column;
    }

    .wrapper {
        padding: 14px 16px;
    }
}
