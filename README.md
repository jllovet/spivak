# Spivak's Calculus

This repo is in conjunction with The Yellow Pigs Society, a study group started for studying Michael Spivak's Calculus.
It contains LaTeX source code of notes, proofs, and articles written about Spivak's Calculus and related texts on mathematical proofs.

## Getting Started

This will get you up and running.

### Dependencies

First, set up a LaTeX environment.

- [LaTeX](https://www.latex-project.org/)
    - [Guide for Mac Install](https://sourabhbajaj.com/mac-setup/LaTeX/)
- [TexMaker](https://www.xm1math.net/texmaker/index.html) (note: already installed on Mac with Homebrew install)

#### Optional

- [Visual Studio Code](https://code.visualstudio.com/)
    - [LaTeX-Workshop](https://github.com/James-Yu/LaTeX-Workshop)

### Hello World

To set up your first LaTeX file, save this into a `hello_world.tex`.
You can find this example under `000-getting-started/000-latex`.

```
\documentclass{article}
\begin{document}
Hello, world!
\end{document}
```

Then, open a terminal, and run this command.

```
xelatex hello_world.tex
```

This should produce a pdf file that you can read, along with a few other files. 

(I've chosen to use the `xelatex` command instead of the `latex` command, because it `xelatex` produces a .pdf directly, while you need a few more steps to get a .pdf if you use the `latex` command.)

I'll leave learning about those other steps and files as an exercise for the reader. 😉

Congratulations!

For real projects, I recommend you use one of the LaTeX GUI environments that are mentioned above to help speed up your writing.

For more instructions and guides on LaTeX, see the resources below.


## Resources

### The Math

- [Michael Spivak - Calculus](https://www.amazon.com/Calculus-Michael-Spivak/dp/0521867444/)
- [Micahel Hutchings - Introduction to Mathematical Arguments](https://math.berkeley.edu/~hutching/teach/proofs.pdf?fbclid=IwAR2dnYJ0OoC0EJRpgnEfqpoe870-tOVH0ePSn5FEywvKnpXv1XxdYNMEQtQ)
- [Daniel Solow - How to Read and Do Proofs](https://www.amazon.com/How-Read-Proofs-Introduction-Mathematical/dp/1118164024)

### LaTeX

- [The Not So Short Introduction to LaTeX](https://tobi.oetiker.ch/lshort/lshort.pdf)


#### Packages for Using LaTeX in Other Projects

- [react-latex]([https://github.com/zzish/react-latex) - React Component to render Latex

### Other Plain-Text Document Generation Languages

#### Markdown

- [Dillinger.io - A Web-Based Markdown Previewer with Some Built-In Examples](https://dillinger.io/)
- [Github Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
- [Markdown Guide](https://www.markdownguide.org/getting-started/)

#### ReStructuredText

- [Rest and Sphinx Memo](https://rest-sphinx-memo.readthedocs.io/en/latest/intro.html)
