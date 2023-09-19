<style>
  @charset "UTF-8";
@import url("https://fonts.googleapis.com/css2?family=Baloo+2:wght@400;500;600;700&family=Noto+Sans+KR:wght@100;300;400;500;700&display=swap");
@import url("https://cdn.rawgit.com/moonspam/NanumSquare/master/nanumsquare.css");
/* reset */
body,
div,
dl,
dt,
dd,
ul,
ol,
li,
h1,
h2,
h3,
h4,
h5,
h6,
pre,
code,
form,
fieldset,
legend,
textarea,
p,
blockquote,
th,
td,
input,
select,
textarea,
button,
header,
main,
article,
footer,
i {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

fieldset,
img {
  border: 0 none;
}

dl,
ul,
ol,
menu,
li {
  list-style: none;
}

blockquote,
q {
  quotes: none;
}

blockquote:before,
blockquote:after,
q:before,
q:after {
  content: "";
  content: none;
}

input,
select,
textarea,
button {
  vertical-align: middle;
}

button {
  border: 0 none;
  background-color: transparent;
  cursor: pointer;
}

body {
  background: #fff;
}

body,
th,
td,
input,
select,
textarea,
button {
  font-size: 16px;
  line-height: 1.5;
  font-family: "Baloo 2", "Malgun Gothic", "Apple Gothic", sans-serif;
  color: #333;
} /* color값은 디자인가이드에 맞게사용 */
a {
  color: #333;
  text-decoration: none;
}

a:active,
a:hover {
  text-decoration: underline;
}

address,
caption,
cite,
code,
dfn,
em,
var {
  font-style: normal;
  font-weight: normal;
}

a:hover {
  text-decoration: none;
}

body {
  background: #fff;
  /*
      background-attachment: fixed, fixed, fixed;
      background-image: url("images/overlay2.png"), url("images/overlay3.svg"), linear-gradient(45deg, $red 40%, #4fa49a 75%, #9dc66b);
      background-position: top left, center center, center center;
      background-size: auto, cover, cover;
  */
}

.blind {
  font-size: 0;
  line-height: 0;
  text-indent: -9999px;
}

.navbar-header {
  margin-top: 5px;
}

.navbar {
  width: 100%;
  margin-bottom: 0;
  background: #fff;
  letter-spacing: 0;
  border: 0;
  transition: all 0.3s;
  border-radius: 0;
}
.navbar .container {
  width: 95% !important;
  max-width: 1280px;
  margin: 0 auto;
}
.navbar .navbar-brand {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 70px;
  margin-left: 0 !important;
  padding: 0;
  color: #000;
  font-family: "Baloo 2", "cursive";
  font-size: 30px;
  font-weight: 400;
  line-height: normal;
}
.navbar .navbar-brand span {
  color: #d45560;
}
.navbar .navbar-brand em {
  display: inline-block;
  margin: -3px 20px 0;
  color: #d45560;
  font-family: "Lato", sans-serif;
  vertical-align: middle;
}
.navbar .navbar-nav {
  margin-right: 20px;
}
.navbar .navbar-nav li.on a {
  color: #d45560;
}
.navbar .navbar-nav > li > a {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 0 20px;
  color: #000;
  height: 70px;
}

.navbar-nav li a:hover, .navbar-nav li.active a {
  color: #d33c4a !important;
  background-color: #fff !important;
}

.contents {
  display: flex;
  align-items: center;
  justify-content: center;
  height: calc(100vh - 75px);
}

.navbar-collapse {
  float: right;
  padding: 0;
}

.navbar .navbar-toggle {
  cursor: pointer;
  border-color: transparent;
  color: #fff !important;
}

.nav-tabs > li > a {
  font-size: 1.6rem;
  font-weight: 400;
  color: #fff;
}
.nav-tabs > li.active > a {
  background-color: #f7f7f7;
}

.nav-tabs > li > a:hover {
  background-color: #d45560;
}

.tab-content {
  padding: 50px;
  background-color: #f7f7f7;
}

.intro {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  overflow: hidden;
  width: 1170px;
  height: 100vh;
  min-height: 520px;
  margin: 0 auto;
  padding-top: 65px;
  /*margin: 0 auto;*/
  /*color: rgba(255, 255, 255, 0.75);*/
}
.intro .btn-down {
  display: block;
  position: absolute;
  bottom: 20%;
  left: 47%;
  width: 40px;
  height: 23px;
  margin-left: 20px;
  color: #fff;
  font-size: 2em;
  /*background: url(../imgs/intro/arrow-down.png) 0 0 no-repeat;*/
}

.intro-bg {
  width: 100%;
  height: 100vh;
}

#banner,
#portfolio,
#about,
#story,
#pricing,
#contact,
footer {
  position: relative;
  z-index: 200;
}

#portfolio {
  padding-top: 50px;
  background-color: transparent;
}

