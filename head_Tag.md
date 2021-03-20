## head태그

- body태그와 달리 문서를 나타내는 메타데이터를 정의한다.

### head 태그의 구성요소


#### title 태그

- 문서의 대제목
- 웹 상단 tap에 들어갈 내용을 마크업 한다.

##### 예시코드

```html
<head>
    <title>웹의 tap입니다.</title>
</head>
```

#### link 태그

- <link> 태그는 해당 문서에 외부 소스(external resource)를 불러올 때 사용한다.
   - 주로 css스타일시트 또는 font를 첨부할 때 사용한다.

##### 예시코드

```html
<head>
    <link rel="stylesheet" href="첨부할 파일이 있는 경로">
</head>
```

#### style 태그 

- html 문서 내에서 css코드를 작성할 때 사용한다.
    
- html 파일이 문서로써의 역할에 충실할 수 있게 하기 위하여 해당 태그를 사용하지 않고 css 파일을 따로 만들어
link태그로 연결하는 것이 선호된다.

##### 예시코드

```html
<head>
    <style>
        body { background-color: lightpink }
        h1 { color: red; }
        p { text-decoration: underline; }
    </style>
</head>
```

#### script 태그

- html 문서내에서 javascript코드를 작성할 때 또는 외부에서 가져올 때 사용한다.

- **head가 아니라 body태그 안**에 작성된다.

    - 웹브라우저가 script태그의 외부 파일을 다운로드 할 때 link태그와 달리 script태그는 스킵하지 않는데
    만약 script태그가 head안에 있다면 script태그의 외부 파일이 다운로드 될때까지 html문서의 다운이 진행되지 않는다.
    그러므로 javascript 코드를 html 문서내에서 작성할 때는 **body태그의 가장 밑**에 적어주는 것이 좋다.

##### 예시코드1: 외부에서 javascript코드를 가져올 때. 

```html
<script src="파일이 있는 경로"></script>
```

##### 예시코드2: html 문서내에서 javascript코드를 작성할 때.

```html
<script>
    html 문서내에 적어줄 javascript코드
</script>
```

