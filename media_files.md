## Media Files

- text가 아닌 여러가지 미디어를 html에 삽입할 떄 사용한다.

### audio태그

#### audio 파일을 삽입하는 2가지 방법

##### 1번째

```html
<audio src="./assets/audio/kimbug.mp3" controls></audio>
```
- control(사용자가 음성재생을 control 할수있음)과 autoplay(자동재생) 속성이 있다.

##### 2번째 
- source를 속성이 아니라 태그로서 적어준다.

```html
<audio controls>
        <source src="./assets/audio/kimbug.mp3" type="audio/mp3">
        <source src="./assets/audio/kimbug.ogg" type="audio/ogg">
        <source src="./assets/audio/kimbug.wav" type="audio/wav">
        <p>
            크롬 브라우져로 앵간하면 바꾸세요....
        </p>
    </audio>
```

- source를 태그로서 사용할때 src속성과 type속성을 반드시 적어준다.

- 첫번째 경로의 파일이 방문자의 브라우저에서 호환이 안될때 다음에에 작성해둔 파일이 대신 재생된다.
    - 여기에서는 모든 음성파일이 재생안될때 p태그를 보여주도록 했다.
    
- 2번째 방법이 쫌 더 사용자를 배려한 방법인 것 같다.



### video태그

- audio태그와 이름만 다르지 나머지는 다 똑같다.

#### 1번째 방법

```html
<video src="./assets/video/kimbug.mov" controls></video>    
```

#### 2번째 방법

```html
<video controls>
        <source src="./assets/video/kimbug.mov" type="video/mp4">
        <source src="./assets/video/kimbug.mp4" type="video/mp4">
        <p>
            크롬으로 바꾸세요~~
        </p>
    </video>
```



### iframe태그

- html안에 다른 html 또는 컨텐츠를 삽입할 때 쓴다.

```html
<iframe width="560" height="315" src="https://www.youtube.com/embed/BsPV5gFsGmg" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
</iframe>
```

- 유튜브나 트위터같은 사이트의 공유버튼을 누르면 iframe코드가 있는데 그걸 걍 복사 붙이기 하면 해당 컨텐츠가 웹사이트에 삽입된다.