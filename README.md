# Enabling the Frontier

*A Playbook for Building and Leading Cutting-Edge R&D Teams* — Eric Forbes. Working draft.

32 principles across 5 sections, in the format of *48 Laws of Power*: bold principle stated first, stories follow and support.

## Source of truth

**`CLAUDE.md` is the canonical reference** for the book's structure, story bank, and open
structural questions. The LaTeX files are the manuscript; when they disagree, `CLAUDE.md` wins.
Stories are never attached to principles without Eric's explicit confirmation.

## Layout

```
CLAUDE.md            Source of truth: structure, story bank, working rules
main.tex             Master document (book class) — inputs all sections
outline.tex          Standalone one-glance structural outline (article class)
preamble.tex         Shared packages, colors, macros (\principle, \sectionintro, \tbd, storybox)
sections/            Front matter + one file per book section
output/main.pdf      Compiled book
output/outline.pdf   Compiled structural outline
```

## Building

Requires a TeX Live installation with `titlesec`, `mdframed`, `tocloft`, and `enumitem`
(Debian/Ubuntu: `texlive-latex-recommended` + `texlive-latex-extra`).

```bash
pdflatex main.tex && pdflatex main.tex     # book (run twice for TOC/refs)
pdflatex outline.tex                        # one-page structural outline
```

Editorial placeholders are marked with the red-italic `\tbd[...]` macro — everything inside
one is scaffolding awaiting Eric's input, not book content.
