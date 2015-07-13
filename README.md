body{
	background:url(../images/head.jpg)0px 0px;
	font-family: 'Lato', sans-serif;
	background-size:cover;
	
}
body a{
	transition: 0.5s all;
	-webkit-transition: 0.5s all;
	-o-transition: 0.5s all;
	-moz-transition: 0.5s all;
	-ms-transition: 0.5s all;
}
ul{
	padding: 0;
	margin: 0;
}

h1,h2,h3,h4,h5,h6,label,p{
	margin:0;	
}
.header{
	background: #30318b;
	border-bottom:7px solid #ffe71d;
	position:relative;
	box-shadow: 0px 50px 55px -40px rgb(43, 42, 42);
	-webkit-box-shadow:0px 50px 55px -40px rgb(43, 42, 42);
	-moz-box-shadow: 0px 50px 55px -40px rgb(43, 42, 42);
	-o-box-shadow: 0px 50px 55px -40px rgb(43, 42, 42);
}
.logo{
	float: left;	
	position:absolute;
}
.header-right{
	float:right;
	margin-top: 2em;
	width: 55%;
}
ul.account {
	color:#fff;
	font-size:10px;
	padding-left: 12em;
}
ul.account li{
	display: inline-block;
}
ul.account li a{
	font-size: 10px;
	text-decoration: none;
	color: #fff;
	font-weight: 300;
	font-style: italic;
	padding: 0 1em;
}
ul.account li a:hover{
	color:#ffe71d;
}
.top-nav ul li{
	display: inline-block;
	padding: 0em 1.5em 1em;
}
.top-nav ul li a{
	font-size: 1.1em;
	text-decoration: none;
	color: #fff;
	font-weight: 700;
	font-style: italic;
}
.top-nav ul li:hover,.top-nav ul li.active  {
	border-bottom: 10px solid #ffe71d;
}
.top-nav span.menu:before{
	content: url(../images/menu.png)no-repeat 0px 0px;
	cursor:pointer;	
	width:100%;
}
.top-nav span.menu{
	display: none;
}
/*--responsive media-quries--*/
@media(max-width:768px){
.top-nav ul{
	display: none;
	position:absolute;
	width:100%;
	z-index: 9999;
	left: 0%;
	margin: 0em;
	background:#f8d62e;

}
.top-nav span.menu{
	display: block;
	width:100%;
	position:relative;
	text-align: right;
	padding:0;
}
.top-nav ul li{
	display: block;
	float:none;
	padding: 1em 0.8em;
	text-align: center;	
}
.top-nav ul li a,.top-nav ul li.active a{
	color:#fff;
	border: none;
	padding: 0;
}
.top-nav ul li:hover{
	
}
.top-nav ul li a:hover,.top-nav ul li.active:hover{
	color:#000;
}
.top-nav ul li:hover,.top-nav ul li.active{
	border:none;
}
}
/*----*/
.top-nav{
	float:left;
	margin-top: 10px;
}
a.cart{	
	float: right;
	text-decoration: none;
	font-style: italic;
	color: #30318b;
	background: #ffe71d;
	padding: 7px 11px;
	font-size: 1.2em;
	font-weight: 900;
}
/*----*/
/* Default Skin */
a.ban:hover{
	text-decoration:none;
}
.wmuSlider {
	position: relative;
	overflow: hidden;
}
ul.wmuSliderPagination{
	display:none;
}
.wmuGallery .wmuGalleryImage {
	margin-bottom: 10px;
}
.wmuSliderPrev, .wmuSliderNext {
	position: absolute;
	width: 55px;
	height: 55px;
	text-indent: -9999px;
	background: url(../images/img-sprite.png)no-repeat;
	z-index: 2;
	cursor: pointer;
	bottom: 13em;
}
.wmuSliderPrev {
	background-position:-13px -13px;
	left: 0em;	
}
.wmuSliderNext {
	background-position:-83px -13px;
	right: 0em;
}
.short{
	float:left;
	width:45%;
	padding-left:4em;
}

