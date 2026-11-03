# East Delta University — B.Sc. Thesis LaTeX Template

A beginner-friendly LaTeX template for preparing undergraduate thesis documents for the **Department of Computer Science & Engineering (CSE), East Delta University (EDU)**.

This template is designed to help students prepare their B.Sc. thesis documents using LaTeX on Overleaf, while maintaining a consistent document structure and formatting.

## Features

- Structured thesis document with predefined chapters and sections.
- Automatic title page generation using student and thesis information.
- Table of Contents, List of Figures, and List of Tables.
- Support for references and bibliography using BibTeX.
- Predefined formatting for chapters, sections, figures, tables, and equations.
- Guidance comments to help students understand and use LaTeX.
- Sample figures and example content.
- Layout settings designed to reproduce the official EDU thesis template.

## Getting Started

### 1. Download or Clone the Repository

Clone the repository using Git:

```bash
git clone https://github.com/Transhumanistx/EDU-BSc-Thesis-LaTeX-Template.git
```

Alternatively, download the repository as a ZIP file from GitHub.

### 2. Upload to Overleaf

1. Visit [Overleaf](https://www.overleaf.com/).
2. Create a new project by selecting **Upload Project**.
3. Upload the downloaded ZIP file.
4. Open the project and locate `main.tex`.

### 3. Required Files

Make sure the following files are available in the same project directory:

```text
.
├── main.tex
├── references.bib
├── edu_logo.jpg
├── edu_logo_inner.png
├── sample_figure.png
└── README.md
```

**Note:** Keep the required image files in the same directory as `main.tex`, unless you update their paths in the LaTeX source.

## How to Use the Template

### Step 1: Enter Your Information

Open `main.tex` and locate **STEP 1**.

Fill in the required information, such as:

- Thesis title
- Student name
- Student ID
- Supervisor name
- Department and university information
- Submission date

These details are automatically used throughout the document where applicable.

### Step 2: Write Your Thesis

Navigate to the relevant sections in `main.tex` and replace the sample content with your own thesis.

The template provides predefined sections for:

- Abstract
- Acknowledgements
- Chapters
- References
- Appendices

Use the comments in the source file to locate the relevant sections.

### Step 3: Add Figures and Tables

Upload your figures to the Overleaf project and include them using the appropriate LaTeX commands.

For example:

```latex
\begin{figure}[htbp]
    \centering
    \includegraphics[width=0.8\textwidth]{sample_figure.png}
    \caption{Example figure}
    \label{fig:example}
\end{figure}
```

### Step 4: Add References

Add your references to `references.bib` using BibTeX format.

Example:

```bibtex
@article{example2026,
    author  = {Author, Example},
    title   = {An Example Research Paper},
    journal = {Example Journal},
    year    = {2026}
}
```

Cite references in your thesis using:

```latex
\cite{example2026}
```

### Step 5: Compile the Document

In Overleaf:

1. Open `main.tex`.
2. Select **Recompile**.
3. Review the generated PDF.
4. Recompile again if the Table of Contents or references require updating.

## Important Notes

- Do not modify the section marked **LAYOUT SETTINGS — DO NOT EDIT** unless you understand the formatting requirements.
- Replace all sample text with your own thesis content before submission.
- Remove guidance comments and placeholder content when they are no longer needed.
- Verify the final PDF against the official thesis submission guidelines provided by East Delta University.
- This template is intended to assist with thesis formatting; students remain responsible for ensuring their thesis complies with current university requirements.

## License

This repository is provided for educational and academic use by students and faculty.

Please check the repository for any additional licensing or usage terms.

## Acknowledgement

Developed to support undergraduate thesis writing in the Department of Computer Science & Engineering, East Delta University.

---

**Copyright © 2026 Tanvir Azhar. All rights reserved.**
