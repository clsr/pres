pres.js
=======

pres is a client-side JS-based presentation program.

It requires no server-side scripting, just hosting static files (the pres.js script, the HTML page and the stylesheet for the pres software and .pres files for presentations themselves).

Presentations are written using a simple markup language that supports most of the basic commonly used features in presentations.

For documentation of the pres markup language, see [the example .pres presentation's source](pres.pres).

To use pres, just put index.html, style.css and pres.js on your web server. index.html can be arbitrarily renamed, but renaming the other two or putting them in a separate directory requires changing the references in index.html's head tag.

To open a presentation, put its filename (.pres can be omitted) in the fragment part of the URL. So, if the pres script is located on http://example.com/pres/, to load the http://example.com/pres/example.pres presentation, go to http://example.com/pres/#example. To go to a specific slide, add another hash mark and the slide number, so http://example.com/pres/#example#2 is the second slide of example.pres. If the presentation name is omitted, pres.pres is loaded (this can be changed on top of pres.js).
