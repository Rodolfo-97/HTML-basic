## meta 태그

- meta 태그는 base, link, script, style, title등 태그들이 나타낼 수 없는 다양한 종류의 메타데이터를 제공할 때 사용된다.

- meta 요소는 언제나 head 요소 내부에 위치해야 한다.

- name 속성이나 http-equiv 속성이 명시되었다면 반드시 content 속성도 함께 명시되어야 하며, 반대로 두 속성이 명시되지 않았다면 content 속성 또한 명시될 수 없다.

### meta 태그를 사용한 여러가지 예시들.


#### 예시코드1: 검색 엔진을 위한 키워드(keyword)를 정의

```html
<meta name="keyword" content="키워드로 사용할 text 입력">
```

#### 예시코드2: 웹 페이지에 대한 설명(description)을 정의

```html
<meta name="description" content="웹 페이지 설명">
```

#### 예시코드3: 문서의 저자(author)를 정의

```html
<meta name="author" content="Rodolfo">
```

#### 예시코드4: 모든 장치에서 웹 사이트가 잘 보이도록 뷰포트(viewport)를 설정

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```
- initial-scale=1.0" 은 처음 보이는 화면의 배율을 나타낸다.

#### 예시코드5: HTML 문서의 문자 인코딩 방식을 명시.

```html
<meta charset="UTF-8">
```
- UTF-8 방식으로 인코딩하지 않으면 웹 페이지으 text들이 꺠질 수 있다.

#### 예시코드6: 5초 뒤에 다른 페이지로 리다이렉트(redirect)시키는 예제

```html
<meta http-equiv="refresh" content="5;url=http://www.google.com">
```

