---
title: "CV for PUBG"
date: 2019-09-11 15:11:00 -0400
categories: CV
---

## 지원자 정보

이름 : 박기남

전화번호 : 010-7704-5824

E-mail : parkinam321@gmail.com(parkinam321@kaist.ac.kr)

## 학력

### 학과정

학교 : KAIST

전공 : 전기 및 전기공학과 전공, 전산학과 부전공(*전산학부 전공 38/42학점 수료. 42학점 부터 복수전공*)

GPA : 3.46/4.3

### 석사과정

학교 : KAIST

전공 : 전산학과

연구실 : CDSNLAB([Page link](http://cds.kaist.ac.kr/))

연구분야 : Data science, Urban computing, Machine learning

## 기술

C, Java, Python, R 기반 언어 사용(Python, R 관련 경험 다수)

Feature Engineering

Python, Jupyter notebook 기반 데이터분석 및 시각화.

NLP(Word embedding, Topic modeling)

Pytorch기반 Deeplearning(CNN, GCGAN, Masked R-CNN)

Instagram web crawler 구현경험

MongoDB, Mysql 사용경험

Javascript를 활용한 front-end 개발경험

Django 기반 back-end 개발경험

## (수상)경력

### ICDM2019 1st author submission(Marginal rejected, under revision)

*Title* : A Placeness Mining Scheme to Infer Land Use and Estimate Its Evolving Changes from Instagram Data

*Abstract* : 서울 지하철 2호선 역세권 내의 축적된 Instagram data로부터 사회활동(social activity)을 식별하고, 식별된 사회적 활동을 이용하여 역세권의 토지사용(landuse)을 추론(inference)하는 Place Mining Scheme을 구축하였다. 또한 연도별 분석을 통해  토지사용의 연도별 변화가 어떤 형태로 사회적 활동에서 탐지(detect)되는지 확인하였다. 

*Methodology* : MS Congitive Service API를 통해 각 이미지에 대한 설명문장을 만들고 Word2Vec을 적용하여 비슷한 context를 지닌 단어끼리 묶이도록 임베딩 하였고 이를 사회활동으로 규정하였다. 이후 Spectral clustering을 통해 묶인 사회활동들을 MTurk survey를 통해 명확한 사회활동으로 규정하고 이에 MLPRegressor를 적용하여 landuse를 추론하는 scheme를 구현하였다. 이 scheme은 baseline보다 낮은 RMSE를 가진다.

[Paper link](https://KinamSalad.github.io/pdf_folder/2019ICDM.pdf)

### Current work(MS thesis)

*Title* : Spatio-temporal analysis of LTE traffic data for detecting social activity changes(가제)

*Abstract* : 축적된 social media(Instagram)로부터 추출된 social activity와 LTE traffic data와의 시공간적 상호관계(spatio-temporal correlation)을 찾아 cyber-physical space service의 단초를 마련다.

*Methodology* : KT에서 받은 50x50m cell 시간별 유동인구 LTE data의 Week scale의 데이터의 cluster들과(Figure 1 참조) Instagram caption으로부터 LDA로 추출한 사회활동(social activity, Figure 2 참조)간의 공간적 상관관계(spatial correlation)를 발견하였다. 또한 LTE data의 시간대의 이상탐지(anomaly detection)을 통해 어느 시간대에 어떤 사회적 활동이 관련있는지 시간적 상관관계(temporal correlation)를 찾는 과정에 있다. 

<center><img src="https://KinamSalad.github.io/image_folder/Hongik_LTE_INSTA.png" width="400"></center>

###### <center>Figure 1. Hirarchical Clutering for LTE data in Hongik University Area</center>


<center><img src="https://KinamSalad.github.io/image_folder/anomaly_detection.png" width="400"></center>

###### <center>Figure 2. Clutering for Instagram activity data in Hongik University Area</center>

### 2018한국정보과학회(KCC) 학부생논문 지도(우수상)

*Title* : 도시 공간에서의 사회적 행위와 물리 센서 데이터 간의 상관관계 분석-북촌지역 사례연구

*Abstract* : 서울 북촌을 대상으로 그 지역에서 일어나는 사회활동(social activity)과 북촌지역에 설치된 물리 센서 데이터와의 상관관계를 파악하였다. 

*Methodology* : 사회적 활동은 인터넷 기사나 북촌관련 도시공학논문을 인용하여 list up하였고, 물리센서데이터로 서울열린데이터광장의 open api를 통해 크롤링한 지능형 CCTV의 10분당 유동인구 수를 사용하였다. 각 사회적활동이 일어난 시간대의 유동인구 데이터를 heuristic하게 분석하여 사회적활동과 physical sensor data간의 상관관계를 파악한 논문이다.

[Paper link](https://KinamSalad.github.io/pdf_folder/2018KCC.pdf)

### 2019한국정보과학회(KCC) 학부생논문 지도(최우수상)

*Title* : 서울시 지하철 2 호선 역세권의 토지피복도를 이용한 소셜 데이터의 통시적 분석

*Abstract* : 소셜미디어(Instagram)로부터 추출된 인구통계(demographic)정보와 국토부 토지사용피복도(LULC map)의 관계성을 regression analysis를 통해 발견하였다. 

*Methodology* : Transfer learning을 통해 7가지 카테고리로 Instagram을  분류하였으며, 이 중 특정 카테고리로 분류된 이미지 내 인구통계(나이, 성별, 사람수)를 MS Face++ API를 이용하여 추출하여 독립변수로 두었다. 그리고 서울 지하철 2호선 역세권의 LULC 사용용도 비율에 대한 hierarchical clustering을 통해 각 지역의 사용용도를 도출하고 이들의 비율을 종속변수로 두었다. 두 변수간의 회귀분석을 통해 각 지역의 인구통계가 LULC와 관계성을 가짐을 보였다. 

[Paper link](https://KinamSalad.github.io/pdf_folder/2019KCC.pdf)


### (Lecture Project) Crowdsourcing service EVENTENCE!

그동안 열린, 열릴 이벤트들에 대해 참가예정자, 참가자들이 한 문장씩 이벤트를 한줄평을 남기고 이를 wordcloud로 보여주어 이벤트에 대한 개요를 사용자에게 효과적으로 전달할 수 있게 보여주는 crowdsourcing기반 웹페이지이다. 좋아요 기능이나 프로필 기반 어떤 학년,전공의 사용자가 관심있는지 등의 간접적 추천 기능또한 있다. Django기반 back-end구현과 front-end에서 Javascript를 이용한 사용자 interaction개발에 기여하였다.

[Page link](http://kinamsalad.pythonanywhere.com/)

### CDSNLAB 'lapras' IoT testbed

연구실 내 자체 IoT testbed인 lapras-web개발에 참여하였다. lapras는 여러 IoT센서에서 받은 데이터를 미들웨어에서 받아(subscribe), 각 상태정보를 데이터베이스에 저장하고 웹에 배포(publish)하는 IoT testbed이다. 센서데이터를 subscribe하는 Java기반 미들웨어 구현과 저장된 센서 데이터를 데이터베이스에서 로드하여 웨에 시각화하는 업무에 기여하였다.

[Page link](http://lapras.kaist.ac.kr)

## 특이사항 

PUBG PC버전(스팀) 플레이 100시간이상
