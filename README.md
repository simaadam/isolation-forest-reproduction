# Isolation Forest

Data Wrangling assignment 2: reproducing part of the main experiment in Liu, Ting and Zhou (2008), *Isolation Forest*.

The notebook compares scikit-learn's Isolation Forest and LOF on public copies of 12 datasets. It includes the results, parameter settings and data sources. ORCA, Random Forest and the additional experiments are not reproduced.

Open `Isolation_Forest.ipynb` in Google Colab and run the cells in order from the top. The data downloads automatically. The last cell saves the three CSV tables. If Colab reconnects to a new session, run the earlier cells again before saving.

The CSV files contain the dataset overview, AUC comparison and runtime comparison. Times depend on the machine and exclude downloading the data.

Paper: Liu, F. T., Ting, K. M., and Zhou, Z.-H. (2008). Isolation Forest. IEEE International Conference on Data Mining, pp. 413–422. https://doi.org/10.1109/ICDM.2008.17
