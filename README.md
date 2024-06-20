# 쇼핑몰 리뷰 감성분석을 통한 감성 점수 계산 머신러닝
## 감성 점수 계산 방법
- 기존에 쇼핑 분야 한국어 감성 사전이 따로 구축되어 있는 것이 없어 Logistic 회귀 계수를 감성 사전으로 이용
- 해당 리뷰 문장의 각 감성 단어의 회귀 계수를 모두 더한 후 0과 10사이로 정규화
## 연구 목표 및 연구 방법
<img width="832" alt="image" src="https://github.com/0chaechae2/sentiment-score-analysis/assets/173161886/182393be-7acf-47b0-a591-55f4f82781bd">

## 분석 파일 목록 및 설명
### **1. sentiment_project_data_processing.ipynb & crawling.ipynb**  
데이터 전처리 및 토큰화 & 크롤링 과정
### **2. sentiment_project_modeling.ipynb & sentiment_project_apply_crawling.ipynb & misclassified_data_sentimetscore.ipynb**  
모델링 및 모델 검증 & 긍정 클래스지만 모델이 부정으로 분류한 데이터
- 용량이 커서 따로 올렸지만 2-2 파일들은 '2. sentiment_project_modeling.ipynb'파일에 이어서 붙여야 합니다.
### **3. wordcloud_frequency.ipynb & wordcloud_regression_coefficient.ipynb**  
시각화 파일  
### **4. survey_refining.ipynb**  
Ground-truth 이상치 제거  
