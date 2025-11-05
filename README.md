# Data Analyst Job Skills Analysis (Text/NLP)
### Project Overview
This project analyzes a dataset of Data Analyst job postings to identify and quantify the most in-demand technical skills. By applying Natural Language Processing (NLP) techniques to job descriptions, this analysis aims to provide a clear, data-driven insight into the current job market landscape for data analysts.

The core of the project involves parsing text data, searching for a predefined list of relevant skills (such as Python, R, SQL, Tableau, etc.), and visualizing the frequency of these skills.

### Files in This Repository
- DataAnalyst.csv: The raw dataset containing job posting information, including titles, locations, and full job descriptions.

- Job Skills Project (Text,NLP).ipynb: A Jupyter Notebook containing all the Python code used for the analysis. This includes data loading, text cleaning, skill extraction, and data visualization.

- job_skills_chart.png: The final output image; a bar chart visualizing the frequency of the most in-demand skills.

### Methodology
The analysis was conducted using Python within a Jupyter Notebook. The key steps are as follows:

1. Data Loading: The DataAnalyst.csv file is loaded into a pandas DataFrame.

2. Text Preprocessing: The "Job Description" column is cleaned to standardize the text for analysis (e.g., converting to lowercase, removing punctuation).

3. Skill Extraction: A predefined dictionary of key technical skills and their common variations is used to search the processed text. The frequency of each skill is counted across all job postings.

4. Data Visualization: The aggregated skill counts are plotted using matplotlib to create a bar chart, providing a clear visual representation of skill demand.

### Results
The analysis identified the frequency of various technical skills mentioned in the job postings. The results are saved in the job_skills_chart.png file, which ranks the skills from most to least in-demand.

### How to Run This Project
To replicate this analysis, you will need a Python environment with Jupyter Notebook.

1. Clone or download this repository.

2. Ensure you have the required Python libraries installed, primarily pandas and matplotlib.
- %pip install matplotlib
- % pip install pandas 
3. Place the DataAnalyst.csv file in the same directory as the Jupyter Notebook.

4. Open and run the cells in Job Skills Project (Text,NLP).ipynb.

5. The script will process the dataset and generate the job_skills_chart.png file in the same directory.
