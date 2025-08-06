# The_Room

### 파일 구조
```
root/
├── public/ # 정적 리소스 (favicon, 텍스처 등)
│ └── assets/ # 외부 이미지, 모델 파일
├── src/
│ ├── assets/ # 내부 리소스 (이미지, 모델 등)
│ ├── components/ # UI 컴포넌트
│ │ └── common/ # 공통 요소 (버튼 등)
│ ├── hooks/ # 커스텀 훅
│ ├── scenes/ # Three.js Scene 및 객체 구성
│ ├── styles/ # 전역/모듈 스타일
│ ├── utils/ # 유틸 함수 모음
│ ├── App.jsx # 메인 컴포넌트
│ └── main.jsx # 진입점
├── .gitignore
├── index.html
├── package.json
└── vite.config.js
```