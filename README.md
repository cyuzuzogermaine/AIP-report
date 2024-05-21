<!DOCTYPE html>
<html lang="en">
<head>
 <script>
 function simple()
 {
var n=document.getElementById("a").value;
var message=document.getElementById("message")
var c=document.getElementById("b").value;
var nice=document.getElementById("nice|")
if(n=="")
{
document.getElementById("message").innerHTML="**password can not be empty**";
return false;    
}<!DOCTYPE html>
<html lang="en">
<head>
 <script>
 function simple()
 {
var n=document.getElementById("a").value;
var message=document.getElementById("message")
var c=document.getElementById("b").value;
var nice=document.getElementById("nice|")
if(n=="")
{
document.getElementById("message").innerHTML="**password can not be empty**";
return false;    
}
else if(n.length<5)
{
document.getElementById("message").innerHTML="**!!New password is too short**";
return false;    
}

else if(n.length>10)
{
document.getElementById("message").innerHTML="**password is strong**";
return false;   
}
else if(n=="password")
{
document.getElementById("message").innerHTML="**password can not be password**";
return false;    
}
else if("n!=c")
{
document.getElementById("nice").innerHTML="**password can't match**";
return false;    
}
 }   
 </script>   
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
<form action="" onsubmit="return simple();">    
<Label>new password</Label>
<input type="password" id="a"placeholder="enter new password"><span id="message" style="color: red;"></span><br><br>
<label >comfirmpassword</label>
<input type="text" id="b"placeholder=" comfirm password"><span id="nice" style="color: red;"></span><br><br>
<button>send</button>    
</body>
</html>
else if(n.length<5)
{
document.getElementById("message").innerHTML="**!!New password is too short**";
return false;    
}

else if(n.length>10)
{
document.getElementById("message").innerHTML="**password is strong**";
return false;   
}
else if(n=="password")
{
document.getElementById("message").innerHTML="**password can not be password**";
return false;    
}
else if("n!=c")
{
document.getElementById("nice").innerHTML="**password can't match**";
return false;    
}
 }   
 </script>   
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
<form action="" onsubmit="return simple();">    
<Label>new password</Label>
<input type="password" id="a"placeholder="enter new password"><span id="message" style="color: red;"></span><br><br>
<label >comfirmpassword</label>
<input type="text" id="b"placeholder=" comfirm password"><span id="nice" style="color: red;"></span><br><br>
<button>send</button>    
</body>
</html>
