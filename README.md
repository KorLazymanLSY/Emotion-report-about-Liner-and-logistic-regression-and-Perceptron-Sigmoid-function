# Emotion-report-about-Liner-and-logistic-regression-and-Perceptron-Sigmoid-function
수치예측:1. 선형회귀 2.손실함수,경사하강법

1.선형회귀:  ![img](file:///C:\Users\HJAN\AppData\Local\Temp\DRW00002100bd6c.gif)  

b는 양수로서 기울기를 조정하다가 분산되어있는 값들이 최소한의 거리가 되는 값을 찾고,

X,Y의 값의 관계를 가장 비슷하게 찾아내어 정리하는 2차원의 가장 간단한 함수입니다.

  ![그림입니다.  원본 그림의 이름: CLP00002100bd47.bmp  원본 그림의 크기: 가로 283pixel, 세로 283pixel](file:///C:\Users\HJAN\AppData\Local\Temp\Hnc\BinData\EMB00002100bd48.bmp)  

\2. 손실함수:손실함수는  오차를 나타내는 방법중 하나로서 인공 신경만 학습의 목표로서 이 함수의 결과값을 최소로 하는 방법이다. 아래는 손실함수중 하나인 평균제곱오차이다. 이를 통하여 기울기를 수정한다.

  ![img](file:///C:\Users\HJAN\AppData\Local\Temp\DRW00002100bd6e.gif)  

3.경사하강법: 아까 상술하였듯이 신경망 학습의 최종 목표는 손실함수의 결과값이 최소로 나타나는 값을 찾는것이고,이차 함수의 그래프로 나타나게 된다. 이때 이차함수의 최솟값일 찾아내는 것이 목적이다, 즉 경사를 조금씩 하강시켜서 찾기에 자취가 이차함수처럼 나타난다.

  ![img](file:///C:\Users\HJAN\AppData\Local\Temp\DRW00002100bd70.gif)  

  ![그림입니다.  원본 그림의 이름: CLP000021000004.bmp  원본 그림의 크기: 가로 825pixel, 세로 155pixel](file:///C:\Users\HJAN\AppData\Local\Temp\Hnc\BinData\EMB00002100bd54.bmp)  

이진분류:1.퍼셉트론 2.로지스틱 회귀 3.Sigmoid Function

퍼셉트론:생물 신경계에서 아이디어를 따와서 만든 방법으로서 신경계처럼 여러 신호를 받아서 가중치를 증가시키고  일정한 세타값을 넘을시 1을 반환하고 그 미만이면 0,-1을 반환한다.  ![그림입니다.  원본 그림의 이름: CLP000021000005.bmp  원본 그림의 크기: 가로 650pixel, 세로 437pixel](file:///C:\Users\HJAN\AppData\Local\Temp\Hnc\BinData\EMB00002100bd5d.bmp)  

\2. 로지스틱 회귀:로지스틱회귀는 일반적인 선형 함수를 사용하지 못할시(두가지중 택 1)에 사용하는 회귀이며 함수식은   ![img](file:///C:\Users\HJAN\AppData\Local\Temp\DRW00002100bd72.gif)  의 형태로 나타나게 된다.  이 로지스틱 회귀의 식은 그림을 수식으로 표현하려 만든 식이므로 그래프의 개형에 더 집중하도록 하자. ![그림입니다.  원본 그림의 이름: CLP000021000006.bmp  원본 그림의 크기: 가로 405pixel, 세로 316pixel](file:///C:\Users\HJAN\AppData\Local\Temp\Hnc\BinData\EMB00002100bd60.bmp)  

\3. 시그모이드 함수:활성화 함수중에 하나이며 위의 로지스틱 회귀또한 시그모이드 함수의 일종이다. 시그모이드 함수는 0또는 1의 함수값을 만들어서 데이터를 분류한다. 즉 이진 분류를 하여 데이터를 판별한다.

​    
