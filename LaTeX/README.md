
# LaTeX

## 1. What I Learned

LaTeX is a document preparation system used to create professional documents, especially academic and technical documents. Instead of formatting everything manually, we write commands that control the structure and appearance of the document.

It is useful for assignments, research papers, mathematical documents, and engineering reports.

## 2. Basic Document Structure

A LaTeX document mainly consists of a preamble and a document body.

```latex
\documentclass[12pt,a4paper]{article}

\usepackage{amsmath}

\title{My First Document}
\author{Student Name}
\date{\today}
\begin{document}
\maketitle
\section{Introduction}
This is my first LaTeX document.

\end{document}
```

 `\documentclass` defines the document type.
 `\usepackage` adds extra features.
 `\begin{document}` and `\end{document}` define the document body.
 `\section` creates a section.

## 3. Important Concepts I Learned


 Document classes | `article`, `report`, `book` | Choose document structure. 
 Text formatting | `\textbf`, `\textit`, `\underline` | Format text. 
 Lists | `itemize`, `enumerate`, `description` | Organise information. 
 Mathematics | `$...$`, `equation`, `align` | Write equations and symbols. 
 Tables | `tabular` | Organise data into rows and columns. |
 Figures | `\includegraphics` | Insert images and diagrams. |
 References | `\label`, `\ref`, `\cite` | Refer to sections and sources. 
 Page layout | `geometry`, `fancyhdr` |Control margins, headers, and footers. 

## 4. Understanding Through Applications

- **Mathematics:** LaTeX makes it easier to write fractions, equations, integrals, and mathematical symbols.
- **Technical reports:** Tables and figures help present experimental results and diagrams.
- **Academic documents:** Sections, citations, and references help organise research papers and assignments.
- **Document formatting:** Packages allow control over page margins, fonts, colours, and headers.

For example, a mathematical expression can be written as:

A table can be created using the `tabular` environment, while images can be inserted using `\includegraphics`.

## 5. My Understanding

I learned that LaTeX is useful when a document needs proper structure, consistent formatting, and accurate mathematical representation. Its command-based approach may take some practice, but it makes larger technical documents easier to organise and maintain.



