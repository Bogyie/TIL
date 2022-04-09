# day 3



## 웹 사이트 배포

### Freenom 사이트 가입

- 사이트 접속

  > **계정 정보가 불완전한 경우 계정이 비활성화 될 수 있음**

  > freenom 사이트의 경우 공인 ip 당 session 개수가 제한이 있으므로, 다중 접속시 주의 필요

### Netlify 연동

- DNS 설정
  - Freenom에서 nameserver 를 netlify 로 변경
  - SSL 적용 확인



### 개인 사이트, 수업 사이트 분리 작업

#### 웹 서버 설치 및 실행

- nginx 설치
  - nginx.org/en/download.html 접속
  - stable version download
  - http://localhost/ 접속해서 nginx 가동 확인
- nginx 설정
  - nginx/conf/nginx.conf
    - server - location
      - root directory path 설정
  - nginx port 설정
    - 내부 망 ip로 접속 확인



### nginx command

> nginx -s [command]

- reload
  - .conf file reload
- quit
  - server shutdown
- stop
  - server interrupt
- reopen
  - log file open



## 기능 추가

### 동영상 추가 태그

- Youtube Share
  - Embed -> Source

### 댓글 기능 -> 가져다 쓰기

- Disqus
  - comment API

### 채팅 기능 -> 가져다 쓰기

- tawk
  - char API

### Google Analytics

- 계정 생성



## 화면 설계

### UML





### 점심시간 개인 공부

https://deview.kr/data/deview/session/attach/3_NAVER%EC%9D%98%20MongoDB%20%EC%A0%91%EA%B7%BC%ED%86%B5%EC%A0%9C%20%EA%B0%9C%EB%B0%9C%EA%B8%B0.pdf

