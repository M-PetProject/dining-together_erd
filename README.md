# dining-together_erd
회식 정하기 ERD(MySQL Workbench ERD)

---

## TOOL

- MySQL Workbench 

---

## 개발 가이드

- 컬럼명 : 명사형 영어단어를 사용합니다
- 코드 성격 컬럼
  - type : 데이터를 구분 짓기 위한 컬럼
  - yn : 여부(Y, N)
  - cd : 공통 코드에서 참조하는 컬럼
- 전사 컬럼 
  - reg_dtm, upd_dtm 은 필수적으로 넣어야합니다.
  - reg_dtm, upd_dtm 은 업무 컬럼으로 사용하면 안됩니다.

---

## 파일 설명

- .mwb 파일이 erd 파일 입니다

- dining_common : 공통 영역
- dining_member : 멤버 영역(팀, 멤버)
- dining_place  : 장소 영역(댓글 포함)
- dining_main   : 회식 영역
- dining_vote   : 투표 영역
- dining_notice : 공지사항 영역(게시판)

---

## TODO

- 업무 영역을 나눠 모델링을 해야합니다