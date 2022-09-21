# Iris-Classification
## 挑選鳶尾花資料集來做訓練的原因
於練習蘭花辨識之前，想先使用較簡單的鳶尾花辨識來做練習與熟悉！  
因為此資料集已經做好基本的分類整理，且是一個完整個數據集，所以挑此資料集來做練習！  
(source of iris dataset:https://archive.ics.uci.edu/ml/datasets/iris)  
## 數據集介紹
此數據集包含150個樣本都屬於鳶尾屬下的三個亞屬，分別是山鳶尾（setosa）、變色鳶尾（verscicolor）和維吉尼亞鳶尾（virginica）  
以花朵的四個特徵來做樣本的定量分析，四個特徵分別為：sepal-lenght, sepal-width, petal-lenght, petal-width  
資料集的前四行是代表上述所量測到的特徵數值，最後一行則是鳶尾花的分類  

以視覺化的方式來呈現資料集：
![iris_data_distribution](https://user-images.githubusercontent.com/62006029/191407616-90013ed7-dfa0-486a-9150-c2196df22cb9.png)
可從散佈圖看出該資料集的特徵分佈都有一定範圍，且分佈是明顯的，因此是一個適合拿來做分類的資料集!

## Training history

### Model accuracy

![model_acc](https://user-images.githubusercontent.com/62006029/191407947-1aa16680-66c0-4977-885b-3746bb012c72.png)

### Model loss

![model_loss](https://user-images.githubusercontent.com/62006029/191408164-40b1e4ca-f6f2-4fc4-bd95-bd01c7cc3ae1.png)

訓練過程中可以看出loss是穩定下降的且波動幅度不大，與其他同學討論過後，應該是正常且成功的訓練過程。

### Result

Accuracy: 100.00% 
