## third_project_MSA <br>

Spring Boot MSA project <br>
언어 : java 1.8 <br>
도구 : eclipes <br>
db정보 : oracle Database 11g <br>
project 내용 :  <br><br>

eureka-server : main project , admin-search project , cs-project 를 하나로 묶어주는 역할 <br>

Main project : index page , 회원가입(중복처리) , 로그인 , 아이디/비밀번호 찾기 , 찜목록보기 <br>

Admin-search project : admin page(동영상 입력,삭제,수정 및 유저관리 , 고객센터 문의사항 확인 접수 ) , search page(동영상 검색 , 자세히보기 , 동영상 실행 , 댓글/평점(중복처리), 동영상 찜하기)  <br>

Cs-project : cs_main page , 1:1문의하기 , 내 문의내역 확인 , 자주하는 질문들  <br>

MSA 연결 : main project에서 컨텐츠 검색 ->로그인o : search project(로그인정보 + 검색어 전달) <br>
 		->로그인 x : search project(검색어만 전달) <br>
           
main project에서 고객센터 이동 - >로그인o : cs project(로그인정보 전달)	 <br>
                                      -> 로그인x : cs project(아무정보 전달x) <br>





