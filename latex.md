# Latex

[Source](https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes)

## The preamble of a document

Everything in your .tex file before **\begin** is called the preamble. In the preamble you define the type of document you are writing, the language you are writing in, the packages you would like to use (more on this later) and several other elements. For instance, a normal document preamble would look like this:

```latex
\documentclass[12pt, letterpaper]{article}
\usepackage[utf8]{inputenc}
```

