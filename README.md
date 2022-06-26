# B. Math $\LaTeX$ Notes

Notes for Courses of B. Math(Hons.) programme by 1st year (2021-'22) students at [ISI Bangalore](https://www.isibang.ac.in)

## Available Notes

[![Compile Latex and put pdfs in asset-pdf branch](https://github.com/BikramHalder/BMath-LaTeX-Notes-2021-24/actions/workflows/build-latex.yml/badge.svg)](https://github.com/BikramHalder/BMath-LaTeX-Notes-2021-24/actions/workflows/build-latex.yml)

- Semester II
  - [X] Analysis II
  - [X] Computer Science II (Numerical Computing)
  <!-- - [ ] Statistics I (Intro to Stat with R) -->

## Contributing (B. Math 1st year people)

### Get Started

```bash
git clone https://github.com/BikramHalder/BMath-LaTeX-Notes-2021-24
```

### Required pieces of software

#### [Git](https://git-scm.com/downloads)

#### LaTeX

- Windows (any 1)
  - [MikTeX](https://miktex.org/download) | [Setup](https://miktex.org/howto/install-miktex)
    - `winget install miktex`
    - [Resolve MikTeX issue](https://tex.stackexchange.com/questions/280631/new-font-file-not-found-with-miktex-installation)
  - [TeX live](https://tug.org/texlive/windows.html)
- macOS
  - [Mac TeX](https://www.tug.org/mactex/) (TeX live included)
    - `brew install mactex`
- Linux
  - [TeX live](https://www.tug.org/texlive/quickinstall.html)

#### Text Editor/IDE (any 1)

- [Vim](https://www.vim.org/download.php) (Linux/macOS)
- [Emacs](https://www.gnu.org/software/emacs/)
- [Microsoft Visual Studio Code](https://code.visualstudio.com/)
  - LaTeX in VS Code
    - [LaTeX on VS Code](https://medium.com/@rcpassos/writing-latex-documents-in-visual-studio-code-with-latex-workshop-d9af6a6b2815)
    - [VSCode LaTeX workshop extension](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)
    - [Perl required for LaTeX workshop extension](https://www.activestate.com/products/perl/)
      - `winget install ActiveState.ActivePerl` (Windows)
  - VS Code and GitHub
    - [Git in VS Code](https://code.visualstudio.com/docs/editor/versioncontrol)
    - [GitHub in VS Code](https://code.visualstudio.com/docs/editor/github)

#### Drawing tool and related LaTeX plugin

- [Inkscape drawing tool for figures in LaTeX](https://castel.dev/post/lecture-notes-2/)
  - `winget install Inkscape.Inkscape` (Windows)
- [TexText](https://github.com/textext/textext/releases/tag/1.8.1)
- [Resolve Issues for Tex Text](https://textext.github.io/textext/usage/troubleshooting.html)

### Build

```bash
pdflatex <file_name>.tex
```
