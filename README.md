# cafesample
<!DOCTYPE>
<html lang="ja">
<head>
<meta charset="UTF-8">
<link rel="stylesheet" type="text/css" href="example.css">
<title>カフェサイト</title>
<style>
header {
  height: 1000px;
}
.pic {
  float: right;
  width: 92%;
}
.pic img {
  width: 90%;
  height: 1500px;
  margin: 50px 50px 200px 50px;
}
.header-nav {
  height: 1600px;
  text-align: center;
}
.header-nav table {
  margin-right: auto;
  margin-left: auto;
}
.header-nav img {
  width: 5%;
}
.header-nav table {
  color: #fff;
}
.header-nav th {
  padding-top: 20px;
}
.nav-big {
  font-size: 1.2em;
  font-family: monospace;
  line-height: .6em;
}
.nav-small {
  font-size: .6em;
  line-height: .6em;
}
.blog-ran {
  background: url(pictures/small-logo.png) center top no-repeat;
  background-size: 64px auto;
  background-position: right 50% top 94%;
  padding: 800px 0 0;
  margin: 0 auto 30px;
  color: #b98e51;
  font-family: 'henriette', sans-serif;
  font-size: 24px;
  font-size: 2.4rem;
  font-weight: normal;
  text-align: center;
  line-height: 1.4;
  letter-spacing: 0.24em;
}
.container .blog, .kodawari, .menu, .calender {
  width: 1200px;
  margin-left: auto;
  margin-right: auto;
}
.article {
  float: left;
  margin-left: 40px;
}
.article a {
  text-decoration: none;
}
.date{
  font-size: 1.2em;
  padding: 15px 0 0 8px;
  letter-spacing: .15em;
}
.article:hover {
  opacity: .7;
  transition: .5s;
}
.article img {
  width: 250px;
}
.article .honbun {
  width: 250px;
  color: #000;
}
.about-ran {
  background: url(pictures/small-logo.png) center top no-repeat;
  background-size: 64px auto;
  background-position: right 50% top 68%;
  padding: 130px 0 0;
  margin: 0 auto 30px;
  color: #b98e51;
  font-family: 'henriette', sans-serif;
  font-size: 24px;
  font-size: 2.4rem;
  font-weight: normal;
  text-align: center;
  line-height: 1.4;
  letter-spacing: 0.24em;
}
.intro-bun {
  width: 900px;
  height: 400px;
  margin-right: auto;
  margin-left: auto;
  line-height: 3.5em;
  letter-spacing: .3em;
  text-align: left;
  padding: 20px 0;
  display: flex;
}
.about {
  text-align: center;
}
.ver-bun {
  writing-mode: vertical-rl;
  font-size: 1.8em;
  height: 350px;
  margin: 0 40px;
  letter-spacing: .3em;
  font-family: メイリオ;
  color: #4b221d;
}
.about-bun {
  height: 100px;
}
.about img {
  width: 100%;
}
.kodawari {
  text-align: center;
}
.kodawari img {
  width: 100px;
  margin: 30px 0;
}
.kodawari table {
  margin-left: auto;
  margin-right: auto;
  margin-bottom: 90px;
}
.kodawari th {
  writing-mode: vertical-rl;
  height: 400px;
  width: 500px;
  line-height: 3em;
  letter-spacing: .2em;
  text-align: left;
}
.kodawari .kodawari-title {
  font-size: 1.3em;
  width: 100px;
  line-height: 2em;
  padding-left: 50px;
}
.kodawari-flame {
  border: solid 1px #000;
  position: relative;
  width: 1100px;
  height: 2250px;
  margin-left: auto;
  margin-right: auto;
  margin-bottom: 60px;
}
.kodawari-flame span {
  position: absolute;
  top: -65px;
  right: 370px;
}
.kodawari-flame img {
  width: 340px;
}
.kodawari-flame span:before {
    content: "";
    background: url(pictures/small-logo.png) center no-repeat;
    background-size: contain;
    width: 62px;
    height: 26px;
    margin: auto;
    position: absolute;
    top: 10px;
    left: 0;
    right: 0;
}
.contents-box {
  height: 600px;
  margin-bottom: 100px;
}
.title-box {
  width: 200px;
  height: 460px;
  text-align: center;
  position: relative;
  top: 100px;
  left: 20px;
  color: #bf9000;
}
.title-box img {
  width: 150px;
}
.title-box h3 {
  writing-mode: vertical-rl;
  position: absolute;
  top: 120px;
  left: 75px;
  font-size: 2.3em;
  font-family: serif;
}
.img-box1 {
  padding: 10px;
  background-image: url(pictures/117.jpg);
  background-repeat: no-repeat;
  top: -300px;
  width: calc(50vw + 300px);
  height: 400px;
  position: relative;
  left: calc(50% - 300px);
  background-size: cover;
}
.img-box2 {
  padding: 10px;
  background-image: url(pictures/116.jpg);
  background-repeat: no-repeat;
  top: -300px;
  width: calc(50vw + 300px);
  height: 400px;
  position: relative;
  left: calc(50% - 300px);
  background-size: cover;
}

