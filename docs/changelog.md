---
layout: page
title: Changelog
nav_order: 24
---

# Changelog


{: .fs-6 .fw-300 }

---

19/Jan 
* Update nav_orders, add 3310, 3330, 3350, 3360, 439R, 4370, and 4520 class placeholders.
* Figure out plan to store quiz, exam, rubrics, and other supporting class info here but not make it searchable or findable, just storable.

15/Jan 2021
* Launch v.8 project; need database, search, static page creation (jekyll takes too long)
	* eleventy.js on github?
* Install [Just The Docs](https://pmarsceill.github.io/just-the-docs/) Jekyll-based documentation theme. 
* Identify basic document structure and update nav_orders. 
* Basic architecture: 
	* syllabus, assignment(s), learning units, about = "course"; courses constitute site.
		* can course information be trimmed down (feels so long)
	* other pages — articles, about, FAQs, classrooms, action plans, experiments, feed/RSS?, Library, contact — float independent.
		* action plans, articles, library = "section"; needs a directory
* Create two test classes, 3370 and 3380, to define child, parent, and grandparent relationships.
* Reconsider bespoke and simplified font, color, footer, 'well' alterations; do this in a separate sass mix in? 
* How to use color to identify courses?
* How can I leverage includes? Lots of text is repeated; theory: pages should be made of predescribed includes so courses can be pieced together. Most of the text, pedagogy is similar.
* Need a customized home screen.
* Site will not publish if configuration.md and customization.md are removed; why? (O_o). Added nav_exclude to them and changed nav_order to 98 and 99.
* Search is broken, need to identify why.




