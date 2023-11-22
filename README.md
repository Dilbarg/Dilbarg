- 👋 Hi, I’m @Dilbarg
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Dilbarg/Dilbarg is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Dilbar portfolio</title>
    <script src="https://kit.fontawesome.com/a7220980ba.js" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="ym.css">
    <style>
    @import url('https://fonts.googleapis.com/css2?family=Nunito:max-width:@200;300;400@;600& display=swap');
          
  *{
    font-family: 'Nunito', sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    outline: none;
    border: none;
    text-transform: capitalize;
    transition: all .2s linear;
}

html{
    font-size: 62.5%;
    overflow-x: hidden;
}

body{
    background: #111;
    overflow-x: hidden;
    padding-left: 35rem;
}

section{
    min-height: 100vh;
    padding: 1rem;
}

.btn{
    padding: 0.7rem 3rem;
    background: #333;
    color: #fff;
    cursor: pointer;
    margin-top: 1rem;
    font-size: 2rem;
    border-radius: 5rem;  
}

.btn i {
    padding: 0 .5rem;
    font-size: 1.8rem;
}

.btn:hover{
    background: rgb(163, 163, 238);
   box-shadow: 2px 2px 10px gray;

}

.heading{
    text-align: center;
    margin: 0 6rem;
    font-size: 4rem;
    padding: 1rem;
    border-bottom: .1rem solid #fff4;
    color: #fff;
}

.heading span{
    color: rgb(9, 255, 0);;
}
/* header */


header{
    position: fixed;
    top: 0;
    left: 0;
    z-index: 1000;
    height: 100%;
    width: 35rem;
    background: #1a1a1a;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-flow: column;
    text-align: center;
}

header .user img{
    height: 20rem;
    width: 20rem;
    border-radius: 50%;
    object-fit: cover;
    margin-bottom: 1rem;
    margin-top: -30px;
    border: .3rem solid #fff;
}


header .user .name{
    font-size: 3.5rem;
    color: #fff;
}

header .user .post{
    font-size: 2rem;
    color: #eee;
}
header .navbar{
    width: 100%;
}
header .navbar ul{
    list-style: none;
    padding: 1rem 3rem;
}
header .navbar ul li a{
    display: block;
    padding: 1rem;
    margin: 1.5rem;
    background: #333;
    color: #fff;
    font-size: 2rem;
    border-radius: 5rem;
    text-decoration: none;
}

header .navbar ul li a:hover{
    background: rgb(163, 163, 235);
    box-shadow: 2px 2px 10px gray;
}

#menu{
    position: fixed;
    top: 2rem;
    right: 2rem;
    color: #fff;
    cursor: pointer;
    font-size: 2.5rem;
    padding: 1rem 1.5rem;
    z-index: 1000;
    display: none;
}

.home{
    display: flex;
    justify-content: center;
    flex-flow: column;
    padding: 0 15rem;
}
.home h3{
    font-size: 2.5rem;
    color:#fff;
}

.home h1{
    font-size: 5rem;
    color:#fff;
}

.home h1 span{
    color: rgb(9, 255, 0);;
}


.home p{
    font-size: 2rem;
    color:#fff;
    padding: 1rem 0;
}

.about .row{
    display: flex;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap;
    padding: 1rem 0;
}

.about .row .info{
    flex: 1 1 48rem;
    padding: 2rem 1rem;
    padding-left: 6rem;  
}

.about .row .info h3{
    font-size: 2rem;
    color: rgb(9, 255, 0);
    padding: 1rem 0;
    font-weight: normal;
}

.about .row .info h3 span{
    color: #eee;
    padding: 0 .5rem;
}

.about .row .counter{
    flex: 1 1 48rem;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap;  
} 

.about .row .counter .box{
    width: 20rem;
    background: #222;
    text-align: center;
    padding: 2rem;
    margin: 2rem;
}

.about .row .counter .box span{
    font-size: 4rem;
    color: rgb(9, 255, 0);
}

.about .row .counter .box  h3{
    font-size: 2rem;
    color: #fff;
}

.education .box_container{
    display: flex;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap;
    padding: 1rem 0;
    padding-left: 3rem;   
}

.education .box_container .box{
    width: 27rem;
    margin: 4rem 1rem;
    padding-left: 4rem;
    border-left: .2rem solid #fff;
    position: relative;
}

.education .box_container .box span{
    font-size: 1.3rem;
    background: #222;
    color: #fff;
    border-radius: 5rem;
    padding: .5rem 2.5rem;
}

.education .box_container .box h3{
    font-size: 2rem;
    color: #fff;
    padding-top: 1.5rem;
}


.education .box_container .box h4{
    font-size: 1.8rem;
    color: #18f60e;
    padding-top: 0.5rem;
}

.education .box_container .box p{
    font-size: 1.4rem;
    color: #fff;
    padding-top: 1rem 0; 
    text-transform: uppercase;   
}

