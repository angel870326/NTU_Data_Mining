# NTU_Data_Mining

### HW1: Dimensionality Reduction & Classification
* Principal Components Analysis
* Entropy-based discretization
* Gaussian Naive Bayes algorithm for classification

Dataset: https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset

### HW2: Classification
* Gaussian Naive Bayes algorithm

Dataset: https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification?select=train.csv

### Final Project: MBTI Personality Types Classification
* LinearSVC
* SVM (linear kernel)
* SVM (polynomial kernel)
* SVM (RBF kernel)

Dataset: https://www.kaggle.com/datasets/zeyadkhalid/mbti-personality-types-500-dataset

#### 防止 Colab 斷線
右鍵 -> 檢查 -> Console
```
function ConnectButton(){
    console.log("Connect pushed");
    document.querySelector("#top-toolbar > colab-connect-button").shadowRoot.querySelector("#connect").click()
}
setInterval(ConnectButton,60000);
```
