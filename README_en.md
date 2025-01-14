# Academic Dropout Analysis

This repository contains a project focused on analyzing and predicting academic dropout in a higher education institution. The goal is to identify students with a higher likelihood of dropping out, enabling preventive actions to increase academic engagement.

## Context

Academic dropout is one of the biggest challenges faced by educational institutions. It has been identified that lack of engagement and non-participation in optional mid-semester evaluations are strongly related to student dropout. This project aims to analyze academic data and develop a Machine Learning model to predict dropout probabilities based on students' behavior in different subjects.

## Data Used

The data provided by the institution includes:

- **Students and Subjects:** Information on students' enrollment in specific subjects.
- **Digital Content Access:** Logs of access to study materials.
- **Completed Exams:** Records of exams completed by students.

⚠️ **Note:** Due to privacy concerns, the original data files are not included in this repository. Only the notebook with the solution is provided.

## Developed Solution

The project follows the steps below:

1. **Data Reading:** Loading raw tables for initial exploration.
2. **Exploratory Data Analysis (EDA):** Visualizations and descriptive statistics to understand data patterns. For example:
   - Most students who dropped out did not take mid-semester exams.
   - The average access to digital content was significantly lower among students who dropped out.
3. **Feature Creation:** Transformation and aggregation of data to create relevant variables for the model.
4. **Table Merging:** Integration of information into a single table per student-subject.
5. **Preprocessing:** Normalization and preparation of data for Machine Learning.
6. **Data Splitting:** Division into training and test sets.
7. **Modeling:** Algorithm selection, model training, and metric definition.
8. **Model Evaluation:** Analysis of performance and interpretation of results.

## Results

- **Performance Metric:** The model achieved an accuracy of 87% on the test set.
- **Key Insights:**
  - The absence of mid-semester evaluations is a strong indicator of dropout.
  - Students with lower engagement in digital content are more likely to drop out.

Relevant graphs and statistics are presented in the notebook, highlighting identified patterns.

## Tools Used

- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## How to Use

1. Clone this repository:
   ```bash
   https://github.com/williamvolpato/analise-evasao-alunos
   ```
2. Open the `.ipynb` file in your preferred tool (such as Jupyter Notebook or Google Colab).
3. Follow the instructions in the notebook to explore and understand the solution.

## License

This project is available solely for educational and demonstration purposes. Data and results are fictional, created to exemplify a technical solution.

Feel free to contribute with improvements or suggestions!
