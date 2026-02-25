# Proby Design System

  

## 개요

  

Proby Design System은 미니멀리스트 미학과 기능적 우수성을 결합한 고대비 블랙 디자인 시스템입니다. 깊은 블랙과 선명한 타이포그래피에 중점을 둔 프리미엄 구조화된 디자인 시스템입니다.

  

---

  

## 1. 색상 팔레트 (Color Palette)

  

### Primary Colors

- **Primary Black**: `#000000`

- 주요 브랜드 컬러

- 버튼, 강조 요소, 아이콘에 사용

  

### Background Colors

- **Background Light**: `#f7f7f7`

- 라이트 모드 배경색

- **Background Dark**: `#191919`

- 다크 모드 배경색

  

### Neutral Colors

- **Pure White**: `#FFFFFF`

- 카드 배경, 텍스트 (다크 모드)

- **Surface Light**: `#F1F5F9`

- 라이트 서페이스

- **Slate Neutral**: `#94A3B8`

- 중립 회색

- **Slate Dark**: `#334155`

- 다크 회색

  

### Text Colors

- **Primary Text (Light)**: `slate-900` (`#0f172a`)

- **Primary Text (Dark)**: `white` (`#ffffff`)

- **Secondary Text (Light)**: `slate-500` (`#64748b`)

- **Secondary Text (Dark)**: `slate-400` (`#94a3b8`)

  

### Border Colors

- **Light Mode**: `slate-200` (`#e2e8f0`)

- **Dark Mode**: `slate-800` (`#1e293b`)

  

---

  

## 2. 타이포그래피 (Typography)

  

### 폰트 패밀리

  

#### Proby Design System (Primary)

- **Display Font**: `Pretendard`

- **Weights**: 100, 200, 300, 400, 500, 600, 700, 800, 900

- **Usage**: 모든 UI 텍스트 (한국어 최적화)

- **CDN**: `https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/static/pretendard-dynamic-subset.css`

- **Fallback**: `-apple-system, BlinkMacSystemFont, system-ui, Roboto, Helvetica Neue, Segoe UI, Apple SD Gothic Neo, Noto Sans KR, Malgun Gothic, sans-serif`

  

#### UI Pattern Library: Minimalist Black

- **Display Font**: `Manrope`

- **Weights**: 300, 400, 500, 600, 700, 800

- **Usage**: 모든 UI 텍스트

  

#### Proby-Inspired Black Design System

- **Display Font**: `Inter`

- **Weights**: 300, 400, 500, 600, 700, 800, 900

- **Usage**: 모든 UI 텍스트

  

### 타이포그래피 스케일

  

#### Heading 1

- **Font**: Pretendard Extra Bold / Inter Extra Bold / Manrope Extra Bold

- **Size**: `48px` / `text-5xl` / `text-6xl`

- **Weight**: `900` (font-black)

- **Tracking**: `tight` / `tighter`

- **Usage**: 메인 헤드라인, 히어로 섹션

  

#### Heading 2

- **Font**: Pretendard Bold / Inter Bold / Manrope Bold

- **Size**: `30px` / `text-3xl` / `text-2xl`

- **Weight**: `700` (font-bold) / `800` (font-extrabold)

- **Tracking**: `tight`

- **Usage**: 섹션 헤더

  

#### Heading 3

- **Font**: Pretendard Bold / Inter Bold / Manrope Bold

- **Size**: `20px` / `text-xl`

- **Weight**: `700` (font-bold)

- **Usage**: 카드 제목, 서브헤더

  

#### Heading 4

- **Font**: Pretendard Semibold / Inter Semibold / Manrope Semibold

- **Size**: `18px` / `text-lg`

- **Weight**: `600` (font-semibold)

- **Usage**: 작은 헤더

  

#### Body Text

- **Font**: Pretendard Regular / Inter Regular / Manrope Regular

- **Size**: `16px` / `text-base`

- **Weight**: `400` (font-normal)

- **Color**: `slate-600` (light) / `slate-400` (dark)

- **Usage**: 본문 텍스트

  

#### Small Text / Caption

- **Font**: Pretendard Medium / Inter Medium / Manrope Medium

- **Size**: `14px` / `text-sm`

- **Weight**: `500` (font-medium)

- **Case**: `uppercase` (캡션의 경우)

- **Tracking**: `wider` / `widest`

- **Usage**: 캡션, 라벨, 메타 정보

  

#### Extra Small Text

- **Font**: Pretendard Bold / Inter Bold / Manrope Bold

