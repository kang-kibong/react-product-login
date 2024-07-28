# 5️⃣ 5주차 로그인 및 관심목록 (with. 테스트코드)
## 🎯 1단계 - Form 부분 테스트 코드 작성하기
### ✅ 기능 목록
- [x] MSW를 사용하여 Mock API가 동작하도록 구현
  - [x] 상품 상세 API 동작
  - [x] 상품 옵션 API 동작
- [x] 단위 테스트 진행
- [x] 상품 상세페이지 통합 테스트 구현
- [x] 결제 페이지의 Form관련한 통합 테스트 코드 구현 
  - [x] 현금영수증 Checkbox가 false인 경우 현금영수증 종류, 현금영수증 번호 field가 비활성화 되어있는지 확인하는 테스트 코드 구현 (만약 true인 경우 현금영수증 종류, 번호 field에 값이 입력 되어야 함)
  - [x] form의 validation 로직이 정상 동작하는지 확인하는 테스트 코드 구현

## 🔐 2단계 - 로그인, 관심 상품 등록 / 삭제, 관심 목록 구현
### ✅ 기능 목록
- [x] 회원가입 구현
  - [x] 회원가입 기능이 동작되게 구현
  - [x] 회원가입을 하면 로그인 되도록 구현
- [] 상품 상세 페이지 관심 등록 버튼 구현
  - [x] 상품 상세 페이지에서 관심 버튼을 클릭 했을 때 관심 추가 동작
  - [x] 관심 등록 성공 시 Alert로 "관심 등록 완료" 메시지를 노출
  - [] 나의 계정 페이지에서 관심 목록 리스트를 만들어요.
  
- [] 관심 목록 리스트
  - [] 관심 목록 API는 카카오테크 선물하기 API 노션의 response 데이터를 사용하여 렌더링
  - [] 관심 삭제 기능 구현