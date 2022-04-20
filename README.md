 practice
    /*console.log("helo")

var name="shubham";
var myage=23;
console.log(true&&true)
class Person {

    constructor(name) {
      this.name = name;
    }
  
    introduce() {
      console.log(`Hello, my name is ${this.name}`);
    }
  
  }
  
  const otto = new Person('Otto');
  
  otto.introduce();

let a = ""+12+12;
console.log(a);
console.log(typeof(a))
var imuseless=null;
NaN===NaN;
console.log(imuseless)
console.log(Number.isNaN(NaN))
console.log(5+5.00)
var a=5
var b=5
console.log("hello"+(a==b))
console.log(3+4)
console.log(40%5)
var  num=15
var numf=num++
console.log(num)
console.log(numf)
var  num=15
var numf=++num
console.log(num)
console.log(numf)
var d=30

var c=-20
console.log(a&b)
console.log((d&&c))
console.log(a>b||b>a)
console.log(3**3)
var f=2
var y=5
f=(f&y)|y
y=(f&y)|y
console.log(f,y)*/



//conditional 
/*var tommotrote=true
var today=false;
console.log(today)
var today=2020
if(score =0)
{
    console.log("we loss")
}
else{
    console.log("we won ")
}*/
/*
var sa=20
;

sa>10?console.log("you can vote "):console.log("you cannot vote");
*/
/*var area="circle";
switch(area)
{
case 'circle':
    console.log("hello")
    break


}


var i=0;

while(i<10)
{

    console.log(i)
    i++
}

var num1=30;
var h=0;
do{
 
 console.log(h);
h++
}
while(h<10);


for(var i=0;i<=5;i++)
{
console.log(i)

}

var a=2;
for(var i=1;i<=10;i++)
{
console.log(a+" * "+i+" = "+(a*i))


function d()
{
var a=0
var b=10
sum=a+b;
console.log(sum)
}

d()

function  mult(a,b=5)
{
return a*b

}
console.log(mult(3,7)) 

let a=7,b=6
 const sum=()=>`the sum is ${a+b}`
 console.log(sum());

 public static function(a,b)

class Polygon {

    constructor() {
       this.name = 'Polygon';
         }
       fun()
         {
             var name
             this.name='hello'
             console.log(name)
         }
  }
  
  
  const poly1 = new Polygon();
console.log(poly1.name)
console.log(poly1.fun)
  // expected output: "Polygon"
  

  
  const o=()=>{var my=new Array;
    var names =['shubham ','sdf'];
    

console.log(names.indexOf('thapa'))
const count=names.unshift('chickemn')
console.log(count)
  for(var x=0;x<names.length;x++)
  {console.log(names[x]);}
return names;}
console.log(o());

var  sirnames =['bhargava','sharma','jain']
sirnames.sort();

for(Element of sirnames)

    
{
console.log(Element)



let f=[1,2,3,4,5]
let arr=f.map((V)=>V*2).filter((CurElem)=> CurElem>4).reduce((accumulator,CurElm)=>{return accumulator +=CurElm},10)
console.log(arr)
var str="apple,banana"
//let res=str.slice(str.indexOf("banana"),str.length)
let res=str.slice(6,12)
console.log(res,str.length)
var d='heeloo';
let fd=d.charCodeAt(2)
let fd2=d.charCodeAt(2)
let fd3=d.repeat(2)
console.log(fd)
console.log(fd2)
console.log(fd3)
//let df=d.charCodeAt(d.lastIndexOf(d.charAt(d.length-1)))
var d='heeloo';
let df=d.charCodeAt(d.length)
console.log(df)

var sr='shusm'
console.log(sr[0])

console.log(Math.trunc(-2.02555))
*/
var x=["sdf","",""]
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
 turnon off light
 <html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
     body{
         display: flex;
         justify-content: center;
         align-items: center;
     }
  .unic{
    display: flex;
    justify-content: center;
    align-items: center;
  }

    </style>
</head>
<body>
    <div class="hello">
        <h1 style="text-align: center;">can you turn on</h1>
       <div class="unic"> <button onclick="document.getElementById('myimages').src='images/lighton.jpg'">turnon</button>
        <img src="images/lightof.jpg" alt="lightoff" id="myimages">
        <button onclick="document.getElementById('myimages').src='images/lightof.jpg'">turnof</button>
    </div></div>
</body>
</html>
 
 temperature conversion app
 html:
 <html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="1.css">
</head>
<body>
    <div class="container">
 <form id="tempCalc" onsubmit="calculatetemp()">
     <label for="temp">please enter temp to convert</label>
     <br/>
     <input type="number" style="margin-left: 30;" name="temp" id="temp">
     <select name="temp-diff" id="temp_diff">
         <option value="cel">celsius</option>
         <option value="fah">fahrenheit</option>
     </select>
     <br/><input type="submit" style="margin:0 70;background-color:black;color:white">
     <br/><span id="result"></span>
     </form>
 </div>
 <script src="temperatureform.js"></script>  
</body>
</html>
 css:
 body{

display: flex;
justify-content: center;
align-items: center;
background-color: rgb(235, 235, 18);
}
.container{
    background-color: rgb(73, 137, 194);
    display: flex;
    align-items: center;
    justify-content: center;
  vertical-align: middle;
  height: 15%;
}
#temp{

width: 50px;
margin: 5px 5px;

}
label{
    margin:0 20px;
}
 javascript:
 const calculatetemp=()=>{
    const numbertemp=document.getElementById('temp').value;
    const temp_selected=document.getElementById('temp_diff');
    const value =temp_diff.options[temp_selected.selectedIndex].value;
   console.log(value);
   const celtofah=(cel)=>{

   let fahrenheit=Math.round((cel*9/5)+32);
   return fahrenheit;
   }
   const fahtocel=(fah)=>{

    let celecius=Math.round((fah-32)*5/9);
    return celecius;
    }
  
  
   let result;
   if(value=='fah')
   {
   result=celtofah(numbertemp);
   document.getElementById('result').innerHTML=`${result}fah`;

   }
   else(value=='cel')
   {
   result=fahtocel(numbertemp);
   document.getElementById('result').innerHTML=`${result}celcius`;

   }
}
