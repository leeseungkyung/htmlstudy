# HTML 

- Hyper Text Markup Language 의 약자
- HTML은 웹서버 저장 됨
- 웹 브라우저에 의해 해석되고 화면에 보여진다



### html의 탄생

- 1990년 월드 와이드 웹과 함께 탄생
- 웹 표준 개발 논의 , 제정 : W3C (World Wide Web consortium



# HTML5

## Doctype

- HTML5의 실용성으로 인해 짧아졌다

```html
<!DOCTYPE html>
```

- 작성규칙

  - 대소문자 구분하지 않음

  - 콘텐츠와 구분을 위해 꺽쇠로 둘러싼다.

    ```
    <p>, <a>, <div>
    ```

  - 시작태그, 마침태그로 요소 범위 지정

  - 마침태그 없이 단독 사용 요소도 있음

    ```
    <br>, <img>, <meta>
    ```

  - 요소의 속성명은 속성명 = "속성값" 형식

    ```
    <img src="img/logo.jpg" alt="Company Logo">
    ```

- 기본 작성 순서

```html
<!Doctyle html>
<html>
	  <head>
	  </head>
	  <body>
    </body>
</html>

1. html은 html코드 전체를 감싼다.
2. head, body부분으로 나뉜다.
3. head에 메타데이터와 스크립, css등 위치함
4. body는 콘텐츠가 담기는 부분으로 웹브라우저에 표현됨.
```



### 메타데이터

- html 파일에 대한 정보를 기록하기 때문에 정확하고 자세하게 작성해야한다.

- 메타요소 : 요소가 필요없는 단독요소 <>안에 사용

  - `<meta name = "">` 이런식으로 사용한다
  - 메타데이터 종류는 description, keywords, author, copyright, reply-to, date 가 있다.
    - description : 주제, 파일의 간략 설명 기술
    - keywords : 키워드
    - author : 작성자
    - copyright : 저작권
    - reply-to : 연락처 메일
    - date : html파일 작성일 (국제 시간에 따른다)

  - 메타요소 중 문자 인코딩만 `<meta charset="">` 사용

### 웹페이지 구성요소

- html : 콘텐츠 구조 (뼈대)

- css : 콘텐츠의 레이아웃 

- javascript : 콘텐츠 작동 - 시각적인 효과 등

  #### 외부 CSS파일의 연결

  `<link rel = "stylsheet" type = "text/css" media = "screen" href = "css/style.css"`

  #### 외부 JavaScript 파일 연결

  `<script lauguage="javascript"></script>`

  `<script src= "js/script.js"></script>`	

  

