## 임요한 교수님
### 교재: An Introduction to Statistical Learning


-------


__Chapter 3. Regression__


------


- 회귀분석 I (1/2): 단순선형회귀, 중회귀분석

- 회귀분석 I (2/2): 잔차분석 및 모형진단

------

__Chapter 4. 분류: Bayes Classifier__

- K-NN, Logistic regression, linear discriminant analysis, confusion matrix
- tree model, random forest, boosting, SVM

------

__Chapter 5. 재추출 방법들__

- Cross Validation(CV), Leave-one-out CV(LOOCV), Bootstrap

------

__Chapter 6. 선형모델 선택 및 Regularization__
목적: 설명을 잘하고 에측을 잘하는 모형을 선택하기 위한 방법을 알아본다.

- 최상의 서브셋 집합

:2^p 이 모델이 생기는 단점으로 변수선택법의 등장

- 전진, 후진, 단계적 변수선택법

: 전진 선택법은 n<p여도 가능

- 최적모델 선택: Cp, AIC, BIC, AdgustedR^2

: BIC는 n>7 모델에 더심한 패널티를 

- Ridge, Lasso Regression

: 예측이 뛰어난 반면 변수 선택이 불가한 Ridge의 보완책으로 Lasso를 사용

------

__Chatper 7. 비선형함수추정__  
목적: 더 유연하게 적합해보자

명령어 위주로 알아보기.

1. 다항회귀  
2. 계단함수  
3. 회귀 스플라인  
4. 평활 스플라인: 1:1 대응만 가능    
5. 국소회귀: span의 가장 중요  교호작용 X
6. 일반화가법모형(GAM)  


------


__Chatper 9. SVM__  
목적: 이진분류(vs 로지스틱)  
조건: Linear Seperable 하다  
idea: 차원을 증가시켜 Linear sperable하게 
개념: Hyperplane, support vector, 

1. maximal margin classfier

2. support vector classfier

3. SVM

----


__Chapter 10. 비지도학습__

1. 군집화


- initial에 따라 결과과 다른 경향  
- EDA과정 중 하나로 사용 

1-1. K-means 클러스터링    
1-2. 계층군집화: 3가지 하위모델이 결과가 다른 단점


2. PCA(주성분분석)
목적: p개 변수의 차원을 낮추자  
Keyword: loading, score  
- 관측치를 선분에 사영시켜 분산를 최대로 만들자   
