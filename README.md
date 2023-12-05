# MoviePlaza - 퍼블리싱 완료

# 수정사항 적용 완료 -> 작업기간 - 23/06 ~ 23/11 - 5개월

<div align=center><h1>📚 STACKS</h1></div>
<div align=center> 
  <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> 
  <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"> 
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> 
  <img src="https://img.shields.io/badge/jquery-0769AD?style=for-the-badge&logo=jquery&logoColor=white">
  <br>
  <img src="https://img.shields.io/badge/bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white">
  <br>
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
  <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/fontawesome-339AF0?style=for-the-badge&logo=fontawesome&logoColor=white">
  <br>
</div>

<h2>MovilePlaza Demo - <a target="_blank" href="https://bp4sp4.github.io/MoviePlazaDemoSite/">MoviePlaza</a><br>
MovilePlaza All - <a target="_blank" href="https://www.figma.com/file/hG4KAIo0PVI0ZOLqZMIQyT/MoviePlaza?type=design&node-id=0-1&mode=design&t=TlKGTC03a9pZN7qv-0">figma</a></h2>

<h3>파트별 설명</h3>
<h3>1. 작품DB</h3>
    
- 가상태그를 사용함에 있어 어렵단 느낌이 들었는데 막상 사용해보니 어렵지 않았다.
- 글만 적어 놓으니 너무 휑한 느낌이 들어 이모티콘과 색을 집어놓았다.
- 사실 first-child 같은 가상태그를 많이 안썼는데 유용하게 사용하게 되면서 이후에도 많이 쓴 계기가 된 거 같다.
<code>
 <pre>
 .movie-info li::before {
   content: "";
   display: block;
   height: 20px;
   background: #000;
   opacity: 0.7;
   position: absolute;
   width: 1px;
   top: 10px;
 }
 .movie-info li:first-child::before {
  width: 0;
}

</pre>
</code>
<h3>2. 트렌트 분석</h3>

- 퍼블 요청으로는 마인드맵을 넣어야했다.
- 직접 디자인을 할까 고민했는데 구글링을 해보니 모비스크롤이라는 라이브러리를 찾아 안쓸이유가 없다 생각이들어 적용했다.

<h3>3. 영화관순위</h3>

- 영화관순위 페이지는 영화진흥위원회 데이터를 크롤링한다고하여 백엔드 유지보수도 좋게 테이블 형식으로 만들었다.

<h3>4. ott 순위</h3>

