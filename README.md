<!DOCTYPE html>
<html>
<head>
<title>Lost and Found</title>

<style>

body{
    background: linear-gradient(to right, #36d1dc, #5b86e5);
    font-family: Arial;
    text-align:center;
    padding-top:50px;
}

.box{
    background:white;
    width:420px;
    margin:auto;
    padding:25px;
    border-radius:12px;
    box-shadow:0 4px 15px rgba(0,0,0,0.2);
}

input, textarea{
    width:90%;
    padding:10px;
    margin:8px;
    border-radius:6px;
    border:1px solid gray;
}

button{
    background:#5b86e5;
    color:white;
    padding:12px 20px;
    border:none;
    border-radius:8px;
    font-size:16px;
    cursor:pointer;
}

button:hover{
    background:#3d63c9;
}

img{
    width:90px;
}

</style>
</head>

<body>

<img src="https://cdn-icons-png.flaticon.com/512/685/685655.png">

<h1>Lost and Found Management System</h1>

<div class="box">

<h2>Report Lost Item</h2>

<input type="text" placeholder="Enter your name">

<input type="text" placeholder="Item lost">

<textarea placeholder="Describe the item"></textarea>

<br><br>

<button>Submit</button>

</div>

</body>
</html>
