# 서울특별시 아파트 실거래가 예측

## Project
- 팀원 : 조여재, 엄대용, 박상우
- 기간 : 2022/09/14 - 2022/09/20
- 발표 : 2022/09/20
- used by: Jupyter notebook, PPT

## Dataset
- apt.csv : 아파트 매매 실거래가 [출처 : 국토교통부 실거래가 공개 시스템]
- day_care.csv : 서울시 어린이집 정보 [출처 : 서울 열린데이터 광장]
- park1.csv : 서울시 공원(1인당 공원면적)통계 [출처 : 공공데이터 포털]
- apartment_price.csv : 데이터들을 전처리 후 저장한 최종 테이블  


## Coding
1. data_cleansing.ipynb
   - apt, day_care, park1 테이블 변수들을 정리 후 apartment_price 파일로 저장 
2. EDA_and_modeling(1).ipynb 
   - EDA
   - Linear Regression, Polynomial Regression, Ridge, Lasso, ElasticNet, 
     Decision Tree Regressor, Random Forest Regressor, Gradient Boosting
3. modeling(2).ipynb
   - Random Forest Regressor, Voting Regressor
4. modeling(3).ipynb
   - Bagging Regressor
5. modeling(4).ipynb
   - Linear SVR
6. apartment_price_final.ipynb
   - Best Model Test : Gradient Boosting
   - Rest Model Test : Linear Regression, Polynomial Regression, Ridge, Lasso, ElasticNet
                       Decision Tree Regressor, Random Forest Regressor, Linear SVR
                       
## Scoring by
- mean squared error (MSE)

## presentation
- 22기 2차 미니 프로젝트 4팀.pdf : 2022/09/20 발표 자료
