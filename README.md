# 5분 실습: loss가 내려가는 것을 직접 본다

《내가 다시 AI를 처음 공부한다면》 2장의 실습 노트북입니다.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Gumini-Research/loss_curve_5min/blob/main/loss_curve_5min.ipynb)

## 하는 법

위의 **Open in Colab** 버튼을 누르고, 열린 노트북에서 셀마다 실행 버튼(▶)을 위에서부터 차례로 누르면 됩니다. 설치할 것도, 준비할 것도 없습니다. 전부 합쳐 5분이면 끝납니다.

## 보게 되는 것

- 작은 신경망이 손글씨 숫자(MNIST) 6만 장을 학습하는 동안 **loss 곡선이 실시간으로 내려가는 장면**
- 보폭(learning rate)을 100배로 키웠을 때 **같은 모델이 학습에 실패하는 장면**

지금은 코드가 안 읽혀도 괜찮습니다. 책의 3장에서 이 곡선을 움직이는 수학을, 5장에서 이 루프의 구조를, 6장에서 진짜 GPT의 곡선을 만나게 됩니다.

## 데이터 출처

MNIST 손글씨 숫자 데이터셋 (Y. LeCun, C. Cortes, C. Burges) · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/)
이 저장소는 데이터를 포함하지 않으며, 노트북 실행 시 공식 배포처에서 내려받습니다.

## 라이선스

이 저장소의 코드는 [MIT License](LICENSE)를 따릅니다.
