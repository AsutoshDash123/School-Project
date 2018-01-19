<html>
<head>
<title>DAV Birgunj</title>
<style>
#left{
	display: inline-block;
}
.hello{
	float: right;
	margin-right: 15%;
	margin-top: 6%;
}
h2{
	color: red;
}
h3{
	color: green;
}
.search{
	text-align: right;
}
#textstyle{
 height: 35px;
	border-radius: 8px; 
	text-align: center;
}
#bottonstyle{
background-color: red;
color: white;
	padding: 7px;
	border-radius: 8px;
	width: 90px;
border: 1px solid red;
}
#bottonstyle:hover{
border: 3px dotted white;
}
.menu{
	background-color: blue;
	height: 40px;

}
.aa ul li{
	background-color: blue;
	width: 185px;
	display: inline-block;
	height: 35px;
	line-height: 35px;
	text-align: center;
	border-right: 1px solid #bbb;
}
.aa ul li a{
	color: white;
	text-decoration: none;
	display: block;
}
li a.active {
	background-color: red;
	color: white;
	height: 40px;
}
@keyframes bounce{
	0%, 20%, 60%, 100% {
		-webkit-transform: translateY(0);
		transform: translateY(0);
	}
	40%{
        -webkit-transform: translateY(-20px);
        transform: translateY(-20px);
	}
	80%{
		-webkit-transform: translateY(-10px);
		transform: translateY(-10px);
	}
}
.aa ul li a:hover:not(.active) {
    background-color: red;
	color: white;
	height: 40px;
	animation: bounce 1s;

}
#kkk{
	height: 5px;
}
#slideshow{
height: 320px;
width: 100%;
}
.mySlides {display:none;}
img:hover{
border-radius: 100% 100%;
}
.writtingsection{
	background-color: lightgrey;
	width: 1000px;
    height: 2250px;
    margin: auto;
}
hr{
	width: 100%;
}
.footer{
	background-color: e9edf2;
	color: black;
	width: 100%;
}
.happy{
	text-align: center;
	margin: auto;
}

</style>
</head>
<body>
<header>
	<div class="h3m">
	<div id="dav logo">
		<div id="left">
		<img src="img\logo2.jpg">
	</div><DIV class="hello">
	<marquee><h1>D.A.V R.B KEDIA HIGHER SECONDARY SCHOOL</h1></marquee>

</DIV>
</div>
<div class="search">
<form>
<input id="textstyle" type="text" name="textbox"placeholder="search...">
<input id="bottonstyle" type="button"name="search"value="Search"/>
</form>
</div>
</div>
</header>
<div class="menu">
	<div class="aa">
<ul>
		<li><a href="index.html">HOME</a></li>
				<li><a href="activities.html">ACTIVITIES</a></li>
				<li><a class="active"href="teachers.html">TEACHER</a></li>
				<li><a href="examtype.html">EXAM TYPE</a></li>
				<li><a href="contact us.html">CONTACT US</a></li>
				<li><a href="feedback.html">FEEDBACK</a></li>