.education .box_container .box i{
    position: absolute;
    top: -1.5rem;
    left: -2.5rem;
    height: 5rem;
    width: 5rem;
    border-radius: 50%;
    line-height: 5rem;
    text-align: center;
    font-size: 2rem;
    color: #fff;
    background: rgb(9, 255, 0);
}
.extra h3{color:rgb(115, 235, 115);font-size: 4rem;margin-top: 10px; padding-left: 400px; margin-bottom: 50px;}
.extra p{color: #fff; font-size: 20px;margin-bottom: 0%;padding: 2rem;}


                            /* portfolio */

.portfolio .box_container{
    display: flex;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap;
    padding: 2rem 0;
}

.portfolio .box_container .box{
    height: 20rem;
    width: 26rem;
    border-radius: 2rem;
    margin: 2rem;
    overflow: hidden;
    cursor: pointer;
}

.portfolio .box_container .box img{
    /* transition: all ease 7s ; */
    object-fit: cover;
    height: 100%;
    width: 100%;
}

.portfolio .box_container .box:hover img{
    transform: scale(1.2);
}

           /* contact */

.contact .row{
    display: flex;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap;    
}

.contact .row .content{
    flex: 1 1 30rem;
    padding: 4rem;
    padding-bottom: 0;
}

.contact .row form{
    flex: 1 1 45rem;
    padding: 2rem;
    margin: 2rem;
    margin-bottom: 4rem;
}

.contact .row form .box{
    padding: 1.5rem;
    margin: 1rem;
    background: #3333;
    color: #fff;
    text-transform: none;
    font-size: 1.7rem;
    width: 100%;
}

.contact .row form .box::placeholder{
    text-transform: capitalize;
}

.contact .row form .message{
    height: 15rem;
    resize: none;
}

.contact .row .content .title{
    text-transform: uppercase;
    color: #fff;
    font-size: 3rem;
    padding-bottom: 2rem;
}

.contact .row .content .info h3{
    display: flex;
    align-items: center;
    font-size: 2rem;
    color: #fff;
    padding: 1rem 0;
    font-weight: normal;
}

.contact .row .content .info h3 i{
    padding-right: 1rem;
    color:rgb(9, 255, 0);
}

.top{
    position: fixed;
    bottom: 7.5rem;
    right: 2rem;
    z-index: 100;
    display: none;
}
.top img{
    max-width: 48px ;
    cursor: pointer;
    transition:.6s ease all;
    border-radius: 50% !important;;
    margin-left:-1em !important;
}
.top img:hover{
    transform : scale(1.1) rotate(-3deg);
    box-shadow: -1px  1px rgb(255 , 255 , 255),
    1px   1px rgba(255 , 255 , 255,.2 );
}










/* media queries */
@media (max-width:1200px){
   
    html{
        font-size: 55%;
    }
    .home{
        padding: 1rem 4rem;
    }
}
@media (max-width:991px){
    header {
        left: -120%;
    }
    #menu{
        display: block;
    }
    header.toggle{
        left: 0%;
    }
    body{
        padding: 0;
    }
}

@media (max-width:768px){
    html{
        font-size: 50%;
    }
}

@media (max-width:400px){
    header {
        width: 100vw;
    }
    .heading{
        margin: 0 3rem;
    }

    .about .row .counter .box{
        width: 100%;
    }

    .education .box_container .box{
        width: 100%;
    }

    .portfolio .box_container .box{
      width: 100%;  
    }

    .contact .row form{
        margin: 3rem 0;
    }

}
    </style>
</head>

