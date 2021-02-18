## 운동동작분류경진대회
### -설명 : 3축 가속도계(accelerometer)와 3축 자이로스코프(gyroscope)를 활용해 측정된 센서 데이터에 머신러닝 알고리즘을 적용해 운동 동작 인식 알고리즘 개발, 
### -시계열데이터를 활용해서 예측
### -대회일정 : 2021.01.11 ~ 2021.02.22
### -링크 : https://dacon.io/competitions/official/235689/overview/
### -내점수(LogLoss) : 1.49488
### -데이터 설명

-train_features.csv (1875000, 8) : id 별 600 time 간 동작 데이터,  id 3125개 x 600 time =1875000 데이터

-train_labels.csv (3125, 3) : id 별 동작과 동작 label(61개)

-test_features.csv (469200, 8) : id 별 600 time간 동작 데이터, id 782개 x 600 time =469200 데이터

-sample_submission.csv (782, 62) : id별 동작을 예측해 작성하는 csv
