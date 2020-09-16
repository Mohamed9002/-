<!DOCTYPE html>

<html lang="en">

<head>

  <meta charset="UTF-8">

  <meta http-equiv="X-UA-Compatible" content="IE=Edge">

  <meta name="viewport" content="width=device-width, initial-scale=1">

  <title>HTML</title>

  

 <style>

   #article{

  

  background:#42445AEB;

  

}

#logo{

  width: 40px ;

  height: 30px ;

  transform: translate(0px,5px )

  

}

#ar{

  transform: translate(266px, -6px );

  

  border-radius: 4px 4px 4px 4px ;

  background: #42445A00;

  

  border-style: double;

  color:white ;

}

#en{

  

  transform: translate(130px,-6px );

  border-radius: 4px 4px 4px 4px ;

  background: #42445A00;

  border-style: double;

  color: white ;

}

#logo2{

  width: 100%;

  transform: translate(0px, 40px);

  

}

#p{

  background: #6DAA63D1;

  border-top: 55px ;

  

}

#hol{

  transform: translate(0px, 10px );

  background:#199AFF;

  margin: 0px ;

  

}

#hr1{

  transform: translateY(19px);

  

}

#hr2{

  

  transform: translateY(0px )

}

#academ{

 background:#32434F0D;

 

  transform: translateY(-16px)

  

}

#call{

  background: #1F59E5;

  border-radius: 10px 10px 10px 10px ;

  color: white ;

  width: 111px;

  height: 30px;

  border-style: none;

  

}

   

   

 </style> 

</head>

<body>

  

  <article id="article">

    

    

     <img src ="Final.png" alt="logo" id="logo" />

 

  <button id="ar" dir="rtl">Arabic</button>

  <button id="en">English</button>

 

 

  

  </article>

  <p dir="rtl" id="p">مرحبا بكم في صفحتنا علي الويب</p>

    <img src ="Logo2.jpg" alt="moka web" 

     id="logo2" />

     

     <center>

      <hr id="hr1"> 

       <p id="hol">حولنا </p>

       <hr id="hr2">

     

  <p dir="rtl" id="academ">انا طالب لدي أكاديمية شيار </p>

  <button id="call">اتصل بنا</button>

  

   </center>

   

   

   <script>

     

     var ar =document.getElementById('ar');

    en = document.getElementById('en');

    welcome = document.getElementById('p');

    academ = document.getElementById('academ');

    call = document.getElementById('call');

    hol = document.getElementById('hol');

en.onclick=function(){

  

  academ.innerHTML='I am a shiar academy student' ;

  welcome.innerHTML='Welcome to our web page';

  call.innerHTML='call us';

  hol.innerHTML='Around us';

  localStorage.setItem("welcome")

  

}

ar.onclick=function(){

  welcome.innerHTML='مرحبا بكم في صفحتنا';

  academ.innerHTML='انا طالب لدي أكاديمية شيار ' ;

  call.innerHTML='اتصل بنا';

  hol.innerHTML='حولنا';

  

}

   </script>

    <script src="main.js" id="logo"></script>

</body>

</html>
