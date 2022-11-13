# 國立陽明交通大學 AI學院 111學年度 第1學期 模組單元課程-Pytorch深度學習實作<br>

## 公告: 
評分方式: 出席率50%、作業20%、問答30% <br>

## 評分結果:
作業成績覺得有問題請跟我聯繫，如果沒有問題，11/18會將成績送出到大助教那邊。<br>
Note: QA次數以周圍單位，如果你三周都有發問，但次數不正確在跟我聯繫一下。<br><br>

**因為有同學成績破表，所以我把QA調整一下，問一次25分，問多次的30分，基本上成績都超過90。**<br>

**製表日(2022/11/13 20:40):**
|學號|QA次數|Homework繳交日|作業成績(總分20)|課程總成績|
|:---:|:---:|:---:|:---:|:---:|
|311831007|1|11/10|15|80|
|311833013|1|11/10|18|98|
|311832017|1|11/9|15|90|
|311832009|1|11/10|18|93|
|311832010|2|11/10|18|95|
|311831009|1|11/9|18|93|
|311833009|1|11/11|15|93|
|311833014|1|11/11|15|90|
|311831008|1|11/10|18|90|
|311833023|1|11/11|15|93|
|311833007|1|11/10|15|90|
|311831013|2|11/09|15|95|
|311831004|1|11/11|15|90|
|311831006|1|11/11|15|90|



## 本課程以實體課程方式進行
* **授課教師：** <br>
 黃志勝 <br>
* **contact email:**<br> 
chih.sheng.huang821@gmail.com<br>
tommy.huang@emc.com.tw<br>
* **先修科目或先備能力：**<br>
 Python<br>
* **課程概述與目標：**<br>
三周的課程教與同學如何使用Pytorch<br>
第一周: 著重在處理dataloader，並跟同學說明一般資料去哪邊取得。<br>
第二周: 著重在CNN相關，包含如何使用conv和設定相關參數等，並建立一個CNN模型，並以ONNX方式進行Inference。<br>
第三周: 結合OPENCV讓同學可以快速使用自己建立的模型搭配web cam在電腦上進行Inference。<br>
------------
 |週次|上課日期|課程進度、內容、主題|投影片|code|Homework|
 |:---:|:---:|:---:|:---:|:---:|:---:|
 |1|2022/10/13 9:00-12:00|- 影像標註方式 <br> - 影像Dataset <br> - Pytorch dataloder |[week1 深度學習_標註.pdf](https://reurl.cc/D3G4Kd)<br>[week1 深度學習Pytorch手把手實作_01_資料庫.pdf](https://reurl.cc/MNq46m)<br>[week1 深度學習Pytorch手把手實作_02_pytorch dataloader.pdf](https://reurl.cc/m3ErRV)<br>|[Week01_01_database.ipynb](https://reurl.cc/2mpzKm)<br>[Week01_01_database_private.ipynb](https://reurl.cc/QbzeYo)<br>[Week01_01_database_pytorch.ipynb](https://reurl.cc/dW6La2)<br>[Week01_02_pytorch_dataloader.ipynb](https://reurl.cc/ERE4QA)<br>[Week01_02_pytorch_dataloader_linux.ipynb](https://reurl.cc/nOerln)|無|
 |2|2022/10/20 9:00-12:00| - MNIST分類訓練<br> - CNN分類-水果分類(私有資料庫)<br> - pytorch Conv.操作|[week2 深度學習Pytorch手把手實作_分類.pdf](https://reurl.cc/O49GMr)<br>[week2 深度學習Pytorch手把手實作_模型.pdf](https://reurl.cc/W1lRNx)<br>|[Week02_01_pytorch_classification.ipynb](https://reurl.cc/bE0DNr)<br>[Week02_02_pytorch_GradientOperator.ipynb](https://reurl.cc/YXyVD4)<br>[Week02_03_pytorch_classification_Fruits.ipynb](https://reurl.cc/nOerxv)<br>[Week02_04_pytorch_operator_conv.ipynb](https://reurl.cc/0X79kM)<br>|無|
 |3|2022/10/27 9:00-12:00|-分類訓練範例:情緒辨識<br> -物件偵測介紹和pytorch訓練: 以交通號誌辨識為例<br>|[week3 深度學習Pytorch手把手實作_物件偵測.pdf](https://reurl.cc/pZnYLl)<br> [week3 深度學習Pytorch手把手實作_物件偵測YOLOv2.pdf](https://reurl.cc/MX1z8K)<br>|[Week03_pytorch_classification_fer2013_resnet18.ipynb](https://reurl.cc/VRpWNA)<br> [Week03_pytorch_classification_fer2013_resnet18byTorchvision.ipynb](https://reurl.cc/lZkYQQ)<br> [Week03_pytorch_classification_fer2013_Inference.ipynb](https://reurl.cc/gQkYGb)<br> [Week03_pytorch_objectdetection.ipynb](https://reurl.cc/eWvkzj)<br>|[main_pytorch_ImageClassification_onnx.py](https://reurl.cc/gQkY6b)|

## 作業: 

寫一份影像分類inference程式，請參閱 Week03的作業範本 [main_pytorch_ImageClassification_onnx.py](https://reurl.cc/gQkY6b) <br>

(1) 可用別人訓練好的模型和應用
要在程式內說明你使用的模型和應用的連結<br>

(2) 訓練自己的資料和應用
要用額外交一份Jupyter Notebook **說明你訓練的資料庫和應用類型**，並將訓練程式貼在筆記本內，見範本[Week03_pytorch_classification_fer2013_resnet18.ipynb](https://reurl.cc/VRpWNA)。<br>

<front color='r'>**Inference模型限定交付onnx。**<br></front>
作業總分20分<br>
選擇(1):作業基礎至少可得5分 <br>
選擇(2):作業基礎至少可得15分 <br>
依據程式碼和說明的完整度來往上調分數。

**期限: 2022/11/11** <br>

作業繳交壓縮成一個檔案上傳，檔案名稱: **111-1_HW_Pytorch深度學習實作_名字_學號** <br>
[作業繳交google drive Link](https://drive.google.com/drive/folders/1oYh7MMkY29AOx7pn6yUmn7FDziBWFp7u?usp=sharing)，如果登入不進去在跟我聯繫一下

