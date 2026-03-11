# Pardot Demo Slides

14-slide LaTeX Beamer presentation showcasing Pardot, an AI teaching assistant for CS education.

## Build Instructions

### Prerequisites

Install a LaTeX distribution with Beamer support:

```bash
# Ubuntu/Debian
sudo apt-get install texlive-latex-base texlive-latex-recommended \
  texlive-latex-extra texlive-fonts-recommended texlive-pictures

# macOS (via Homebrew)
brew install --cask mactex

# Arch Linux
sudo pacman -S texlive-core texlive-latexextra
```

### Compile

```bash
pdflatex slides.tex
pdflatex slides.tex   # run twice for proper cross-references
```

The output is `slides.pdf`.

### CI/CD

Pushing to `main` triggers a GitHub Actions workflow that compiles the PDF and deploys it to GitHub Pages.

## Slide Overview

| # | Title |
|---|-------|
| 1 | Title slide |
| 2 | Problem: Faculty challenges |
| 3 | Solution: AI TA overview |
| 4 | Setup: Discord + GitHub + course materials |
| 5 | Student interaction example (screenshot placeholder) |
| 6 | Scaffolded response example |
| 7 | Grading: before & after |
| 8 | Grading output: rubric feedback |
| 9 | Proactive monitoring |
| 10 | Academic integrity guardrails |
| 11 | Guardrails example |
| 12 | Results: time saved & consistency |
| 13 | Technical architecture |
| 14 | Q&A / Contact |

