## Label 태그

- input 태그에 이름(label)을 붙여주는 태그, 부가적인 태그이기 때문에 반드시 사용하지 않아도 된다.
- 어떠한 input 과 관련있는지 연결해야한다.
    - 이때 사용하는 속성이 for 속성이다.

    ```html
        <label for="user-name">이름</label>
        <input type="text" id="user-name" placeholder="이름" required>
    ```

    - 코드를 보면 input태그에 id값을 주고 label태그의 for의 값으로 iuput태그의 id값이 온다는 것을 알 수 있다.
        - id값을 적을때 #을 쓰지않는다.

- label코드의 컨텐츠를 누르면 해당 라벨이 가르키는 입력값으로 입력바가 이동하기 때문에 미약하지만 편의성을 높일 수 있다.


## 예시코드

    ```html
        <form action="#" method="POST">
            <label for="user-name">이름</label>
            <input type="text" id="user-name" placeholder="이름" required>

            <label for="user-id">아이디</label>
            <input type="text" id="user-id" minlength="5" maxlength="10" placeholder="최소 5자,최대 10자" required>

            <label for="user-pwd">비밀번호</label>
            <input type="password" id="user-pwd" minlength="6" maxlength="12" placeholder="최소 6자,최대 12자" required>

            <label for="user-email">이메일</label>
            <input type="email" id="user-email" placeholder="이메일">

            <label for="user-tel">전화번호</label>
            <input type="tel" id="user-tel" placeholder="전화번호(***-****-****)" required pattern="[0-9]{3}-[0-9]{4}-[0-9]{4}">

            <label for="user-age">만 나이</label>
            <input type="number" id="user-age" min="12" max="122" placeholder="12세 이상 122세 이하">         
            
            <label for="user-profile">프로필 사진</label>

            <input type="file" id="user-profile" accept=".png,.jpg" placeholder="PNG,JPG만 허용">
            <button type="submit">
                가입하기
            </button>
        </form>
    ```
