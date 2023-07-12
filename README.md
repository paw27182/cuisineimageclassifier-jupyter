# cuisine-image-classifier

# 1. What you can do

* 写真イメージの分類器を生成し，この分類器を用いて写真イメージを分類できます<br>
  To create an image-classifier model, and predict images by the model.

<br>

<img src="cuisineimageclassifier.png">

<br>

# 2. How to use

* Create a model
  * Execute Jupyter notebook : **_1_train.ipynb**<br>

<br>

* Predict image(s)
  * Execute Jupyter notebook : **_2_predict.ipynb**

<br>

# 3. System
* OS: Windows 10, Ubuntu 20.04.6 LTS<br>
* Python 3.10.11<br>
* Python Libraries: See the requirements.txt file

<br>

# 4. Directories and Files

| Directory/File |D/F| description |
| :------------- | :-| :---------- |
| dataset | Dir | image files|
| dataset/images.zip | File | a compressed file of 810 photo images |
| model | Dir | Machine learning model |
| model/best_model_2.13.0.h5 | File | trained model |
| output | Dir | working directory |
| _1_train.ipynb | File | create a model |
| _2_predict.ipyno | File | prediect image(s) |
| READMD.md | File ||
| requirements.txt | File | prerequisite libraries |
| setup_dataset.ipynb | File | unzip images.zip and prepare input data |

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
