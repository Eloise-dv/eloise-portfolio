# Eloise's Portfolio Website

박사과정 지원자 Eloise의 포트폴리오 웹사이트입니다.

## 🚀 Features

- 반응형 디자인
- 모던한 UI/UX
- 프로젝트 카드 그리드 레이아웃
- 스무스 스크롤 기능
- 접근성 최적화

## 🛠️ Tech Stack

- HTML5
- CSS3 (Custom Properties, Flexbox, Grid)
- Vanilla JavaScript
- No external dependencies

## 📦 Project Structure

```
rowan-portfolio/
│
├── index.html          # 메인 HTML 파일
├── style.css          # 스타일시트
├── script.js          # JavaScript 파일
└── README.md          # 프로젝트 문서
```

## 🎨 Design Features

- CSS 변수를 활용한 일관된 디자인 시스템
- 반응형 그리드 레이아웃
- 부드러운 애니메이션 효과
- 모바일 퍼스트 접근

## 🚀 Getting Started

1. 저장소 클론
```bash
git clone [repository-url]
```

2. 프로젝트 디렉토리로 이동
```bash
cd rowan-portfolio
```

3. `index.html` 파일을 웹 브라우저에서 열기

## 📱 Responsive Design

- Desktop (1200px 이상)
- Tablet (768px - 1199px)
- Mobile (480px - 767px)
- Small Mobile (480px 미만)

## 🔧 Customization

### 프로젝트 추가하기

`script.js` 파일의 `projects` 배열에 새로운 프로젝트를 추가하세요:

```javascript
const projects = [
    {
        title: "프로젝트 제목",
        description: "프로젝트 설명",
        link: "프로젝트 링크"
    }
];
```

### 스타일 수정하기

`style.css` 파일의 CSS 변수를 수정하여 디자인을 커스터마이즈하세요:

```css
:root {
    --primary-color: #2d3436;
    --accent-color: #0984e3;
    /* 기타 변수들 */
}
```

## 📄 License

MIT License

## 👤 Author

Eloise - 박사과정 지원자 