<body>
    <header>
        <div class="user">
            <img src="./dilbar gurjar.jpg" alt="">
            <h3 class="name">Dilbar Gurjar</h3>
            <p class="post">Front end developer</p>
        </div>
        <!-- navbar links -->
        <div class="navbar">
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About me</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#contact">Contact Me</a></li>
            </ul>
        </div>
    </header>

    <!-- header section end -->

    <div id="menu" class="fa-solid fa-bars"></div>

    <!-- home section start -->
    <section class="home" id="home">
        <h3>HI THERE !</h3>
        <h1>I'M <span class="text">Dilbar Gurjar</span></h1>
        <p>Hello everyone, my name is Dilbar Gurjar. I am from Alwar Rajasthan. Recently I am pursing B.C.A from CIITM College Sitapura Jaipur.</p>

        <a href="#about"><button class="btn">About me <i class="fa-solid fa-user"></i></button></a>
    </section>
    <!-- home section End -->

    <!-- About section Start -->
    <section class="about" id="about">
        <h1 class="heading"><span>About</span> Me</h1>

        <div class="row">

            <div class="info">
                <h3><span>Name :</span>Dilbar Gurjar</h3>
                <h3><span>Age :</span> 21</h3>
                <h3><span>Qualification :</span>Pursing B.C.A</h3>
                <h3><span>Post :</span> Front end developer</h3>
                <h3><span>language :</span> Hindi, English</h3>
                <a href="./gurjar.jpeg" download><button class="btn">Download CV <i
                            class="fa-solid fa-download"></i></button></a>
            </div>

            <div class="counter">
                <div class="box">
                    <span>3</span>
                    <h3>Months of experience</h3>
                </div>

                <div class="box">
                    <span>3+</span>
                    <h3>Projects completed</h3>
                </div>
            </div>

        </div>
    </section>
    <!-- About section End -->


    <!-- education section start -->
    <section class="education" id="education">
        <h1 class="heading">My <span>Education</span> </h1>

        <div class="box_container">

            <div class="box">
                <i class="fa-solid fa-graduation-cap"></i>
                <span>2018</span>
                <h3>Board of Secondary Education, Rajasthan (RBSE)</h3>
                <h4>Krishana Public School Hamirpur (Alwar)</h4>
                <p>1st grad</p>
                

            </div>
            <div class="box">
                <i class="fa-solid fa-graduation-cap"></i>
                <span>2021</span>
                <h3>Board of Secondary Education, Rajasthan (RBSE)</h3>
                <h4>Rawat Public  SR. Sec. School (Jaipur)</h4>
                <p>2nd grade</p>
                
            </div>
            <div class="box">
                <i class="fa-solid fa-graduation-cap"></i>
                <span>2023</span>
                <h3>Bachelor of Computer Applications(B.C.A)</h3>
                <h4>CIITM College Jaipur</h4>
                <p>pursing</p>
                
                
                </div>
        </div>
        <div class="extra box " style="margin-top: 360px; margin-bottom: 380px;">
            <h3>CERTIFICATIONS</h3>
            <p><span>1.</span>Front-end Web Development(AU Skill Center Jiapur)<i class="fa-solid fa-circle-check"></i></p>
            <p><span>2.</span>IT quiz(IPS College Jaipur )  <i class="fa-solid fa-circle-check"></i></p>          
            <p><span>3.</span> RSCIT (Matrix Classes Jaipur) <i class="fa-solid fa-circle-check"></i></p>
           
           
            
        </div>
    </section>
    <!-- education section end -->

    <!-- portfolio section start -->
    <section class="portfolio" id="portfolio">
        <h1 class="heading">My <span>Skills</span></h1>
          
        <div class="extra box">
            <!-- <h3>CERTIFICATIONS</h3> -->
            <p><span>1.</span> HTML <i class="fa-solid fa-circle-check"></i></p>
            <p><span>2.</span> CSS <i class="fa-solid fa-circle-check"></i></p>          
            <p><span>3.</span> Bootstrap <i class="fa-solid fa-circle-check"></i></p>          
            <p><span>4.</span>Javascript <i class="fa-solid fa-circle-check"></i></p>
             
            
        </div>

        <!-- <div class="box_container"> -->
            <!-- netflix-homepage -->
            <!-- <div class="box">
                <a href="#"><img
                        src="picss/p1.webp" alt="fitness" title="fitness"></a>
            </div> -->
            <!-- Calculator -->
            <!-- <div class="box">
                <a href="#"><img src="picss/p2.png" alt="blog"
                        title="blog"></a>
            </div> -->
            <!-- college website -->
            <!-- <div class="box">
                <a href="#"><img src="#"
                        alt="TO-DO app" title="TO-DO app"></a>
           
        </div> -->
    </section>
    <!-- portfolio section end -->

    <!-- contact section start -->

    <section class="contact" id="contact">
        <h1 class="heading"><span>Contact </span>Me</h1>

        <div class="row">

            <div class="content">
                <h3 class="title">Contact info</h3>

                <div class="info">
                    <h3> <i class="fa-solid fa-envelope"></i>&nbsp;dilbargurjar7031@gmail.com</h3>
                    <h3> <i class="fa-solid fa-phone"></i>&nbsp;+91-8963095488</h3>
                    <!-- <h3> <i class="fa-solid fa-phone"></i>&nbsp;+91-9105127889</h3> -->
                    <h3> <i class="fa-solid fa-map-marker-alt"></i>&nbsp;Village Thanagazi (Alwar)</h3>
                </div>
            </div>

            <form action="">
                <input type="text" placeholder="NAME" required class="box">
                <input type="email" placeholder="Email Address " required class="box">
                <input type="text" placeholder="Projects" required class="box">
                <textarea name="" cols="30" rows="10" placeholder="Message..." class="message box"></textarea>
                <button type="submit" class="btn" >Send <i class="fa-solid fa-paper-plane"></i></button>
            </form>

        </div>
    </section>

    <!-- contact section end -->

    <!-- scroll top button -->
    <a href="#home" class="top">
        <img src="STB.png" alt="">
    </a>

    <!-- jquery link -->
    <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.7.0/jquery.min.js"></script>
    <script src="script.js"></script>
</body>

</html>
