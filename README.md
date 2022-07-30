body{
    background-image: url(background.jpg);
    -webkit-background-size: cover;
    background-size:cover;
    background-position:center center;
}

.form-area{
    width:500px;
    height:450px;
    margin:auto;
    position:relative;
    background: rgba (0,0,0,0.5);
    text-align:center;
    margin-top:60px;
    padding:35px;
    border:3px solid #fff;
    -webkit-border-radius:;
    border-radius:70px 0 70px 0;
    box-shadow:10px 0 10px 0px #fff;
}

.form-area h2{
    margin-bottom:45px;
    color:#fff;

}

.img-area{
    width:80px;
    height:80px;
    border-radius:50px;
    background-color:white;
    position:absolute;
    top:-5%;
    left:45%;
}

.img-area img{
    width:60%;
    padding:10px;
}

input{
    width:100%;
    height:50px;
    border-radius:15px 0 15px 0;
    border:2px solid #ffff;
    margin-bottom:15px;
    background-color:transparent;
    color:#fff;  
}

.form-area p{
    text-align:center;
    color:#fff;
    text-transform:uppercase;
    font-weight:bold;
}

.btn{
    display:inline-block;
    height:40px;
    width:150px;
    line-height:40px;
    overflow:hidden;
    position:relative;
    text-align:center;
    background:tomato;
    border-radius:25px;
    color:#fff;
    text-transform:uppercase;
    margin-top:20px;
    cursor:pointer;
    text-decoration:none;
}

.btn-text{
    display:block;
    height:100%;
    position:relative;
    top:0;
    -webkit-transition:top 0.6s;
    -moz-transition:top 0.6s;
    transition: top 0.6s;
    width:100%;
}

.btn:hover .btn-text{
            top:-100%;

}

.for-pass{
    text-decoration:none;
    display:block;
    margin-top:30px;
    font-weight:bold;
    font-size:20px;
    color:#fff;
}
::-webkit-input-placeholder{
    color:black;
    text-align:center;
    font-size:15px;
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Registratio Form</title>
</head>
<body>
        <div class="form-area">
            <div class="img-area">
                <img src="avatar.png" alt="Kichui nai">
            </div>
            <h2>Login Form</h2>
            <p>Your Name: </p>
            <input type="text" placeholder="Input your name">
            <p>Your Email: </p>
            <input type="email" placeholder="Enter your email address">
            
            <a href="#" class="btn">
                <span class="btn-text">Sign In</span>
                <span class="btn-text">Log In</span>
            </a>
            <a href="#" class="for-pass">Forgot Password</a>
        </div>
</body>
</html>
