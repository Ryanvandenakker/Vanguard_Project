# Vanguard Modern UI 

### Introduction

In response to growing competition in the field of investments, Vanguard implemented a modernized user interface (UI) with timely in-context prompts to improve customer experience in an attempt to turn the tide. Data between the 15th of March to 20th June 2017 were collected from an A/B test consisting of a control group using the previous UI and a test group using the updated UI. We analyzed client's interaction on the UI to assess whether the modernized UI boosted client's pverall engagement and user experience. Through data cleaning, exploratory data analysis, key performance indicators, and hypothesis testing, we determined whether the redesign of the UI was effective. 

### Datasets
**Client Profile:** Profile, account details, and client activity\
**Digital Footprint:** Data detailing interactions with the online process\
**Experiment Roster:** Indicates whether clients were in the control or test group

### KPIs
Three key performance indicators were used to determine the success of the new UI design:\
**Completion Rates:** The new UI design led to an average increase of 3.7% in completion rates\
**Average Step Duration:** Clients were completing the process on average 3 seconds slower when using the new UI design. Majority of the time is spent on steps 2 and 3 of the online process and the confirmation step saw a drastic increase in mean duration when using the new UI\
**Error Rate:** The new UI design saw a 0.8% increase in error rate. Steps 1 and Steps 2 had a drastic increase in error rates when using the new UI compared to the previous UI 

### Hypothesis Testing
**Completion Rate Differences:** The test confirmed that there is a significant difference observed between the completion rate of the test group and the completion rate of the control group\
**Cost-Effectiveness Threshold:** The test indicated that the test group completion rate is not significantly greater than the control group rate plus 5%. This implies that although the new UI improved completion rate, the increase falls short of the 5% benchmark set by the Vanguard team

### Recommendations
Further enhancements can be made to improve the customer experience and increase overall engagement\
For instance, the team should look to decrease the time it takes to complete steps 2 and 3. Possibly by improving the prompts that were newly introduced to the UI\
Additionally, higher error rates were observed in the new UI which should be addressed by improving the instructions and clarity of paticularly steps 1 and 2

### Tableau
Explore the interactive visualizations using Tableau through the link:\
[Client Demographics](https://public.tableau.com/app/profile/ryan.van.den.akker2210/viz/Vanguard-ClientDemographics/Demographics)\
[KPIs](https://public.tableau.com/app/profile/ryan.van.den.akker2210/viz/Vanguard-KPIs/KPIs)

### Libraries Used
- pandas\
- numpy\
- seaborn\
- matplotlib\
- scipy.stats\
- yaml



