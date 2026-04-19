Это 6 лаба Верстка
Html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Document</title>
</head>
<header class="top-bar">
        <div class="logo">
                <img src="/res/chef-hat (2) 1.svg" alt="" width="32px" srcset="">
                <a href="" class="logoLink">Foo</a>
        </div>
        <nav class="nav">
            <div class="menu-items">
                <a href="..." class="Btn-menu">Home</a>
                <a href="..." class="Btn-menu">Menu</a>
                <a href="..." class="Btn-menu">Contact</a>
                <a href="..." class="Btn-menu">Shop</a>
            </div>
        </nav>
        <div class="Search">
            <img src="/res/Vector.svg" alt="" width="18">
            <span class="Text_search">Search</span>
            <div class="Cart">
                <img src="/res/Shopping cart.svg" width="20" alt="">
                <div class="pop">2</div>
            </div>   
        </div>
    </header>
<body>
    <div class="actions">

        <div class="textBlock">
            <div class="title">
                <span class="Fast">Fast</span><span class="FD">Food<br>Delivery</span>
            </div>
            <span class="subtext">
                Sed ut perspiciatis unde omnis iste natus sit<br>voluptatem accusantium doloremque laudantium
            </span>
            <div class="btns">
                <div class="btnOrder">Order Now</div> 
                <div class="btnWatchV">
                    <div class="btnPlay"><div class="triangle"></div></div>Watch Video
                </div>
            </div>
            <div class="ratingBlock">
                <div class="stars">
                    <div class="star"></div><div class="star"></div><div class="star"></div><div class="star"></div><div class="star"></div>
                </div>
                <div class="textRating">
                    <span class="r1Rat">5 star rating</span><br><span class="r2Rat">based on 1788 reviews</span>
                </div>
            </div>
        </div>
        
        
            <img src="/res/17372 [Converted] 1.png" alt="" class="FoodImg">
        
    </div>
    
</body>
</html>
```

css

```
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
.top-bar{
    display: flex;
    padding: 30px 15px 30px 15px;
    box-sizing: border-box;
    height: fit-content;
    justify-content: space-around;

}
.logo {
    display: flex;
    align-self: baseline;
}
.logoLink{
    font-family: "Poppins", sans-serif;
    font-weight: 600;
    font-size: 32px;
    color: black;
    text-decoration: none;

}
.nav{
    display: flex;
    height: fit-content;
    align-self:center;
}
.menu-items{
    display: flex;
    align-self:center;
    width: 50%;
    justify-content: space-around;
    gap: 25px;
}

.Btn-menu{
    font-family: "Poppins", sans-serif;
    font-weight: 400;
    text-decoration: none;
    font-size: 22px;
    color: black;
    padding: 5px;
    margin: 5px;
}
.Search{
    display: flex;
    flex-grow: 0;
    width: 314px;
    height: 60px;
    border: 1px solid rgba(0, 0, 0, 0.156);
    border-radius: 30px;
    box-shadow: 1px 12px 40px rgba(243, 255, 187, 0.375);
    align-content: center;
    align-items: center;
    justify-content: flex-start;
    padding: 0px 15px;
    gap: 10px;
}
.Text_search{
    font-family: "Poppins", sans-serif;
    font-weight: 400;
    font-size: 22px;
}
.Cart{
    padding: 15px;
    margin-left: auto;
    position: relative;
}
.pop{
    border: 2px solid red;
    font-family: "Poppins", sans-serif;
    font-weight: 400;
    color: white;
    font-size: 12px;
    width: 17px;
    height: 17px;
    border-radius: 30px;
    background-color: crimson;
    box-shadow: 1px 3px 25px rgb(255, 0, 0);

    position: absolute;
    right: 0px;
    top: 5px;

    display: flex;
    align-items: center;
    justify-content: center;
}

/* BODY */
body{
    background: linear-gradient(to right, #f4ece1, #fcfbf7);
}
.actions{
    display: flex;
    justify-content: center;
    align-items: center;
    width: 90%;
    padding-left: 20px;
}
.textBlock{
    display: flex;
    flex-direction: column;
}
.title{
    display: flex;
    align-items: center;
}
.FoodImg{
    min-width: 0px;
    min-height: auto;
}
.Fast{
    font-family: "Poppins";
    font-weight: 700;
    font-size: 9em;
    color: #ff7e00;
}
.FD{
    
    line-height: 1;
    font-family: "Poppins";
    font-weight: 700;
    font-size: 52px;
}
.subtext{
    font-family: "Poppins";
    font-weight: 400;
    font-size: 22px;
    color: #909090;
}
.btns{
    margin-top: 70px;
    display: flex;
    gap: 35px;
    flex-direction: row;
    align-items: center;
}
.btnOrder{
    display: flex;
    justify-content: center;
    align-items: center;
    font-family: "Poppins";
    font-weight: 600;
    font-size: 20px;
    color: white;
    border: 1px solid black;
    background-color: #2f2f2f;
    box-shadow: 0px 20px 32px rgba(0, 0, 0, 0.20);
    border-radius: 50px;
    width: 188px;
    height: 70px;
}
.btnWatchV{
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    font-family: "Poppins";
    font-weight: 600;
    font-size: 20px;
    color: rgb(0, 0, 0);
}

.triangle {
    width: 18px;
    height: 18px;
    background-color: #000;
    clip-path: polygon(0% 0%, 0% 100%, 100% 50%);  
}
.btnPlay{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 60px;
    width: 60px;
    min-width: 0px;
    min-height: auto;
    box-shadow: 0px 20px 38px -16px rgba(0, 0, 0, 0.637);
    background-color: #fff8ee;
    border: 1px solid #fff8f0;
    border-radius: 300px;
    margin: 10px;
}
.stars{
    display: flex;
    flex-direction: row;
    gap: 3px;
}
.star {
    width: 28px;
    height: 25px;
    background-color: #ffd000;
    clip-path: polygon(
    50% 0%,    
    63% 38%,    
    100% 38%,   
    69% 59%,   
    82% 100%,   
    50% 75%,    
    18% 100%,   
    31% 59%,    
    0% 38%,     
    37% 38%    
  );
}
.r1Rat{
    font-family: "Poppins";
    font-weight: 600;
    font-size: 18px;
    color: #000000;
}
.r2Rat{
    font-family: "Poppins";
    font-weight: 300;
    font-size: 18px;
    color: #000000;
}
.ratingBlock{
    padding-top: 50px;
    display: flex;
    flex-direction: column;
    gap: 15px;
}

@media (max-width: 768px) {
    .top-bar{
    flex-direction: column;
    }  
    .Search{
    width: 90%;
    } 
    .logo{
        display: flex;
        width: 90%;
        justify-content: center;
        align-items: center;
    }
    .FoodImg{
        width: 0px;
        height: 0px;
    }
    body{
        background-image:  
        linear-gradient(linear-gradient(to right, #f4ece100, #fcfbf700)),
        image-set("/res/17372 [Converted] 1.png");
    }
    .menu-items{
    gap: none;
    }
    .Btn-menu{
    padding: 0px;
    margin: 0px;
    }
    .Fast{
    font-size: 5em;
    color: #ff7e00;
    }
    .FD{
    font-size: 2em;
    }
    .subtext{
        font-size: 1em;
    }
    .btnOrder{
        font-size: 1em;
        width: 130px;
        height: 50px;
    }
    .btnWatchV{
        font-size: 0.8em;
    }
    .btnPlay{
        height: 50px;
        width: 50px;
    }
}
```

