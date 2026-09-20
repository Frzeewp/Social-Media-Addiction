# Background
Social media platforms like Instagram, TikTok, and YouTube have become an inseparable part of students' lives. However, behind the ease of access to information and entertainment, there is a risk of addiction that can affect mental health and academic productivity.

## Problem Description
In this competition, you are asked to build a machine learning model that can predict whether a student is addicted to social media or not, based on their digital behavior and demographic data.

## About the Dataset

### Data Collection
This dataset contains information about students' social media usage habits from various countries, covering demographic data, platforms used, sleep schedules, and mental health scores.

### Column Description
<table>
  <tr>
    <td><b>Column Name</b></td>
    <td><b>Data Type</b></td>
    <td><b>Description</b></td>
  </tr>
  <tr>
    <td>id</td>
    <td>String</td>
    <td>Unique student ID</td>
  </tr>
  <tr>
    <td>gender</td>
    <td>String</td>
    <td>Gender</td>
  </tr>
  <tr>
    <td>age</td>
    <td>Integer</td>
    <td>Student age</td>
  </tr>
  <tr>
    <td>country</td>
    <td>String</td>
    <td>Country of origin</td>
  </tr>
  <tr>
    <td>education_level</td>
    <td>String</td>
    <td>Level of education</td>
  </tr>
  <tr>
    <td>social_media_platform</td>
    <td>String</td>
    <td>Most frequently used social media platform</td>
  </tr>
  <tr>
    <td>avg_daily_usage_hours</td>
    <td>Float</td>
    <td>Average hours of social media use per day</td>
  </tr>
  <tr>
    <td>academic_impact</td>
    <td>String</td>
    <td>Impact of social media on academics (Yes/No)</td>
  </tr>
  <tr>
    <td>bedtime</td>
    <td>String</td>
    <td>Bedtime</td>
  </tr>
  <tr>
    <td>wake_time</td>
    <td>String</td>
    <td>Wake-up time</td>
  </tr>
  <tr>
    <td>mental_health_score</td>
    <td>Integer</td>
    <td>Mental health score (1–10)</td>
  </tr>
  <tr>
    <td>relationship_status</td>
    <td>String</td>
    <td>Relationship status</td>
  </tr>
  <tr>
    <td>social_media_conflicts</td>
    <td>Integer</td>
    <td>Number of conflicts caused by social media</td>
  </tr>
  <tr>
    <td>addiction</td>
    <td>String</td>
    <td>Social media addiction (Yes/No) — TARGET</td>
  </tr>
</table>

### Dataset Information
+ Number of training data: 542 rows
+ Number of testing data: 163 rows
+ Number of features: 13
+ Target: addiction (binary classification: Yes / No)

### Evaluation Metric
Predictions are evaluated using Macro F1-Score.
