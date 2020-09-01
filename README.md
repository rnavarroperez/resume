# resume
My Resume in LaTeX

The source code allows to generate english and spanish versions of the CV.

To generate the english version one simply executes inside of the `src/` directory
```
latexmk -pdf navarro-cv-en.tex
```

To generate the spanish version one executes inside of the `src/` directory
```
latexmk -pdf navarro-cv-es.tex
```

When using sublime, one can compile from the editor the english version when
inside of any of the `.tex` files (except for `navarro-cv-es.tex`)