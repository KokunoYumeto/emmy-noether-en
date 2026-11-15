# Emmy Noether — Mathematical works in English

An English translation of the collected mathematical works of Emmy Noether (1882–1935): papers 1–43, the lectures
*Algebra der hyperkomplexen Größen* (winter semester 1929/30) written up by M. Deuring, and H. Kapferer's paper with
its supplement written jointly with E. Noether, followed by the bibliography and the lists of short communications,
book reviews and books produced with Emmy Noether's participation. The edition is published as PDF and as editable
LaTeX.

[**Read the base text — PDF, 463 pages**](https://github.com/KokunoYumeto/emmy-noether-en/releases/download/noether-en-2026-11-15-r2/01-noether-en-base.pdf) ·
[Text with emendations — PDF, 468 pages](https://github.com/KokunoYumeto/emmy-noether-en/releases/download/noether-en-2026-11-15-r2/04-noether-en-emendations.pdf) ·
[All files of the edition of 27 October 2026](https://github.com/KokunoYumeto/emmy-noether-en/releases/tag/noether-en-2026-11-15-r2)

## How this was made: AI's failure modes, and what we do about them

Everything here was produced by AI. The translation was made in a first pass mostly by GPT-5.6 Sol (OpenAI Codex,
reasoning effort ultra) (July and August 2026). Its formulas were then brought into line with the German text, which Claude Opus 5.5 at
effort max compared page by page with Noether's printed originals (785 page checks, 26 October 2026), in automatic and
hand rounds by Claude Opus 5.5 at effort max (26-27 October; 2,570 lines in the last hand round), against the known
failures of AI translation of mathematics: renamed letters, formulas changed or dropped, statements narrowed, passages
reworked or garbled, sentences and displays dropped, broken layout. Every change passes a release filter, and every PDF
is checked for lines running into the margin (Claude Opus 5.5 at effort high, 15 November). No person has reviewed the
translation. What was done in each round, the measured figures and what is still open:
[How this was made](https://github.com/KokunoYumeto/emmy-noether#how-this-was-made-ais-failure-modes-and-what-we-do-about-them).

## How it was made

The English text is AI-translated, mostly by GPT-5.6 Sol (OpenAI Codex, reasoning effort ultra), from
the project's AI-transcribed German text of the original printings, edition NOETH-DE-ED-0021. Corrections and
typesetting were produced by OpenAI Codex — GPT-6 Astra, Ultra effort, on 23–24 October 2026, and by Claude Opus 5.5
(Anthropic, effort max) on 26–27 October 2026, which brought the formulas into line with the German text as read from Noether's
printed pages. The build program was written by OpenAI Codex — GPT-6 Astra, Ultra effort, on 24 October 2026.

## Status

The edition contains all the works listed above. The translation has not been reviewed by a person, and errors may
remain; a few formulas may still follow the earlier German transcription where the translation words a passage in its
own way. Corrections are welcome through the [issues page](https://github.com/KokunoYumeto/emmy-noether-en/issues).

## Contents and where to start

The edition has two text layers, each as a PDF, a single editable LaTeX file and a source archive:

| Text layer | PDF | LaTeX | Sources |
|---|---|---|---|
| Base text: keeps the readings of the original printings; editorial notes discuss the readings in question | [PDF, 463 pp.](https://github.com/KokunoYumeto/emmy-noether-en/releases/download/noether-en-2026-11-15-r2/01-noether-en-base.pdf) | [LaTeX](https://github.com/KokunoYumeto/emmy-noether-en/releases/download/noether-en-2026-11-15-r2/02-noether-en-base.tex) | [ZIP](https://github.com/KokunoYumeto/emmy-noether-en/releases/download/noether-en-2026-11-15-r2/03-noether-en-base-sources.zip) |
| Text with emendations: applies the editorial corrections, each explained in an editorial note | [PDF, 468 pp.](https://github.com/KokunoYumeto/emmy-noether-en/releases/download/noether-en-2026-11-15-r2/04-noether-en-emendations.pdf) | [LaTeX](https://github.com/KokunoYumeto/emmy-noether-en/releases/download/noether-en-2026-11-15-r2/05-noether-en-emendations.tex) | [ZIP](https://github.com/KokunoYumeto/emmy-noether-en/releases/download/noether-en-2026-11-15-r2/06-noether-en-emendations-sources.zip) |

[SHA-256 checksums](https://github.com/KokunoYumeto/emmy-noether-en/releases/download/noether-en-2026-11-15-r2/07-noether-en-SHA256SUMS.txt).
The same files are in [`editions/2026-10-24-r2/en/`](editions/2026-10-24-r2/en/).

To build a PDF: the single LaTeX file contains every source file with its preamble. The Python program
[`build.py`](editions/2026-10-24-r2/en/build.py) extracts the files, compiles them with XeLaTeX and joins the PDFs in
reading order; it needs Python 3, pypdf and the TeX packages and fonts named in the preambles. The ZIP archive holds
the same sources in their original structure, with the build program.

The edition of August 2026 is kept in [`reader/`](reader/) (linked PDF) and [`source/`](source/) (LaTeX), with its
check records in [`evidence/`](evidence/). The German text and the editions in other languages are listed on the
[central page](https://kokunoyumeto.github.io/emmy-noether/), together with the known differences between the editions.

## Sources and credits

- The mathematical works are by Emmy Noether and the co-authors named in them: Werner Schmeidler (Paper 17), R. Brauer
  (Paper 32), and R. Brauer and H. Hasse (Paper 38). The 1929/30 lectures were written up by M. Deuring. Work 45 is by
  H. Kapferer, with a supplement written jointly with E. Noether. Original publication details, signatures and
  citations are given in the texts.
- The translation was made from the German edition NOETH-DE-ED-0021 (source SHA-256
  `0B7ED4189AA4AB46C4879DC7CC31C55DFFC20DA2C13C17CDE8FA6BE6897F21C9`). Its formulas follow the German source text
  compared page by page with the printed originals,
  [release noether-de-2026-10-26](https://github.com/KokunoYumeto/modern-latex-manuscripts/releases/tag/noether-de-2026-10-26).

## Rights

Emmy Noether died in 1935, so her writings are in the public domain in the European Union and wherever the term of protection ends 70 years after the author's death. In the United States, her papers first published in 1931 or later remain protected until 95 years after publication (the papers of 1931 become free on 1 January 2027). To the extent the publisher holds any rights in the AI-produced translation, corrections and typesetting, they are dedicated to the public domain under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). The lectures written up by M. Deuring, the work of H. Kapferer and the contributions of the named coauthors are not covered by this statement; their rights remain with their authors or heirs.