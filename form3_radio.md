## radio 

- 단일 선택 
- 반드시 name속성과 value속성을 같이 써줘야 한다.
    - name속성을 통해 radio박스들을 같은 radio그룹으로 지정해 중복선택을 막는다.

    - value 속성을 통해 어떤 radio값이 선택되었는지를 서버가 알 수 있게 해준다.
        - url을 보면 name=value 형식으로 서버에 전송된값을 확인할 수 있다.


## 예시코드

    ```html
        <form action="#" method="GET">
        <label for="sub">구독중</label>
        <input type="radio" id="sub" name="subscription" value="sub">

        <label for="unsub">미구독</label>
        <input type="radio" id="unsub" name="subscription" value="unsub">
        
        <button type="submit">
            제출하기
        </button>
        </form>
    ```