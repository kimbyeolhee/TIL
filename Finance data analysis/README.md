# 증권데이터 수집 및 분석
## 2021-05-01
### KRX 전체 종목 분석 ###
- FinanceDataReader로 한국거래소 상장종목 불러오기
- 데이터 타입 변경 
- 특정 섹터별, 지역별 등 다양한 칼럼들의 빈도 수 시각화
  - 한글폰트 설정
  - pandas
  - seaborn
  - groupby, pivot_table, crosstab
 - 데이터 색인

## 2021-05-02
### 종목 별 수익률 분석 ###
- 특정 상장기업명을 입력하면 해당 상장기업의 Symbol값 출력하는 함수
- 특정 상장기업의 종가 변화 시각화
- 여러 기업들의 종가 변화 비교 시각화
- 수익률 시각화
- 왜도, 첨도


## 2021-05-03
### 웹스크래핑으로 주가 데이터 수집 ###
- 웹 스크래핑을 통해 naver증권 일별 데이터 수집
- requests
- beautifulsoup
- pandas.read_html
- 수집 데이터 통합 pd.concat
- 중복 데이터 제거 pd.drop_duplicates()
- 전체 과정 

## 2021-05-04 ##
### 주가 데이터 인터렉티브 시각화 ###
- plotly 
- CandleStick 차트
- OHLC 차트 
### ETF 전체 종목 데이터 수집 및 저장 ###
- 브라우저 네트워크 탭을 통해 requests, pandas로 데이터수집
- JSON 타입 데이터프레임화

참고 https://github.com/corazzon/finance-data-analysis