- 아래 사진 참고해 만들었다.
  ![ottrank](https://github.com/bp4sp4/MoviePlazaDemoSite/assets/62207757/1b71719b-1254-4cec-a5f9-1c6a0b350d47)

프로젝트 아쉬운점

- 퍼블리싱 피드백 텀이 길어 작업기간이 길어졌다.
- 실 작업 시간은 1달정도 걸렸다.
<h2>To-Do-List</h2>
<ul>
<li> [X] 작품db 검색이후 화면 디자인 </li>
<li> [X] 작품db 제작비, 흥행여부 추가 </li>
<li> [X] 아이디검색 -> 아이디 찾은 후 나오는 화면 </li>
<li> [X] OTT 순위 화면 디자인 </li>
<li> [X] OTT 순위 화면 클릭 후 표 </li>
<li> [X] 영화관 순위 페이지</li>
<li> [X] 트렌드분석 마인드맵</li>
</ul>

<h1>23/11/09</h1>
1. 비밀번호재설정페이지 생성완료 -> 로그인 -> 비밀번호 재설정<br>
2. 영화관순위 생성완료

<h1>23/11/08</h1>
1. 에러페이지 생성완료<br>
2. 네트워크오류페이지 생성완료<br>
3. 검색결과없을때 페이지 생성완료

<h1>23/11/06</h1>
1. 트렌드분석 검색후 디자인 완료 <br>
2. ott 순위 화면 디자인 완료<br>
3. 아이디 찾은후 화면 완료<br>

<h1>23/11/04</h1>
1. 작품db 검색이후 화면 디자인 완료 <br>
2. 어드민 로그아웃 버튼 생성<br>
3. 작품db 제작비 추가완료, 흥행여부 추가완료<br>

<h1>23/08/08</h1>
1. html,css 주석달기<br>
2. 로그인쪽 반응형 태블릿 반영<br>
3. MovilePlaza 전체 <a target="_blank" href="https://www.figma.com/file/hG4KAIo0PVI0ZOLqZMIQyT/MoviePlaza?type=design&node-id=0-1&mode=design&t=TlKGTC03a9pZN7qv-0">figma</a>생성

<h1>23/08/07 테스트후 수정</h1>
1. workdb 모바일디자인이상발견 -> 검색버튼쪽 스크립트로 해결<br>
2. 트렌드분석 <,> 버튼이상 발견 위치조정완료<br>
3. 어드민선택 반응형 완료 <br>
4. 모바일 햄버거 클릭시 메인컬러 적용 <br>
5. 트렌드분석 모바일 swiper 이상발견 -> 수정방안생각

 <h1>23/08/07</h1>
 1. 트렌드분석 좌우버튼 버그 수정<br>
 2. 트렌드분석 좌우버튼 반응형 모바일 테스트 해야함 테스트 후 수정<br>
 3. 모든탭메인 네비바와 간격수정<br>
 4. 어드민선택영역 타이틀 및 비쥬얼 업데이트<br>
 
 <h1>23/08/05</h1>
 1. 영화어드민 목록버튼 전체목록 검색추가<br>
 2. 영화어드민 영화개봉 label추가 (디자인 해야하는지 검수)<br>
 3. 메인페이지 메인컬러 적용<br>
 4. 제작비 추가 변경 버튼 추가<br>

 <h1>23/08/04</h1>
 1. wordkdb.html 검색 디자인 바꿈<br>
 2. 반응형 웹디자인 적용 (모바일, 테블릿, 웹) <br>
 3. 어드민눌렀을떄 회원, 영화어드민 선택 만들기<br>
 4. 메인컬러 설정<br>
 5. 회원어드민 목록 버튼 검색버튼추가<br>

 <h1>23/08/03</h1>
 1. 작품DB 비쥬얼업데이트 (시계바꿔야함)<br>
 2. 트렌드분석 일별, 주간별, 월별 , 연도별 Swiperjs 추가<br>
 3. OTT순위 비쥬얼업데이트, 페이지네이션 프론트작업 해야함<br>

 <h1>23/08/01</h1>
1. 작업DB 포스터와 내용들 추가 반응형 작업해야함<br>
2. 트렌드분석 select option 추가함<br>
3. ott순위 박스오피스와 비슷하게 만듬<br>
<hr>

 <h1>23/07/31</h1>
<h1>회의내용 참고해서 만들기</h1>
1. admin.html -> adminLogin.html<br>
2. 네비게이션바 -> 로그인, 로그아웃 추가<br>

 <h1>23/07/23</h1>
 <h2>반응형 웹디자인 로그인영역</h2>
 <h3>1.로그인<br>
 2. 아이디찾기<br>
 3. 비밀번호찾기<br>
 4. sns로그인<br>
 5. 메인 메뉴바</h3>

 <h2>트렌드분석</h2>
 <h3>포스터 우겨넣음 검수</h3>

 <h1>남은것들<h1>
 <h3>1. DB순위</h3>
 <h3>2. 영화관순위</h3>
 <h3><del>3.트렌드분석</del></h3>
 <h3>4. OTT순위</h3><br>

 <h1>어드민페이지</h1>
 <h3>1. 영화DB탭추가</h3>
 <p>불안요소 어드민페이지가 코드가 상당히 더러움 백엔드작업시 매우힘듬을 예상</p>

<h1>남은것들</h1>
<h3>UI</h3>
<h3>1. DB순위<br>
2.트렌드분석 <br>
3. 영화관순위<br>
4. OTT순위</h3>
<h3><del>5. 로그인 SNS 디자인</del></h3>
<h3><del>6. SNS 로그인 디자인</del></h3>

<h3>삭제예정</h3>
Contact Us 협의<br>
<br>

<h1> 23/06/22</h1>
<h2>수정사항</h2>
<h3>1. login.html sns영역 수정<br>2. snsjoin.html 사진 수정<br>
3. 타이틀 수정</h2>

<h1>23/06/21</h1>
<h2>Git Repo Create</h2>
<h2>추가사항</h2>
<h3>1. admin page <br>
2. myinfo.page <br>
3. myinfoupdate</h3>
