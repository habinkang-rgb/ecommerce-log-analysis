# ecommerce-log-analysis

# 이커머스 웹 로그 데이터 분석

## 프로젝트 개요
이커머스 사용자 행동 로그 데이터를 기반으로
KPI, 퍼널, 리텐션 분석을 수행하고
매출 개선을 위한 전략을 도출했습니다.

---

## 분석 내용

### 1. KPI 분석
- GMV는 DAU(유입)와 구매전환율에 의해 결정
- 매출 변화는 유입과 전환 효율이 핵심

### 2. 퍼널 분석
- View → Cart 전환율 약 1.95%
- 주요 이탈 구간은 View → Cart
- 전환 그룹은 "적은 상품 깊게 탐색" 패턴

### 3. 리텐션 분석
- Day0 → Day1에서 60~70% 이탈 발생
- 상품조회수 높은 사용자일수록 초기 리텐션 높음
- 월초 유입 사용자 리텐션이 더 높음

---

## 주요 인사이트
- 매출은 유입과 전환율이 결정
- 탐색 깊이가 전환에 중요한 요소
- 초기 사용자 경험이 리텐션을 좌우

---

## 사용 기술
- Python (Pandas, Numpy, SciPy 등)
- SQL
- Jupyter Notebook
- Tableau

---

## 파일 설명
- ecommerce_analysis.ipynb: 전체 분석 코드
- dashboard.twbx: 시각화 대시보드

---

## 데이터

- Kaggle Ecommerce Behavior Dataset 사용  
- 수백만 건 이상의 사용자 행동 로그 데이터  
- 이벤트: view, cart, purchase 포함  
- 데이터 용량 문제로 repository에는 포함하지 않음  

👉 https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store
