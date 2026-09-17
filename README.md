# ssaju

정적 HTML 페이지 모음 (빌드 도구 없이 순수 HTML/CSS/JS).

## 페이지

- [index.html](index.html) — 설이의 사주카페 (메인)
- [saju-cafe.html](saju-cafe.html) — 설이의 사주카페
- [inyeon-teahouse.html](inyeon-teahouse.html) — 인연다원
- [curriculum-planner.html](curriculum-planner.html) — 공부 설계도

외부 리소스로 Google Fonts, cdnjs의 `marked.js`를 CDN에서 불러오며, 별도 서버·API·환경 변수 없이 동작합니다.

## 로컬 실행

빌드 과정이 필요 없습니다. 원하는 HTML 파일을 브라우저로 열거나, 로컬 서버로 띄우려면:

```bash
npx serve .
```

## 배포

Vercel에 정적 사이트로 배포되어 있습니다. 저장소를 Vercel 프로젝트와 연결하면 `main` 브랜치 push 시 자동 배포됩니다.
