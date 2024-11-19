# Stanford Open Policing Project: An Exploration on the Obscure Interactions of Factors With Police Stoppings
## Abstract
Traffic stops are among the most common law enforcement interactions, significantly impacting public perceptions of police fairness. Existing evidence suggests that minority groups, particularly racial minorities, may face higher rates of stops, searches, and arrests, potentially indicating systemic bias. However, the cumulative effect of less visible factors, such as how stop times, reasons, or driver age intersect with race and gender, remains underexplored. \vspace{.5em}

Looking past these disparities, we want to examine some of these nuanced interactions to help support a more equitable policing model. Our study explores the Stanford Open Policing Project dataset and analyzes the more obscure interactions between multiple factors that interact in policing outcomes. By potentially surfacing biases that are less obvious when looking at isolated variables, our study aims to uncover hidden patterns in traffic stop practices that reveal deeper layers of policing dynamics.
\vspace

Complex, interrelated factors in traffic stops—such as time, location, driver demographics, stop reasons, and outcomes like warnings, citations, searches, and arrests—can identify subtle trends and potential biases not captured by surface-level analyses of individual variables.


Quantitative data analysis starts with data cleaning and preprocessing. We can apply concepts from CS 577 to to examine the correlations between combined factors influencing traffic stop outcomes. Geographic and temporal visualizations will also be employed to contextualize findings, revealing potential policy implications for minimizing unintentional bias in law enforcement. This approach will highlight complex patterns that, while subtle, have meaningful implications for policing practices and public trust.

## Dataset
In order to evaluate inherent disparities that may be present during police traffic stops, we must have a dataset that is both accurate and has sufficient size. During our initial research, we found several reputable datasets, but ultimately decided on the Stanford Open Policing Project dataset. This dataset contains millions of traffic stop data, with another 2.8 million stops included in 2023 from locations like Mesa, Arizona, Aurora, Colorado, and Chicago Illinois. 

Evidently, the scope of this project must be properly evaluated with this large dataset, so we intend to limit our findings to Californian cities or traffic stops that occurred in San Diego, California. Within this dataset, there are 72 columns with relevant information corresponding to each unique traffic stop.

Some of these features may not be as useful as others, such as officer first and last name as well as the department that made the arrest. However, other important features of the dataset we will use include time, location, subject race, office race, and others we find valuable to our report. Most of the aforementioned columns have data types of a time stamp, location, string, as well as Boolean variables.

With this large dataset, we will need to make sure we have proper data cleaning, filtering, and validation. This includes selecting the traffic stops within the city or region we are looking for, as well as other column filtering that is important to our proposed research question.
