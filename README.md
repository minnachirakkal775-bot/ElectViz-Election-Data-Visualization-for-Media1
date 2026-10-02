# 📊 ElectViz – Election Data Visualization for Media

<p align="center">
  <b>Interactive Election Data Analysis and Visualization using Power BI</b>
</p>

<p align="center">
  <i>Infosys Springboard Internship Project</i>
</p>

---

## 📌 Project Overview

**ElectViz – Election Data Visualization for Media** is an interactive
**Power BI-based election data analysis and visualization project** developed
as part of the **Infosys Springboard Internship Program**.

The project focuses on transforming complex election datasets into
interactive and easy-to-understand visual dashboards.

ElectViz enables users to analyze:

- Election results
- Political party performance
- Candidate performance
- Voter turnout
- Vote share
- Seats won
- State-wise results
- Constituency-level results
- Demographic participation
- Gender-based participation
- Historical election trends

The main goal of the project is to make large and complex election datasets
easier to understand through **interactive Business Intelligence
visualizations**.

---

# 🎯 Project Objectives

The major objectives of ElectViz are:

- Analyze election data using modern data visualization techniques.
- Study voting patterns across different states and constituencies.
- Analyze political party performance.
- Analyze candidate-level election performance.
- Calculate and visualize voter turnout.
- Compare election results across different years.
- Analyze demographic participation.
- Analyze male and female voter participation.
- Visualize vote share and seats won.
- Provide constituency-level election analysis.
- Develop interactive and user-friendly Power BI dashboards.
- Present complex election datasets in a simple and understandable format.

---

# ✨ Key Features

## 📌 Election Overview

Provides a high-level summary of election results using:

- Total Seats
- Seats Won
- Total Votes
- Vote Share
- Voter Turnout
- Party Performance
- State-wise results

---

## 📈 Historical Election Trends

The historical analysis allows users to compare election results across
different election years.

It includes:

- Year-wise seats won
- Year-wise vote share
- Voter turnout trends
- Party performance trends
- Historical election comparisons
- Regional changes over time

---

## 🏛️ Party Performance Analysis

The project provides detailed political party analysis using:

- Seats won
- Total votes
- Vote share
- State-wise performance
- Constituency-wise performance
- Historical performance

---

## 👤 Candidate-Level Analysis

Candidate analysis includes:

- Candidate name
- Political party
- Constituency
- State
- Votes received
- Winning margin
- Winning percentage
- Age
- Gender
- Educational information

---

## 🗺️ State & Constituency Analysis

The dashboard provides geographical analysis of election results.

Users can analyze:

- State-wise seats
- State-wise votes
- Constituency results
- Regional voting patterns
- Constituency-level performance
- Highest turnout regions
- Lowest turnout regions

---

## 🗳️ Voter Turnout Analysis

The project analyzes voter participation using:

- Total electors
- Total votes cast
- Male electors
- Female electors
- Male votes
- Female votes
- Male turnout
- Female turnout
- Overall turnout percentage
- State-wise turnout

---

## 👥 Demographic Analysis

The project provides demographic analysis using available election data.

The analysis includes:

- Gender participation
- Age groups
- Male vs Female voters
- Social category analysis
- Regional participation
- Demographic turnout patterns

---

## 📊 Vote Share Analysis

The dashboard provides visualization of vote distribution among parties.

It includes:

- Party-wise votes
- Vote share percentage
- State-wise vote share
- Constituency-level vote share
- Historical vote share comparison

---

## 🪑 Seats Won Analysis

The project visualizes seats won by political parties.

Users can analyze:

- Party-wise seats
- State-wise seats
- Year-wise seats
- Alliance-level results
- Historical seat changes

---

# 🏗️ System Architecture

ElectViz follows a layered:

**Data Sources → Data Processing → Data Modeling → DAX Analytics → Visualization → Media Insights**

architecture.

