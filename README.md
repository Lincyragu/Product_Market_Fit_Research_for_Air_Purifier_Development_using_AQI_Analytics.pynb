Product-Market-Fit Research for Air Purifier Development Using AQI Analytics
This repository contains a complete data-driven market research project conducted as part of the Codebasics Resume Project Challenge (#16).
The project focuses on analyzing India’s air quality (AQI) trends, health outcomes, vehicle adoption, and competitor landscape to evaluate product-market fit for air purifier development.

📌 Project Overview
Objective: Identify market opportunities, target audience, and optimal product features for air purifiers in India using AQI-driven insights.
Scope: Primary and secondary data analysis of AQI (2022–2025), health costs, vehicle adoption, demographics, and product benchmarking.
Outcome: Actionable strategic recommendations for air purifier design, smart features, and market prioritization.
📂 Repository Contents
AQI (2022 – 2025).xlsx → Air Quality Index data (city/state level)
Health Consequences (2022 – 2025).xlsx → Reported diseases & health impacts linked to AQI
Population data.xlsx → State-wise population growth & projections (2011–2036)
Vehicle data (2022 – 2025).xlsx → Vehicle registrations by fuel type & class
Primary_and_Secondary_Analysis.pdf → Detailed write-up of research insights
Google Colab Notebook → Complete code (Python, Pandas, Seaborn, Matplotlib) + exploratory analysis
PPT Presentation → Final business presentation summarizing research findings and strategic direction
🧹 Data Cleaning & Processing
Performed end-to-end data wrangling before analysis:

Removed irrelevant/redundant columns, handled missing values through imputation/removal.
Standardized vehicle fuel types, disease names, pollutant categories, and state labels.
Unified date formats and validated pollutant names.
Documented every preprocessing step in the Google Colab Notebook.
📊 Key Analyses & Insights
🔹 Primary Analysis
Top vs Bottom AQI Regions (2024–25): Bihar, NCR, Haryana worst → Southern states much cleaner.
Southern States Pollutants: PM10 & PM2.5 dominate; CO in Karnataka, O₃ in Puducherry.
Weekday vs Weekend AQI: No uniform trend — varies by city sources/traffic/weather.
Worst Months: Winter (Oct–Jan) most polluted due to stubble burning + inversion.
Disease Burden: Diarrheal diseases + food poisoning dominate; dengue/malaria in NE & north.
EV Adoption vs AQI: EV-heavy states still polluted → EV adoption alone cannot reduce AQI.
🔹 Secondary Analysis
Vulnerable Groups: Children <5 and elderly most at risk during AQI spikes (asthma, respiratory cases).
Competitor Benchmarking:
Dyson: premium, multifunction, advanced VOC removal.
Philips: balanced performance, smart features, trusted brand.
Coway: quiet, durable filters, but lacks smart features.
Population vs AQI: Large states like Karnataka manage good air quality; AQI not tied to population size alone.
Public Awareness: Higher in metros (Delhi, Mumbai); limited elsewhere due to outreach and trust issues.
Policy Impact (NCAP, BS-VI): Mixed results — regional variation, partial success, several hotspots persist.
🔹 Critical Insights
City Risk Analysis: Delhi, Kolkata, Noida, Ghaziabad = top priority for interventions and products.
Health Cost Impact: Delhi faces >1200 crores/year in pollution-driven health costs; other metros show high burden too.
Feature Gap Matrix: Consumers want multi-pollutant sensors, AQI syncing, portable compact design, energy-efficient modes, health-focused modes (for kids/elderly).
Consumer Behavior: Pollution emergencies trigger spikes in purifier demand (Delhi, Mumbai, Ludhiana).
💡 Strategic Recommendations
Product Design:

Multi-pollutant sensing (PM, NO₂, SO₂, VOCs).
Compact & portable designs for urban homes.
Smart syncing with real-time AQI + health-focused modes.
Longer filter life + clear alerts.
Market Targeting:

Focus on high-risk, high-income metros: Delhi, Noida, Ghaziabad, Kolkata, Greater Noida.
Expand later into Tier-2 cities with education-driven marketing.
Awareness & Education:

Build consumer trust with reliable AQI-linked campaigns.
Partner with government clean-air initiatives.
🛠 Tools & Resources
Python (Pandas, Matplotlib, Seaborn) → data cleaning, EDA, and visualizations
MS PowerPoint → Report storytelling + product strategy presentation
Colab → Interactive, reproducible analysis
Flaticon, Slideshare → Icons & design assets
Sources: AQI.in, IQAir, CPCB, Lancet, WHO, Economic Times, CREA Report, etc.
🙏 Acknowledgements
This project was completed as part of the Codebasics Resume Challenge #16.
Thanks to Codebasics for the opportunity and to DATAFUL for providing the datasets.
Special thanks to OpenAI & Perplexity AI for research assistance during exploration.

👨‍💻 About Me
Hi, I’m Lincy R, an aspiring Data Analyst passionate about turning complex environmental and market data into actionable insights for business impact.

💼 LinkedIn: Avik Sarkhel
📧 Email: avik305sarkhel@gmail.com
⭐ If you found this project insightful, please give this repo a star — it really helps!
