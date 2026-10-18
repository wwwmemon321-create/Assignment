# Assignment
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="image">
           <img width="150px" src="https://static.vecteezy.com/system/resources/thumbnails/049/950/118/small/red-and-black-emblem-with-hooded-figure-cut-out-transparent-png.png" alt="">
        </div>
        <ul>
            <li class="L0">Home</li>
            <li class="L1">Product</li>
            <li class="L2">Contact</li>
            <li class="L3">Our-Shop</li>
            <li class="L4">Sign-in</li>
        </ul>
    </header>
    <section class="hero-section">
        <div class="container-1">
            <h3>Welcome To Lugx</h3>
            <h1>Best gaming Site Ever!</h1>
        </div> 
         <p>
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Pariatur, possimus? <br>Illum labore deleniti natus error nam  eveniet architecto in velit maiores accusantium <br>dolor cumque tempora, eum cupiditate nemo, excepturi voluptate. 
        </p>
        <div class="input">
          <input class="btn-2" placeholder="Enter Something" type="text">
          <button class="btn-1">Search Now</button>
        </div>
        <img class="hero-img" src="https://encrypted-tbn3.gstatic.com/images?q=tbn:ANd9GcTY0tyshPtvHZj4bV0HcvKFXL5gQGoGTJuZzQOaD7k1zhbotknG" alt="">        
    </section>
</body>
</html>



CSS File:
*{
    align-items: center;
    padding: 0px 10px;
}

body{
     background-color: rgb(0, 157, 255);
}
 
header{
    display: flex;
    justify-content: space-between;
    
}
ul{
    display: flex;
    gap: 30px;
    list-style: none;
    font-size: large;
    color: white;
    font-weight: bold;

}

.L0{
    background-color: rgb(183, 183, 183);
    width: 100px;
    height:50px ;
    border-radius: 250px;
    align-content: center;
    text-align: center;
}

.L4{
    background-color: brown;
    width: 100px;
    height:50px ;
    border-radius: 250px;
    align-content: center;
    text-align: center;
}

.container-1{
    padding: 50px 50px 0px;
     font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
     font-size: xx-large;
     color: white;
     font-style: bold;

    
}

p{
    font-size: larger;
    padding-left: 60px;
    padding-top: 20px;
    font-weight: bold;
    font-family: Arial, Helvetica, sans-serif;
}

.input{
    position: relative;
    top: 100px;
    left: 60px;
    background-color: white;
    /* width: 200px;
    height: 50px; */
    width: 400px;
    height:50px ;
    border-radius: 250px;
    align-content: center;
    
    
}

.hero-section{

}

.hero-img{
    position: relative;
    left: 900px;
     bottom: 400px;
     border-radius: 30px;
     border: ;
}

.btn-1{
    background-color: #EA636A;
    width: 130px;
    height: 50px;
    border: none;
    border-radius: 30px;
    position: relative;
    left: 94px;
}

.btn-2{
    position: relative;
    left: 20px;
    border: none;
}

    

