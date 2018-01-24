---
layout: post
title: kkbox 다음달 이탈유저 예측 프로젝트
date: 2017-12-15 00:00:00 +0900
description: # Add post description (optional)
img: # Add image post (optional)
tags: []
---
#### 'kaggle kkbox 다음달 이탈자 예측 프로젝트', 예측률 향상 & 실제 kkbox에서 사용할 수 있는 분석툴 개발(가상웹사이트)
##### kkbox is a music streaming service established by a group of Taiwanese software programmers in 2004.

#### ※ 분석 도구
- Python : 간편한 script(jupyter notebook)
- Hive : 대용량 데이터 처리
- mysql : 전처리에 사용

#### ※ 분석 방법
- Hive 환경<br>hadoop_version 1<br>namenode+snamenode+datanode6개
- mysql, 가상머신의 Hadoop과 window의 mysql간 sqoop방법으로 데이터를 주고 받음
- 전처리, Hive:4GB의 UserLog file을 거래 transaction 단위로 압축,요약 하는데 활용
- 분석, python에서 신경망 활용

#### ※ 웹사이트 개발 방법
- ruby on rails + SQLite
- 실제 데이터가 아닌 sample 데이터만을 활용해서 가상으로 분석 웹사이트를 만들었기 때문에 간단히 SQLite를 활용했습니다.

#### ※ 분석하며 느낀 점
- 대용량 데이터처리에 있어서 하둡의 위대함을 느꼈고, log분석을 하는데 있어서 다양한 방법을 시도해보지 못한 점이 매우 아쉬웠습니다.

#### ※ 내가 기여한 부분
Hadoop 환경셋팅 및 분석 전반<br>
전처리 및 웹사이트 개발은 팀원들에게 많이 의지함

#### ※ Code
- <a href="https://github.com/The-G/kkbox">https://github.com/The-G/kkbox</a>