.img-box3 {
  padding: 10px;
  background-image: url(pictures/115.jpg);
  background-repeat: no-repeat;
  top: -300px;
  width: calc(50vw + 300px);
  height: 400px;
  position: relative;
  left: calc(50% - 300px);
  background-size: cover;
}

.text-box {
  position: relative;
  top: -300px;
  left: 250px;
  width: 800px;
  letter-spacing: .5em;
  font-size: 1.17em;
  line-height: 1.8em;
  text-align: left;
}
.more-button {
  text-align: center;
}
.more-button img {
  width: 120px;
  margin: 40px 0;
}
.more-button a:hover {
  opacity: .7;
  transition: .5s;
}
.cafe-space{
  text-align: center;
}
.cafe-space img {
  width: 100%;
}
.menu {
  padding-top: 50px;
}
.menu-line-up {
    background: url(pictures/small-logo2.png) center top no-repeat;
    background-size: 64px auto;
    padding: 38px 0 0;
    margin: 0 auto 50px;
    color: #b98e51;
    font-family: 'henriette', sans-serif;
    font-size: 24px;
    font-size: 2.4rem;
    font-weight: normal;
    text-align: center;
    line-height: 1.4;
    letter-spacing: 0.24em;
}
.menu .box-wrap {
  padding: 0 0 20px 40px;
}
.menu .box-wrap img {
  width: 525px;
}
.menu .box-wrap a:hover {
  opacity: .7;
  transition: .4s;
}
.menu .box-wrap-col2 {
  padding: 0 0 20px 20px;
}
.menu .box-wrap-col2 img {
  width: 250px;
  padding: 0 0 0 20px;
}
.menu .box-wrap-col2 a:hover {
  opacity: .7;
  transition: .4s;
}
.menu .menu-img-box {
  display: flex;
}
.shop-info {
    background: url(pictures/small-logo.png) center top no-repeat;
    background-size: 64px auto;
    padding: 38px 0 0;
    margin: 0 auto 50px;
    color: #b98e51;
    font-family: 'henriette', sans-serif;
    font-size: 24px;
    font-size: 2.4rem;
    font-weight: normal;
    text-align: center;
    line-height: 1.4;
    letter-spacing: 0.24em;
}
.calender {
  text-align: center;
  padding: 50px 0;
}
.calender img {
  width: 900px;
  margin-bottom: 50px;
}
.shop-info-area {
  display: flex;
}
.shop-info-text {
  width: 380px;
  height: 550px;
  text-align: left;
  margin: 20px 50px 0 150px;
}
.shop-info-text h4, h5 {
  letter-spacing: .2em;
}
.shop-info-text h4 {
  font-size: 1.4em;
}
.shop-info-text h5 {
  font-size: 1em;
  line-height: 0em;
}
.shop-info-text h4 a {
  text-decoration: none;
  color: #b98e51;
}
.shop-info-area img {
  width: 550px;
}
.map {
  position: relative;
  padding-bottom: 20%;
  height: 0;
  overflow: hidden;
}
.map iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100% !important;
  height: 100% !important;
}
.footer-nav {
  height: 160px;
  display: flex;
  padding: 20px 0 0 0;
}
.left-block {
  margin-left: auto;
}
.left-block img {
  width: 130px;
}
.right-block {
  color: #fff;
  width: 400px;
  height: 100px;
  margin-right: auto; 
  line-height: .7;
  margin-top: 10px;
}
.right-box-top {
  display: flex;
}
.right-box-top li {
  list-style-type: none;
  margin: 0 15px;
  font-family: Microsoft Sans Serif;
  letter-spacing: .1em;
}
.right-box-bottom {
  display: flex;
}
.right-box-bottom li {
  list-style-type: none;
  margin: 0 16px;
  font-family: Microsoft Sans Serif;
  letter-spacing: .1em;
}
.footer-sns {
  position: relative;
  bottom: 64px;
  left: 370px;
} 
.footer-sns img {
  width: 32px;
  margin: 0 2px;
}
.footer-nav h3 {
  position: relative;
  bottom: 24px;
  left: 54px;
  font-family: Microsoft Sans Serif;
  width: 500px;
  font-size: .9em;
  letter-spacing: .3em;
}


