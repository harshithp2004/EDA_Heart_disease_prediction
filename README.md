# EDA_Heart_disease_prediction
## This exploratory data analysis (EDA) project aims to delve into a comprehensive dataset containing various medical attributes and outcomes related to heart health. Through rigorous examination and visualization of the dataset, we seek to uncover valuable insights, patterns, and correlations that can aid in developing robust predictive models.
## Columns:
●Age: Represents the age of the patient in years.
●Sex: Indicates the gender of the patient. Typically encoded as 0 for female and 1 for male.
●CP (Chest Pain Type): Describes the type of chest pain experienced by the patient. It's often categorized into four types: typical angina, atypical angina, non-anginal pain, and asymptomatic.
●Trestbps (Resting Blood Pressure): Refers to the resting blood pressure of the patient measured in mm Hg (millimeters of mercury) upon admission to the hospital.
●Chol (Serum Cholesterol): Represents the serum cholesterol level of the patient measured in mg/dl (milligrams per deciliter).
●Fbs (Fasting Blood Sugar): Indicates whether the patient's fasting blood sugar level is greater than 120 mg/dl (1 = true; 0 = false).
●Restecg (Resting Electrocardiographic Results): Describes the resting electrocardiographic results, typically categorized into normal, having ST-T wave abnormality, or showing probable or definite left ventricular hypertrophy.
●Thalach (Maximum Heart Rate Achieved): Represents the maximum heart rate achieved by the patient during exercise.
Exang (Exercise-Induced Angina): Indicates whether the patient experienced exercise-induced angina (1 = yes; 0 = no).
●Oldpeak (ST Depression Induced by Exercise Relative to Rest): Reflects the ST depression induced by exercise relative to rest.
●Slope (Slope of the Peak Exercise ST Segment): Describes the slope of the peak exercise ST segment, typically categorized as upsloping, flat, or downsloping.
●Ca (Number of Major Vessels Colored by Fluoroscopy): Represents the number of major vessels colored by fluoroscopy (0-3).
●Thal (Thalassemia): Describes a blood disorder; in this context, it indicates the presence of thalassemia (a type of anemia) and is categorized into three types: normal, fixed defect, or reversible defect.
●Target: Represents the presence of heart disease (1 = presence; 0 = absence). This column serves as the target variable for predictive modeling, where the objective is to predict the likelihood of heart disease based on the other attributes.

## Steps involved in EDA:
Raw data -> Structured data -> Data Preprocessing -> EDA -> Insights,Graphs
## Univariate Analysis:
1.What do the line plots suggest about the trends in maximum heart rate achieved and cholesterol levels across the dataset? How might the observed variability indicate fluctuations in heart health metrics?
Conclusion:
The line plots display trends in maximum heart rate achieved and cholesterol levels over the dataset index. Variability is evident in both variables, indicating potential fluctuations in individuals' heart health metrics

2.What differences or similarities are evident in the distribution of 'restecg' values between the first and last 50 data points, as shown by the boxplots? How could these results inform our understanding of electrocardiographic outcomes over the dataset?
 Conclusion:
The boxplots illustrate the distribution of 'restecg' values among the first and last 50 data points, highlighting potential differences or similarities in electrocardiographic results between the initial and final portions of the dataset.

3.What does the age distribution histogram reveal about the demographics within the dataset? How might the bell-shaped distribution and peak in a specific age range provide insights into potential age-related trends?
Conclusion:The histogram illustrates the distribution of ages within the dataset, indicating a predominantly bell-shaped distribution with a peak around a certain age range. This visualization provides insight into the age demographics represented in the data and may inform further analysis regarding age-related trends or associations with other variables.

## Bivariate Analysis:
1.How does the scatter plot reflect the relationship between age and serum cholesterol levels? What conclusions can be drawn about the variability in cholesterol levels across different age groups?
Conclusion:The scatter plot illustrates the relationship between age and serum cholesterol levels. While there appears to be a tendency for cholesterol levels to increase with age, the scatterplot also reveals considerable variability in cholesterol levels across different age groups, suggesting other influencing factors beyond age alone."

2.What does the violin plot suggest about the distribution of maximum heart rate achieved between genders? How do the patterns differ, and what might this indicate about heart rate variability among males and females?
Conclusion:violin plot demonstrates the distribution of maximum heart rate achieved between genders, showcasing potential differences in heart rate patterns. While both genders exhibit similar median heart rates, males display slightly wider variability in maximum heart rates compared to females.

3.How does the bar plot represent the distribution of chest pain types among individuals with and without heart disease? What insights can be drawn from the differences in chest pain type frequencies between the two groups?
Conclusion:The bar plot depicts the distribution of chest pain types among individuals with and without heart disease. Chest pain type 0 appears to be the most prevalent among both groups, with a notably higher frequency observed in individuals without heart disease. Chest pain type 2 shows a relatively higher frequency among individuals with heart disease compared to those without.”

What does the box plot reveal about the distribution of ages between genders? How do the interquartile ranges and medians for females and males compare, and what conclusions can be drawn from this comparison?
Conclusion:The box plot illustrates the distribution of ages between genders, revealing potential differences in age distributions among females and males. While both genders exhibit similar median ages, the interquartile range for males appears slightly wider than that for females

## Multivariate Analysis:
1.How does the pairplot illustrate the relationships between age, cholesterol, maximum heart rate, and heart disease? What insights can be derived from the scatter plots and diagonal KDE plots regarding potential correlations and patterns?
Conclusion:pairplot visually represents pairwise relationships among age, cholesterol, maximum heart rate achieved, and the presence of heart disease. The diagonal KDE plots show the distributions of each variable, while scatter plots reveal potential associations between them, aiding in the exploration of correlations and patterns within the dataset."

2.What does the heatmap of the correlation matrix indicate about the relationships between age, cholesterol, maximum heart rate, and resting blood pressure? What key positive and negative correlations are revealed, and how might they inform further analysis?
Conclusion:The heatmap displays the correlation matrix of selected variables, revealing the pairwise correlations between age, cholesterol, maximum heart rate achieved, and resting blood pressure. Positive correlations exist between age and resting blood pressure, as well as between age and cholesterol, while age shows a negative correlation with maximum heart rate achieved

## Final Conclusion:
●We identified key demographic factors such as age and gender that may influence the likelihood of heart disease, with older age groups and males showing higher prevalence.
●Examination of clinical indicators including resting blood pressure, serum cholesterol levels, and maximum heart rate achieved during exercise provided insights into potential risk factors associated with cardiovascular health.
●Analysis of symptoms such as chest pain type and exercise-induced angina shed light on the diverse manifestations of heart disease and their diagnostic significance.
●Exploration of diagnostic tests such as resting electrocardiographic results and the number of major vessels colored by fluoroscopy highlighted important markers for assessing cardiac function and identifying potential abnormalities.