- **Size**: `10px` / `text-[10px]`

- **Weight**: `800` (font-black)

- **Case**: `uppercase`

- **Tracking**: `[0.2em]` / `widest`

- **Usage**: 카테고리 라벨, 태그

  

---

  

## 3. 간격 시스템 (Spacing)

  

### Tailwind Spacing Scale 사용

- **xs**: `0.25rem` (4px)

- **sm**: `0.5rem` (8px)

- **base**: `1rem` (16px)

- **lg**: `1.5rem` (24px)

- **xl**: `2rem` (32px)

- **2xl**: `3rem` (48px)

  

### 주요 간격 패턴

- **Section Spacing**: `mb-20` (5rem / 80px)

- **Card Padding**: `p-6` ~ `p-8` (1.5rem ~ 2rem)

- **Element Gap**: `gap-3` ~ `gap-8` (0.75rem ~ 2rem)

- **Header Padding**: `px-6 lg:px-20 py-4`

- **Main Content Padding**: `px-6 lg:px-20 py-12`

  

---

  

## 4. 보더 반경 (Border Radius)

  

- **DEFAULT**: `0.25rem` (4px) - `rounded`

- **lg**: `0.5rem` (8px) - `rounded-lg`

- **xl**: `0.75rem` (12px) - `rounded-xl`

- **2xl**: `1rem` (16px) - `rounded-2xl`

- **full**: `9999px` - `rounded-full` (완전한 원형)

  

### 사용 패턴

- **Buttons**: `rounded-lg`

- **Cards**: `rounded-xl` / `rounded-2xl`

- **Inputs**: `rounded-lg`

- **Avatars**: `rounded-full`

- **Badges**: `rounded-full` / `rounded`

  

---

  

## 5. 컴포넌트 스타일

  

### 버튼 (Buttons)

  

#### Primary Button

```css

background: #000000 (primary)

color: white

height: 48px (h-12)

padding: 0 32px (px-8)

border-radius: 0.5rem (rounded-lg)

font-weight: 700 (font-bold)

hover: bg-slate-800

```

  

#### Outlined Button

```css

border: 2px solid #000000

color: #000000

background: transparent

height: 48px (h-12)

padding: 0 32px (px-8)

border-radius: 0.5rem (rounded-lg)

font-weight: 700 (font-bold)

hover: bg-slate-50

```

  

#### Ghost Button

```css

color: #000000

background: transparent

height: 48px (h-12)

padding: 0 32px (px-8)

border-radius: 0.5rem (rounded-lg)

font-weight: 700 (font-bold)

hover: bg-slate-100

```

  

#### Secondary Button

```css

background: slate-100

color: slate-900

height: 48px (h-12)

padding: 0 32px (px-8)

border-radius: 0.5rem (rounded-lg)

font-weight: 700 (font-bold)

hover: bg-slate-200

```

  

#### Icon Button

```css

background: #000000

color: white

size: 48px (size-12)

border-radius: 0.5rem (rounded-lg)

display: flex

align-items: center

justify-content: center

```

  

#### Disabled Button

```css

background: slate-100

color: slate-500

opacity: 0.5

cursor: not-allowed

```

  

### 입력 필드 (Form Inputs)

  

#### Default Input

```css

height: 48px (h-12)

border: 1px solid slate-200

background: slate-50

border-radius: 0.5rem (rounded-lg)

padding: 0 16px (px-4)

focus: border-primary, ring-1 ring-primary

```

  

#### Input with Icon

```css

height: 48px (h-12)

border: 1px solid slate-200

background: slate-50

border-radius: 0.5rem (rounded-lg)

padding-left: 48px (pl-12)

icon: absolute left-4

```

  

### 카드 (Cards)

  

#### Standard Card

```css

background: white (light) / slate-900 (dark)

border: 1px solid slate-200 (light) / slate-800 (dark)

border-radius: 0.75rem (rounded-xl) / 1rem (rounded-2xl)

padding: 1.5rem ~ 2rem (p-6 ~ p-8)

shadow: shadow-sm

hover: shadow-md / shadow-xl

transition: transition-shadow / transition-all

```

  

#### Primary Card

```css

background: #000000 (primary)

color: white

border: 1px solid #000000

border-radius: 1rem (rounded-2xl)

padding: 2rem (p-8)

shadow: shadow-2xl

```

  

### 테이블 (Tables)

  

#### Table Header

```css

background: slate-50 (light) / slate-800/50 (dark)

font-size: 10px (text-[10px])

text-transform: uppercase

letter-spacing: widest

color: slate-500

font-weight: 700 (font-bold)

padding: 1rem 1.5rem (px-6 py-4)

```

  

