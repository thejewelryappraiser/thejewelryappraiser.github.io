---
layout: post
title: How to update this site
---

This website is built using Jekyll and Bootstrap, following the advice from this [link](http://code.tutsplus.com/articles/building-static-sites-with-jekyll--net-22211), but most of the content is written using Markdown.

The website is maintained using Git and has it's an open source on [Github](http://turbulencelab.github.io)


In order to add a page, e.g. for a new student, please use one of the pages as a template. The structure is very simple


		---
		layout: default
		title: Firstname Lastname
		---

		### Short Bio

		<html>
			<img src = "{{ site.baseurl }}/images/yourimage.jpg" align = "right">
		</html>


		### Research project



		### Links to the publicaitons, presentations, etc.  




#### Using Github

1. Fork the website
2. Add your file
3. Send pull request or a patch

or simply send the file to our contact e-mail.


#### How to update the site on http://www.eng.tau.ac.il/~tsl

1. After Github update and build check that the site is working
2. on your local machine install jekyll and what's needed with it (kramdown, bundle ,etc.)
3. use the following command and then upload the result _site folder to the www.eng.tau.ac.il

    jekyll serve --baseurl="/~tsl"

