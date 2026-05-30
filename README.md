# TurnTable-Data-Analyst-Assessment
## Objective

This project consolidates Radio, YouTube, and Audiomack music consumption data to generate a unified Weekly Top 10 chart.

## Part 1: Technical Validation & Data Aggregation
### Methodology
### Data Cleaning
- Standardized column names
- Converted text fields to lowercase
- Removed extra whitespace
- Converted platform metrics to numeric format
- Aggregated duplicate song records

### Normalization
Platform metrics were normalized using max-value scaling to account for differences between radio impressions and streaming counts.

### Weighting Assumptions
- YouTube: 35%
- Audiomack: 35%
- Radio: 30%

### Data Limitations
- Radio data did not contain artist infomation.
- Radio matches were performed using song titles only.
- Songs with identical titles across artists may introduce ambiguity.

### Deliverables
- Jupyter Notebook containing all code and analysis
- Top 10 leaderboard export
- Analytical commentary for chart interpretation

## Part 2: Industry Insight & Interpretation
- PBUY's #1 debut on streaming reflects the impact of release-week demand and digital-first music consumption. Streaming platforms respond immediately to listener behavior, and Asake's momentum from earlier hits generated strong first-week activity driven by fans, social media conversations, and repeat plays. The movement from #1 to #3 in week two suggests release-week hype began to normalize as listening shifted from discovery to sustained consumption.

- The rise from #6 to #1 on radio reflects the slower adoption cycle of Nigerian radio programming. Unlike streaming platforms where demand is immediate, radio growth depends on playlist additions, presenter and DJ support, audience response, and promotional activity. Strong streaming performance likely validated audience demand, resulting in increased radio rotation in the following week.

- The weaker TV performance (#31) compared with streaming and radio highlights differences in distribution speed and audience behavior. Television airplay depends on factors such as video availability, playlist approval processes, and scheduling constraints, creating a slower path to chart growth. It also reflects the broader shift in Nigerian music discovery toward mobile streaming and social platforms, where younger audiences typically engage with new releases first.

