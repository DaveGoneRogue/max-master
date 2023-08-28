# Forked thesis-NTNU

This is a modification of CoPCSE@NTNUs LaTeX document class. Its purpose is to make a more friendly environment for writing mathematics while removing some redundancy.


Some other changes to this template are that it uses LuaLaTeX instead of pdflatex to compile pdfs. The main font of this document is libertine, and if using a recent tex distribution it should be included in the local installation. 

#### Building document locally
Option 1: Run/build the main tex file named 'thesis.tex' with your LaTex program of choice, such as Visual Studio Code, Sublime Text, TeXShop Atom, etc.
Option 2: Build the document locally using the attached 'makefile'. This requires that you have a LuaLaTeX compiler, such as ['texlive'](https://www.tug.org/texlive/), installed locally, which has to provide the commands 'lualatex' and 'biber'.
Option 3: Upload to overleaf and run there. s