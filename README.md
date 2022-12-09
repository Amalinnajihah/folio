<!DOCTYPE html>
<html>
<head>
	<title>Portfolio website</title>
	<link rel="stylesheet" type="text/css" href="css/test.css">

	<link rel="preconnect" href="https://fonts.gstatic.com">
  <link href="https://fonts.googleapis.com/css2?family=Josefin+Sans:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;1,100;1,200;1,300;1,400;1,500;1,600;1,700&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body>
    <div class="hero">

        <video autoplay loop muted plays-inline class="back-video">
<source src="img/video.mp4" type="video/mp4">

        </video>

        <nav>
            <img  class="logo">
            <ul>
                <li><a href="#content">HOME</a></li>
                <li><a href="#about">ABOUT ME</a></li>
                <li><a href="#tentangsaya">COURSE ACHIEVEMENT</a></li>
                <li><a href="#wrapper">SKILLS</a></li>
                <li><a href="#activities">ACTIVITIES</a></li>
                <li><a href="#program">BLOGS</a></li>
            </ul>
            <a section id="btn" class="btn">CLICK ME</a>
			<script>
				document.getElementById("btn").addEventListener("click", function(){
					alert("HELLO GUYS!");});
			</script>
        </nav>
        <div section id="content" class=" content">
        <h1>AMALINFOLIO</h1>
        <a onmouseover="mOver(this)" onmouseout="mOut(this)">Let's Go</a>

		<script>
			function mOver(obj){
				obj.innerHTML= "Let's Go"
			}
			function mOut(obj){
				obj.innerHTML= "Visit My Website"
			}
		</script>
        <h3><marquee behavior="scroll" direction="left">HELLO! Welcome to my website <3</marquee></h3>
        </div>
    </div>

    <section id="about" class="about">
		<div class="main">
			<img src="img/my.jpg">
			<div class="about-text">
				<h2>ABOUT <span>ME</span></h2>

				<p style = "color:rgb(23, 26, 23);"><i>My name is Nur Amalin Najihah.My matric numbers is 067981. I'm 21 years old, stayed at Tanah Merah,Kelantan. I am second year student, studies in Universiti Sultan Zainal Abidin at Besut,Terengganu. Proceeding with my studies in a bachelor's degree in informatics media.</i></p>
				<button href="#" type="button">Let's Talk</button>
			</div>
		</div>
	</section>

    <div id="tentangsaya" class="tentangsaya">
		<div class="title">
			<h2><marquee direction = "left">COURSE <span>ACHIEVE</span>MENT</marquee></h2>
		</div>

		<div class="box">
			<div class="card">
				<i class="fa fa-building"></i>
				<h5>SPM</h5>
				<div class="pra">
					<p style = "color:rgb(23, 26, 23);">  I'm a pure Science student during high school </p>
					<p style="text-align: center;">

					</p>
				</div>
			</div>

			<div class="card">
				<i class="fa fa-building"></i>
				<h5>STPM</h5>
				<div class="pra">
					<p style = "color:rgb(23, 26, 23);"> Course that I took for STPM is Social Science and I got 3.13 for CGPA in STPM.</p>

					<p style="text-align: center;">

					</p>
				</div>
			</div>

			<div class="card">
				<i class="fa fa-university"></i>
				<h5>Bachelor</h5>
				<div class="pra">
					<p style = "color:rgb(23, 26, 23);"> studying in informatic media for 3years and a half at UniSZA Campus Besut. Currently, as a second years student</p>

					<p style="text-align: center;">

					</p>
				</div>
			</div>
		</div>
	</div>

    <div section id="wrapper" class="wrapper">
		<div class="title2">
		  <h2> <marquee direction = "right">S<span>KILL</span>S</h2></marquee>
		</div>
			<div class="shape-1"></div>
			<div class="shape-2"></div>
			<div class="container">
				<div class="skills">
					<div class="details">
						<span1>COMMUNICATION</span1>
						<span1>80%</span1>
					</div>
					<div class="bar1">
						<div id="html-bar"></div>
					</div>
				</div>
				<div class="skills">
					<div class="details">
						<span2>TIME MANAGEMENT</span2>
						<span2>75%</span2>
					</div>
					<div class="bar2 ">
						<div id="css-bar"></div>
					</div>
				</div>
				<div class="skills">
					<div class="details">
						<span3>CREATIVITY</span3>
						<span3>70%</span3>
					</div>
					<div class="bar3">
						<div id="js-bar"></div>
					</div>
				</div>
				<div class="skills">
					<div class="details">
						<span4>MULTITASKING</span4>
						<span4>65%</span4>
					</div>
					<div class="bar4">
						<div id="jQuery-bar"></div>
					</div>
				</div>
			</div>
		</div>

