# DLBDSMLUSL01
# Machine Learning – Unsupervised Learning and Feature Engineering

## Task 1: Mental Health in Technology-related Jobs

### Overview
This project analyzes the Kaggle dataset on mental health in the tech industry to support HR teams in addressing workplace challenges. By cleaning data, reducing dimensions, and clustering participants, it provides actionable insights for targeted mental health programs.

### Dataset
This dataset contains responses from the OSMI Mental Health in Tech Survey conducted in 2016. The survey measures attitudes towards mental health in tech workplaces and examines the frequency of mental health disorders among tech workers.

Key features include:
- **Survey Responses**: Questions related to workplace environment and mental health.
- **Demographic Information**: Age, gender, and other relevant personal attributes.
- **Workplace Support**: Details on whether employers offer mental health resources.
- **Mental Health Conditions**: Information on diagnosed mental health disorders and treatment.

The dataset contains 63 columns, categorized as follows:
- **String**: 54 columns
- **Integer**: 7 columns
- **Boolean**: 2 columns

The dataset is publicly available on Kaggle and can be accessed using the following link:  
[OSMI Mental Health in Tech Survey 2016](https://www.kaggle.com/datasets/osmi/mental-health-in-tech-2016)

### Project Goals
1. **Data Cleaning**: Prepare the dataset by handling missing values, converting columns to appropriate types, and ensuring it is ready for analysis.
2. **Feature Engineering**: Extract meaningful features and preprocess data for analysis.
3. **Dimensionality Reduction**: Use UMAP for reducing high-dimensional data into fewer dimensions for visualization and clustering.
4. **Clustering**: Apply Gaussian Mixture Model (GMM) to identify patterns and group respondents into clusters.
5. **Evaluation and Insights**: Analyze the identified clusters to provide actionable insights for HR teams to develop targeted mental health programs.

### Model
#### Dimensionality Reduction
- **Technique**: UMAP (Uniform Manifold Approximation and Projection)
- **Purpose**: Non-linear dimensionality reduction for effective visualization of high-dimensional data.

#### Clustering Algorithm
- **Model**: Gaussian Mixture Model (GMM)
- **Best Number of Clusters (K)**: 3
- **Evaluation Metric**: Silhouette Score
- **Best Silhouette Score**: 0.8427

### Results and Insights
- Three distinct clusters were identified, representing unique mental health profiles within the tech industry.
- Insights from the clustering process were used to provide HR teams with recommendations for designing targeted mental health initiatives tailored to each group.

### Copyright Information
The dataset used in this project is publicly available on Kaggle and is provided by OSMI (Open Sourcing Mental Illness). The dataset is intended for educational and research purposes.

For more information, visit the [Kaggle Dataset Page](https://www.kaggle.com/datasets/osmi/mental-health-in-tech-2016).


### Requirements  
To run this project successfully, you will need the following dependencies. These libraries are essential for data preprocessing, visualization, dimensionality reduction, and clustering:  

- **`pandas`**: For data manipulation and analysis, especially when working with tabular data.  
- **`numpy`**: Used for numerical computations and efficient handling of arrays.  
- **`matplotlib`**: A core library for creating static, animated, and interactive visualizations.  
- **`seaborn`**: Built on matplotlib, this library enhances data visualization with aesthetically pleasing plots.  
- **`scikit-learn`**: A machine learning library used for clustering, dimensionality reduction, scaling, and evaluation.  
- **`umap-learn`**: A specialized library for non-linear dimensionality reduction using the UMAP algorithm.  

You can install all the required dependencies using the following command:  

```bash
pip install pandas numpy matplotlib seaborn scikit-learn umap-learn

```

### How to Run
1. Download the dataset from Kaggle using the link provided.
2. Set up your environment by installing the required dependencies.
3. Open the project notebook in Google Colab or your local Python environment.
4. Follow the sections in the notebook to clean the dataset, perform dimensionality reduction, and train the clustering model.
5. Visualize and interpret the results to gain insights.

---
For additional details, refer to the [notebook](#) or contact the author.
negin.hezarjaribi@iu-study.org
