# poketmon_clone

<img src="https://github.com/user-attachments/assets/0bb05da7-1aee-4ec0-ae9d-1e04b7b9ed70" width=1000 />

### 구성
## 1. 로그인
   - 회원가입
      - 아이디, 비밀번호, 비밀번호 확인, 닉네임, 이메일
   - 회원탈퇴 후 재가입시 30일 제한
     - 구분방식 : 이메일
   로그인
   - 휴면 계정 관리
     - 30일 이상 접속이 안될 경우 이메일 확인 후 접속 가능
   - 마이페이지
     - 내가 쓴 Q & A 개시물 확인
     - 회원 정보 수정 : 비밀번호, 닉네임 / 이메일 수정 불가
     - 회원 탈퇴
       - 탈퇴 이유 확인
       - 탈퇴 최종 확인 : ex) 정말로 탈퇴하시겠습니까? 탈퇴한 후 30일동안 재가입은 불가능합니다.

## 1-1 관리자 로그인
   - 로그인
   - 마이 페이지
     - 회원관리 -> 가입한 회원의 활동기록 조회 가능
       - 회원 활동 정지 가능 : ex) 1일 활동 정지
     - 게시판 관리
       - Q&A 질문에 답변 기능, 공지사항 작성 가능
     - 도감 관리
       - 도감 (포켓몬) 추가 및 삭제 가능

## 2 카테고리
  1. 포켓몬 도감
     - 즐겨찾기
       - 선택한 포켓몬 즐겨찾기 페이지에 저장
       - 최대 30마리 저장 가능
       - 포켓몬 이미지 좌측 상단에 하트로 구분 / 다시 클릭시 즐겨찾기 해제
     - 도감으로 이동
       - 분류 기준에 따른 검색기능
       - 필터 기능
         - 도감번호 / 역순 정렬
         - 포켓몬 타입 별 정렬
         - 가나다 순 정렬
  2. 게시판
     - 전체 내용 표시
       - 최신 순으로 정렬 : 최신순 정렬 고정
     - 공지사항
       - 최신 순으로 정렬 : 최신순 정렬 고정
     - Q & A
       - 로그인 / 비 로그인 구분 -> 비 로그인 유저는 답글, 질문 X
       - 빈도가 높은 순으로 정렬 : 빈도순 정렬 고정 / 조회수 동일할 시 가나다 순 정렬
  3. 포켓몬 굿즈
     - 굿즈 상점으로 이동
  4. 포켓몬 게임
     - 포켓몬 이미지 보고 이름 맞추기 게임 (주관식)
  5. 통합검색
     - 카테고리 내 모든 내용 검색 가능
     - 도감 필터 기능 차용
     - 최신순 정렬 검색
