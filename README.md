# modul18.html

task 1 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="task1var.css">
</head>
<body>

   <div>

   <button id="primarybtn">Primary button </button>
    <button id="secondrybtn">secondry button</button>
   </div>
    
</body>
</html>


css 
:root{

    --primarycolor: blue;
    --secondrycolor: red;

}
#primarybtn{

 background-color: var(--primarycolor);
 color:aliceblue;
 border-radius: none;
 padding: 10px 15px;
 border: none;
 border-radius: 5px;



}
#secondrybtn{

 background-color: var(--secondrycolor);
 color:aliceblue;
 border-radius: none;
 padding: 10px 15px;
 border: none;
 border-radius: 5px;
 


}

div{

   height: 500px;
   width: 1000px;
   border: 1px solid black ;
   padding: 10px;



}
task3

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="task3-loader.css">
</head>
<body>

    <div class="loader">
        </div>
    
</body>
</html>


css


.loader{
    
    border: solid rgb(193, 187, 187) 4px;
    height: 50px;
    width:50px;
    border-top: solid black 4px;
    border-radius: 50%;
    border-top: solid blue 4px;
    animation: load 1s linear infinite;

    

}
@keyframes load{
    0%{
        transform: rotate(0deg);
    }
    100%{
        transform: rotate(360deg);
    }
}