/* text animate */
.content {
  position: relative;
  margin-bottom: 40px;
  padding: 0 40px;
  /*-webkit-transform: translate(-50%, -50%);*/
  /*transform: translate(-50%, -50%);*/
  font-family: "Lato", sans-serif;
  font-size: 6em;
  color: #ecf0f1;
  font-weight: 600;
}
.content:before {
  content: "{";
  left: -10px;
  color: #16a085;
}
.content:after {
  content: "}";
  position: absolute;
  right: 0;
  color: #d33c4a;
  position: absolute;
  top: 13px;
  font-size: 0.7em;
  font-weight: normal;
  line-height: normal;
  -webkit-animation-name: opacity;
  -webkit-animation-duration: 2s;
  -webkit-animation-iteration-count: infinite;
  animation-name: opacity;
  animation-duration: 2s;
  animation-iteration-count: infinite;
}
.content:before {
  position: absolute;
  top: 13px;
  font-size: 0.7em;
  font-weight: normal;
  line-height: normal;
  -webkit-animation-name: opacity;
  -webkit-animation-duration: 2s;
  -webkit-animation-iteration-count: infinite;
  animation-name: opacity;
  animation-duration: 2s;
  animation-iteration-count: infinite;
}

.content__wrap {
  overflow: hidden;
  height: 110px;
}

.content__container__text {
  display: inline;
  float: left;
  margin: 0 !important;
  line-height: 106px;
}

.content__container__list {
  margin-top: 0;
  padding-left: 80px;
  text-align: left;
  list-style: none;
  -webkit-animation-name: change;
  -webkit-animation-duration: 10s;
  -webkit-animation-iteration-count: infinite;
  animation-name: change;
  animation-duration: 10s;
  animation-iteration-count: infinite;
  transform: translate3d(0, -75%, 0);
}

.jumbotron {
  height: 100vh;
  background-color: #f4511e;
  color: #fff;
  padding: 100px 25px;
  font-family: Montserrat, sans-serif;
}

.container-fluid {
  max-width: 1280px;
}
.container-fluid .row {
  overflow: hidden;
  margin-bottom: 30px;
}

@media screen and (max-width: 768px) {
  .container-fluid {
    padding: 0 8%;
  }
}
.bg-grey {
  background-color: #f6f6f6;
}

.logo-small {
  color: #f4511e;
  font-size: 50px;
}

.logo {
  color: #f4511e;
  font-size: 12.5em;
}

.thumbnail {
  padding: 0 0 15px 0;
  border: none;
  border-radius: 0;
  background-color: transparent;
}
.thumbnail h3 {
  font-size: 2rem;
  color: #fff;
}
.thumbnail p {
  margin: 10px 0;
  color: #fff;
  opacity: 0.8;
}
.thumbnail .image {
  overflow: hidden;
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;
  margin: 0 0 2em 0;
  width: 100%;
  height: 150px;
  border: 1px solid rgba(238, 238, 238, 0.7);
  border-radius: 8px;
  background: #fff;
}
.thumbnail img {
  width: auto;
  height: 80%;
  margin-bottom: 10px;
  transition: all 0.3s;
}
.thumbnail:hover img {
  transform: scale(1.1);
}
.thumbnail .daum img {
  width: 30%;
}
.thumbnail p {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 45px;
}
.thumbnail .hashtag {
  margin-right: 10px;
  color: #fff;
  opacity: 0.5;
}

footer {
  padding: 20px 8% 10px !important;
  background: transparent;
  color: #fff;
  letter-spacing: 0;
}
footer .glyphicon {
  font-size: 1.25em;
  margin-bottom: 20px;
  color: #fff;
}

/*sub*/
.box-explain {
  display: flex;
  margin-bottom: 30px;
  padding: 15px 40px 10px;
  text-align: left;
  background: #fff;
  border: 1px solid #ddd;
  border-top: 3px solid #d33c4a;
}
.box-explain dl {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
  width: 50%;
  margin: 0;
}
.box-explain dt {
  width: 20%;
  height: 26px;
  margin-bottom: 5px;
  background: #444;
  text-align: center;
  font-weight: normal;
  font-size: 0.75em;
  line-height: 26px;
  color: #ddd;
}
.box-explain dd {
  width: 75%;
  /*height: 26px;*/
  font-size: 0.875em;
  line-height: 26px;
}
.box-explain a {
  display: block;
}

