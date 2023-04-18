# Situation
I previously worked with an assessment service provider that conducted academic subject tests designed to help adults obtain their high school equivalency diploma. The credential earned through these tests could have a significant impact on their lives, as it provided access to better employment opportunities and higher education, as well as served as a positive example for younger students.

Our client was interested in identifying patterns of testing performance differentials across the academic subject test market that may have been linked to local testing facilities and resources. They were also interested in exploring the potential factors driving those discrepancies.

By understanding these patterns, our client aimed to proactively communicate with relevant jurisdictions about areas that may have benefited from additional support. Ultimately, the goal was to take concrete actions that could help improve the persistence rates of those who were pursuing their high school equivalency diploma through our client's testing service.

# Process Framework
The analysis process followed an adaptive approach, utilizing causal inference techniques, dimensionality reduction, clustering, and unsupervised modeling techniques.

In overview, the following steps were taken:

* Data cleaning and merging
* Causal inference was applied to identify important features and their impact on test performance.
* Data was prepared for modeling.
* Clustering was performed to identify patterns and cluster properties.
* Analysis and insights were generated based on the results obtained from the previous steps.

# Data Cleaning and Merging
Data cleaning and merging were performed as the initial steps in the analysis process. The dataset used for the analysis consisted of both candidate and test data, with 509,722 and 2,852,791 data points, respectively. The candidate data had 40 dimensions, while the test data had 18 dimensions.

During the data cleaning process, it was identified that a few columns had null values and a few outliers. It was important to handle these issues as they could have interfered with the analysis, making it difficult to attribute results to specific causes.

# Feature Selection and Engineering
The success metric chosen for our analysis was "pass" instead of the score, as the score is a continuous variable that may not have been determined solely by the features analyzed. Our focus was to identify patterns of success in passing rather than the score.

Identifying important features was a crucial step in the analysis as it helped reduce noise caused by unimportant features. By identifying the features that impacted test performance more, we were able to capture more variation and attribute it to the relevant features. This information could later be used for recommendations.

We used causal inference techniques to identify the important features and validate them against the explanations provided by the client.

# Data preparation
The goal was to identify testing performance disparities among different regions in the jurisdiction. Therefore, candidate and test data with important features were needed.

After merging, the candidate data and test data had many features with multiple dimensions, as the analysis was at the candidate's zipcode level. The data was rolled up to the candidate zip-code level, retaining important features extracted from the previous step.

# Clustering
Candidate's performance had an impact on the region's performance, and clustering was used to group similar performing regions together. Clustering was a crucial step in the process, with the goal of grouping similar performing regions in the country and analyzing funnel drop-offs and opportunities at the regional level. The most important part of the funnel was to identify the best-performing funnel and identify common behaviors among the group.

Common behaviors were co-related with the testing and preparation facilities, and a thesis was built on solving for them effectively.

# Analysis and Insights
The analysis process delivered several insights that could be used to improve testing performance and increase the persistence rates of individuals pursuing their high school equivalency diploma through the client's testing service.

Firstly, the analysis identified important features that impacted test performance, which could be used to recommend areas for improvement to the relevant jurisdictions.

Secondly, clustering analysis grouped similar performing regions together, allowing the identification of common behaviors and potential causes for the observed testing performance disparities. This information could be used to recommend targeted solutions to improve testing facilities and preparation resources in specific regions.

Lastly, the analysis focused on the pass rate as the success metric, instead of the score, allowing for the identification of patterns of success in passing. This could be used to recommend targeted interventions to support individuals in passing the academic subject tests, thereby improving their lives by providing access to better employment opportunities and higher education.
