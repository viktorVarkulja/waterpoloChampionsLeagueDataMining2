# Supervised Machine Learning Project on Water Polo Champions League Data  

This project applies principles of supervised machine learning to analyze data from the **2023/2024 LEN Water Polo Champions League** group stage. The analysis focuses on training and testing a Decision Tree algorithm to derive insights and predictions from the collected data.  

## Overview  

The project utilizes **Python** in a Jupyter Notebook environment, leveraging key libraries such as:  
- **Selenium**: For automated data collection from the LEN Champions League website.  
- **import_ipynb**: To modularize and import Jupyter Notebooks into the main notebook.  
- **Pandas**: For data manipulation and cleaning.  
- **scikit-learn**: For implementing the machine learning algorithm.  
- **matplotlib**: For data visualization.  

### Data Source  
The dataset was obtained using Selenium to scrape data from the official LEN Champions League website. It includes game results and statistics from the group stage of the 2023/2024 season. The Final Four data was excluded as the matches were not played at the time of analysis.  

### Workflow  

1. **Data Collection**:  
   - Automated the scraping process with Selenium.  
   - Saved the raw data in a `.csv` file.  

2. **Data Cleaning**:  
   - Cleaned and processed the dataset to ensure consistency and accuracy.  
   - Performed further refinement during analysis.  

3. **Algorithm Training and Testing**:  
   - Used a Decision Tree algorithm to analyze the data.  
   - Experimented with various parameters to optimize performance.  

4. **Notebook Modularization**:  
   - Leveraged `import_ipynb` to import helper notebooks into the main file for a cleaner workflow.  
   - Centralized execution within the `Main.ipynb` file.  

5. **Visualization**:  
   - Created visualizations of the Decision Tree and other insights derived from the data.  

## Results  

The project provides:  
- **Tables**: Showing the processed data used for training and testing.  
- **Diagrams**: Highlighting the performance of the Decision Tree algorithm.  
- **Explanations**: Detailing how parameters influence predictions and the importance of using clean, relevant data for training.  

## Key Learnings  

- **Decision Tree Analysis**: An in-depth explanation of how the algorithm functions and processes the given data.  
- **Importance of Data Quality**: Insights into how data cleaning impacts predictions.  
- **Challenges and Solutions**: Documentation of issues faced during the project and the solutions implemented to address them.  

## Getting Started  

1. Clone this repository:  
   ```bash  
   git clone https://github.com/your-username/water-polo-ml.git  
   ```
2. Install required Python libraries:
  ```bash
  pip install selenium pandas scikit-learn matplotlib import-ipynb  
  ```
3. Run the `Main.ipynb` notebook to execute the project workflow:
  ```bash
  jupyter notebook Main.ipynb  
  ```
