# Backpack Prediction Challenge

kaggle コンペ詳細: https://www.kaggle.com/competitions/playground-series-s5e2

目的: Predict the price of backpacks given various attributes.

評価指標: RMSE = \sqrt{\frac{1}{N} \sum_{i=1}^{N} (y_i - \hat{y}_i)^2}

### ディレクトリ構成
```
|-- EDA
|-- ML
|-- preprocess
|-- preprocess_results
|-- model
|-- model_results
|-- .gitignore
|-- README.md
```

|ディレクトリ名|説明|
|---|---|
|EDA|
|pre_process|特徴量を決定する処理|
|pre_process_result|pre_processの結果を格納|
|model|modelを格納|
|model_results|modelの結果を格納|

### pre_process
|ファイル名|説明|
|---|---|
|P1|train,testをlabel encoding，欠損値は平均で埋める|
|P2|train,test,extra_dataをlabel encoding，欠損値は平均で埋める|


### MLモデル
|ファイル名|説明|
|---|---|
|ML1|GBDT，Optunaでチューリング|


### result 
|ファイル名|RMSE|
|---|---|
|P1_ML1|39.12364|

### memo

