# cv-latex

LaTeX CV project converted from `cv placement officiel.pdf`.

## Compile with Tectonic

Install Tectonic, then run:

```sh
tectonic --outdir build main.tex
```

The compiled CV will be created at `build/main.pdf`.

## Files

- `main.tex` - ATS-friendly one-page LaTeX CV source.
- `cv placement officiel.pdf` - original uploaded CV.
- `.gitignore` - ignores LaTeX build outputs and common temporary files.

## Notes

The LaTeX source preserves the information from the original PDF in an ATS-friendly one-page format.
