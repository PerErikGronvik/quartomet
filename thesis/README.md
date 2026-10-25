# Thesis starter

Edit `main.qmd`, keep references in `references.bib`, and put images in `figures/`.

Render from this directory with:

```powershell
quarto render main.qmd --to pdf
```

This project uses Quarto, LuaLaTeX, and the standard KOMA-Script `scrreprt` class. Body text uses Arial, 12 pt, 1.5 line spacing, and left alignment to match the report-format guidance. References use the Norwegian APA manual in English locale; the local CSL prints recorded access dates before DOI or URL links. No Python environment or test suite is required.

The PDF starts with a title page with the OsloMet logo and project details. Replace `ACITxxxx` with the course code. Figure, table, and code captions are bold; code captions use the `Code` label.