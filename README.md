theme: jekyll-theme-slate
title: Welcome to the home page of bug-free-memo!
description: Feel free to bookmark this to keep an eye on my project updates!
trying to understand how to upload my projects here
<body>
  <header class="header">
		<h1 class="logo"><a href="#">Logo</a></h1>
      <ul class="main-nav">
          <li><a href="#">Home</a></li>
          <li><a href="#">About</a></li>
          
          <li><a href="#">Portfolio</a></li>
          
            
          <li><a href="#">Contact</a></li>
      </ul>
    
      
	</header> 
 
  <section class="hero">
    <div class="parallax">
    <h1>Gorgeous Stylish Bags</h1>
    <h2
        >Look like a Super Model with this amazing collection of accessories</h2>
    <a href="#" class="btn">Enter</a>
    </div>
    
  </section>
  <section class= "collection">
    <h2>Some Of Our Collection</h2>
    <p>Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Loren Ipsum Loren Ipsum Lorem Ipsum</p>
    
    
      <div class="container">
        <div class="gallery">

		<div class="gallery-item">
			<img class="gallery-image" src="https://images.pexels.com/photos/1231059/pexels-photo-1231059.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" alt="lady carrying backpack">
		</div>

		<div class="gallery-item">
			<img class="gallery-image" src="https://images.pexels.com/photos/1921717/pexels-photo-1921717.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" alt="lady with a backpack">
		</div>

		<div class="gallery-item">
			<img class="gallery-image" src="https://images.pexels.com/photos/737532/pexels-photo-737532.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" alt="lady with a small backpack">
		</div>

		<div class="gallery-item">
			<img class="gallery-image" src="https://images.pexels.com/photos/1627820/pexels-photo-1627820.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" alt="woman holding a backpack">
		</div>

		<div class="gallery-item">
			<img class="gallery-image" src="https://images.pexels.com/photos/842956/pexels-photo-842956.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" alt="view of woman wearing a backpack">
		</div>

		<div class="gallery-item">
			<img class="gallery-image" src="https://images.pexels.com/photos/1046564/pexels-photo-1046564.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" alt="woman carrying a small rucksack">
		</div>

	</div>

</div>
  
  </section>
  <section class="features">
    <h3>Features and Services</h3>
    <p>Ipsum Loren Ipsum Loren Ipsum Loren Ipsum Loren Ipsum Loren Ipsum Loren Ipsum</p>
    <hr>
    <ul class="grid">
      <li>
        <i class="fa fa-cubes"></i>
        <h4>Wardrobe Styling</h4>
        <p>Ipsum Lorem Ipsum Loren Ipsum Loren Ipsum Loren Ipsum Loaren Ipsum Loren Ipsum</p>
        
      <li>
        <i class="fa fa-newspaper-o"></i>
        <h4>Fashion Styling</h4>
        <p>Ipsum Loren Ipsum Loren Ipsum Loren Ipsum Loren Ipsum Loren Ipsum Loren Ipsum</p>
      </li>
      
      <li>
        <i class="fa fa-newspaper-o"></i>
        <h4>Custom Designing</h4>
        <p>Ipsum Loren Ipsum Loren Ipsum Loren Ipsum Loren Ipsum Loren Ipsum Loren Ipsum</p>
      </li>
    </ul>  
   
  </section>
  
  <section class = "reviews">
    <h3 class="title">What Others Say</h3>
    
    <p class="quote">Ipsum Loren Ipsum Loren Imsum Loren Ipsum Loren Ipsum Loren Ipsum Ipsum Loren Ipsum Loren Ipsum Loren Ipsum Ipsul Loren Loren </p>      
    <p class="author">Maurice Kutler</p>
    
    
    <p class="quote">Ipsum Loren Ipsum Loren Imsum Loren Ipsum Loren Ipsum Loren Ipsum Ipsum Loren Ipsum Loren Ipsum Loren Ipsum Ipsul Loren Loren </p>      
    <p class="author">George Wallace</p>
    
    
    <p class="quote">Ipsum Loren Ipsum Loren Imsum Loren Ipsum Loren Ipsum Loren Ipsum Ipsum Loren Ipsum Loren Ipsum Loren Ipsum Ipsul Loren Loren </p>      
    <p class="author">Anna Muller</p>
    
  </section>
  
  <section class="contact">
    <h3>Join Our Fan Club</h3>
    <p>Loren Ipsum Loren Ipsum Loren Ipsum Loren Ipsum Loren Ipsum Loren Ipsum Loren</p>
    <hr>
    <form>
      <input type="email" placeholder="email">
      <a href="#" class="button">Subscribe Now</a> 
    </form>
  </section>
          

  <footer class="page-footer">
    <ul class="social-icons icons-flat list-unstyled  list-inline">
      <li><a href="#" target="_blank"><i class="fa fa-twitter-square"></i></a></li>
      <li><a href="#" target="_blank"><i class="fa fa-facebook-square"></i></a></li>
      <li><a href="#" target="_blank"><i class="fa fa-instagram-square"></i></a></li>
      <li><a href="#" target="_blank"><i class="fa fa-pinterest-square"></i></a></li>
      <li><a href="#" target="_blank"><i class="fa fa-github-square"></i></a></li>
        
      
    </ul>
        <p>Made by <a href="facebook.com/fashionblogger2009" target="_blank">Meera Menon</a>. Images courtesy to <a href="https.unsplash.com" target="_blank">Unsplash</a></p>
  </footer>
