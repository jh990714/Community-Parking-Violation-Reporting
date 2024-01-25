<div align="center">
<h2>[2023]커뮤니티를 통한 불법 주차 신고 시스템 </h2>
</div>

## 목차
  - [개요](#개요) 
  - [프로젝트 구현 결과](#프로젝트-구현-결과)
  - [설계 내용](#설계-내용)
<br><br>

## 개요
- 프로젝트 이름: 커뮤니티를 통한 불법 주차 신고 시스템
- 프로젝트 기간: 2023.03 ~ 2023.11
- 개발 엔진 및 언어:
<br><br>

## 프로젝트 구현 결과
  |회원가입|

  
  |로그인|

  
  |신고하기|
  

  |신고차량 위치 확인|
  

  |게시물 보기|


  |댓글|

<br><br>

## 설계 내용

### ° 번호판 인식 및 OCR

  ![image](https://github.com/jh990714/Community-Parking-Violation-Reporting/assets/144774186/e3d3b2f5-95a2-4a04-a8aa-9c38ab2e5697)

  - YOLOv8를 사용하여 Object Dectection(차량, 번호판) 학습
  - CLOVA AI에서 제공하는 deep-text-recognition-benchmark 오픈소스 프로젝트를 이용해 OCR모델 학습

<br>

### ° 신고 유형 판단
