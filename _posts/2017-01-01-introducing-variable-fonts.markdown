---
layout: post
title: "Introducing OpenType Variable Fonts"
date: 2017-01-01 16:40:39 +0100
categories: article
author: John Hudson
publisher:  Medium
publicationDate: 2016
link: https://medium.com/@tiro/https-medium-com-tiro-introducing-opentype-variable-fonts-12ba6cd2369#.94v2uf2wl
---

THE FUTURE! Flexible fonts look like the natural progression for typefaces to go through - we don't have to cast them in lead anymore, so there is no reason to limit the number of variations within a type family. And the tools used to draw typefaces do some of this interpolation anyway, so why not make that the standard. Here's a summary:

> Version 1.8 of the OpenType font format specification introduces an extensive new technology, affecting almost every area of the format. An OpenType variable font is one in which the equivalent of multiple individual fonts can be compactly packaged within a single font file. This is done by defining variations within the font, which constitute a single- or multi-axis design space within which many font instances can be interpolated. A variable font is a single font file that behaves like multiple fonts.

Instead of a set number of cuts we get what the creators of the standard call a "design space":

> An OpenType variable font contains one or more axes that each provide particular variation between different extremes of a typeface design. The format also allows for the possibility of intermediate designs, for the whole glyph set or for individual glyphs, to provide finer control over the design as it changes across the variations design space. In addition, there are mechanisms that allow for radical glyph shape changes to be substituted for discrete areas of the resulting design space

This sounds amazing. Also makes a lot of sense in the context of screen based media where dimensions are always changing, layouts are fluid and content can be updated all the time etc.