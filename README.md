# COVID_Detection_System
可以參照這篇medium
https://watson-john.medium.com/transfer-learning-gradcam-with-flask-implementation-220042cbeb58
1. 下載好資料，並將其處理成./dataset/covid 跟./dataset/normal
2. 把vgg16權重下載好放到 ./vgg16_weighht/ 中
3. 安裝相關套件 
4. 運行train 以訓練模型
5. 運行Gradcam 已觀察模型抓取特徵。
6. 運行API.py展示網頁

最終畫面（左：初始，右：提交照片後）：


![image](https://github.com/johnwalking/COVID_Detection_System/blob/main/1*ZxwdLGM41El-nwW0pFZRuw.png)
