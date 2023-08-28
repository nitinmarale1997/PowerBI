<H1> Call Center Analysis | Pwc Switzerland Power BI Virtual Case Experience 
  

## Table of contents
- [Problem Statement](https://github.com/calmk/PWC-Virtual-Case-Experience/tree/main/Task%202:%20Call%20Center%20Dashboard#Problem-Statement)
- [Data Preparation](https://github.com/calmk/PWC-Virtual-Case-Experience/tree/main/Task%202:%20Call%20Center%20Dashboard#Data-Preparation)
- [Data Modeling](https://github.com/calmk/PWC-Virtual-Case-Experience/tree/main/Task%202:%20Call%20Center%20Dashboard#Data-Modeling)
- [Data Visualization](https://github.com/calmk/PWC-Virtual-Case-Experience/tree/main/Task%202:%20Call%20Center%20Dashboard#Data-Visualization)
- [Analysis and Insights](https://github.com/calmk/PWC-Virtual-Case-Experience/tree/main/Task%202:%20Call%20Center%20Dashboard#Analysis-and-Insights)
- [Shareable Link](https://github.com/calmk/PWC-Virtual-Case-Experience/tree/main/Task%202:%20Call%20Center%20Dashboard#Shareable-Link)


# Problem Statement

- **Problem:** The manager at PhoneNow (a big telecom company) is seeking transparency and insight into the Call Center dataset to gain an accurate overview of long-term customer and agent behavior trends.
- **Objective:** The purpose of this analysis is to create a dashboard in Power BI for Call Center Manager that reflects all relevant Key Performance Indicators (KPIs) and metrics to:
    - Self-exploratory call trends
    - Overview of the agent’s performance and behaviors
    - Overview the customer satisfaction
    - Contain many metrics and plots related to a single area of business for discussing with higher managers and generating further analysis.
    - Allows for minimal interaction
- **Possible KPIs** include (but are not limited to):
    - Overall customer satisfaction
    - Overall calls answered/abandoned
    - Calls by time
    - Average speed of answer
    - Agents performance quadrant -> average handle time(talk duration) vs calls answered

# Data Sourcing

The Dataset used for this analysis was provided by [Pwc Switzerland](https://www.pwc.ch/en/careers-with-pwc/students/virtual-case-experience.html) and available here: [Call Center Dataset](https://github.com/calmk/PWC-Virtual-Case-Experience/blob/main/Task%202%3A%20Call%20Center%20Dashboard/01%20Call-Center-Dataset.xlsx)
# Data Preparation

The dataset was loaded into Microsoft Power BI Desktop for transformation in Power Query and modeling.

### Data Cleaning

Data Cleaning for the dataset was done in Power Query as follows:

- Unnecessary columns were removed
- Each of the columns in the table was validated to have the correct data type
- Unnecessary rows were removed


# Data Modeling

After the dataset was cleaned and transformed, it was ready to be modeled, but the dataset just included one table, so the Data Modeling is nothing much to modify

# Data Visualization
Add Image in Repo


Data visualization for the datasets was done in Microsoft Power BI Desktop and designed in PowerPoint, the dashboard includes:

- One main dashboard
- Six tooltip pages


### Key Performance Indicators and Metrics:

**About Calls and Agents:** 

- Overall calls answered/abandoned
- Calls received by time, day 
- Average speed of answer, handle duration
- Resolved rate by Agents, Topics
- Agent’s performance quadrant -> average handle time (talk duration) vs calls answered

**About Customer satisfaction:**

- Overall customer satisfaction
- Customer satisfaction distribution by Agents, Topics
### Measures

The measure used in visualization are:




# Analysis and Insights
The purpose of this dashboard is to serve as self-exploratory for managers, but I still note some highlighted points that I recognize below:

********************About Call trends:********************

- Customers tend to call more between 5:00 pm - 5:30 pm at 250 calls received with an abandoned rate is 18.40% (approximately to the average abandoned rate) and distributed mainly in the middle of the month
- The highest abandoned rate is 28.03% between 1:00 pm - 1:30 pm
- Customers have more problems with Streaming service
- The resolved rate is at a high rate (89,94%)

********************About performance of agents:********************

- The agent who satisfies customers most is Becky with a 12.02% of “Very good” rating
- The agent who has the highest resolved rate is Jim and he is effective with solving problems related to “Contract related” and “Admin Support”

********************About customer satisfaction:********************

- The average customer satisfaction is at an acceptable rate with 3.40, mainly comes from “Average” (30.04%) and “Good” (29.11%) rating
- The correlation between call answered and call resolved is strongly positive which resulted in a increase in the customer satisfaction rate

