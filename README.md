# How Social Media Affects Productivity?

Explore the correlation between **social media usage, screen time, and individual productivity** with real survey data and actionable insights.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Dataset](#dataset)
- [Main Features](#main-features)
- [Project Structure](#project-structure)
- [Installation & Setup](#installation--setup)
- [Usage](#usage)
- [Analysis Workflow](#analysis-workflow)
- [Key Insights](#key-insights)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

---

## Project Overview

This repository holds a Jupyter Notebook that analyzes the **impact of social media and screen time on productivity**, helping individuals and organizations clarify whether digital habits hinder work and study efficiency. The study leverages survey responses from 30,000 participants.

---

## Objectives

- **Quantify** if increased time spent on social media correlates with lower productivity.
- **Identify patterns**: How notifications, platform preferences, focus/wellbeing app usage, and demographics affect productivity.
- **Recommend strategies** for healthier, more productive tech use.

---

## Dataset

- **Source**: Social Media vs. Productivity dataset by Mahdi Mashayekhi (Kaggle).
- **Format**: CSV.
- **Rows**: 30,000.
- **Columns**: 19 features including demographics, technology use, productivity, and wellbeing.

### Main Features

| Feature                         | Description                                  |
|----------------------------------|----------------------------------------------|
| `age`, `gender`, `job_type`     | Demographic details                          |
| `daily_social_media_time`        | Hours per day spent on social media          |
| `social_platform_preference`     | Favorite platform (Facebook, TikTok, etc.)   |
| `number_of_notifications`        | Notifications received/day                   |
| `work_hours_per_day`             | Total hours spent working/studying           |
| `perceived_productivity_score`   | Self-rated productivity (2-9 scale)          |
| `actual_productivity_score`      | Computed productivity (0.3-9.8 scale)        |
| `stress_level`                   | Stress rating (1-10)                         |
| `sleep_hours`                    | Average sleep per day                        |
| `screen_time_before_sleep`       | Screen use immediately before bed            |
| `breaks_during_work`             | Number of breaks taken per day               |
| `uses_focus_apps`                | Uses focus apps (True/False)                 |
| `has_digital_wellbeing_enabled`  | Digital wellbeing control active             |
| `job_satisfaction_score`         | Satisfaction in current role (0-10 scale)    |
| Additional wellbeing fields      | Burnout days, coffee intake, offline hours   |

---

## Project Structure
```
Efficiency_Track.ipynb # Main analysis notebook
README.md # This documentation
social_media_vs_productivity.csv # Dataset (download automatically)
```
---

## Installation & Setup

### Prerequisites

- Python 3
- Jupyter Notebook or Google Colab

### Required Libraries
```
pip install pandas numpy matplotlib seaborn scikit-learn

```
---


## Usage

1. **Clone the repository and open the notebook**:
    - Launch `Efficiency_Track.ipynb` in Jupyter or Colab.
2. **Run all cells**:
    - The notebook will automatically download the data and perform the analysis.


---

## Analysis Workflow

1. **Introduction**
    - Sets objectives, introduces the problem, and details dataset relevance.

2. **Preprocessing**
    - Validates and loads the CSV data.
    - Confirms no missing values; structures data for analysis.

3. **Exploratory Data Analysis (EDA)**
    - Summarizes distributions for main features.
    - Categorizes demographic and platform variables.

4. **Feature Engineering**
    - Derives usage ratios, platform categories, and bins for easier segmentation.

5. **Statistical Analysis**
    - Correlates digital habits with productivity and job satisfaction.
    - Assesses influence of notifications, sleep, and wellbeing controls.

6. **Findings & Recommendations**
    - Identifies factors that most impact productivity.
    - Provides evidence-driven suggestions for individuals and organizations.

---

## Key Insights

- **Average daily social media use:** 3.1hrs.
- **Average productivity score:** 4.95/10.
- **Negative correlations:** High social media time, notification overload, and sleep deficit.
- **Positive correlations:** Use of focus apps and digital wellbeing features.
- **Clear split in platform preferences and productivity among demographics.

---

## Contributing

Feedback, code contributions, and new data analyses are welcome!  
Open an issue or submit a pull request.

---

## License

Review the dataset license on Kaggle.  
This repository is intended for research and educational purposes.

---

## Acknowledgments

- Dataset by Mahdi Mashayekhi (Kaggle)
- Python open-source contributors
- Digital wellbeing research inspiration

---
