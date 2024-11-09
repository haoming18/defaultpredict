https://www.kaggle.com/wanghaoming17

Steps to Run the Project

1. Download the Datasets:
   - Download the raw dataset and save it to the input/amex-default-prediction directory.
   - Download the processed dataset from this link: https://www.kaggle.com/datasets/raddar/amex-data-integer-dtypes-parquet-format and save it to the input/amex-data-integer-dtypes-parquet-format directory.

2. Run fe.ipynb:
   - Execute code/fe.ipynb to generate feature files. This step might take some time.

3. Run lgb.ipynb:
   - Execute code/lgb.ipynb to train the LightGBM (LGB) model.

4. Run xgb.ipynb:
   - Execute code/xgb.ipynb to train the XGBoost (XGB) model using GPU.

5. Run fe_v2.ipynb:
   - Execute code/fe_v2.ipynb to generate version 2 feature files. This step might also take some time.

6. Run lgb_v2.ipynb:
   - Execute code/lgb_v2.ipynb to train the LightGBM v2 model.

7. Run lgb_v3.ipynb:
   - Execute code/lgb_v3.ipynb to train the LightGBM v3 model.

8. Run combine.ipynb:
   - Execute code/combine.ipynb to generate the final combined results.

9. Submit the Results:
   - Submit the file sub/submission.csv to Kaggle.

Note: The process requires 64GB of memory.
