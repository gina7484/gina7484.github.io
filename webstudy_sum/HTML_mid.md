HTML 중급 내용 정리
=============
##### 작성일시: 2020.01.15
##### source: <http://webberstudy.com/>
웹표준
-------------
* 웹표준이 중요한 이유
  - 작업한 페이지가 어느 한 웹 브라우저에서 의도와 다르게 나타날 때 코드와 브라우저 중 어느 쪽이 수정되어야 할 지를 판단하는 기준
    * ex: 표준을 준수했음에도 그 브라우저만 다르게 나타난다 -> 브라우저의 버그
  - 현재 나오고 있는 최신 브라우저들은 대부분 웹 표준을 준수
* 웹표준의 준수
  - HTML(의미)과 CSS(외형), Javascript(동작)를 역할에 맞게 분리
    + HTML
      + 블록 요소를 인라인 요소에 넣지 않는 것
      + p, ul, ol, dl 같은 특수한 경우의 제약사항들
      + 검증: [마크업 서비스](http://validator.w3.org/)

doctype
-------------
* Doctype:  웹 표준을 지키는 문서의 타입 종류 중 어떤 타입(document type)을 사용하는지 선언하는 것
  + 가장 처음에 선언해줘야 함
  + version
    - HTML 4.01
      ```
      <img src="../img.png" alt="이미지는 그 스스로가 내용입니다.">
      ```
      - 스스로 닫는 태그를 <br />이 아닌, <br>의 방식으로 표현해도 문제가 없음.
      - 태그 사용에 XHTML에 비해 유연함
    - XHTML 1.0
      ```
      <p>p 요소는 내용을 감싸기 때문에 열리고 닫힙니다.</p><!-- 열리고 닫히는 형태 -->
      <img src="../img.png" alt="이미지는 그 스스로가 내용입니다." /> <!-- 스스로 닫히는 태그 -->
      ```
      - HTML보다 태그 사용에 엄격하지만 추후 유지보수가 쉬워진다.
    - XHTML 1.1
      - 가장 엄격함
  + type
    - 독타입의 타입 종류는 HTML 4.01과 XHTML 1.0에 있다.
    - 종류들
      - strice
        - 엄격한 규격을 나타냄
        - 새로 페이지를 만든다면 추천
      - transitional
        - 과도기 적인 규격
        - 이미 예전부터 서비스하고 있던 페이지를 수정할 경우
      - frameset
        - 지금은 거의 사용하지 않는 타입
  + doctype 종류별 선언
    - 외울 필요 없고 찾아서 쓰면 된다: [doctype 종류별 선언](http://webberstudy.com/html-css/html-2/doctype/)
  + 크로스 브라우징: 여러 브라우저에서 올바르게 나오도록 하는 것
    - 작업하면서 페이지가 계속 이상하게 나오면 [페이지 정보]-[일반]-[렌더링 방식]이 표준 모드인지 확인하기

사용하지 말아야 할 요소들
-------------
##### 사용하지 말아야 할 것들 위주이기 때문에 요점 정리 위주로 읽자.
##### http://webberstudy.com/html-css/html-2/elements-should-not-use/

문구 요소들2
-------------
##### HTML 문구에 의미를 부여하는 태그 address, abbr, acronymm dof, code, samp 요소를 살펴본다.

테이블 요소의 기본
-------------

테이블 요소의 의미적 작성
-------------

테이블 요소와 레이아웃
-------------





