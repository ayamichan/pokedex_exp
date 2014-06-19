Pokedex - Front-end playground

-- This is a very simple project to test and practice my skill on CSS & HTML --

Objectives: 
- Master the responsive techniques
- Master the new sectioning tags of HTML5
- Respect the Semantic & Acessibility
- Master the cross-browsing techniques
- Deal and memorize solutions to common bugs
- Work with Mobile first Concept
- Master DRY Skills 
- Apply SASS / LESS Techniques
- Work with the most common js cripts

If you think I'm not executing well anything of these objectives, fell free to comment.

Bugs / Solved Problems:

- IE8 - : Don't Identify the HTML5 sectioning tags.
solution: script made by Remy Sharp that generates empty tags and gives them the proper names 
 <script src="http://html5shiv.googlecode.com/svn/trunk/html5.js"></script>
----------------
- IE7- e FF2.0 Display: inline-block not working
solution FF: display: -moz-inline-stack;
solution IE: zoom: 1;
                  *display: inline;
		  vertical-align:top (only for aligment)
----------------
- IE7-: Margin or padding is collapsing
solution: do not use padding to layout, use margin.
----------------
- Dotted/dashed border-radiused corners are rendered as solid at FF
FF do not have any solution at the moment
----------------
- IE8 - : Don't suport @media queries
solution: Still working.
----------------
- PNG Images do not show on IE6
solution: Still working.
}