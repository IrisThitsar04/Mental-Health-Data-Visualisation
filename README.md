# Mental Health Lifestyle & Stress Analysis Dashboard

## Project Overview

This project analyses a mental health dataset containing **50,000 records and 17 variables** covering demographic characteristics, lifestyle behaviours, mental health severity levels, stress indicators, and medical-related measures.

The project has **two primary objectives**:

- **To analyse how lifestyle behaviours and demographic features relate to mental health severity and stress levels.**
- **To assess the proportion of individuals with mental health conditions who do not seek medical-related help.**

To address these objectives, the project implements **four interactive visualisations** integrated into a **dashboard** to support exploratory analysis and insight generation.

## Dataset Description

The dataset includes variables related to:

- **Demographics** (e.g. age, gender, occupation, country)
- **Lifestyle behaviours** (e.g. sleep hours, physical activity, work hours, social media usage, diet quality, alcohol consumption, smoking habits)
- **Mental health indicators** (severity levels, stress levels)
- **Medical-related measures** (consultation history, medication usage)

## Data Preparation

Before visualisation, multiple **calculated fields** were created to convert continuous variables into categorical ranges for improved clarity and comparability.

Examples include:

- **Age** grouped into ranges such as 18–24, 25–34, 35–44, etc.

- **Sleep Hours, Physical Activity Hours, Work Hours,** and **Social Media Usage** grouped into meaningful categorical ranges.

These transformations were applied consistently across features to simplify interpretation and enhance visual clarity.

## Visualisations and Design Considerations

**Visualisation 1: Mental Health Severity vs Lifestyle Score**  
Analyses how mental health severity is distributed across composite lifestyle score groups (Healthy, Moderate-Healthy, Poor, Extremely Unhealthy). A clustered bar chart was used for clear comparison. Records were filtered to include only individuals with confirmed mental health conditions, with tooltips and filters added for interpretability.

**Visualisation 2: Stress Levels by Demographic and Lifestyle Features**  
Explores stress level distributions across demographic and lifestyle variables including age group, gender, occupation, country, sleep hours, work hours, and physical activity hours. A parameter-driven clustered bar chart enables dynamic comparison across features.

**Visualisation 3: Social Media Usage by Age Group or Stress Level**  
Examines social media usage patterns by age group or stress level using a parameter-controlled heatmap. The heatmap was selected to provide visual variation while remaining readable due to limited sub-categories.

**Visualisation 4: Medical Help-Seeking Behaviour by Severity Level**  
Assesses consultation history and medication usage across mental health severity levels. A stacked bar chart was used to support comparison of help-seeking behaviour across severity groups.

## Dashboard Integration

All four visualisations are combined into an **interactive dashboard.**

- **Visualisation 1 acts as a global filter,** dynamically updating the remaining visualisations.
- This enables both **individual-level analysis** and **cross-visualisation insights** that are not observable in isolation.

## Key Insights

- Individuals across **all lifestyle categories**, including healthier groups, experience **high-severity mental health issues**.
- Stress levels show variation across **age groups, occupations, and physical activity levels**, though differences are often subtle.
- Regardless of age or stress level, most individuals report **2-5 hours of daily social media usage**.
- **Nearly half of individuals with mental health conditions do not seek professional help or take medication**, even at higher severity levels.

## Key Takeaway

The most critical insight from this analysis is the **high proportion of individuals with mental health conditions who do not seek or receive appropriate medical-related help**. This finding highlights a potential gap in **awareness, access, or utilisation of mental health services**.

The results suggest a need for **increased awareness, targeted interventions, and improved access to mental health support** by public health stakeholders, healthcare providers, and non-profit organisations.
