<----README.md---->
*/
@import "//netdna.bootstrapcdn.com/font-awesome/3.0/css/font-awesome.css";
body{
    font-family:Verdana;
}
 
#tabela{
    width:100%;
    text-align:center;
    border-radius: 15px;
    }
 
#tabela tbody tr{
    border-radius: 15px;
    color:#000000;
    height:30px;
    cursor:pointer;
    display: none;
}
 
#tabela thead th:nth-child(1){
    width:100px;
    border-radius: 15px;
    color:#fff;
    }
#tabela input{
    color:#d11507;
    text-decoration: none;
    background: #ededed;
    width:99%;
    outline:#c3c3c3;
    margin-left:0;
    height: 36px;
    border-radius: 15px;
    border:1px solid #c3c3c3;
}
awesome/3.0/css/font-awesome.css";

.mainLoginInput{
  height: 40px;
  padding: 0px;
  font-size: 30px;
  margin: 5px 0;
}

.mainLoginInput::-webkit-input-placeholder { 
font-family: FontAwesome;
font-weight: normal;
overflow: visible;
vertical-align: top;
display: inline-block !important;
padding-left: 5px;
padding-top: 2px;
color: #000000;
}

.mainLoginInput::-moz-placeholder  { 
font-family: FontAwesome;
font-weight: normal;
overflow: visible;
vertical-align: top;
display: inline-block !important;
padding-left: 5px;
padding-top: 2px;
color: #000000;
}

.mainLoginInput:-ms-input-placeholder  { 
font-family: FontAwesome;
font-weight: normal;
overflow: visible;
vertical-align: top;
display: inline-block !important;
padding-left: 5px;
padding-top: 2px;
color: #000000;
}


/* Dropdown Button */
.dropbtn {
  background-color: #fff;
  color: black;
  width: 39px;
  padding: 10px;
  font-size: 16px;
  border: none;
  border-radius: 50%;
  cursor: pointer;
}

/* Dropdown button on hover & focus */
.dropbtn:hover, .dropbtn:focus {
  background-color: #ddd;
  outline: none;
}


/* The container <div> - needed to position the dropdown content */
.dropdown {
  position: relative;
  display: inline-block;
}
/* Dropdown Content (Hidden by Default) */
.dropdown-content {
  display: none;
  position: absolute;
  margin-left:-245px;
  margin-top:-40px;
  background-color: #f6f6f6;
  min-width: 230px;
  border-radius: 15px;
  border: 1px solid #ddd;
  z-index: 1;
}

/* Links inside the dropdown */
.dropdown-content a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
}

