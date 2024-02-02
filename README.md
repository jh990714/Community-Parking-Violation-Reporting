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


- 주정차 신고

  https://github.com/jh990714/Community-Parking-Violation-Reporting/assets/144774186/e17a8827-ae89-485c-b1d4-d78f6984c9d4

  <br>

- 신고 반려
  
  https://github.com/jh990714/Community-Parking-Violation-Reporting/assets/144774186/edba6dd4-6fdb-44c5-ab88-ca8eaae5a0d3

  <br>

- 게시물 보기/댓글
  
  https://github.com/jh990714/Community-Parking-Violation-Reporting/assets/144774186/4423b687-a58a-4941-98ab-5ae686cd4c70

  <br>

- 신고차량 위치 확인

  https://github.com/jh990714/Community-Parking-Violation-Reporting/assets/144774186/43212685-410b-4db8-a014-8f3b63d69ed5

  <br>

- 알림
  - 신고 요청 알림
    
    ![image](https://github.com/jh990714/Community-Parking-Violation-Reporting/assets/144774186/f6af6cda-4458-4ddb-ab5b-c9923c331a67)

  - 차량 이동 요청
    
    ![image](https://github.com/jh990714/Community-Parking-Violation-Reporting/assets/144774186/6c3d98b7-af80-4da3-aea3-9fb44ecaafc6)

  - 신고 반려
    
    ![image](https://github.com/jh990714/Community-Parking-Violation-Reporting/assets/144774186/e50cf5ba-a45b-4a31-a4bf-2d03bf230fed)

<br><br>

## 설계 내용

### ° 번호판 인식 및 OCR

  ![image](https://github.com/jh990714/Community-Parking-Violation-Reporting/assets/144774186/e3d3b2f5-95a2-4a04-a8aa-9c38ab2e5697)

  - YOLOv8를 사용하여 Object Dectection(차량, 번호판) 학습
  - CLOVA AI에서 제공하는 deep-text-recognition-benchmark 오픈소스 프로젝트를 이용해 OCR모델 학습

<br>

### ° 신고 유형 판단
  - 실선
  - 횡단보도
  - 버스 정류소, 소화전
