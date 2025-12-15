# 데이터마이닝과분석 텀프로젝트 (`회귀 · 정규화`)

## 프로젝트 개요

본 프로젝트는 `수치형 변수 기반 회귀 예측 모델` 구축을 목표로 한 데이터마이닝과분석 과목 텀프로젝트입니다.  


---

## 분석 목표

- `비선형 모델을 배제하고, 해석 가능한 선형 모델의 성능 명확히 이해`
    
- `전처리, 정규화가 회귀 성능과 일반화에 미치는 영향 분석`
    
- `Validation 성능과 Test 성능 간 괴리를 최소화하여 과적합 방지`
    

---

### 사용 지표

- **Adjusted R²** (수정된 결정계수)
    
- **MAPE** (Mean Absolute Percentage Error)

    
### 최종 성능 점수 (M)

```
M = ( max(0, Adjusted R²) + max(0, 1 − MAPE) ) / 2
```  

---

## 저장소 구성

```
├── train.ipynb                         # 전체 분석 및 모델 학습 노트북
├── model.pkl                           # 최종 학습된 회귀 모델
├── regression_train_public.csv         # 공개 학습 데이터
├── regression_test_private.csv         # 비공개 테스트 입력 데이터
├── regression_test_private_target.csv  # 비공개 테스트 타깃 (평가용)
├── Term_Project_회귀공지.pdf            # 과제 공지 및 평가 기준
└── README.md                           # 프로젝트 설명 문서
```

---

## 상세 분석 문서

프로젝트의 전체 분석 과정, 전처리 근거, 모델링 과정 및 해석은  
아래 문서에 정리되어 있습니다.

👉 **[Term_Project_회귀공지.pdf](Term_Project_회귀공지.pdf)**

