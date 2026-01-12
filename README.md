# resume_analyzer
Overview

This project is a Python-based Resume Analyzer that compares a candidate’s resume with a job description and evaluates how well the skills match.
It simulates basic Applicant Tracking System (ATS) logic using rule-based text analysis instead of unrealistic AI claims.

The tool identifies matching skills, missing skills, skill strength based on keyword frequency, and provides actionable suggestions to improve the resume.
Features

Reads resume and job description from text files

Extracts technical skills using regex-based matching

Calculates skill match percentage

Identifies missing job-required skills

Measures skill strength based on keyword frequency

Generates practical resume improvement suggestions

Handles file errors gracefully
Project Structure
resume_analyzer/
under this folder create files
├── analyzer.py
├── resume.txt

└── job_description.txt
How It Works

The resume and job description are loaded from text files.

A predefined skill list is used for comparison.

Skills are extracted using case-insensitive regex matching.

Matching and missing skills are identified using set operations.

Skill strength is calculated based on how often a skill appears.

A match score and improvement suggestions are generated.
How to Run the Project

Clone or download the project.

Place your resume text in resume.txt.

Place the job description in job_description.txt.

Run the script: python analyzer.py
