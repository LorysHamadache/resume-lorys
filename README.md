# Lorys Hamadache – Resume Repository

This repository contains all current and past versions of my resume and cover letters, in both InDesign and LaTeX formats.

---

## 📁 Structure

### `indesign-cv/`

InDesign version of my CV

- `latest_cv.indd` – Source file
- `LorysHamadacheCV-20241220.pdf` – Exported PDF

### `tex-cv/`

LaTeX-based resume and cover letter using the `moderncv` template repo

- `cv-lorys/` – My working LaTeX project
  - `cv.tex` – CV source
  - `cover-letter.tex` – Cover letter source
  - `data-inputs/` – Assets (images, `.bib`, etc.)
  - `layout-styles/` – Custom LaTeX styles
  - `output/` – Compiled files (ignored by git)
- `moderncv/` – Full clone of the [`moderncv`](https://github.com/moderncv/moderncv) repo for full styling control

### `_old/`

Archived past CVs and templates

- `2020-endofstudies \inDesign/` – Early InDesign templates and exports
- `2021–2024/` – Older versions of the CV

### `visual-assets/`

Visual materials (e.g. cover thumbnails)

- `.png`, `.psd` assets for display or branding

---

## 🛠 Build Instructions (LaTeX)

```bash
cd tex-cv/cv-lorys
latexmk -pdf -output-directory=output cv.tex
latexmk -pdf -output-directory=output cover-letter.tex
```

---

## 📌 Notes

- `moderncv/` is an unmodified clone for full local build.
- Contact details may be redacted in public outputs.
- Old files are kept in `_old/` for historical reference.

---

## License

This repository is not licensed for reuse or redistribution. Shared for personal reference only.
