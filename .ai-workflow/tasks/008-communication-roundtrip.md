# Task 008 — ChatGPT ↔ Claude Code 왕복 소통 테스트

## 목적
ChatGPT가 GitHub에 등록한 지시서를 Claude Code가 읽고, 결과를 GitHub에 Push하면 ChatGPT가 별도 복사·붙여넣기 없이 확인할 수 있는지 검증합니다.

## 실행 지시
1. 기존 `/run-task`의 모든 저장소 확인, 변경 범위, 보안 검사, 순차 검증, 승인 및 자동 Push 정책을 그대로 따릅니다.
2. 포트폴리오 문서·코드·설정 파일은 변경하지 마세요.
3. 다음 경로에 결과 보고서 하나만 생성하세요: `.ai-workflow/results/008-communication-roundtrip.md`.
4. 보고서에 다음 문구를 **정확히 그대로** 포함하세요: `ROUNDTRIP-008: 토끼가 우편함에 답장을 넣었습니다.`
5. 보고서에 작업 상태(완료), 수행한 작업, 변경 파일, 검사 결과, 원격 Push 계획을 기록하세요.
6. 검사를 모두 끝내고 통과한 뒤에만 커밋·Push하세요. 검사와 Push를 병렬로 실행하지 마세요.
7. 정상적인 결과 보고서 한 파일 추가만 발생하고 기존 자동 Push 허용 조건을 만족하면 추가 승인 없이 Push하세요. 허용 조건을 만족하지 못하면 기존 정책대로 승인 요청하세요.

## 완료 기준
- GitHub `main`에 `.ai-workflow/results/008-communication-roundtrip.md`가 존재함
- 결과 보고서에 지정 문구가 정확히 포함됨
- 기존 포트폴리오 내용에 변경이 없음
