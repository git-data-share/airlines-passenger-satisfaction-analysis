
# Airlines Passenger Satisfaction Analysis

Airlines collect large volumes of passenger feedback, but this data is often unstructured and difficult to interpret. As a result, it becomes challenging to identify key drivers of satisfaction and areas that require improvement.

The objective of this project is to analyze passenger feedback data to:
- Measure overall satisfaction levels
- Identify underperforming service areas
- Understand customer behavior across different segments
- Provide actionable insights to improve passenger experience


## Overview
This Power BI dashboard provides a comprehensive analysis of airline passenger satisfaction using survey and operational data.

The dashboard is structured into four main pages:
- Passengers
- Key Metrics
- Overview
- Feedback Analysis

It enables users to explore satisfaction trends based on service quality, passenger demographics, travel behavior, and operational factors such as delays.


## Key Business Questions
- What is the overall passenger satisfaction rate?
- Which services are performing poorly?
- Which customer segments are most dissatisfied?
- How do delays impact satisfaction?
- Which travel class has the highest satisfaction?
- How do age group and travel type influence experience?


### 1. Passengers Page

![Power BI Report](https://github.com/git-data-share/airlines-passenger-satisfaction-analysis/raw/main/images/passengers.jpg)

**Purpose:**  
To analyze passenger demographics and understand how satisfaction varies across different customer segments.

**Key Insights:**
- Overall satisfaction rate is 43 percent, indicating that more than half of the passengers are not satisfied.
- Business class passengers have the highest satisfaction rate at 69 percent.
- Economy passengers have significantly lower satisfaction at 19 percent, followed by Economy Plus at 25 percent.
- Returning passengers make up 82 percent, while first-time passengers account for only 18 percent.
- Younger (under 18) and older (65+) passengers show higher dissatisfaction.
- Business travel customers are more satisfied compared to personal travel customers.

**Conclusion:**  
Customer satisfaction varies significantly by class, age group, and travel type, with economy passengers and extreme age groups being key areas of concern.


### 2. Key Metrics Page

![Power BI Report](https://github.com/git-data-share/airlines-passenger-satisfaction-analysis/raw/main/images/key.jpg)

**Purpose:**  
To evaluate operational performance and identify factors influencing satisfaction.

**Key Insights:**
- Overall satisfaction rate is 43 percent.
- Average arrival delay is 15.1 minutes and departure delay is 14.7 minutes.
- Short distance flights (less than 1,000 miles) show higher dissatisfaction.
- Even without departure delay, only 45.94 percent of passengers are satisfied.
- Highest rated services include inflight service and baggage handling (3.6 rating).
- Lowest rated services include inflight Wi-Fi (2.8) and online booking (2.9).

**Conclusion:**  
Delays impact satisfaction, but service quality plays a more critical role in determining passenger experience.


### 3. Overview Page

![Power BI Report](https://github.com/git-data-share/airlines-passenger-satisfaction-analysis/raw/main/images/overview.jpg)

**Purpose:**  
To highlight the worst-performing service areas and provide recommendations.

**Key Insights:**
- Inflight Wi-Fi, online booking, and gate location are the lowest rated services.
- Overall dissatisfaction rate is 57 percent, which is higher than the satisfaction rate.

**Recommendations:**
- Improve Wi-Fi reliability and speed
- Enhance online booking experience with better user interface
- Improve gate communication and accessibility

**Conclusion:**  
A few key service areas are responsible for a large portion of dissatisfaction and should be prioritized.


### 4. Feedback Analysis Page

![Power BI Report](https://github.com/git-data-share/airlines-passenger-satisfaction-analysis/raw/main/images/feedback.jpg)

**Purpose:**  
To analyze detailed service ratings and overall feedback distribution.

**Key Insights:**
- 29 percent of ratings fall in the low range (1–2), indicating poor experience.
- 49 percent of ratings are high (4–5), indicating satisfaction.
- Average ratings:
  - Pre-boarding: 3.14
  - In-flight: 3.34
  - Essential services: 3.37
- Inflight Wi-Fi and online booking have the highest percentage of low ratings.

**Conclusion:**  
Passenger experience is inconsistent, with a mix of highly satisfied and highly dissatisfied customers, driven mainly by specific service issues.

## Challenges Identified from Analysis
- Overall satisfaction is low (43%) compared to dissatisfaction (57%).
- Inflight Wi-Fi, online booking, and gate location are the lowest-performing services.
- Economy and Economy Plus passengers show significantly lower satisfaction than Business class.
- First-time passengers are less satisfied than returning customers.
- Under 18 and 65+ age groups have higher dissatisfaction levels.
- Short-distance flights show more dissatisfaction despite shorter travel time.
- Even without delays, satisfaction remains low, indicating service quality issues.
- Inconsistent service performance across categories affects overall passenger experience.

## Recommendations

**Business Recommendations:**
- Focus on improving low-performing services such as Wi-Fi, online booking, and gate experience
- Enhance the experience for economy class passengers
- Provide targeted improvements for first-time passengers and senior citizens
- Ensure consistency in service quality across all touchpoints

**Analytics Recommendations:**
- Track satisfaction trends over time
- Introduce Net Promoter Score (NPS) for deeper analysis
- Enable real-time feedback tracking for faster decision-making


## Conclusion
The dashboard demonstrates that passenger satisfaction is influenced more by service quality than operational delays.

Key findings include:
- Economy passengers and certain age groups are less satisfied
- A few critical services are major contributors to dissatisfaction
- Improving these areas can significantly enhance overall customer experience and loyalty
