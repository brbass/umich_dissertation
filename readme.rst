--------------------------------------
Dissertation at University of Michigan
--------------------------------------

This is the final copy of my dissertation from the University of Michigan. The file "Bassett_Meshless_2018.pdf" is the accepted document. The other code is included for the benefit of other University of Michigan students formatting their dissertation.

The dissertation is written in LyX with some explicit LaTeX sections and formatting.

The code that implements the theory from this dissertation can be found at https://github.com/brbass/ibex. 

-----------------
Creating document
-----------------

To output a complete version of the dissertation without the separate List of Appendices, use LyX and output using pdflatex with the Output_LyX branch enabled and the Output_LaTeX branch disabled.

To output the dissertation with the separate List of Appendices:

- Enable the Output_LaTeX branch and disable the Output_LyX branch
- Output Bassett_Meshless_2018.lyx to Bassett_Meshless_2018.tex using pdflatex (or use the included .tex file)
- Edit make_doc file if you want to use an editor other than emacs
- Run "./make_doc Bassett_Meshless_2018.tex"
- In the editor, move the \usepackage[...]{hyperref} line down to the comment "Move hyperref here" (around line 61)
- Close the editor
