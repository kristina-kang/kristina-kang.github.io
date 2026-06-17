---
layout: default
title: Bellabeat Smart Device Analysis
permalink: /projects/project2/
---

# Smart Fitness Tracker Usage Analysis

## Project Overview

Bellabeat is a wellness technology company focused on smart health devices.

This project analyzes smart device usage data to understand consumer activity patterns and identify opportunities for improving product strategy, user engagement, and marketing decisions.

The analysis follows the six-step data analysis process:

**Ask → Prepare → Process → Analyze → Share → Act**

**Tools:** SQL, BigQuery, Tableau

---

## Business Problem

Bellabeat aims to expand its presence in the global smart device market.

The goal of this analysis was to understand how consumers use non-Bellabeat fitness devices and uncover behavioral patterns that could help inform:

- Product development
- Marketing strategies
- User engagement initiatives

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

The data includes minute-level and daily-level tracking information collected over approximately one month.

---

## Data Preparation

Before analysis, the dataset was cleaned and prepared using SQL.

Performed:

- Checked for missing values
- Validated duplicate records
- Reviewed dataset time ranges
- Combined multiple activity tables
- Created analysis-ready datasets

Example transformations included:

- Adding day-of-week attributes
- Rounding numerical values for consistency
- Creating time-of-day categories:
  - Morning
  - Afternoon
  - Evening
  - Night

---

## Data Analysis

SQL was used to aggregate and analyze activity patterns across multiple datasets.

Analyzed relationships between:

- Activity intensity and calories burned
- Steps and user engagement
- Time of day and activity levels
- Sleep and wellness behaviors

---

## Key Findings

### Users showed different activity patterns throughout the day

Activity levels changed significantly depending on the time of day, suggesting opportunities for personalized engagement strategies.

### Higher intensity activity was associated with increased calorie expenditure

Movement and intensity metrics provided insights into how users interact with their fitness devices.

### Smart device data can support personalized wellness experiences

Usage patterns highlight opportunities for features such as:

- Personalized activity recommendations
- Engagement notifications
- Wellness-focused marketing campaigns

---

## Business Recommendations

Based on the analysis:

### 1. Develop personalized user experiences

Bellabeat could use activity patterns to create tailored recommendations based on individual behavior.

### 2. Improve user engagement

Smart reminders and personalized insights could encourage consistent device usage.

### 3. Create targeted marketing strategies

Understanding consumer behavior can help Bellabeat better position products for different user segments.

---

## Tableau Dashboard

An interactive Tableau dashboard was created to visualize:

- Daily activity trends
- Steps and calories
- Intensity patterns
- Consumer usage behavior


<div class="tableau-container">

<div class='tableauPlaceholder' id='viz1781670878993' style='position: relative'>

<noscript>
<a href='#'>
<img alt='Home_board' 
src='https://public.tableau.com/static/images/be/bellabeat_17090733211060/Home_board/1_rss.png' 
style='border: none' />
</a>
</noscript>

<object class='tableauViz' style='display:none;'>

<param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />

<param name='embed_code_version' value='3' />

<param name='site_root' value='' />

<param name='name' value='bellabeat_17090733211060/Home_board' />

<param name='tabs' value='no' />

<param name='toolbar' value='yes' />

<param name='static_image' value='https://public.tableau.com/static/images/be/bellabeat_17090733211060/Home_board/1.png' />

<param name='animate_transition' value='yes' />

<param name='display_static_image' value='yes' />

<param name='display_spinner' value='yes' />

<param name='display_overlay' value='yes' />

<param name='display_count' value='yes' />

<param name='language' value='en-US' />

</object>

</div>


<script type='text/javascript'>

var divElement = document.getElementById('viz1781670878993');

var vizElement = divElement.getElementsByTagName('object')[0];

if (divElement.offsetWidth > 800) {

vizElement.style.width='900px';

vizElement.style.height='700px';

} 

else if (divElement.offsetWidth > 500) {

vizElement.style.width='900px';

vizElement.style.height='700px';

} 

else {

vizElement.style.width='100%';

vizElement.style.height='900px';

}

var scriptElement = document.createElement('script');

scriptElement.src='https://public.tableau.com/javascripts/api/viz_v1.js';

vizElement.parentNode.insertBefore(scriptElement, vizElement);

</script>


</div>


---

## Conclusion

This project demonstrates how SQL and Tableau can transform raw smart device data into actionable insights.

By analyzing consumer behavior patterns, organizations can make data-driven decisions that improve product strategy, marketing effectiveness, and customer engagement.

---

<a href="/" class="back-button">← Back to Home</a>
