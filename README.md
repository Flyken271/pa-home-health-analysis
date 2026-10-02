# Pennsylvania Home Health Agencies: Ownership, Quality & Services

## The Question
Do for-profit home health agencies in PA rate lower or offer fewer
services than non-profits?

## The Data
- Source: CMS Home Health Care Agencies (July 2026), 415 PA agencies
- Tools: Power BI (Power Query, DAX)

## How I Cleaned It
• Filtered source data to only include the state of Pennsylvania.
• Consolidated source data to remove "-" (unknown data points) and rename corresponding data points to "UNKNOWN".
• Renamed data columns to better represent their corresponding data.
• Added an additional data column to consolidate data into "Services Offered" for better data readings.

## Key Findings
• For-profits make up 70% of PA agencies (290 of 415).
• Government PA agencies list unknown data points (services offered and or star ratings).
• UNKNOWN agencies score lower star ratings.
• Non-profit and for-profit agencies roughly offer similar percentages of services compared to each other.

## Limitations
• Under half of the listed agencies have a star rating.
• Data Selection is limited to the state of Pennsylvania.
• Unknown data points exist within the report.
• Government agencies are excluded from "Services Offered" and "Agency Count" as there was only 1 agency listed as GOVERNMENT.

## Screenshot
![Dashboard](Dashboard.png)