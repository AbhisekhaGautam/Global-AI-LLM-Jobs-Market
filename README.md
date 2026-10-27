# AI & LLM Job Market Analysis | January 2024 – March 2025

## Project Dashboard

![Power BI Dashboard](https://github.com/AbhisekhaGautam/Global-AI-LLM-Jobs-Market/blob/main/Images/Screenshot%202026-10-27%20112603.png)

## MySQL Analysis

![MySQL Skill Analysis](https://github.com/AbhisekhaGautam/Global-AI-LLM-Jobs-Market/blob/main/Images/Screenshot%202026-10-27%20111952.png)

## Excel Analysis

![Excel Skill Analysis](https://github.com/AbhisekhaGautam/Global-AI-LLM-Jobs-Market/blob/main/Images/Screenshot%202026-10-27%20111506.png)

## Project Overview

The **AI & LLM Job Market Analysis** project is an end-to-end data analytics project focused on understanding employment trends in the Artificial Intelligence (AI) and Large Language Model (LLM) job market from **January 2024 to March 2025**.

Using a Kaggle dataset containing approximately **2,500 job listings**, I performed data cleaning, preprocessing, exploratory data analysis, SQL-based transformations, and analytical querying to uncover patterns in job demand, salaries, technical skills, experience requirements, and employment arrangements.

The project combines **Microsoft Excel, MySQL, and Microsoft Power BI** to transform raw job-posting data into structured, analysis-ready information and an interactive dashboard. PDF and DOCX documentation were also prepared to explain the analytical workflow and project findings.

This project demonstrates a practical data analytics workflow, from raw data preparation and database analysis to business intelligence reporting and data visualization.

## Project Objectives

- Clean and prepare raw job-market data for accurate analysis.
- Identify and remove duplicate job records.
- Check missing values, correct data types, and standardize data fields.
- Use Excel formulas and pivot tables for data preparation and exploratory analysis.
- Import the dataset into MySQL for database-based cleaning and analysis.
- Use SQL to transform data, extract individual skills, and calculate aggregated metrics.
- Analyze job demand by country, sector, job title, and experience level.
- Investigate salary patterns and frequently requested technical skills.
- Explore LLM technologies and work arrangements mentioned in job postings.
- Develop an interactive Power BI dashboard to communicate analytical findings.
- Document the workflow, queries, and visualizations for transparency and reproducibility.

## Tools & Technologies

| Tool | Application |
|---|---|
| Microsoft Excel | Data cleaning, duplicate removal, missing-value checks, standardization, formulas, pivot tables, and exploratory analysis |
| MySQL | Database creation, data storage, further cleaning, transformations, and analytical queries |
| SQL | Filtering, aggregation, grouping, sorting, ranking, string manipulation, and skill extraction |
| Microsoft Power BI | Interactive dashboards, KPI cards, charts, maps, and slicers |
| PDF | Project methodology and analytical documentation |
| Microsoft Word (DOCX) | Detailed documentation of the data analytics process |

## Project Workflow

### 1. Data Collection

- Obtained the job-market dataset from Kaggle.
- Worked with approximately 2,500 AI and LLM job listings.
- Examined the dataset structure, available attributes, and data quality before analysis.

The dataset includes job-related attributes such as job titles, companies, sectors, countries, work modes, experience levels, annual salaries, required skills, LLM technologies, and application counts.

### 2. Data Cleaning & Preparation — Excel

Excel was used for the initial data-cleaning and preparation stage.

Key activities:
- Inspected the dataset for inconsistencies and quality issues.
- Identified and removed duplicate records.
- Checked for missing values.
- Standardized relevant text and categorical fields.
- Corrected data types where required.
- Used Excel formulas and pivot tables to support data preparation and preliminary analysis.
- Reviewed the resulting data before database import.

**Outcome:** A more consistent dataset prepared for further processing and analysis.

### 3. Database Management & Data Transformation — MySQL

The dataset was imported into MySQL for database management, additional cleaning, and structured analysis.

Key activities:
- Created and selected the project database.
- Imported the job-market dataset into a MySQL table.
- Validated the imported records and column structure.
- Applied SQL-based transformations and data-cleaning operations.
- Used string functions to process fields containing multiple comma-separated skills.
- Applied aggregations, filtering, grouping, sorting, and ranking to analyze job-market patterns.
- Used Common Table Expressions (CTEs) and recursive SQL to split individual skills into separate records for frequency analysis.

For example, the skill analysis used a recursive CTE to extract individual skills from the `required_skills` column and count how often each skill appeared across job listings.

This approach made it possible to rank technical skills such as PyTorch, Weights & Biases, RAG, TensorFlow, Rust, and Python by their frequency in the dataset.

**Outcome:** Structured data and SQL-generated analytical results suitable for further exploration and visualization.

### 4. Exploratory Data Analysis — Excel & MySQL

Exploratory data analysis was performed to investigate patterns and relationships across the available job-market attributes.

The analysis covered:

- Job distribution by country and sector.
- Demand for different AI and LLM job titles.
- Average annual salaries across experience levels.
- Frequency of technical skills and frameworks.
- LLM technologies mentioned in job descriptions.
- Remote, hybrid, and on-site work arrangements.
- Experience requirements across job listings.
- Application counts and recruitment activity.

The results of these analyses informed the metrics, comparisons, and charts used in the Power BI dashboard.

### 5. Interactive Dashboard Development — Power BI

The cleaned and analyzed database data was brought into Power BI to create an interactive dashboard titled **AI Job Market — Global Talent Intelligence**.

The dashboard combines KPI cards, a geographic map, a doughnut chart, bar charts, and interactive slicers to present the analysis in a clear, accessible format.

#### Dashboard Pages

**Overview**

Provides a high-level summary of the job market, including:
- Total job listings.
- Average annual salary.
- Number of countries represented.
- Number of job titles.
- Total applications.
- Geographic distribution of job opportunities.
- Job distribution by work mode.
- Average salary by experience level.
- LLM demand and top technical skills.

**Salary Analysis**
- Examines salary patterns across experience levels and job categories.
- Supports comparisons of compensation across different job-market segments.
- Helps identify differences in salary distributions within the dataset.

**Skills Analysis**
- Ranks frequently requested technical skills.
- Explores demand for AI frameworks, development tools, and LLM-related technologies.
- Highlights recurring technical requirements in job descriptions.

**Jobs Analysis**
- Examines job-title distribution and hiring patterns.
- Enables comparisons across countries, sectors, and experience levels.
- Explores the distribution of employment opportunities and work arrangements.

**Insights**
- Presents key observations derived from the analysis.
- Summarizes relevant salary, skill-demand, and job-market patterns.
- Communicates findings through concise, data-driven takeaways.

#### Interactive Filters

The dashboard includes slicers for:

- Country
- Sector
- Experience Level
- Work Type

These filters allow users to explore different segments of the job market interactively.

### 6. Documentation & Reporting

PDF and DOCX files were prepared to document the project's analytical workflow.

The documentation covers the data-cleaning approach, SQL processing, analysis, and dashboard visualizations, helping explain how the raw dataset was transformed into useful analytical outputs.

## Key Analytical Questions

| Area | Questions Investigated |
|---|---|
| Job Demand | Which countries, sectors, and job titles have the highest representation? |
| Salary Analysis | How does average salary vary by experience level and job category? |
| Technical Skills | Which skills and frameworks occur most frequently in job requirements? |
| LLM Technologies | Which LLM technologies are mentioned in the available job postings? |
| Work Mode | How are jobs distributed across remote, hybrid, and on-site arrangements? |
| Experience | What experience levels are requested by employers? |
| Recruitment Activity | How are application counts distributed across the job listings? |

## Key Findings & Dashboard Highlights

The following are example metrics displayed on the dashboard overview. They should be interpreted in the context of the dataset and its definitions.

| Metric | Dashboard Value |
|---|---:|
| Total Job Listings | Approximately 2.5K |
| Average Salary | $134.45K annually |
| Countries Represented | 30 |
| Job Titles | 20 |
| Applications | 5M |

The dashboard also visualizes:
- Geographic job distribution across countries.
- The distribution of remote, hybrid, and on-site work.
- Average salaries across experience categories.
- The most frequently listed LLM technologies.
- The top technical skills identified through SQL-based skill extraction.

*Note: These are dashboard-displayed values, not independently verified market-wide statistics. The results reflect the source dataset, its coverage, and the calculation methods used.*

## Skills Demonstrated

**Data Analytics**
- Data cleaning and preprocessing
- Duplicate removal and missing-value checks
- Data standardization and type correction
- Exploratory data analysis (EDA)
- Data validation and quality checks

**SQL & Database Management**
- MySQL database operations
- SQL-based data transformations
- Common Table Expressions (CTEs)
- Recursive CTEs
- String manipulation and skill extraction
- Aggregations, filtering, grouping, and ranking

**Data Visualization & Business Intelligence**
- Microsoft Power BI dashboard development
- KPI design
- Bar charts, doughnut charts, and geographic maps
- Interactive slicers and filtering
- Comparative analysis and data storytelling

**Reporting & Documentation**
- Analytical documentation
- PDF and DOCX reporting
- Communicating findings through visualizations


## How to Explore the Project

1. Review the Excel workbook to understand the initial data preparation and exploratory analysis.
2. Open the SQL scripts to examine database processing, transformations, and analytical queries.
3. Open the Power BI PBIX file in Power BI Desktop to explore the interactive dashboard.
4. Review the dashboard screenshots for a quick overview of the visualizations.
5. Read the PDF or DOCX documentation for additional details about the methodology and analysis.

The PBIX file requires compatible Power BI Desktop software. Access to the original dataset may also be necessary to reproduce the full workflow.

## Conclusion

The AI & LLM Job Market Analysis project demonstrates a practical, end-to-end data analytics workflow using Excel, MySQL, SQL, and Power BI.

Starting with a Kaggle dataset of approximately 2,500 job listings, the project applies data-cleaning techniques, database transformations, exploratory analysis, skill-frequency analysis, and interactive visualization to examine the AI and LLM employment landscape from January 2024 to March 2025.

The project highlights the importance of data quality, structured querying, and effective visualization in turning raw job-market information into useful insights.

It also demonstrates practical skills in data preparation, SQL analysis, dashboard development, and technical documentation that are relevant to data analyst and business intelligence roles.

---

**Project Type:** End-to-End Data Analytics

**Dataset Source:** Kaggle: https://www.kaggle.com/datasets/sangrampatil5150/global-ai-and-llm-jobs-market-20242025

**Analysis Period:** January 2024 – March 2025

**Tools:** Microsoft Excel | MySQL | SQL | Microsoft Power BI

**Deliverables:** Excel workbook | SQL scripts | Power BI PBIX | Dashboard screenshots | PDF documentation | DOCX documentation
