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


## 2021-05-05 ##
### ETF 수집 데이터 전처리 ###
- etfTabCode에 따른 etfTabName칼럼 생성
- 컬럼 명 변경
- 파생변수 생성

## 2021-05-06 ##
### ETF 전체 종목 분석 및 시각화 ###
- 변수 두개의 빈도수와 비율 
- barplot
- groupby로 barplot그래프의 수치 계산
- 수치형 / 범주형 변수의 서브플롯 (boxplot, volinplot, countplot, barplot)
- enumerate 함수
- 상관계수
- 마스크

## 2021-05-07 ##
### 특정 업종/테마의 모든 정보에 대한 상세정보 수집 ###
- 종목/테마 정보 하나 선택하여 해당 종목/테마의 종목 목록을 수집 (read_html , dropna)
- 개별 종목의 상세정보 수집 (read_html, concat, set_index, transpose)
- 처음 수집한 모든 종목의 상세정보를 수집 (함수 만들어서 apply)
- 수집한 목록에 상세 정보를 합침 (merge)

## 2021-05-08 ##
### 업종_테마 텍스트데이터 전처리 ###
- dtype 데이터타입 변경
- 정규표현식
- split()
- filter()
- melt()로 tidy 데이터화
- del 로 사용하지 않는 컬럼 제거

## 2021-05-09 ##
### 업종테마 분석 ###
- 천단위 숫자 구분 format()
- 사용하지않는 칼럼 삭제 del()
- 상하위 10개 종목 시각화
  - sort_values()
  - set_index()
- 이상치 찾기
- 최대 손실 낙폭
- 전체 변수에 대한 상관계수 및 시각화
- 종목 별 상관계수

## 2021-05-10 ##
### 기술적분석 ###
- 일별 수익률
  - shift()
  - pct_change()
- 누적 수익률
  - cumprod()
- 단순/누적/지수 이동평균
  - rolling()
  - expanding()
  - ewm()
- 주기별 데이터 추출 및 샘플링
  - asfreq
  - resample

## 2021-05-11 ##


참고 https://github.com/corazzon/finance-data-analysis
