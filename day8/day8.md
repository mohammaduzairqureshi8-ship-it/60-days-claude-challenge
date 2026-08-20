#prompt:

Act as a Senior Data Analyst, Environmental Researcher, UX Designer, and Frontend Dashboard Developer.
Create a Claude Artifact called:
🌍 Personal Environmental Health Analyzer
DATA RULES
If a dataset is provided, use it. If no dataset is provided, automatically search the web for the latest AQI and water-quality data for the user's current city/location. If location is unavailable, ask for the city name first. Use the most recent available data, cite sources, clean the data, handle missing values, and validate quality before analysis.
ANALYSIS
Generate: cleanest city, most polluted city, highest AQI city, lowest AQI city, average AQI, number of cities analyzed, trends, anomalies, most surprising observation, executive summary.
INTERACTIVE DASHBOARD
Create a fully interactive Claude Artifact with:
📊 Key Metrics: average AQI, highest AQI city, lowest AQI city, number of cities analyzed, environmental health score.
📈 Visualizations: AQI comparison chart, PM2.5 comparison chart, PM10 comparison chart, city ranking chart, AQI distribution chart.
🎛 Interactive Filters: city selector, AQI range filter, pollutant selector, health-risk filter, date filter (if available), city comparison mode.
📋 City Detail Cards: AQI, PM2.5, PM10, air-quality category, health score, water-quality score.
🚦 AQI Categories: Good (Green), Satisfactory (Light Green), Moderate (Yellow), Poor (Orange), Very Poor (Red), Severe (Dark Red).
ENVIRONMENTAL HEALTH ANALYSIS
For the selected city explain AQI impact on lungs, sleep, energy levels, exercise performance, long-term health, and water-quality impact on hair fall, hair dryness, scalp health, skin dryness, acne, and sensitive skin.
Use risk indicators: 🟢 Low, 🟡 Moderate, 🔴 High.
PERSONAL REPORT CARD
Generate an Environmental Health Score (0–100) with breakdowns for Air Quality Score, Water Quality Score, and Overall Environmental Score.
Assign grades for Air Quality (A–F), Water Quality (A–F), Hair Risk, and Skin Risk.
INSIGHTS PANEL
Include: top 3 cleanest cities, top 3 most polluted cities, biggest anomaly, most surprising observation, recommended actions.
PERSONALIZED RECOMMENDATIONS
Provide: daily actions, indoor air improvements, outdoor activity guidance, hair-care recommendations, skin-care recommendations, water-quality improvement suggestions.
DESIGN
Modern, professional, mobile responsive, dark theme, smooth animations, premium UI, clean typography, dashboard-style layout, highly visual, colourful, LinkedIn-shareable.
OUTPUT
Generate a complete downloadable HTML application that is fully responsive and ready to save as index.html.
IMPORTANT
Do not provide code snippets. Create a complete interactive Claude Artifact with working charts, filters, cards, insights, report cards, and dashboards that users can interact with directly.

output:

Here's your 🌍 Personal Environmental Health Analyzer — a fully interactive, LinkedIn-shareable dashboard built with live data sourced from IQAir, AQI.in, and CPCB.

What's inside (all 6 tabs):

📊 Dashboard — Lucknow's current AQI is 98 (Moderate) with PM2.5 at 34 µg/m³ and PM10 at 39 µg/m³, benchmarked against 11 other major cities. Five interactive charts: AQI comparison, PM2.5 vs WHO guideline, PM10, city ranking, and a 2026 seasonal trend. Filters by region, AQI range, pollutant, and risk level.
AQI

🏙️ City Cards — 12 city detail cards with AQI, PM2.5, PM10, water quality, air/water/health grades, and click-to-select for personalised analysis.

🫀 Health Analysis — Switch between cities to see AQI impact on lungs, sleep, energy, exercise, long-term risk, plus water quality impact on hair fall, scalp health, skin dryness, and acne — each with 🟢/🟡/🔴 risk indicators.

📋 Report Card — In 2026, 0% of 222 days in Lucknow were within WHO's safe air quality limits. The card generates an overall Environmental Health Score (0–100) with letter grades for Air (F), Water, Hair Risk, and Skin Risk.
AQI

💡 Insights — India's average PM2.5 concentration in 2025 was 48.9 µg/m³, nearly 9.78 times higher than the WHO annual guideline of 5 µg/m³. Includes executive summary, top 3 cleanest/most polluted cities, biggest anomaly, and surprising observations.
IQAir

✅ Recommendations — Personalised daily actions, indoor air upgrades, outdoor guidance, hair care, skin care, and water quality tips for Lucknow specifically.

<iframe src="./page.html" width="100%" height="400px" frameborder="0"></iframe>
