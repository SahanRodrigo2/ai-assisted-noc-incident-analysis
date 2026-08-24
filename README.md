# AI-Assisted NOC Incident Analysis

## Project Overview

This project demonstrates the use of AI-assisted thematic analysis,
spreadsheet-based analysis, and NOC operational reasoning to analyze
a synthetic dataset of 200 infrastructure and network incidents.

The project was developed as a practical application of the Cisco
"Apply AI: Analyze Customer Reviews" course concepts, adapted to an
IT Operations and NOC environment.

## Objective

The objective was to determine whether AI could assist with the
first-pass analysis of NOC incident descriptions while maintaining
human validation and rule-based classification.

The analysis focused on:

- Incident categorization
- Incident subcategorization
- Operational impact
- Customer impact
- Suggested causes
- Recurring incident themes
- Proactive monitoring opportunities

## Dataset

The dataset contains 200 synthetic NOC incidents covering areas such as:

- Server
- Network
- Application
- Authentication
- Backup
- Storage
- Cloud

No real customer or production incident data was used.

## Methodology

The project followed a structured workflow:

1. Created a synthetic NOC incident dataset.
2. Defined classification rules.
3. Used an LLM for first-pass incident analysis.
4. Classified incidents by category and subcategory.
5. Assessed operational and customer impact.
6. Generated suggested causes where supported by the incident description.
7. Performed human validation and spot-checking.
8. Applied thematic analysis to identify recurring incident patterns.
9. Summarized the results using Excel.
10. Created a NOC-focused dashboard and monitoring recommendations.

## Key Findings

- 200 incidents were analyzed.
- 131 incidents (65.5%) were classified as High operational impact.
- 72 incidents (36.0%) were categorized as Server incidents.
- 63 incidents (31.5%) were categorized as Network incidents.
- Server and Network incidents represented 67.5% of the dataset.
- Server Unavailability was the most frequent incident theme with 27 incidents.
- High CPU Utilization was the second most frequent theme with 23 incidents.

## NOC Operational Insights

The analysis identified several areas suitable for proactive monitoring:

- Server availability and health monitoring
- CPU utilization trend monitoring
- Network interface monitoring
- Packet-loss monitoring
- VPN connectivity monitoring
- Backup capacity monitoring
- Backup job failure monitoring
- Disk capacity monitoring
- Authentication failure monitoring

## AI Usage

AI was used as a first-pass analytical assistant rather than as the
final decision-maker.

The workflow combined:

**LLM → Rule-based classification → Human validation → Thematic analysis → Dashboard**

This approach was used to reduce unsupported assumptions and improve
consistency in incident classification.

## Tools Used

- Microsoft Excel
- Large Language Model (LLM)
- AI-assisted thematic analysis
- Spreadsheet-based data analysis
- Data visualization
- NOC / IT Operations concepts

## Limitations

The dataset is synthetic and intended for educational and portfolio
purposes.

Customer impact was classified as Unknown when the incident description
did not provide sufficient evidence to determine actual customer impact.

Suggested causes were not treated as confirmed root causes when the
incident description did not contain sufficient evidence.

## Outcome

This project demonstrates how AI can support NOC analysts with high-volume first-pass incident classification and thematic analysis
while keeping human validation and operational judgment in the workflow.
high-volume first-pass incident classification and thematic analysis
while keeping human validation and operational judgment in the workflow.
