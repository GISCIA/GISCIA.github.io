INFORMATION ABOUT HOW TO CREATE A NEW PROJECT ENTRY

1. Create a new markdown file in the folder directory: /research/_posts/YEAR_MONTH_DAY_URL.md (Jekyll needs this format, please do not use spaces in the URL, instead use: '_')
2. At the the beginning of the file write the following header (with the three hyphens at the top and at the bottom, for dumb people: from line 6 to 12):

---
title: Title Example
reflink: title_example
layout: post
area: NLP
categories: [project]
---

title: here goes the title of the project
reflink: write some nickname for the project, this is necessary for the sidebar, prefereably write something short
layout: post # just write post
area: 	these are the available areas, write just the FIRST word, the short one.
		if you want to add a new one, please contact the geniuses who made this page or try to hack it (actually, just understand jekyll).
		-----------------------------------------
		| CV      | Computer Vision				|
		| ML  	  | Machine Learning			|
		| NLP	  | Natural Language Processing |
		| Robo    | Robotics					|
		| Control | Control Systems				|
		| Finance | Finance-Economics			|
		-----------------------------------------
categories: [project] # just put it

3. Once you finished with the header, you now can write the content. 

4. Use the tag "<!--more-->" (without quotes) as a delimiter between the excerpt that is shown in the Research page and the remaining content. 

5. That's it.

Example:

---
title: Title
reflink: Title_nick
layout: base
area: ML
categories: [project]
---

CONTENT OF THE EXCERPT
<!--more-->
MORE CONTENT