/* Change color of dropdown links on hover */
.dropdown-content a:hover {background-color: #f1f1f1}

/* Show the dropdown menu (use JS to add this class to the .dropdown-content container when the user clicks on the dropdown button) */
.show {display:block;}

head{
margin-top:-60px;}
div.scrollmenu {
  height:55px;
  background-color: #363636;
  border: none;
  margin-top:116px;
  border-radius: 0px;
  overflow: auto;
  white-space: nowrap;
}

div.scrollmenu a {
  display: inline-block;
  color: #d11507;
  text-align: center;
  padding: 19px;
  border: none;
  width:50px;
  border-radius: 15px;
  text-decoration: none;
}

div.scrollmenu a:hover {
  background-color: #777;
  border: none;
  border-radius: 15px;}

body{
    margin:0px;
    padding: 0px;
    font-family: poppins;
    background-color: rgba(151,151,151,0.03);
}
*{
    box-sizing: border-box;
}
ul{
    list-style: none;
}
a{
    text-decoration: none;
}
nav{
    display: flex;
    justify-content: space-around;
    align-items: center;
    width:100%;
    heigth: 85%;
    border-bottom:7px solid #363636;
    background: #d11507;
    position: absolute;
    left: 0;
    top: 0;
    z-index: 100;
}
.logo img{
    height: 30px;
    margin-top:-2px;
    margin-left: 0px;
    border-radius: 15px;
}
.icon {
    margin-left: 10px;
}
nav .menu{
    display: flex;
}
nav .menu li a{
    height: 45px;
    line-height: 43px;
    margin: 0px;
    padding: 10px 2px;
    display: flex;
    font-size: 0.8rem;
    text-transform: uppercase;
    font-weight: 500;
    border-radius: 0px;
    background:#d11507;
    color:#fff;
    letter-spacing: 1px;
}
nav .menu li a:hover{
    background-color: #242424;
    color:#ffffff;
    box-shadow: 5px 10px 30px rgba(53,53,53,0.1);
    transition: all ease 0.2s;
}
#main{
    padding-top: 80px;
    background-color: #ffffff;
}
.cs-hidden{
    overflow: visible !important;
}
nav .menu-btn{
    display: none;
}
@media(max-width:1100px){
    nav{
        justify-content: space-between;
        height: 115px;
        padding: 0px 10px;
    }
 nav .menu{
       display: none;
        position: absolute;
        top: 82px;
        left: 0px;
        border-radius: 17px;
        background: #d11507;
        border-bottom:0px solid #242424;
        width:100%;
        height:346px;
        padding:0px;
        margin:0px;
    }
    .menu li{
        width:100%;
    }
    nav .menu li a{
        width: 100%;
        height: 30px;
        align-items: center;
        margin: 0px;
        padding:15px;
        border:1px solid rgba(38,38,38,0.03);
    }
 nav .menu-icon{
        cursor: pointer;
        float: right;
        padding:18px 10px;
        border-radius: 50%;
        position: relative;
        user-select: none;
        margin-top:6px;
        display: block;
    }
    nav .menu-icon .nav-icon{
        background-color: #000000;
        display: block;
        height: 2px;
        position: relative;
        transition: background 0.2s ease-out;
        width: 18px;
    }
    nav .menu-icon .nav-icon:before,
    nav .menu-icon .nav-icon:after{
        background: #000000;
        content: '';
        display: block;
        height: 100%;
        position: absolute;
        transition: all ease-out 0.2s;
        width: 100%;
    }
    nav .menu-icon .nav-icon:before{
        top:5px;
    }
    nav .menu-icon .nav-icon:after{
        top:-5px;
    }
    nav .menu-btn:checked ~ .menu-icon .nav-icon{
        background: transparent;
 
    }
    nav .menu-btn:checked ~ .menu-icon .nav-icon:before{
        transform: rotate(-45deg);
        top: 0;
    }
    nav .menu-btn:checked ~ .menu-icon .nav-icon:after{
        transform: rotate(45deg);
        top: 0;
    }
    nav .menu-btn{
        display: none;
    }
    nav .menu-btn:checked ~ .menu{
        display: block;
    }
    .logo img{
        height: 33px;
    }
}



/* Create three equal columns that floats next to each other */
.column {
  float: center;
  width: 100.00%;
  padding:1%;
  background: #363636;
  border-radius:10px;
  border:2px solid none;
}
.column2 {
  float: left;
  width: 45.00%;
  margin:2.50%;
  background: #363636;
  margin-top:17px;
  border-radius:10px;
  border:2px solid none;
  color:#fff;
}
.column5 {
  float: left;
  width: 100.00%;
  margin-top:17px;
  background: #none;
  border-radius:10px;
  border:2px solid none;
}

/* width */
::-webkit-scrollbar {
  width: 10px;
  display: none;
}

/* Track */
::-webkit-scrollbar-track {
  background: #f1f1f1;
  display: none;
}

/* Handle */
::-webkit-scrollbar-thumb {
  background: #888;
  margin-top: 5px;
}

/* Handle on hover */
::-webkit-scrollbar-thumb:hover {
  background: #555;
}

img {vertical-align: middle;
         border-radius: 10px;
 }
.coluna{
  float: center;
  display: inline-block;
  margin:0px;
  margin-top:15px;
  height: 233px;
  width: 142px;
  font-size: 15px;
  background: #d11507;
  border:2px solid #d11507;
  border-radius: 10px;
  color:#fff;
  text-align: center;
	-moz-transition: all 0.3s;
	-webkit-transition: all 0.3s;
	transition: all 0.3s;
}

.coluna:hover  {
	-moz-transform: scale(1.1);
	-webkit-transform: scale(1.1);
	transform: scale(1.1);
        background: #a51b0b;
        border: 2px solid #a51b0b;
}
/* Clear floats after the columns */
.row:after {
  content: ("");
  display: table;
  clear: both;
}
img {vertical-align: middle;
         border-radius: 10px;
 }
