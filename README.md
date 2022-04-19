# javascript-hackls
1.how to centre a flexbox on screen
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
   #contain{
       display: flex;
       column-gap: 2px;
       justify-content: center;
       align-items: center;
       overflow: hidden;
       position: absolute;
       width: 100%;
       height: 100%;
   }

    </style>
</head>
<body>
    <div id="contain">///shortcut to create this div is (div>div+div)
      <div>hello</div>
        <div>hello</div>
    </div>
</body>
</html>
/************************************************************/
#2.add class dynamically in html using css and javascript

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="app.css" >
</head>
<body>
    <p style="text-align: center;">hello</p>
    <h1 id="fd" style="text-align: center;">hello</h1>

    <button id="buttons" onclick="changecolor()"  style="margin:0 auto; display:block; width: 100px;"(to convert button into block and resize and reposition it)>click here</button>
    <script>
        changecolor=()=>{
 if(document.getElementById('fd').innerHTML=="welcome")
 { 
    document.getElementById('fd').innerHTML="hello"
    const btn=document.getElementById("buttons")
    btn.addEventListener('click',()=>{
        btn.style.backgroundColor="red"
        btn.style.color="yellow" })
    
        const x=document.getElementsByClassName("ew")
        for(let i = 0; i < x.length; i++){
            x[i].classList.remove('zy');//added zy class dynamically from css//
            console.log(x[i]);
        }
    }
else
   {
    document.getElementById('fd').innerHTML="welcome"
    const btn=document.getElementById("buttons")
   btn.addEventListener('click',()=>{
       btn.style.backgroundColor="white"
       btn.style.color="black"
   })
   const x=document.getElementsByClassName("ew")
   console.log(x);
   
   for(let i = 0; i < x.length; i++){
       x[i].classList.add('zy');
       console.log(x[i]);
   }

        }}


    </script>
    <div>

<div class="fddr">
<div class="ew">hello</div>
<div class="ew">hello 2</div>
<div class="ew">hello3</div>
<div class="ew">hello4</div>
<div class="ew">hello</div>
<div class="ew">hello</div>
<div class="ew">hello</div>
<div class="ew">hello</div>
</div>
</body>
</body>
</html>

  app.css contents
  
  body
{  background-image: url('https://source.unsplash.com/random');
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}
.fddr{
    display: flex;
    height: 200px;
    align-items: center;
    justify-content: center;
    justify-items: center;

}
.ew{
   
  background-color:grey;
  width: 100px;
  margin: 10px;
  text-align: center;
  line-height: 75px;
  flex-grow: 1;
  width: calc(100% * (1/4) - 10px - 1px);
  width: calc(100% * (1/4) - 10px - 1px);
  color:"red";
  
}
.zy{
    font-size: 30px;
    color: red;
}
  /**********************************************************/
  <html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <div class="main">
        <div>
            <p id="showmy"></p>
            <br>
            <button id="btn" onmouseover="fun()" onmouseout="fun2()">click here</button>
            <button id="btn1" >increasesize</button>
        </div>
</div>
    <script>
        const myname=document.querySelector('#showmy')
        const btn=document.getElementById('btn')
           const fun=()=>{   
         btn.style.fontSize='40px'
    };
    const fun2=()=>{   
        btn.style.fontSize='12px'
   };
    const showmyname=()=>{
myname.innerHTML="loading"
 setTimeout(()=>{
     myname.innerHTML="shubham"
 },2000)

        }
        btn.addEventListener('click',showmyname)
    </script>
    <style>
        #btn1:hover{
font-size: 80px;

        }
    </style>
</body>
</html>
  
  
  /*********************************/
  
