solitaire-js
============

Context from Nicolas Ramz:
>Solitaire JS is an HTML5 game I originally wrote for a contest organized for the launch of the original webOS Palm Pré launch in France: [SFR Jeunes Talents](http://www.generation-nt.com/sfr-jeunes-talents-concours-palm-webos-actualite-959281.html).
>Since the game has been written at least 4/5 years ago, don't expect to see a package.json file, nor any .bowerrc: this is pure JavaScript ;)"

At some point after moving to a new state, I was diagnosed with strabismus, also known as cross-eyedness, and prescribed visual therapy to help my eyes focus together again. One of the exercises was wearing R/G glasses (red on the right eye!) and playing Solitaire. As I had to eventually return the deck of cards I used to play during my treatment, I found Mr. Ramz's project and modified the graphics to make it work for visual therapy.

The cards now use a solid red and black color scheme to allow for compatibility with R/G glasses.

Demo for Original Version
====

* HTML5 browser-based version: [SolitaireHD](http://solitaire.warpdesign.fr)
* Original webOS version: [YouTube](http://www.youtube.com/watch?v=7L9sC-nBhf0), [Palm Catalog](https://developer.palm.com/appredirect/?packageid=com.warpdesign.warpklondike)


Background
==========

The webOS game is known as "warpKlondike" features:

* Customizable theme (cards & background)
* Game can be saved and resumed at any time
* Local Score table
* Localisation: game available in 4 languages
* Game statistics

Nicolas Ramz made some changes to make the game work on a webbrowser:

* Ported Prototype code to jQuery
* Ported database code to web-based database (using Lawnchair)
* Removed localisation
* Added HD graphics (work done by Guillaume Poyet)
* Added unlimited undo/redo
* Made the game play nice with the original iPad by adding CSS3 acceleration (which wasn't supported by the original webOS)

Years later, I came in and essentially striped down the features and replaced the graphics with ones that are compatible with visual therapy for my strabismus. 

Future
======

What could be done in the future:

* make the game responsive (it's now only adapated to 1024x768 screens)

Licence
-------

This software is distributed under an MIT licence.

Copyright 2010-2014 © Nicolas Ramz
Copyright 2022-2026 

> Permission is hereby granted, free of charge, to any person obtaining a copy of this software
> and associated documentation files (the "Software"), to deal in the Software without
> restriction, including without limitation the rights to use, copy, modify, merge, publish,
> distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the
> Software is furnished to do so, subject to the following conditions:
> The above copyright notice and this permission notice shall be included in all copies or
> substantial portions of the Software.
> The Software is provided "as is", without warranty of any kind, express or implied, including
> but not limited to the warranties of merchantability, fitness for a particular purpose and
> noninfringement. In no event shall the authors or copyright holders be liable for any claim,
> damages or other liability, whether in an action of contract, tort or otherwise, arising from,
> out of or in connection with the software or the use or other dealings in the Software.
