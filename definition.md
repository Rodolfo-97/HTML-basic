## Definition List

*언제 사용해야하나?
    *정의형 목록을 만들 때 사용.
    *key - value로 정보를 제공할 때 사용 

```html
<dl>
    <dt>
        학습 學習 [학씁]
    </dt>
    <dd>
        1. noun 배워서 익힘.
    </dd>
    <dd>    
        2. noun 심리 경험의 결과로 나타나는, 비교적 지속적인 행동의 변화나 그 잠재력의 변화. 또는 지식을 습득하는 과정
    </dd>
</dl>
```
### dl태그: Definition List로 정의 목록을 나타내는 태그이다.

### dt태그: Definition Term으로 정의할 용어를 나타낸다.

### dd태그: Definition Description 정의된 제목(dt태그)에 대한 설명을 나타낸다.


## 주의사항

- dl태그의 직계자식으로는 반드시 dt, dd, div 태그만 올 수 있다.
- dt와 dd가 반드시 쌍을 이뤄야 하는 것은 아니지만 dt태그가 나오고 dd태그가 해당 dt태그를 설명한 뒤에 
새로운 dt태그만 한번 더 나와선 안된다. 마지막은 dd로 끝나야한다.
