#Convolutional Neural Networks for ETC data prediction

用CNN來預測車流量，資料集來源為[交通資料庫](http://tisvcloud.freeway.gov.tw)中M03A項，本專案含

* 先將2014\_sum.csv與2015\_sum.csv透過clean\_traffic\_data轉換成訓練、測試資料集
* 再用CNN\_traffic\_slim來訓練與測試、視覺化