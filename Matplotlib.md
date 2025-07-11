# 📝 Matplotlib 레포트 작성하기
- [1. Matplotlib란?](#1-Matplotlib란)
- [2. Matplotlib 개요](#1-Matplotlib란)
- [3. Matplotlib의 기본 구조](#3-Matplotlib의-기본-구조)
- [4. 기본 그래프 그리기](#4-기본-그래프-그리기)
- [5. 그래프 요소 추가 및 커스터마이징](#5-그래프-요소-추가-및-커스터마이징)
- [6. 서브플롯과 여러 그래프 그리기](#6-서브플롯과-여러-그래프-그리기)
- [7. Matplotlib 코드베이스는 어디에 있나요?](#7-Matplotlib-코드베이스는-어디에-있나요)
- [8. Matplotlib을 colab에서 직접 실습해보면서 공부하기](#8-Matplotlib을-colab에서-직접-실습해보면서-공부하기)

## 1. Matplotlib란?
- Matplotlib은 시각화 유틸리티 역할을 하는 파이썬의 **저수준 그래프 플로팅 라이브러리**입니다.
- Matplotlib은 John D. Hunter가 만들었습니다.
- Matplotlib은 오픈 소스이므로 자유롭게 사용할 수 있습니다.
- Matplotlib은 대부분 Python으로 작성되었으며, 일부 부분은 플랫폼 호환성을 위해 C, Objective-C 및 Javascript로 작성되었습니다.
- ![image](https://github.com/user-attachments/assets/7f505fd0-2981-40fa-8691-b0b24f4497ce)

## 2. Matplotlib 개요
- Matplotlib은 파이썬에서 데이터를 시각적으로 표현하기 위해 개발된 대표적인 오픈 소스 라이브러리입니다.
- 2003년 John D. Hunter에 의해 개발되었으며, 현재는 데이터 과학, 통계 분석, 공학, 자연과학 등 다양한 분야에서 널리 사용되고 있습니다.
- Matplotlib은 선 그래프, 막대 그래프, 산점도, 히스토그램, 파이 차트 등 다양한 2D 그래프를 지원하며, 일부 3D 그래프도 그릴 수 있습니다.
- 무엇보다 자유도 높은 커스터마이징 기능과 다른 데이터 분석 라이브러리(pandas, NumPy 등)와의 뛰어난 호환성이 큰 장점입니다.

## 3. Matplotlib의 기본 구조
- Matplotlib은 크게 **Figure, Axes, Axis**라는 세 가지 핵심 구성 요소로 이루어져 있습니다.
- **Figure**는 전체 그래프의 틀을 의미하며, 하나의 Figure 안에 여러 개의 Axes(서브플롯)를 배치할 수 있습니다.
- **Axes**는 실제로 그래프가 그려지는 영역으로, x축과 y축이 포함됩니다.
- **Axis**는 각 축(예: x축, y축) 자체를 의미하며, 눈금, 레이블 등 세부 요소를 포함합니다.
- pyplot 모듈은 MATLAB과 유사한 함수형 인터페이스를 제공해, 간단한 코드로 빠르게 그래프를 그릴 수 있게 도와줍니다.

## 4. 기본 그래프 그리기
- Matplotlib에서는 다양한 그래프 유형을 지원합니다.
- **선 그래프(plot)**: 시계열 데이터, 연속적인 변화 등을 표현할 때 사용합니다.
- **산점도(scatter)**: 두 변수 간의 상관관계나 분포를 시각화할 때 유용합니다.
- **막대 그래프(bar)**: 범주형 데이터의 값을 비교할 때 자주 사용됩니다.
- **히스토그램(hist)**: 데이터의 분포와 빈도를 확인할 때 효과적입니다.
- **원 그래프(pie)**: 전체 대비 각 부분의 비율을 시각적으로 보여줍니다.
- 각 그래프는 함수 한 줄로 그릴 수 있으며, 데이터의 특성과 목적에 맞게 적절한 그래프를 선택하는 것이 중요합니다.

## 5. 그래프 요소 추가 및 커스터마이징
- Matplotlib은 그래프의 세부 요소를 매우 자유롭게 설정할 수 있습니다.
- 제목, 축 레이블, 범례 등은 각각 **plt.title(), plt.xlabel(), plt.ylabel(), plt.legend()** 함수로 추가할 수 있습니다.
- **색상, 마커, 선 스타일, 투명도** 등 시각적 요소도 함수 인자를 통해 지정할 수 있습니다.
- 폰트 크기, 눈금 간격, 배경색 등도 세밀하게 조정할 수 있어, 발표 자료나 논문 등 다양한 목적에 맞는 시각화가 가능합니다.

## 6. 서브플롯과 여러 그래프 그리기
- 하나의 Figure 내에 여러 개의 Axes(서브플롯)를 배치하면, 여러 그래프를 한 화면에 동시에 표현할 수 있습니다.
- **plt.subplot()** 또는 **plt.subplots()** 함수를 이용해 원하는 형태(행, 열)의 서브플롯을 만들 수 있습니다.
- 이 기능은 여러 데이터셋을 한 번에 비교하거나, 다양한 시각화를 동시에 보여줄 때 매우 유용합니다.

## 7. Matplotlib 코드베이스는 어디에 있나요?
- https://github.com/matplotlib/matplotlib

## 8. Matplotlib을 colab에서 직접 실습해보면서 공부하기
- [Matplotlib_기본_응용](./Matplotlib_기본_응용.ipynb)
- [Matplotlib_기본_응용2](./Matplotlib_기본_응용2.ipynb)
- [Matplotlib_기본_응용3](./Matplotlib_기본_응용3.ipynb)
