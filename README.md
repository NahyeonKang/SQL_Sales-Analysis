# SQL_Sales-Analysis
Database의 상거래 데이터를 파이썬에서 SQL문으로 불러와 시각화
## Northwind.ipynb
### 일별 매출 시각화
![newplot](https://user-images.githubusercontent.com/24906028/179972430-4188f99e-dc31-4cf7-89be-5599c13fb2eb.png)
### 월별 매출 시각화
![newplot (1)](https://user-images.githubusercontent.com/24906028/179972455-04f9b739-4eb5-4033-8d01-fe647ffc3f3b.png)
![newplot (2)](https://user-images.githubusercontent.com/24906028/179972507-289cb50d-0e93-46fc-b403-d4a7f5ced446.png)
### Category 월별 매출액 추이
![newplot (3)](https://user-images.githubusercontent.com/24906028/179972545-65f12a33-e9ae-4e96-9d85-86a36f479be7.png)
![newplot (4)](https://user-images.githubusercontent.com/24906028/179972616-e8eaf523-b711-4e0c-b770-1b20be1bf53a.png)
### Treemap으로 카테고리별 상품 매출 시각화
![newplot (5)](https://user-images.githubusercontent.com/24906028/179972657-2d5e2ad7-e16d-419a-95cb-6b858dccf384.png)
### 동년도 월별 누적 매출
![newplot (6)](https://user-images.githubusercontent.com/24906028/179972708-a69b730b-b7bf-4d86-905c-efa6a8d2d5ec.png)
### 5일, 20일 이동 평균 매출액 구하기
![newplot (7)](https://user-images.githubusercontent.com/24906028/179972834-c3d0293d-8597-465a-add3-ee1a28499a47.png)
![newplot (8)](https://user-images.githubusercontent.com/24906028/179972997-bf0a577c-0c4e-46b4-a4e8-f60c0f98da6e.png)
### 작년 대비 동월 매출액 비교 시각화
![newplot (9)](https://user-images.githubusercontent.com/24906028/179973052-87cbe441-2911-46ec-8baa-446212e782e0.png)
### 카테고리 별 기준 월 대비 매출 비율 추이
![newplot (10)](https://user-images.githubusercontent.com/24906028/179973570-8043d092-4d7b-4b2d-8211-800d70478dcb.png)
### 매출 Z 차트 시각화
![newplot (11)](https://user-images.githubusercontent.com/24906028/179973653-58b6e064-87ae-4ea6-a9ab-1588a8a7375a.png)
### 이전 주문이후 현 주문까지 걸린 기간 히스토그램 시각화
![newplot (12)](https://user-images.githubusercontent.com/24906028/179973663-02722863-86d5-4d59-9bc0-963c675d63f4.png)

-----
-----
## RFM
### Google Analytics.ipynb
![newplot](https://user-images.githubusercontent.com/24906028/179987332-d41cf1f9-5c4f-41b5-9c58-aa3d76b05df3.png)  

Recency 2016년 11월 1일 기준 고객이 언제 주문했는가  
Frequency 얼마나 자주 주문했는가  
Monetary 얼마나 많은 금액을 사용했는가  

-----
-----
## 웹사이트 접속 및 매출 분석
### Google Analytics_web.ipynb
DAU, WAU, MAU 및 채널별 매출 분석  
#### 일별 고유 사용자 및 세션 건수, 사용자별 평균 세션 건수
![newplot](https://user-images.githubusercontent.com/24906028/182039187-fc0ea983-95af-461a-9d84-21f7d1cd1c26.png)
#### 고착도(Stickiness) = DAU/MAU
![newplot (1)](https://user-images.githubusercontent.com/24906028/182039217-97faca70-2974-4850-affc-aa036427e3b1.png)
#### 사용자별 월별 세션 접속 횟수 구간별 분포 집계
![newplot (2)](https://user-images.githubusercontent.com/24906028/182039226-2df41567-4133-449b-aff5-dd34ce3513b3.png)
#### 채널별 고유/주문 사용자 건수와 매출 금액 및 비율
![newplot (3)](https://user-images.githubusercontent.com/24906028/182039232-b6bc34f4-0281-4a96-8059-d0d731287cae.png)
![newplot (4)](https://user-images.githubusercontent.com/24906028/182039249-cc881b87-b071-4f8e-b7cb-c02b95ab7b7a.png)
![newplot (5)](https://user-images.githubusercontent.com/24906028/182039251-b962ac8d-fed5-41b1-a570-a2dc3dc0d491.png)
![newplot (6)](https://user-images.githubusercontent.com/24906028/182039255-718fe6d4-06da-47a3-bdf2-1cae626600de.png)

### Google Analytics_web performance.ipynb
이탈율(Bounce Rate), 종료율(Exit Rate), 잔존율(Retention Rate)  
매출전환율, 전환퍼널분석
#### 과거 30일간 일별 페이지 조회수 및 30일 평균 일별 페이지 조회수
![newplot](https://user-images.githubusercontent.com/24906028/182117451-a5c07837-b212-467d-9a35-6f4cf2d53198.png)
#### 일자별 세션의 매출 전환율과 매출액
![newplot (1)](https://user-images.githubusercontent.com/24906028/182117637-eee067c4-8c22-422c-a405-d01de53ee14d.png)
![newplot (2)](https://user-images.githubusercontent.com/24906028/182117650-707bb692-131b-4743-927d-aba3745eac14.png)
#### 채널별 월별 세션의 매출 전환율
![newplot (3)](https://user-images.githubusercontent.com/24906028/182117680-b3cf6101-6137-430c-b653-5cca9beb9d28.png)
#### 채널별 전환 퍼널
![newplot (4)](https://user-images.githubusercontent.com/24906028/182142704-547e5f1e-6b44-4f03-990d-8ac3f3becf9a.png)
![newplot (5)](https://user-images.githubusercontent.com/24906028/182142733-82e46983-7845-41a9-a66b-52c2628a5ff4.png)

