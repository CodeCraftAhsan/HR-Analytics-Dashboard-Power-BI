# Project overview

I developed an HR Analytics Dashboard in Power BI to bring key employee indicators into one reporting experience. The report connects employee records with engagement survey data and a calendar table, giving HR teams a way to compare employee sentiment across departments, follow work-life balance over time, and monitor termination patterns.

!image.png

The goal was to make workforce information easier to interpret and support focused HR conversations based on data.

## Business questions

- How does employee engagement vary across departments?
- Which departments report higher or lower satisfaction?
- How does work-life balance change month to month?
- What do monthly employee termination trends look like?
- How are employees distributed across performance-score categories?
- How can the view be narrowed by employment status?

## What I built

**Executive dashboard:** A consolidated view of employee count, engagement, satisfaction, work-life balance, departmental comparisons, performance-score distribution, and an employment-status slicer.

<img width="1276" height="721" alt="image" src="https://github.com/user-attachments/assets/a64a1ed8-6311-4eb5-9407-88aa1ce896f0" />

**Engagement analysis:** Department-level engagement comparisons supported by summary cards.

<img width="1252" height="690" alt="image" src="https://github.com/user-attachments/assets/28753cc4-75a2-43df-b83c-4189261735aa" />


**Satisfaction analysis:** Department-level satisfaction comparisons and survey summary cards.

<img width="1242" height="695" alt="image" src="https://github.com/user-attachments/assets/39d6ca7a-0f8f-45de-a42e-ecc10c8f122b" />


**Average engagement view:** A focused visual for comparing department engagement.

<img width="1155" height="691" alt="image" src="https://github.com/user-attachments/assets/daddffc5-0d72-474d-b1ab-a1742dfd3fa0" />


**Work-life balance analysis:** A monthly trend chart alongside survey context.

<img width="1272" height="685" alt="image" src="https://github.com/user-attachments/assets/6bd50b65-e160-4e10-9127-daffe06217d7" />


**Termination analysis:** Monthly termination count and percentage trends.

<img width="1231" height="522" alt="image" src="https://github.com/user-attachments/assets/0484feb2-68db-4d59-aa27-73607477b2df" />


## Data and reporting approach

The Power BI model includes three named tables: `employee_data`, `employee_engagement_survey_data`, and `Calender`. Report visuals use employee department, employment status, performance score, survey measures, and a month-year field for time-based reporting.

I structured the reporting around two levels of analysis: a dashboard for a quick overview and focused pages for exploring individual HR measures. Column charts support departmental comparisons; line charts show time trends; a donut chart shows performance-score distribution; cards surface high-level indicators.

## Business value

The report can help an HR or people-analytics team identify where further investigation is needed, such as lower survey scores within a department or changes in termination trends. These visuals are **descriptive**: they help locate patterns but do not prove why a pattern occurred.

## Skills demonstrated

**Power BI reporting:** Multi-page report design, KPI cards, column and line charts, donut charts, and interactive filtering.

**Data modeling:** Working with employee, survey, and calendar tables.

**HR analytics:** Engagement, satisfaction, work-life balance, employee status, performance segmentation, and termination reporting.

**Business communication:** Translating HR questions into readable dashboards for stakeholders.

## My takeaway

This project strengthened my ability to organize related HR metrics into a reporting experience that balances a management-level overview with focused analysis pages. It also reinforced the importance of validating measure definitions before making business decisions from percentages or trends