</ul>
</div>
</div>
<div id="slideshow">
		<div id="kkk"></div>
  <script type="text/javascript" src="js/jssor.slider.min.js"></script>
    <!-- use jssor.slider.debug.js instead for debug -->
    <script>
        jssor_1_slider_init = function() {
            
            var jssor_1_options = {
              $AutoPlay: true,
              $ArrowNavigatorOptions: {
                $Class: $JssorArrowNavigator$
              },
              $ThumbnailNavigatorOptions: {
                $Class: $JssorThumbnailNavigator$,
                $Cols: 4,
                $SpacingX: 4,
                $SpacingY: 4,
                $Orientation: 2,
                $Align: 0
              }
            };
            
            var jssor_1_slider = new $JssorSlider$("jssor_1", jssor_1_options);
            
            //responsive code begin
            //you can remove responsive code if you don't want the slider scales while window resizing
            function ScaleSlider() {
                var refSize = jssor_1_slider.$Elmt.parentNode.clientWidth;
                if (refSize) {
                    refSize = Math.min(refSize, 810);
                    jssor_1_slider.$ScaleWidth(refSize);
                }
                else {
                    window.setTimeout(ScaleSlider, 30);
                }
            }
            ScaleSlider();
            $Jssor$.$AddEvent(window, "load", ScaleSlider);
            $Jssor$.$AddEvent(window, "resize", $Jssor$.$WindowResizeFilter(window, ScaleSlider));
            $Jssor$.$AddEvent(window, "orientationchange", ScaleSlider);
            //responsive code end
        };
    </script>

    <style>
        
        /* jssor slider arrow navigator skin 02 css */
        /*
        .jssora02l                  (normal)
        .jssora02r                  (normal)
        .jssora02l:hover            (normal mouseover)
        .jssora02r:hover            (normal mouseover)
        .jssora02l.jssora02ldn      (mousedown)
        .jssora02r.jssora02rdn      (mousedown)
        */
        .jssora02l, .jssora02r {
            display: block;
            position: absolute;
            /* size of arrow element */
            width: 55px;
            height: 55px;
            cursor: pointer;
            background: url('img/a02.png') no-repeat;
            overflow: hidden;
        }
        .jssora02l { background-position: -3px -33px; }
        .jssora02r { background-position: -63px -33px; }
        .jssora02l:hover { background-position: -123px -33px; }
        .jssora02r:hover { background-position: -183px -33px; }
        .jssora02l.jssora02ldn { background-position: -3px -33px; }
        .jssora02r.jssora02rdn { background-position: -63px -33px; }
