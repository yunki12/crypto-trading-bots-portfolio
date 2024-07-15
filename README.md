# crypto-trading-bots-portfolio

# 암호화폐 자동매매 애플리케이션

### 플로우 차트
<img src="https://github.com/user-attachments/assets/4b9a0ce8-0d35-415b-8ec6-c209eed8387d" width="900" height="700"/>

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
