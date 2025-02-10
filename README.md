# Personal Resume

My professional resume/CV written in LaTeX.

## Prerequisites

You'll need a LaTeX distribution installed on your system. I would recommend:
- macOS: [MacTeX](https://www.tug.org/mactex/)
- Windows: [MiKTeX](https://miktex.org/)
- Linux: TeX Live (`sudo apt-get install texlive-full` for Ubuntu/Debian)

## Required Packages

The resume uses these LaTeX packages:
- article
- geometry 
- titlesec
- enumitem
- hyperref

These should be included in most standard LaTeX distributions.

## Compiling to PDF

### Using latexmk (recommended)
```bash
latexmk -pdf cv.tex
```

###  Manual compilation
```bash
pdflatex cv.tex
```

## License
Code is licensed under MIT License.