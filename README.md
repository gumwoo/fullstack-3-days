오늘의 학습일기 :css

2023년 12월 28일

오늘은 CSS에 대한 깊이 있는 학습을 진행했다.
'Gungle'이라는 나만의 검색 페이지를 만들면서, CSS의 각종 속성과 스타일링 기법에 집중했다.
특히, 구글의 인터페이스를 모방하여 Roboto 폰트와 색상 있는 글자로 로고를 디자인하는 과정에서, CSS 선택자의 다양한 활용 방법을 배웠다.
입력 필드와 버튼의 배치 및 스타일링을 통해 위치 지정의 개념을 확실히 이해하게 되었고, position 속성의 absolute와 relative 값의 차이점을 몸소 체험했다.
또한, CSS 박스 모델에 대한 이해를 바탕으로 테두리와 여백을 조절하는 방법을 연습했다. 
내일은 더 복잡한 레이아웃과 반응형 디자인에 도전해볼 것이다.
오늘 하루 동안 CSS에 대한 새로운 지식을 습득하고, 직접 코딩을 통해 학습한 내용을 실제로 적용해보며 많은 것을 배울 수 있었다.

오늘은 CSS에 대한 깊이 있는 학습을 진행했다. 'Gungle'이라는 나만의 검색 페이지를 만들면서, CSS의 각종 속성과 스타일링 기법에 집중했다. 특히, 구글의 인터페이스를 모방하여 Roboto 폰트와 색상 있는 글자로 로고를 디자인하는 과정에서, CSS 선택자의 다양한 활용 방법을 배웠다. 입력 필드와 버튼의 배치 및 스타일링을 통해 위치 지정의 개념을 확실히 이해하게 되었고, position 속성의 absolute와 relative 값의 차이점을 몸소 체험했다. 또한, CSS 박스 모델에 대한 이해를 바탕으로 테두리와 여백을 조절하는 방법을 연습했다. 내일은 더 복잡한 레이아웃과 반응형 디자인에 도전해볼 것이다. 오늘 하루 동안 CSS에 대한 새로운 지식을 습득하고, 직접 코딩을 통해 학습한 내용을 실제로 적용해보며 많은 것을 배울 수 있었다.

여기에는 제가 오늘 작업한 CSS 코드의 일부를 공유합니다:

```css
/* 로고 스타일링 */
.logo {
  font-family: 'Roboto', sans-serif;
  color: #4285F4; /* Google Blue */
  font-size: 36px;
}

/* 입력 필드 스타일링 */
.search-input {
  width: 100%;
  padding: 8px;
  margin-bottom: 20px;
  border: 1px solid #ddd;
}

/* 버튼 스타일링 */
.search-button {
  padding: 10px 20px;
  background-color: #4285F4;
  color: white;
  border: none;
  cursor: pointer;
}

/* 위치 지정 예시 */
.search-container {
  position: relative;
}

.search-icon {
  position: absolute;
  top: 10px;
  right: 10px;
}






