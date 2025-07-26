# Toss 클론 프로젝트

> Toss 공식 홈페이지를 참고하여 제작한 반응형 클론 웹사이트입니다.  
> 실제 서비스와 유사한 UI/UX 흐름을 분석하고, 시멘틱 구조 및 인터랙션까지 구현했습니다.

---

## 🔗 데모 사이트

👉 [https://toss-clone.netlify.app](https://toss-clone.netlify.app)

---

## 📌 주요 기능

- **GNB(Global Navigation Bar)**  
  상단 고정 내비게이션 구성 및 언어 전환 기능 구현

- **Hero 섹션**  
  앱 다운로드 버튼과 브랜드 메세지를 중심으로 구성

- **서비스 소개 섹션**  
  소비, 송금, 대출, 신용, 투자, 결제, 사업 등 핵심 서비스 흐름을 시각적으로 구성

- **GSAP 기반 인터랙션 (section07)**  
  마스크 애니메이션으로 양쪽 흰 박스가 열리며 이미지가 드러나는 효과 구현

- **IntersectionObserver 활용**  
  스크롤에 따라 섹션별 콘텐츠가 순차적으로 등장

- **jQuery 사용**  
  언어 선택 버튼의 클래스 토글 제어에 jQuery 사용  
  DOM 탐색 및 이벤트 처리에 간결함을 위해 일부 UI 인터랙션을 jQuery로 처리

- **반응형 대응**  
  모바일 / 태블릿 / 데스크탑 해상도에서 콘텐츠가 유연하게 동작하도록 설계

- **푸터 디렉토리 구조**  
  실제 토스 하단 메뉴와 동일한 카테고리 및 링크 구성

---

## 🛠 사용 기술

| 구분       | 기술 스택                                  |
| ---------- | ------------------------------------------ |
| 마크업     | HTML5 (Semantic 구조)                      |
| 스타일링   | SCSS (컴포넌트화 + 변수화)                 |
| 인터랙션   | JavaScript, **jQuery**                     |
| 애니메이션 | GSAP (ScrollTrigger), IntersectionObserver |
| 기타       | Netlify 배포                               |

---

## 📁 프로젝트 구조

toss-clone/
├── assets/
│ ├── css/
│ ├── images/
│ └── js/
├── index.html
├── gsap.html
└── README.md

yaml
복사
편집

---

## 💡 학습 포인트

- 실제 서비스의 UI 구조를 분석하고 시멘틱 마크업으로 구현하는 경험
- SCSS 모듈화 및 변수 관리를 통해 유지보수성과 확장성 향상
- GSAP 및 IntersectionObserver를 활용한 스크롤 기반 애니메이션 구현
- jQuery를 활용한 DOM 조작 및 클래스 토글 처리 경험

---

## 📜 라이센스

본 프로젝트는 **학습 및 포트폴리오 목적**으로 제작되었으며,  
상업적 사용은 금지됩니다.  
Toss 브랜드 및 로고, 콘텐츠는 Viva Republica의 자산입니다.
