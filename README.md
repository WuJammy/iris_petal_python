# 將iris的花瓣(petal) 之寬度(y軸)與高度(x軸)以散佈圖方式呈現
### (一) iris資料:
  (1) [下載連結](https://archive.ics.uci.edu/ml/datasets/iris)  
      (2) 請將下載好的csv檔與要執行的程式檔(.py)放在同一個資料夾
### (二) 引入Pandas及Matplot這兩個套件:
  ```python
  import pandas as pd
  import matplotlib.pyplot as plt
  ```
### (三) 導入iris的資料:
 ```python
  pd.read_csv("iris.csv",index_col="class",encoding = "utf8")
  ```

### (三) 輸出結果:
(1) 紅色: setosa  <br>
(2) 橘色: versicolor <br>
(3) 紫色: virginica


![image](https://github.com/WuJammy/iris_petal_python/blob/master/img/1420.png)