/* Responsive layout - makes the three columns stack on top of each other instead of next to each other on smaller screens (600px wide or less) */
@media screen and (max-width: 600px) {
  .column {
    width: 95.50%;
    background: #363636;
    border-radius:10px;
    padding:1px;
    margin-left:2%;
}
  .column2 {
    width: 95%;
    margin-top:17px;
    border-radius: 10px;
    border:none;
  }
.column5{
width: 100%;
    background: none;
    border-radius:10px;
    padding:1px;
}
.column2 h2 img{
width:100%;
height:100%;
}
}



* {
  box-sizing: inherit;
}

.pn-ProductNav_Wrapper {
  position: relative;
  padding: 0 0px;
  box-sizing: border-box;
  height:280px;
  margin-top:17px;
  background: #363636;
  border-radius:10px;
}

.pn-ProductNav {
    /* Make this scrollable when needed */
    overflow-x: auto;
    /* We don't want vertical scrolling */
    overflow-y: hidden;
    /* For WebKit implementations, provide inertia scrolling */
    -webkit-overflow-scrolling: touch;
    /* We don't want internal inline elements to wrap */
    white-space: nowrap;
    /* If JS present, let's hide the default scrollbar */
    .js & {
        /* Make an auto-hiding scroller for the 3 people using a IE */
        -ms-overflow-style: -ms-autohiding-scrollbar;
        /* Remove the default scrollbar for WebKit implementations */
        &::-webkit-scrollbar {
            display: none;
        }
    }
  /* positioning context for advancers */
  position: relative;
  // Crush the whitespace here
  font-size: 0;
}

.pn-ProductNav_Contents {
  float: left;
  transition: transform .2s ease-in-out;
  position: relative;
  height: 280px;
}

.pn-ProductNav_Contents-no-transition {
  transition: none;
}

.pn-Advancer {
  /* Reset the button */
  appearance: none;
  background: transparent;
  padding: 0;
  border: 0;
  &:focus {
    outline: 0;
  }
  &:hover {
    cursor: pointer;
  }
  /* Now style it as needed */
  position: absolute;
  top: 0;
  bottom: 0;
  /* Set the buttons invisible by default */
  opacity: 0;
  transition: opacity .3s;
}

.pn-Advancer_Left {
  left: 0;
  [data-overflowing="both"] ~ &,
  [data-overflowing="left"] ~ & {
    opacity: 1;
  }
}

.pn-Advancer_Right {
  right: 0;
  [data-overflowing="both"]  ~ &,
  [data-overflowing="right"] ~ & {
    opacity: 1;
  }
}

.pn-Advancer_Icon {
  width: 20px;
  height: 44px;
  fill: #bbb;
}

.pn-ProductNav_Indicator {
  position: absolute;
  bottom: 0;
  left: 0;
  height: 4px;
  width: 100px;
  background-color: transparent;
  transform-origin: 0 0;
  transition: transform .2s ease-in-out, background-color .2s ease-in-out;
}




* {
  box-sizing: border-box;
}

/* Create four equal columns that floats next to each other */
.movies-heading h2{
    font-weight: 400;
    margin: 0px;
    padding: 1px 20px;
    border-radius: 10px 10px 0 10px;
    text-shadow: 1px 1px rgba(0, 0, 0, 0.5);
    background-color: #d11507;
    color:#fff;
    border: none;
    font-arial: 15pt;
    letter-spacing: 1px;
    text-transform: uppercase;
    width: 100%;
    margin-top: 5px;
}
.movies-heading{
    display: flex;
    margin:0px 0%;
}
.column3 h1{
position:absolute;
width:60px;
margin-top:5px;
color: #fff;
font-size: 15px;
background: #088A68;
border-radius:7px;
}
.column3 h2{
position:absolute;
width:100px;
margin-top:-30px;
color: #fff;
font-size: 15px;
background: #088A68;
border-radius:7px;
}
.h1{
position:absolute;
width:60px;
margin-top:0px;
color: #fff;
font-size: 15px;
background: #088A68;
border-radius:7px;
}
.h3{
position:absolute;
width:100px;
margin-top:-50px;
color: #fff;
font-size: 15px;
background: #088A68;
border-radius:7px;
}
.column3 {
  float: left;
  width: 18%;
  padding: 0px;
  margin:1%;
  margin-left: 5%;
border:2px solid #d11507;
        border-radius: 10px 10px 10px 0;
        font-size: 15px;
        color:#fff;
        background: #d11507;
-moz-transition: all 0.3s;
	-webkit-transition: all 0.3s;
	transition: all 0.3s;
}
.column3:hover{
background: #a51b0b;
border:2px solid #a51b0b;
-moz-transform: scale(1.1);
	-webkit-transform: scale(1.1);
	transform: scale(1.1);
}
/* Clear floats after the columns */
.row2:after {
  content: "";
  display: table;
  clear: both;
}
/* On screens that are 600px wide or less, go from four columns to two columns */
@media screen and (max-width: 600px) {
  .column3 {
    width: 23%;
   padding: 0px;
   margin:1%;
  }
.column3:hover{
background: #a51b0b;
border:2px solid #a51b0b;
width:23%;
-moz-transform: scale(1.1);
	-webkit-transform: scale(1.1);
	transform: scale(1.1);
}
}

