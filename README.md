# Steady-State-Detection
APC 모델링 자동화를 위한 Steady-State-Detection

## 1. 실행환경: 아나콘다 Jupyter Notebook

## 2. 실행방법: Steady State Detector.ipynb 파일을 아나콘다 Jupyter Notebook으로 실행한 후 Cell 실행

## 3. 코드설명: 
a. 우선 Steady State Detect에 앞서 Nonlinear한 모델을 Linear하게 바꾸는 과정을 먼저 진행한다.
b. Linear하게 바꾸는 과정에서 Particle Filtering을 한다. 코드에 number_particles는 filtering을 하기 위한 particles의 수이다. 이 수가 늘어나면 연산시간이 증가한다.
c. Linear하게 만든 모델에서 Steady-State-Detection을 진행한다. a-c까지의 과정을 model.train에서 진행한다. 연산시간이 매우 오래 걸린다.

