# CV_MaD

LaTeX repository for a CV and cover letter.

## Files

- `cv.tex`
- `cover-letter.tex`

## GitHub Actions

The workflow in `.github/workflows/latex-build.yml` runs on every push, compiles both LaTeX files, and uploads PDF artifacts named with:

- the UTC build date
- a workflow version based on the GitHub run number and run attempt

This keeps artifacts unique even when multiple builds happen on the same date.

## Local build

Compile locally with:

```bash
pdflatex cv.tex
pdflatex cover-letter.tex
```
