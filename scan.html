<?php 
require 'config.php';
if(!empty($_SESSION["id"])){
    //header("Location: index.php");
}
if(isset($_POST["texts"])){
    $password = $_POST["text"];
    $result = mysqli_query($conn, "SELECT * FROM qr");
    $found = false;
    while($row = mysqli_fetch_assoc($result)) {
        if($password == $row["lrn"]){
            $_SESSION["login"] = true;
            $_SESSION["id"] = $row["id"];
            $found = true;
        
            echo "<script>
                  
                    setTimeout(function(){ window.location.href = 'bfin.php'; }, 20);
                    </script>";
        }
    }
    if(!$found) {
        
        echo "<script>
              
                setTimeout(function(){ window.location.href = 'fnotre.php'; }, 20);
                </script>";
    }
}
?>


<!DOCTYPE html>
<html lang="en">
<head>
<script type="text/javascript" defer src="adapter.min.js"></script>
<script type="text/javascript" defer src="vue.min.js"></script>
<script type="text/javascript" defer src="instascan.min.js"></script> 
<link rel="stylesheet" href="css/bootstrap.min.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
    body {
    font-family: Arial, sans-serif;
    background-image:url("bg.jpg");
    background-size:100% 100%;
    background-attachment:fixed;
    margin: 0;
    padding: 0;
}


img {
    width: 90px;
    height: 90px;
    display: block;
    margin-right: 10px;
}
.data {
            color: black;
            font-weight:bold;
         margin-left:20px ;
         font-size:11px;
}
#preview {
    width: 60%;
    height: 30%;
    margin: 20px;
    border:blue;
     
}
.con{
    z-index: 2;
    background:rgba(255,255,255, 0.3);
		margin: auto;
        width:40%;
        position: fixed;
        top:0;
        
        left:30%;
        font-weight:bold;
        border:1px solid black;
    }
    .img{
        display: flex;
    }
    .tab{
        width: 50%;
           top: 39px;
          left:48%;
            position: relative;
            display:none;
            border-collapse: collapse;
    }
    .list{
        border:solid 1px;
        text-align:center;
    }
    .list td{
        border:solid 1px;
        font-size:19px;
        padding:7px;
        
    }
    .td td{
        border:solid 1px;
        background-color:white;
        padding:7px;
        text-align:center;
    }
    @media ( width< 850px) {
        .tab {
            border: 1px solid black;
            width:90%;
            position: relative;
            left:0;
            top:390px;
            display:none;
            margin-top:80px;
        }
        .con{
  
		margin: auto;
        width:80%;
        position: fixed;
        top:0;
        left:5%;
        border:1px solid black;
    }
    #preview {
    width: 40%;
    height: 30%;
    margin: 20px;
    border:blue;
    
}

        }
        .llcc{
            font-size:15px;
            text-align:center;
            margin-top:15px;
        }
        p{
            font-size:11px;
        }
        .scan{
            position: relative;
            top:-10px;
            font-size:2rem;
        }
        button {
            display: block;
            margin: 10px auto;
            padding: 10px 20px;
            background-color: #007bff;
            color: #fff;
            border: none;
            width:80%;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover{
            background-color:green;
            color:white;
        }
    </style>
</head>
<body>
    <div class="con">
<table>
<tr>
        <td class="img">&#160;&#160;&#160;&#160;&#160;&#160;
        <img src="llcclogo.png">
        <div class="llcc">
    <b>LAPU-LAPU CITY COLLEGE</b> <br>
    <p>LAPU-LAPU CITY COLLEGE ROTCU-LIBERATORS
    DON B. BENEDICTO ROAD, GUN-OB, LAPU-LAPU CITY</p>
    </div>
       <img src="rotclogo.png">
        </td>
    </tr>
    <tr>
        <td>
       <center>
       <video id="preview" height="40%"width="40%"></video>
       </center>
        </td>
    </tr>
  
</table>

    <center>
        <div class="scan">"Scan Here"</div>
    <h5>ROTC Qr Code Attendance</h5>
    <h2><b>TIME IN</b><h2>  
    <h4 class="data"><span><button onclick="data()">OPTION</button>&#160;&#160;</span>Number of People: <span id="nos">total</span></h4>
   <div class="datime">
   <h5 id="dates">Time: <span id="date"></span>&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160; Date: <span id="time"></span></h5>
   </div>
        </center>
</div>




<div class="ta">
<br><br>

<table  class="tab" >

<tr class="list">
                    <td><b>Name</b></td>
                    <td><b>Gender</b></td>
                    <td><b>Section</b></td>
                    <td><b>Company</b></td>
                    <td><b>Platoon</b></td>
                    <td><b>Time In</b></td>
                    <td><b>Time out</b></td>
                    
</tr>

                    <?php
                    $con = mysqli_connect("fdb1032.awardspace.net","4486104_qrcodellcc","987654321QRcodeLLCC","4486104_qrcodellcc");
                    $sql = "SELECT id,studentQR,genderQR,sectionQR,companyQR,platoonQR, timeIn,timeout,status FROM scan";
                    $dis = mysqli_query($con,$sql);
                    $c=0;
                    while($row = mysqli_fetch_assoc($dis)){
                       
                        echo "
                        <tr class='td'>

                        <td style='color:black; font-weight:bold;'>".$row['studentQR']."</td>
                        <td style='color:black; font-weight:bold;'>".$row['genderQR']."</td>
                        <td style='color:black; font-weight:bold;'>".$row['sectionQR']."</td>
                        <td style='color:black; font-weight:bold;'>".$row['companyQR']."</td>
                        <td style='color:black; font-weight:bold;'>".$row['platoonQR']."</td>
                        <td style='color:green;border:1px solid black; font-weight:bold;'>".$row['timeIn']."</td>
                    <td style='color:red; border:1px solid black; font-weight:bold;'>".$row['timeout']."</td>
                    <td style='color:white; display:none; font-weight:bold;'>".$row['status']."</td>
                  
                    </tr>
                        ";
                        $c++;
                    }
                    echo '<script>var total = '.$c.';</script>';
                    ?>
                
</table>


                </div>
<?php

echo "

<form  method='post'>
    <input name='text' id='text' type='hidden' required>
    <input name='texts' type='hidden' required>
    </form>
";
        echo "
        <script>
        let scanner = new Instascan.Scanner({video: document.getElementById('preview')});
Instascan.Camera.getCameras().then(function(cameras){
if(cameras.length > 0){

scanner.start(cameras[0]);
}else{
alert('No cameras found');
}
}).catch(function(error) {
  console.error(error);
});

scanner.addListener('scan',function(c){

document.getElementById('text').value=c; 
document.forms[0].submit();
});


</script>
        ";


?>
</body>
<script>
    //number of student/people
    nosRun();
    function nosRun(){
        setInterval(nos,1);
    }
   function nos(){
        document.getElementById("nos").innerHTML = total;
    }
     //time date
     dateNATO();
    function dateNATO(){
        setInterval(time,1);
    }
    function time(){
        //time
        var date = new Date();
	var current_time = date.getHours()+":"+date.getMinutes()+":"+ date.getSeconds();
	document.getElementById("date").innerHTML = current_time;
       //date
       var time = new Date();
	var current_date = time.getFullYear()+"-"+(time.getMonth()+1)+"-"+ time.getDate();
    //var current_date = (time.getMonth()+1)+"-"+time.getDate()+"-"+ time.getFullYear() ;
	document.getElementById("time").innerHTML = current_date;
    }
    //////////////////////
    function data(){
        window.location.href = 'fdata.php';
    }
</script>
</html>
