# React TypeScript Styled-Components Boilerplate

🎉 **React + TypeScript + Styled-Components 보일러플레이트** 🎉  
이 프로젝트는 React 애플리케이션 개발을 빠르게 시작하기 위해 설정된 템플릿입니다. TypeScript와 Styled-Components를 활용하여 타입 안정성과 스타일링 유연성을 제공합니다.

---

## 📦 프로젝트 구성

```text
src/
├── apis/             # API 요청 관련 코드
│   └── utils/
│       └── instance.ts  # Axios 인스턴스 설정
├── assets/           # 정적 리소스 (이미지, 폰트 등)
│   ├── fonts/
│   │   └── fonts.css   # 웹 폰트 스타일
│   └── react.svg       # React 로고
├── components/       # 재사용 가능한 UI 컴포넌트
│   └── temp.txt
├── pages/            # 페이지 단위 컴포넌트
│   └── index/
│       └── Home.tsx    # 홈 페이지
├── store/            # Redux Toolkit 관련 파일
│   ├── store.ts       # Redux 스토어 설정
│   └── userSlice.ts   # Redux 슬라이스 예제
├── styles/           # 글로벌 및 테마 스타일
│   ├── theme/
│   │   └── Theme.ts    # Styled-Components 테마 설정
│   └── GlobalStyle.tsx # 글로벌 스타일 설정
├── utils/            # 유틸리티 함수 모음
│   └── temp.txt
├── App.tsx           # 메인 앱 컴포넌트
├── main.tsx          # 진입 파일
└── vite-env.d.ts     # Vite 환경 설정

```


## 🛠️ 설치 및 실행

### 1. 레포지토리 클론
```zsh
git clone https://github.com/Anhye0n/react-ts-boilerplate.git
