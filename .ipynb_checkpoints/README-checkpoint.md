# Day Type Identification of Algerian Electricity Load

**Introduction:**

This Jupyter notebook explores the identification of different day types based on electricity load patterns in an Algerian city. We will analyze a dataset containing hourly recordings of Maximum Power Demand (PMA) and Temperature for two years, from January 1st, 2016, to December 31st, 2017. By applying data mining techniques, we aim to:

* **Preprocess and explore the data:**
    * Analyze descriptive statistics and visualize trends in PMA and Temperature.
    * Extract additional features from the date information, including day of week, week of year, month, and holiday identification.
* **Identify day types:**
    * Implement and compare clustering algorithms, such as K-means and Hierarchical clustering, to group days based on their similarity in PMA and Temperature patterns.
    * Evaluate the performance of each algorithm using metrics like silhouette score and Calinski-Harabasz index.
* **Analyze and interpret the results:**
    * Characterize the identified day types based on their PMA and Temperature distributions.
    * Discuss potential implications and applications of the findings for electricity load forecasting and grid management.

**Data Source:**

The dataset used in this analysis is stored in a file named `pma.xlsx`. It contains three columns:

* `time`: Date and time (including hour)
* `pma`: Maximum Power Demand (MW)
* `tmp`: Temperature (°C)

**Software and Tools:**

This project will utilize Python libraries such as:

* `pandas` for data manipulation and analysis
* `numpy` for scientific computing
* `matplotlib` and `seaborn` for data visualization
* `scikit-learn` for machine learning and clustering algorithms

