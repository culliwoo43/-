<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8" />
<title>한류</title>
<style type="text/css">
	* {
		margin: 0;
		padding: 0;
	}
	ul li{
		list-style: none;
	}
	a {
		text-decoration: none;
		color:#333;
	}

	#menu {
		font:bold 16px "malgun gothic";
		width:700px;
		height:50px;
		background: #ccc;
		color:black;
		line-height: 50px; 
		margin:0 auto;
		text-align: center;
	}

	#menu > ul > li {
		float:left;
		width:140px;
		position:relative;
	}
	#menu > ul > li > ul {
		width:130px;
		display:none;
		position: absolute;
		font-size:14px;
		background: skyblue;
	}
	#menu > ul > li:hover > ul {
		display:block;
		
	}
	#menu > ul > li > ul > li:hover {
		background: orange;
		}
	h1 { text-align: center;}
	</style>
</head>
<body>
	<h1 >한류 페이지</h1>
<div id="menu">
	<ul>
		<li><a href="#">K-pop</a>
			<ul>
				<li><a href="#" onclick="location.href = 'BTS.html'">BTS</a></li>
				<li><a href="#" onclick="location.href = 'BlackPink.html'">Black Pink</a></li>
				<li><a href="#" onclick="location.href = 'PSY.html'">PSY</a></li>
			</ul>
		</li>
		<li><a href="#">한식</a>
			<ul>
				<li><a href="#" onclick="location.href = 'KimChi.html'">김치</a></li>
				<li><a href="#" onclick="location.href = 'bolgogi.html'">불고기</a></li>
				<li><a href="#" onclick="location.href = 'bibimbab.html'">비빔밥</a></li>
			</ul>
		</li>
		<li><a href="#">스포츠스타</a>
			<ul>
				<li><a href="#" onclick="location.href = 'son.html'">손흥민</a></li>
				<li><a href="#" onclick="location.href = '박지성.html'">박지성</a></li>
				<li><a href="#" onclick="location.href = '정찬성.html'">정찬성</a></li>
			</ul>
		</li>
		<li><a href="#">전통음악</a>
			<ul>
				<li><a href="#" onclick="location.href = '아리랑.html'">아리랑</a></li>
				<li><a href="#" onclick="location.href = '사물놀이.html'">사물놀이</a></li>
			</ul>
		</li>
		<li><a href="#">퀴즈</a>
			<ul>
				<li><a href="#" onclick="location.href = 'son.html'">난이도 상</a></li>
				<li><a href="#" onclick="location.href = '문제중.html'">난이도 중</a></li>
				<li><a href="#" onclick="location.href = '문제하.html'">난이도 하</a></li>
			</ul>
		</li>
	</ul>
</div>
</body>
</html>
