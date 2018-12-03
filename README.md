# Mason Fidino's Curriculum Vitae

This cv is made using the `moderncv` tex class. The `moderncv` class does not talk well with many of the citation packages in latex so I modified my own version of the `abbrv` and `unsrt` bibliography styles to make an apa-like citation which will bold the name of a specific author (so that your own name is bolded in the citations). As a result, the bibliography is not sorted in any way (you will need to organize it how you want in your own `bib` file). This fix is a temporary solution until I figure out how to have the file sort by year then by first author. 

If you want to use this layout for your own purposes there are few changes you will need to do (aside from putting in your own `bib` file and other information):

- Put your name in place of mine on line 41 of `unsrt_abbrv.bst`. This will bold your name instead in the publications part of the CV.
- Modify the `masonFidino.sty` file on line 2 (put your name there) and update information with your own on lines 39 - 46.
- I call `masonfidino.sty` on line 3 of `Fidino_cv.tex`. If you change that file name update here as well.
- Line 7 in `Fidino_cv.tex` is what I changed the bibliography title to. If you do not need any extra notes as I did you can simplify this to just be "Publications"
- Update with your own personal information on lines 21 - 24 of `Fidino_cv.tex`
-Write your CV with modern style.
