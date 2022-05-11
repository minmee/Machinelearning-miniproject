# Machinelearning-miniproject


새싹 미니 프로젝트 4조 - 명소연, 구은혜, 박현주, 임채범, 정혜리, 신철호, 장국주, 이찬영


참고 코드 : [Private 1위 0.6581] | 소회의실 | Catboost의 코드 https://dacon.io/competitions/official/235713/codeshare/2768?page=1&dtype=recent / 
참고 코드 : [Private 5위 0.66016] | Team SsulleBal | Catboost의 코드 https://dacon.io/competitions/official/235713/codeshare/2746?page=1&dtype=recent


## 1. 프로젝트 목적
- 데이터 분석 및 전처리와 머신러닝을 사용하여 신용카드 사용자 데이터를 분석하여 사용자의 신용카드 대금 연체 정도를 예측하고자 진행함.

## 2. 데이터
- DACON에서 진행했던 '신용카드 사용자 연체 예측 AI 경진대회'에서 제공한 데이터로, 2010년대 해외 데이터임.

- Train data : (26457, 20)
- Test data : (10000, 19)

## 3. 전처리
- 참고 코드에 우리 조가 생각한 파생변수를 추가하였음.

![캡처메롱](https://user-images.githubusercontent.com/97076352/167835531-18fdead7-3da8-4a52-97c2-ade3a0656f3c.PNG)

![캡처메롱2](https://user-images.githubusercontent.com/97076352/167835588-5d1a9f1b-cd90-4ee0-beb6-b6c03bf6f2df.PNG)

![캡처메롱3](https://user-images.githubusercontent.com/97076352/167835662-93fcb5aa-0755-4941-a671-15af80d0cbcc.PNG)


- 연봉 관련, 회원 각각의 고유한 번호 생성 (ID) 파생변수 추가함.


## 4. 모델링
- Decision Tree, Random Forest, XGBoost, LightGBM, k-겹 교차 검증 StratifiedKFold를 이용한 Catboost
- 다양한 모델을 사용하여 신용카드 대금 연체 정도를 예측하는 인공지능 알고리즘을 개발하려고 노력함.

![캡처짱](https://user-images.githubusercontent.com/97076352/167837503-b3ae4c01-3b90-4e8d-b7a7-255e509c1675.PNG)



