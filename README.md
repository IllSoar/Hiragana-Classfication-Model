# < ひらがなを判別する分類モデルを開発 >
#
## 作成したモデルの性能は下記の通りです。
### LOSS : 0.155, ACCURACY : 0.959
### 安定性、正解率両方とも悪くない数値を表していますが、
### 学習させた画像と大きさが異なる画像を使ったpredict及びevaluateの際は
### 汎化性能が低いだろうと考えています。
# -------------------------------------------------------
# <strong>開発環境</strong>
### Jupyter Notebook, Windows
# -----------------------------------------------------
# <strong>ライブラリ</strong>
### os, random, math
### Numpy, Matplotlib, PIL
### Scikit-Learn : train_test_split, LabelEncoder, confusion_matrix, classification_report
### Tensorflow : tensorflow, Sequential, Dense, Conv2D, MaxPooling2D, Input, Flatten, Dropout, BatchNormalization
### Seaborn
#-----------------------------------------------------
# <strong>利用したデータセット</strong>
### hiragana.zip
#-----------------------------------------------------
# <strong>モデルの作成</strong>
### aip2_任意提出課題_1_model_25ca0224.ipynb
# -----------------------------------------------------
# <strong>モデルの再利用及びテスト</strong>
### aip2_任意提出課題_2_use_25ca0224.ipynb
# -----------------------------------------------------
# <strong>作成したモデル</strong>
### hiragana_classification_model_25ca0224.h5
# -----------------------------------------------------
