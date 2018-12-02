# simple-response-corrections

Template for a simple response and list of corrections, to editors or reviewers, in LaTeX.

**Website:**<br>
https://github.com/zachscrivena/simple-response-corrections

**Lead author:**<br>
Zach Scrivena (https://github.com/zachscrivena/)

**Compiled sample document:**<br>
[ResponseCorrections.pdf](https://raw.githubusercontent.com/zachscrivena/simple-response-corrections/master/ResponseCorrections.pdf)

**Sample pages (click to enlarge):**

<img height="500" src="https://raw.githubusercontent.com/zachscrivena/simple-response-corrections/master/Miscellaneous/ResponseCorrections-01.png" alt="ResponseCorrections-01">

<img height="500" src="https://raw.githubusercontent.com/zachscrivena/simple-response-corrections/master/Miscellaneous/ResponseCorrections-02.png" alt="ResponseCorrections-02">

<img height="500" src="https://raw.githubusercontent.com/zachscrivena/simple-response-corrections/master/Miscellaneous/ResponseCorrections-03.png" alt="ResponseCorrections-03">

## Main Features

- Simple template that can be further customized or extended.
- Template document contains numerous examples.

## Overview

The main LaTeX source file is `ResponseCorrections.tex`; the compiled document is `ResponseCorrections.pdf`.

Instructions for compiling the document (TeX &rarr;(pdflatex)&rarr; PDF):

- **Method 1:** Use `latexmk` for fully automated document generation:
	- `latexmk -pdf "ResponseCorrections.tex"`
	(add the `-pvc` switch to automatically recompile on changes)

- **Method 2:** Use `LaTeX` directly:
	- `latex "ResponseCorrections.tex"`
	(run multiple times to resolve cross-references if needed)

## License

This is free and unencumbered software released into the public domain.
For more information, please see the file `LICENSE` or refer to <http://unlicense.org>.
