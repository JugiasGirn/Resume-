# Resume-
Jugias Girn, Resume 
# Jugias Singh Girn — LaTeX Résumé

This repository contains the LaTeX source (`jugias_resume.tex`) for my one‑page résumé.  
Feel free to fork, adapt, or study it for your own use.

| PDF preview | Source |
|-------------|--------|
| 👉 **[Download latest built résumé](https://github.com/JugiasGirn/resume/releases/latest/download/jugias_resume.pdf)** | [`jugias_resume.tex`](./jugias_resume.tex) |

---

## 📄  Features

* **One‑page layout** optimized for recruiters & ATS parsing  
* Clean sections for Education, Work Experience, Projects, and Technical Skills  
* Simple command macros—easy to add new projects or jobs  
* Hyperlinked contact icons and project source‑code links  
* Compiles on Overleaf or any modern TeX distribution (TeX Live, MiKTeX)

---

## 🚀  Quick Start

### 1  Build on Overleaf (no install)

1. Sign in at <https://overleaf.com> → **New Project ▸ Upload Project**  
2. Drag‑drop `jugias_resume.tex` (and this repo’s other files).  
3. Overleaf auto‑compiles to PDF—download via **Menu ▸ Download PDF**.

*(This is the fastest option if you don’t have LaTeX locally.)*

### 2  Build locally with TeX Live / MiKTeX

```bash
# Clone the repo
git clone https://github.com/JugiasGirn/resume.git
cd resume

# Compile (Linux/macOS)
latexmk -pdf jugias_resume.tex

# or Windows (MiKTeX):
pdflatex jugias_resume.tex
