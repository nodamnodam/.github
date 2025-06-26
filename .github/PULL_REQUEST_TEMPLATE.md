<!--
* 테스트/검증은 자동화(CI)와 리뷰 정책에 따라 진행됩니다.
* 이슈 연결은 브랜치 네이밍 또는 PR 본문(fixes #이슈번호)으로 자동 처리해주세요.
-->
---

## What 📝  
<!--  
실제 작업한 내용을 구체적으로 작성해 주세요. (What did you do?)  
예시:  
- User 모델에 email 필드 추가  
- /api/v1/user 엔드포인트에서 프로필 이미지 반환 로직 수정  
- 불필요한 콘솔 로그 제거 및 주석 정리  
- 구글 로그인 에러 처리 로직 리팩토링  
- README에 배포 방법 문서화  
- 다국어 번역 리소스(en, ja) 추가  
- 의존성 패키지 react 18로 업그레이드  
- 로그인 버튼 UI 컴포넌트 디자인 변경  
- Sentry 연동 제거  
-->

## How 🖼️  
<!--  
위 작업의 결과, 실제로 무엇이/어떻게 달라졌는지(동작/화면/UI/API 등) 중심으로 설명해 주세요.  
(How did it change the system? Describe the actual result of your work.)  
가능하다면 변경 전/후 스크린샷, 예시, 로그, 표 등 비교 자료를 첨부해 주세요.  
예시:  
- 변경 전: 프로필 조회 시 이미지가 항상 기본 이미지로 표시됨  
  변경 후: 사용자가 업로드한 이미지가 정상적으로 표시됨  
- 기존에는 로그인 실패 시 에러 메시지가 노출되지 않았음 → 이제 에러 토스트 메시지 노출  
- "회원가입" 버튼 색상이 파란색에서 초록색으로 변경됨 (스크린샷 첨부)  
- API 응답 예시  
  before: `{ "name": "홍길동" }`  
  after: `{ "name": "홍길동", "email": "test@example.com" }`  
- 로그 예시  
  기존: `[ERROR] something went wrong`  
  변경 후: `[ERROR][USER:123] Email not found`  
-->

## Why 🛠️  
<!--  
이 방식을 선택한 이유, 문제 해결/기능 개선을 위해 이 접근이 적합한 이유, 대안 검토 결과 등 설명해 주세요.  
(Why did you choose this approach? Explain your reasoning and alternatives considered.)  
예시:  
- 기존 구조에서 email 필드가 없어 인증 로직에 문제 발생 → email 필드 추가가 필요  
- UX 개선을 위해 버튼 색상을 디자인 시스템에 맞춰 변경  
- 외부 라이브러리 의존성 최소화를 위해 Sentry 연동 제거  
- 구글 로그인 오류가 자주 발생해, 추가적인 에러 처리가 필요했음  
- 최신 React 버전에서만 지원되는 기능 사용을 위해 패키지 업그레이드  
- 복잡한 조건문 대신 Optional Chaining을 사용해 코드 가독성 및 유지보수성 향상  
-->

---

<!--  
고려할 사항(잠재적 위험, 추후 작업 필요, 마이그레이션 등),  
기술적 의견, 참고할 만한 링크,  
관련된 사람(@username), 참고 이슈/문서 등이 있다면 자유롭게 작성해 주세요.  
(Notes, risks, TODOs, technical comments, related links or people, etc.)  
-->