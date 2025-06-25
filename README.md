# Aviation Risk Analysis

## Author
Neema Naledi

## Objective

This project provides a data-driven assessment of aviation accident history to inform investment decisions as your organization enters the aircraft acquisition space. Leveraging National Transportation Safety Board (NTSB) aviation accident data from 1962 to 2023, the goal is to identify aircraft types with the *lowest operational risk* for commercial and private use.

Support the aviation division in selecting the safest aircraft for purchase and operation by:
- Analyzing historical accident trends
- Identifying low-risk aircraft makes and models
- Translating insights into actionable, business-friendly recommendations

## Tools & Methods

- **Platform**:  VS code
- **Data Cleaning & Transformation**: Jupyter Notebook 
- **Data Aggregation**:
  - Grouping by **aircraft make/model**, **year**, **injury severity**, and **purpose of flight**
  - Calculating **accident frequency rates** per aircraft
- **Handling Missing Values**:
  - Key identifiers (e.g. date, aircraft type): rows removed if missing
  - Less critical fields categorized as "Unknown"

## Analysis Journey

### 1. Data Preparation
Filtered dataset to exclude:
- Non-civil flights
- Duplicates and entries lacking aircraft info
- Incidents without injury or damage records

### 2. Aggregation & Metrics
- Total accidents by **aircraft make/model**
- Accidents by **flight type** and **injury severity**
- **Fatality ratio** by aircraft type (fatal accidents ÷ total accidents)

### 3. Visualization Strategy
Three dashboard pages to tell a concise story:
- **Overview Page**: Total accidents over time, severity breakdown, key KPIs
- **Aircraft Risk Profile**: Ranked list of aircraft types with incident rates and fatality ratios
- **Flight Operation Insights**: Breakdown by flight purpose and environmental conditions

## Key Findings & Business Recommendations

1. **Prioritize Aircraft with Low Fatality Ratios**  
   Aircraft like the *Cessna 172* and *Beechcraft Bonanza* showed high usage but relatively fewer fatal outcomes, making them ideal low-risk starter models.

2. **Avoid Aircraft with High Frequency & High Severity Incidents**  
   Models such as the *Piper PA-46* had disproportionately high fatality rates, warranting caution.

3. **Target Commercial Use Aircraft with Favorable Safety Records**  
   Aircraft primarily used for scheduled passenger service (e.g., regional jets and light twin-engine aircraft) had lower overall accident rates per operational hour.

##  Why It Matters

Effective risk management is essential to long-term success in aviation. This dashboard empowers leaders to make investment decisions rooted in safety data, not guesswork.

By combining solid data cleaning, clear aggregation, and visual storytelling, the analysis aligns directly with the company's strategic goal of minimizing liability while entering a competitive industry.

##  Getting Started

To explore the dashboard:
1. Open `aviation-risk-dashboard.pbix` in Power BI Desktop.
2. Use slicers to filter by year, flight type, or aircraft model.
3. Hover over visuals for detail tooltips.

##  Future Enhancements

- Incorporate FAA operational hour data for normalized risk scoring
- Add interactive narrative tooltips to guide non-technical users
- Monitor real-time updates using live NTSB data feeds

  ## Contributions
Contributions to Aviation Risk Analysis are welcome! 
If you have any suggestions, bug fixes, or additional features you'd like to add, please feel free to submit a pull request or open an issue.

## Acknowledgments
Inspiration

## Support
For support, email naledi.student@moringaschool.com



