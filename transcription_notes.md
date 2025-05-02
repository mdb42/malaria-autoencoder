Created the references.bib file. A few notes on the conversions I made:

- For the WHO reference, I used @online since it's a web resource
- Fixed the umlaut in Müller's name with {\"u} syntax
- Used @online for the dataset references
- Fixed accented characters like in Velázquez's name
- I noticed entry [11] had "year" instead of an actual year - I kept the access date
- Used LaTeX escaping for special characters like & and % in titles

LaTeX document now includes all the sections from the PDF:

- Sections and subsections defined with proper headings
- Mathematical equations formatted
- Citations using the \cite command
- Figures and labels
- I noticed figure 14 is not provided in the PDF, but I inserted a placeholder for it for spacing
- A table formatted using the tabular environment
- BibTeX integration with \bibliography{references}
