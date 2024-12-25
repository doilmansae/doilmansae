Coursera Data Management and Visualization 과제
# MODULE 4
## 1단계: 변수에 대한 단변량 그래프
. 단변량 그래프를 통해 각 변수에 대해 히스토그램, 박스플롯, 밀도 그래프 등을 그려 변수의 분포를 파악합니다.
![image](https://github.com/user-attachments/assets/17ed6bb4-6f5d-4f95-b99c-8f8cac68c722)



1. 소득수준
. 값의 범위가 커서 히스토그램을 사용하여 그래프를 그려보았으며, 소득이 낮은 구간 10000이하에 많은 국가가 있으므로 로그 변환 히스토그램을 사용함.

![image](https://github.com/user-attachments/assets/7dd7ca95-eb3d-4d9c-b7c3-55908cfdd407)
![image](https://github.com/user-attachments/assets/65824ff8-eb2e-4081-b21c-e90a38dd7ba2)


3. 유방암 발병비율
. 0~100% 구간의 퍼센트 데이터임으로 히스토그램을 사용하여 도식화함.  
![image](https://github.com/user-attachments/assets/649f98d0-6349-40ba-b90a-f0af55d2dcd0)


4. 기대수명
. 상대적으로 좁은 범위 50~80세이며 평균 주위에 몰려있는 경향이 커서 밀도곡선(KDE)를 사용하여 도식화함.  
![image](https://github.com/user-attachments/assets/d21da015-32f1-4754-9700-844f4902f724)


## 2단계: 두 변수간의 연관성을 보여주는 이변량 그래프
. 소득 수준(incomeperperson)과 기대수명(lifeexpectancy): 소득이 높을수록 기대수명이 증가하는 경향을 볼 수 있는지 확인하기 위해 산점도(scatter plot)를 사용함.  
![image](https://github.com/user-attachments/assets/1d9bdfa8-1cb2-43ce-b4fb-fee8615d48b0)
![image](https://github.com/user-attachments/assets/5c3171ba-c335-4806-95fa-f1f110bf79f5)


**요약 : 소득 수준이 올라갈수록 기대수명이 올라가는 경향이 있음을 확인 할 수 있음.  **
