# Compiling LaTeX

For "classic" Pdflatex and Bibtex, you can try to compile your files with the following commands:

```bash
pdflatex bwHPC-template.tex
bibtex bwHPC-template
pdflatex bwHPC-template.tex
pdflatex bwHPC-template.tex
```

For Xelatex/Lualatex and Biber you can try to compile your files with the following commands:
```bash
xelatex bwHPC-template.tex
biber bwHPC-template
xelatex bwHPC-template.tex
xelatex bwHPC-template.tex
```

You can mix and test *latex and Bibtex/Biber as you wish.
We will probably use Xelatex and Biblatex/Biber for the final document.
This document has been tested with Texlive 2020-2023.

The Overleaf link for this template is:

https://www.overleaf.com/read/vbdzmrfjrntj#c56916

The Github template link is:

https://github.com/nemo-cluster/10th-bwHPC-Symposium-Freiburg-Template
