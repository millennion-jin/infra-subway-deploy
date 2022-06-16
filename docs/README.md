# 그럴듯한 서비스 만들기

## 1단계 - 서비스 구성하기
### 필요기능
- [x] 웹 서비스를 운영할 네트워크 망 구성하기
- [x] 웹 애플리케이션 배포하기

## 2단계 - 서비스 배포하기
### 운영환경 구성하기
- [x] 웹 애플리케이션 앞단에 Reverse Proxy 구성하기
  - [x] 외부망에 Nginx로 Reverse Proxy를 구성
  - [x] Reverse Proxy에 TLS 설정
- [x] 운영 데이터베이스 구성하기
### 개발환경 구성하기
- [x] 설정 파일 나누기
    - [x] JUnit : h2, Local : docker(mysql), Prod : 운영 DB를 사용하도록 설정

## 3단계 - 서비스 배포하기
- [x] 배포 스크립트 작성하기
- [x] 스크립트 서버 테스트 진행
- [x] 매 분마다 동작하도록한 crontab 적용
- [x] crontab과 /etc/crontab 의 차이에 대해 학습
  - crontab -e 의 경우 현재 유저의 권한으로 실행되는 crontab 목록에 등록이 되며, 별도로 실행 유저를 설정하지 못함
  - /etc/crontab 의 경우 root 권한으로 수정이 가능하며, crontab 상의 동작을 실행시킬 주체가 되는 유저의 설정이 가능
