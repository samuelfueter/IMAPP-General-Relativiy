# General Relativity (IMAPP M1, UCA) - LaTeX documents

- `lecture_notes/GR_Lecture_Notes.tex` (+ `chapters/`): complete lecture notes. Compiled: `GR_Lecture_Notes.pdf`.
- `problems/GR_Problems_Solutions.tex`: the 4 problem sheets with complete solutions. Compiled: `GR_Problems_Solutions.pdf`.
- `common/preamble.tex`: shared packages and macros.

Build (run twice for references/TOC):

    cd lecture_notes && pdflatex GR_Lecture_Notes.tex && pdflatex GR_Lecture_Notes.tex
    cd ../problems  && pdflatex GR_Problems_Solutions.tex && pdflatex GR_Problems_Solutions.tex
