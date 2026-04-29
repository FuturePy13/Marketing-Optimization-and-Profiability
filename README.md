## Business Problem
The company is investing in multiple marketing channels but lacks visibility into acquisition efficiency and customer profiability. High marketing spend combined with uneven performance across channels suggest potential inefficiences in budget allocation. The goal of this analysis is to evaluate key unit economics metrics(CAC, LTV, ROMI) to identify which channels drive profiability and optimize marketing investment.

## Data Overview
The dataset includes:
- User activity (sessions, visits).
- Orders and revenue
- Marketing spend by acquisition source
This allows analysis of customer behavior, conversion patterns and profiability across marketing channels.

## Analysis
This analysis was conducted using SQL and Python, focusing on:
 - User activity trends
 - Conversion Behavior
 - Revenue per user and LifeTime Value (LTV)
 - Customer Acquisiton Cost (CAC) by channel
 - Return of Marketing Investment (ROMI)

## Key Insights
- The business is currently unprofitable, with a total profit of approximately -7M, driven by marketing costs exceeding generated revenue. 
- Performance varies significantly across acquisition sources, highlighting inefficent budget allocation.
- Source 1 is the most efficent and profitable channel, with the highest ROAS and strong positive profit contribution, making it the top-performing source.
- Source 2,4 and 5 show stable and positive performance, with healthy profiability and acceptable efficiency levels.
- Source 3 is the main driver of losses, with  ROAS below 1 and significantly negative profit, indicating clear value destruction.
- Conversion Rate differs across sources, suggestions variations in traffic quality and funnel effectiveness.
- Some sources contribute minimal impact (low volumne and low profit), indicating limited strategic value.

## Business Recomendations
- Rellocate marketing budget from underperforming sources (especially source 3), to high-performing and efficient channels like 1, 2, 4 and 5.
- Investigate the root causes of poor perfomance in Source 3 (Low Conversion Rate, High Acquisition Cost, Low-quality Traffic).
- Scale channels with strong ROAS and consistenly profiability to maximize return of investment.
- Optimize mid-performing sources to improve efficiency, focusing on increasing conversion rate and reducing Acquisition costs.
- Consider reducing or eliminating low-impact sources that do not significantly contribute to revenue or growth.
- Continously monitor conversion rates and funnel performance to identify opportunities for improving traffic quality and overall eficiency.

## Expected Impact 
- Potential reduction in wasted marketing spend by 20-30%
- Improved ROI through budget reallocation toward high-perfoming channels.
- Increased overall marketing efficiency and profiability.
- Better alignment between customer acquisition and long-term value (LTV)

## Dashboard & Visualizations
Key metrics were visualized to support decision-making:
- CAC by channel  
- LTV and revenue per user  
- ROMI by source  
- User activity trends
<img width="1310" height="723" alt="image" src="https://github.com/user-attachments/assets/be7fc22c-d2b5-48d4-a88a-1d3e84b13340" />


## Tools used
- SQL (Data extraction and aggregation)
- Python (Pandas, Matplotlib)
- Data Visualization (Power BI)
