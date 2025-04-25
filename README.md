# Personal Resume

This repository contains the LaTeX source code for my personal resume.

## 📜 Description

This project uses LaTeX to generate a professional resume. The main TeX file (in my case `Awad_Yousef.tex`) contains the structure and content.

## 🛠️ Building

To compile the resume from the source code, you will need a LaTeX distribution installed (such as [TeX Live](https://www.tug.org/texlive/), [MiKTeX](https://miktex.org/), or [MacTeX](https://www.tug.org/mactex/)).

You may also need specific LaTeX packages depending on the template used. Check the `libraries.tex` file preamble (the section before `\begin{document}`) for `\usepackage{...}` commands to see the requirements.

Once you have the necessary setup, navigate to the repository directory in your terminal and compile the resume using:

```bash
pdflatex Awad_Yousef.tex # Change name to your Last_First.tex
```

*Note: You might need to run the command multiple times if your resume includes features like a table of contents, bibliography, or complex cross-references.*
