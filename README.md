# Generic TeX Writer for the Pandoc Document Converter (bachelor's thesis)

## Abstract

Pandoc is a utility able to convert between dozens of document formats
including TeX formats such as LaTeX and ConTeXt, but it provides
no support for other well-known TeX formats such as plain TeX.
Moreover, it offers no way to influence the style of its output. The goal
of this thesis is to integrate Pandoc with the TeX package Markdown,
which allows users to embed blocks of text in the lightweight markup
language Markdown into their documents, as well as change the styling of
individual elements. Using macros from the Markdown package, the author
produces a proof of concept for a generic TeX writer for Pandoc, which
is capable of producing output for any TeX format based on plain
TeX.

## Typesetting

`$ latexmk thesis.tex -pdf`

## Attachments

The attached archive mentioned at the end contains a ZIP of [version 0.1 of drehak/pandoc-to-markdown](https://github.com/drehak/pandoc-to-markdown/releases/tag/0.1).
