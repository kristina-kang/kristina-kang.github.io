---
layout: default
title: Bellabeat Smart Device Analysis
permalink: /projects/project2/
---

# Smart Fitness Tracker Usage Analysis

## Project Overview

Bellabeat is a wellness technology company focused on smart health devices.

This project analyzes smart device usage data to understand consumer behavior patterns and identify opportunities for improving product strategy, user engagement, and marketing decisions.

The analysis follows the six-step data analysis process:

**Ask → Prepare → Process → Analyze → Share → Act**

**Tools:** SQL, BigQuery, Tableau

---

## Business Problem

Bellabeat aims to expand its presence in the global smart device market.

The objective of this analysis was to understand how consumers use fitness tracking devices and uncover behavioral insights that could support:

- Product development
- Marketing strategy
- Customer engagement

---

## Data Source

The analysis used the Fitbit Fitness Tracker Dataset from Kaggle.

The dataset contains smart device usage data from 30 Fitbit users, including:

- Daily activity
- Steps
- Calories burned
- Heart rate
- Sleep patterns
- Activity intensity

The dataset includes minute-level and daily-level tracking data collected over approximately one month.

---

## Data Preparation

The dataset was cleaned and prepared using SQL.

Key preparation steps:

- Checked for missing values
- Verified duplicate records
- Validated dataset time ranges
- Combined multiple activity tables
- Created analysis-ready datasets

Additional transformations:

- Added day-of-week attributes
- Standardized numerical values
- Created time-of-day categories:
  - Morning
  - Afternoon
  - Evening
  - Night

---

## Data Analysis

SQL was used to aggregate and analyze smart device usage patterns.

The analysis explored relationships between:

- Activity intensity and calories burned
- Steps and user activity levels
- Time of day and workout behavior
- Sleep and wellness patterns

---

## Key Findings

### Activity patterns vary throughout the day

Users demonstrated different activity behaviors depending on the time of day, suggesting opportunities for personalized engagement.

### Higher intensity activity was linked to increased calorie expenditure

Activity intensity metrics provided insights into how users interact with fitness tracking devices.

### Smart device data can enable personalized wellness experiences

Consumer behavior patterns can support:

- Personalized activity recommendations
- Engagement reminders
- Targeted wellness campaigns

---

## Business Recommendations

### 1. Create personalized user experiences

Bellabeat can leverage activity patterns to provide customized wellness recommendations.

### 2. Increase user engagement

Personalized reminders and insights can encourage consistent device usage.

### 3. Improve marketing strategies

Understanding consumer behavior can help Bellabeat better target different user segments.

---

## Tableau Dashboard

An interactive Tableau dashboard was created to visualize:

- Daily activity trends
- Steps and calories
- Activity intensity
- Consumer usage behavior


<div class="tableau-container">

<div class='tableauPlaceholder' id='viz1781670878993'>

<noscript>
<a href='#'>
<img alt='Bellabeat Dashboard'
src='https://public.tableau.com/static/images/be/bellabeat_17090733211060/Home_board/1_rss.png'
style='border:none'/>
</a>
</noscript>

<object class='tableauViz'>

<param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F'/>

<param name='embed_code_version' value='3'/>

<param name='name' value='bellabeat_17090733211060/Home_board'/>

<param name='tabs' value='no'/>

<param name='toolbar' value='yes'/>

</object>

</div>


<script type='text/javascript'>

var divElement = document.getElementById('viz1781670878993');

var vizElement = divElement.getElementsByTagName('object')[0];

if (divElement.offsetWidth > 800) {
    vizElement.style.width='900px';
    vizElement.style.height='700px';
} 
else {
    vizElement.style.width='100%';
    vizElement.style.height='700px';
}

var scriptElement = document.createElement('script');

scriptElement.src='https://public.tableau.com/javascripts/api/viz_v1.js';

vizElement.parentNode.insertBefore(scriptElement, vizElement);

</script>

</div>


## Conclusion

This project demonstrates how SQL and Tableau can transform raw smart device data into actionable business insights.

By analyzing consumer behavior patterns, companies can make data-driven decisions that improve product strategy, marketing effectiveness, and customer engagement.

---

<a href="/" class="back-button">← Back to Home</a>
