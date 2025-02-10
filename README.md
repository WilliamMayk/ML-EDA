# ML-EDA

## Overview

This dataset contains information about Gen Z individuals and their usage of dating apps. It includes various attributes such as user demographics, app preferences, usage patterns, satisfaction levels, challenges faced, and desired features. The data is collected from 500 users across different locations in India.

## Dataset Details

- **Number of Rows:** 500  
- **Number of Columns:** 16  
- **File Format:** CSV  
- **Target Audience:** Data scientists, analysts, researchers studying dating trends among Gen Z.

## Column Descriptions

| **Column Name**               | **Description**                                                                                               |
|-------------------------------|---------------------------------------------------------------------------------------------------------------|
| `User_ID`                     | Unique identifier assigned to each user. Data Type: **Integer**.                                               |
| `Age`                         | Age of the user in **years**. Data Type: **Integer**. Range: **18-65**.                                       |
| `Gender`                      | Gender identity of the user. Data Type: **Categorical**. Possible values: **'Male'**, **'Female'**, **'Non-binary'**, **'Other'**. |
| `Location`                    | City where the user is currently residing. Data Type: **Categorical**. Example: **'Delhi'**, **'Bangalore'**.  |
| `Education`                   | Highest education level attained. Data Type: **Categorical**. Possible values: **'Undergraduate'**, **'Graduate'**. |
| `Occupation`                  | User's job status. Data Type: **Categorical**. Example: **'Freelancer'**, **'Full-time Job'**, **'Intern'**.   |
| `Primary_App`                 | The main dating app the user engages with. Data Type: **Categorical**. Possible values: **'Hinge'**, **'OkCupid'**, **'Tinder'**. **Note:** 107 missing values. |
| `Secondary_Apps`              | Other dating apps the user uses. Multiple apps may be separated by commas. Data Type: **Categorical**.         |
| `Usage_Frequency`             | Frequency of using dating apps. Data Type: **Categorical**. Possible values: **'Daily'**, **'Weekly'**, **'Monthly'**. |
| `Daily_Usage_Time`            | Average time spent on dating apps per day, measured in **minutes** or **hours**. Data Type: **String**. Example: **'1 hour'**, **'30 minutes'**. |
| `Reason_for_Using`            | The primary reason users engage with dating apps. Data Type: **Categorical**. Examples: **'Finding a Partner'**, **'Casual Dating'**, **'Casual Fun'**. |
| `Satisfaction`                | User satisfaction rating on a scale from **1 (Very Dissatisfied)** to **5 (Very Satisfied)**. Data Type: **Integer**. |
| `Challenges`                  | Challenges faced by users while using dating apps. Data Type: **Categorical**. Examples: **'Safety Concerns'**, **'Time-Wasting'**, **'None'**. |
| `Desired_Features`            | Features users would like to see in dating apps. Data Type: **Categorical**. Examples: **'Video Calls'**, **'AI Recommendations'**, **'Detailed Profiles'**. |
| `Preferred_Communication`     | Preferred method of communication with matches. Data Type: **Categorical**. Examples: **'Text'**, **'Video Calls'**, **'Voice Notes'**. |
| `Partner_Priorities`          | Attributes users prioritize in a partner, listed in order of importance. Data Type: **String**. Example: **'Values > Personality > Appearance'**. |

## Potential Use Cases
1. **Behavioral Analysis:** Understanding how Gen Z interacts with dating apps.
2. **App Development:** Identifying desired features and challenges to improve dating app functionalities.
3. **Marketing Research:** Understand the preferences and behaviors of Gen Z users on dating apps.
4. **Machine Learning Models:** Predicting user satisfaction, preferred communication styles, or likelihood of facing challenges.

## How to Use
**1. Load the Dataset:** Use a CSV reader or data analysis library (e.g., Pandas in Python) to load the dataset.

**2. Data Cleaning:** Handle missing values and ensure data consistency.

**3. Exploratory Data Analysis (EDA):** Perform EDA to uncover trends and patterns.

**4. Visualization:** Create visualizations to better understand the data distribution and relationships.

**5. Modeling:** Build predictive models to forecast user satisfaction or app preferences.

## Example Analysis Questions
- What are the most popular dating apps among Gen Z users?
- How does satisfaction vary across different age groups or genders?
- What challenges are most commonly reported, and how do they correlate with app usage frequency?
- What features do users desire most, and how can this guide app development?

---

*Prepared by:* William Josue Okwale Mayoukou  
*Date:* 10th Frebruary 2025  
*Project:* GenZ Dating App Data Analysis

