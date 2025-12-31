# Google Generative AI Issues Analysis

This repository contains bug tracking data for Google's Generative AI repositories.

## Data Summary

This analysis covers repositories owned by Google that contain 'generative-ai' in their names, focusing on open issues labeled as 'type:bug'.

### Repositories Analyzed

1. **google/generative-ai-docs** - Documentation for Google's Gen AI site including Gemini API and Gemma
   - Language: Jupyter Notebook
   - Stars: 2,223
   - Forks: 743
   - Open bug issues: 15

2. **google/generative-ai-go** - Go SDK for Google Generative AI
   - Language: Go
   - Stars: 834
   - Forks: 96
   - Open bug issues: 7

### Key Findings

- **Total open bug issues**: 22 across both repositories
- **Most affected repository**: google/generative-ai-docs (15 bugs, ~68% of total)
- **Average bugs per repository**: 11

## Bug Categories Observed

Based on the issue analysis, common bug types include:

- **Documentation issues**: Broken links, missing content, outdated examples
- **API integration problems**: Authentication errors, connection timeouts
- **SDK compatibility**: Version conflicts, missing features
- **Build/dependency issues**: Package installation problems

## Files

- `google_generative_ai_bug_report.csv` - CSV file containing the bug count data
- `README.md` - This documentation file

## Usage

The CSV file can be used for:
- Data analysis and visualization
- Tracking bug resolution trends
- Understanding project health metrics
- Learning about common issues in AI/ML projects

## Methodology

Data was collected using GitHub's API to search for:
- Repositories owned by Google with 'generative-ai' in the name
- Open issues labeled with 'type:bug'
- Issue counts aggregated by repository

This analysis provides insights into how large organizations like Google manage bug tracking and issue resolution in their AI/ML projects.