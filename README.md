# Prisoner Recidivism Analysis Tool (PRAT)
During my time as a data analyst fellow at the Bureau of Justice Statistics, I worked on building the Prisoner Recidivism Analysis Tool which resulted in a final Tableau dashboard. This tool permits users to create their own customized reports on recidivism rates based on various characteristics they choose such as sex, race, age at arrest, prior arrest history, and sentencing offense.

The data for which this tool was orignally built to analyze is not publicly available, so this iteration of the tool uses an alternative dataset from the National Institute of Justice. Formatting of the tool has been updated to fit the NIJ data.

Before creating the tool, I cleaned the raw data so it could be in a useable format before uploading it into Tableau. I also created a few preliminary crosstables and visualizations with the data once it was cleaned. An example of the code used in this step is available in the '.' file.

After data preprocessing was complete, I created the dashboard in Tableau. The final dashboard allows the user to visualize important metrics such as cumulative recidivism rate and annual failure rate, both altogether and separated by certain attributes. The standard deviation and confidence interval of these metrics is displayed as well. The user can also review characteristics of the dataset such as the distribution of the data by attribute and geographically by state.

The link to the final Tableau dashboard can be found here: https://public.tableau.com/views/PRAT-NIJData/PRATTool?:language=en-US&:display_count=n&:origin=viz_share_link
