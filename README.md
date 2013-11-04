Please read the `LICENSE`.

To build: `zip -r ansilove.xpi chrome.manifest install.rdf chrome/`

In FireFox: Tools > Add-ons > Gears Icon > Install Add-on From File... > Choose the XPI file and install.

You should now have a contextual menu, listed as "Filter Links With AnsiLove" when right-clicking a page.

When sucessfully run, any web page with links to .ans, .asc, .ads, .bin, .idf, .pcb, .tnd, .xb,  will now open with a image preview when shift-clicked, instead of redirecting to a page or downloading the file from the server.

Known issues:
- urls pointing to pages are mistaken for images.

This extension uses [ansilove.js][1] to render textmode-art images.  
[ansilove™][2] is a trademark of Frederic Cambus.

[1]: http://andyherbert.github.io/ansilove.js/
[2]: https://github.com/fcambus/ansilove