# 나상원의 포트폴리오
<!--
## Table of Contents
  * [**1. Outline**](#1-outline)
    + [1.1. Profile](#11-profile)
    + [1.2. Educations](#12-educations)
    + [1.3. Awards](#13-awards)
    + [1.4. Skills](#14-skills)
    + [1.5. Experiences](#15-experiences)
  * [**2. 과목 프로젝트**](#2-과목-프로젝트)
    + [2.1. JSP와 MySQL를 이용한 영화 예매 시스템](#21-for-a-lifetime)
    + [2.2. 음악 정보 공유 웹 서비스 개발](#22-self-improvement)
  * [**3. 학부연구생 프로젝트**](#3-외부-프로젝트)
    + [3.1. Data Enrichment 확장 요소 도출 및 데이터 분석](#23-standardization)
    + [3.2. 침해지표 공유를 위한 침해지표 포맷 및 공유 방안 연구](#24-documentation)
    + [2.5. 적법 위장 타겟형 변종 은닉 악성 디지털 파일 자동 검출 시스템 개발](#25-test-driven-development)
-->

## 1. 소개 ##
### 1.1. 교육 ###
한신대학교, 2018-03 ~ 2024-02
 
 - 주전공: 컴퓨터공학부
 - 학점: 4.27/4.5

컴퓨터공학부를 다니면서 학부연구생으로 활동한 것은 값진 경험이라고 생각합니다. 혼자서는 어떻게 개발 관련 진로 준비를 해야할지 막막했는데 교수님과 함께 지도를 받으며 진행한 것이 큰 도움이 됐고, 팀 프로젝트를 수행하면서 저보다 실력이 있는 학우를 보며 도전을 받고 배울 수 있는 것도 기억에 남습니다.

### 1.2. 스킬 ###
주로 Python을 경험해봤습니다.
프로젝트 두 번에 걸쳐 ERD 설계를 해봤습니다.

## 2. 과목 프로젝트 ##
### 2.1. JSP와 MySQL를 이용한 영화 예매 시스템 ###
https://github.com/NaSangWon/gigabox

* Java EE
* JSP
* MySQL

영화관 플랫폼 운영에 필요한 데이터베이스를 E-R 다이어그램으로 설계하고, MySQL로 구현했습니다. JSP, JDBC로 웹어플리케이션을 만들었습니다. 회원가입, 영화관, 영화, 상영, 예매 관련 정보를 조회하거나 수정할 수 있도록 했습니다.

### 2.2. 음악 정보 공유 웹 서비스 개발 ###

* Python
* MySQL

Python으로 음악 스트리밍 플랫폼 링크를 변환해주는 웹어플리케이션을 개발했습니다. E-R 다이어그램으로 데이터베이스를 설계했고, 각 플랫폼 별 정보 크롤링을 담당했습니다. 기본적인 API 설계/구현 관련 이해와 웹 어플리케이션이 어떻게 동작하는지 배웠습니다.

[설계한 ERD 보기](https://www.erdcloud.com/d/pCHrAkF7qg84Z5vjS)

## 3. 학부연구생 프로젝트 ##
### 3.1. Data Enrichment 확장 요소 도출 및 데이터 분석 ###

* Python
* PyQt

보안 관련 위협 정보 공유 오픈소스 플랫폼인 [MISP](https://github.com/MISP/MISP), [IntelMQ](https://github.com/certtools/intelmq)의 Github 등을 참고하여 IoC 정보로부터 추가 정보를 이끌어내는 Data Enrichment를 어떻게 수행하는지 알아보고, Data Enrichment로 활용되는 주요 플랫폼의 API를 이용해 Python으로 GUI 모듈을 구현했습니다.

이 프로젝트에서 처음으로 Github를 접하는 것이었는데, IntelMQ 이용 중 생긴 문제를 리포지토리 소유자와 소통하면서 해결해보려 했습니다.

https://github.com/certtools/intelmq/issues/2196

MISP module 문서를 읽다가 발견한 링크 오타도 PR을 올려 수정해보려 했습니다. 비록 문서 구조를 이해 못 해 직접 해결은 하지 못했지만, 나름대로의 기여를 한 것 같아 뿌듯했습니다.

https://github.com/MISP/misp-modules/pull/617

### 3.2. 침해지표 공유를 위한 침해지표 포맷 및 공유 방안 연구 ###

* Python

위협 정보 공유 플랫폼, MISP이 어떤 침해지표 표현 방법을 따르는지 분석하고, 사용하기 쉬운 새 IoC 분류체계를 제시했습니다.

MISP 공유 시스템을 분석한 내용으로 논문을 공저자로 등록되게 되었습니다. "Cyber Threat Intelligence Methods for Sharing Indicators of Compromise Information on Malware Infected IoT/Edge Systems"
(The 15th International Conference on Computer Science and its Applications.)

### 3.3. 적법 위장 타겟형 변종 은닉 악성 디지털 파일 자동 검출 시스템 개발 ###
https://github.com/NaSangWon/ooxml-malware-detection-machine-learning

* Python
* scikit-learn
* PyQt

OOXML 문서, Windows office 문서 파일의 악성 요소를 탐지하는 머신러닝 모듈을 개발했습니다. 

![ooxml ml module preocess](/assets/ooxml_process.png)

OOXML 압축 위변조 구조, VBA Macro, VirusTotal 샌드박스 분석 결과를 feature로 추출했습니다. 악성 코드를 분석하기 위해 VMware로 Ubuntu 가상환경을 구축했습니다. scikit learn으로 머신러닝을 구현했습니다.

이 연구 과정과 결과물을 토대로 교수님이 논문을 등록하였습니다. "ML based Malicious Hidden Data Analysis and Detection Method on OOXML-based MS-Office Digital Files"
(The 2nd International Conference on Internet of Things and Convergence 2023)
