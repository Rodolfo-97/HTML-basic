## checkbox

- 중복 선택이 가능하다.
- 반드시 name속성과 value속성을 같이 써줘야 한다.
    - name속성을 통해 checkbox박스들을 같은 checkbox그룹으로 지정해 중복선택을 막는다.

    - value 속성을 통해 어떤 checkbox값이 선택되었는지를 서버가 알 수 있게 해준다.
        - url을 보면 name=value 형식으로 서버에 전송된값을 확인할 수 있다.

- 사용하는 방법은 radio와 동일하다고 보면 된다.


## 예시코드

```html
    <h1>
        사용 가능 언어
    </h1>
    <form action="#" method="GET">
        <input type="checkbox" id="html" name="stacks"value="html">
        <label for="html">HTML</label>
        <input type="checkbox" id="css" name="stacks" value="css">
        <label for="css">CSS</label>
        <input type="checkbox" id="js" name="stacks" value="javascript">
        <label for="js">JAVASCRIPT</label>
        <button type="submit">
            제출하기
        </button>
    </form>
```