<div class="headline"><h2><marquee direction = "left"><span>AC</span>TIVITI<span>ES</span></marquee></h2></div>
        <div section id="activities" class="activities">
			<div class="title3">
						<img src="img/colorun.jpg">
						<div class="layer"> </div>
						<h5 style = "color:rgb(23, 26, 23);">COLOR RUN</h5>
						<p style = "color:rgb(225, 250, 86);">"Have fun. Regret nothing and don't let people bring you down"</p>
						<div class="pra">
							<p style="text-align: center;">
							</p>

						</div>
					</div>
					<div class="title3">
						<img src="img/volleyball.jpg">
						<div class="layer"> </div>
						<h5 style = "color:rgb(23, 26, 23);">VOLLEYBALL</h5>
						<p style = "color:rgb(225, 250, 86);">"Champions believe in themselves, even when no one else does"</p>
						<div class="pra"></div>
							<p style="text-align: center;">
							</p>
					</div>
					<div class="title3">
						<img src="img/ceramah.jpg">
						<div class="layer"> </div>
						<h5 style = "color:rgb(23, 26, 23);">TALK</h5>
						<p style = "color:rgb(225, 250, 86);">"Remember the reason you are doing this is to make your life better"</p>
						<div class="pra"></div>
							<p style="text-align: center;">
							</p>
					</div>
				</div>


	<div class="headline1"> <h2><marquee direction = "right"><span>BLO</span>GS</marquee></h2></div>
        <div section id="program" class=" program">
            <div class="blog">
                <h2 style = "color:rgb(23, 26, 23);">PROBABILITY & STATISTICAL DATA ANALYSIS</h2>
                <div class="caption">
                    <p>After learning Probability & Statistical Data Analysis for almost 8weeks, I learned several types of statistical analysis tools that can help organization or anyone to analysis the data. Then it can help to come up a solution or answer from the data that is collected. I also can help myself to be more confident to answer this type of mathematical questions. Other than that, I love how the lecturer explain to me about several topic. Their explanations really make all the topics easy to understand for me.</p>
                    <button type="button">Know More</button>
                </div>
                <img src="img/math.jpg">
            </div>
            <div class="blog">
                <h2 style = "color:rgb(23, 26, 23);">WEB APPLICATION DEVELOPMENT</h2>
                <div class="caption">
                    <p>The process of learning coding in web application was enjoyable. Although sometimes it was difficult to understand the attributes such as in HTML, CSS, JAVASCRIPT and many others. However, I eventually accepted that coding may be fun when we understand how to use it.</p>
                    <button type="button">Know More</button>
                </div>
                <img src="img/cc.jpg">
            </div>
            <div class="blog">
                <h2 style = "color:rgb(23, 26, 23);">DATABASE</h2>
                <div class="caption">
                    <p>I was introduced to data modelling techniques and database analysis, recording, and understanding. Various of the valuable commercial database administration tools were also discussed, as well as some tools for easy and quick data visualisation and retrieval. Moreover, we learned how to analyze, access and employ data in an effective manner during the course.</p>
                    <button type="button">Know More</button>
                </div>
                <img src="img/donno.jpg">
            </div>
</div>








    </body>
    </html>
    
    
    
    *{
margin: 0;
padding: 0;
box-sizing: border-box;
font-family: 'Poppins', sans-serif;
}
body{
	background-color:#aec6cf;
}
.hero{
    width: 100%;
    height: 100vh;
    background-image: linear-gradient(rgba(12,3,51,0.3),rgba(12,3,51,0.3));
    position: relative;
    padding:  0 5%;
    display: flex;
    align-items: center;
    justify-content: center;
}
nav{
    width: 100%;
    position: absolute;
    top:0;
    left:0;
    padding: 20px 8px;
    display: flex;
    align-items: center;
    justify-content: space-between;
}
nav.logo{
    width:20px;
}
nav ul li{
    list-style: none;
    display: inline-block;
    margin-left: 40px;
}
nav ul li a{
    text-decoration: none;
    color:#ffff;
    font-size: 17px;
	text-transform: capitalize;
}
nav ul li a:hover{
        color: #000000;
        transition: .4s;
 }    
