# Resume

LaTeX source for my resume.

## Edit

- Update section content in `sections/`.
- Add or edit jobs in `experience/`, then include them from `sections/experience.tex`.
- Add or edit references in `references/`, then include them from `sections/references.tex`.

## Build

Run from the project root:

```bash
latexmk -pdf resume.tex
```
