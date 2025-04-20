# AI Automation Assignment – Lead Management System
This project is part of an internship assignment that demonstrates how to automate a lead management system using Make.com, Phantombuster, Apify, Google Sheets, and Python. The aim was to streamline lead generation, enrichment, and storage for outreach campaigns.

# Objective
To automate the process of:
Extracting leads from Google Maps.
Enriching lead data using additional scraping techniques.
Storing and updating the data in Google Sheets.
Scraping brand info using Python.
Generating content from niche-related keywords.

# Tools Used
Make.com – For automation workflows.
Phantombuster and Apify – Used for lead scraping.
Google Sheets – For storing and managing extracted leads.
Python – For web scraping and keyword-based content generation.

# Project Structure
Part A – Lead Automation Workflow
1. Setting Up Phantombuster Monitoring (Apify Alternative)
Set up a Phantombuster agent to extract business leads from Google Maps.


2. Automating Data Transfer to Google Sheets (via Make.com)
Make.com scenario monitors the completion of the Phantombuster task.
Automatically fetches the newly extracted data.
Cleans and formats the data to ensure:
Consistency
No duplication

3. Lead Enrichment
A custom scraper was built and integrated into the workflow.
It visits each company’s official website to extract alternative or secondary email addresses.
This increases the chance of successful contact by sales teams.

4. Integration with Google Sheets
Enriched data is sent to Google Sheets in real-time.
Each new entry is appended, maintaining structure and ease of access.
Allows better analysis and prioritization of leads.

# Task 2 – Python-Based Brand Scraper & Content Generator
Step 1: Scrape Brand Descriptions
Selected 2 brands from the lead data stored in Google Sheets.
Wrote a Python script to extract "About Us" or brand descriptions from their official websites.

Step 2: Generate Keyword-Based Content
Extracted niche-related keywords from the brand descriptions using simple NLP techniques.
Used those keywords to auto-generate content that could be used for marketing or email outreach.

# Access The Drive
link:https://drive.google.com/drive/folders/1qCmd4oTvFLjWIs82hcypqo320-tiukrD?usp=sharing
