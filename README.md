# Data Job Skills & Salary Analysis Dashboard

This project features an interactive Excel dashboard designed to analyze the skills, demand, and salaries for various data-related professions[cite: 1]. It serves as a visual guide for data professionals to evaluate whether learning a specific skill is highly demanded or highly lucrative for their desired career path[cite: 1].

## 🎥 Dashboard Demo

Watch the dashboard dynamically update as different job titles are selected.

<video width="100%" controls>
  <source src="data_job_analysis_recording.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

_(Note: If the video preview is not supported by your markdown viewer, please open the `data_job_analysis_recording.mp4` file included in this directory to view the demonstration.)_

## 🛠️ Key Features

- **Interactive Slicer:** Includes a clickable menu on the right side of the screen to filter data by specific job titles, such as Business Analyst, Cloud Engineer, Data Analyst, Data Engineer, and Data Scientist[cite: 1].
- **Dual-Metric Combo Chart:** Overlays a line graph on top of a bar chart to compare two different metrics simultaneously[cite: 1].
  - **Average Yearly Salary:** Displayed as blue bars, representing the average pay for jobs requiring specific skills, read via the left-hand vertical axis[cite: 1].
  - **Job Count (Demand):** Displayed as a line graph, showing how many job postings actively ask for the skill, read via the right-hand vertical axis[cite: 1].
- **Dynamic Data Table:** Provides the raw numerical values for the exact job count and average salary, instantly repopulating to show the top skills whenever a new job title is selected[cite: 1].

## 📊 Data Insights

The dashboard illustrates how the required software tools and languages completely shift depending on the selected role[cite: 1].

- When filtering for a **Business Analyst**, the dashboard highlights demand for tools like Python, R, SAS, Tableau, SQL, Power BI, Excel, and Word[cite: 1].
- When switching to a **Cloud Engineer**, the graph entirely changes to highlight hardcore infrastructure and data tools like MongoDB, Databricks, Airflow, Spark, Kafka, Terraform, AWS, and Azure, alongside notably higher salary brackets[cite: 1].

## 🚀 How to Use

1. Clone or download this repository to your local machine.
2. Open the main Excel workbook.
3. Use the Slicer on the right side of the dashboard to select a target job title.
4. Review the Combo Chart to identify which skills offer the highest intersection of salary and market demand.

## Found a Typo? Want to Contribute?

- If you find an error in this repo, please feel free to make a pull request by:
  - Forking the repo
  - Making any changes
  - Submitting a pull request
