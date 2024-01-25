```css 

html{
	scroll-behavior:smooth;
}

body{
	background:lightBlue;
	color:black;
	font-family: monosans;
	width:100%;
	height:100%;
}

/* you can change the color of you want. */
div{
	background:linear-gradient(black, grey);
	color:white;
	/* you can customized things below. */
	padding:25px;
	border-radius:25px;
	border:white solid 1px;
}

/* legend is like a title in html too. but outputted into your website. */
legend{
	color:peach;
	font-size:35px;
	paadding:10px;
	background:rgba(50,50,50,0.5);
}

/* you can also customized this headers down here. */
/* spamming llinear gradient on this one */
/* in which you can customized every header and background with this CSS beautiful function */
/* in each header i will show an example of how linear-gradient() & radial-gradient() works. */
/* background:linear-gradient({color}, {color}) */
/* background:radial-gradient({color}, {color}) */
/* background:linear-gradient(to {position} {position}, {color}, {color}) */
/* background:radial-gradient(to {position} {position}, {color}, {color}) */
/* color can be repeated and can be any other colors */

h1{
	background:linear-gradient();
	color:transparent;
	background-clip: text;
}

h2{
	background: radial-gradient(white, black);
}

h3{
	background:radial-gradient(to bottom right, white, black);
}

h4{
	background:linear-gradient(white, black);
}

h5{
	background:linear-gradient(to top left, white black);
}

```