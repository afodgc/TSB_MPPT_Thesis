# Afonso Coelho PIC2

This repo contains the state of the art and solucion proposal of Afonso Coelho master thesis named "Fast response MPPT switched charger for the Técnico Solar Boat". 

PDF file: [Link](Main_Document.pdf)

## LaTeX Document Template
This repo used a GitHub latex repo and a latex template made by Rui Santos Cruz. Both templates were combined as like. Following is explained how to set up vs code for latex


## 🚀 Quick Start

### Prerequisites

1. **Install TeX Live**:
   - **Ubuntu/Debian**: `sudo apt update && sudo apt install texlive-full`
   - **Fedora**: `sudo dnf install texlive-scheme-full`
   - **macOS**: Download from [MacTeX](https://www.tug.org/mactex/)
   - **Windows**: Download from [TeX Live](https://www.tug.org/texlive/)

2. **Install VS Code Extension**:
   - Open VS Code
   - Go to Extensions (Ctrl+Shift+X)
   - Search for "LaTeX Workshop" by James Yu
   - Install the extension

### Usage

1. **Clone or download** this template
2. **Open the folder** in VS Code
3. **Edit document** for your content
4. **Compile the document** by opening `main.tex` in VS Code and pressing Ctrl+Alt+B

## 🏗️ Building the Document

### Using LaTeX Workshop (VS Code)
1. Open `main.tex`
2. Use one of these methods:
   - Press `Ctrl+Alt+B` to build
   - Press `Ctrl+Alt+V` to view PDF
   - Use Command Palette (`Ctrl+Shift+P`) → "LaTeX Workshop: Build LaTeX project"

### Using Command Line
```bash
# Basic compilation
pdflatex main.tex

# With bibliography (if using BibTeX)
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```



## 🎨 Tips for Usage

1. **Keep images organized** in the `Images/` directory with descriptive names
2. **Use consistent formatting** across all section files
3. **Comment your code** for future reference
4. **Use labels and references** for figures, tables, and equations
5. **Compile frequently** to catch errors early



## Tips Added by Afonso
### How to hide trash files in vscode 

1. Open the command palette (Ctrl+Shift+P) and type Preferences: Open Settings (JSON).
2. Add or edit the files.exclude section like this:
```yaml
{
  "files.exclude": {
    "**/*.log": true,
    "**/*.aux": true,
    "**/*.out": true,
    "**/*.maf": true,
    "**/*.mtc*": true,
    "**/*.fls": true,
    "**/*.loc": true,
    "**/*.blg": true,
    "**/*.soc": true,
    "**/*.gz": true,
    "**/*.fdb_latexmk": true,
    "**/*.bbl": true,
    "**/*.toc": true
  }
}
```
---
### Good VScode extensions for latex
1. Latex Workshop
2. Code Spell Checker
4. vscode-pdf (pdf visualizer)
3. vscode-icons (just for better icons)
5. LTeX (grammar and spell check)


---
### How to ignore trash files when using git 

1. Create a .gitignore file
2. Copy my gitignore (basically ignores all files except PDF and latex files)

---

### Wrap text
1. Alt+Z : this command lets you see one full line without scrolling
