## 개발 의도

- 심심하기도 하고 풀스택 개발을 해서 유지보수할 프로젝트를 만들고 싶은 것
프론트는 대충할 것이고 백엔드와 인프라 위주.
- 유튜브 추천 알고리즘 없이 원하는 채널만 모아보기 위해서
추천 알고리즘이 나의 시간을 훔쳐가기 때문.
채널 모아보기를 폴더로 그룹핑하여 모아본다.
- 유튜브에는 추천 기능 끄기와 채널 모아보기 기능이 없음.

## 기획

### 화면

- 메인 화면으로 좋아요한 동영상 자동 그룹핑.
<img width="1206" alt="메인화면" src="https://github.com/monkeyDugi/foltube/assets/53487385/9b8d0e16-bf23-4be8-b965-51f37939fe02">

    

- 구독 그룹 추가
<img width="1193" alt="구독그룹추가1" src="https://github.com/monkeyDugi/foltube/assets/53487385/e5fe9a08-98d7-44f6-b98d-e4696b27d4e0">
<img width="1199" alt="구독그룹추가2" src="https://github.com/monkeyDugi/foltube/assets/53487385/44631c5b-6722-4bbf-ab9c-1a11480fbf17">

    
- 생성한 그룹 영상 최신순으로 보기
<img width="1195" alt="생성한 그룹" src="https://github.com/monkeyDugi/foltube/assets/53487385/d160443e-fe39-47e9-a533-81d406f2e7d3">

    
- 영상 재생
<img width="1200" alt="영상재생" src="https://github.com/monkeyDugi/foltube/assets/53487385/6b741162-6717-4576-b396-b7695e6687ea">

    

- 영상 화면 스크롤은 무한 스크롤
- OAuth 구글 로그인.

## 개발

### ERD

### 프로세스

### 기술 스택

- 백엔드
    - SpringBoot
    - JPA
    - Docker
    - Gradle
    - MySQL
- 인프라
    - AWS EC2
    - Sentry
        - https://engineering.linecorp.com/ko/blog/log-collection-system-sentry-on-premise
    - Github Action

## 얻고자 하는 것

- 실제 내가 사용할 수 있는 서비스 운영
- AWS 운영
- 인프라 구축
    - CI/CD, AWS, 로그
- 트래픽 가정한 경험
- 동시성을 가정한 경험
- 프론트엔드 최소한의 개발 경험
