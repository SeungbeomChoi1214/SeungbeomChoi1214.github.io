# 최승범 — 개발자 포트폴리오

임베디드부터 클라우드까지, 한 사이클을 직접 만드는 개발자의 작업 포트폴리오 사이트.

**🔗 https://seungbeomchoi1214.github.io/**

## 무엇

핵심 프로젝트(PyeonipCheck-Web · SmartFactory-AIoT · PostureGuard · Workbench · 한이음)를
문제·판단·결과·배운 점 흐름으로 정리한 단일 페이지 포트폴리오.

## 어떻게

- **정적 웹** — 빌드 도구·프레임워크 없이 순수 HTML/CSS/JS 단일 파일(`index.html`).
- **반응형** — 모바일(375)·데스크톱(1280) 레이아웃, CSS Grid로 카드 리듬 구성.
- **직접 구현한 인터랙션** — 스크롤 진행바, 1회성 fade-up(IntersectionObserver),
  숫자 카운트업, 프로젝트 이미지 탭 전환, 필터칩, 이미지 라이트박스.
- **접근성** — `prefers-reduced-motion` 존중(모션 비활성 시 즉시 표시), 아이콘은 이모지 대신 SVG.

## 배포

GitHub Pages (user-site, `main` 브랜치 루트).

## 구조

```
index.html      포트폴리오 본문 (구조·스타일·스크립트 일체)
assets/         프로젝트 스크린샷·다이어그램·도면 이미지
```