.box-img.row {
  margin-bottom: 100px;
}
.box-img.mb0 {
  margin-bottom: 0;
}
.box-img img {
  width: 100%;
  margin-bottom: 20px;
  border-radius: 8px;
}

.slideanim {
  visibility: hidden;
}

.slide {
  animation-name: slide;
  -webkit-animation-name: slide;
  animation-duration: 1s;
  -webkit-animation-duration: 1s;
  visibility: visible;
  margin-top: 100px;
}

@keyframes slide {
  0% {
    opacity: 0;
    transform: translateY(70%);
  }
  100% {
    opacity: 1;
    transform: translateY(0%);
  }
}
@media screen and (max-width: 1250px) {
  .content {
    font-size: 10vw;
  }
  .content:after, .content:before {
    top: 193px;
    /*font-size: 200px;*/
  }
}
@media screen and (max-width: 768px) {
  .wrap {
    padding-top: 70px;
    background-size: cover;
  }
  .col-sm-4 {
    margin: 25px 0;
  }
  .btn-lg {
    width: 100%;
    margin-bottom: 35px;
  }
  .navbar-header {
    margin-top: 0;
  }
  .navbar-nav {
    margin: 0;
  }
  .navbar-nav > li {
    float: left;
    margin-left: 0;
  }
  .navbar-nav > li > a {
    padding-top: 15px;
    padding-bottom: 15px;
  }
  .container-fluid .row {
    margin-bottom: 0;
  }
  .navbar .navbar-brand {
    margin-left: 20px !important;
    font-size: 1.7em;
  }
  .navbar .navbar-brand b {
    font-size: 1.6em;
    line-height: 0.7em;
  }
  .navbar .navbar-brand b:before {
    top: 9px;
    left: -3px;
  }
  .navbar-collapse {
    float: none;
    position: absolute;
    top: 0;
    right: 0;
    border: none;
    box-shadow: none;
  }
}
@media screen and (max-width: 480px) {
  body {
    letter-spacing: 0;
  }
  .navbar .navbar-brand {
    margin-left: 10px !important;
    font-size: 1.5em;
  }
  .navbar .navbar-brand b {
    font-size: 1.4em;
    line-height: 0.7em;
  }
  .navbar .navbar-brand b:before {
    top: 9px;
    left: -3px;
  }
  .navbar-collapse {
    top: 2px;
    right: 0;
  }
  .navbar .navbar-nav > li > a {
    font-size: 0.875em;
    padding: 15px 10px;
  }
  .navbar .navbar-nav > li:last-child > a {
    padding: 15px 15px;
  }
  .navbar .navbar-nav > li > a > span {
    display: none;
  }
  .affix .navbar-header .navbar-brand {
    margin: 14px 0 0 0;
  }
  .affix .navbar-collapse {
    top: 0;
  }
  .logo {
    font-size: 9.375em;
  }
  .content {
    padding: 0;
    font-size: 12vw;
  }
  .content:after {
    top: 98px;
  }
  .content:before {
    top: 98px;
    left: -17px;
  }
  .content:after {
    right: -18px;
  }
  .content__wrap {
    height: 60px;
    margin-top: -15px;
  }
  .intro .btn-down {
    bottom: 14%;
    left: 50%;
    margin-left: -10px;
  }
  h2 {
    font-size: 1em;
    margin-bottom: 20px;
  }
  #about h2 {
    font-size: 2em;
  }
  .thumbnail .image {
    height: 180px;
  }
  .about-history-list strong {
    font-size: 1.1em;
  }
  #contact {
    height: 90vh;
  }
  .slide {
    display: none;
  }
  .box-explain {
    flex-direction: column;
    padding: 15px;
  }
  .box-explain dl {
    width: 100%;
  }
  .box-explain dt {
    width: 21%;
  }
  .box-explain dd a {
    display: block;
    overflow: hidden;
    white-space: nowrap;
    text-overflow: ellipsis;
  }
}/*# sourceMappingURL=comm.css.map */
</style>

