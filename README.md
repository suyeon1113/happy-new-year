<!DOCTYPE html>

<html lang="en">

​

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>얘들아 안뇽</title>

​

<link rel="shortcut icon" href="https://img.favpng.com/9/10/17/clip-art-santa-claus-free-content-openclipart-image-png-favpng-iUqtTcCpyFMswv9r1ctc5mnRk.jpg">

​

<meta property="og:image" content="https://manateequeen.com/wp-content/uploads/2018/09/christmas-lights-cruise-jupiter-florida-800x400.jpg">

<meta property="og:title" content="수연이의 카드">

<meta property="og:description" content="2021년 코딩왕을 노리며">

<script src="https://s3.ap-northeast-2.amazonaws.com/materials.spartacodingclub.kr/xmas/snow.js"></script>

​

<link rel="preconnect" href="https://fonts.gstatic.com">

<link href="https://fonts.googleapis.com/css2?family=Nanum+Gothic+Coding&display=swap" rel="stylesheet">

​

​

<style>

* {

font-family: 'Nanum Gothic Coding', monospace;

}

​

body {

​

background-color: #9b070f;

}

​

.envelope {

​

width: 200px;

height: 200px;

background-image: url('https://pngimg.com/uploads/envelope/envelope_PNG18366.png');

background-size: cover;

background-position: center;

margin: 200px auto 0px auto;

cursor: pointer;

}

​

.envelope-msg {

text-align: center;

color: honeydew;

}

​

.letter-close {

​

display: block;

}

​

.letter-open {

​

display: none;

}

​

.rtan {

background-color: white;

width: 200px;

height: 200px;

​

​

background-image: url('https://s3.ap-northeast-2.amazonaws.com/materials.spartacodingclub.kr/xmas/Webp.net-gifmaker+(2).gif');

background-size: cover;

background-position: center;

border-radius: 400px;

margin: 100px auto 0px;

border: white;

box-shadow: 0px 0px 10px 10px white;

​

}

​

h1 {

​

color: white;

text-align: center;

margin-top: 35px;

}

​

.messagebox {

background-color: thistle;

color: black;

text-align: center;

width: 300px;

height: 230px;

margin: auto;

font-size: 18px;

line-height: 30px;

box-shadow: 0px 0px 10px 10px white;

​

}

​

.from {

text-align: right;

}

​

@media screen and (max-width: 760px) {

.messagebox {

width: 300px;

padding: 20px;

}

}

</style>

<script>

function open_letter() {

document.getElementsByClassName("letter-close")[0].style.display = 'none'

document.getElementsByClassName("letter-open")[0].style.display = 'block'

​

}

​

function go_rtan()

{

alert('수연이 블로그에 놀러올래?!');

window.location.href='https://blog.naver.com/you_0_0'

}

​

</script>

</head>

​

<body>

<div class="letter-close">

​

​

<div class="envelope" onclick="open_letter()"></div>

<h2 class="envelope-msg">봉투를 열어봐</h2>

</div>

​

​

<div class="letter-open">

<div class="rtan" onclick="go_rtan()"></div>

<h1>오늘은 12월 25일</h1>

<div class="messagebox">

친구들에게. <br />

밖에 나가지 말아라 <br />

감기 걸린다 코로나 걸린다 <br />

따듯하게 입고 다니렴 <br />

나 코딩 잘하지?! <br />

<p class="from">2020.12.25 수연이가</p>

</div>

</div>

</body>

​

</html>
