# Dragon Book Notes

These are my notes on the "Dragon Book".

## Structure/Setup

My notes are contained in the `compilers.tex` file. The minted package expects you to be building to an output directory called `out`. To compile to a pdf simply run

```bash
pdflatex  -shell-escape -output-directory="out"  "compilers.tex"
```