# latex_GA
This is a template repository for compiling latex documents with Github Actions.

[Download the latest release (pdf)](https://github.com/remdelaportemathurin/phdthesis/releases/latest/download/main.pdf)

To compile locally simply run:

```
docker run --rm -it -v $(pwd):/workdir danteev/texlive:edge latexmk -pdf main.tex
```

