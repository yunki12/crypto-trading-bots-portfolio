# crypto-trading-bots-portfolio

# 암호화폐 자동매매 애플리케이션

### 플로우 차트
<img src="https://private-user-images.githubusercontent.com/31138701/349994461-53fb5af0-993e-489d-8958-5ec8315d3f91.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjEzODU1MjMsIm5iZiI6MTcyMTM4NTIyMywicGF0aCI6Ii8zMTEzODcwMS8zNDk5OTQ0NjEtNTNmYjVhZjAtOTkzZS00ODlkLTg5NTgtNWVjODMxNWQzZjkxLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTklMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzE5VDEwMzM0M1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWYxMmY2ODg4YzVlYzY1YTM4NTMwYjg0ZDlmNDRlOGY1YWEyZmNmZjJkYmM0NGI2YzZlMjQ1OTBlNTk5MjI0NDkmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0._tCH4yvh9QdrVtIPjmJLhdEGNM1gMXTNq4ZQY0BQ12Y" width="900" height="700"/>

### 기술 스택
Cloud : GCP (인스턴스 OS : Debian GNU/Linux 11)
Application : Spring Boot 3.2, JPA, Querydsl, WebClient, Java 17, Gradle 8.5

### 주요 기능
1.매수
1) 분할 매수
 - 동적 분할 매수 기능
 - 매수 수치 로직
    - 24시간 거래대금
    - 매수 가능 금액 비율 조정

2.매도
1) 수익 매도 퍼센트
2) 손절 매도 퍼센트


3. 알림
1) 매수 알림
2) 매도 알림
