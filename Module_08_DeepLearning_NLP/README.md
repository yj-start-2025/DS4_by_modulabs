## Module 08 : DeepLearning & NLP
- 1일차 : 딥러닝 예시, 미니프로젝트 제출
- 2일차 : 텐서 소개, 딥러닝 모델 구조 정의 및 학습
- 3일차 : 모델 저장, 로드, 콜백, early-stopping, L1/L2규제, 가중치 초기화, 배치 정규화
- 4일차 : Boston주택가격, Reuters기사분류, CIFAR-10 MLP 적용하기
  - CIFAR-10 : MLP로는 test_set의 accuracy가 0.5 달성도 어려움(CNN이 나음)
    - MLP : loss 1.4466, accuracy 0.4807
    - CNN 실험결과 요약

| 실험 | 주요 특징                           | Test Loss | Test Accuracy |
|------|------------------------------------|-----------|----------------|
| 1    | Conv2D(32)-MaxPool-FC              | 1.210     | 0.580          |
| 2    | Conv2D(64)-Dropout(0.3)-FC         | 0.980     | 0.640          |
| 3    | Conv2D(64)-BatchNorm-ReLU-GlobalAvgPool | 0.850     | 0.690          |
| 4    | Data Augmentation + CNN            | 0.800     | 0.720          |

## 참고사항
- 현재 KDT 교육과정에는 CNN으로 이미지 처리하는 것은 다루지 않음
- 조별 study인 'wrap-up'때 CNN 관련 발제 6/22
  
## 작성자
- yj-start-2025
