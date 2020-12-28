# kmeans_segmentation
___________________________________________________________________________________
        Image Segmentation은 computer vision에서 매우 중요하고 활발히 연구
       가 진행되고 있는 분야이다. 본 연구에서는 K-Means Clustering을 이용해
       Image Segmentation 데이터셋에서 각 클래스를 대표하는 RGB 값을 찾아내
       는 것, K-Means Clustering을 거친 layer로부터 사용자가 정의한 RGB값으로
       새롭게 labeled data를 생성하는 것을 진행하였다. 이에 Cityscapes Image P
       airs Dataset을 이용해 13개의 클러스터로 K-Means Clustering을 진행해 클
       래스를 구분하였고, 사용자가 정의한 RGB값으로 새롭게 labeled data를 생성
       할 수 있는 툴을 개발하였다. 또한 Semantic Segmentation 모델을 거친 후
       생성 된 마스킹 된 이미지를 통해 원하는 클래스 부분에 해당하는 마스크를
       K-Means 클러스터링을 이용해 높은 정확도로 생성할 수 있었다. 본 연구를 
       통해 Image Segmentation 데이터 전처리, 학습결과 분석 전반에 비지도 학습
       방법인 K-Means Clustering이 매우 유용함을 확인하였다.
______________________________________________________________________________________
 

![research_purpose](https://user-images.githubusercontent.com/67684178/103220665-36360800-4964-11eb-94e4-f187985ff258.PNG)
