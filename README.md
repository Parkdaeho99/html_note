<HTML lang="ko">
	<HEAD>
		문서 정보
		화면에 출력 안되는 부분
		<meta charset="UTF-8">
		<TITLE> 제목 표시줄에 표시 </TITLE>
		<LINK>
		<STYLE> 스타일 정의
		<SCRIPT> 자바스크립트 등
	</HEAD>
	<BODY background="flower.jpg">
		화면에 출력 되는 부분
		<link> 링크(링크 색을 지정, 파란색)
		<vlink> visited링크(링크를 방문했었을 때 색을 지정, 보라색)
		<alink> active링크(링크를 클릭했을 때 색을 지정, 빨간색)
		<br> 한 줄 띄우기
		<font color = "FFFFFF"> 하얀글씨 </font>
		<p> 문 단 설 정, 이 안에 있는 건 모두 한 문단, 문단 구별을 위해 시작 점에서 한 줄 띄움 </p>
		<a href="http://www.naver.com"> 네이버로 이동합니다. </a> <-- a 태그의 href 옵션? -->
	</BODY>
</HTML>

주석표시방법 : <!-- 주석내용 -->
숫자표시방법 : 샵표시 (#0000FF)

<br> <link>는 쌍을 이루는 태그가 없고
<title> <font>는 쌍을 이루는 태그가 있다. 기준이?

------------------------------------------------------------------------------------------------------------------------------------------
EX)

<HTML lang="ko">
	<HEAD>
		<!-- 주석 테스트-->
		<meta charset="UTF-8">
		<TITLE> 홍길동의 홈페이지 </TITLE>
	</HEAD>
	<BODY background="flower.jpg" link="#0000ff" vlink="#808080" alink="ff0000" >
		<font color="#00ff00"> 녹색입니다. </font><br>
		아무것도 적용 안 한 글자입니다. <br>
		<p>문단의 시작점입니다.<br>
		<a href = "http://www.naver.com"> 하이퍼 레퍼런스 네이버로 이동 </a><br>
		<a href = "http://www.daum.net"> 하이퍼 레퍼런스 다음으로 이동 </a><br>
		문단 끝 </p>
		속성 없는 줄 긋기
		<hr><br>
		줄 사이즈(두께) 12
		<hr size="12"><br>
		그림자 없는 줄 긋기
		<hr noshade><br>
		줄 사이즈(두께) 30, 폭이 100픽셀, 그림자 없는 줄 긋기
		<hr size="30" width="100" noshade>
		줄 사이즈(두께) 30, 폭이 100%픽셀, 그림자 없는 줄 긋기
		<hr size="30" width="100%" noshade>
		TEST
		<hr color="0000FF" size="5" width="80%" align="left">
		<H1 align="center"> H1~H6 중 1 사이즈의 헤드라인(제목) + center 정렬 </H1>
		<H3 align="left"> H1~H6 중 3 사이즈의 헤드라인(제목) + left 정렬 </H3>
		<H6 align="right"> H1~H6 중 6 사이즈의 헤드라인(제목) + right 정렬 </H6>
		
	</BODY>
</HTML>
