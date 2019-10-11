# thesis-template
Latex template for PhD thesis

Note: for simplicity, only one empty page is inserted at page break after the title page. One can manually insert blank pages using 
```
\newpage\null\thispagestyle{empty}\newpage
``` 
(as shown in the example) to avoid chapters starting from even page numbers.

Overview of directory structure:
```
thesis-template
├── chapters
│   ├── chapter1intro.tex
│   ├── chapter2charmm.tex
│   ├── chapter3lammps.tex
│   ├── chapter4namd.tex
│   └── chapter5conclusions.tex
├── figures
│   ├── 1
│   │   └── latex-logo.png
│   ├── 2
│   │   └── charmm-logo.png
│   ├── 3
│   │   └── lammps-logo.png
│   └── 4
│       └── namd-logo.png
├── misc
│   ├── abbreviation.tex
│   ├── abstract.tex
│   ├── acknowledgment.tex
│   ├── dedication.tex
│   ├── reference.bib
│   └── titlepage.tex
└── thesis.tex
```

TODO:
- [ ] fix minor bugs when compiling.
- [ ] add all details once thesis submitted.