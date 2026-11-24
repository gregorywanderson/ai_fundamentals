# Making Sense of AI

**How AI Works, How It Is Changing, and How to Evaluate It**  
*A Primer for Faculty, Students, and Staff*

Gregory Anderson  
Department of Physics, Northeastern Illinois University  
ORCID: [0000-0003-0346-7258](https://orcid.org/0000-0003-0346-7258)

## Download

- **[Download the PDF (working draft)](ai_fundamentals.pdf)**

## Abstract

This document introduces artificial intelligence to faculty, students, and staff across academic disciplines. It explains how contemporary AI systems are trained and generate responses, and distinguishes AI models from the applications and agents built on them. It then examines why AI capabilities have advanced rapidly, why progress varies across tasks, and how that progress is measured. Finally, it explains why capability does not guarantee reliability. Two recurring examples—a historian's question about the French Revolution and an environmental scientist's question about ozone trends in Chicago—illustrate the document's central point: the important question about an AI response is not whether it sounds convincing, but what information and methods produced it and how its conclusions can be checked. The document focuses on foundational understanding rather than classroom pedagogy or institutional policy. It is intended to support AI literacy training and to serve as a reference.

## Contents

1. What Is Artificial Intelligence?
2. How Do AI Models Work?
3. AI Models, Applications, and Agents
4. How AI Capabilities Are Advancing
5. Limitations and Critical Evaluation
6. Further Reading and Resources
7. Afterword: Reflections on Writing with AI

The document also includes learning outcomes, an introduction built around two recurring queries, and references.

## Files

| File | Description |
|------|-------------|
| `ai_fundamentals.pdf` | Compiled document |
| `ai_fundamentals.tex` | Main LaTeX source |
| `ai.bib` | Bibliography (BibTeX) |
| `optimization_figure.tex` | TikZ source for Figure 2 |
| `images/` | Supporting figure files |

To build from source, use a LaTeX distribution with support for tagged PDF output:

```sh
pdflatex ai_fundamentals
bibtex ai_fundamentals
pdflatex ai_fundamentals
pdflatex ai_fundamentals
```

## Accessibility

The PDF includes tagged document structure, language metadata, figure alternative text, and semantic table headers. Accessibility review is ongoing. Automated PDF/UA-2 validation of the current version reports two issues associated with decorative footnote separator lines; omitting those lines produces a passing automated validation result. Automated validation does not replace manual reading-order and screen-reader testing.

## Status

Working draft. Comments and corrections are welcome; please [open an issue](https://github.com/gregorywanderson/ai_fundamentals/issues).

## AI Assistance

AI applications (ChatGPT, Claude, and Gemini) assisted with brainstorming, drafting, editing, and developing illustrations. The document's conceptual framing, selection of examples, fact checking, and substantive revisions were directed by the author, who retains responsibility for all of its content. Further reflections on the writing process appear in Section 7.

## Citation

A DOI will be added when the document is archived on Zenodo. Until then, please cite as:

> Anderson, G. (2026). *AI Fundamentals: How AI Works, How It Is Changing, and How to Evaluate It—A Primer for Faculty, Students, and Staff.* Working draft. https://github.com/gregorywanderson/ai_fundamentals

## License

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/). You may share and adapt the material, including for commercial purposes, provided you give appropriate credit and distribute adaptations under the same license.
