<!-- Gatsby는 JAM
Javscript API M  -->

Gatsby Link API의 성능상 이점

Gatsby는 Prefetch를 통해 페이지에서 사용할 리소스의 로딩 속도를 높인다고 합니다.

그럼 어떻게 페이지를 찾고 Prefetch를 진행할까요?

이를 위한 것이 바로 Gatsby Link API에서 제공하는 Link 컴포넌트입니다.

페이지가 로드되면 Gatsby는 리소스 로드 속도를 높이기 위해 현재 페이지에서 사용되는 모든 링크를 찾은 후, 각 링크의 페이지를 미리 로드하기 시작합니다.

우리가 생성한 프로젝트에서 확인해보면 메인 페이지의 로딩이 완료되면, Gatsby는 /info 링크를 찾고, 이 페이지를 미리 로드하는 것이죠.

이를 통해 Gatsby는 더 높은 사용자 경험을 제공할 수 있는 것입니다.

---

그러다 EmotionJS 라이브러리가 등장했는데 해당 라이브러리는 styled-components의 기능을 거의 동일하게 사용할 수 있었을 뿐더러, 추가적으로 라이브러리를 설치해 손쉽게 기능 확장이 가능합니다.

하지만 제일 중요한 점은 이런 기능을 그대로 구현한 라이브러리의 번들 용량이 다른 라이브러리에 비해 압도적으로 작다는 것입니다.

따라서 저희는 이번 강의에서 EmotionJS를 통해 스타일링을 진행하겠습니다.

---

글로벌 스타일 지정 방법
Tagged Template Literal 방식을 통한 CSS 정의 및 적용 방법
Tagged Template Literal 방식을 통한 Styled Component 생성 방법
객체를 통한 Styled Component 생성 방법
Styled Component에서 Props를 받아 처리하는 방법