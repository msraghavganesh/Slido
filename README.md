# Slido

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Live Poll Access</title>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:
    "Inter",
    "Segoe UI",
    Arial,
    sans-serif;
}


body{

    min-height:100vh;

    background:
    linear-gradient(
    135deg,
    #0b0b0c,
    #17191d
    );

    display:flex;
    align-items:center;
    justify-content:center;

    color:white;

}


.wrapper{

    width:100%;
    max-width:430px;
    padding:20px;

}



.card{


    background:
    rgba(20,20,22,.95);


    border-radius:24px;


    border:
    1px solid rgba(255,255,255,.12);


    padding:42px 32px;


    box-shadow:
    0 20px 60px rgba(0,0,0,.6);


    animation:
    fade .5s ease;

}



@keyframes fade{

from{
opacity:0;
transform:translateY(20px);
}

to{
opacity:1;
}

}



.logo{


font-size:42px;
font-weight:800;

letter-spacing:-2px;

color:#16a34a;

margin-bottom:35px;


}



.small{

color:#cfcfcf;

font-size:18px;

margin-bottom:18px;

}



.event{


font-size:26px;

font-weight:700;

line-height:1.25;


margin-bottom:12px;


}



.date{

color:#aaa;

font-size:16px;

margin-bottom:45px;


}




.field{


display:flex;

align-items:center;


border-bottom:

1px solid #555;


margin-bottom:28px;


}


.icon{

opacity:.7;

font-size:18px;

margin-right:10px;

}



input{


background:none;

border:none;

outline:none;


color:white;

width:100%;

font-size:16px;

padding:14px 5px;


}



input::placeholder{

color:#999;

}




.join{


margin-top:10px;

width:100%;

padding:16px;


border:none;

border-radius:10px;


background:

linear-gradient(
90deg,
#159447,
#1db954
);


font-size:17px;

font-weight:600;

color:white;


cursor:pointer;


transition:.3s;


}



.join:hover{

transform:scale(1.02);

}




.anonymous{


text-align:center;

margin-top:28px;

color:#bbb;

font-size:16px;


}



.footer{


text-align:center;

margin-top:35px;

font-size:12px;

color:#777;


}





@media(max-width:360px){


.card{

padding:35px 22px;

}


.event{

font-size:22px;

}

}

</style>


</head>


<body>


<div class="wrapper">


<div class="card">


<div class="logo">

slido

</div>



<div class="small">

Welcome to

</div>



<div class="event">

Cyber Awareness Quiz

</div>



<div class="date">

Live Session • June 2026

</div>




<div class="field">

<span class="icon">🔒</span>

<input placeholder="Passcode">

</div>



<div class="field">

<span class="icon">👤</span>

<input placeholder="Full name (optional)">

</div>




<button class="join">

Join session

</button>




<div class="anonymous">

Continue anonymously

</div>



</div>




<div class="footer">

Security Awareness Program
<br><br>

Privacy • Terms • Help

</div>



</div>



</body>

</html>