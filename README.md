# crypto-trading-bots-portfolio

# 암호화폐 자동매매 애플리케이션

### 비즈니스 목표
24시간 자동매매를 통해 금융소득 창출

### 플로우 차트
https://github.com/yunki12/crypto-trading-bots-portfolio/blob/main/365414026-ee74c00c-671b-4be7-bfd9-5d2a3fc4330d.png?raw=true

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
