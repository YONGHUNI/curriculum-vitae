# Curriculum Vitae

Academic CV of Yong-Hun Suh, compiled from `CV.tex` using XeLaTeX.

## Reproducible build (NixOS / Linux / CI)

The local build and GitHub Actions use **the same pinned Nix flake**.
The fonts under `Fonts/` and the custom `simpleresumecv.cls` and
`datetime2.sty` remain in the repository.

```bash
nix develop
latexmk -xelatex -file-line-error -halt-on-error -interaction=nonstopmode -pdfxe CV.tex
```

Or run it in one command:

```bash
nix develop --command latexmk -xelatex -file-line-error -halt-on-error -interaction=nonstopmode -pdfxe CV.tex
```

Clean generated auxiliaries (does not delete CV.pdf):

```bash
nix develop --command latexmk -c CV.tex
```

`flake.lock` pins the Nixpkgs revision so both environments use the
same TeX Live package set, XeLaTeX engine, and latexmk. On GitHub Actions,
the PDF is built, uploaded as a workflow artifact, committed to `main`
when changed, and prepared for GitHub Pages.

The Pages deployment requires **Settings → Pages → Build and deployment:
GitHub Actions** in the repository settings.
