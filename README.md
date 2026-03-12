# Resume–Job Matching Module

This repository contains the **resume–job semantic matching component** of the blog post *“Building an Automated Resume–Job Matching Workflow.”*

The code compares a candidate’s resume with a collection of job descriptions and ranks job opportunities based on semantic similarity. It is designed as a **decision-support tool** to help prioritize job applications.

## Method

The workflow includes the following steps:

1. Extract resume text from a PDF file  
2. Normalize resume and job description text  
3. Generate embeddings using Sentence Transformers (`all-MiniLM-L6-v2`)  
4. Compute cosine similarity between the resume and job descriptions  
5. Rank job postings and visualize the Top-K matches

## Blog Article

A detailed explanation of the full project pipeline is available in our Medium blog post:

https://medium.com/sfu-cspmp/from-manual-search-to-data-driven-decisions-building-an-automated-resume-job-matching-workflow-029c5c7e36d4

## Team

- Hongrui Qu  
- Jiayi Li  
- Joohyun Park  
- Tracy Cui  