</body>

/*-------------
 	General
-------------*/

*{
	margin: 0;
	padding: 0;
	box-sizing: border-box;
}

body, html{
	font: normal 16px sans-serif;
	color: black;
  height: 100%;
}

ul, .nav{
	list-style: none;
  float: left;
}

a{
	text-decoration: none;
	color: inherit;
	cursor: pointer;

	opacity: 0.9;
}

a:hover{
	opacity: 1;
}

a.btn{
	color: black;
	border-radius: 4px;
	text-transform: uppercase;
	
	font-weight: 800;
	text-align: center;
}

hr{
	width: 150px;
	height: 2px;
	background-color: black;
	border: 0;
	margin-bottom: 80px;
}

section{
	display: flex;
	flex-direction: column;
	align-items: center;

	padding: 125px 100px;
}

@media (max-width: 1000px){

	section{
		padding: 100px 50px;
	}

}

@media (max-width: 600px){

	section{
		padding: 80px 30px;
	}

}

section h3.title{
	color: whitesmoke;
	text-transform: capitalize; 
	font: bold 32px 'Open Sans', sans-serif;
	margin-bottom: 35px;
	text-align: center;
}

section p{
	max-width: 800px;
	text-align: center;
	margin-bottom: 35px;
	padding: 0 20px;
	line-height: 2;
}

ul.grid{
	width: 100%;
	display: flex;
	flex-wrap: wrap;
	justify-content: center;
}


/*-------------
 	Header
-------------*/


* {
	box-sizing: border-box;
}
body {
	font-family: 'Montserrat', sans-serif;
	line-height: 1.6;
	margin: 0;
	min-height: 100vh;
}
ul {
  margin: 0;
  padding: 0;
  list-style: none;
}


h2,
h3,
a {
	color: whitesmoke;
}

a {
	text-decoration: none;
}



.logo {
	margin: 0;
	font-size: 1.45em;
}

.main-nav {
	margin-top: 5px;

}
.logo a,
.main-nav a {
	padding: 1px 15px;
  
	text-transform: uppercase;
	text-align: center;
	display: block;
  color: black;
}

.main-nav a {
	color: black;
	font-size: 20px;
  font-style: bold;
}

.main-nav a:hover {
	color: yellow;
}



.header {
	padding-top: .2em;
	padding-bottom: .1em;
	
	background-color: grey;
	-webkit-box-shadow: 0px 0px 14px 0px rgba(0,0,0,0.75);
	-moz-box-shadow: 0px 0px 14px 0px rgba(0,0,0,0.75);
	box-shadow: 0px 0px 14px 0px rgba(0,0,0,0.75);
	-webkit-border-radius: 5px;
	-moz-border-radius: 5px;
	border-radius: 5px;
}


/* ================================= 
  Media Queries
==================================== */




@media (min-width: 769px) {
	.header,
	.main-nav {
		display: flex;
	}
	.header {
		flex-direction: column;
		align-items: center;
    	.header{
		width: 80%;
		margin: 0 auto;
		max-width: 1000px;
	}
	}

}