.month{
	float:right;
	width:55%;
	margin-top: 3em;
}
.month h4{
	color: #30318b;
	font-size: 1.5em;
	font-weight: 900;
	background: #ffe71d;
	padding: 0.4em 2em;
	width: 75%;
	margin-bottom: 1em;
	font-style: italic;
}
.month-grid{
	background:rgba(126, 129, 147, 0.8);
	border-left:8px solid #ffe71d;
	width: 75%;
	padding: 1em 1em 2em;
}
.month-grid p{
	font-size: 1.1em;
	color: #fff;
	width: 100%;
	margin: 1em;
	line-height: 1.5em;
}
.banner {
	padding: 7em 0 2em;
}
.banner-btns{
	text-align:center;
}
.banner-btns span{
	text-decoration:none;
	color:#30318b;
	font-size:1.2em;
	font-weight:600;
	background:#ffe71d;
	padding: 0.5em 1.5em;
}
.banner-btns span:hover{
	background:#30318b;
	color:#ffe71d;
}
span.buy{
	padding: 0.5em;
	margin-left: 1em;
}
/*----*/
.content-top{
	background:#30338d;
	border-top:3px solid #ffe71d;
	margin:2em 0;
	padding: 1em 4em;
	box-shadow:0px 36px 31px -18px rgb(43, 42, 42);
	-webkit-box-shadow:0px 36px 31px -18px rgb(43, 42, 42);
	-moz-box-shadow: 0px 36px 31px -18px rgb(43, 42, 42);
	-o-box-shadow: 0px 36px 31px -18px rgb(43, 42, 42);
}
h5.welcome{
	float:left;
	color:#ffe71d;
	font-size:1.5em;
	font-style:italic;
}
.search{
	float:right;
	position: relative;
	background: #ecf0f1;
	width: 32%;
}
.search input[type="text"] {
	outline: none;
	padding:6px 15px;
	background: none;
	width: 91%;
	border: none;
	font-size:1em;
	color:#3b3c3e;	
	font-weight:400;
	font-style:italic;
}
.search input[type="submit"] {	
	width: 32px;
	height: 32px;
	background: #ffe71d url(../images/img-sprite.png) -147px -22px no-repeat;
	border: none;
	cursor: pointer;
	position: absolute;
	outline: none;
	top: 0;
	right: 0;
	outline: none;
}
/*----*/
.content-middle{
	background:url(../images/men.jpg)no-repeat 0px 0px;
	width:100%;
	min-height:315px;
	display:block;
	background-size:cover;
	margin: 0 0 2em;
}
.middle-content{
	float:right;
	text-align:center;
	margin-right: 4em;
}
.middle{
	background:#ffe71d;
	margin-bottom: 2em;	
	padding: 4em 1em 0.5em;
}
.middle h3{
	font-size:2.5em;
	color:#30318b;
	font-family: 'Vollkorn', serif;
	font-weight: bold;
	font-style: italic;
}
.middle p{
	font-size:1.2em;
	color:#30318b;
	padding: 0.5em 0;
	font-style: italic;
	font-weight: 600;
	line-height: 1.5em;
}
.middle p span{
	display:block;
}
.middle p b{
	font-size:1.7em;
}
p.from{
	font-weight:900;
}
a.get{
	text-decoration:none;
	color:#ffe71d;
	font-size:1.2em;
	font-weight:700;
	padding:0.7em 1.5em;
	background:#30318b;
}
a.get:hover{
	background:#ffe71d;
	color:#30318b;
}
/*----*/
p.tun{
	background:#30318b;
	font-size:1.2em;
	color:#fff;
	position:absolute;
	bottom:0;
	width: 100%;
	padding: 1em 0 1em 9em;
	font-weight: 700;
}
p.best{
	background:#cd2027;
	font-size:1.2em;
	color:#fff;
	position:absolute;
	top:0;
	right: 9%;
	font-weight: 900;
	padding: 1em;
	font-style: italic;
	text-align: center;
}
p.best span,p.number span{
	display:block;
}
.bottom-content {
	padding: 0;
	width: 32%;
	margin-right: 2%;
	position:relative;
}
.bottom-content:nth-child(3) {
	margin-right:0;
}
p.number{
	background:#ffe71d;
	font-size:1.2em;
	color:#30318b;
	position:absolute;
	bottom:0;
	left: 9%;
	font-weight: 900;
	padding: 1em;
	font-style: italic;
	text-align: center;
}
.content-bottom {
	padding-bottom: 13em;
}
.grid-top-in {
	position: relative;
}
.bottom-content:hover .pro-grid{
	display:block;
}
.pro-grid{
	text-align:center;
	position:absolute;
	top:0;
	width:100%;
	height:100%;
	display:none;
	padding: 8em 0 0;
}
.pro-grid p{
	font-size: 1.2em;
	color: #ffe71d;
	font-weight: 700;
	font-style: italic;	
}
.pro-grid b{
	font-size: 1.2em;
	color: #fff;
	font-style: italic;
	padding: 0.5em 0 1.5em;
	display: block;
	
}
.pro-btns span{
	text-decoration:none;
	color:#30318b;
	font-size:1.1em;
	font-weight:600;
	background:#ffe71d;
	padding: 0.5em 1.5em;
	text-transform: uppercase;
	font-style: italic;
}
.pro-btns span:hover{
	background:#30318b;
	color:#ffe71d;
}
span.buy-in{
	padding: 0.5em;
	margin-left: 1em;
}
.grid-top{
	background-image: linear-gradient(to bottom, #FFDF1F 0%, #FFC625 100%);
	padding:2em;
	position: absolute;
	bottom: -8em;
	box-shadow: 0px 50px 55px -40px rgb(43, 42, 42);
	-webkit-box-shadow:0px 50px 55px -40px rgb(43, 42, 42);
	-moz-box-shadow: 0px 50px 55px -40px rgb(43, 42, 42);
	-o-box-shadow: 0px 50px 55px -40px rgb(43, 42, 42);
}
.top-grid h5{
	font-size:1.2em;
	color:#30318b;
	font-weight: 900;
	font-style: italic;
	font-family: 'Vollkorn', serif;
	padding: 0 0 1em;
}
.top-grid p,.add p{
	font-size:1em;
	color:#30318b;
	line-height:1.5em;
	font-weight: 500;
}
i.in-house{
	width: 28px;
	height: 28px;
	background: url(../images/img-sprite.png) -189px -23px no-repeat;
	display:block;
	float:left;
}
i.in-on{
	background-position:-224px -23px;
}
.add{
	float:right;
	width:87%;
}
ul.social-in {
	float: left;
	padding: 0em 2em 0 0;
}
.house {
	padding-bottom: 1em;
}
.house:nth-child(3){
	padding-bottom:0;
}
ul.social-in li{
	list-style:none;
}
ul.social-in li a i{
	width: 35px;
	height: 35px;
	background: url(../images/img-sprite.png) -257px -20px no-repeat;
	display: inline-block;
	transition: 0.5s all;
	-webkit-transition: 0.5s all;
	-o-transition: 0.5s all;
	-moz-transition: 0.5s all;
	-ms-transition: 0.5s all;
}
ul.social-in li a i.thumblr{
	background-position:-350px -20px;
}
ul.social-in li a i.pin{
	background-position:-437px -20px;
}
ul.social-in li a i.twitter{
	background-position:-524px -20px;
}
ul.social-in li a i.dot{
	background-position:-608px -20px;
}
ul.social-in li a i:hover{
	background-position:-305px -20px;
}
ul.social-in li a i.thumblr:hover{
	background-position:-392px -20px;
}
ul.social-in li a i.pin:hover{
	background-position:-481px -20px;
}
ul.social-in li a i.twitter:hover{
	background-position:-567px -20px;
}
ul.social-in li a i.dot:hover{
	background-position:-653px -20px;
}
/*--product--*/
.top-product {
	margin: 8em 0 2em;
}
.bottom-product {
	padding-bottom: 2em;
}
ul.start{
	text-align:center;
	padding: 2em 0 10em;
}
ul.start li{
	display:inline-block;
}
ul.start li a span{
	text-decoration:none;
	color:#30318b;
	font-size:1.2em;
	padding:0.5em 1em;
}
ul.start li a span:hover{
	background:#30318b;
	color:#ffe71d;
}
ul.start li a i{
	width: 20px;
	height: 24px;
	background: url(../images/img-sprite.png) -27px -101px no-repeat;
	display:inline-block;
	vertical-align: middle;
}
ul.start li a i.next{	
	background-position: -51px -102px ;
}
/*--404--*/
.four{
	text-align:center;
	padding: 8em 1em 10em;
	min-height: 560px;
}
.four h1{
	font-size: 7em;
	color: #30318b;
	font-weight: 700;
	font-family: 'Vollkorn', serif;
}
.four p{
	font-size:1.5em;
	color:#fff;
	padding:0.7em 0 2em;
	font-style: italic;
}
a.details {
	text-decoration: none;
	font-size: 1.2em;
	color: #30318b;
	background: #ffe71d;
	padding: 0.4em 1em;
	font-weight: 700;
}
a.details:hover {
	background:#30318b;
	color:#ffe71d;
}
/*--contact--*/
.contact-in h4,.contact-form h4{
	font-size: 1.7em;
	color: #ffe71d;
	padding: 0 0 0.5em;
	font-style: italic;
	text-transform: uppercase;
}
p.your-para{
	font-size:1.2em;
	color:#30318b;
}
.map iframe{
	width: 100%;
	min-height:197px;
	border:none;
}
.contact-grid input[type="text"],.contact-grid textarea{
	width: 100%;
	padding: 1em;
	margin: 1em 0;
	background: #fff;
	outline:none;
	border: none;
	-webkit-appearance: none;
}
.contact-grid textarea{
	resize:none;
}
.send input[type="submit"]{
	width: 23%;
	font-size: 1.3em;
	background: #30318b;
	padding: 0.6em 1em;
	color: #ffe71d;
	border: none;
	outline:none;
	-webkit-appearance: none;
	text-transform: uppercase;
}
.send input[type="submit"]:hover{
	background:#ffe71d;
	color:#30318b;
}
.contact-form {
	padding: 6em 0 11em;
}
.contact-in p{
	font-size:1.2em;
	color: #30318b;
	width: 100%;
	line-height: 1.5em;
}
.address-more,.address-left{
	float:left;
	width:40%;
}
.map {
	padding: 6em 0 0.8em;
}
.address-left p a {
	text-decoration: underline;
	color: #30318b;
}
.address-left p a:hover{
	text-decoration: none;
}
/*--login--*/
.login-left h3, .login-right h3 {
	color:#ffe71d;
	font-size: 1.7em;
	font-style:italic;
	padding-bottom: 0.5em;
	text-transform:uppercase;
}
.login-left p, .login-right p {
	color:#30318b;
	display: block;
	font-size:1.2em;
	margin: 0 0 1.5em 0;
	line-height: 1.5em;
}
.acount-btn {
	background: #30318b;
	padding: 0.6em 1em;
	color: #ffe71d;
	font-size:1.2em;
	transition: 0.5s all;
	-webkit-transition: 0.5s all;
	-moz-transition: 0.5s all;
	-o-transition: 0.5s all;
	display: inline-block;
	text-transform: uppercase;
}
.acount-btn:hover{
	text-decoration:none;
	background:#ffe71d;
	color:#30318b;
}
.login-right span {
	font-size:1.2em;
	color:#30318b;
}
.login-right input[type="text"],.login-right input[type="password"] {
	width: 100%;
	padding: 1em;
	margin: 1em 0;
	background: #fff;
	outline:none;
	border: none;
	-webkit-appearance: none;
}
.login-right input[type="submit"] {
	background: #30318b;
	padding: 0.6em 1em;
	color: #ffe71d;
	font-size:1.2em;
	transition: 0.5s all;
	-webkit-transition: 0.5s all;
	-moz-transition: 0.5s all;
	-o-transition: 0.5s all;
	display: inline-block;
	text-transform: uppercase;
	border:none;
	outline:none;
}
.login-right input[type="submit"]:hover{
	background:#ffe71d;
	color:#30318b;
}
a.forgot {
	font-size:1.2em;
	color:#30318b;
}
.register {
	padding: 6em 0 11em;
}
/*--register--*/
.register-top-grid h3, .register-bottom-grid h3 {
	color:#ffe71d;
	font-size: 1.7em;
	font-style:italic;
	padding-bottom: 0.5em;
	text-transform:uppercase;
}
.register-top-grid span, .register-bottom-grid span {
	font-size:1.2em;
	color:#30318b;
	display:block;
}
.register-top-grid input[type="text"], .register-bottom-grid input[type="password"] {
	width: 100%;
	padding: 1em;
	margin: 1em 0;
	background: #fff;
	outline:none;
	border: none;
	-webkit-appearance: none;
}
.checkbox {
	margin-bottom: 4px;
	padding-left: 27px;
	line-height: 27px;
	cursor: pointer;
	float: left;
	position: relative;
}
.news-letter {
	color: #30318b;
	font-size: 1em;
	margin-bottom: 1em;
	display:inline-block;
	text-transform: uppercase;
	transition: 0.5s all;
	-webkit-transition: 0.5s all;
	-moz-transition: 0.5s all;
	-o-transition: 0.5s all;
	font-weight:400;
}
.checkbox i {
	position: absolute;
	bottom: 5px;
	left: 0;
	display: block;
	width:20px;
	height:20px;
	outline: none;
	border: 2px solid #ffe71d;
}
.checkbox input + i:after {
	content: '';
	background: url("../images/tick1.png") no-repeat 1px 2px;
	top: -1px;
	left: -1px;
	width: 15px;
	height: 15px;
	font: normal 12px/16px FontAwesome;
	text-align: center;
}
.checkbox input + i:after {
	position: absolute;
	opacity: 0;
	transition: opacity 0.1s;
	-o-transition: opacity 0.1s;
	-ms-transition: opacity 0.1s;
	-moz-transition: opacity 0.1s;
	-webkit-transition: opacity 0.1s;
}
.checkbox input {
	position: absolute;
	left: -9999px;
}
.checkbox input:checked + i:after {
	opacity: 1;
}
.news-letter:hover {
	color:#ffe71d;
}
.register-bottom-grid input[type="submit"] {
	background: #30318b;
	padding: 0.6em 1em;
	color: #ffe71d;
	font-size:1.2em;
	transition: 0.5s all;
	-webkit-transition: 0.5s all;
	-moz-transition: 0.5s all;
	-o-transition: 0.5s all;
	display: inline-block;
	text-transform: uppercase;
	border:none;
	outline:none;
}
.register-bottom-grid input[type="submit"]:hover{
	background:#ffe71d;
	color:#30318b;
}
/*--checkout--*/
h4.title {
	color:#ffe71d;
	font-size: 2em;
	font-style:italic;
	text-transform: uppercase;
}
p.cart {
	color:#30318b;
	font-size:1.2em;
	line-height:1.5em;
	padding: 0 0 0.5em;
}
p.cart a {
	text-decoration: underline;
	color: #ffe71d;
}
p.cart a:hover {
	text-decoration: none;
}
.check-out {
	padding: 10em 0em 15em;
	min-height: 438px;
}
/*--single--*/
/* start details */
.single {
	padding: 7em 0 10em;
}
.desc h3 {
	color: #ffe71d;
	font-size: 1.7em;
	margin-bottom: 10px;
	font-style:italic;
	text-transform: uppercase;
}
.desc p {
	font-size: 1.1em;
	color: #30318b;
	line-height: 1.5em;
}
.desc h5 {
	margin-top: 2%;
	font-size: 1.6em;
	color: #ffe71d;
	line-height: 1.5em;
}
.desc h5 a {
	margin-left: 5px;
	color: #30318b;
	font-size: 14px;
}
.images_3_of_2 {
	width: 37%;
	float: left;
	margin-right: 2.6%;
}
.desc1 {
	display: block;
	float: right;
	width: 60%;
}
.det_nav {
	margin: 6% 0;
}
.det_nav h4 {
	line-height: 1.5em;
	font-size: 2em;
	color: #ffe71d;
	margin-bottom: 4%;
	font-style:italic;
}
.det_nav ul li {
	display: inline-block;
	width: 20%;
	margin-right:4%;
}
/* start tabs */
.sap_tabs{
	padding: 1em 0;
}
.resp-tabs-list {
	width: 100%;
	list-style: none;
	padding: 0;
}
.resp-tab-item:first-child{
	border-left:none;
}
.resp-tab-item{
	font-size: 0.8125em;
	cursor: pointer;
	padding: 12px 10px;
	display: inline-block;
	margin: 0 ;
	text-align: center;
	list-style: none;
	float: left;
	outline: none;
	-webkit-transition: all 0.3s ease-out;
	-moz-transition: all 0.3s ease-out;
	-ms-transition: all 0.3s ease-out;
	-o-transition: all 0.3s ease-out;
	transition: all 0.3s ease-out;
	text-transform: uppercase;
}
.resp-tab-active{
	background:#ffe71d;
	color:#30318b;	
}
.resp-tab-item span{
	font-size:1.1em;
	color:#30318b;
	font-style: italic;
font-weight: 700;
}
.resp-tabs-container {
	padding: 0px;
	clear: left;
}
h2.resp-accordion {
	cursor: pointer;
	padding: 5px;
	display: none;
}
.resp-tab-content {
	display: none;
}
.resp-content-active, .resp-accordion-active {
   display: block;
}
h2.resp-accordion {
	font-size:1em;
	margin: 0px;
	padding: 10px 15px;
	background:#ffe71d;
	margin:10px 0;
	color:#30318b;
}
h2.resp-accordion:hover{
	background:#ffe71d;
	text-shadow: none;
}
.facts{
	border: 1px solid #D4D1D1;
	padding: 2em;
	background: #fff;
}
.facts p{
	color:#30318b;
	font-size:1.1em;
	line-height:1.7em;
	padding:0 0 1em;
}
.facts ul li{
	list-style:none;
	color:#30318b;
	font-size:1.1em;
	padding:0.3em 0;
}
 .block-subtitle {
	font-size: 1.5em;
	color: #ffe71d;
	text-transform: uppercase;
	margin-bottom: 10px;
	font-style:italic;
}
.list h5{
	font-size: 1.3em;
	color: #ffe71d;
}
.price-top li a{
	color:#30318b;
	font-size:1.2em;
	padding: 0.2em 0;
display: block;
}

ol.price-top {
	color: #30318b;
}
a.link1 {
	font-size: 1.1em;
	color: #30318b;
	display:block;
	padding:0.5em 0 0;
}
.tags {
	list-style: none;
	margin-top: 2em;
}
h4.tag_head {
	color: #ffe71d;
	font-weight: bold;
	font-size: 1.2em;
	margin-bottom: 1em;
}
ul.tags_links {
	padding: 0;
	list-style: none;
}
ul.tags_links li {
	display: inline-block;
	margin: 8px 3px;
}
ul.tags_links li a {
	font-size:1em;
	padding: 5px 10px;
	background: #fff;
	text-decoration:none;
	color:#30318b;
}
ul.tags_links li a:hover{
	color: #ffe71d;
	background:#30318b;
}
/* end details */
/*----*/
.footer {
	background: #30318b;
	padding: 10em 0 5em;
	border-top:5px solid #ffe71d;
	text-align:center;
}
.footer p {
	font-size: 1.1em;
	color: #fff;
}
.footer p a{
	text-decoration:none;
	color: #ffe71d;
}
.footer p a:hover{
	color: #fff;
}
#toTop {
	display: none;
	text-decoration: none;
	position: fixed;
	bottom: 25px;
	right: 10px;
	overflow: hidden;
	width: 52px;
	height: 52px;
	border: none;
	text-indent: 100%;
	background: url('../images/up.png') no-repeat 0px 0px;
}
/*--responsive--*/
@media(max-width:1440px){
}
@media(max-width:1366px){
.top-product {
	margin: 5em 0 2em;
}
}
@media(max-width:1280px){
}
@media(max-width:1024px){
.banner {
	padding: 5em 0 2em;
}
.pro-grid {
	padding: 4em 0 0;
}
.header-right {
	width: 62%;
}
.wmuSliderPrev, .wmuSliderNext {
	bottom: 8em;
}
.register {
	padding: 5em 0 11em;
}
.desc1 {
	width: 52%;
}
.images_3_of_2 {
	width: 44%;
}
}
@media(max-width:768px){
.header-right {
	width: 42%;
}
ul.account {
	padding-left: 0em;
}
.header-right {
	margin: 1.5em 0 1em;
}
a.cart {
	margin-top: 9px;
}
.month h4 {
	font-size: 1.1em;
	width: 82%;
}
.month-grid {
	width: 82%;
	padding: 0.1em 1em 2em;
}
.bottom-content {
	float: left;
}
.top-grid {
	float: left;
	width: 33.333%;
}
.month-grid p {
	font-size: 1em;
	height: 45px;
	overflow: hidden;
}
.month {
	margin-top: 1em;
}
.banner {
	padding: 5em 0 0em;
}
.middle h3 {
	font-size: 2em;
}
.middle p {
	font-size: 1.1em;
}
.middle {
	padding: 2em 1em 0.5em;
}
.content-middle {
	min-height: 260px;
}
p.number {
	font-size: 0.65em;
	left: 5%;
	padding: 0.8em;
}
p.best {
	font-size: 0.75em;
}
p.tun {
	font-size: 0.8em;
	padding: 1em 0 1em 7em;
}
.pro-grid p {
	font-size: 1em;
}
.pro-btns span {
	font-size: 0.8em;
}
.pro-grid p {
	font-size: 1em;
	padding: 0.5em;
}
span.buy-in {
	margin-left: 0.2em;
}
.pro-grid b {
	padding: 0.2em 0 0.5em;
}
.top-grid h5 {
	font-size: 0.9em;
}
 p.sed {
	height: 145px;
	overflow: hidden;
}
.add {
	width: 78%;
}
.wmuSliderPrev, .wmuSliderNext {
	bottom: 5em;
}
.send input[type="submit"] {
	width: 15%;
	font-size: 1.2em;
}
.map {
	padding: 2em 0 0.8em;
}
.contact-form {
	padding: 5em 0 12em;
}
.login-left {
	padding-top: 2em;
}
.login-right input[type="text"], .login-right input[type="password"]
,.register-top-grid input[type="text"], 
.register-bottom-grid input[type="password"] {
	width: 90%;
}
.desc h3 {
	font-size: 1.4em;
}
.det_nav h4 {
	font-size: 1.4em;
}
.sin {
	padding: 0;
}
.desc1 {
	width: 54%;
}
.images_3_of_2 {
	width: 42%;
}
.desc h3 {
	font-size: 1.3em;
}
.sin-left {
	padding: 0;
}
}
@media(max-width:640px){
.logo {
	width: 45%;
}
.logo img{
	width: 100%;
}
.header-right {
	width: 51%;
}
.header-right {
	margin: 1em 0 0.5em;
}
a.cart {
	padding: 5px 9px;
	font-size: 0.9em;
}
.top-nav {
	margin-top: 5px;
}
.month-grid p {
	font-size: 1em;
	width: 76%;
	margin:0.4em 1em;
}
.banner-btns span  {
	font-size: 1em;
}
.banner {
	padding: 3em 0 0em;
}
p.tun {
	font-size: 0.7em;
	padding: 1.2em 0 1.2em 7em;
}
.month-grid {
	width: 76%;
	padding: 0.1em 0em 2em;
}
.month {
	margin-top: 0em;
}
.content-top {
	padding: 1em 1em;
}
.search {
	width: 40%;
}
h5.welcome {
	font-size: 1.3em;
	padding-top: 0.4em;
}
.middle-content {
	margin-right: 2em;
}
.pro-grid {
	padding: 3em 0 0;
}
.grid-top {
	padding: 1em 0;
}
.top-grid h5 {
	font-size: 0.86em;
}
.content-bottom {
	padding-bottom: 9em;
}
a.get {
	font-size: 1em;
}
.bottom-product {
	padding-bottom: 2em;
}
ul.start {
	padding: 1em 0 9em;
}
.contact-form {
	padding: 5em 0 10em;
}
.register {
	padding: 4em 0 9em;
}
.desc1 {
	width: 43%;
}
.single {
	padding: 5em 0 9em;
}
.images_3_of_2 {
	width: 54%;
}
.desc h3 {
	font-size: 1.2em;
}
}
@media(max-width:480px){
ul.account {
	display: none;
}
a.cart {
	display: none;
}
.top-nav {
	float: right;
}
.logo {
	width: 58%;
}
.top-nav{
	margin:7px 0;
}
.short {
	float: none;
	width: 100%;
	padding-left: 0em;
}
.month {
	float: none;
	width: 100%;
}
.wmuSliderPrev, .wmuSliderNext {
	bottom: 18em;
}
.month h4 {
	font-size: 1.2em;
	width: 100%;
}
.month-grid {
	width: 100%;
}
h5.welcome {
	font-size: 0.9em;
	padding-top: 0.8em;
}
.search {
	width: 50%;
}
.middle h3 {
	font-size: 1.5em;
}
.middle p {
	font-size: 1em;
}
.middle {
	padding: 1em 1em 0.5em;
}
.content-middle {
	min-height: 220px;
}
.bottom-content {
	width: 49%;
}
.act{
	margin-right:0;
}
.ten{
	display:none;
}
.top-grid {
	width: 50%;
}
.top-grid:nth-child(1){
	display:none;
}
.top-product {
	margin: 3em 0 2em;
}
ul.start {
	padding: 1em 0 8em;
}
.contact-in h4, .contact-form h4 {
	font-size: 1.5em;
}
.send input[type="submit"] {
	width: 18%;
	font-size: 1em;
}
.address-more, .address-left {
	width: 50%;
}
.contact-form {
	padding: 4em 0 9em;
}
.register {
	padding: 4em 0 9em;
}
.login-right input[type="submit"] ,.acount-btn,
.register-bottom-grid input[type="submit"]{
	padding: 0.6em 0.8em;
	font-size: 1em;
}
.check-out {
	padding: 7em 0em 12em;
	min-height: 364px;
}
.images_3_of_2,.desc1 {
	width: 100%;
}
.resp-tab-item span {
	font-size: 1em;
}
.facts p {
	height: 50px;
	overflow: hidden;
}
}
@media(max-width:320px){
.logo {
	width: 70%;
}
.header-right {
	margin: 0.3em 0 0;
}
.month h4 {
	font-size: 0.9em;
}
.banner-btns span {
	font-size: 0.9em;
}
.month-grid p {
	width: 93%;
	margin: 0.5em 1em;
}
.month-grid {
	padding: 0.3em 0em 1.5em;
}
.banner {
	padding: 2em 0 0em;
}
.wmuSliderPrev, .wmuSliderNext {
	bottom: 16em;
}
h5.welcome {
	float:none;
	padding-top: 0;
}
.search {
	float: none;
	width:100%;
	margin: 0.5em 0 0;
}
.content-top {
	text-align: center;
}
.search input[type="text"] {
	padding: 6px 8px;
}
.middle h3 {
	font-size: 1.2em;
}
.middle p {
	font-size: 0.8em;
	width: 70%;
	margin: 0 auto;
}
.middle-content {
	margin-right: 0em;
	float:none;
}
.middle {
	padding: 1em 0.5em 0.5em;
	width: 88%;
	margin:0 auto 1em;
}
a.get {
	font-size: 0.9em;
	padding: 0.7em 1em;
}
.content-middle {
	min-height: 189px;
}
.top-grid:nth-child(3){
	display:none;
}
.top-grid {
	width: 100%;
}
.pro-grid b ,.pro-btns{
	display: none;
}
p.best {
	font-size: 0.7em;
	padding:0.5em;
}
p.number {
	font-size: 0.65em;
	left: 3%;
	padding: 0.5em;
}
p.tun {
	font-size: 0.6em;
	padding: 1.3em 0 1.3em 7em;
}
p.tun span{
	display:none;
}
.pro-grid p {
	font-size: 0.8em;
}
.grid-top {
	width: 100%;
}
.add p {
	font-size: 0.8em;
}
.footer p {
	font-size: 1em;
}
.content-bottom {
	padding-bottom: 5em;
}
.top-nav ul {
	margin: 2em 0;
}
.bottom-product {
	padding-bottom: 1em;
}
ul.start {
	padding: 1em 0 4.5em;
}
.footer {
	padding: 10em 0 3em;
}
.four h1 {
	font-size: 5em;
}
.four p {
	font-size: 0.9em;
}
a.details {
	font-size: 1em;
}
.four {
	padding: 4em 0em 5em;
	min-height: 322px;
}
.single {
	padding: 3em 0 5em;
}
.desc p {
	font-size: 1em;
	height: 60px;
	overflow: hidden;
}
.facts p {
	font-size: 1em;
	line-height: 1.5em;
	height: 64px;
}
.facts ul li {
	font-size: 1em;
}
.block-subtitle {
	font-size: 1.3em;
}
.contact-form {
	padding: 2.5em 0 5em;
}
.contact-grid ,.contact-in{
	padding: 0;
}
.contact-in h4, .contact-form h4 {
	font-size: 1.3em;
}
p.your-para {
	font-size: 1.1em;
}
.contact-grid input[type="text"], .contact-grid textarea {
	padding: 0.7em;
	margin: 0.5em 0;
}
.send input[type="submit"] {
	width: 25%;
}
.map iframe {
	min-height: 110px;
}
.contact-in p {
	font-size: 1em;
}
}