#### Table Row

```css

font-size: 14px (text-sm)

border-bottom: 1px solid slate-100 (light) / slate-800 (dark)

padding: 1rem 1.5rem (px-6 py-4)

hover: bg-slate-50 (light) / slate-800/30 (dark)

```

  

### 배지 (Badges)

  

#### Status Badge - Active

```css

background: green-100 (light) / green-900/30 (dark)

color: green-800 (light) / green-400 (dark)

padding: 0.25rem 0.625rem (py-1 px-2.5)

border-radius: 9999px (rounded-full)

font-size: 12px (text-xs)

font-weight: 500 (font-medium)

```

  

#### Status Badge - Review

```css

background: amber-100 (light) / amber-900/30 (dark)

color: amber-800 (light) / amber-400 (dark)

padding: 0.25rem 0.625rem (py-1 px-2.5)

border-radius: 9999px (rounded-full)

font-size: 12px (text-xs)

font-weight: 500 (font-medium)

```

  

#### Category Badge

```css

background: #000000 (primary)

color: white

padding: 0.25rem 0.5rem (px-2 py-1)

border-radius: 0.25rem (rounded)

font-size: 10px (text-[10px])

font-weight: 800 (font-black)

text-transform: uppercase

letter-spacing: widest

```

  

---

  

## 6. 레이아웃 패턴

  

### 컨테이너

- **Max Width**: `max-w-7xl` (1280px)

- **Padding**: `px-6 lg:px-20` (모바일: 1.5rem, 데스크톱: 5rem)

- **Centering**: `mx-auto`

  

### 그리드 시스템

- **1 Column**: `grid-cols-1`

- **2 Columns**: `grid-cols-2` (md: `md:grid-cols-2`)

- **3 Columns**: `grid-cols-1 sm:grid-cols-2 lg:grid-cols-3`

- **Gap**: `gap-6` ~ `gap-12` (1.5rem ~ 3rem)

  

### 헤더 (Header)

```css

position: sticky

top: 0

z-index: 50

border-bottom: 1px solid slate-200 (light) / slate-800 (dark)

background: white/80 (light) / background-dark/80 (dark)

backdrop-filter: blur-md

padding: 1rem 1.5rem (px-6 py-4) / 1rem 5rem (lg:px-20)

```

  

### 푸터 (Footer)

```css

border-top: 1px solid slate-200 (light) / slate-800 (dark)

padding: 3rem 1.5rem (py-12 px-6) / 3rem 5rem (lg:px-20)

background: white (light) / black (dark)

```

  

---

  

## 7. 아이콘 시스템

  

### Material Symbols Outlined

- **Font**: Material Symbols Outlined

- **Variation Settings**: `'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24`

- **Usage**: 모든 아이콘에 사용

  

### 주요 아이콘 크기

- **Small**: `text-sm` (14px)

- **Base**: `text-base` (16px)

- **Large**: `text-lg` (18px)

- **XL**: `text-xl` (20px)

- **2XL**: `text-2xl` (24px)

- **3XL**: `text-3xl` (30px)

- **4XL**: `text-4xl` (36px)

  

### 아이콘 색상

- **Primary**: `text-primary` (검정) / `text-white` (다크 모드)

- **Secondary**: `text-slate-400` / `text-slate-500`

  

---

  

## 8. 다크 모드 (Dark Mode)

  

### 구현 방식

- **Method**: `class` 기반 (Tailwind `darkMode: "class"`)

- **Toggle**: HTML 요소에 `dark` 클래스 추가/제거

  

### 색상 변환 규칙

- **Background**: `bg-background-light` → `dark:bg-background-dark`

- **Text**: `text-slate-900` → `dark:text-white`

- **Secondary Text**: `text-slate-500` → `dark:text-slate-400`

- **Borders**: `border-slate-200` → `dark:border-slate-800`

- **Cards**: `bg-white` → `dark:bg-slate-900`

  

---

  

## 9. 애니메이션 및 트랜지션

  

### 트랜지션

- **Colors**: `transition-colors`

- **Shadow**: `transition-shadow`

- **All**: `transition-all`

- **Duration**: 기본 150ms, `duration-300` (300ms), `duration-500` (500ms)

  

### 호버 효과

- **Buttons**: 배경색 변경, 그림자 증가

- **Cards**: `hover:shadow-md` / `hover:shadow-xl`

- **Links**: `hover:text-primary`