@media (min-width: 1025px) {
	.header {
		flex-direction: row;
		justify-content: space-between;
	}

}
/*----------------
 	Hero Section
----------------*/
.hero{
  width: 100vw;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  background-image: linear-gradient(rgba(0, 0, 0, 0.5),rgba(0, 0, 0, 0.5)), url("https://images.pexels.com/photos/63778/pexels-photo-63778.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  background-attachment: fixed;
  height: 100%;
}

/*media query for background image
/* Turn off parallax scrolling for all tablets and phones. Increase/decrease the pixels if needed */
@media only screen and (max-device-width: 1366px) {
  .parallax {
    background-attachment: scroll;
  }
}




.hero h1{
  font-size: 5em;
	margin-top: 0;
	margin-bottom: 0.5em;
  color: whitesmoke;
}


.hero a{
  color: black;
}



.hero .btn{
  display: block;
  width: 140px;
  border: 3px solid white;
  padding: 0.1em;
  margin-top: 50px;
  margin-left: auto;
  margin-right: auto;
  color: white;
  text-decoration: none;
  font-size: 1.5em;
  border-radius: 20px;
  background-color: rgba(147, 112, 219, 0.8);

}

@media (max-width: 800px){

	.hero{
		min-height: 800px;
    color:whitesmoke;
	}

	.hero h1{
		font-size: 48px;
    color: whitesmoke
	}

	.hero h3{
		font-size: 24px;
    color: whitesmoke;
	}

	

}



/*--------------------
 	Our collection Section
---------------------*/

.gallery {
	display: flex;
	flex-wrap: wrap;
	/* Compensate for excess margin on outer gallery flex items */
	margin: -1rem -1rem;
}

.gallery-item {
	/* Minimum width of 24rem and grow to fit available space */
	flex: 1 0 24rem;
	/* Margin value should be half of grid-gap value as margins on flex items don't collapse */
	margin: 1rem;
	box-shadow: 0.3rem 0.4rem 0.4rem rgba(0, 0, 0, 0.4);
	overflow: hidden;
}

.gallery-image {
	display: block;
	width: 100%;
	height: 100%;
	object-fit: cover;
	transition: transform 400ms ease-out;
}

.gallery-image:hover {
	transform: scale(1.15);
}


ul{
  display: table-cell;
}
li{
  list-style: none;
}
.collection{
	background-color: lightseagreen;
  
}

.wrapper .collection{
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-column-gap: 2px;
  grid-column-gap: 2px;
  width: 70%;
  
}
.wrapper > div img{
  max-width: 100%;
}
.collection .grid li{
	padding: 20px;
	height: 350px;
	border-radius: 3px;

	background-clip: content-box;
	background-size: cover;
	background-position: center;
	background-color: blue;
}

.collection .grid li.small{
	flex-basis: 40%;
}

.collection .grid li.large{
	flex-basis: 60%;
}


@media (max-width: 1000px){

	.collection .grid li.small,
	.collection .grid li.large{
		flex-basis: 100%;
	}

}



/*----------------------
 	Features Section
----------------------*/

.features{
	background-color: lightgrey;
  
}

.features .grid li{
	padding: 0 30px;
	flex-basis: 33%;
	text-align: center;
}

.features .grid li i{
    font-size: 50px;
    color: black;
    margin-bottom: 25px;
}

.features .grid li h4{
	color: black;
    font-size: 20px;
    margin-bottom: 25px;
}

.features .grid li p{
    margin: 0;
}


@media (max-width: 1000px){

	.features .grid li{
		flex-basis: 70%;
		margin-bottom: 65px;
	}

	.features .grid li:last-child{
		margin-bottom: 0;
	}

}


@media (max-width: 600px){

	.features .grid li{
		flex-basis: 100%;
	}

}



/*--------------------
 	Reviews Section
--------------------*/

.reviews{
	background-color: lightslategray;
}

.reviews .quote{
	text-align: center;
	width: 80%;
    font-size: 22px;
    font-weight: 300;
    line-height: 1.5;
    margin-bottom: 20px;
    padding: 0;
}

.reviews .author{
    font-size: 18px;
    margin-bottom: 50px;
}

.reviews .author:last-child{
    margin-bottom: 0;
}

@media (max-width: 1000px){

	.reviews .quote{
		font-size: 20px;
	}

	.reviews .author{
	    font-size: 16px;
	}

}



/*---------------------
 	Contact Section
---------------------*/

.contact{
	background-color: grey;
}

.contact form{
	display: flex;
	align-items: center;
	justify-content: center;
	flex-wrap: wrap;

	max-width: 800px;
	width: 80%;
}

.contact form input{
	padding: 15px;
	flex: 1;
	margin-right: 30px;
	font-size: 18px;
	color: #555;
}

.contact form .btn{
	padding: 18px 42px;
}


@media (max-width: 800px){

	.contact form input{
		flex-basis: 100%;
		margin: 0 0 20px 0;
	}

}




/*-------------
 	Footer
-------------*/

footer{
	display: flex;
	flex-direction: column;
	align-items: center;
	text-align: center;
	color: #fff;
	background-color: black;
	padding: 20px 0;
}

footer ul{
	display: flex;
	margin-bottom: 25px;
	font-size: 32px;
}

footer ul li{
	margin: 0 8px;	
}

footer ul li:first-child{
	margin-left: 0;	
}

footer ul li:last-child{
	margin-right: 0;	
}

footer p{
	text-transform: uppercase;
	font-size: 14px;
	color: rgba(255,255,255,0.6);
	margin-bottom: 10px;
}

footer p a{
	color: #fff;
}

@media (max-width: 700px){

	footer{
		padding: 80px 15px;
	}

}

/* styling all font awesome icons*/
.social-icons .fa{
  font-size: 1.5em;
  width: 50px;
  text-align: center;
  text-decoration: none;
}

/*adding a hover effect to the icons*/
.fa:hover{
  opacity: 0.7;
}

/* Facebook*/
.fa-facebook{
  
  color: white;
  
}
           

<script type="text/javascript">
//scroll to top on page refresh (PART1)
window.onbeforeunload = function () {
  window.scrollTo(0, 0);
}
//for arrow click part (PART2)
$(document).ready( function () {
 $('#down').on('click',function () {
  $("html").scrollTop(0);
   $('html, body').animate({
     scrollTop: $(where-you-want-to-scroll).offset().top
 }, 1000);
 });
});
</script>
