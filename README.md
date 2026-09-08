Erik Nazarian
# CIT384-HW2
Repo for CIT384-HW2 all files + hosted page.

Live site: [View on GitHub Pages](https://nazarianerik.github.io/CIT384-HW2/)

Answer for 1b:

The structure.html file uses a header element which serves as the header of the page and includes the title, h1 and h2 page headings, and main navigation for 
navigating to the other pages. The ARIA role, role="banner" is there to communicate with assistive technology. Inside the header, a nav element (with role="navigation") 
contains the site's list of links to the other pages. Most of the content is inside the main. There is an article element and it contains the main lesson content.
Within it, that content is then split into different parts for each lesson topic using section. Those sections are "Sectioning elements," "Document outlines," and "WAI-ARIA Roles".
All of them are built around their own h3 heading. Within the "Document outlines" section, an aside (role="complementary") is included. The effect of this, with the given css styling,
places a blue box which seperates the W3C Warning from the rest of the paragraphs. a p element describes the warning and the blockquote following after it is the actual
quote from the W3C, idented and italicized. Lastly, the footer element includes a link to CSUN as well as the address.
