# Form-m
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">s"> 
<style>
    body{
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        background-image: url('pexels.jpg');
    }
    .container{
        display: flex;
        justify-content: center;
        margin-top: 90px;
}
form{
    display: flex;
    justify-content: center;
    flex-direction: column;
    border: 2px solid white;
    border-radius: 10px;
    padding: 20px;
    width: 250px;
    background-color: rgba(0, 0, 0, 0.5);
}

input{
    padding: 10px;
    border-radius: 20px;
    border: 1px solid rgb(250, 250, 250);
    color: white;
    width: 230px;
    background-color: inherit;
    height: 20px;
    font-family:Arial, Helvetica, sans-serif;
    font-size: 16px;
}
button{
    background-color: white;
    color: black;
    border: none;
    padding: 10px 14px;
    width: 250px;
    font-size: 14px;
    font-weight: bold;
    border-radius: 20px;
}
h3{
    color: white;
    text-align: center;
    font-size: 25px;
}
i{
    color: white;   
}
.check{
    color: white;
    font-family:Arial, Helvetica, sans-serif;
    font-size: 12px;
}
p{
    text-align: center;
    color: white;
    font-size: 12px;
    font-family:Arial, Helvetica, sans-serif;
}

a{
    color: yellow;
}
</style>
</head>
<body>
    
    <div class="container">
        <form action="#" method="post">
            <h3>Login</h3>
            <div class="input">
            <input class="Username" type="text" name="username" placeholder="Username"  required><i class="fas fa-user"></i><br>
            <input class="password" type="text" name="password" placeholder="Password"  required><i class="fas fa-lock"></i><br>
            <div class="check"><input type="checkbox">Remember me &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp Forget password?<br><br>
            </div>
            </div>
            
    <button type="submit">Login</button>
    <p>Don't have an account? &nbsp<a href="www.form.com"> Register</a></p>
    </form>
        </div>
        
    
</body>
</html>
