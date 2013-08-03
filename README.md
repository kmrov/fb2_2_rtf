fb2_2_rtf
=========

FB2 to RTF and TXT converter. Originally created by Dmitry Gribov (GribUser), published at http://www.gribuser.ru/xml/fictionbook/ and published here by his kind permission.

Installation
============

For now just clone the project and install the following packages (for Ubuntu): libimage-size-perl libxslt1.1 libxml-perl libxml-xslt-perl libxml-libxml-perl libxml-libxslt-perl

Usage
=====

Conversion to RTF format:
`perl fb2_2_rtf.pl <input_filename> FB2_2_rtf.xsl <output_filename>`

Conversion to TXT format:
`perl fb2_2_rtf.pl <input_filename> FB2_2_txt.xsl <output_filename>`