/* jssor slider thumbnail navigator skin 11 css *//*.jssort11 .p            (normal).jssort11 .p:hover      (normal mouseover).jssort11 .pav          (active).jssort11 .pav:hover    (active mouseover).jssort11 .pdn          (mousedown)*/.jssort11 .p {    position: absolute;    top: 0;    left: 0;    width: 200px;    height: 69px;    background: #181818;}.jssort11 .tp {    position: absolute;    top: 0;    left: 0;    width: 100%;    height: 100%;    border: none;}.jssort11 .i, .jssort11 .pav:hover .i {    position: absolute;    top: 3px;    left: 3px;    width: 60px;    height: 30px;    border: white 1px dashed;}* html .jssort11 .i {    width /**/: 62px;    height /**/: 32px;}.jssort11 .pav .i {    border: white 1px solid;}.jssort11 .t, .jssort11 .pav:hover .t {    position: absolute;    top: 3px;    left: 68px;    width: 129px;    height: 32px;    line-height: 32px;    text-align: center;    color: #fc9835;    font-size: 13px;    font-weight: 700;}.jssort11 .pav .t, .jssort11 .p:hover .t {    color: #fff;}.jssort11 .c, .jssort11 .pav:hover .c {    position: absolute;    top: 38px;    left: 3px;    width: 197px;    height: 31px;    line-height: 31px;    color: #fff;    font-size: 11px;    font-weight: 400;    overflow: hidden;}.jssort11 .pav .c, .jssort11 .p:hover .c {    color: #fc9835;}.jssort11 .t, .jssort11 .c {    transition: color 2s;    -moz-transition: color 2s;    -webkit-transition: color 2s;    -o-transition: color 2s;}.jssort11 .p:hover .t, .jssort11 .pav:hover .t, .jssort11 .p:hover .c, .jssort11 .pav:hover .c {    transition: none;    -moz-transition: none;    -webkit-transition: none;    -o-transition: none;}.jssort11 .p:hover, .jssort11 .pav:hover {    background: #333;}.jssort11 .pav, .jssort11 .p.pdn {    background: #462300;}
        
    </style>


    <div id="jssor_1" style="position: relative; margin: 0 auto; top: 0px; left: 0px; width: 810px; height: 300px; overflow: hidden; visibility: hidden; background-color: #000000;">
        <!-- Loading Screen -->
        <div data-u="loading" style="position: absolute; top: 0px; left: 0px;">
            <div style="filter: alpha(opacity=70); opacity: 0.7; position: absolute; display: block; top: 0px; left: 0px; width: 100%; height: 100%;"></div>
            <div style="position:absolute;display:block;background:url('img/loading.gif') no-repeat center center;top:0px;left:0px;width:100%;height:100%;"></div>
        </div>
        <div data-u="slides" style="cursor: default; position: relative; top: 0px; left: 0px; width: 600px; height: 300px; overflow: hidden;">
            <div data-p="112.50" style="display: none;">
                <img data-u="image" src="img/177965admission.jpg" />
                <div data-u="thumb">
                    <img class="i" src="img/177965admission.jpg" />
                     <div class="t">Adamission</div>
                    <div class="c">Adamission banner</div>
                </div>
            </div>
            <div data-p="112.50" style="display: none;">
                <img data-u="image" src="img/108850meraton.jpg" />
                <div data-u="thumb">
                    <img class="i" src="img/108850meraton.jpg" />
                    <div class="t">Sports</div>
                    <div class="c">Sports curriculum</div>
                </div>
            </div>
            <div data-p="112.50" style="display: none;">
                <img data-u="image" src="img/248526comp.jpg" />
                <div data-u="thumb">
                    <img class="i" src="img/248526comp.jpg" />
                    <div class="t">Computer lab</div>
                    <div class="c">practicle education</div>
                </div>
            </div>
            <div data-p="112.50" style="display: none;">
                <img data-u="image" src="img/15317sankar.jpg" />
                <div data-u="thumb">
                    <img class="i" src="img/15317sankar.jpg" />
                    <div class="t">Honerable chairman</div>
                    <div class="c">Honerable chairman(Lt Sankarlal Kedia)</div>
                </div>
            </div>
            <div data-p="112.50" style="display: none;">
                <img data-u="image" src="img/248521lib.jpg" />
                <div data-u="thumb">
                    <img class="i" src="img/248521lib.jpg" />
                    <div class="t">library</div>
                    <div class="c">Students reading book</div>
                </div>
            </div>
            <div data-p="112.50" style="display: none;">
                <img data-u="image" src="img/10930class 10.jpg" />
                <div data-u="thumb">
                    <img class="i" src="img/10930class 10.jpg" />
                    <div class="t">Students</div>
                    <div class="c">Students of D.A.V School</div>
                </div>
            </div>
            <div data-p="112.50" style="display: none;">
                <img data-u="image" src="img/award.jpg" />
                <div data-u="thumb">
                    <img class="i" src="img/award.jpg" />
                    <div class="t">Honerable Principal</div>
                    <div class="c">Our Honerable Principal(Mr p.chatterji)</div>
                </div>
            </div>                            
        </div>
       
        <!-- Thumbnail Navigator -->
        <div data-u="thumbnavigator" class="jssort11" style="position:absolute;right:5px;top:0px;font-family:Arial, Helvetica, sans-serif;-moz-user-select:none;-webkit-user-select:none;-ms-user-select:none;user-select:none;width:200px;height:300px;" data-autocenter="2">
            <!-- Thumbnail Item Skin Begin -->
            <div data-u="slides" style="cursor: default;">
                <div data-u="prototype" class="p">
                    <div data-u="thumbnailtemplate" class="tp"></div>
                </div>
            </div>
            <!-- Thumbnail Item Skin End -->
        </div>
        <!-- Arrow Navigator -->
        <span data-u="arrowleft" class="jssora02l" style="top:0px;left:8px;width:55px;height:55px;" data-autocenter="2"></span>
        <span data-u="arrowright" class="jssora02r" style="top:0px;right:218px;width:55px;height:55px;" data-autocenter="2"></span>
        <a href="http://www.jssor.com" style="display:none">Bootstrap Carousel</a>
    </div>
    <script>
        jssor_1_slider_init();
    </script>
</div>
    <!-- #endregion Jssor Slider End -->
<div class="writtingsection">
	<center><img src="img\Tea.jpg"></center>
<center><h1>OUR TEACHING WAY</h1></center>
<center><h2>Learning Medium And Methodology</h2></center>
<center><h4>The School believes that every child possesses unique characteristics and temperament.thus the teaching and learning remain the core activities,with the student ass the focus.The school has memorised these mantras:<br><b><h3>|I hear,I know. || I see,I remember. || I do,I understand.|</h3></b><br> learning by doing is a best method that the school follows. DAV schooling emphasises always on applied education. The school is committed to enhancing learners' activities and exposure for global competence and recognition. It applies participatory,student centered teaching-learning activities at all levels</h4></center>
<center><h1>TEACHING FACULTY </h1></center>
<h4>The school is proud of having highly motivated,dedicated,experienced,and trained teaching staffs.Each individual teacheris confident expert in his/her subject matter.They have possessed  the willingness  to go deep into the thought and sprint to impart quality education for the development and betterment of each individual student.</h4>
<CENTER><h1>OUR TEACHER FACULTY </h1></CENTER>
<div class="suu"><h2>Pre-Primary Section</h2></div>
<ul><b>
	<li>MRS.Kakali Ghosh</li>
	<li>MRS.Joyti Singh</li>
	<li>MRS.Joyti  Ghimire</li>
	<li>MRS.Niva Karn</li>
	<li>MRS.Laxmi Sriwastava</li>
	<li>MRS.Sangeeta Sherestha</li>
	
</b>
</ul>

<center><h2>Secondary Section</h2></center><center><h3>Department of English</h3></center>
<ul><b>
	 <li>MRS. S.Sherpa</li>
	 <li> MR. Deepak</li>
     <li>MR. P.Pandy</li>
	 <li>MRS. S.Dey</li>
	 <li>MR.Ramayan Chaurasia</li>
</b></ul>
<center><h3>Department of Nepali</h3></center>
<ul><b>
	  <li>MRS. Nirmala</li>
	  <li>MRS. Radha</li>
</b></ul>	  
<center><h3>Department of Hindi/Sanskrit</h3></center>
<ul><b>
	  <li>MRS. Madhaukant Pathak</li>
	  <li>MRS. vijaya tripathi</li>
</b></ul>
<center><h3>Department of Science</h3></center>
<ul><b>
	<li>MR. P.Chatterje</li>
	<li>MRS. Megha</li>
    <li>MR. Akbar Hussan</li>
    <li>***********************</li>
    <li>MR. Barun</li>
</b></ul>
<center><h3>Department of Maths</h3></center>
<ul><b>
	<li>MR. Sudhir Singh</li>
	<li>MR. Munna Shah</li>
    <li>MR. chandresawar</li>
</b></ul>
<center><h3>Department of SST</h3></center>
<ul><b>
    <li>MRS. B.Mandal</li>
    <li>MRS. Mausumi Datta</li>
</b></ul>
<center><h3>Department of Computer</h3></center>
<ul><B>
	<li>MRS. Neeta</li>
    <li>MRS. kemika Singh</li>
    <li>MR. Roshan Shah</li>
</B></ul>
<center><h3>Department of Commers</h3></center>
<ul><b>
	 <li>MR. Pawan Shah</li>
	 <li>MR. Mukesh</li>
	 <li>MR. Sarfosh</li>
</b></ul>
<center><h3>Department of Sports</h3></center>
<ul><b>
	  <li>MR. Sakhil</li>
      <li>MR. Naresh</li>
</b></ul>
<center><h3>Department of Dance and Music</h3></center>
<ul><b>
	  <li>MRS. Priyanka</li>
	  <li>MR. Prakash</li>
	  <li>MR. kiran</li>
</b></ul>


</div>
<hr>
<footer>
<div class="footer">
	<div class="happy">
		The DAV School,2017.All rights reserved.<br>
		| Disclamer| Privacy policy | Sitemap | Vacancy at DAV<br>
		The DAV School website has been designed by<br>
		<b>Aayush Singh,Asutosh Dash,Raj Pachauri and Aditya Singh</b><br>
		of standerd-8(2017/2018) <br><b>Special Thanks To,</b><br>
		<b>Mrs kemika singh</b>(computer teacher)/<b>Mr Roshan shah</b>(computer teacher)/<b>Mr P.chatterji</b>(Principal)<br><br>
		The DAV School,Parwanipur(Near kedia hospital),Birgunj,Parsa,Nepal,Pin-******<br>
		Direct Number- +977-51-690107/525500,Email:######,<br>
		

</div>
</div>



</footer>
</body>
</html>
                              
