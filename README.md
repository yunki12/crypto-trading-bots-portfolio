# crypto-trading-bots-portfolio

# 암호화폐 자동매매 애플리케이션

### 비즈니스 목표
24시간 자동매매를 통해 금융소득 창출

### 플로우 차트
<img src="https://private-user-images.githubusercontent.com/31138701/365413823-b3d2f469-c0a3-4685-a383-c23912468586.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjYyOTQzODMsIm5iZiI6MTcyNjI5NDA4MywicGF0aCI6Ii8zMTEzODcwMS8zNjU0MTM4MjMtYjNkMmY0NjktYzBhMy00Njg1LWEzODMtYzIzOTEyNDY4NTg2LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA5MTQlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwOTE0VDA2MDgwM1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTcxMDNkMjUwZTFhMzhlNmM3NDRlMDEwNTRhNzM5NWJjZTU1Mzk2YWE1NGUxZTM3YWFmMzkxMzY4ZTA5MjE3NGImWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.0AArFCU5c1VjrZnQT9jubFFSF2c99si2sQBpZ354czM](https://github.com/yunki12/crypto-trading-bots-portfolio/blob/main/365414026-ee74c00c-671b-4be7-bfd9-5d2a3fc4330d.png?raw=true" width="900" height="700"/>

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

#### 3.매수취소
1) 매일 8시55분에 전일 매수 종목 취소

#### 4.알림
1) 매수 알림
2) 매도 알림
3) 매수 취소 알림
