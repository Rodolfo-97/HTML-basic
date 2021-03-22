## button 태그

- 말 그대로 버튼을 만드는 태그이다.

- 반드시 type 속성을 적어주어야 하는데 type값으론 button, submit, reset 등이 있다.

### 아래 코드를 보자.

#### button 타입

```html
        <button type="button">
            버튼
        </button>
```

- javascript로 버튼의 상태(눌렀을때)를 조건으로 특수한 효과를 줄 수 있다고 한다.

- type으로 submit과 reset을 사용하지 않는다면 button 타입을 적어준다고 보면 된다.


#### submit 타입

```html     
        <button type="submit">
            제출
        </button>
```

- form 안에 있는 입력값들을 서버로 보낸다.

- type 속성을 적어주지 않으면 자동으로 submit 타입으로 설정된다.


#### reset 타입

```html
        <button type="reset">
            다시쓰기
        </button>
```

- 입력해 놓았던 값들을 리셋시킨다. 
