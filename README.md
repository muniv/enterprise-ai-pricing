# Enterprise AI Pricing Calculator

기업이 상용 AI(Anthropic Claude · OpenAI ChatGPT · Google Gemini)를 도입할 때
**직무별 인원 + 선호 툴**을 고르면 월/연 예상 비용을 추정해주는 단일 페이지 계산기입니다.

🔗 **Live:** https://muniv.github.io/enterprise-ai-pricing/

## 기능
- 직무 템플릿(개발자·기획·디자이너·마케팅·데이터·리서치·사무)으로 팀 구성
- 같은 개발자라도 **Claude Code · Codex · Gemini Code Assist · Antigravity** 등 선호 툴 선택
- 시트(구독)비 + 사용량(토큰/크레딧/쿼리)비 자동 합산
- 월납 / 연납(할인) 토글 — 모든 금액·토큰을 선택 단위로 표시
- 월/연 제공 토큰 및 인당 제공 토큰 환산 (Gemini 쿼리 → 토큰 환산 포함)
- 최소 계정 수 경고, 벤더별 비용 분해, 원화 환산
- 가정값(사용강도별 토큰량·입출력 비율·쿼리 환산) 직접 조정 가능

## 데이터 기준
- 2026년 6월 공개 정책 + 커뮤니티 추정치 기반 **참고용 견적**
- 실제 엔터프라이즈 요금은 협상·약정·사용량에 따라 달라집니다.

## 사용
`index.html` 파일 하나로 동작합니다. 브라우저로 열거나 정적 호스팅에 올리면 됩니다.
