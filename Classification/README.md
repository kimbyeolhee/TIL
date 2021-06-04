분류: 나이브 베이즈, 로지스틱 회귀, 결정트리, SVM, KNN, 신경망, 앙상블 알고리즘<br/>
<br/>
# 결정 트리<br/>
결정트리는 쉽고 직관적이지만 rule 규칙을 만들기 위해 쉽게 오버피팅 된다는 단점 존재<br/>
[1. 결정 트리 및 사용자 행동 인식데이터를 이용한 실습](https://github.com/kimbyeolhee/TIL/blob/main/Classification/%EA%B2%B0%EC%A0%95%20%ED%8A%B8%EB%A6%AC%20%EB%B0%8F%20%EC%82%AC%EC%9A%A9%EC%9E%90%20%ED%96%89%EB%8F%99%20%EC%9D%B8%EC%8B%9D%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%A5%BC%20%EC%9D%B4%EC%9A%A9%ED%95%9C%20%EC%8B%A4%EC%8A%B5.ipynb)<br/>
<br/>
# 앙상블 알고리즘<br/>
앙상블은 약한 학습기를 이용해  오버피팅같은 단점을 순화시키고 장점은 강화시키는 형태로 구성<br/>
앙상블 알고리즘은 **보팅**, **배깅**, **부스팅**, **스태킹**으로 나뉨<br/>
보팅: 보팅 분류기 , 배깅: 랜덤포레스트, 부스팅: GBM, XGBOOST, LightGBM
## 보팅, 배깅<br/>
RandomForest: 각각의 학습기들이 중복을 허용한 부트스트래핑으로 샘플링된 데이터를 학습하여 예측<br/>
[2. 앙상블 학습](https://github.com/kimbyeolhee/TIL/blob/main/Classification/%EC%95%99%EC%83%81%EB%B8%94%20%ED%95%99%EC%8A%B5_%20RandomForest_GBM.ipynb)<br/>
<br/>
## 부스팅<br/>
GBM:오류가 발생한 데이터에 대해서 다음의 학습기가 더 잘 학습하도록 가중치 부여, 경사하강법으로 오류가 감소하는 방법으로 지속적으로 학습 진행<br/>
XGBoost, LightGBM: GBM에서 발전된 형태<br/>
[3. XGBoost](https://github.com/kimbyeolhee/TIL/blob/main/Classification/XGBoost.ipynb)<br/>
[4. LightGBM](https://github.com/kimbyeolhee/TIL/blob/main/Classification/LightGBM.ipynb)<br/>
<br/>
## 스태킹<br/>
각각의 개별 모델들이 학습하여 예측한 값을 기반으로 최종적인 메타 모델이 예측값을 스태킹한 데이터를 학습하고 예측 
[5. 스태킹 앙상블](https://github.com/kimbyeolhee/TIL/blob/main/Classification/%EC%8A%A4%ED%83%9C%ED%82%B9%20%EC%95%99%EC%83%81%EB%B8%94.ipynb)<br/>


