# 자동차 이미지를 학습 및 시험하기 위한 데이터입니다.

훈련 데이터는 총 1,920장으로 이루어져있고
시험 데이터는 총 480장으로 이루어져있습니다.

이미지를 각 카테고리별 라벨링 했으며 코드는 다음과 같습니다.
0 = sedan, 1 = sportscar, 2 = suv, 3 = truck

# 합성곱 신경망 구조입니다.

총 4개의 계층으로 이루어져있고
3개의 Conv - ReLU - Pool - Bn,
1개의 Flat - Affine - Softmax로 이루어져 있습니다.
[![NNN](/47406388/69895516-a4308a00-1374-11ea-9b59-c6f0597e71d4.jpg)](https://user-images.githubusercontent.com/)

# References
1. Cars Dataset, Stanford Univ. 2013 
(https://ai.stanford.edu/~jkrause/cars/car_dataset.html)

2. Namin Neural Network, Min Woo Na. 2019
(https://github.com/roqhdehd502/Namin-Neural-Network)
