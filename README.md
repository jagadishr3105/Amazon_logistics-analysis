# Amazon_logistics-analysis

## **Objective:**
To explore all possible logistics aspects of the given dataset and extract actionable insights using Python for supply chain optimization.

## **Key Questions Explored:**
1. What is the impact of traffic conditions on delivery times?
2. How do delivery times vary across different geographical areas?
3. How do agent attributes (age, rating) affect delivery performance?
4. What is the role of weather in delivery delays?

---

## **Data Cleaning and Preparation:**
1. Handled missing values in the `Weather` and `Agent_Rating` columns using the most frequent value and mean, respectively.
2. Verified and converted column data types to ensure accurate calculations.

---

## **Key Findings:**
1. **Delivery Time Insights:**
   - Grocery has the shortest delivery times (~26 minutes), while other categories like Apparel, Electronics, and Skincare have similar delivery times (~130 minutes).
   - Toys had slightly faster delivery times (~129 minutes).

2. **Geographical Trends:**
   - Semi-Urban areas face the longest delivery times (~238 minutes), likely due to distance and infrastructure.
   - Urban and Metropolitan areas have shorter delivery times (~109 and ~129 minutes, respectively).

3. **Traffic Impact:**
   - Traffic jams increase delivery times significantly (~147 minutes), while low traffic conditions result in optimal delivery (~101 minutes).

4. **Agent Performance:**
   - Agents aged 26-35 were the most efficient, delivering faster on average.
   - Higher agent ratings correlated with faster delivery times, emphasizing the value of experienced agents.

5. **Weather Factors:**
   - Adverse weather increases delivery times, highlighting the need for weather-adjusted planning.

---

## **Recommendations:**
1. Optimize routing for Semi-Urban areas and during peak traffic conditions to reduce delays.
2. Invest in agent training and maintain a pool of well-rated agents for consistent performance.
3. Use predictive weather data to plan and allocate resources during adverse conditions.
4. Prioritize deliveries in high-density areas (e.g., Urban and Metropolitan) for faster turnaround.

---

## **Tools Used:**
- Python libraries: pandas, matplotlib, seaborn
- Key methods: Correlation analysis, heatmaps

---

This project demonstrates the importance of data-driven decisions in logistics and supply chain management. The findings and recommendations can significantly optimize delivery times and customer satisfaction.

