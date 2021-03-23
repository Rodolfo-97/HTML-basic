## form 태그

- 입력양식 전체를 감싸는 태그. 
- 사용자로부터 input을 받기위한 태그.

### form 태그의 속성들

    - name : form의 이름, 서버로 보내질 때 이름의 값으로 데이터 전송
    - action: 사용자가 입력한 값을 보낼 주소
    - method: 입력값의 전송방법
        - post(url에 입력값을 숨김)과 get(url에 입력값이 나타남)
            - post는 보내는 데이터의 길이 제한이 없지만 get은 길이 제한이 있다.
    - autocomplete : 자동 완성. on으로 하면 form 전체에 자동 완성 허용

## input 태그 

    - form태그의 내부에서 어떤 형식의 입력값을 받는지 결정함

### input 태그의 속성들

    - type: 입력받는 값이 어떤 형식인지 정함
        - input type의 값들
            - text: 텍스트를 받음
            - password: 입력값이 보이지 않음
            - email: 이메일 형식의 입력값을 받음
            - reset: form에 입력한 모든 데이터 삭제
            - radio: 단일 선택
            - checkbox: 다중 선택
            - file: 파일 업로드
            - hidden: 눈에 보이지 않는 정보를 서버로 보냄
            - number: 숫자를 입력값으로 받음
    
    - placeholder: 입력박스에 안내문을 넣음

    - value: 입력박스에 초기값을 설정

    - minlength, maxlength: 입력값의 길이의 최댓값 최소값 설정

    - min, max 입력한 숫자의 최댓값 최솟값 설정

    - accept: 입력받을 파일의 확장자를 제한할 수 있다.


## 예시코드

```html
    <form action="" method="POST">
        이름        <input type="text">
        아이디      <input type="text" minlength="5" maxlength="10" placeholder="최소 5자,최대 10자" required>
        비밀번호    <input type="password" minlength="6" maxlength="12" placeholder="최소 6자,최대 12자" required>
        이메일      <input type="email">
        만 나이     <input type="number" min="12" max="122" placeholder="12세 이상 122세 이하">
        프로필 사진 <input type="file" accept=".png,.jpg" placeholder="PNG,JPG만 허용">
                    <input type="submit">
    </form>
```
