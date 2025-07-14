# health-survey-disease-prediction
# 건강 설문 기반 질환 예측 모델 및 대시보드

📌 **프로젝트 개요**  
국민건강영양조사(KNHANES) 데이터를 활용하여 고혈압, 당뇨, 이상지질혈증 발생 가능성을 예측하고,  
Streamlit 대시보드로 위험도를 시각화하는 MultiOutputClassifier 딥러닝 모델을 개발했습니다.

---

## 🚀 프로젝트 주요 내용

✅ **데이터**  
- 국민건강영양조사 10년치 (약 72,000건)  
- 개인 건강 설문 문항, 임상 수치, 생활습관 데이터 포함

✅ **모델링**  
- MultiOutputClassifier 기반 Conv1D 신경망
- 5-Fold Cross Validation, Stacking 실험
- PyTorch, Scikit-learn 활용

✅ **대시보드 구현**  
- Streamlit으로 질환별 발생 확률 및 변수 중요도 시각화
- 사용자 CSV 업로드 → 실시간 예측 결과 제공
