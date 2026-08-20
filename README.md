# Ai-hiring-market-analysis
Global AI Hiring Market Analysis — Skills, Salaries, Roles, Geography &amp; Predictive Modeling

## Overview

This project analyzes the global AI job market to understand which **skills, roles, experience levels and geographic markets** are associated with higher hiring demand and compensation.

The project was built as a client facing **"State of AI Hiring"** analysis for HR and talent teams. The objective was not only to report statistics, but to turn job-market data into practical recommendations for recruitment and compensation strategy.

The analysis uses the **AI Job Market Global 2026** dataset, which contains real AI job postings with information on skills, salaries, locations, experience levels and roles.

---
![AI Jobs Market Intelligence Dashboard](images/Screenshot 2026-08-20 202306.png)

## Business Problem

AI and data hiring is growing rapidly, but HR teams face an important question:

> **Which AI skills, roles and markets are actually worth paying a premium for?**

This project investigates:

- Which AI skills are most in demand?
- Which skills are associated with higher salaries?
- Where is AI hiring concentrated geographically?
- How does salary vary across countries?
- How does compensation differ by experience level?
- Does having more listed skills necessarily mean higher salary?
- What separates high-paying AI jobs from the rest?

---

## Project Objectives

The analysis was structured around four stages:

### Part A — Data Understanding & Cleaning

- Load and inspect the job market dataset
- Examine missing values and data types
- Identify salary-related data quality issues
- Calculate average salary from minimum and maximum salary
- Normalize the skills data
- Prepare the dataset for analysis

### Part B — Skill Premium & Demand Analysis

- Calculate job demand by individual skill
- Calculate average salary associated with skills
- Analyze hiring demand by country
- Compare salary across major hiring markets
- Analyze demand and compensation by experience level

### Part C — Analytical / Predictive Layer

The project follows the Data Analyst track with deeper analysis of:

- Salary correlations
- Experience level relationships
- Skill count relationships
- Salary segmentation
- High paying salary bands
- Characteristics of higher-paying jobs

### Part D — Client-Facing Report

The findings were converted into a short **State of AI Hiring 2026** report with:

- Key market insights
- Salary and skill findings
- Geographic hiring patterns
- HR implications
- A practical compensation recommendation

---

## Dataset

**Dataset:** AI Job Market Global 2026

The dataset contains approximately 5,700+ real AI job postings collected from public job APIs.

Key fields include:

- Job title
- Company
- Country
- City
- Minimum salary
- Maximum salary
- Currency
- Remote type
- Experience level
- Required skills
- Posted date
- Job description
- Source

The assignment describes the dataset as real job-market data rather than simulated data.

---

## Tools & Technologies

### Python

- Pandas
- NumPy
- Matplotlib

### Business Intelligence

- Microsoft Power BI
- DAX
- Power Query

### Analysis

- Data cleaning
- Exploratory data analysis
- Correlation analysis
- Salary segmentation
- Skill demand analysis
- Geographic analysis

---

## Data Preparation

Salary was converted into an estimated midpoint using:

```text
Average Salary = (Salary Minimum + Salary Maximum) / 2
