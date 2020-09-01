# The Consistent Histories Approach to the Stern-Gerlach Experiment

Bachelor's thesis for the physics program at Oregon State University.

[Based off of zachscrivena's thesis template](https://github.com/zachscrivena/simple-thesis-dissertation)

## Compiling

The main XeLaTeX source file is `Thesis.tex`; the compiled document is `Thesis.pdf`.

Instructions for compiling the document (TeX &rarr;(XeLaTeX)&rarr; PDF):

- **Method 1:** Use `latexmk` for fully automated document generation:
	- `latexmk -xelatex "Thesis.tex"`
	(add the `-pvc` switch to automatically recompile on changes)

- **Method 2:** Use `xelatex` directly:
	- `xelatex "Thesis.tex"`
	(run multiple times to resolve cross-references if needed)

## License

This is free and unencumbered software released into the public domain.
For more information, please see the file `LICENSE` or refer to <http://unlicense.org>.
