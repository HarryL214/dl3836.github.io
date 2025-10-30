# dl3836.github.io

This repository contains the source files for my P8105 Homework 4 website. The site is built using HTML and R Markdown content to satisfy the assignment requirements.

## Contents

- `index.Rmd` / `index.html`: Landing page introducing Dianchen Li.
- `resume.Rmd` / `resume.html`: Experience page embedding my curriculum vitae stored as `CV_ Li Dianchen_final.pdf`.
- `dashboard.Rmd` / `dashboard.html`: Flexdashboard specification and corresponding interactive Instacart visualization page.
- `_site.yml`: Navbar configuration shared across the R Markdown pages.
- `hw4.Rproj`: R Project file for reproducible workflows.

To reproduce the dashboard locally, open the R project and knit `dashboard.Rmd`; the document loads the Instacart dataset from the `p8105.datasets` package and generates Plotly visualizations.
