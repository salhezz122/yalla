<?php

include "connfig/db.php";

$username=$_POST['username'];
$first=$_POST['first'];
$last=$_POST['last'];
$pass1=$_POST['pass1'];
$pass2=$_POST['pass2'];

$sql="select * from users where username='$username'";
$op = mysqli_query($conn,$sql);
$row = mysqli_fetch_assoc($op);

if(isset($row)){
    header("location: register.php?msg1");
    exit;
}

if($pass1!==$pass2){
    header("location: register.php?msg2");
    exit;
}

if(strlen($pass1)<6){
    header("location: register.php?msg3");
    exit;
}

$sql="insert into users (first,last,username,password)
values('$first','$last','$username','$pass1')";
$op = mysqli_query($conn,$sql);

header("location: index.php?create");
    exit;

?>
