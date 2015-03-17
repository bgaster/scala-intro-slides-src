Reveal.js HTML Source for Introduction to Scala Course
===================================================

This repo contains the source for my Scala Introduction Course. 
The developing examples and PDF slides can be found in:

https://github.com/bgaster/scala-intro

Setup
========

You will need to install Reveal.js, which can be found here:

    https://github.com/hakimel/reveal.js/

You also need Grunt:

    http://gruntjs.com/getting-started#installing-the-cli

Finally some of the slideshows depend on a locally installed MathJax

    git clone git://github.com/mathjax/MathJax.git MathJax

You could create a symbolic link to the MathJax directory from within
the reveal.js directory.

Also create a symbolic link to the resources directory in reveal.js,
as this is used to store any images and so on.

After this you should have a reveal.js directory that looks something like:

    reveal.js
        ../<path>/resources
	../<path>/MathJax
	the reveal.js distrabution

Running a Slideshow
===================

Make sure that you have deleted the sample index.html in reveal.js
directory and then create a symbolic link to the particuar
scala_*.html file for the show to index.html reveal.js.

Now simply run the following command from within reveal.js directory:

   grunt serve

and open at browser and point it to localhost:8000.

