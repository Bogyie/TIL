> 사담
>> 자습시간 : 아침 6시 30분 ~ 5시 50분 <br>
>> 개발자 -> 누가 더 정리 잘하냐 싸움; 절차 지향 <br>
>> 서버 또는 블로그를 이용해 자신의 지식을 누적하자 -> 필요할때 찾아서 사용 <br>
>> 개인정보와 데이터 관리의 중요성 <br>
>> vscode tag wrap : ctrl + shift + p -> emmet -> tag <br>
>> vscode dup : shift + alt + arrow <br>
>> 시각장애인을 위한 시멘틱 웹 지원 필요 <br>
>> 강의를 끝까지 듣기 위해 자기관리 필요! <br>
>> vscode -> code reformat -> beauty <br>


## 참고
- [카카오 오븐](https://ovenapp.io/)
  - GUI based HTML Element mockup online tool
  - UI design
- 개발자로 살아남기 - 박종천
- [w3 : 웹 표준화 기구](https://www.w3.org)
- [수업 중 작성한 소스코드](https://www.notion.so/boggy/WEB1-02ef558eccfa492ababae5c2b614e836)


## 웹 페이지를 구성하는 기본적인 요소와 문법
> 통계에 기반한 주요 태그 공부 <br>
> **html 문서 구조가 맞아야 live server에서 실시간 반영됨** <br>
> **HyperText** -> navigation 되는 페이지를 통칭 <br>

- vscode 에서 ! 입력해서 HTML 기본 서식 자동완성
- html 은 태그를 열고 <> 닫아야 함 </>

#### TAG
- br : break
  - \n 기능
- **p : paragraph(문단)**
  - 이용빈도 84% 이상!
  - 검색엔진 최적화 (SEO)
  - **html tag의 의미론적(semantic) 사용**
    - br vs p
  - style = margin-top: 40px -> CSS style inline 예시
- strong
  - bold
- u
  - underline
- h (1 ~ 6) : heading(제목)
  - 줄넘김, margin, bold default
- span
  - inline container
  - semantic 정보를 전달하지 못하기 때문에 사용을 지양해야 함
- img
  - image -> img
  - source -> src
  - 이미지 저작권 문제
    - [unsplash](https://unsplash.com/)
    - Google Copyright free image filter
  - 이미지 크기 설정
    - width, height
    - px, %, ...
- li : list(목록)
  - ul : 순서 없음
  - ol : 순서 있음 (자동 넘버링)
- a : anchor(닻)
  - link
  - href : hypertext reference 의 약자
  - 새 창에서 열기 -> target = _blank
    - [blank vs _blank](https://velog.io/@tngusglaso/HTML-%EB%A7%81%ED%81%AC-targerblank%EC%99%80-targerblank%EC%9D%98-%EC%B0%A8%EC%9D%B4%EC%A0%90)
  - caption -> title attribute

#### HTML Structure Tag
- title
  - browser 상의 window name -> title 설정
- meta
  - charset : charators encoding


## 서버와 클라이어트 구조 이해하기
> 의문이 있어야 한다 -> 웹 생태계, CS 전반에 대한 다양한 관심을 가져야 한다. <br>
> 클라이언트 : 고객 ( 웹 브라우저 ) <br>


## 무료 도메인을 이용한 웹 사이트 만들기
> [bscodig](https://www.bscoding.ga) <br>
> ga 도메인 : https (SSL 인증) 무료로 제공 <br>
> 웹은 저작권과 이용료가 없기 때문에 널리 퍼질 수 있었다 <br>


## 사용자 요구사항
> 고객의 요구사항에 맞춰서 웹을 제작하는 경우, 차후 지속적인 보완이 필요함 <br>
> 고객의 요구사항이 변경되는 경우 리팩토링이 진행되어야 함 <br>
> HTML 문법과 태그를 적절히 사용하면 리팩토링이 용이해짐 <br>


## 부모 - 자식 관계
> 부모의 속성 또는 기능을 자식이 상속 받아 사용 <br>
``` html
<div>
    <span></span>
</div>
```
> div -> 부모 태그, span -> 자식 태그 <br>


## 간단한 예제로 웹사이트 완성해 보기
> web dir

## 원시 웹
> [info.cern](http://info.cern.ch/)

## 웹 배포
- 무료 도메인 : freenom
