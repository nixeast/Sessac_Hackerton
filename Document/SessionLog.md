# AI 페어프로그래밍 세션 로그 (Session Log)

본 문서는 사용자와 AI 에이전트 간의 대화 세션별 주요 결정 사항, 작업 내역, 생성 파일 및 향후 액션 플랜을 압축 기록하는 세션 아카이브입니다. 새 채팅 세션을 열었을 때도 프로젝트 맥락을 즉시 파악할 수 있도록 관리합니다.

---

## 📌 [Session 1] 2026-10-17 16:03 ~ 16:30
- **참여자**: 정훈 (사용자), Antigravity (AI 에이전트)
- **주요 목표**: 해커톤 공식 양식(`참가신청서.pdf`) 분석, 기획서 작성 사양서 확립 및 전용 초안 템플릿 세팅

### 1. 주요 작업 및 결정 사항
1. **공식 신청서 및 모집 공고 정밀 분석**
   - `Data/참가신청서.pdf`와 `Data/모집공고.pdf`를 OCR 및 텍스트 뷰어로 교차 검증.
   - **핵심 제한 규격 도출**: `[붙임 2] 아이디어 기획서`는 **전체 A4 3쪽 이내(표·이미지 포함)**로 엄격히 제한되며, 양식 내 **회색 안내문은 작성 후 삭제 필수**.
   - **서류 심사 배점 구조 확인**: 
     - 문제인식 및 정책 연계성 (**30점**, 동점자 최우선 선발 기준)
     - AI 활용 창의성 (**30점**)
     - 실현가능성 (**25점**)
     - 팀 역량 (**15점**)
   - **출처 명시 의무**: 통계, 조사자료, 정책 인용 시 출처 표기 필수.

2. **기획서 작성 사양서 작성 완료**
   - 파일: [`Document/Idea_Specification.md`](file:///c:/Users/eastn/Documents/GitHub/Sessac_Hackerton/Document/Idea_Specification.md)
   - 4개 주요 섹션별 요구사항, 작성 팁, 페이지별 권장 분량 배분 가이드(Page 1: 35%, Page 2: 40%, Page 3: 25%) 및 자가 체크리스트 정리.

3. **기획서 작성 전용 초안 파일 세팅**
   - 파일: [`Document/Idea_Proposal_Draft.md`](file:///c:/Users/eastn/Documents/GitHub/Sessac_Hackerton/Document/Idea_Proposal_Draft.md)
   - 공식 서식 규격 1:1 매핑, 섹션별 안내 주석 및 분량 힌트 포함.
   - 팀원 4명(김승우, 최윤주, 박정훈, 박찬종) 역할 분담표 및 서비스 플로우차트(Mermaid) 뼈대 구축.

4. **마크다운 뷰어 환경 가이드 제공**
   - 에디터 내 분할 미리보기 단축키 (`Ctrl + K` ➡️ `V`) 및 실시간 렌더링 방식 안내.
   - 파일 탐색기 및 크롬에서 `.md` 파일을 웹페이지처럼 열람하는 방법(`Markdown Viewer` 확장 프로그램 및 로컬 파일 URL 접근 허용 설정) 공유.
   - 전용 뷰어 앱 추천 (Typora, MarkText).

### 2. 생성 및 수정된 파일
- [`Document/Idea_Specification.md`](file:///c:/Users/eastn/Documents/GitHub/Sessac_Hackerton/Document/Idea_Specification.md): 해커톤 기획서 작성 세부 사양서 (규격, 배점, 작성 가이드)
- [`Document/Idea_Proposal_Draft.md`](file:///c:/Users/eastn/Documents/GitHub/Sessac_Hackerton/Document/Idea_Proposal_Draft.md): 공식 서식 맞춤형 기획서 작성용 작업 초안
- [`Document/SessionLog.md`](file:///c:/Users/eastn/Documents/GitHub/Sessac_Hackerton/Document/SessionLog.md): 세션 대화 내용 및 진행 상황 요약 로그 (본 파일)

### 3. 다음 세션(또는 다음 작업) To-Do
- [ ] 팀 최종 확정 주제 검토 (정훈 님 메인 추천안: 고립·은둔 청년 사회 복귀 × 어르신 복지 동행 등)
- [ ] [`Document/Idea_Proposal_Draft.md`](file:///c:/Users/eastn/Documents/GitHub/Sessac_Hackerton/Document/Idea_Proposal_Draft.md)의 **[섹션 1. 목적 (문제 인식 및 정책 연계성)]** 본문 작성 착수 (서울시 공식 통계 및 기존 사업 연계 논리 구체화)
- [ ] 3쪽 분량 기준에 맞춘 서비스 개요 및 AI 파이프라인(섹션 2) 압축 정리
