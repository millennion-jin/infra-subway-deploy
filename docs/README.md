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
