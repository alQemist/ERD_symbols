# ERD_symbols for ERD Diagrams

Author : Ben Marchbanks ben@alQemy.com

These ERD relationship symbols are created as SVG paths and are designed to be used as "markers" which can be appended to paths in an SVG diagram.
Developed for projects which utilized a d3.v4 forceLayout ERD diagram.

Usage
Import or include the javascript file in your project and peforms the following:

1.  Automatically adds an SVG to the body
2.  Automatically adds a DEFS to the SVG
3.  Appends the symbols as "markers" to the DEFS element

RELATIONSHIP SYMBOL IDs

	11 - One to One
	1M - One to Many
	01 - Zero or One
	0M - Zero or Many
	arrow - included for miscellaneous use

Append any of the symbols to a path using

path.attr("marker-end", "url(#1M)") // adds a one to many symbol to the path.