- **Images**: `group-hover:scale-110` (그룹 호버 시)

  

---

  

## 10. 반응형 브레이크포인트

  

### Tailwind 기본 브레이크포인트

- **sm**: `640px` 이상

- **md**: `768px` 이상

- **lg**: `1024px` 이상

- **xl**: `1280px` 이상

- **2xl**: `1536px` 이상

  

### 주요 반응형 패턴

- **Padding**: `px-6 lg:px-20`

- **Grid**: `grid-cols-1 md:grid-cols-2 lg:grid-cols-3`

- **Navigation**: `hidden md:flex` / `hidden lg:flex`

- **Search**: `hidden sm:block`

  

---

  

## 11. 사용 가이드라인

  

### 색상 사용

- **Primary Black**은 강조 요소, 버튼, 브랜드 요소에만 사용

- 배경은 가능한 한 중립 색상 사용

- 텍스트는 충분한 대비 확보 (WCAG AA 이상)

  

### 타이포그래피

- 헤딩은 계층 구조를 명확히 유지

- 본문 텍스트는 가독성을 위해 적절한 line-height 사용 (`leading-relaxed`)

- 캡션과 라벨은 uppercase와 letter-spacing으로 구분

  

### 간격

- 일관된 간격 시스템 유지

- 섹션 간 충분한 여백 확보 (mb-20)

- 카드 내부 패딩은 콘텐츠 양에 따라 조정 (p-6 ~ p-8)

  

### 컴포넌트

- 버튼은 최소 48px 높이 유지 (접근성)

- 입력 필드는 명확한 포커스 상태 제공

- 카드는 호버 시 시각적 피드백 제공

  

### 다크 모드

- 모든 컴포넌트는 다크 모드 지원 필수

- 색상 대비는 라이트/다크 모드 모두에서 충분히 확보

- 배경과 텍스트의 대비 비율 유지

  

---

  

## 12. 코드 예시

  

### Tailwind Config

```javascript

tailwind.config = {

darkMode: "class",

theme: {

extend: {

colors: {

"primary": "#000000",

"background-light": "#f7f7f7",

"background-dark": "#191919",

},

fontFamily: {

"display": ["Pretendard", "-apple-system", "BlinkMacSystemFont", "system-ui", "Roboto", "Helvetica Neue", "Segoe UI", "Apple SD Gothic Neo", "Noto Sans KR", "Malgun Gothic", "sans-serif"] // 한국어 최적화 폰트

},

borderRadius: {

"DEFAULT": "0.25rem",

"lg": "0.5rem",

"xl": "0.75rem",

"full": "9999px"

},

},

},

}

```

  

### 기본 버튼 예시

```html

<button class="bg-primary text-white h-12 px-8 rounded-lg font-bold hover:bg-slate-800 transition-all">

Button Text

</button>

```

  

### 기본 카드 예시

```html

<div class="bg-white dark:bg-slate-900 border border-slate-200 dark:border-slate-800 rounded-xl p-8 shadow-sm hover:shadow-md transition-shadow">

<!-- Card content -->

</div>

```

  

### 기본 입력 필드 예시

```html

<input class="w-full h-12 rounded-lg border-slate-200 bg-slate-50 focus:border-primary focus:ring-1 focus:ring-primary px-4 transition-all"

placeholder="Enter text..."

type="text"/>

```

  

---

  

## 13. 체크리스트

  

새로운 디자인을 만들 때 다음 사항을 확인하세요:

  

- [ ] Primary 색상 (#000000)이 적절히 사용되었는가?

- [ ] 다크 모드가 지원되는가?

- [ ] 타이포그래피 계층이 명확한가?

- [ ] 간격 시스템이 일관되게 적용되었는가?

- [ ] 보더 반경이 가이드라인을 따르는가?

- [ ] 버튼 높이가 최소 48px인가?

- [ ] 호버 상태가 정의되어 있는가?

- [ ] 반응형 디자인이 적용되었는가?

- [ ] 색상 대비가 충분한가?

- [ ] Material Symbols 아이콘이 올바르게 사용되었는가?

  

---

  

## 버전 정보

  

- **Last Updated**: 2024

- **Design System Version**: 1.0

- **Based on**: Proby-Inspired Black Design System & UI Pattern Library: Minimalist Black

  

---

  

이 디자인 시스템 문서는 앞으로의 모든 디자인 작업의 기준이 됩니다. 새로운 컴포넌트나 화면을 만들 때 이 가이드라인을 참고하여 일관된 사용자 경험을 제공하세요.