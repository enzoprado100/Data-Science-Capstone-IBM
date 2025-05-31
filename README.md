# Data-Science-Capstone-IBM
IBM Applied Data Science Capstone and Course Projects
This project represents the culminating (10th) course of the IBM Data Science Professional Certificate specialization. It integrates and applies all key concepts and skills acquired throughout the program in the form of a comprehensive, real-world data science project.

📄 Project Background
SpaceX has revolutionized commercial spaceflight by drastically reducing launch costs, primarily through the reusability of its Falcon 9 rocket's first stage. While a typical Falcon 9 launch costs $62 million, competitors charge more than $165 million per launch. Accurately predicting whether the first stage will land successfully is crucial for estimating mission costs. This project leverages publicly available data and machine learning to forecast the likelihood of first-stage recovery, offering insights into SpaceX’s operational efficiency.

📄 Research Questions

How do features like payload mass, launch site, flight frequency, and orbital parameters influence first-stage landing outcomes?

Is there an observable trend of increasing landing success rates over time?

Which classification algorithm is most effective for predicting landing success?

📄 Methodology

Data Collection: Acquired launch data using SpaceX’s REST API and web scraping Wikipedia entries.

Data Wrangling: Filtered and cleaned data, addressed missing values, and applied One-Hot Encoding to prepare the dataset for binary classification tasks.

Exploratory Data Analysis (EDA): Conducted using SQL queries and data visualizations.

Interactive Visualization: Developed with Folium and Plotly Dash to map and explore launch data interactively.

Predictive Modeling: Built, tuned, and evaluated classification models (SVM, Decision Tree, KNN) to determine the most accurate predictor of first-stage landing success.
