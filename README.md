# DeepLearningZeroToAll Season1 tutorial (Tensorflow 1.14.0)

- 이 장에서는 모두를 위한 딥러닝 시즌1의 튜토리얼을 다루었다. 코드를 구현해봄으로써 전반적인 코드의 원리들을 파악하고 부차적으로 발생하는 오류들을 수정하였다. 기계학습 수업 시간에 배운 MLP를 CNN, RNN(+LSTM) 등으로 직접 구현해보았고, Activation function, Backpropagation, optimizer 등으로 학습을 시켜봄으로써 개념과 실습을 연결할 수 있었던 유용한 경험이었다. 한 가지 아쉬운 점은 tensorflow version 1.14를 다루었기에, 현재 안정화 버전이 나온 tensorflow 2.0으로 구현해보았더라면 하는 것이었다. 모두의 딥러닝 시즌2에서 2.0을 다루고 있으므로 이후 공부할 예정이다. 배웠던 수학 개념들이 코드 한 줄로 완성되는 점이 인상깊었고, hyper parameter 설정을 위한 수학 개념 복습이 필요함을 인지하였다.

### Course Contents
1. 머신러닝의 개념과 용어
2. Linear Regression 의 개념
3. Linear Regression cost 함수 최소화
4. 여러개의 입력(feature)의 Linear Regression
5. Logistic (Regression) Classification
    - Hypothesis 함수 소개, Cost 함수 소개, TensorFlow 에서의 구현
  
6. Softmax Regression (Multinomial Logistic Regression)
    - Multinomial 개념 소개, Cost 함수 소개
    - Lab1: TensorFlow에서의 구현, Lab2: TensorFlow에서의 Fancy한 구현
  
7. ML의 실용과 몇가지 팁
    - 학습 rate, Overfitting, 그리고 일반화 (Regularization), Training/Testing 데이타 셋
    - Lab 1: TensorFlow에서의 구현 (학습 rate, training/test 셋으로 성능평가), Lab 2: Meet MNIST dataset
  
8. 딥러닝의 기본 개념과, 문제, 그리고 해결
    - 딥러닝의 기본 개념: 시작과 XOR 문제, 딥러닝의 기본 개념2: Back-propagation 과 2006/2007 '딥'의 출현
    - Lab : Tensor Manipulation
  
9. Neural Network 1: XOR 문제와 학습방법, Backpropagation (1986 breakthrough)
    - XOR 문제 딥러닝으로 풀기, 특별편: 10분안에 미분 정리하기, 딥넷트웍 학습 시키기 (backpropagation)
    - 실습1: XOR을 위한 텐스플로우 딥넷트웍, 실습2: Tensor Board로 딥네트웍 들여다보기
  
10. Neural Network 2: ReLU and 초기값 정하기 (2006/2007 breakthrough) 
    - XSigmoid 보다 ReLU가 더 좋아, Weight 초기화 잘해보자, Dropout 과 앙상블, 레고처럼 넷트웍 모듈을 마음껏 쌓아 보자
    - 실습: 딥러닝으로 MNIST 98%이상 해보기
  
11. Convolutional Neural Networks
    - ConvNet의 Conv 레이어 만들기, ConvNet Max pooling 과 Full Network, ConvNet의 활용예
    - 실습1: TensorFlow CNN 의 기본, 실습2: TensorFlow로 구현하자 (MNIST 99%), 실습3: Class, tf.layers, Ensemble (MNIST 99.5%)
  
12. Recurrent Neural Network 강의 슬라이드  실습 슬라이드 
    - NN의 꽃 RNN 이야기 비디오 
    - 실습1: RNN의 기본 비디오, 실습2: Hi Hello RNN Traning 비디오 , 실습3: Long Sequence RNN 비디오,
    - 실습4: Stacked RNN + Softmax Layer 비디오, 실습5: Dynamic RNN 비디오, 실습6: 타임시리즈 RNN
