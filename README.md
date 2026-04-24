# Experiment No. 19-20: Real-World and Interactive Visualization (COVID-19 Analysis)

**Name:** Vibhas Shukla  
**PRN:** 25070123164  
**Branch:** F.Y. E&TC (2025–29)  
**Batch:** A1  
**Subject:** Exploratory Data Analysis with Python  

---

## 1. Aim
The aim of this experiment is to study and implement real-world and interactive visualization techniques using Python to represent complex data in an interactive and meaningful way.

---

## 2. Objective
- To understand advanced visualization techniques used in real-world applications  
- To create interactive visualizations such as choropleth maps and analytical dashboards  
- To analyze relationships, distributions, and trends in real-world datasets  
- To improve data interpretation using tools like Plotly  
- To understand how visualization helps in decision-making and data storytelling  

---

## 3. Dataset Description
The dataset used in this experiment contains global COVID-19 data including:
- Observation date  
- Country/Region  
- Province/State  
- Confirmed cases  
- Deaths  
- Recovered cases  

The dataset consists of over 300,000 records covering multiple countries and time periods.

---

## 4. Data Preprocessing
- Converted ObservationDate into datetime format  
- Converted Confirmed, Deaths, and Recovered into integer values  
- Checked dataset structure and data types  
- Handled missing values in Province/State column  
- Replaced unknown values using the most frequent value (mode)  

---

## 5. Feature Engineering
A new column **Active Cases** was created using the formula:

Active = Confirmed - Deaths - Recovered

This helps in identifying currently infected individuals.

---

## 6. Latest Data Extraction
- Extracted the most recent date available in the dataset  
- Filtered the dataset to analyze only the latest COVID-19 statistics  
- Identified that the dataset contains data for **195 countries**

---

## 7. Country-wise Analysis
- Grouped data by Country/Region  
- Calculated total Confirmed, Deaths, Recovered, and Active cases  
- Identified top affected countries  

### Key Observation:
- USA and India are among the most affected countries  
- India recorded:
  - Confirmed: 27,894,800  
  - Deaths: 325,972  
  - Recovered: 25,454,320  
  - Active: 2,114,508  

---

## 8. World Map Visualization
A choropleth map was created to visualize global COVID-19 spread:
- Each country is colored based on confirmed cases  
- Darker shades indicate higher case counts  
- Helps in understanding global impact visually  

---

## 9. Top Countries Analysis
- Countries were sorted based on confirmed cases  
- Top affected countries include:
  - USA  
  - India  
  - Brazil  
  - France  
  - Turkey  

---

## 10. India State-wise Analysis

### Data Filtering
- Extracted data specific to India  
- Identified total number of states: **38**

### Data Cleaning
- Replaced missing and unknown state values with the most frequent state name  

### Latest State Data
- Extracted the latest available data for all Indian states  

---

## 11. Top States by Cases
- Grouped data by state  
- Sorted states based on confirmed cases  

### Key Observation:
- **Maharashtra** has the highest number of COVID-19 cases in India  
- Other highly affected states:
  - Karnataka  
  - Kerala  
  - Tamil Nadu  
  - Uttar Pradesh  

---

## 12. Key Insights
- COVID-19 dataset includes global data across 195 countries  
- India is one of the most impacted countries  
- Maharashtra is the most affected state in India  
- Data visualization helps in quickly identifying trends and patterns  
- Choropleth maps effectively represent geographical spread  

---

## 13. Conclusion
In this experiment, real-world COVID-19 data was analyzed using Python. Data preprocessing, feature engineering, and aggregation techniques were applied to extract meaningful insights.

Interactive visualization using tools like Plotly made it easier to understand global trends and patterns. The experiment demonstrated how real-world datasets can be transformed into valuable insights through proper analysis and visualization.

Overall, this experiment highlights the importance of interactive visualization in modern data analysis and decision-making.
