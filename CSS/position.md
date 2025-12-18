## 🪅**position**

position 속성은 **문서 상에 요소를 배치하는 방법**을 지정한다. <br><br>

1\. **static** (default)

\- 일반적인 문서 흐름에 따라 배치

\- top, right, bottom, left, z-index 값 적용 X<br><br>

2. **relative**

\- 일반적인 문서 흐름에 따라 배치

\- top, right, bottom, left 값에 따라 오프셋 적용

\- 오프셋은 다른 요소에는 영향 주지 않음 → 요소가 차지하는 공간은 static일 때와 동일<br><br>

3\. **absolute**

\- 일반적인 문서 흐름에서 **제거**, **공간 배정 X**

\- 가까운 조상 요소를 기준으로 배치

\- 최종 위치는 top, right, bottom, left 값이 지정<br><br>

4\. **fixed**

\- 일반적인 문서 흐름에서 **제거**, **공간 배정 X**

\- 뷰포트의 초기 컨테이닝 블록을 기준으로 배치 (→ )  

\- 최종 위치는 top, right, bottom, left 값이 지정<br><br>

5\. **sticky**

\- 일반적인 문서 흐름에 따라 배치

\- 가까운 스크롤 조상(또는 뷰포트)을 기준으로 배치

\- top, right, bottom, left 값에 따라 오프셋 적용

\- 오프셋은 다른 요소에는 영향 주지 않음

\- 설정한 위치에 도달하면 화면에 고정

\- 부모 요소의 영역 안에서만 움직이며, 부모와 함께 사라짐<br><br><br><br><br><br>

참고

[\- https://developer.mozilla.org/ko/docs/Web/CSS/Reference/Properties/position](https://developer.mozilla.org/ko/docs/Web/CSS/Reference/Properties/position)
