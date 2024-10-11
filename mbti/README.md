# folder structure

        src/
        ├── components/
        │ ├── common/
        │ │ └── Button.js
        │ ├── layout/
        │ │ └── Header.js
        │ └── mbti/
        │ └── MBTITest.js
        ├── pages/
        │ ├── Home.js
        │ └── Result.js
        ├── hooks/
        │ └── useMBTI.js
        ├── utils/
        │ └── mbtiCalculator.js
        ├── styles/
        │ ├── global.css
        │ └── variables.css
        ├── constants/
        │ └── mbtiQuestions.js
        ├── services/
        │ └── api.js
        ├── context/
        │ └── MBTIContext.js
        ├── App.js
        └── index.js

# components

    - components/: 재사용 가능한 UI 컴포넌트들을 저장합니다.
    - pages/: 라우팅될 페이지 컴포넌트들을 저장합니다.
    - hooks/: 커스텀 훅을 저장합니다.
    - utils/: 유틸리티 함수들을 저장합니다.
    - styles/: 전역 스타일과 변수를 저장합니다.
    - constants/: 상수 값들을 저장합니다.
    - services/: API 호출 등의 서비스 로직을 저장합니다.
    - context/: React Context 관련 파일들을 저장합니다.
