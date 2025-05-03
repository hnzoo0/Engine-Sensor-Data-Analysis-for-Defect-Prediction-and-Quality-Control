## ❗ 문제 정의

- 에코 모빌리티의 엔진 센서 데이터를 활용하여, 차량의 결함 여부 및 결함 유형(0: 정상, 1~3: 결함) 을 사전에 예측하는 머신러닝 모델을 개발하고, 결함과 밀접한 주요 센서 변수를 도출함으로써 품질관리와 안전성 개선에 기여한다.



## 📊 데이터 활용 계획

- 탐색적 데이터 분석(EDA):
  - 변수 분포 확인, 이상치 탐지, 결함 그룹별 센서 데이터 특성 비교

- 통계 분석:
  - t-검정, ANOVA를 활용해 정상 그룹과 결함 그룹 간 센서 변수의 유의미한 차이 분석

- 머신러닝 예측 모델:
  - 로지스틱 회귀, 랜덤포레스트, LightGBM 등 분류 모델을 학습하여 결함 유형 예측

- 피처 중요도 분석:
  - 모델 기반 변수 중요도를 활용해 주요 결함 관련 지표 식별





## 🎯 예상 결과물 및 기대 효과


- 예상 결과물

  - 엔진 결함 여부 및 유형을 분류하는 머신러닝 예측 모델

  - 결함 발생과 밀접한 주요 센서 변수 리스트 및 중요도 분석 리포트

  - 정상 vs 결함 조건 간 유의미한 차이를 도출한 통계 분석 결과



- 기대 효과

  - 결함 사전 탐지 및 예방 정비를 통한 차량 안전성 향상

  - 주요 결함 유발 요인을 기반으로 한 공정 개선 및 품질 강화

  - 결함 예측 자동화를 통해 정비 효율성 및 고객 신뢰도 향상

  - 데이터 기반 의사결정 체계 구축 및 품질관리 고도화
 
----------------------------------------------------------------------------------------------------------------------------------------------

## ❗ Problem Definition
- Utilize Eco Mobility's engine sensor data to develop a machine learning model that predicts vehicle defects and defect types (0: Normal, 1-3: Defect) in advance, and identify key sensor variables closely related to defects, thereby contributing to quality management and safety improvement.

## 📊 Data Utilization Plan
- Exploratory Data Analysis (EDA):

  - Verify variable distributions, detect outliers, compare sensor data characteristics by defect group.
    
- Statistical Analysis:

  - Utilize t-tests and ANOVA to analyze significant differences in sensor variables between the normal and defect groups.
    
- Machine Learning Prediction Model:

  - Train classification models such as Logistic Regression, Random Forest, and LightGBM to predict defect types.
    
- Feature Importance Analysis:

  - Identify key defect-related indicators using model-based variable importance.
    
## 🎯 Expected Outcomes and Benefits

- Expected Outcomes

  - A machine learning prediction model that classifies engine defect presence and type.
  - A report analyzing key sensor variables closely related to defect occurrence and their importance.
  - Statistical analysis results identifying significant differences between normal vs. defect conditions.
    
- Expected Benefits

  - Improved vehicle safety through proactive defect detection and preventative maintenance.
  - Enhanced process improvement and quality reinforcement based on key defect-causing factors.
  - Improved maintenance efficiency and customer trust through defect prediction automation.
  - Establishment of a data-driven decision-making system and advancement of quality management.
