# PCA와 MNIST 데이터셋 분석

이 주피터 노트북은 주성분 분석(PCA)을 MNIST 손글씨 숫자 데이터셋에 적용하는 과정을 단계별로 설명합니다.

## 개요

이 프로젝트는 다음과 같은 내용을 다룹니다:

1. MNIST 데이터셋 로드 및 전처리
2. 원본 이미지 시각화
3. PCA 적용
4. 설명된 분산 비율 분석
5. 이미지 재구성
6. 주성분 시각화
7. 2D로 축소된 데이터 시각화

## 요구사항

이 노트북을 실행하기 위해 다음 라이브러리가 필요합니다:

- numpy
- matplotlib
- scikit-learn

## 설치 방법

1. 이 저장소를 클론합니다:
   ```
   git clone https://github.com/yourusername/pca-mnist-analysis.git
   ```

2. 필요한 라이브러리를 설치합니다:
   ```
   pip install numpy matplotlib scikit-learn
   ```

## 사용 방법

1. Jupyter Notebook을 실행합니다:
   ```
   jupyter notebook
   ```

2. 브라우저에서 `PCA_MNIST_Analysis.ipynb` 파일을 엽니다.

3. 노트북의 각 셀을 순서대로 실행합니다.

## 주요 결과

이 노트북을 통해 다음과 같은 결과를 얻을 수 있습니다:

- MNIST 데이터셋의 차원 축소
- 주성분의 시각화 및 해석
- 차원 축소 후 데이터 재구성의 품질 평가
- 2D 공간에서의 데이터 분포 시각화
