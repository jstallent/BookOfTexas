# BookOfTexas
This is a sample EPUB 3 document that I use for testing and examples.

The file contains a variety of features that may be of interest to eBook developers, such as:

1. A well-structured OPF file, including good examples of metadata for EPUB 3.
2. HTML5 markup, with examples of different kinds of markup that you might run into in an EPUB file.
3. Backwards compatibility with EPUB 2.
3. The file passes [FlightDeck](http://ebookflightdeck.com) with flying colors!
4. The index is set up for future support for the Indexes markup in EPUB 3.
5. Proper use of semantic markup and accessibility features.
6. ...and more!

Please note: All rights reserved. While the text of this book is in the public domain and available on Google Books, the design of this eBook file was developed by eBook Architects with a significant investment of time and resources. Please respect our work and do not use the contents in commercial projects.

The contents of this eBook file may only be used for non-commercial testing by individual eBook developers.

## Change Log

#### Version 2.1
- Added lang and xml-lang attributes to the <html> tag
- Added aria-describedby content to the tables in Part 2.
- Added a footnote to Part 1, Chapter 2 as an example
- Added epub:type="pullquote" in Intro and in Part 1, Chapter 2
- Updated structural semantics in Index

#### Version 2.0.4
- Added type="text/css" to the CSS link. Required for Amazon.
- changed guide item "text" to "bodymatter"

#### Version 2.0.3
- rendition:spread value changed to "auto" so that it would not override the system default

#### Version 2.0.2
- added prefix for rendition, backwards compatibility with EPUBCheck 3 -- rendition: http://www.idpf.org/vocab/rendition/#

#### Version 2.0.1
- Removed column-count:1; from body.fullpage in the CSS. This is not the replacement for oeb-column-number:1 as I previously believed.
- Added <meta property="rendition:spread">both</meta> for ADE two-page control[1][2]
- Added properties="rendition:spread-none" to cover HTML spine item[3]
- Added figure {display: block;} to CSS[4]
- Replaced <figure> tag in 13-imagegroup02.xhtml with proper <section> tag.

[1] http://www.idpf.org/epub/301/spec/epub-publications.html#fxl-property-spread
[2] https://code.google.com/p/epub-revision/issues/detail?id=499
[3] http://www.idpf.org/epub/301/spec/epub-publications.html#fxl-property-spread-overrides
[4] https://twitter.com/dvsch/status/570986639998255104

#### Version 2.0
- Major update
- New Glossary section
- Tons of changes to HTML
- CSS cleaned up and expanded
