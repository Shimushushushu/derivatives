# Elegant derivatives-**derivatives**

## Introduction
This package simply wraps some commonly-used commands to typeset derivatives.

## Usage

To compile the package from bottom up, including the documentation, run the
following commands.  If only the `.sty` file is desired, just run the first
command.
```
pdflatex derivatives.ins
pdflatex derivatives.dtx
makeindex -s gind.ist -o derivatives.ind derivatives.idx
makeindex -s gglo.ist -o derivatives.gls derivatives.glo
biber derivatives
pdflatex derivatives.dtx
```
Then, put them (`.sty`, `.ins`, `.dtx`, and probably `.pdf`) in
`<TeX-directory>/texmf-local/tex/latex/derivatives/`, or simply
`<TeX-directory>/texmf-local/`, then run `texhash` to finish the installation.

## Disclaimer
See LPPL-1.3c, and reach me by 