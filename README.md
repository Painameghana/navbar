navbar

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="nav.css">
</head>
<style>
    a{
        text-decoration: none;
        color: antiquewhite;
        text-align: center;
    }
    li{
        list-style-type: none;
        padding: 10px;
        text-align: center;
        display: inline;
       
    }
    .hi{
        background-color: blueviolet;
        border-radius: 30px;
    
    }
    .bi{
        background-color: aqua;
        border-radius: 30px;
    }
    .hey{
        background-color: rgb(37, 39, 172);
        border-radius: 30px;
    }
   .hi:hover{
        color: blueviolet;
        background-color: beige;
        border-radius: 10px;

    }
    .bi:hover{
        color: blueviolet;
        background-color: rgb(186, 186, 74);
        border-radius: 10px;

    }
    .hey:hover{
        color: blueviolet;
        background-color: rgb(229, 95, 11);
        border-radius: 10px;
     }
    .navbar{
        padding: 10px;
        background-color: black;
        text-align: center;

    }
    
</style>
<body>
    <nav>
        <div class="navbar">
            <ul>
             <a href="#"><li class="hi">Home</li></a>
             <a href="#" ><li class="bi">Contact</li></a>
             <a href="#"><li class="hey">Shop</li></a>
            </ul>

        </div>
    </nav>
