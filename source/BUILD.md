# Build the linked reader

Keep `Noether_English_ED0014.tex` and the PNG asset in the same directory, then
run two serial passes:

    xelatex -interaction=nonstopmode -halt-on-error -file-line-error Noether_English_ED0014.tex
    xelatex -interaction=nonstopmode -halt-on-error -file-line-error Noether_English_ED0014.tex

The checked release reader is bound to 10.5281/zenodo.21923146. Exact engine,
source, PDF, extraction, outline, and rendered-page QA identities are preserved
under `evidence/`; arbitrary future TeX installations are not asserted to
produce byte-identical PDF metadata.
