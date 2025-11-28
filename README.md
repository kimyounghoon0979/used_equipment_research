# Used Construction Equipment Research Dataset  
연구: *모바일 기반 중고 건설장비 거래 플랫폼 UX 최적화 및 AI 통합 설계 연구*

본 저장소는 논문의 부록으로 활용되는 **연구 데이터셋, 설문 자료, 시나리오 자료, 시스템 성능측정 자료** 등을 포함하고 있습니다.  
개인정보 또는 특정 플랫폼을 직·간접적으로 식별할 수 있는 정보는 모두 제거 또는 익명화하였습니다.


## Structure
├── README.md
├── survey/
│ ├── 1.survey_original_questions.pdf
│ └── 2.survey_responses_aggregated.xlsx
└── dataset/
├── 1.trade_data_clean.xlsx
├── 2.behavior_scenario.xlsx
├── 3.system_performance.xlsx
└── 4.used_equipment_market_listings.xlsx

---

## 📁 1. Survey (설문 자료)

### **1.survey_original_questions.pdf**
- UX 평가용 설문지 원본  
- SUS(시스템 사용성 척도), UEQ, SEQ 문항 포함  

---

### **2.survey_responses_aggregated.xlsx**
- 수집된 설문 응답을 항목별로 집계한 자료  
- SUS 점수 변환, UEQ 6개 차원 평균 산출, SEQ 중앙값 포함  
- 개인 식별정보 없음 (익명처리 완료)

---

## 📁 2. Dataset (연구 데이터셋)

### **1.trade_data_clean.xlsx**
- 거래 기초데이터를 온라인 매물 정보를 참고해 재가공한 데이터
- 총 126건 규모의 거래 데이터 생성
- 개인정보 및 매물 식별정보 미포함

---

### **2.behavior_scenario.xlsx**
- 추천 시스템(ALS·Hybrid·Bandit) 개발 시 사용된 사용자 행동 시나리오  
- 가상의 synthetic data 기반 (개인 정보 없음)

---

### **3.system_performance.xlsx**
- 플랫폼 기능(등록/검색/추천/이미지 처리 등)의 처리시간 측정  
- 모델 응답속도, API 지연시간, 페이지 로딩 속도 등 포함  

---

### **4.used_equipment_market_listings.xlsx**
- 국내 중고 건설장비 시장의 구조적 특성 분석을 위해 정제된 매물 리스트  
- 특정 플랫폼을 직접 언급하지 않으며, URL/위치/판매자 등 민감정보 제거  
- 포함 변수:  
  - 대분류 / 중분류  
  - 제조사 / 모델명  
  - 제작년식  
  - 희망가격 / 보정가격  
  - 등록 날짜  
- “개인 판매자 비율 산출(5.1%)” 등 논문 Chapter 1.1 연구의 필요성에서 활용됨  
- 특정 판매자, 특정 사이트, 연락처 등은 모두 제거된 비식별 데이터

---

## 🔒 개인정보 및 민감정보 처리
- 모든 파일은 개인정보보호법 준수를 위해 **익명화·비식별화**되었음  
- URL, 작성자명, 상세 위치(시·군 제외), 전화번호·아이디 등 **전부 삭제됨**  
- 시장 구조 분석 목적의 **통계적 항목만 유지**

---

