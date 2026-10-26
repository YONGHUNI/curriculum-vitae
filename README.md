# Curriculum Vitae

LaTeX source for Yong-Hun Suh's academic CV.

## Build

The main document is `CV.tex` and uses XeLaTeX.

```bash
latexmk -xelatex -interaction=nonstopmode -halt-on-error CV.tex
```

GitHub Actions automatically builds `CV.pdf` on pushes to `main` and provides it as a downloadable workflow artifact.

The blog publication workflow is intentionally separate and not configured here.
