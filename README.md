**Running the Analysi**s
Open analysis_report.Rmd in RStudio.
Ensure that the input/process_data.csv file is in the correct directory.
Knit the R Markdown file to generate the PDF report.
**Analysis Details**
**Simulated Data Generation**
The project begins by generating a simulated dataset representing a manufacturing process. The dataset includes 1,000 hourly observations of various process variables such as temperature, pressure, pH level, production output, and quality metric.

**Statistical Process Control (SPC)**
SPC techniques, specifically x-bar charts, are used to monitor the temperature variable over time to identify any out-of-control conditions.

**Multivariate Analysis**
Principal Component Analysis (PCA) is performed to reduce the dimensionality of the dataset and uncover underlying patterns and relationships among the variables.

**Design of Experiments (DOE) Analysis**
A multivariate regression analysis is conducted to understand the effects of temperature, pressure, and pH on production output, allowing for the identification of critical factors impacting manufacturing performance.

**Advanced Data Manipulation and Visualization**
Feature engineering is applied to create new variables such as the hour of the day, day of the week, and month from the timestamp. Boxplots are used to visualize production output and quality metrics over time.

**Data Pipeline Activities**
Data intake and validation steps are performed to clean and preprocess the dataset, ensuring the integrity and reliability of the data used for analysis.
**
**Setting Best Practices for Data Analytics****
Best practices for data analytics are established, including ensuring correct data types, removing missing values, and normalizing numeric features.

**Additional Duties**
Custom tasks are performed to address specific needs, such as identifying and analyzing anomalies in the quality metric.

**Conclusion**
This project demonstrates the comprehensive application of various statistical techniques to analyze and improve manufacturing process data. The results provide valuable insights into process variability and critical factors affecting production quality and efficiency.

Authors
Sathish Reddy Gurram
