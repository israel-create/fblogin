#<!document>
<html>
 <head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial=scale-1.0"/>
  <title>facebook login</title>
   <link rel="stylesheet" href="css/fontawesome.min.css">
  <style type="text/css">
 
 *{
 margin:0;
 padding:0;
 font-family:sanc-serif;
 background:
 width:100%;
 box-sizing:border-box;
 max-width:940px;
 }
 
 nav{
 width:100%;
 background-color:#0033cc;
 position:relative;
 top:0;
 left:0;
 overflow: hidden;
 }
 .create{
 box-sizing:border-box;
 background:#669900;
 width: 130px;
float: right;
margin-right:1px;
border:1px solid #0033cc;
 }
 .create:after{
 clear: right;}
 nav .create .p1{
 color:#fff;
 font-size:1em;
 margin:4px 0;
 }
nav #logo{
color:#fff;
font-size:21px;
padding:2px 2px;
display:inline-block;
 }

.lite{
width:100%;
background:#ffffcc;
border:1px solid #ffcc33;
}
 #lit{
  margin:10px 0;
  color:#0033cc;
  display:inline-block;
  }
#mobile{
font-size:30;
text-decoration:none;
}
/*nav area end*/
.form{
position:relative;
top:12px;
width:95%;
margin: 0 auto;}
form{
position:relative;
display: block;
border-bottom:1px solid grey;}
form .p2{
font-size:14;
font-weight: bold;
color:grey;}

input{
display: block;
width:100%;
height:2.3rem;
border:1px solid grey;
margin-bottom: 10px;}

form #submit{
background-color:#0033cc;
botder:2px solid #0033cc;
height:2.4rem;
border-radius:3px;
color:#fff;
font-size:1rem;
margin-bottom:15px;
}
.form .or{
position: absolute;
left:50%;
top:78%;
transform: translate(-50%);
text-align:center;
width:50px;
background:#fff;
font-size:14;
}
.form .new{
position: relative;
top:30px;
background-color:#669900;
color:#fff;
font-size:13;
text-align: center;
width:180px;
border-radius:1px;
margin:0 auto;
padding:13px;}

.form #a1{text-decoration:none;
color:#fff;}

#forget{
 text-decoration: none;
  display:block;
  position: relative;
  font-size:13;
  color:#3366cc;
  top:50px;
  left:10px;
  padding-top:7px;}



</style>
</head>
 <body>
 <nav>
<h1 id="logo">facebook</h1>
 <a href="#"><div class="create">
 <p class="p1">Create Account</p>
 </div></a>
 </nav>
 <!--nav area end -->
 
 <div class="lite">
 
<a href="#" > <!--<span id="mobile"> &#9667; </span>--> <p id="lit"> Get Facebook Lite and browse faster.</p></a>
 </div>
 
 <!--start form areas-->
 
 <div class="form">
  <form method="POST" action="#">
   <p class="p2"> Email address or phone number</p>
   <input type="text" name="text" required="required" /> 
   <p class="p2">Password</p>
   
   <input type="password" name="password" required="required"/>
   
   <input type="submit" name="submit" value="Log in"id="submit">
   </form>
   
   <div class="or">or</div>
   <div class="new"> <a href="#" id="a1">Create New Account </div></a></div> 
   
   <a href="#" id="forget" >Forgotten password?</a>
   <a href="#" id="forget" >Help Center</a>
   
   </div>
  
    
    
    
 </div>
 
 </body>
</html>
