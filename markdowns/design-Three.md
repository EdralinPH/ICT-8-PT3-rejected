```css

/* in this one im just gonna show you another idea in web design */
/* in this part im gonna be using division or <div></div> tags with id's and classes */
/* and gonna be introducing you to :hover function in CSS, using transition:ease-in-out {time}s */
/* ease, ease-in, in-out, out, ease-in-out then {time}s */
/* for exammple transition:ease-in-out 1s; */
/* can be image or animated, but i havnt learn how to animate in a website yet. plus i read that you need to use javascript in order to create something like it which is hard. because its framework */


.cloud, .cloud2, .cloud3{ /* can be edited at once, but cannot be edited again as a new one. */
	background-color: lightBlue;
	border-radius: 25px; /* value is optional */
	border: white solid 1px; /* value is optional here too */
	box-shadow: 0px 10px 10px 0px darkBlue; /* value is optional here too */
	height: 100%; /* value is optional can be px em om ex */
	width: 100%; /* same here and the rest not sure about the "ex, om"*/
}

#sky{
	background-color: rgb(200, 200, 255);
	width: 100%;
	height: 100%;
	transition: ease-in-out 1s;
	
}

#sky:hover{
	background-color: rgb(50, 50, 100);
	
}

```