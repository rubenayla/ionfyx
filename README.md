# Ionfyx Project

This repository contains a credibility analysis of Ionfyx's infrared pain-relief claims, available in both [English](ionfyx_report.pdf) and [Spanish](informe_ionfyx.pdf).

## Generating PDFs from LaTeX Documents

To generate the PDF documents from the LaTeX source files, follow these steps in VS Code:

1.  **Open the desired LaTeX file:**
    *   For the English version: `latex/main.tex`
    *   For the Spanish version: `latex_spanish/main.tex`

2.  **Open the Command Palette:** Press `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (macOS).

3.  **Search for and select "LaTeX Workshop: Build LaTeX project".**

4.  **Choose the appropriate build recipe:**
    *   For the English PDF (`ionfyx_report.pdf`): Select "Compile to Root (ionfyx_report)"
    *   For the Spanish PDF (`informe_ionfyx.pdf`): Select "Compile to Root (informe_ionfyx)"

This will compile the `.tex` file and output the PDF directly into the root of this project directory.

## Generated PDF Documents

*   [English Report: ionfyx_report.pdf](ionfyx_report.pdf)
*   [Spanish Report: informe_ionfyx.pdf](informe_ionfyx.pdf)
