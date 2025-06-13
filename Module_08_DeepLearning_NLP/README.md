## Module 08 : DeepLearning & NLP
- 1일차 : 딥러닝 예시, 미니프로젝트 제출
- 2일차 : 텐서 소개, 딥러닝 모델 구조 정의 및 학습
- 3일차 : 모델 저장, 로드, 콜백, early-stopping, L1/L2규제, 가중치 초기화, 배치 정규화
- 4일차 : Boston주택가격, Reuters기사분류, CIFAR-10 MLP 적용하기
  - CIFAR-10 : MLP로는 test_set의 accuracy가 0.5 달성도 어려움(CNN이 나음)
    - MLP : loss 1.4466, accuracy 0.4807
    - CNN 실험결과 요약 

| 실험 | 주요 특징                           |          Test Loss | Test Accuracy |
|------|------------------------------------|-----------|----------------|
| 1    | 기본적인 CNN 구조 적용               | 0.8940     | 0.7042         |
| 2    | 데이터 증강, CNN-layer 깊이 더 깊게   | 0.7393     | 0.8025         |
| 3    | 분류기(Classifier) 부분 강화, 학습률 스케줄러 | 0.2759  | 0.9049       |
| 4    | 전이학습 EfficientNetB0            | 0.2349     | 0.9228          |

- 5일차 : NLP

## 참고사항
- 현재 KDT 교육과정에는 CNN으로 이미지 처리하는 것은 다루지 않음
- 조별 study인 'wrap-up'때 CNN 관련 발제 6/22
  
## 작성자
- yj-start-2025
