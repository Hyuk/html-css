# HTML & CSS


## HTML 이란?
Hyper Text Markup Language

## HTML TAG
* HTML5 Declaration
```html
<!DOCTYPE html>
```

* HTML5 basic structure
```html
<!DOCTYPE html>
<html lang="ko">
    <head>
        <meta charset="UTF-8">
        <title>HTML</title>
    </head>
    <body>
        <h1>Hello, HTML</h1>
    </body>
</html>
```

* Header Tag
```html
<h1></h1>
<h2></h2>
<h3></h3>
<h4></h4>
<h5></h5>
<h6></h6>
```

* Anchor Tag
```html
<a href="https://www.naver.com">네이버</a>
```

* Linebreak Tag
```html
<br />
```

* Image Tag
```html
<img src="" alt="네이버" width="400px" height="300px">
```

* Input Tag
```html
<input type="">
```

* Comment
```html
<!-- <h1>TItle</h1> -->
```

* Form Tag
```html
<form action="">
		<h1>Form 관련 요소</h1>
		<fieldset>
			<legend>기본 정보</legend>
			<label for="userid">아이디 : </label> <input type="text" placeholder="영문으로만 써주세요" id="userid"><br>
			<label for="userpw">비밀번호 : </label> <input type="password" id="userpw"><br>
			성별 : <label for="male">남자</label> <input type="radio" name="gender" id="male" checked>, <label for="female">여자</label> <input type="radio" name="gender" id="female"><br>
		</fieldset>
		<fieldset>
			<legend>부가 정보</legend>
			취미 : 영화 감상 <input type="checkbox" name="hobby" checked>, 음악 감상 <input type="checkbox" name="hobby">, 독서 <input type="checkbox" name="hobby"><br>
			프로필 사진 업로드 : <input type="file"><br>
			사는 지역 : <select>
				<option>서울</option>
				<option>경기</option>
				<option>강원</option>
				<option selected>제주</option>
			</select><br>
			자기소개 : <textarea cols="30" rows="5" placeholder="자기소개는 짧게 해주세요."></textarea><br>
			<button type="submit">전송</button>
			<button type="reset">취소</button>
		</fieldset>
	</form>
```

# Flexbox and CSS Grids
* Flexbox is one demension
* CSS Grids is two demensions

