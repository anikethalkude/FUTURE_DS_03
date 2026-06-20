# Marketing Funnel & Conversion Performance Analysis

## Overview

This project was completed as part of the **Data Science & Analytics Internship Program** by Future Interns.

The objective of this project is to analyze marketing campaign performance and customer conversion behavior using the Bank Marketing Dataset. The analysis focuses on identifying conversion trends, high-performing customer segments, effective contact channels, and opportunities to improve overall marketing funnel performance.

---

## Project Objective

The primary goals of this project are to:

* Analyze customer conversion performance
* Identify high-performing marketing channels
* Measure conversion rates across customer segments
* Detect conversion drop-off opportunities
* Provide actionable recommendations to improve campaign effectiveness

---

## Dataset

**Dataset Used:** Bank Marketing Dataset

Source:
https://archive.ics.uci.edu/dataset/222/bank+marketing

The dataset contains information about direct marketing campaigns conducted by a banking institution and includes customer demographics, campaign details, and subscription outcomes.

### Key Features

* Age
* Job
* Marital Status
* Education
* Balance
* Contact Method
* Campaign Contacts
* Previous Campaign Outcome
* Month
* Subscription Outcome (Target Variable)

Target Variable:

```text
y
```

* Yes = Customer Subscribed
* No = Customer Did Not Subscribe

---

## Tools Used

* Tableau
* Microsoft Excel (Data Inspection)
* GitHub

---

## Data Cleaning & Preparation

The following preprocessing steps were performed:

1. Verified and validated data types
2. Checked for missing or inconsistent values
3. Created calculated fields for conversion analysis
4. Grouped customers into age bins for segmentation analysis
5. Prepared data for dashboard visualization and KPI tracking

### Calculated Fields

**Converted Customers**

```text
IF [y] = "yes" THEN 1 ELSE 0 END
```

**Not Converted**

```text
IF [y] = "no" THEN 1 ELSE 0 END
```

**Conversion Rate**

```text
SUM([Converted]) / COUNT([y])
```

---

## Dashboard Components

### KPI Cards

* Total Leads
* Converted Customers
* Conversion Rate (%)

### Visualizations

* Conversion by Contact Method
* Conversion by Month
* Conversion by Occupation
* Conversion by Education
* Conversion by Age Group
* Previous Campaign Outcome Analysis
* Marketing Funnel Overview

### Interactive Filters

* Month
* Job
* Education
* Contact Method

---

## Analysis Performed

### Marketing Funnel Analysis

Evaluated the customer journey from campaign contact to successful subscription.

### Conversion Performance Analysis

Measured overall conversion rates and identified areas for optimization.

### Channel Performance Analysis

Compared conversion performance across different communication methods.

### Customer Segmentation

Analyzed conversion behavior based on age, occupation, and education level.

### Campaign Effectiveness Analysis

Studied the impact of campaign timing and previous campaign outcomes on customer conversion.

---

## Key Insights

### Conversion Trends

Marketing campaign performance varies significantly across customer segments and communication channels.

### Contact Method Performance

Certain contact methods consistently generate higher conversion rates and should be prioritized in future campaigns.

### Customer Segmentation

Specific age groups and occupations demonstrate stronger conversion behavior compared to others.

### Campaign Timing

Conversion performance changes across different months, indicating potential seasonal trends.

### Previous Campaign Impact

Customers with successful previous interactions are more likely to convert in future campaigns.

---

## Business Recommendations

1. Allocate more resources to high-performing contact channels.
2. Focus campaigns on customer segments with historically strong conversion rates.
3. Increase marketing activity during high-conversion periods.
4. Re-engage customers who responded positively to previous campaigns.
5. Optimize messaging and targeting strategies for low-performing segments.
6. Continuously monitor funnel performance and conversion metrics.

---

## Dashboard Preview

The Tableau dashboard provides an interactive view of marketing funnel performance, customer conversion behavior, campaign effectiveness, and customer segmentation insights.

---

## Project Structure

FUTURE_DS_03

├── Dataset
│ └── bank_marketing.csv

├── Tableau Dashboard
│ └── FUTURE_DS_03.twbx

├── Screenshots
│ └── dashboard.png

├── Report
│ └── Marketing_Funnel_Analysis.pdf

└── README.md

---

## Skills Demonstrated

* Marketing Funnel Analysis
* Conversion Rate Analysis
* Customer Segmentation
* KPI Development
* Data Visualization using Tableau
* Business Intelligence Reporting
* Marketing Analytics
* Insight Generation and Storytelling

---

## Internship Information

**Internship:** Data Science & Analytics Internship

**Task:** Marketing Funnel & Conversion Performance Analysis (Task 3)

**Organization:** Future Interns

---

## Author

**Aniket**

Data Science & Analytics Intern

Future Interns