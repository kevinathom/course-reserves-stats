# Summary
Tools for working with and representing data about course reserves at the University of Pennsylvania Libraries.

# Tool descriptions
## instructor-stats.qmd (ready to use)
- Outputs a PDF report for delivery to a course instructor.
- Written in R and Quarto.
- Requires data from two sources, limited to the course codes you want reported:
  - Metridoc's leganto-usage-views report, exported to a CSV file
  - Alma's alma_citations table from one or more reading lists, exported to a single CSV file
## list-stats.qmd (early development)
- Outputs a PowerPoint report for presentation within Penn Libraries.
- Written in R and Quarto.
