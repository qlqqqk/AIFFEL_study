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

    4. **Kaggle House price Prediction(머신러닝 회귀)**  
        캐글 대회 예제 실습을 통해 데이터 EDA 시각화 및 전처리  
        GridSearch를 활용한 모델 학습 및 하이퍼파라미터 최적화  

    5. **가위바위보 이미지 분류(머신러닝 분류)**  
        직접 데이터셋을 구성하고 CNN 모델 커스텀  

    6. **영어 가사 생성 RNN모델(NLP)**  
        텍스트 데이터 전처리 및 토큰화  
        simple LSTM model 구현 및 inference 함수 구성  

    7. **뉴스 요약 RNN모델(NLP)**  
        attention을 활용한 인코더-디코더 형태의 RNN모델 설계  
        추출적 요약과 추출적 요약 output 비교  
    
    8. **고양이 수염 그리기(CV)**
        dlib를 활용한 face detection & stick a cat sticker  
    
    9. **영화리뷰 긍부정 데이터를 활용한 Word2vec(NLP)**  
        NLP DataLoader 구성 및 모델 클래스 구현/학습  
        vocab을 활용한 CNN,RNN,word2vec의 embedding 비교분석    
        
    10. **인물모드 사진 만들기(CV)**  
        아웃포커싱 효과와 크로마키 사진만들기  
        cv2를 활용 semantic segmentation 구현  

    11. **한국어 챗봇 만들기(NLP)**  
        SubwordTextEncoder를 활용한 tokenizing  
        transformer class 구현과정 학습  

    12. **여러가지 OCR tool 활용해보기(cv)**  
        한국어와 영어로 되어있는 사진들에 OCR기법 적용(keras-ocr,Tesseract)  

    13. **BERT(NLP)**
        korQuAD data set을 QA task에 맞게 전처리 후 EDA  
        BERT model 구현,학습 및 inference  

    14. **GAN(CV)**  
        CIFAR10 data set을 활용한 simple GAN 실습  

    15. **Movie Recommendation(Resys)**  
        추천시스템에서 중요한 sparse matrix를 CSR(Compressed Sparse Row)방법으로 다루기  
        ALS Algorithm을 활용한 Recommendation 과정 실습  
    
    16. **Pix2Pix(CV)**  
        이미지 데이터에 대한 확률적 augmentation 함수 구성  
        pix2pix model(U-Net, PatchGAN) 구성  

    17. **Session Based Recommendation(Resys)**  
        sequential data 분석 및 GRU Recommendation model 구성  






