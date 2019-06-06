# 모두를 위한 인공지능의 활용(2019-1)

----------------------------------------------------------
# Team Project 15조 : (Darknet YOLO tensorflow version) "DarkFlow"
21700748 최지호, 21900556 이재민

## 프로젝트 개요
____________________________________________
## Darknet YOLO tensorflow version "DarkFlow"에 대하여
--------
+ Darket Yolo는 수업시간 ted강의로 나왔던 주제입니다. C와 CUDA로 작성된 오픈 소스 신경망 프레임 워크이며, 빠르고 설치가 쉽고 CPU 및 GPU계산을 지원하고 있습니다.

+ 그렇지만 매우 강력한 오픈 소스 신경망 프레임 워크인 Darknet YOLO는 CUDA를 사용하기 때문에 NVIDIA사의 그래픽이 없는 컴퓨터는 CUDA를 사용할 수 없다는 점이 있었고

+ 원 저자는 C를 이용하여 프로그램을 짰기 때문에, Tensorflow의 Tensorvboard와 같은 유용한 기능들을 사용할 수 없는 점이 있습니다. 그래서 어느 개발자가 TensorFlow 버전 YOLO인 DarkFlow를 개발하여 오픈소스로 공개하였고 python 기반으로 작성을 했습니다!

------

## 프로젝트의 목적
MAC OS에서도 darknet yolo를 구동 할 수 있어 본 프로젝트는 "MAC OS" 환경의 터미널에서 "Darkflow 설치 및 실행해보기" 입니다.

+ 프로젝트를 통해

 1. Darkflow 개발환경 설치
 2. Darkflow 돌려보기
 3. 모델 및 여러가지 제공 명령어 학습
 4. VOC로 Yolo 학습시키는 법,
 5. 객체 탐지 예제 실행해보기(사진 & 실시간 웹캠) with threshold

을 해보았습니다.

