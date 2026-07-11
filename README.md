# limch-skills

Claude Code 스킬 모음 마켓플레이스.

## 설치

```
/plugin marketplace add companyjad1-beep/claude-skills
/plugin install kickoff@limch-skills
```

## 스킬 목록

### kickoff — 프로젝트 킥오프

> **이관 공지 (2026-07-11)**: kickoff의 개발 원본은 [brt-plugin](https://github.com/companyjad1-beep/brt-plugin)으로 옮겨졌습니다. 이 레포의 kickoff는 v0.3에서 동결되며, 최신판은 brt-plugin 설치로 받으세요. (marketing-plan은 이 레포에서 계속 관리)

새 프로젝트를 시작할 때 `/kickoff` 한 번으로:

1. **딥 인터뷰** — 소크라테스식 질문(한 번에 하나, 추천안 포함)으로 제품 정의·범위·스택·브랜드/디자인·운영 규칙 5개 트랙을 확정. 초보자 눈높이 설명 내장. 확정된 결정은 즉시 파일로 남아 세션이 끊겨도 이어서 재개
2. **문서 일괄 생성** — CLAUDE.md, PRD, BRAND(컬러·톤앤매너·보이스), DESIGN(디자인 규칙), SCREENS(화면·네비 구조), UI-RULES(공통 버그 예방), 결정 기록(decisions/), .env.example. 참고 브랜드(Vercel·Airbnb 등)를 고르면 실제 디자인 시스템을 시작점으로 가져옴(getdesign.md)
3. **저장소 초기화** — git init + .gitignore + 첫 커밋
4. **외부 서비스 연결** — Supabase·Vercel 등 CLI 로그인과 프로젝트 연결까지 단계별 안내

### marketing-plan — 마케팅 기획

킥오프가 끝난 프로젝트에서 `/marketing-plan` 한 번으로:

1. **재료 선독** — PRD·BRAND·결정 기록을 먼저 읽고 확인 요약으로 시작. 이미 결정된 타겟·문제·보이스는 다시 묻지 않음
2. **마케팅 딥 인터뷰** — 포지셔닝·메시지·채널 플레이북(+명시적 제외 채널)·출시 플랜·예산 5트랙. 채널·경쟁 서비스 사실 관계는 직접 조사해 통보, 판단만 질문. 결정은 즉시 `docs/decisions/`에 기록되어 중단해도 재개 가능
3. **docs/MARKETING.md 생성** — 엘리베이터 피치, 채널별 형식(이미지/영상/쇼츠/글)·빈도·톤 변주·확정 예시 카피, 프리런칭~포스트런칭 타임라인, 측정 방법이 붙은 KPI까지. 인터뷰·조사로 추적 안 되는 수치·카피는 안 넣음
