# Tasks — Prompt Validator Agent

## 실행 단계 분해

---

## Phase 1: 환경 설정

- [x] **T-01** 프로젝트 디렉토리 구조 생성
- [x] **T-02** `.env.example` 작성
- [x] **T-03** `.gitignore` 작성

---

## Phase 2: 핵심 구현

- [x] **T-04** `SYSTEM_PROMPT` 설계 (4가지 기준 + 출력 형식 정의)
- [x] **T-05** `validate_prompt()` 함수 구현 (OpenAI API 호출)
- [x] **T-06** `main()` CLI 루프 구현 (여러 줄 입력, exit 처리)

---

## Phase 3: 문서화

- [x] **T-07** `README.md` 작성 (병목·이유·구조·실행·테스트 입력 형식·5회 결과)
- [x] **T-08** `CHECKLIST.md` 작성 (자가 검증 항목)
- [x] **T-09** `requirements.md` 작성
- [x] **T-10** `design.md` 작성
- [x] **T-11** `steering.md` 작성
- [x] **T-12** `tasks.md` 작성

---

## Phase 4: 테스트

- [x] **T-13** `test-input/case-1.txt` 작성 (역할 + 형식 지정 프롬프트)
- [x] **T-14** `test-input/case-2.txt` 작성 (컨텍스트 기반 QA 프롬프트)
- [ ] **T-15** 실제 API 호출로 5회 실행 결과 검증
- [ ] **T-16** CHECKLIST.md 항목 전체 통과 확인

---

## 완료 기준

- `python prompt_validator.py` 실행 시 오류 없이 동작
- 4가지 기준이 모두 포함된 검증 프롬프트 출력
- `exit` 입력 시 정상 종료
- CHECKLIST.md 전 항목 ✅
