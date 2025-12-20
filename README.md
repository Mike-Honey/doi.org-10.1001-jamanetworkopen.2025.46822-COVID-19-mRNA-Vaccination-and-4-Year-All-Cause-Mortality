# Semenzato L, Le Vu S, Botton J, et al. COVID-19 mRNA Vaccination and 4-Year All-Cause Mortality Among Adults Aged 18 to 59 Years in France.
JAMA Netw Open. 2025;8(12):e2546822. 
doi:[10.1001/jamanetworkopen.2025.46822](https://doi.org/10.1001/jamanetworkopen.2025.46822)

## DataViz project to explore alternative visualisations of the open data shared with this scientific paper, which was read from the Appendix Supplementary materials.

My analysis on the data produced for this paper integrates the data behind Table 2.

The table is shared as an image, so I worked through a semi-manual data extract pipeline to convert it into, using the tools: PDF X-Change Editor and Excel.  Apologies if I introduced any manual errors during that process.


The final tool used is [Power BI](https://powerbi.microsoft.com/). This is an interactive data visualisation tool, that allows interactive filtering and exploration of the data.  I have used this to first integrate the data and reproduce a similar table to that shown in the paper, and then explore alternative presentations.

### % Incidence Change

This page presents the same data as the original paper, but focussed on a derived % Incidence Change (unvaccinated vs vaccinated), which is also presented as a databar. For a less-technical audience, I expect this metric is easier for them to consume and comprehend than Hazard ratios. It shows how much more likely the unvaccinated were to die of any particular cause.

An interactive "slicer" control at the right of the page allows the user to restrict the rows of ICD-10 data shown, to focus on an area of interest.

The table can be instantly resorted by clicking any column header.

[Link to interactive DataViz](https://app.powerbi.com/view?r=eyJrIjoiZDJmYWI3ZWEtYjJhNy00NzllLTgyNDQtOTlhZjMxZGZkNzlkIiwidCI6ImRjMWYwNGY1LWMxZTUtNDQyOS1hODEyLTU3OTNiZTQ1YmY5ZCIsImMiOjEwfQ%3D%3D&pageName=ed536217f33cd26c64ae)

[![Click to view and interact with the report](https://github.com/Mike-Honey/doi.org-10.1001-jamanetworkopen.2025.46822-COVID-19-mRNA-Vaccination-and-4-Year-All-Cause-Mortality/raw/main/pct-of-incidence-change.png)](https://app.powerbi.com/view?r=eyJrIjoiZDJmYWI3ZWEtYjJhNy00NzllLTgyNDQtOTlhZjMxZGZkNzlkIiwidCI6ImRjMWYwNGY1LWMxZTUtNDQyOS1hODEyLTU3OTNiZTQ1YmY5ZCIsImMiOjEwfQ%3D%3D&pageName=ed536217f33cd26c64ae)


### Hazard ratios

This page presents the Hazard ratios as a horizontal box plot. The horizontal bars show the 95% Confidence Intervals (wider = less confidence), while the dark bars show the Median Hazard ratio. 

An interactive "slicer" control at the right of the page allows the user to restrict the rows of ICD-10 data shown, to focus on an area of interest.  The user can also switch from Hazard ratio - Weighted to Crude.

In the full version of Power BI or Power BI Desktop, the end user can sort these by any metrics. Unfortunately, that feature is suppressed in this "Publish to Web" scenario.

[Link to interactive DataViz](https://app.powerbi.com/view?r=eyJrIjoiZDJmYWI3ZWEtYjJhNy00NzllLTgyNDQtOTlhZjMxZGZkNzlkIiwidCI6ImRjMWYwNGY1LWMxZTUtNDQyOS1hODEyLTU3OTNiZTQ1YmY5ZCIsImMiOjEwfQ%3D%3D&pageName=d2be287e02cc7ce944f0)

[![Click to view and interact with the report](https://github.com/Mike-Honey/doi.org-10.1001-jamanetworkopen.2025.46822-COVID-19-mRNA-Vaccination-and-4-Year-All-Cause-Mortality/raw/main/hazard-ratio.png)](https://app.powerbi.com/view?r=eyJrIjoiZDJmYWI3ZWEtYjJhNy00NzllLTgyNDQtOTlhZjMxZGZkNzlkIiwidCI6ImRjMWYwNGY1LWMxZTUtNDQyOS1hODEyLTU3OTNiZTQ1YmY5ZCIsImMiOjEwfQ%3D%3D&pageName=d2be287e02cc7ce944f0)


### Reproduction - Table 2

This page follows the style of the original table. The interactive features allow filtering and re-sorting of the data.

[Link to interactive DataViz](https://app.powerbi.com/view?r=eyJrIjoiZDJmYWI3ZWEtYjJhNy00NzllLTgyNDQtOTlhZjMxZGZkNzlkIiwidCI6ImRjMWYwNGY1LWMxZTUtNDQyOS1hODEyLTU3OTNiZTQ1YmY5ZCIsImMiOjEwfQ%3D%3D&pageName=465e1d4f84036a256c0c)

[![Click to view and interact with the report](https://github.com/Mike-Honey/doi.org-10.1001-jamanetworkopen.2025.46822-COVID-19-mRNA-Vaccination-and-4-Year-All-Cause-Mortality/raw/main/repro-table-2.png)](https://app.powerbi.com/view?r=eyJrIjoiZDJmYWI3ZWEtYjJhNy00NzllLTgyNDQtOTlhZjMxZGZkNzlkIiwidCI6ImRjMWYwNGY1LWMxZTUtNDQyOS1hODEyLTU3OTNiZTQ1YmY5ZCIsImMiOjEwfQ%3D%3D&pageName=465e1d4f84036a256c0c)


#### Original Table 2

![Table 2](https://github.com/Mike-Honey/doi.org-10.1001-jamanetworkopen.2025.46822-COVID-19-mRNA-Vaccination-and-4-Year-All-Cause-Mortality/raw/main/Table%202%20Comparison%20of%20Causes%20of%20Death.png)


### Methods

I used [PDF-XChange Editor](https://www.pdf-xchange.com/product/pdf-xchange-editor) to run OCR on the image for Table 2, then copied the results into Excel for cleaning.The results are a cell for each row, with variable spaces between Table 2's columns. I then used Power BI's Power Query Editor to integrate that and split it into tidy columns.

## 🤝 Support

Contributions, issues, feature requests and sponsorship are all welcome!

Give a ⭐️ if you like this project!
