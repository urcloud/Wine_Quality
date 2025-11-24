# 적색 와인 품질 예측 프로젝트

## 목표
본 프로젝트의 목표는 적색 와인의 특성을 바탕으로 품질 점수를 예측할 수 있는 심층 신경망 모델을 구축하고, 이를 단계적으로 발전시켜 최적화하고, 높은 일반화 성능을 보이는 모델을 개발하는 것입니다.

## 설명
타깃 변수인 품질은 평가를 통해 부여된 3~8 사이의 정수형 점수로, 와인의 품질 수준을 나타냅니다. 이러한 특성에 따라 본 프로젝트는 품질 점수를 예측하는 회귀 문제로 정의됩니다. 모델은 총 11개의 특성을 입력 변수로 사용하여 품질 점수를 예측하도록, DNN 모델의 성능 향상 과정 자체에 초점을 맞춰 진행되었습니다.

## 데이터셋 개요
출처: Kaggle “Red Wine Quality” 데이터셋
https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009/data

표본 수: 1,599개의 적색 와인 샘플

입력 변수(feature):
* fixed acidity (고정 산도)
* volatile acidity (휘발성 산도)
* citric acidity (구연산 함량)
* residual sugar (잔류 당분)
* chlorides (염화물 함량)
* free sulfur dioxide (유리 이산화황)
* total sulfur dioxide (총 이산화황)
* density (밀도)
* pH (산도)
* sulphates (황산염 함량)
* alcohol (알코올 도수)

출력 변수(target):
* quality(품질)