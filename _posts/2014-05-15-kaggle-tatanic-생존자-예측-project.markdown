---
layout: post
title: kaggle 타이타닉 생존자 예측 프로젝트
date: 2014-05-15 00:00:00 +0900
description: 빅데이터 대학생 연합동아리 합류 후 첫 데이터 분석 프로젝트 # Add post description (optional)
img: titanic-a.png # Add image post (optional)
tags: [analysis_project, titanic, 데이터분석대회]
---
#### ‘R을 이용한 타이타닉 생존자 예측 데이터 분석 프로젝트', 타이타닉 사고 당시 어떤 사람들이 생존하였는지 예측하는 Binary Classification 문제

#### ※ 분석 도구
- R : 다양한 통계패키지를 보유, 다양한 분석 방법들을 적용해 볼 수 있어서 좋았음
- SAS

#### ※ 분석 방법
- Decision tree를 이용, 종속변수에 영향을 미치는 원인이 무엇인지 명확하게 파악할 수 있어서 유용하다고 판단
- Logistic regression
- ensemble

#### ※ 분석하며 느낀 점
분석에 대한 도메인 지식의 중요성과 데이터 타입에 따른 확연한 분석 결과를 경험 할 수 있었습니다. 타이타닉에 대한 5편의 다큐멘터리를 보아야 했고, 그에 따른 생존 여부를 결정하는 스토리도 파악 할 수 있었습니다.

#### ※ 내가 기여한 부분
종속변수에 미치는 유효한 변수를 찾기 위해서 반복적인 작업을 하는 부분이 있었는데, 이 부분을 R을 이용해서 자동으로 모든 변수의 모든 경우에 따른 Decision tree 예측률 결과를 산출해 주는 코드를 작성했습니다.

#### ※ 결과
82.775%의 예측률을 달성할 수 있었습니다.

#### ※ 사진
![I and My friends]({{site.baseurl}}/assets/img/titanic-a.png)
