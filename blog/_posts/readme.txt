INFORMATION ABOUT HOW TO CREATE A NEW BLOG ENTRY

1. Create a new markdown file in the folder directory: /blog/_posts/YEAR_MONTH_DAY_URL.md (Jekyll needs this format, please do not use spaces in the URL, instead use: '_')
2. At the the beginning of the file write the following header (with the three hyphens at the top and at the bottom, for dumb people: from line 6 to 11):

---
title: TITLE
layout: post
banner: "PATH_TO_IMAGE"
categories: [post]
---

title: here goes the title of the project
layout: post # just write post
banner: the path to the image, please place the image in the "images" folder.
categories: [post] # just put it

3. Once you finished with the header, you now can write the content. 

4. Use the tag "<!--more-->" (without quotes) as a delimiter between the excerpt that is shown in the Research page and the remaining content. 

5. That's it.

Example:

---
title: POST ABOUT BLAH BLAH
layout: post
banner: "/images/giscia.jpg"
categories: [post]
---

CONTENT OF THE EXCERPT
<!--more-->
MORE CONTENT