.btn{
	background-color:#557c80;
	color: white;
	text-decoration: none;
	border: 2px solid transparent;
	font-weight: bold;
	padding: 10px 25px;
	border-radius: 30px;
	transition: transform .4s; 
}
.btn:hover{
	transform: scale(1.2); 
}
#content{
    text-align: center;
}
.content h1{
    font-size: 160px;
    color: #ffff;
    font-weight: 600;
    transition: 0.5s;
}
.content h1:hover{
    -webkit-text-stroke: 2px #ffff;
    color: transparent;

}
.content a{
    text-decoration: none;
    display: inline-block;
    color:#ffff;
    font-size:20px;
    border: 2px solid #ffff;
    padding: 14px 50px;
    border-radius: 50px;
    margin-top:70px;
}
.content a:hover{
    transform: scale(1.2); 
}
h3{
	color: white;
	font-size: 25px;
	margin-bottom: 50px;
    padding: 14px 70px;
    border-radius: 50px;
    margin-top:20px;
}
.back-video{
    position:absolute;
    right: 0;
    bottom: 0;
    z-index:-1;
}
@media( min-aspect-ration: 16/9){
    .back video{
        width:100%;
        height:auto;
    }
}
@media( max-aspect-ration: 16/9){
    .back video{
        width:auto;
        height:100%;
    }
}
.about{
	width: 100%;
	padding: 100px 0px;
	background-color: #aec6cf  ;
}
.about img{
	height: auto;
	width: 430px;
}
.about-text{
	width: 550px;
	
}
.main{
	width: 1130px;
	max-width: 95%;
	margin: 0 auto;
	display: flex;
	align-items: center;
	justify-content: space-around;
}
.about-text h2{
	color: rgb(255, 255, 255);
	font-size: 75px;
	text-transform: capitalize;
	margin-bottom: 20px;
}
.about-text h5{
	color: white;
	letter-spacing: 2px;
	font-size: 22px;
	margin-bottom: 25px;
	text-transform: capitalize;
}
.about-text p{
	color: #fcfc;
	letter-spacing: 1px;
	line-height: 28px;
	font-size: 18px;
	margin-bottom: 45px;
}
span{
	color: #fcff2e;
}
button{
	background-color:#557c80;
	color: white;
	text-decoration: none;
	border: 2px solid transparent;
	font-weight: bold;
	padding: 13px 30px;
	border-radius: 30px;
	transition: .4s; 
}
button:hover{
	background-color: transparent;
	border: 2px solid #557c80;
	cursor: pointer;
}
#tentangsaya{
	background:#03033fe6  ;
	width: 100%;
	padding: 100px 0px;
}
.title h2{
	color: rgb(255, 255, 255);
	font-size: 75px;
	width: 1130px;
	margin: 30px auto;
	text-align: center;
}
span{
	color: #fcff2e;
}
.box{
	display: flex;
	justify-content: center;
	align-items: center;
	min-height: 400px;
}
.card{
	height: 365px;
	width: 335px;
	padding: 20px 35px;
	background:#bcb88a;
	border-radius: 20px;
	margin: 15px;
	position: relative;
	overflow: hidden;
	text-align: center;
	box-sizing: border-box;
	transition: 0.5s; 
}
.card i{
	font-size: 50px;
	display: block;
	text-align: center;
	margin: 25px 0px;
	color:#004242;

}
h5{
	color: white;
	font-size: 23px;
	margin-bottom: 15px;
}
.pra p{
	color: #fcfc;
	font-size: 16px;
	line-height: 27px;
	margin-bottom: 25px;
}
.card .button{
	background-color:#557c80;
	color: white;
	text-decoration: none;
	border: 2px solid transparent;
	font-weight: bold;
	padding: 9px 22px;
	border-radius: 30px;
	transition: .4s; 
}
.card .button:hover{
	background-color: transparent;
	border: 2px solid #557c80;
	cursor: pointer;
}
#wrapper{
	padding: 50px 200px 200px 150px;
	background-color:#aec6cf ;
  
  }
  .title2 h2{
	color: rgb(255, 255, 255);
	font-size: 75px;
	width: 1130px;
	margin: 30px auto;
	text-align: center;
  }
  span{
	color: #fcff2e;
}
  .span1{
	color: #000;
  }
  .skill{
	width: 100%;
	height: 500px;
	background: #000000;
	display: flex;
	align-items: center;
	flex-direction: column;
	justify-content: center;
	box-sizing: border-box;
  }
  .skill p{
	color: white;
	font-size: 50px;
	font-weight: bold;
	margin-bottom: 25px;
  }
  
  .skills:not(:last-child){
	  margin-bottom: 30px;
  }
  .details{
	  width: 100%;
	  display: flex;  
	  justify-content: space-between;
	  margin-bottom: 10px;
  }
  .bar{
	  position: relative;
   
	  border: 2px solid #8926df;
   
	  border-radius: 20px;
	
  }
  .bar div{
	  position: relative;
	  width: 0;
	  height: 9px;
	  border-radius: 10px;
	  background-color: #8926df;
	 
  }
  .bar1 {
	position: relative;
   
	  border: 2px solid #04938e;
   
	  border-radius: 20px;
  }
  .bar1 div {
	position: relative;
	  width: 0;
	  height: 9px;
	  border-radius: 10px;
	  background-color: #04938e;
  }
  .bar2 {
	position: relative;
   
	  border: 2px solid #4f4fd3;
   
	  border-radius: 20px;
  }
  .bar2 div {
	position: relative;
	  width: 0;
	  height: 9px;
	  border-radius: 10px;
	  background-color: #4f4fd3;
  }
  .bar3 {
	position: relative;
   
	  border: 2px solid #ec0043;
   
	  border-radius: 20px;
  }
  .bar3 div {
	position: relative;
	  width: 0;
	  height: 9px;
	  border-radius: 10px;
	  background-color: #ec0043;
  }
  .bar4 {
	position: relative;
   
	  border: 2px solid #f4ff2d;
   
	  border-radius: 20px;
  }
  .bar4 div {
	position: relative;
	  width: 0;
	  height: 9px;
	  border-radius: 10px;
	  background-color: #f4ff2d;
  }
  #html-bar{
	  animation: html-fill 2s forwards;
  }
  @keyframes html-fill{
	  100%{
		  width: 90%;
	  }
  }
  #css-bar{
	  animation: css-fill 2s forwards;
  }
  @keyframes css-fill{
	  100%{
		  width: 75%;
	  }
  }
  #js-bar{
	  animation: js-fill 2s forwards;
	
  }
  @keyframes js-fill {
	  100%{
		  width: 72%;
	  }
  }
  #jQuery-bar{
	  animation: jQuery-fill 2s forwards;
  }
  @keyframes jQuery-fill{
	  100%{
		  width: 58%;
	  }
  }
