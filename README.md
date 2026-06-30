# K-Content Intelligence Dashboard — 개발 포트폴리오

> 외국 팬의 K-콘텐츠 반응을 한국어 인사이트로 변환하는 다중 SNS 분석 플랫폼.
> Reddit · YouTube · Instagram · TikTok · MyDramaList · Google Trends 6개 소스 통합.

**🌐 Live**: https://erimii.github.io/k-content-portfolio/

## 📄 파일

| 파일 | 설명 |
|------|------|
| [`index.html`](./index.html) | 인터랙티브 웹 포트폴리오 (반응형 + 다크 모드 + sticky nav) |
| [`K-Content-Portfolio.pdf`](./K-Content-Portfolio.pdf) | 인쇄용 PDF 버전 (A4 16 페이지) |
| [`images/`](./images/) | 대시보드 스크린샷 10장 |

## 🎯 프로젝트 한 줄 요약

K-콘텐츠가 세계적으로 화제이지만 한국 마케팅·기획팀은 외국 팬 반응을 영어·스페인어·포르투갈어로 직접 읽어야 했다는 비대칭을, 6개 SNS 자동 수집 + Groq LLM 한국어 번역 + 다중 소스 매칭으로 해결한 단독 개발 프로젝트.

## ⭐ 핵심 기여

- **다중 소스 매칭 알고리즘** (정적 사전 + MDL 동적 동기화 hybrid) — 작품 언급 정확도 **13배**
- **차별화 분석 카드 2종** — Atlas (글로벌 팬덤 지도) + Viral DNA (rule-based 점수)
- **Anti-bot 회피 5종** — 마우스 자연 이동·가변 스크롤·자연 진입·캡션 읽기·delay 1.5×
- **Fire-and-forget 비동기 패턴** — 주간 크롤 응답 시간 **2.5h → 6ms**
- **운영 무중단** — PM2 + macOS launchd로 **168시간+** 검증, 매일 cron 7회 연속 자동 발송

## 🛠 기술 스택

`TypeScript` · `Node.js 25` · `Express` · `SQLite` · `Playwright` · `youtubei.js` · `Groq LLM` · `Vanilla JS SPA` · `Chart.js` · `Resend` · `PM2` · `node-cron`

## 📊 규모

- TypeScript **14,765 lines**
- JS/CSS **6,165 lines**
- **73 commits** · 단독 개발 · 2026.04 ~

---

*이력서 / 자기소개서 용으로 자유롭게 참조 가능합니다.*
