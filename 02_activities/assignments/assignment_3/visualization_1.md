### What software did you use to create your data visualization? 
Python (pandas + matplotlib)

### Who is your intended audience?
Policy analysts, researchers, and data science students examining long-term patterns in reported intimate partner and family violence.

### What information or message are you trying to convey with your visualization?
The visualization communicates how reported incidents of intimate partner and family violence have changed over time. By aggregating reports annually, the chart highlights long-term trends and periods of increase or decrease. 

### What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots?
I focused on clarity, readability, and visual hierarchy. A line chart was chosen to emphasize temporal change. A consistent color palette and moderate line width were used to keep attention on the trend rather than decorative elements. Markers were added to clearly indicate individual yearly data points, while a subtle grid supports value estimation without overpowering the data. High resolution ensures the figure remains legible in reports or presentations.

### How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?
The visualization is fully reproducible because it is generated entirely through a Python script. The code explicitly loads the dataset, performs the aggregation, and renders the plot. Anyone with access to the dataset and script can reproduce the same result. 

### How did you ensure that your data visualization is accessible?
Accessibility was addressed by using clear axis labels, a descriptive title, and a single visual encoding (position along axes) rather than relying on color to convey meaning. The color contrast between the line and background is sufficient for readability.

### Who are the individuals and communities who might be impacted by your visualization?
The visualization may impact policymakers, social service providers, and advocacy organizations who rely on trend data to allocate resources and design interventions. Indirectly, it affects communities represented in the data, as visualized trends can influence public discourse and policy priorities related to family and intimate partner violence.

### How did you choose which features of your chosen dataset to include or exclude from your visualization?
Only REPORT_YEAR and COUNT_ were included to maintain focus on overall temporal trends. Other variables such as neighbourhood, premises type, or relationship details were excluded to avoid overcrowding the visualization and to prevent conflating time trends with spatial or demographic factors.

### What ‘underwater labour’ contributed to your final data visualization product?
Following D’Ignazio and Klein’s concept of data visualization as the tip of the iceberg, this visualization depends on forms of labour that are not visible in the final chart. This includes the work of frontline responders, social workers, and community organizations who support victims and facilitate the reporting of intimate partner and family violence. It also includes administrative and data-entry labour involved in recording incidents, maintaining databases, and ensuring consistency over time. Additional underwater labour includes public-sector IT staff who manage data infrastructure, researchers and analysts who clean and standardize records, and caregivers whose unpaid domestic and emotional labour enables institutional work to occur. 