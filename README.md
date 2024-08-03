# MSA 2024 Phase 2 Project

This repository contains the submissions for the MSA 2024 Phase 2 project, which involves data analysis, preprocessing, and model development for various datasets. The project is divided into three parts, each focusing on different aspects of data science and machine learning.

## Project Structure

- **Part 1: Data Analysis and Visualization**
- **Part 2: Model Development and Tuning**
- **Part 3: Neural Network Implementation and Evaluation**

## Part 1: Data Analysis and Visualization

### Exploratory Data Analysis (EDA)

The initial phase of the analysis focuses on understanding the dataset by conducting an exploratory data analysis (EDA). The dataset comprises features, sales, and store information from a retail chain. Key steps include loading the datasets and examining their structure and summary statistics. This involves displaying the first few records, calculating statistical measures such as mean, standard deviation, minimum, and maximum values, and understanding data types and non-null counts. The primary goal is to get an initial understanding of the dataset's distribution and characteristics.

### Preprocessing Steps

The preprocessing phase involves transforming the data to make it suitable for modeling. This includes creating features and target variables, where the target is the weekly sales, and the features include store, department, date, and holiday indicators. The date field is converted into a numerical format to facilitate analysis. The dataset is then split into training and testing sets using a 70-30 split.

### Power BI Analysis

In addition to Python-based EDA and preprocessing, Power BI was utilized to create interactive visualizations and dashboards. Power BI provided a user-friendly interface to visualize sales trends, seasonal patterns, and store performance. Key visualizations include line charts showing weekly sales trends, bar charts comparing sales across different stores and departments, and heatmaps to identify peak sales periods.

## Part 2: Model Development and Tuning

### Exploratory Data Analysis (EDA)

Continuing from Part 1, this notebook delves deeper into the dataset by conducting further exploratory data analysis. It involves examining relationships between different variables and the target variable, weekly sales. This step includes visualizing the data through plots and graphs to uncover patterns and correlations.

### Preprocessing Steps

Preprocessing in this phase involves feature engineering and data transformation. New features are created to enhance model performance, such as encoding categorical variables, handling missing values, and scaling numerical features. The data is prepared for modeling by splitting it into features (X) and target (y).

### Bonus: Model Tuning and Other Algorithms

Additionally, model tuning was performed using GridSearchCV to find the best hyperparameters for the Linear Regression model. Other algorithms, including Decision Tree, Random Forest, and Gradient Boosting, were also evaluated for comparison. The tuning process involved setting a parameter grid and using cross-validation to find the optimal parameters, resulting in improved model performance.

## Part 3: Neural Network Implementation and Evaluation

### Exploratory Data Analysis (EDA)

In this notebook, the focus shifts to classification tasks using neural networks. The dataset used is CIFAR-10, a standard dataset for image classification. The EDA involves loading and exploring the CIFAR-10 dataset, understanding its structure, and visualizing sample images to get an idea of the data distribution and class balance.

### Preprocessing Steps

Preprocessing for neural network models includes transforming the image data into a suitable format for model training. This involves normalizing the pixel values, converting labels to categorical format using one-hot encoding, and splitting the dataset into training and testing sets.

### Model Implementation and Accuracy Evaluation

A simple Multi-Layer Perceptron (MLP) model is built using TensorFlow and Keras. The model is compiled with the Adam optimizer and sparse categorical cross-entropy loss function. Training involves running the model for a fixed number of epochs while monitoring validation accuracy. After training, the model's performance is evaluated on the test set to ensure it generalizes well. The results, including accuracy, are saved to `submission.csv` for further evaluation.

## Files and Directories

- `part1-submission.ipynb`: Jupyter notebook for Part 1.
- `part2-submission.ipynb`: Jupyter notebook for Part 2.
- `part3-submission.ipynb`: Jupyter notebook for Part 3.
- `msa phase2.pbit`: Power BI template for Part 1.
- `submission.csv`: Results of the neural network model in Part 3.

## How to Run

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/msa-2024-phase2.git
    ```

2. Navigate to the project directory:
    ```sh
    cd msa-2024-phase2
    ```

3. Open the Jupyter notebooks using Jupyter Lab or Jupyter Notebook:
    ```sh
    jupyter lab
    ```
    or
    ```sh
    jupyter notebook
    ```

4. Follow the steps in each notebook to reproduce the analysis and results.

## Conclusion

This project demonstrates various aspects of data analysis, preprocessing, and model development using both traditional machine learning techniques and neural networks. The use of Power BI for visualization provides additional insights into the data, making the analysis more comprehensive and interactive.

Feel free to explore the notebooks and the Power BI report to gain a deeper understanding of the project.

---

Feel free to edit this README.md file to suit your specific needs or repository structure. If you have any further questions or need additional modifications, let me know!
