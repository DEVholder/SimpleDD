# Simple Daily Diary with NEXTJS and MongoDB

이 Toy 프로젝트는 간단한 일일 한줄 일기를 작성할 수 있도록 한다.

해당 Toy 프로젝트는 다음 환경에서 개발된다

* NEXTJS -Version 13
* Bootstrap 
* MongoDB 

app/
DD 메인 페이지 
소개글과 통계를 보여준다

app/sign in
계정 로그인

app/list
DD 리스트 조회

app/detail/[id]
DD 상세 정보 확인 
[id]값을 통해 DB 조회

api/post/new
새로운 게시글을 DB에 저장하는 api

api/post/edit
기존 게시글을 수정하는 api

api/post/delete
게시글을 DB에서 삭제하는 api

api/auth/signin
사용자 계정 로그인을 처리하는 api