#activities{
	display: flex;
	justify-content: center;
	align-items: center;
	min-height: 400px;
	background-color: #03033fe6 ;

}
.headline h2{
	color: #FFFFFF;  
		width: 100%;
		padding-bottom: 40px;
		padding-top: 40px;
	margin:auto;
	font-size: 75px;
	text-align: center;
		background-color: #03033fe6 ;

}
span{
	color: #fcff2e;
}
.title3{
	height: 465px;
	width: 335px;
	padding: 20px 35px;
	background:#99c7cca7;
	border-radius: 20px;
	margin: 15px;
	position: relative;
	overflow: hidden;
	text-align: center;
	box-sizing: border-box;
	transition: 0.5s; 
	box-shadow: 0 0 20px rgb(20, 16, 16);
	flex-basis: 32%;
	border-radius: 10px;
	margin-bottom: 30px;
	position: relative;
	overflow: hidden;
}
.title3 img{
	width: 100%;
	border-radius: 10px;
}
.layer{
	background: transparent;
	height: 100%;
	width:100%;
	position: absolute;
	top:0;
	left: 0;
	transition: 0.5;
}
.layer:hover{
	background: #bcb88ac1 (252, 110, 110, 0.593);
}
.layer h5{
	width: 100%;
	font-weight: 500;
	color: #fff;
	font-size: 26px;
	bottom: 0;
	left:50%;
	transform: translateX(-50%);
	position: absolute;
	transition: 0.5s;
}
.layer: hover h5{
	bottom: 49%;
	opacity: 1;
}
.pra{
	color:#fef1f1;
	font-size: 23px;
	line-height: 27px;
	margin-bottom: 15px;
}

#program{
    width: 1000px;
    height: 400px;
    background:#aec6cf ;
    margin: 120px auto;
    display:flex;
   background-color:#aec6cf;
}
span{
	color: #fcff2e;
}
.blog{
    height:100%;
    flex:1;
    color:#ffff;
    box-sizing:border-box;
    padding: 25px;
   position:relative;
   transition: 0.6s;
   background-color:#aec6cf;
}
.blog:nth-child(1){
background: #2a5287;
}
.blog:nth-child(2){
    background:#848dd1;
}
.blog:nth-child(3){
    background: #6a6f94;
}
.headline1 h2{
	color: #FFFFFF;  
	margin: 30px auto;
	font-size: 75px;
	text-align: center;
	background-color:#aec6cf;


}
.caption{
    max-width:230px;
    font-size:12px;
    margin:28px 0;
    display:none;
}
.caption button{
    border: 1px solid #fff;
    background: transparent;
    outline: none;
    padding: 8px 18px;
    color:#fff;
    border-radius:30px;
    margin-top:20px;
    cursor: pointer;
    font-size:12px;
}
.blog img{
    width:200px;
    position: absolute;
    right:20%;
    bottom:10px;
    text-align: center;
    border-radius: 10px;
}
.blog:hover{
    flex-grow:2.5;
}
.blog:hover .caption{
display:block;
}
.col:hover h2{
    text-align:left;
}


 
