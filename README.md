# Finding-Your-Personality-Palette
Check Point Report: https://reurl.cc/1Z7ADp  
Video: https://reurl.cc/e372xM
### Author
Chieh-Yu Chuang, Chun-Pei Chen  
National YangMing ChiaoTung University Hsinchu, Taiwan
### Introduction
The topic idea comes from our enthusiasm towards color science and psychological tests. We found out that the psychology tests nowadays restrict their participants to answer particular questions to get an customized output. However, since people's emotions and personality are quite complicated, we think it would be better to accept a wider range of inputs to analyze the results better. Also, we believe that dialogues may not contain only one type of emotions, it could be complicated combinations. Therefore, we chose to show our results via colors.

### Prerequisites
Environment: Google Colaboratory  
Packages version: refer to [requirements.txt](https://github.com/chiehyyu/Finding-Your-Personality-Palette/blob/main/requirement.txt) in our github
### Usage
Dataset: https://reurl.cc/VDQxYn  
Happy　35%  
Sadness　31%  
Anger　15%  
Fear　14%  
Surprise　5%  
### Hyperparameters
Epoch/iteration: 10  
Learning Rate: 0.01  
TrainData, ValidationData, and TestData proportion: 6-1-3  
### Baseline
Multinomial Logistic Regression (MLR)

### Main Approaches
Gate Recurrent Unit (GRU)  
Long Short-Term Memory (LSTM)  
Bidirectional Long Short-Term Memory (Bi-LSTM)

### Execution Results  
<img src="https://github.com/chiehyyu/Finding-Your-Personality-Palette/blob/main/Accuracy_Compare.png" width="300">  <img src="https://github.com/chiehyyu/Finding-Your-Personality-Palette/blob/main/Running_Time_Compare.png" width="300">  <img src="https://github.com/chiehyyu/Finding-Your-Personality-Palette/blob/main/Learning_Rate_Compare.png" width="300">

### Contribution
Chieh-Yu Chuang: 50%, Chun-Pei Chen: 50%
