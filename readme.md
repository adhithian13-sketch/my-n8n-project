# AI Resume Screening & Candidate Evaluation Automation

## Overview

This project automates the resume screening process using AI and workflow automation.

The system accepts candidate resumes, extracts relevant information, analyzes skills and experience, compares candidates against job requirements, and generates structured evaluation reports.

The workflow eliminates manual resume review, reduces hiring time, and helps recruiters identify suitable candidates more efficiently.

---

## Problem Statement

Recruiters often spend significant time manually reviewing resumes to identify qualified candidates.

Challenges include:

* Large volume of applications
* Inconsistent resume formats
* Manual skill matching
* Time-consuming candidate evaluation
* Human bias and oversight

This automation streamlines the process by using AI to extract, analyze, and evaluate candidate information automatically.

---

## Features

### Resume Processing

* Accept PDF resumes
* Extract candidate information
* Parse skills and experience
* Identify educational qualifications
* Detect certifications and projects

### AI Candidate Evaluation

* Analyze candidate profiles
* Compare skills with job requirements
* Generate candidate summaries
* Evaluate candidate suitability
* Produce structured hiring insights

### Automated Reporting

* Candidate score generation
* Skill gap analysis
* Recruiter-friendly summaries
* Structured output for decision making

---

## Technology Stack

### Workflow Automation

* n8n

### AI Models

* OpenAI GPT Models

### Document Processing

* PDF Parsing
* Text Extraction

### Integrations

* Webhooks
* HTTP Requests
* Cloud Storage
* Recruitment Workflows

---

## Architecture

Resume Upload

↓

Resume Extraction

↓

Text Processing

↓

AI Analysis

↓

Skill Evaluation

↓

Candidate Scoring

↓

Report in google sheets

↓

Recruiter Dashboard / Output

---

## Workflow Breakdown

### Step 1: Resume Submission

Candidate uploads a resume in PDF format.

---

### Step 2: Document Extraction

The workflow extracts all text content from the resume.

Information identified includes:

* Name
* Contact Information
* Skills
* Education
* Experience
* Certifications
* Projects

---

### Step 3: AI Analysis

The extracted content is sent to an LLM for intelligent analysis.

The AI:

* Understands candidate background
* Identifies key competencies
* Summarizes professional profile
* Evaluates overall suitability

---

### Step 4: Skill Matching

The candidate profile is compared against predefined hiring criteria.

Examples:

* Required technologies
* Experience level
* Educational qualifications
* Domain expertise

---

### Step 5: Candidate Evaluation

The AI generates:

* Candidate summary
* Strengths
* Weaknesses
* Missing skills
* Hiring recommendation

---

### Step 6: Report Generation

A structured report is generated for recruiters in google sheets

* Candidate Details
* Skill Assessment
* Experience Analysis
* Recommendation Score
* Final Summary

---



---

## Use Cases

### Recruitment Agencies

Automated candidate screening.

### HR Teams

Resume filtering and ranking.

### Staffing Companies

Bulk resume processing.

### Educational Institutions

Student placement evaluation.

---

## Key Benefits

* Faster resume review
* Reduced manual effort
* Consistent candidate evaluation
* Improved recruiter productivity
* Scalable hiring workflows
* AI-assisted decision making

---

## Results

* Automated resume analysis
* Structured candidate insights
* Reduced screening time
* Improved hiring efficiency
* Standardized evaluation process

---

## Future Improvements

* ATS Integration
* Multi-job Role Matching
* Candidate Ranking Dashboard
* Email Automation
* Interview Scheduling
* Resume Database Search
* RAG-based Candidate Search

---

## Skills Demonstrated

* AI Automation
* n8n Workflow Development
* Document Processing
* Prompt Engineering
* Resume Parsing
* Candidate Evaluation Systems
* API Integration
* Recruitment Automation

---

## Author

Adhithian

AI Automation Enthusiast

Portfolio Focus:

* AI Agents
* Workflow Automation
* RAG Systems
* WhatsApp Chatbots
* Business Process Automation