<div id="profile" class="container-fluid text-center bg-grey">
                <ul class="lst-profile">
                    <li>
                        <a href="./portfolio-flato.html" class="thumbnail">
                            <span class="image mintpink">
                                odd:odd
                            </span>
                            <h3>odd:odd</h3>
                            <p>프론트엔드, 웹접근성, 인터랙션, 반응형, UI/UX, 웹퍼블리싱</p>
                            <div class="card__hashtags">
                                <span class="hashtag">#React</span>
                                <span class="hashtag">#Javascript</span>
                                <span class="hashtag">#Responsive</span>
                                <!-- <span class="hashtag">#jQuery</span> -->
                                <span class="hashtag">#Bootstrap</span>
                                <span class="hashtag">#SASS</span>
                                <span class="hashtag">#Photoshop</span>
                                <span class="hashtag">#Illustrator</span>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="portfolio-flato.html#p2" class="thumbnail">
                            <span class="image daum">
                                <img src="http://eehd80.dothome.co.kr/imgs/intro/logo-daumkakao.png" alt="daumkakao" />
                            </span>
                            <h3>Daum service</h3>
                            <p>Daum, kakao UI개발</p>
                            <div class="card__hashtags">
                                <span class="hashtag">#Javascript</span>
                                <span class="hashtag">#jQuery</span>
                                <span class="hashtag">#Responsive</span>
                                <span class="hashtag">#Bootstrap</span>
                                <span class="hashtag">#SCSS</span>
                                <span class="hashtag">#Photoshop</span>
                                <span class="hashtag">#Illustrator</span>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="http://cafe.naver.com/mocoding" class="thumbnail" target="_blank">
                            <span class="image">
                                <img src="http://eehd80.dothome.co.kr/imgs/intro/logo-green.png" alt="그린컴퓨터 아카데미" />
                            </span>
                            <h3>그린컴퓨터 아카데미</h3>
                            <p>
                                UIUX 반응형 웹 프로젝트 /<br />
                                웹디자인기능사 / GTQ 강의
                            </p>
                            <div class="card__hashtags">
                                <span class="hashtag">#HTML5</span>
                                <span class="hashtag">#CSS3</span>
                                <span class="hashtag">#Javascript</span>
                                <span class="hashtag">#Bootstrap</span>
                                <span class="hashtag">#Photoshop</span>
                                <span class="hashtag">#Illustrator</span>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="./portfolio-paxnet.html" class="thumbnail">
                            <span class="image">
                                <img src="http://eehd80.dothome.co.kr/imgs/intro/logo-paxnet.png" alt="paxnet" />
                            </span>
                            <h3>No.1 재테크포털 모네타/팍스넷</h3>
                            <p>
                                사이트 내 UI/UX, 웹디자인, 웹퍼블리싱<br />
                                모의투자대회
                            </p>
                            <div class="card__hashtags">
                                <span class="hashtag">#HTML5</span>
                                <span class="hashtag">#CSS3</span>
                                <span class="hashtag">#Photoshop</span>
                                <span class="hashtag">#Illustrator</span>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="./portfolio-woongjin.html" class="thumbnail">
                            <span class="image"><img src="http://eehd80.dothome.co.kr/imgs/intro/logo-woongjin.png" alt="웅진패스원" /></span>
                            <h3>웅진패스원(KG패스원)</h3>
                            <p>농협, 동국제강, SK네트웍스, 대한병원협회, <br />아주그룹 직무교육 사이트 제작</p>
                            <div class="card__hashtags">
                                <span class="hashtag">#html5</span>
                                <span class="hashtag">#scss</span>	                            
                                <span class="hashtag">#responsive</span>
                                <span class="hashtag">#javascript</span>
                                <span class="hashtag">#mobile 최적화</span>
                                <span class="hashtag">#웹표준</span>
                                <span class="hashtag">#웹접근성</span>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="portfolio-flash.html" class="thumbnail" target="_blank">
                            <span class="image"><img src="http://eehd80.dothome.co.kr/imgs/intro/logo-flash.png" alt="플래시책저" /></span>
                            <h3>플래시 책 저</h3>
                            <p>
                                플래시8 Motion+Action <br />
                                플래시MX 모든걸 가르쳐주마
                            </p>
                            <div class="card__hashtags">
                                <span class="hashtag">#제우미디어</span>
                                <span class="hashtag">#flash</span>
                                <span class="hashtag">#Motion</span>
                                <span class="hashtag">#Action</span>
                            </div>
                        </a>
                    </li>
                </div>
