## 🪅**display**

display 속성은 요소의 내부 및 외부 표시 유형을 설정하는데,

**외부** 유형은 **요소의 레이아웃 흐름 참여 여부**를 설정하고

**내부** 유형은 **자식 요소의 레이아웃**을 설정한다.
<br><br>
### **\*Outside** \- 내 주변 요소들과 어떻게 어울릴까?<br><br>

1\. **block**

\- 블록 상자를 생성

\- 일반적인 흐름에서 요소 앞뒤에 줄 바꿈을 생성<br><br>

2\. **inline**

\- 줄 바꿈을 생성하지 않는 하나 이상의 인라인 박스 생성

\- 일반적인 흐름에서는 공간이 있는 경우 다음 요소가 같은 줄에 표시됨<br><br>

\+ Multi-keyword를 지원하는 브라우저에서 외부 값만 존재할 경우, 내부 값은 **flow**로 설정됨
<br><br>
### **\*Inside** \- 내 자식들을 어떻게 배치할까?<br><br>

1\. **flow**

\- 특별한 레이아웃(flex, grid)을 지정하지 않았을 때의 기본 동작

\- 주변 환경에 따라 block이 될지 inline이 될지 결정됨<br><br>

2\. **flex**

\- 자식 요소를 한 줄(가로 or 세로)로 배치\]

\- 형제 요소와는 위아래로 쌓이지만, 자식 요소는 유연하게 배치<br><br>

3\. **grid**

\- 자식 요소를 바둑판(가로+세로)처럼 배치

\- 형제 요소와는 위아래로 쌓이지만, 자식 요소는 유연하게 배치<br><br>

\+ Multi-keyword를 지원하는 브라우저에서 내부 값만 존재할 경우, 외부 값은 **block**으로 설정됨
<br><br>
### **\*Box** - 나라는 상자를 화면에 그릴까 말까?<br><br>

1\. contents

\- 본인의 상자는 생성 X, 자식 요소의 상자만 생성 O

\- 부모-자식 관계에서 자신은 건너뛰고, 자식은 조부모 요소의 레이아웃 규칙에 영향 받음 <br><br>

2\. none

\- 상자 자체가 생성되지 않음 → 공간 차지 X
<br><br><br><br>

참고

\- [https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/display](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/display)

