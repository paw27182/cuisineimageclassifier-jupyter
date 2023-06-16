# cuisine-image-classifier

# 1. What you can do

* 写真イメージの分類器を生成し，この分類器を用いて写真イメージを分類できます<br>
  To create an image-classifier model, and predict images by the model.
* TensorFlow CNNを使ったモデルの学習・予測の仕方の例を学べます<br>
  To learn an example how to create machine learning models using TensorFlow CNN.

<br>

<img src="cuisineimageclassifier.png">

<br>

# 2. How to use

* Create a model
  * Execute Jupyter notebook : **_2_train.ipynb**<br>
  （This notebook executes **_1_setup_dataset.ipynb** in its first part.)

<br>

* Predict image(s)
  * Execute Jupyter notebook : **_3_predict.ipynb**

<br>

* Prepare input dataset
  * Execute Jupyter notebook : **_1_setup_dataset.ipynb**

<br>

# 3. System
* OS: Windows 10, Ubuntu 20.04.6 LTS<br>
* Python 3.10.11<br>
* Python Libraries: matplotlib numpy Pillow seaborn scikit-learn tensorflow jupyter

<br>

# 4. Directories and Files

| Directory/File |D/F| description |
| :------------- | :-| :---------- |
| dataset | Dir | image files|
| dataset/images.zip | File | a compressed file of 810 photo images |
| model | Dir | Machine learning model |
| model/best_model_2.12.0.h5 | File | trained model |
| output | Dir | working directory |
| _1_setup_dataset.ipynb | File | unzip images.zip and prepare input data |
| _2_train.ipynb | File | create a model |
| _3_predict.ipyno | File | prediect image(s) |
| READMD.md | File ||
| requirements.txt | File | prerequisite libraries |


## contents of images.zip

| Directory | Cusine | number of images |
| :-------- | :------| :--------------- |
| test/salad | サラダ | 70 |
| test/sushi | すし | 70 |
| test/tofu | 麻婆豆腐 | 70 |
| train/salad | サラダ | 200 |
| train/sushi | すし | 200 |
| train/tofu | 麻婆豆腐 | 200 |
||Total | 810 |
