Spatiotemporal Characteristics and Driving Factors of Soil Erosion in the Kangding River Basin (Southwest China) Based on the RUSLE Model
Author: Yuqi Guan
This repository contains the code used in the paper:
Spatiotemporal Characteristics and Driving Factors of Soil Erosion in the Kangding River Basin (Southwest China) Based on the RUSLE Model.
We applied CatBoost, XGBoost, and LightGBM to analyze the spatiotemporal variations of soil erosion and its driving factors. SHAP values were used to interpret feature importance across multiple time periods.
DATE：
Input data: CSV file containing Year, driving factors, and target variable (A).
Due to licensing restrictions, raw data are not included here.
Researchers can replace the CSV file path in the script with their own dataset.
How to Run：
1.Install dependencies:pip install pandas shap matplotlib scikit-learn catboost xgboost lightgbm
2.Place your dataset (e.g., date.csv) in a local folder.
3.Update the file path in the script:df = pd.read_csv(r"your_path/40086.csv")
4.Run the script:python shap_models.py
5.utput:SHAP summary plots (.png)
SHAP mean values (.xlsx)
Saved under Desktop/shap数据/[ModelName]/
License：This code is released under the MIT License. You are free to use and modify it with proper citation.
Citation：If you use this code, please cite the following paper:
Yuqi Guan. Spatiotemporal Characteristics and Driving Factors of Soil Erosion in the Kangding River Basin (Southwest China) Based on the RUSLE Model.