-----------------------------

  동영상: [동영상 설명서](https://www.youtube.com/watch?v=yxQGlMLegcs&feature=youtu.be)

  블로그: [포스팅 블로그](https://blog.naver.com/co748/221554688233)

  ppt파일: [Darknet_Yolo_Tensorflow.pptx](https://github.com/idebtor/JoyAI/blob/master/projects/15%EC%A1%B0/Darknet_Yolo_Tensorflow.pptx)

  코드: 해당 블로그 주소 포스팅을 통해 git clone이 가능합니다.

  -----------------------------------

# Team Project 9조

홍유빈(21500804) / 이수지(21800528) / 김영민(21900141)

## <프로젝트 링크>

[Kaggle Project Link](https://www.kaggle.com/cdabakoglu/heart-disease-classifications-machine-learning/notebook)

## <프로젝트 계기>

전공과의 연관성을 살려, 생명분야에서 인공지능이 사용되는 사례를 조사하고자 하였다.
지금까지 배웠던 많은 내용들을 포괄할 수 있는 주제를 선정하고자 하였다.

## <프로젝트 개요>

1. Heart desease.csv 데이터를 분석한다.
2. Logistic Regression Algorithm을 포함한 다른 Algorithms(KNN , SVM , naive bayes , decision tree, random forest + confusion matrix)을 이용해서 heart disease를 예측해본다.
3. 만든 모델들을 Accuracy와 Confusion Matrix를 이용해서 비교 후 최선의 모델이 무엇인지 찾아낸다.

## <발표자료>

[script.ipynb](https://github.com/idebtor/JoyAI/tree/master/projects/9%EC%A1%B0-%EC%8B%AC%EC%9E%A5%EC%A7%88%ED%99%98(LogisiticRegression))

[보충자료.docx](https://github.com/idebtor/JoyAI/tree/master/projects/9%EC%A1%B0-%EC%8B%AC%EC%9E%A5%EC%A7%88%ED%99%98(LogisiticRegression))

* 동영상은 나누어 제작(1편, 2편)
[동영상 설명 1](https://youtu.be/ODGJN-cBx7Q)
[동영상 설명 1](https://youtu.be/cgOMwMOXBX8)

---------------------------------

# Team Project 18조 - 블록체인을 이해하고 간단한 블록체인 코어를 구현해보기

최혁진(21900771)
-------------------------------

## <프로젝트 소개>
화폐의 원래 개념과, 은행에서의 transaction vs. 블록체인의 transaction원리를 비교해 보고 블록체인의 코어를 코딩해보고 구동해보는 것입니다.



## <다루게 될 기술>
hashlib
json
파이썬
class 함수

## <프로젝트 개요>
class를 통해 블록에 거래내역 (nonce, Tstamp, transaction, prevhash)을 부여한다

hashlib과 json을 import해 블록의 거래내역을 암호화 한다 (sha.256사용)

class를 이용해 Genesis블록과 블록체인을 구현한다

for range를 이용해 블록이 손상됬을 경우 블록이 체인에 추가되지 못하도록 한다

블록체인 구현을 한것을 임의로 만든 것과, 그 만든 것의 데이터를 조작 (해킹)한 후 블록이 쓰일 수 있는 블록인지 (True) 쓰일 수 없는 블록인지 (Invalid, False) 구분한다


<동영상 링크>
https://www.youtube.com/watch?v=EA4dXhY91a8&feature=share

21900771_최혁진_Block_Chain_.ipynb

21900771_최혁진__미래의_화폐로서의_가능성_블록체인.pptx

--------------------------------------------------

# Team Project 12조 - 파이션을 이용해 Neraul Style Network 구현하기

### < 프로젝트 소개 >

  - 일반 사진을 유명 화가의 그림같이 보이게 한다
--------------------------------------------------------

# <프로젝트 개요>
- Neural Style Transfer에 대해 알아보기

- 이미지의 스타일을 학습하기

- 학습한 스타일을 바탕으로 Neural Style Transfer 구현하기

# <프로젝트>

----------------------------------
_piazza_clz_md_2009_piazza_clz_md_2009

CoreAAC_DirectShow_Filter.exe

StyleTranfer_소개.docx

Neural_Style_Transfer_with_Eager_Execution.ipynb

(sound track is not good)
동영상 1 : https://piazza.com/class/jsflt1hhzmp45n?cid=335
동영상 2 : https://piazza.com/class/jsflt1hhzmp45n?cid=335

--------------------------------------------

Team Project 14 - keras와 flask web server를 활용한 타이타닉호 생존자 분석 및 예측 프로그램

정혜윰(21700680)/이원빈(21900608)
---------------------------
## 프로젝트 개요

1912년 침몰한 타이타닉호 생존 가능성 예측 프로그램입니다.

타이타닉호의 탑승자들의 데이터를 받고 정보에 따라 분석해서, keras로 학습합니다. 플라스크 웹 서버에 접속하고 안내를 따라 이름, 성별, 나이, 탑승 호실 등급, 동승자 등의 정보를 입력하면  타이타닉 호 침몰 시 해당 사람의 생존 가능성을 계산하여 알려줍니다.

## github 주소
https://github.com/hyeyoomj/TitanicSurvivor

(비디오 용량이 너무 커서 링크로 업로드합니다)
## Video 1
데이터 분석 및 학습하기 튜토리얼
https://youtu.be/NgRdTigDO3o
https://www.youtube.com/watch?v=NgRdTigDO3o&feature=youtu.be

## Video 2
학습 모델 플라스크 웹 서버와 연동하기 튜토리얼
https://youtu.be/Vl6cupU0MKM

## 자료 및 코드파일
TitanicSurvivormaster.zip

----------------------------------------------------



## Optional [심화 학습과 텐서플로루 특강 Tensorflow and deep learning](https://www.youtube.com/watch?v=vq2nnJ4g6N0)
  - Speaker: Devoxx
  - 2:35:52
  - 영어 + 영어 자막

  _One thing I know, I was blind but now I see. John 9:25_