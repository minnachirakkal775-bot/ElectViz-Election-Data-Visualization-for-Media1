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
