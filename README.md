# Hospital-Emergency-Admissions-Exploratory-Analysis
Unkiversity of Warwick - Programming for Business Application. 

Project Overview

This project was part of an introductory programming module for business applications, where I worked with a real-world style dataset on Accident & Emergency (A&E) admissions in a London hospital.

The dataset contained hourly admissions across one week, split by admission type (e.g., road traffic accidents, sports injuries, deliberate self-harm). The objective was to produce three visualizations that could help management improve hospital service planning.

My analysis focused on staffing and resource allocation, identifying key patterns in admissions by:

Shift (Morning, Evening, Night) across weekdays

Reason for attendance vs day of week

Average admissions by reason vs hour of the day (heatmap)

> **Note:** As an academic assignment, the project was bound by a specific requirements and a strict word count, which limited its scope and creative exploration. Furthermore, the use of a dataset spanning just one week also restricted the ability to identify potentially useful long-term patterns, such as seasonal or monthly trends.

Insights & Recommendations

Insight: On weekdays, admissions peak in the morning shift (08h–16h), while on weekends, demand shifts to evening and night hours.
Recommendation: Adjust workforce scheduling dynamically — reinforce morning staffing during weekdays and evening/night coverage on weekends to match patient inflow patterns.

Insight: Assault-related admissions increase significantly on weekends, peaking late at night.
Recommendation: Ensure availability of emergency physicians, security staff, and psychiatric specialists during weekend nights to handle both medical and psychosocial aspects effectively.

Insight: Deliberate self-harm cases remain steady throughout the week but concentrate between 19h–02h.
Recommendation: Strengthen night-shift mental health support by increasing the presence of psychiatrists, psychologists, and crisis intervention teams during late evenings.

Insight: Sports injuries peak on Sundays and early evenings, reflecting recreational activity patterns.
Recommendation: Schedule more orthopedic specialists and physiotherapy resources on Sundays and evenings to reduce treatment delays and improve patient flow.

Insight: Traffic accidents consistently rise in the from early evening to late afternoond (they start increasing at 16h and peak from 18h to 21h).
Recommendation: Expand availability of trauma surgeons and diagnostic imaging equipment (X-rays, CT scans) during these hours to reduce waiting times and optimize emergency care response.

Insight: High variability exists in admissions for “unknown reasons”, showing unpredictable surges.
Recommendation: Improve data collection processes to reduce “unknown” categories, and develop predictive models to better anticipate sudden peaks and allocate floating staff flexibly.

Tools & Methods

Python (first project using it)

Main Libraries: Pandas, Numpy, Seaborn, Matplotlib

Simple Data Cleaning: handling missing values, transforming categorical variables, deriving new features (e.g., shifts, total admissions)

Selected Visualizations: bar chart, line chart, and a heatmap to communicate insights effectively

🚀 Why This Project Matters

This was my first Python project, and it gave me a first practical experience applying programming to business and decision-making. 
This project can be seen as an example of what I would deliver if given only a limited dataset, around one hour to prepare, and five minutes to present simple, actionable ideas to a manager for improving operational performance.
The focus was not coding but turning data into the first actionable insights aligned with business objectives, while presenting and communicating the findings visually and intuitively for non-technical stakeholders.
