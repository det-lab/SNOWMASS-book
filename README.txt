

This directory contains a template for the Snowmass 2021 Book.

To build the book, just type   “pdflatex SnowmassBook.tex” in this directory.  There are two ways to build the book.   As the file is set up now, the file will generate the complete Snowmass book, eventually about 2000 pages.  This book will include the Frontmatter, the Summary paper, the major Frontier reports, and a Glossary, followed by the various Topical Group reports.  [Note: As of now, only the Topical Group reports through the Rare Processes Frontier are included.  I need a little more time to include everything.]    To generate a smaller book that ends with the Glossary, uncomment the statement  \end{document}  just under the Glossary.   

Remember the incantation that you should run pdflatex 3 times in succession to properly define all references.  After you have done this, your pdf file should look like the file SnowmassBook-result.pdf included here.

This distribution can also be used to build specific group reports.

To build only the Energy Frontier report, type “pdflatex SnowmassBook-Energy.tex”.  To build other Frontier reports, modify the file SnowmassBook-Energy.tex by commenting out Energy and commenting in the desired frontier.

To build only the Neutrino NF01 report, type “pdflatex SnowmassBook-NOscillations.tex”.  To build other Topical Group reports, modify the file SnowmassBook-NOscillations.tex by commenting out this group name and commenting in the desired group.

I recommend that each group work ONLY WITHIN THEIR OWN FOLDER, without touching the master file or the material in any other folder.   Each group should prepare the LaTeX and pdf files for their own report, and post this on the arXiv, and notify me when this is done.  I will then take the responsibility for the editing required to make the whole package LaTeX together as a single book.

To create a Frontier report, you may delete the folders for the Frontmatter and the other Frontiers.  However, please keep all of the auxiliary files in at the top level of this distribution (e.g.  fancyhea.sty, tcibook.cls).

To create a Topical Group report, you may delete all of the folders except yours.  However, please keep your folder in the folder of the Frontier that you belong to. And please keep all of the auxiliary files in at the top level of this distribution (e.g.  fancyhea.sty, tcibook.cls).

Please notice that I have made the following conventions for the author lists:

1. The authors of the summary paper, listed on the cover page, are the Frontier conveners, the DPF chairs, and the Editorial Committee.
2. The authors of the Frontier reports are the Frontier conveners and the Topical Group conveners.
3. The authors of the Topical Group reports are the Topical Group conveners plus any members of the community that contribute to the report.

This follows the decisions that we made for Snowmass 2013.   The conveners should decide whether to keep these conventions or change them.  However, the whole volume should follow a uniform set of conventions.  Please let me know what your decision is. 
    
If you prepare your LaTeX using Overleaf, please be sure to upload all of the needed files from this distribution into your Overleaf directory, including the top-level auxiliary files.   Each group should use its own Overleaf or other document system, in order to avoid LaTeX conflicts.

If you would like to use BibTeX for your references, that is optional. Please look at the instructions in each LaTeX file just above the references.  I supply the JHEP.bst style file with this distribution; this file plays well with INSPIRE. 

I have provided a simple macropackage   workshopsymbols.tex .   The macros are described in the file   aboutworkshopsymbols.pdf .   Please resist the urge to dump your full personal macropackage into your LaTeX files.  This will undoubtedly result in conflicts that are difficult to resolve.

Please limit the size of any individual subgroup report to about 3Mb.  In particular, please reduce the size of any oversize figures.  All figures should be in pdf or png format.

For the final report, I will create a web page (indexed in INSPIRE) that serves the reports individually as well as in the huge book. 

Please send any feedback or corrections to :  mpeskin@slac.stanford.edu .

Thank you,

Michael Peskin   

