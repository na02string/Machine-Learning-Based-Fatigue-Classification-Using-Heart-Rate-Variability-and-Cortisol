# Machine Learning-Based Fatigue Classification Using Heart Rate Variability and Cortisol : A Multimodal Approach to Wearable Health Monitoring
**HRV 및 코르티솔 데이터를 활용한 피로 예측 모델 개발 (저널 투고 예정)**

이 프로젝트는 HRV 지표와 코르티솔 수치를 활용하여 피로도(FSS)를 예측하는 머신러닝 기반 모델을 개발한 코드입니다.  
주요 변수인 결측 코르티솔 수치를 MICE 기반으로 보정한 뒤, TabNet 모델링 및 delta-adjustment 기반 민감도 분석을 수행하였습니다.  
특히 의료 데이터 특성상 결측 보정값 사용에 대한 타당성을 확보하기 위해 **Little’s MCAR Test**, **Logistic Regression Missingness Test** 등을 활용해 결측 메커니즘이 MCAR, MAR, MNAR 중 어떤 유형에 가까운지 통계적으로 검토했습니다.  
이를 통해 결측 보정 방식의 적절성을 확인하고, 모델 예측의 신뢰성을 확보하고자 하였습니다.
