# CEO Ops Dashboard Spec

## 목적
대표가 모든 업무를 직접 기억하지 않아도 되게, 오늘/이번주/위험업무만 한눈에 보이는 관제판을 만든다.

## 1. 상단 KPI
- 오늘 마감 건수
- 이번 주 마감 건수
- Critical 리스크 건수
- 승인 대기 건수
- 증빙 누락 건수
- 48시간 이상 업데이트 없음 건수

## 2. 핵심 보드
### A. Today Board
- 오늘 해야 할 일 3개
- 오늘 승인할 것 3개
- 오늘 위험한 것 3개

### B. Government Grant Board
- 사업명
- 단계(검토/작성/검수/제출/접수완료)
- 마감일
- 담당
- 증빙 누락 여부
- 최종 승인자
- 접수번호/제출증빙

### C. Finance / Ops Board
- 급여/세무/계약/갱신/구매 반복 일정
- 마감 D-14/D-7/D-3 표시

### D. Exception Board
- 병목
- 지연 사유
- 누구 결정이 필요한지
- 언제까지 안 정하면 사고 나는지

## 3. 대표 입력 최소화 원칙
대표는 매일 아래 3가지만 보면 된다.
1. 오늘 승인할 것
2. 오늘 놓치면 사고 나는 것
3. 오늘 DEO/피스가 대신 처리할 수 없는 것

## 4. 상태값 표준
- Not Started
- In Progress
- Waiting Approval
- Waiting Docs
- Blocked
- Submitted
- Archived

## 5. 리스크 표준
- Low
- Medium
- High
- Critical

## 6. 즉시 운영 방식
- 피스가 스프레드시트 소유
- 디오가 예외/병목 정리
- 미나가 보고 품질과 리스크 검수
- 대표는 승인/반려만 수행
