# TurnTable-Data-Analyst-Assessment
## Objective

This project consolidates Radio, YouTube, and Audiomack music consumption data to generate a unified Weekly Top 10 chart.

##Task 1: Methodology
Data Cleaning
Standardized column names
Converted text fields to lowercase
Removed extra whitespace
Converted platform metrics to numeric format
Aggregated duplicate song records

###Normalization
Platform metrics were normalized using max-value scaling to account for differences between radio impressions and streaming counts.
Weighting Assumptions
YouTube: 35%
Audiomack: 35%
Radio: 30%

###Data Limitations
Radio data did not contain artist metadata.
Radio matches were performed using song titles only.
Songs with identical titles across artists may introduce ambiguity.


##Task 2: Industry Insight & Interpretation

PBUY's immediate success on streaming platforms reflects the speed of digital fan engagement and release-week hype. By June 2022, Asake had already built significant momentum through previous releases, creating strong anticipation and first-week streaming demand.

The song's movement from #6 to #1 on radio demonstrates the delayed adoption cycle typical of Nigerian radio programming. Strong streaming performance likely validated audience demand, resulting in increased radio rotation in subsequent weeks.

The significantly weaker TV performance compared to streaming and radio highlights structural differences in music discovery and distribution. Television airplay depends on video availability, playlist approvals, and scheduling, while younger Nigerian audiences increasingly discover music through streaming and social platforms.
