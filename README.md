# crypto-trading-bots-portfolio

# 암호화폐 자동매매 애플리케이션

### 플로우 차트
<img src="[https://github.com/DevSpaceHub/AST/assets/66311276/64b326e7-3063-4ec7-98fd-86453ea70d61](https://private-user-images.githubusercontent.com/31138701/365414026-ee74c00c-671b-4be7-bfd9-5d2a3fc4330d.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjU3NzAwMzUsIm5iZiI6MTcyNTc2OTczNSwicGF0aCI6Ii8zMTEzODcwMS8zNjU0MTQwMjYtZWU3NGMwMGMtNjcxYi00YmU3LWJmZDktNWQyYTNmYzQzMzBkLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA5MDglMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwOTA4VDA0Mjg1NVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTBiMDU1N2QwMDgzZjAyMTVlMWM1ZjM5NDBhYTIzMjhlNDQwYzY4NWU5OTBkOTNkNWI3M2QwZWQyZDA0MmJkOTYmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.Y9kx0k2qGM1yRI3iDc45e0CtexoJnNlCZ6Qke3lxelg)" width="900" height="700"/>

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