```text
                         ┌─────────────────────────┐
                         │   Media User / Analyst  │
                         └────────────┬────────────┘
                                      │
                                      ▼
                         ┌─────────────────────────┐
                         │   Power BI Dashboard    │
                         └────────────┬────────────┘
                                      │
                                      ▼
                 ┌────────────────────────────────────┐
                 │       Election Data Sources        │
                 │                                    │
                 │ • Election Results                 │
                 │ • Candidate Data                   │
                 │ • Political Party Data             │
                 │ • State Data                       │
                 │ • Constituency Data                │
                 │ • Voter Data                       │
                 │ • Demographic Data                 │
                 └─────────────────┬──────────────────┘
                                   │
                                   ▼
                         ┌─────────────────────────┐
                         │      Data Import        │
                         │                         │
                         │       Excel / CSV       │
                         └────────────┬────────────┘
                                      │
                                      ▼
                         ┌─────────────────────────┐
                         │       Power Query       │
                         │                         │
                         │ • Data Cleaning         │
                         │ • Data Transformation   │
                         │ • Data Formatting       │
                         │ • Data Filtering        │
                         └────────────┬────────────┘
                                      │
                                      ▼
                         ┌─────────────────────────┐
                         │   Data Validation &     │
                         │    Quality Checks       │
                         └────────────┬────────────┘
                                      │
                                      ▼
                         ┌─────────────────────────┐
                         │   Power BI Data Model   │
                         │                         │
                         │ • Relationships         │
                         │ • Dimensions             │
                         │ • Fact Data              │
                         └────────────┬────────────┘
                                      │
                                      ▼
                         ┌─────────────────────────┐
                         │   DAX Analytics Engine  │
                         │                         │
                         │ • Measures              │
                         │ • KPIs                  │
                         │ • Calculations          │
                         └────────────┬────────────┘
                                      │
             ┌────────────────────────┼────────────────────────┐
             │                        │                        │
             ▼                        ▼                        ▼
      ┌──────────────┐        ┌──────────────┐        ┌──────────────┐
      │   Election   │        │ Historical   │        │    Party     │
      │   Overview   │        │   Trends     │        │  Performance  │
      └──────┬───────┘        └──────┬───────┘        └──────┬───────┘
             │                       │                       │
             └───────────────────────┼───────────────────────┘
                                     │
             ┌───────────────────────┼────────────────────────┐
             │                       │                        │
             ▼                       ▼                        ▼
      ┌──────────────┐       ┌──────────────┐        ┌──────────────┐
      │  Candidate   │       │    State &   │        │    Voter     │
      │   Analysis   │       │ Constituency │        │   Turnout    │
      └──────┬───────┘       │   Analysis   │        └──────┬───────┘
             │               └──────┬───────┘               │
             └───────────────────────┼───────────────────────┘
                                     │
                         ┌───────────▼───────────┐
                         │  Demographic Analysis │
                         │       & Vote Share    │
                         └───────────┬───────────┘
                                     │
                                     ▼
                         ┌─────────────────────────┐
                         │     Media Insights &    │
                         │   Data-Driven Reporting │
                         └─────────────────────────┘

🔄 Project Workflow

Election Data Collection
          ↓
Data Import
          ↓
Data Cleaning & Preprocessing
          ↓
Data Transformation
          ↓
Data Validation
          ↓
Data Modeling
          ↓
DAX Measure Creation
          ↓
Dashboard Development
          ↓
Testing & Validation
          ↓
Performance Optimization
          ↓
Final Power BI Dashboard
          ↓
Media Insights & Reporting

🧩 Architecture Components
| Layer               | Component           | Purpose                                   |
| ------------------- | ------------------- | ----------------------------------------- |
| Data Source Layer   | Election datasets   | Provides raw election information         |
| Data Import Layer   | Excel / CSV         | Imports datasets                          |
| Processing Layer    | Power Query         | Cleans and transforms data                |
| Validation Layer    | Data Quality Checks | Verifies data consistency                 |
| Modeling Layer      | Power BI Data Model | Creates relationships between data        |
| Analytics Layer     | DAX                 | Creates measures and calculations         |
| Visualization Layer | Power BI            | Displays interactive dashboards           |
| Insight Layer       | Media Analysis      | Provides understandable election insights |

🛠️ Tools and Technologies
| Technology               | Purpose                                      |
| ------------------------ | -------------------------------------------- |
| **Microsoft Power BI**   | Dashboard development and data visualization |
| **Power Query**          | Data cleaning and transformation             |
| **DAX**                  | Analytical calculations and measures         |
| **Microsoft Excel**      | Dataset preparation                          |
| **CSV**                  | Election data storage                        |
| **Power BI Data Model**  | Data relationships and modeling              |
| **Power BI Maps**        | Geographical visualization                   |
| **Microsoft PowerPoint** | Project presentation                         |
| **Microsoft Word**       | Project documentation                        |

📂 Dataset

The project uses election-related datasets containing information such as:
Election Year
State
Constituency
Candidate
Political Party
Votes
Seats
Vote Share
Winning Margin
Winning Percentage
Gender
Age
Age Group
Male Electors
Female Electors
Male Votes
Female Votes
Voter Turnout

🧹 Data Cleaning & Preprocessing

Power Query is used to prepare raw election datasets.

Data Cleaning

The following operations are performed:

Remove duplicate records
Handle missing values
Correct data types
Standardize column names
Standardize party names
Standardize state names
Remove unnecessary columns
Correct inconsistent values
Data Transformation

Power Query is used for:

Creating calculated columns
Creating age groups
Transforming categorical data
Filtering records
Merging datasets
Appending datasets
Formatting data
Preparing turnout fields
🗃️ Data Modeling

The cleaned data is organized into a Power BI data model.

The main analytical dimensions include:

                         Election Data
                              │
          ┌───────────────────┼───────────────────┐
          │                   │                   │
          ▼                   ▼                   ▼
        State             Party              Candidate
          │                   │                   │
          ▼                   ▼                   ▼
    Constituency          Votes              Performance
          │                   │                   │
          └───────────────────┼───────────────────┘
                              │
                              ▼
                       Voter Participation
                              │
                 ┌────────────┴────────────┐
                 │                         │
                 ▼                         ▼
              Gender                   Demographics


🧮 DAX Analytics

DAX (Data Analysis Expressions) is used to create dynamic measures.

Total Seats
Total Seats =
COUNT('Lok Sabha'[PC_Name])

Total Seats
Total Seats =
COUNT('Lok Sabha'[PC_Name])
Total Votes
Total Votes =
SUM('Lok Sabha'[Total_Votes])
Seats Won
Seats Won =
CALCULATE(
    COUNT('Lok Sabha'[PC_Name]),
    'Lok Sabha'[Result] = "Won"
)
Seat Share
Seat Share =
DIVIDE(
    [Seats Won],
    [Total Seats],
    0
) * 100
Average Female Turnout
Average Female Turnout =
DIVIDE(
    SUM('Lok Sabha'[Female_Voters]),
    SUM('Lok Sabha'[Female_Electors]),
    0
) * 100
Average Male Turnout
Average Male Turnout =
DIVIDE(
    SUM('Lok Sabha'[Male_Voters]),
    SUM('Lok Sabha'[Male_Electors]),
    0
) * 100
📊 Dashboard Components
📌 KPI Cards

The dashboard can contain KPI cards for:

Total Seats
Seats Won
Total Votes
Vote Share
Voter Turnout
Average Turnout
📈 Charts

The project uses various Power BI charts including:

Bar Charts
Column Charts
Line Charts
Donut Charts
Pie Charts
Tables
Matrix Visuals
KPI Cards
Maps
🎛️ Interactive Filters

Users can dynamically filter election information using:

┌───────────────────────────────┐
│       INTERACTIVE FILTERS     │
├───────────────────────────────┤
│ Election Year                 │
│ State                         │
│ Constituency                  │
│ Political Party               │
│ Candidate                     │
│ Gender                        │
│ Age Group                     │
└───────────────────────────────┘

All dashboard visuals update dynamically based on the selected filters.

📊 Dashboard Modules
1. Election Overview Dashboard

Provides:

Total Seats
Seats Won
Total Votes
Vote Share
Voter Turnout
Party Performance
State-level summary
2. Historical Trends

Provides:

Year-wise election results
Party seat trends
Vote share trends
Turnout trends
Historical comparisons
3. Party Performance

Provides:

Party-wise seats
Party-wise votes
Vote share
State-wise party performance
Constituency-level performance
4. Candidate Analysis

Provides:

Candidate name
Party
Constituency
State
Votes
Winning margin
Winning percentage
Age
Gender
Education
5. State Analysis

Provides:

State-wise seats
State-wise votes
State-wise turnout
Female turnout
Male turnout
Party performance
6. Constituency Analysis

Provides:

Constituency results
Candidate performance
Votes received
Winning margin
Vote share
Turnout
7. Voter Turnout Analysis

Provides:

Total electors
Total votes cast
Male electors
Female electors
Male votes
Female votes
Male turnout
Female turnout
Overall turnout
8. Demographic Analysis

Provides analysis based on:

Gender
Age Group
Social Category
Geography
Regional participation
9. Vote Share Analysis

Provides:

Party-wise vote share
State-wise vote share
Constituency-level vote share
Historical vote share
Total votes
📁 Project Structure
ElectViz/
│
├── README.md
│
├── Dataset/
│   ├── election_data.csv
│   ├── candidate_data.csv
│   └── voter_data.csv
│
├── PowerBI/
│   └── ElectViz_Dashboard.pbix
│
├── Screenshots/
│   ├── election_overview.png
│   ├── historical_trends.png
│   ├── party_analysis.png
│   ├── candidate_analysis.png
│   ├── state_analysis.png
│   └── turnout_analysis.png
│
├── Documentation/
│   ├── Project_Report.docx
│   └── Project_Presentation.pptx
│
└── References/
    └── data_sources.txt

🚀 How to Run the Project
Step 1 – Install Power BI

Install Microsoft Power BI Desktop on your computer.

Step 2 – Clone the Repository
git clone https://github.com/your-username/ElectViz.git

Move into the project directory:

cd ElectViz
Step 3 – Prepare Dataset

Place the required CSV/Excel datasets inside:

Dataset/
Step 4 – Open Power BI File

Open:

PowerBI/ElectViz_Dashboard.pbix

using Microsoft Power BI Desktop.

Step 5 – Update Data Source

If the dataset path has changed:

Home
  ↓
Transform Data
  ↓
Data Source Settings
  ↓
Change Source

Select the correct dataset location.

Step 6 – Refresh Data

Click:

Home → Refresh

Power BI will update the dashboard using the latest available dataset.

Step 7 – Explore Dashboard

Use:

Slicers
Filters
KPI Cards
Charts
Maps
Tables
Interactive visuals

to explore the election data.

💡 Example Analytical Insights

The dashboard can be used to examine:

Changes in party performance across election years.
Distribution of seats across parties.
State-wise voting patterns.
Constituency-level election results.
Voter turnout differences.
Male and female participation.
Vote share distribution.
Candidate performance.
Regional election trends.
Demographic participation.
🎯 Target Users

ElectViz is designed for:

Media organizations
Journalists
Election data analysts
Researchers
Students
Data visualization professionals
Academic projects
Users interested in election data
💻 Application Flow
                    ┌───────────────┐
                    │     USER      │
                    └───────┬───────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ Power BI Dashboard  │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ Interactive Filters │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │   DAX Calculations  │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │   Data Model        │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │  Power Query        │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ Election Dataset    │
                 └─────────────────────┘
🔮 Future Enhancements

Future versions of ElectViz can include:

Real-time election result integration
Automated dataset updates
Advanced geospatial analysis
Machine learning-based election trend analysis
AI-powered election data summaries
Natural-language querying
Automated media report generation
Advanced interactive maps
Additional election datasets
Automated dashboard refresh
Cloud-based Power BI deployment
📌 Project Information
Information	Details
Project Name	ElectViz – Election Data Visualization for Media
Domain	Data Analytics & Business Intelligence
Primary Technology	Microsoft Power BI
Data Processing	Power Query
Analytics	DAX
Data Format	Excel / CSV
Project Type	Data Visualization & Election Analytics
Program	Infosys Springboard Internship Program
👩‍💻 Developer

Vaishnavi

Developed as part of the:

Infosys Springboard Internship Program

📜 License

This project is developed for educational, academic, and internship
purposes.

The datasets used in the project remain subject to the licenses and terms
of their respective sources.

⭐ Conclusion

ElectViz demonstrates how Power BI, Power Query, DAX, and data modeling
can be used to transform complex election datasets into meaningful and
interactive visualizations.

The project provides an integrated platform for exploring:

Election Results
      ↓
Party Performance
      ↓
Candidate Analysis
      ↓
State Analysis
      ↓
Constituency Analysis
      ↓
Voter Turnout
      ↓
Demographic Participation
      ↓
Vote Share
      ↓
Historical Trends
      ↓
Interactive Media Insights

ElectViz makes complex election data easier to explore, compare, and
understand through an interactive Business Intelligence dashboard.