---------
header {background-color: #fff;}
.pic {background-color: #fff;}
.header-nav {background-color: #cd780d;}
.blog {background-color: #fff;}
.about {background-color: #fff;}
.kodawari {background-color: #fff;}
.cafe-space {background-color: #fff;}
.menu {background-color: ;}
.menu-back {background-color: #fff1ec;}
.calender {background-color: #fff;}
.map {background-color: #789667;}
.footer-nav {background-color: #4b221d;}
---------

</style>
<body>

<!============ヘッダー=============>
<header>
  <div class="pic">
    <img src="pictures/pan.png">
  </div>
  <div class="header-nav">
    <img src="pictures/logo.png">
    <table>
      <tr class="nav-big">
        <th>CONCEPT</th>
      </tr>
      <tr class="nav-small">
        <th>こだわり</th>
      </tr>
      <tr class="nav-big">
        <th>MENU</th>
      </tr>
      <tr class="nav-small">
        <th>メニュー</th>
      </tr>
      <tr class="nav-big">
        <th>BLOG</th>
      </tr>
      <tr class="nav-small">
        <th>ブログ</th>
      </tr>
      <tr class="nav-big">
        <th>SHOP</th>
      </tr>
      <tr class="nav-small">
        <th>店舗情報</th>
      </tr>
    </table>
  </div>
</header>


<!============メイン=============>
<div class="container">
  <div class="blog">
    <h2 class="blog-ran">Blog</h2>
    <div class="article">
    <a href="a.html">
      <img src="pictures/124.jpg">
      <div class="honbun">
        <div class="date">2019.5.04</div>
        <p>ホールウィートクロワッサン</p>
      </div>
    </a>
    </div>    
    <div class="article">
    <a href="a.html">
      <img src="pictures/125.jpg">
      <div class="honbun">
        <div class="date">2019.4.22</div>
        <p>クラフトビール醸造所見学ツアー</p>
      </div>
    </a>
    </div>
    <div class="article">
    <a href="a.html">
      <img src="pictures/126.jpg">
      <div class="honbun">
        <div class="date">2019.2.03</div>
        <p>2019年バレンタイン限定ギフト販売開始</p>
      </div>
    </a>
    </div>
    <div class="article">
    <a href="a.html">
      <img src="pictures/127.jpg">
      <div class="honbun">
        <div class="date">2018.12.13</div>
        <p>【SOLD OUT】クリスマスローストチキンパッケージ</p>
      </div>
    </a>
    </div>
  <br style="clear: both;">
  </div>
  <div class="more-button">
    <a href="1.html"><img src="pictures/yajirusi.png"></a>
  </div>
  <div class="about">
  <h2 class="about-ran">About New Style Bakery</h2>
    <div class="intro-bun">
      <p class="ver-bun">北海道の清々しい朝</p>
      <p class="about-bun">こだわりぬいた乳牛から絞られた牛乳で作るバターが格別の味わい。牧場で食べるソフトクリームを上回る濃厚さで今日という日をノックアウト。ぜひご賞味あれ。
こだわりぬいた乳牛から絞られた牛乳で作るバターが格別の味わい。牧場で食べるソフトクリームを上回る濃厚さで今日という日をノックアウト。ぜひご賞味あれ。
こだわりぬいた乳牛から絞られた牛乳で作るバターが格別の味わい。牧場で食べるソフトクリームを上回る濃厚さで今日という日をノックアウト。ぜひご賞味あれ。</p>
    </div>
    <img src="pictures/hokkaidou4.png">
  </div>
  <div class="kodawari">
    <img src="pictures/logo2.png">
    <table>
      <tr>
        <th>「朝が好きになる街」。<br>
ここ札幌のの景色と、<br>
地元北海道産の食材にこだわった<br>
ハード系を中心としたパン屋です。<br>
毎日食べても飽きないベーシックな<br>
パンにこだわり、地元の方にも<br>
観光で北海道を訪れた方にも<br>
ワクワクしていただける場所でありたい。<br>
窓から見える絶景を見ながら<br>
いつもより豊かな朝を感じてください。</th>
        <th class="kodawari-title">北海道の朝と<br>
地元の食材に<br>こだわったパン屋</th>
      </tr>
    </table>
    <div class="kodawari-space">
      <div class="kodawari-flame">
        <span><img src="pictures/kodawari.png"></span>
        <div class="contents-box">
          <div class="title-box">
            <img src="pictures/01.png">
            <h3>四季折々の素材</h3>
          </div>
          <div class="img-box1">
          </div>
          <div class="text-box">
            <p>地元北海道の特産品を使った四季折々のパンを作っています。<br>
パンに使う小麦粉は北海道産のものにこだわっており、<br>
地産地消を目指しパンを楽しんでいただけるよう、<br>
日々精進してまいります。</p>
          </div>
          <br style="clear: both;">
        </div>
        <div class="contents-box">
          <div class="title-box">
            <img src="pictures/02.png">
            <h3>北海道の景色</h3>
          </div>
          <div class="img-box2">
          </div>
          <div class="text-box">
            <p>北海道の清々しい朝。<br>
そんな絶景を望みながらパンを召し上がっていただけるよう、
席数は少ないですがカフェスペースを設置いたしました。<br>
予約制でカフェスペース限定のプレートをご用意しております。</p>
          </div>
          <br style="clear: both;">
        </div>
        <div class="contents-box">
          <div class="title-box">
            <img src="pictures/03.png">
            <h3>お土産・贈り物</h3>
          </div>
          <div class="img-box3">
          </div>
          <div class="text-box">
            <p>お土産・贈り物としてパンのギフトはいかがですか<br>
ハード系のお案は普通のパンよりも日持ちするため、贈り物
にオススメです。</p>
          </div>
          <br style="clear: both;">
        </div>
        <div class="more-button">
          <a href="1.html"><img src="pictures/yajirusi.png"></a>
        </div>
      </div>
    </div>
  </div>
  <div class="cafe-space">
    <img src="pictures/pan3.png">
  </div>
  <div class="menu-back">
  <div class="menu">
    <h2 class="menu-line-up">Menu Line Up</h2>
    <div class="menu-img-box">
      <div class="img-box-bigtop">
        <div class="box-wrap">
          <a href="a.html"><img src="pictures/123.png"></a>
        </div>
        <div class="box-wrap-col2">
          <a href="a.html"><img src="pictures/118.png"></a>
          <a href="a.html"><img src="pictures/119.png"></a>
        </div>
      </div>
      <div class="img-box-bigbottom">
        <div class="box-wrap-col2">
          <a href="a.html"><img src="pictures/120.png"></a>
          <a href="a.html"><img src="pictures/121.png"></a>
        </div>
        <div class="box-wrap">
          <a href="a.html"><img src="pictures/122.png"></a>
        </div>
      </div>
    </div>
    <div class="more-button">
      <a href="1.html"><img src="pictures/yajirusi.png"></a>
    </div>
  </div>
  </div>
  <div class="calender">
    <h2 class="shop-info">Shop Info</h2>
    <img src="pictures/pan2.png">
    <div class="shop-info-area">
      <div class="shop-info-text">
        <h4>New Style Bakery</h4>
        <h5>〒○○○-○○○○</h5>
        <h5>北海道札幌市</h5>
        <h4>TEL 　<a href="a.html">○○○-○○○○-○○○</a></h4>
        <h4>MAIL 　<a href="a.html">aaa@gmail.com</a></h4>
        <h5>営業時間/8:00～16:00 ※売り切れ次第終了</h5>
        <h5>定休日/水</h5><br>
        <h5>札幌駅から徒歩5分</h5>
        <h5>駐車場 6台有り</h5>
      </div>
    <img src="pictures/calender.png">
    </div>
  </div>
</div>

<!============フッター=============>	
<footer>
  <div class="map">
    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2914.705338261852!2d141.3485666149236!3d43.06866449804987!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x5f0b2974d2c3f903%3A0xa5e2b18cdd4a47a5!2z5pyt5bmM6aeF!5e0!3m2!1sja!2sjp!4v1559110701199!5m2!1sja!2sjp" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>
  </div>
  <div class="footer-nav">
    <div class="left-block">
      <img src="pictures/small-logo3.png">
    </div>
    <div class="right-block">
      <ul class="right-box-top">
        <li>TOP PAGE</li>
        <li>MENU</li>
        <li>BLOG</li>
      </ul>
      <ul class="right-box-bottom">
        <li>CONCEPT</li>
        <li>SHOP</li>
      </ul>
      <div class="footer-sns">
        <a href="a.html"><img src="pictures/twitter-icon.png"></a>
        <a href="a.html"><img src="pictures/instagram-icon.png"></a>
      </div>
      <h3>Copyright(C) 札幌のパン屋 All rights reserved.</h3>
    </div>
  </div>
</footer>

</body>
</html>
