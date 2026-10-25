# Impact Data Analysis — Portfolio Project

## Purpose
This project demonstrates a structured approach to analysing programme participation and follow-up survey data. The dataset is **synthetic** and is not based on real participants or actual client results.

## Questions to explore
1. How many participants are recorded by province and workshop?
2. What is the survey response rate by workshop?
3. What changes are reported between a fictional pre-workshop score and post-workshop score?
4. Are there missing values, duplicate participant IDs or inconsistent categories?
5. What limitations should be explained before interpreting the results?

## Files
- `synthetic_impact_data.csv` — fictional sample records.
- `data_dictionary.md` — field definitions.
- `analysis_plan.md` — suggested data-quality checks and reporting steps.

## Suggested workflow
1. Open the CSV in Excel and format the data as a table.
2. Check duplicate IDs, missing fields, valid ranges and category consistency.
3. Use PivotTables or Power BI to summarise participants by province and workshop.
4. Calculate response rate using the number of completed follow-up surveys divided by eligible participants.
5. Compare pre- and post-workshop scores only for records with both values.
6. Document sample size, missing data and limitations alongside any charts.

## Suggested visuals
- Participants by province (bar chart)
- Survey completion rate by workshop (bar chart)
- Average pre- and post-workshop score (clustered column chart)
- Missing-data summary (bar chart or table)

## Important interpretation note
A change in survey scores is not, by itself, proof that a workshop caused the change. Report the sample size, missing responses and any limitations. Do not claim impact beyond what the data supports.
