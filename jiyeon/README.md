
# 머신러닝 이론

## 회귀와 분류의 공통점과 차이점

> 가장 큰 차이점은 연속성!

1. 회귀 (Regression)
연속적인 숫자, 또는 부동소수점수 (실수)를 예측하는 것. 주식 가격을 예측하여 수익을 내는 알고 트레이딩 등이 이에 속한다. 

2. 분류 (Classification)
미리 정의된, 가능성 있는 여러 <u>클래스 레이블(class label)</u> 중 하나를 예측하는 것. 얼굴 인식, 숫자 판별 등이 이에 속한다.
- 이진 분류 (binary classification) : 두개로만 나뉨. 한 클래스를 양성(positive), 다른 하나를 음성(negative) 클래스라고 한다. 
- 다중 분류 (multiclass classifiaction) : 셋 이상의 클래스로 분류

---

## 선형 회귀(Linear Regression)란?
어떤 변수에 다른 변수들이 주는 영향력을 <u>선형적으로 분석</u>하는 대표적인 방법.

### 선형 회귀 분석을 하는 방법
1. 선형 회귀 모델 (linear regression model) 만들기
여기서 말하는 모델은 수학 식으로 표현되는 함수를 말한다. 영향을 주는 변수와 영향을 받는 변수로 구성되어 있다. 영향을 주는 변수는 <u>독립 변수(independent variable) 또는 설명 변수(explanatory variable)</u> 등으로 불리며 영향을 받는 변수는 <u>종속 변수(dependent variable) 또는 반응 변수(response variable)</u> 등으로 불린다.

### 독립 변수의 개수에 따른 선형 회귀 모델
1. 독립 변수가 1개일 때 - 단순 선형 회귀 모델 (Simple Linear Regression)
 Y=β0+β1X+ϵ

2. 독립 변수가 n개일 때 - 다중 선형 회귀 모델 (Multiple Linear Regression)
 Y=β0+β1X1+…+βnXn+ϵ

### 최적의 계수를 찾는 방법 - LSE
> LSE (Least Square Estimation)
error 제곱이 최소화가 되도록 계수를 찾는 방법!


---
## 정규화의 방법

### 1. L1 Regularization
정규화의 일종. 모델 가중치의 L1 norm(가중치 각 요소 절대값의 합)에 대해 패널티를 부과한다. 대부분의 요소값이 0인 sparse feature에 의존한 모델에서 L1 정규화는 불필요한 

---

# NN

## 신경망이란?


---

# Reference
- <https://ddanggle.github.io/LearningHowToCodeNeuralNetworks>
