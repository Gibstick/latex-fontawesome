latex-fontawesome
=================

Bindings for [FontAwesome](http://fortawesome.github.io/Font-Awesome/) icons to be used in XeLaTeX.

The current version of FontAwesome icons used is 4.3.0. See [this](http://www.ctan.org/tex-archive/fonts/fontawesome) for an older version (using FontAwesome version 3.1.1) with better documentation, examples, and for more information.

How to Use
----------

### Requirements
* You must have the FontAwesome font installed on your machine (download the `.otf` file [here](https://github.com/FortAwesome/Font-Awesome/blob/master/fonts/FontAwesome.otf?raw=true)).
* You must be using XeLaTeX and have the `fontspec` package installed.

### Usage
1. Download the `fontawesome.sty` file and put it in the same directory as the LaTeX file using the icons.
2. Include the package as normal (in the preamble of the `.tex` file, add the line `\usepackage{fontawesome}`).
3. Use an icon by typing `\faIconName`. For example, to use the `fa-quote-left` icon, convert it to camelcase and prepend the slash: `\faQuoteLeft`.

