## 一個間單的分類器實作
### 專案包含:
1. 資料收集
2. 模型訓練
3. 實際展示

### 使用到的工具:
1. Pytorch
2. Jupyter Lab
3. Jetson nano + CSI camera

### 使用到的訓練模型:
Alexnet：
* 激勵函數：ReLU
* 在GPU上實現
* 共八層：
> 1~5 層是 Convolutional Layers （卷積層）與Pooling（池化層）
> 6~8 層是 Fully Connected Layers（全連接層）
* 最高可達到1000個類別（在使用上只要替換最後一層即可）

