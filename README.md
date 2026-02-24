# CRM Lead Generation & Lead Scoring Pipeline

## Overview
This project demonstrates an end-to-end CRM data preparation workflow, focusing on lead generation, data cleaning, enrichment, and rule-based lead scoring.

The goal is to transform raw, messy lead data into a clean, structured, and prioritized dataset that can be directly imported into a CRM system for sales and marketing use.

---

## Business Problem
Sales teams often receive large volumes of raw leads with inconsistent formatting, missing values, and no prioritization.  
Without proper cleaning and scoring, high-quality leads can be overlooked while low-quality leads consume sales resources.

This project addresses that problem by:
- Standardizing lead data
- Enriching key attributes
- Assigning a lead score to prioritize outreach

---

## Key Features
- Cleaning and standardization of raw lead data
- Email validation and normalization
- Creation of derived fields (e.g., full name)
- Country, company, and lead-source normalization
- Rule-based lead scoring logic
- CRM-ready structured output

---

## Tools & Technologies
- Python
- Pandas
- Jupyter Notebook
- Mockaroo (for realistic mock lead data)
- Git & GitHub

---

## Dataset
The dataset represents simulated CRM lead data and includes fields such as:
- First name
- Last name
- Email address
- Company
- Country
- Lead source
- Job title

The raw data intentionally includes inconsistencies (capitalization, spacing, formatting) to reflect real-world CRM data challenges.

---

## Lead Scoring Logic
Leads are scored using a rule-based approach, including factors such as:
- Email domain quality (business vs free email providers)
- Lead source quality (e.g., LinkedIn, referrals, website)
- Target country alignment
- Completeness of lead information

Each lead receives a numerical score that can be used to:
- Prioritize sales outreach
- Segment leads
- Support automated CRM workflows

---

## Workflow
1. Load raw lead data
2. Clean and normalize text fields
3. Validate and standardize email addresses
4. Create derived fields (full name)
5. Apply rule-based lead scoring logic
6. Produce a CRM-ready dataset

---

## Project Structure
