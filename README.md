#   Detecting Defective Product 🥠

##  📜 개요
주어진 데이터를 가시화, 분석하여 제품 불량 탐지에 적합한 예측 모델 개발. <br><br>
  • 이진 분류 문제 <br>
  • 목표 변수 (label): 불량 여부 <br>

## 📊 데이터
  • 학습 데이터: train.csv 정답 레이블 포함 <br>
  • 데이터 인코딩: UTF-8 <br>
  • <b>변수 명세<b> <br>

```diff
+ Num: 제품번호   
+ insp: 검수자 코드
+ date: 검수일자
+ buydate: 구입일자 
+ ingr_A: 식품 원료 A 함량 
+ ingr_B: 식품 원료 B 함량
+ ingr_C: 식품 원료 C 함량
+ wtcd: 수원지 코드 
+ gram: 식품 중량
+ 
- label (0: Not Defective, 1: Defective) 
```


  
  
    
