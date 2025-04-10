# Curriculum Vitae

![LaTeX](https://img.shields.io/badge/LaTeX-blue?style=for-the-badge&logo=latex)

This repository contains the source files for my CV, written using **LaTeX**.

## Table of Contents

- [About](#about)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## About

This repository stores the LaTeX source code for my CV. It uses a clean and elegant design developed by [Aras Güngöre](https://github.com/arasgungore) that highlights key information effectively.

---

## Installation

### LaTeX Editors
You can open the ```main.tex``` file on the following editors for fast editing.
   - [Overleaf](https://www.overleaf.com/) (Online LaTeX editor)
   - [TeXstudio](https://www.texstudio.org/) (Desktop application)

### Installation on Linux (Debian/Ubuntu)

If you're using a Debian-based Linux distribution (e.g., Ubuntu), you can install the required LaTeX packages and tools using the following command:

```bash
sudo apt-get install --no-install-recommends pandoc texlive texlive-latex-extra texlive-extra-utils texlive-fonts-extra latexmk
```

This command installs: 

* pandoc : A universal document converter (optional, if you need to convert between formats).
* texlive : The core LaTeX distribution.
* texlive-latex-extra : Additional LaTeX packages.
* texlive-extra-utils : Extra utilities for LaTeX.
* texlive-fonts-extra : Additional fonts for LaTeX.
* latexmk : A Perl script for automating LaTeX document compilation.

---

## Usage

To compile the CV into a PDF:

```bash
pdflatex main.tex
```

or

```bash
latexmk -pdf main.tex
```