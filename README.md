# 프로젝트 기획안🚀

## 1. 개요

 본 프로젝트는 서울시의 교통 안전 및 자전거 교통사고 현황을 분석하고, 이를 바탕으로 플레이데이터 서초캠퍼스 데이터엔지니어 31기 수강생들을 대상으로, 안전 운전 및 교통사고 인식 제고를 목표로 함.

## 2. 범위

* 지난 3주 간 강의 시간에 배운 내용을 바탕으로, 웹크롤링, 데이터베이스 구축, 데이터 분석 및 시각화 기술을 이용하여, 프로젝트를 수행

## 3. 목표

* 서울시의 교통사고 발생 패턴을 분석하고, 시각화하여 안전 운전에 대한 인식 제고
* 특히, 다양한 요인(위반 유형, 사고 유형, 기상 상태, 도로 형태, 운전 경력, 연령대)에 따른 교통사고, 발생 패턴을 분석하고, 자전거 이용량과 교통사고 발생 사이의 상관관계 파악

## 4. 데이터 수집 및 가공

1. 데이터  
BeautifulSoup4 라이브러리를 이용하여 2018년~2022년에 교통안전정보관리시스템 홈페이지로부터 서울시에서 발생한 교통사고 데이터 수집
* 광역자치단체 중 서울시의 데이터만을 추출하여 분석

## 5. 데이터베이스 구축

* pymysql을 이용하여 공유 서버에 데이터베이스 연결
* 수집한 데이터를 기반으로 스타스키마 기반의 데이터베이스 구축
* 데이터베이스 테이블은 교통사고 유형, 차량 속도, 자전거 이용량을 포함

## 6. 데이터 분석 및 시각화

[공공자전거 이용률](image/nums_of_rent_by_gugun.png)

...

## 7. 레퍼런스

* [교통안전정보관리시스템](https://tmacs.kotsa.or.kr/)
* [서울시 열린 데이터 광장 통계목록 - 서울시차량통행속도실태조사](https://data.seoul.go.kr/dataService/boardList.do)
* [서울시 공공자전거 이용현황](https://data.seoul.go.kr/dataList/OA-14994/F/1/datasetView.do) : 렁우렁우님이 API 키 발급 받음. 
* [서울시 공공자전거 이용정보(월별)](https://data.seoul.go.kr/dataList/OA-15248/F/1/datasetView.do)
* [서울시 공공자전거 대여소 정보](https://data.seoul.go.kr/dataList/OA-13252/F/1/datasetView.do)
* [GitHub - repository](https://github.com/pladata-encore/DE31-1st-traffic_survey)
* [서울시 자전거도로 현황 통계](https://data.seoul.go.kr/dataList/276/S/2/datasetView.do)