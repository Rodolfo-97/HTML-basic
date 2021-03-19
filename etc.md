## 기타 태그들


### abbr 태그

- abbreviation은 약어(약자)란 뜻이다.

- 사용자에게 약자를 설명하고 싶을 때 사용한다.

- 반드시 title 속성을 써줘야 한다.

#### 예시 코드

```html
    <p>
        웹의 뼈대는 <abbr title="HyperText Markup Language">HTML</abbr> 입니다.
    </p>
```

- title 속성값으론 약어의 원형을 적어준다.


### address 태그

- 전화번호, 주소, 이메일, URL 등 연락망을 나타내는 태그이다.

#### 예시 코드

```html
    <address>
        <h1>Rodolfo</h1>
        <p>
            tel: 010-1234-5678
        </p>
    </address>
```


### pre 태그

- 여백이나 줄 바꿈 등 태그에 마크업한 내용을 있는 그대로 웹에 나타낸다.
    - 독특한 서식의 텍스트나 컴퓨터 코드 등을 HTML 문서에 그대로 표현할 수 있다.

#### 예시 코드

```html
    <pre>
        ㅇ ㅏ  ㄴ ㅕ  ㅎ ㅏ  ㅅ ㅔ  ㅇ
          ㄴ     ㅇ                 ㅛ .
    </pre>
```


### code 태그

- 태그명 그대로 코드를 나타낼 때 쓰이는 태그이다.

#### 예시 코드

```html
<p>
        다음은 자바 코드의 일부분 입니다.
    </p>
    <code>
        system.out.println("Hello Wolrd");
    </code>
```


### 컴퓨터코드는 여백이나 줄바꿈이 중요하기 때문에 code태그를 pre태그로 감싸서 쓰기도 한다.

#### 예시 코드

```html
    <p>
        다음은 자바 코드의 일부분 입니다.
    </p>
    <pre>
        <code>
            int total3 = 0;
			for(int i4=1; i4<=100; i4++) {
				if(i4%2==0) {
					total3 += i4;
				}
			}
        </code>
    </pre>
```
