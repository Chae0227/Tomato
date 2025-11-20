# 🍅 TOMATO — HERE COMES TOMATO!

**https://tomatomato-mato.netlify.app/**  

토마토 감성으로 꽉 채운 인터랙티브 웹 프로젝트입니다.  
다양한 토마토 소개, 레시피 카드, 랜덤 토마토 지식, 인터랙티브 모션 등  
스크롤할수록 즐거운 토마토 세계가 펼쳐집니다!

---

## 🧑‍💻 Team

| 역할 | 이름 | 소개 |
|------|------|------|
| Front-end 개발 | **김은채 (한림대학교 콘텐츠IT 21학번)** | 전체 페이지 구성, 인터랙션, 애니메이션, JS 로직 구현 |
| UI / Visual Design | **김은진 (서울여자대학교 산업디자인과 24학번)** | 전체 디자인 기획, Figma 아트워크, 이미지 제작, 컬러/레이아웃 디자인 |

📌 전체 디자인(이미지 포함)은 김은진이 Figma로 제작 →  
Figma 링크: https://www.figma.com/design/6SzEtAaPWQyoden2YZqOgp

---

## 📁 Sections

### 1. 🍅 `#hero` — Main Hero  
**기능**
- 메인 인트로 화면  
- 토마토 이미지 + "HERE COMES TOMATO!"  
- 인용문: *“You say tomato. I say tomato.”*

**디자인 요소**
- 전체 붉은 배경  
- 중앙 정렬  
- 폰트: **Amatic SC**  
- 감성적인 층위 강조

---

### 2. 🍅 `#meet-me` — Meet Me, Tomato!  
**기능**
- 다양한 토마토 종류 소개  
- 마우스 호버 → 접시(plate.png) + 설명 툴팁 등장  
- 상세 정보: 특징 / 보관법 / 영양 정보

**애니메이션**
- 상단 토마토(rotating_tomato.png) 무한 회전 (`@keyframes spin`)  
- hover 시 슬라이드 등장

---

### 3. 🍅 `#tasty` — TomaTasty!  
**기능**
- 슬라이드형 토마토 요리 레시피 카드  
- 3개 카드가 한 화면에 표시  
- 좌/우 슬라이드 버튼으로 이동  
- `< RECIPE >` 버튼 → 외부 링크 이동

---

### 4. 🍅 `#pick` — Pick My Plate!  
**기능**
- 클릭 시 랜덤 레시피 카드 생성  
- 이미지, 제목, 해시태그, 링크 포함  
- 두 번째 클릭 → 카드 닫힘

**애니메이션**
- 카드가 translateY로 위로 튀어오름  
- confetti 라이브러리로 파티클 폭죽 효과

---

### 5. 🍅 `#secret` — MY SECRET…  
**기능**
- 토마토맨 클릭 → 랜덤 토마토 지식 팝업  
  예: “토마토는 사실 과일이다!”

**인터랙션**
- 캐릭터 클릭하면 swing 애니메이션  
- 문구는 `secrets[]` 배열에서 랜덤 선택

---

## 🧭 공통 기능

### 🔻 네비게이션
- 스크롤 시 sticky 전환 (`.scrolled` 클래스)
- 섹션 id에 바로 이동 anchors

### 🔻 커서 커스터마이징
- tomato_cursor.png로 모든 페이지 영역에서 커서 대체

---

## 🚀 배포
- **Netlify**  
- 자동 빌드 & 실시간 반영  
- URL: https://tomatomato-mato.netlify.app/

---

## 📜 라이선스
본 프로젝트의 모든 **UI / 이미지 디자인은 김은진(서울여대 산업디자인과)**이 제작하였습니다.  
무단 도용 금지.  
