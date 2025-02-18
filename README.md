# Poc_ishiyaseika

kaggle コンペ詳細: https://www.kaggle.com/competitions/playground-series-s5e2

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
|P1|train,test,extraをlabel encoding，欠損値は平均で埋める|


### MLモデル
|ファイル名|説明|
|---|---|
|ML1|GBDT，Optunaでチューリング|


### result 
|ファイル名|RMSE|
|---|---|
|P1_ML1|39.12364|

### データから得た知見
|知見|ネクストアクション|
|---|---|