/* On screens that are 520px wide or less, make the columns stack on top of each other instead of next to each other */
@media screen and (max-width: 520px) {
  .column3 {width: 43%;
margin:8px;
padding: 0px;
margin-left:4%;
  }
.column3:hover{
background: #a51b0b;
border:2px solid #a51b0b;
width:43%;
-moz-transform: scale(1.1);
	-webkit-transform: scale(1.1);
	transform: scale(1.1);
}
}



/* ===== GOOGLE CUSTOM SEARCH ENGINE ===== */
.gsc-adBlock { display: none!important; }
.gsc-cursor-box {
   margin: 0 0 90px;
   border-top: 1px solid #eaeaea;
   border-bottom: 1px solid #eaeaea;
   padding: 12px 0;
}
.gsc-cursor {
   float: right;
   vertical-align: middle;
   margin: 0;
   padding-left: 0;
   border-radius: 4px;
   display: inline-block; 
} 
.gsc-cursor-box:after {
   content: "";
   display: block;
   clear: both; 
} 
.gsc-cursor-page {
   padding: 6px 13px;
   background-color: #fff;
   border: 1px solid #eaeaea;
   color: #222;
   transition: all 0.45s;
   text-decoration: none!important;
   margin-right: 0px!important; 
} 
.gsc-cursor-page:hover {
   z-index: 2;
   color: #23527c;
   background-color: #eee;
   border-color: #ddd; 
} 
.gsc-cursor-page.gsc-cursor-current-page {
   z-index: 3;
   color: #fff!important;
   cursor: default;
   background-color: #337ab7;
   border-color: #337ab7; 
}


header {
height: 0px;
visibility: hidden;
display: none;
}


footer{display: none;}
body{
  height: 0vh;
  background: #000115;
  cursor: none;
}


.circle-icons {

  padding: 10px; /* espa??amento */

  font-size: 18px; /* tamanho do icone */

  width: 39px; /* tamanho do fundo */

  text-align: center;
  
  text-decoration: none;

  margin: 5px 2px; /* espa??amento entre eles */

  border-radius: 50%;  

  background: #fff; /* cor do fundo */

  color: #000000; /*cor do icone */

}

.circle-icons2 {

  padding: 10px; /* espa??amento */

  font-size: 18px; /* tamanho do icone */

  width: 39px; /* tamanho do fundo */

  text-align: center;
  
  text-decoration: none;

  margin: 5px 2px; /* espa??amento entre eles */

  border-radius: 50%;  

  background: #088A68; /* cor do fundo */

  color: #fff; /*cor do icone */

}

.circle-icons:hover {

    background: #ccc; /*  cor de fundo com mouse encima */

    color: #fff;  /* cor do icone com mouse encima */

    opacity: 0.7;

}
h5{text-align: center; margin-top: 10px;}
{width: 100%; height:400px; margin-top: 0px; background: #d11507;}



footer{
  position: relative;
  display: none;
  bottom: 15%;
  height: 0px;
  width: 100%;
}
.bottom center{
  padding: 5px;
  font-size: 0.9375rem;
  height:120px;
  color:#fff;
  bottom: 0px;
  background: #d11507;
}


.wnd-free-stripe-text{
display: none;
}

.wnd-free-stripe-logo{
display:none;
bottom:70px;
}

*/!
