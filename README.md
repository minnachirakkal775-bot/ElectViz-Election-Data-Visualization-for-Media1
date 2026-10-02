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
