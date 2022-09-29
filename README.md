# HTML, CSS로 캐릭터 만들기

**흐물이**

![흐물이](./%ED%9D%90%EB%AC%BC%EC%9D%B4.gif)

[보러 가기](https://custardcream98.github.io/CSS-Character-Heumuri/)

## 배운점

1. CSS에서 `import` 구문은 꼭 문서의 최상단에 있을때만 작동합니다.
2. CSS animation은 잘개 쪼갤수록 다루기 편했습니다.
3. 한 요소에 여러 animation keyframes를 줄 수 있습니다.
4. `z-index`, `position` 등의 property의 작동법에 대해 다시 한번 익혔습니다.

## 개선해야 할 점

![흐물이v1](./%ED%9D%90%EB%AC%BC%EC%9D%B4v1.gif)

1. 흐물이는 `scale3d` CSS 함수를 이용해 사이즈가 조절되는데, 이 때 pixel 차이로 인해 미세한 갭이 생깁니다. 이로 인해 네 개의 div 요소로 표현하던 부분을 하나의 div 요소로 바꿀 수 밖에 없었습니다. 다소 단조로운 모양이 돼버려 아쉽습니다.
