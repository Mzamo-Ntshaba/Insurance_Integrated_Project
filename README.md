# Insurance Data Analysis Integrated Project

This project is focused on analyzing, transforming, and visualizing insurance claims data. The workflow involved cleaning raw data, performing exploratory data analysis (EDA), transforming data for visualization, and building an interactive dashboard. The primary goal is to extract actionable insights and provide a high-level overview of trends and operations in the insurance industry, specifically in Africa.

## Project Structure and Components

1. **Insurance Claims Data**:  
   The initial dataset provided in the form of a excel file (`insurance_claims.xlsx`). This raw data serves as the foundation for all subsequent processing steps.

2. **Cleaned Data**:  
   The cleaned and normalized version of the dataset, saved as `insurance_claims_cleaned.xlsx`. Cleaning steps include the removal of null values, data normalization, and creating pivot tabes for numerical analysis.

3. **Data Cleaning and Transformation**:  
   A Jupyter Notebook (`feature_engineering.ipynb`) was used to clean and transform the data. Key actions include handling missing values, performing exploratory data analysis, and preparing the data for visualization. The output of this notebook is saved as `Advanced_feature_claims_data.xlsx`, which is used as input for Looker Studio.

4. **Dashboard**:  
   An interactive dashboard created in Looker Studio. This dashboard links directly to the transformed data, allowing users to explore trends and insights. The dashboard supports filtering and customization for specific dimensions of the data. You can access it [here](https://lookerstudio.google.com/reporting/30fe56e3-9801-4527-bd00-2bd797ed470a).

5. **Project Landscape**:  
   A high-level overview of the insurance industry in Africa, detailing key challenges and opportunities. This is presented in a document titled `project_landscape.pdf`.

6. **Trello Board**:  
   A visual representation of project task management, categorized into "To Do," "Doing," and "Done." This board illustrates the project's planning and execution. A screenshot of the Trello board can be found in the trello board.png.

   

## Workflow Summary

The following steps outline the workflow followed in this project:
- **Step 1: Data Cleaning and EDA**  
   Raw data was cleaned by removing null values, normalizing columns, and calculating a five-number summary. Pivot tables were also created for aggregated views of key metrics.
- **Step 2: Data Transformation**  
   The cleaned data was further transformed using Python in the Jupyter Notebook, preparing it for advanced visualization. The output was saved as a csv 'Advanced_feature_claims.csv`).
- **Step 3: Visualization**  
   The transformed data was visualized in Looker Studio for building a fully interactive dashboard. The dashboard allows users to filter, drill down, and explore insights.
- **Step 4: Project Management**  
   A Trello board was used to track tasks and ensure timely completion. Categories included "To Do," "Doing," and "Done."

## Key Insights

1. **Industry Trends**:  
   The dashboard highlights claim patterns, high-risk areas, and performance metrics in the African insurance sector.
2. **Data Quality Improvements**:  
   Cleaning and transformation improved data accuracy and usability, enabling better decision-making.
3. **Interactive Dashboard**:  
   The Looker Studio dashboard empowers stakeholders with a user-friendly platform for exploring data-driven insights.

## Access Instructions

To explore the interactive dashboard:
1. Visit the [Looker Studio Dashboard](https://lookerstudio.google.com/reporting/30fe56e3-9801-4527-bd00-2bd797ed470a).
2. Use the filters on the dashboard to focus on specific metrics, time periods, or categories of interest.
