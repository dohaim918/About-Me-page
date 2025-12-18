
> **"디자인의 의도를 이해하고, 견고한 구조로 구현하는 프런트엔드 개발자 김도하입니다."**

본 프로젝트는 단순한 자기소개 페이지를 넘어, **디자인 가이드라인을 실제 웹 환경에서 어떻게 가장 효율적으로 구현할 것인가**에 대한 고민을 담은 프로젝트입니다. 시각적 균형과 코드의 구조적 안정성을 동시에 확보하는 데 집중했습니다.

## 🔗 Project Overview
- **개발 기간**: 2025.12.12 ~ 12.18
- **주요 목표**: 
  - 피그마(Figma) 디자인의 100% 구현
  - 유지보수가 용이한 HTML/CSS 구조 설계
  - 사용자 시나리오에 따른 자연스러운 시선 흐름(Flow) 구축

## 🛠 Tech Stack
<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white"/>
</p>

---

## 💡 Key Design & Development Points

### 1. 설계 단계: 디자인과 개발의 간극 줄이기
- **Grid & Alignment**: 작업 시작 전 피그마에서 그리드 라인을 설정하여 레이아웃의 규칙을 정의했습니다. 
- **Component Thinking**: 디자인 단계부터 `div` 구조와 `padding/margin` 값을 계산하여, '예쁜 화면'이 아닌 '구현 가능한 화면'을 설계했습니다.

### 2. 레이아웃: 사용자 경험을 고려한 시선의 흐름
- **PC-First & Navigation**: 상단 네비게이션을 고정(Fixed)하여 접근성을 높였고, 스크롤에 따라 정보가 자연스럽게 이어지도록 구성했습니다.
- **Card UI**: 복잡한 정보(Education, Experience 등)를 카드 형태로 모듈화하여 가독성을 극대화했습니다.

### 3. 기술적 최적화: 시멘틱 구조를 활용한 깔끔한 마크업
- **Pseudo-elements & SVG**: 단순 꾸밈 요소로 인해 HTML이 복잡해지는 것을 방지하기 위해 가상 요소(`::before`, `::after`)와 배경 이미지 처리를 적극 활용했습니다.
- **Clean Code**: 장식 요소가 콘텐츠 읽기를 방해하지 않도록 HTML 구조를 단순하게 유지했습니다.

---

## 🔥 Challenges & Solutions

### 📱 유동적 레이아웃과 반응형 대응의 고민
**Problem**: 초기 설계 시 `vw`, `%` 단위를 남용하여 화면 크기 변화 시 요소들이 의도치 않게 겹치거나 정렬이 깨지는 문제가 발생했습니다.

**Solution**:
- **전략 수정**: 무분별한 `flex` 사용을 지양하고, `max-width`와 `width: 100%` 조합을 통해 전체 컨테이너의 안정성을 먼저 확보했습니다.
- **Layout Logic**: `Auto-fit` 개념을 도입하여 공간 부족 시 요소들이 자연스럽게 하단으로 떨어지도록 구현했습니다.
- **Soft Transition**: 레이아웃이 변하는 브레이크 포인트에 `transition`을 적용하여 사용자에게 부드러운 시각적 경험을 제공했습니다.

---

## 🎤 Retrospective: 무엇을 배웠는가?
> "디자인을 코드로 옮기는 것은 단순히 배치를 복사하는 것이 아니라, 수많은 선택과 논리적인 판단의 연속임을 깨달았습니다."

이번 프로젝트를 통해 **디자인 시스템의 기초**와 **반응형 웹의 구조적 원리**를 깊이 있게 이해하게 되었습니다. 단순히 화려한 화면보다는 서비스의 목적에 맞는 견고한 구조와 접근성을 고려하는 개발자가 되는 것이 저의 목표입니다.

---

## 📸 Screen Shots
<img width="1856" height="3211" alt="image" src="https://github.com/user-attachments/assets/e0ea6686-3fa1-4c25-a84f-f3deb38414e9" />

---
Copyright © 2025 Kim Doha. All rights reserved.
