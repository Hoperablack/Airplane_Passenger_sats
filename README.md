# Airplane_Passenger_sats
Airplane Passenger Satisfaction 
Airline Passenger Satisfaction Analysis

Overview

This project analyzes airline passenger satisfaction data to uncover key insights into factors influencing customer experience. Using Pandas, Seaborn, and Matplotlib, we explore trends related to satisfaction levels, age influence, class differences, and feature correlations.

Dataset

The dataset contains passenger details, flight-related metrics, and customer service ratings. Key columns include:

Satisfaction (Satisfied / Neutral or Dissatisfied)

Age

Travel Class (Business, Economy, Economy Plus)

Seat Comfort, Leg Room Service, In-flight Entertainment

Departure & Arrival Delays

Check-in, Online Boarding, Baggage Handling

Key Insights

1️⃣ Passenger Satisfaction Distribution

More passengers fall into the "Neutral or Dissatisfied" category than the "Satisfied" category.

This suggests the need for airlines to improve service quality and passenger experience.

2️⃣ Satisfaction by Travel Class

Business Class passengers have the highest satisfaction levels, with more satisfied travelers than dissatisfied ones.

Economy Class passengers show significantly more dissatisfaction, indicating potential service or comfort issues.

Economy Plus has the lowest passenger count but still shows a higher number of dissatisfied travelers.

3️⃣ Correlation Analysis (Heatmap)

Departure Delay and Arrival Delay are highly correlated (0.97) – delays at departure significantly impact arrival times.

Seat Comfort, Leg Room Service, and Cleanliness are key factors positively influencing satisfaction.

Baggage Handling, Check-in Service, and Online Boarding are moderately correlated, suggesting ground services play a role in customer experience.

Visualizations

The analysis includes the following plots:

Countplot: Passenger satisfaction distribution.

Boxplot: Age influence on satisfaction.

Barplot: Satisfaction by travel class.

Heatmap: Correlation between numerical features.

Technologies Used

Python

Pandas

Seaborn

Matplotlib

Google Colab

How to Run the Analysis

Clone the repository:

git clone <repo-url>

Open the Jupyter Notebook or Google Colab.

Install necessary libraries (if not already installed):

pip install pandas matplotlib seaborn

Load the dataset and run the analysis.

Conclusion

The findings highlight the importance of improving Economy Class experience and reducing flight delays to enhance passenger satisfaction. Airlines can focus on improving seat comfort, in-flight services, and baggage handling to boost customer experience.

Repository Structure

├── data
│   ├── airline_passenger_satisfaction.csv
├── analysis
│   ├── airline_satisfaction_analysis.ipynb
├── images
│   ├── satisfaction_distribution.png
│   ├── class_satisfaction.png
│   ├── correlation_heatmap.png
├── README.md
