<html>
<head>
<title>genghis.com</title>
<style>
* {
  box-sizing: border-box;
}
body {
  font-family: Arial;
  padding: 10px;
  background: #f1f1f1;
}
.header {
  padding: 30px;
  text-align: center;
  background: white;
}
.header h1 {
  font-size: 50px;
}
.topnav {
  overflow: hidden;
  background-color: #333;
}
.topnav a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}
.topnav a:hover {
  background-color: #ddd;
  color: black;
}
.leftcolumn {   
  float: left;
  width: 75%;
}
.rightcolumn {
  float: left;
  width: 25%;
  background-color: #f1f1f1;
  padding-left: 20px;
}
.fakeimg {
  background-color: #aaa;
  width: 100%;
  padding: 20px;
}
.card {
  background-color: white;
  padding: 20px;
  margin-top: 20px;
}
.row:after {
  content: "";
  display: table;
  clear: both;
}
.footer {
  padding: 20px;
  text-align: center;
  background: #ddd;
  margin-top: 20px;
}
@media screen and (max-width: 800px) {
  .leftcolumn, .rightcolumn {   
    width: 100%;
    padding: 0;
  }
}
@media screen and (max-width: 400px) {
  .topnav a {
    float: none;
    width: 100%;
  }
}
</style>
</head>
<body>
<div class="header">
  <h1>genghis.com</h1>
  <p>the homepage of the great khan</p>
</div>
<div class="topnav">
  <a href="http://localhost:8080/about_genghis_khan/">all about the khan</a>
  <a href="http://localhost:8080/mongol_empire/">about the mongol empire</a>
  <a href="http://localhost:8080/mongolia/">about mongolia</a>
  <a href="http://localhost:8080/resources/">resources</a>
  <a href="http://localhost:8080/" style="float:right">home</a>
  <a href="http://localhost:8080/about/" style="float:right">about genghis.com</a>
</div>
<div class="row">
  <div class="leftcolumn">
    <div class="card">
      <h2>Genghis Khan biography</h2>
      <img src="https://upload.wikimedia.org/wikipedia/commons/3/35/YuanEmperorAlbumGenghisPortrait.jpg" style="height:200px;">
      <p>Click on the link below to hear the inspiring story of the rise greatest emperor that ever lived</p>
      <a href="http://localhost:8080/about_genghis_khan/genghis_khan_bioagraphy/">the story of genghis khan</a>
    </div>
    <div class="card">
      <h2>Fun facts about Genghis Khan</h2>
      <img src="https://upload.wikimedia.org/wikipedia/commons/f/f5/Dschingis_Khan_01.jpg" style="height:200px;">
      <p>Did you know that khan never let anyone paint his portrait. Click on the link for more fast facts about Chinghis Khaan</p>
      <a href='http://localhost:8080/about_genghis_khan/genghis_khan_fun_facts/'>genghis khan fun facts</a>
    </div>
    <div class="card">
      <h2>Genghis Khan good or bad</h2>
      <img src="https://upload.wikimedia.org/wikipedia/commons/b/bc/Mongol_Empire_map_2.gif" style="height:200px;">
      <p>To some the great khan was a brutal barbarian, to others he was a god. Click on the link to learn more</p>
      <a href='http://localhost:8080/about_genghis_khan/genghis_khan_good_or_bad/'>was genghis khan good or bad</a>
    </div>
    <div class="card">
      <h2>Genghis Khan battle tactics</h2>
      <img src="https://upload.wikimedia.org/wikipedia/commons/d/d0/Battle_of_Mohi.svg" style="height:200px;">
      <p>Learn the art of warfare from one of the greatest military geniuses of all time</p>
      <a href='http://localhost:8080/about_genghis_khan/genghis_khan_battle_tactics/'>genghis khan battle tactics</a>
    </div>
  </div>
  <div class="rightcolumn">
    <div class="card">
      <h2>About Me</h2>
      <p>Hey, im Matthew the founder of genghis.com. Click the link below to learn more about me.</p>
      <a href="http://localhost:8080/about/">About the developer</a>
    </div>
    <div class="card">
      <h3>Sugested pages</h3>
      <img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Siège_de_Beijing_%281213-1214%29.jpeg" style="height: 175px; width: 175px">
      <a href="http://localhost:8080/about_the_khan/">Learn about the Khan.</a>
      <img src="https://upload.wikimedia.org/wikipedia/commons/0/02/Arkhangai_Aimag6.JPG" style="height:175px; width: 175px;">
      <a href="http://localhost:8080/mongolia/">Learn about Mongolia.</a>
      <a href="http://localhost:8080/about/">About genghis.com</a>
    </div>
  </div>
</div>
<div class="footer">
  <h1>A tribute to the Khan.</h1>
  <h2 style="font-size: 100%;">created by Matthew Cordero</h2>
</div>
</body>
</html>
