# Student Performance Analytics Dashboard – Power BI Project

## Project Overview

This project is a **Student Performance Analytics Dashboard** created using **Microsoft Power BI**.
The dashboard helps analyze student academic performance, attendance, sleep patterns, study habits, and placement status using interactive visualizations and KPI cards.

The dashboard provides insights into:

* Student exam performance
* Attendance trends
* Study habits
* Sleep analysis
* Placement status comparison
* Previous vs current academic performance

---

## Tools & Technologies Used

* Microsoft Power BI
* Microsoft Excel / CSV Dataset
* Data Visualization Techniques
* Dashboard Analytics

---

## Dataset Information

The dataset contains the following important fields:

* `exam_score`
* `previous_score`
* `study_hours`
* `sleep_hours`
* `attendance`
* `placement_status`
* `assignments_completed`
* `internet_usage`

---

# Steps Performed in Power BI

## Step 1: Import Dataset into Power BI

1. Open Microsoft Power BI Desktop.
2. Click **Home → Get Data**.
3. Select the dataset file (Excel/CSV).
4. Load the dataset into Power BI.
5. Verify data types and clean data if necessary.

---

# Dashboard Visualizations

## KPI Cards Created

The following KPI cards were added to the dashboard:

1. **Average Exam Score**
2. **Total Sleep Hours**
3. **Average Attendance**
4. **Total Study Hours**

These KPI cards help provide a quick overview of overall student performance metrics.

---

## Visualizations Created

### 1. Pie Chart

**Visualization:** Total Placement Status by Placement Status

* Used to show the percentage of:

  * Placed Students
  * Not Placed Students

---

### 2. Column Chart

**Visualization:** Average Attendance by Placement Status

* X-Axis: `placement_status`
* Y-Axis: `average(attendance)`

This chart compares attendance levels between placed and non-placed students.

---

### 3. Bar Chart

**Visualization:** Total Exam Score by Placement Status

* X-Axis: `placement_status`
* Y-Axis: `sum(exam_score)`

Helps analyze exam performance based on placement outcome.

---

### 4. Line Chart

**Visualization:** Total Previous Score and Total Exam Score

* Values:

  * `sum(previous_score)`
  * `sum(exam_score)`

Used to compare previous academic performance with current exam performance.

---

### 5. Table Visual

The table visual includes:

* `assignments_completed`
* `attendance`
* `exam_score`
* `internet_usage`

This visual displays detailed student-level information.

---

### 6. Bar Chart

**Visualization:** Average Previous Score and Average Exam Score

* Compares:

  * `average(previous_score)`
  * `average(exam_score)`

Used to evaluate academic improvement trends.

---

### 7. Donut Chart

**Visualization:** Sum of Sleep Hours by Placement Status

* Legend: `placement_status`
* Values: `sum(sleep_hours)`

Helps analyze whether sleep habits influence placement outcomes.

---

### 8. Column Chart

**Visualization:** Sum of Exam Score and Sum of Assignments Completed

* Values:

  * `sum(exam_score)`
  * `sum(assignments_completed)`

Shows the relationship between assignment completion and academic performance.

---

### 9. Scatter Chart

**Visualization:** Placement Status, Study Hours, and Exam Score

* X-Axis: `study_hours`
* Y-Axis: `exam_score`
* Legend: `placement_status`

Used to identify the relationship between study hours and exam performance.

---

# Dashboard Insights

The dashboard provides several meaningful insights:

* Students with higher study hours generally achieve better exam scores.
* Attendance has a positive impact on placement status.
* Students completing more assignments tend to score higher.
* Sleep hours show noticeable patterns in placement outcomes.
* Previous academic scores strongly correlate with current performance.

---

# Key Features

* Interactive Dashboard
* KPI Metrics
* Academic Performance Tracking
* Placement Analysis
* Comparative Visualizations
* Student Behavior Insights

---

# Conclusion

This Power BI dashboard helps institutions and educators analyze student performance effectively using visual analytics. It enables better decision-making by identifying patterns related to attendance, study habits, sleep schedules, and placement success.

---

# Dashboard Preview

The dashboard includes:

* KPI Cards
* Pie Charts
* Column Charts
* Bar Charts
* Scatter Plot
* Table Visual
* Donut Chart
* Line Chart

---

# Author

**Student Performance Analytics Dashboard Project**

Created using Microsoft Power BI for academic data analysis.
