## select 태그

- 풀 다운 메뉴를 만들 때 사용함
- 자식태그인 option 태그를 이용해 메뉴 내용을 구성함

## 코드를 보자

```html
    <form action="#" method="GET">
        <label for="stacks">기술 스택</label>
        <select name="stacks" id="stacks">
            <option value="html">HTML</option>
            <option value="css">CSS</option>
            <option value="js">JAVASCRIPT</option>
        </select>
        <button type="submit">
            제출하기
        </button>
    </form>
```

- select에는 반드시 name을 주어야 하고 자식요소인 option태그에는 name속성을 줄 필요는 없다.
    - 어차피 option태그는 select에 속해 있기 때문이다.
    
- 서버가 어떤 값이 들어왔는지 구분할 수 있도록 반드시 option태그에 value값을 주어야 한다.
