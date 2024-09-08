# crypto-trading-bots-portfolio

# 암호화폐 자동매매 애플리케이션

### 플로우 차트
<img src="https://private-user-images.githubusercontent.com/31138701/356856248-97951d59-1f23-48b2-9a8b-a422a208cae9.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjU3NjEzODksIm5iZiI6MTcyNTc2MTA4OSwicGF0aCI6Ii8zMTEzODcwMS8zNTY4NTYyNDgtOTc5NTFkNTktMWYyMy00OGIyLTlhOGItYTQyMmEyMDhjYWU5LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA5MDglMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwOTA4VDAyMDQ0OVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWYyZTI3MWI1MDEyY2UxYTNmODdhNjRlYzc4YmQ2OTJmMDMyZmIwMzIwNDRlZmNmMjQzMzVlN2M4MWZlZDA0ODYmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.YPYyA-juBMl8U7mMQaPP0fVz10wdq89wpq0HLWkKFHI" width="900" height="700"/>

### 기술 스택
Cloud : GCP (인스턴스 OS : Debian GNU/Linux 11)
Application : Spring Boot 3.2, JPA, Querydsl, WebClient, Java 17, Gradle 8.5

### 주요 기능
#### 1.매수
1) 분할 매수
 - 동적 분할 매수 기능
 - 매수 수치 로직
    - 24시간 거래대금
    - 매수 가능 금액 비율 조정

#### 2.매도
1) 수익 매도 퍼센트
2) 손절 매도 퍼센트

#### 3. 알림
1) 매수 알림
2) 매도 알림
