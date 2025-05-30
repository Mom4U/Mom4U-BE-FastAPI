## 📌 작업 목적
<!-- 해당 PR을 통해 해결하고자 하는 문제나 구현하고자 하는 기능을 설명해 주세요 -->
예: 회원가입 페이지 내 유효성 검사 및 서버 연동 로직 구현

---

## 🔨 주요 작업 내용
<!-- 주요 커밋이나 변경 사항을 bullet point로 요약해서 작성해 주세요 -->
예:
- 회원가입 폼 UI 구성
- `useSignupForm` 훅 작성
- 이메일/비밀번호 유효성 검사 로직 추가
- API 연동 후 에러 핸들링 구현

---

## 🧪 테스트 방법
<!-- 어떤 방식으로 기능이 정상 동작하는지 확인했는지 작성해 주세요 -->
예:
- [ ] 올바른 정보 입력 시 회원가입 성공 후 홈으로 이동되는지 확인
- [ ] 유효하지 않은 이메일 입력 시 에러 메시지 출력 확인
- [ ] 서버 에러 응답 시 토스트 메시지 출력 확인

---

## 📎 관련 이슈
<!-- 해당 PR과 관련된 이슈를 정확히 연결해주세요 -->  
<!-- `Closes #이슈번호` 형식으로 작성하면 PR 머지 시 해당 이슈가 자동으로 닫힙니다. -->  

예:  
- Closes #12 ← 구현 완료
- Refs #14, #15 ← 관련 논의 참고

---

## 💬 논의 또는 고민한 점
<!-- 구현 중 고민한 부분, 리뷰어에게 설명하고 싶은 맥락이 있다면 작성해 주세요 -->
예:  
- 유효성 검사를 Yup과 직접 작성 중 어떤 게 더 유연할지 고민했습니다.  
- 서버 에러 구조가 일정하지 않아 에러 메시지 추출 로직을 분리했습니다.

---

## 📷 스크린샷
<!-- 사진을 첨부해 주세요 -->
<!-- UI 변경 사항이 있다면 before/after 비교 스크린샷 첨부해 주세요 -->
| Before | After |
|--------|-------|
| ![](before.png) | ![](after.png) |

---

## ✅ 체크리스트
- [ ] 코드에 `any`가 사용되지 않았습니다
- [ ] Storybook 문서가 추가/수정되었습니다 (해당 시)
- [ ] 테스트 코드가 작성되었습니다 (해당 시)
- [ ] 이슈와 커밋이 명확히 연결되어 있습니다
