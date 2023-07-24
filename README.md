# Bootcamp_DeepLearning
 플레이데이터 부트캠프 데이터 엔지니어링 과정 - **딥러닝** 강의 파일, 복습파일 등을 저장한 `repo` 입니다.
 <br><br>

# 가상 환경
 - 딥러닝은 계산이 매우 복잡하여 CPU 하나로 계산하기엔 너무 오래 걸리기 때문에 **"GPU"** 의 존재가 필요하다.
 - 따라서 머신러닝의 가상환경이었던 Jupyter notebook이 아닌 `Colab`을 사용합니다.
 - Colab에서는 무료로 GPU를 제공하여 학습하는데 문제없이 사용이 가능합니다.
 - 그러나 강의 자료의 이미지 파일이 Colab에서는 깨져서 나오고, Jupyter notebook에서는 문제없이 출력됩니다.
 - 따라서 **실행은 `Colab`에서** 하고, **강의 내용-이론 학습은 대부분 `Jupyter notebook` 에서** 진행합니다.

## Tensorflow 설치
`pip install tensorflow`
<br>Jupyter notebook cell 에서 -> `!pip install tensorflow`

## Colab 사용 (ex..CNN model,...)
- `CNN(Convolution Neural Network)` 학습부터 연산량이 상당히 많기 때문에
- 많은 Epoch 수를 설정할수록 시간이 오래 걸린다.
- 따라서, **`Colab`** 환경에서, GPU를 사용해서 해당 시간을 줄여준다.
