# Exploration
- 각 실습 노트북 최하단에는 당시 작성한 회고록이 있으며, 폴더의 경우 회고록이 폴더 내 README에 작성되어있습니다.  

- 어떤 실습을 진행하였는지 요약하여 정리하였습니다. 괄호에는 해당하는 노트북의 관련된 테스크가 작성되어있습니다.  
    1. **MNIST 손글씨,와인,유방암 데이터 분류(머신러닝 분류)**  
        데이터 특성 파악 및 전처리 과정과 사이킷런의 모델 분류성능을 classification_report & confusion_matrix로 비교    

    2. **MNIST 당뇨수치,자전거 수요 회귀(머신러닝 회귀)**  
        Regression model의 내부 구조를 직접 구현(Loss,Gradient)
        PolynomialFeatures, K-Fold, L1/L2 penalty 등 성능개선을 위한 방법론 활용 실험   

    3. **ARIMA를 활용한 주가 예측(시계열)**  
        20일 이동평균선을 기준으로 로그와 차분을 활용해 안정시계열로 변환
        ACF(점진적으로 감소하는가),PACF(절단면으로 진입하는 시점)를 기준으로 ARIMA 인자 선택 MAPE로 성능 확인  

    4. 
        