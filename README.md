# SENM
<!--Social Page and also Home page-->
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SENM</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="moreStyle.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Heebo:wght@100&family=Lato:wght@100&family=Oswald:wght@200&family=Roboto:wght@100&display=swap');
        @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;900&display=swap');


        .group {
            margin-left: 20px;
            font-weight: 700;
            font-size: 20px;

        }


        #notification {
            border-radius: 50%;
            background-color: rgba(255, 255, 255, 0.7);
        }

        main {
            background-color: lightgray;
            display: flex;
            margin: 0;
            width: 100%;


        }

        .main-left {
            width: 100%;
            padding: 5px;
            height: 820px;
            overflow-x: hidden;
        }

        .main-center-home {
            width: 98%;
            margin: 5px;
            border-radius: 3px;
        }

        .main-right {
            width: 98%;
            margin: 5px;
            border-radius: 3px;
        }

        .mainsubleft {
            padding: 30px 30px 30px;
            background-color: rgba(255, 255, 255);
            border-radius: 3px;
            box-shadow: 0 0 1px;
        }

        .mainsubleft ul li {
            display: flex;
            margin-bottom: 15px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
          
        }
        .mainsubleft ul li a {
        
            font-size: medium;
            color: darkblue;
          
        }

        #icons {
            margin-left: -2.5px;
            margin-right: 2.5px;
        }

        .institution {
            min-width: 200px;
            height: 250px;
            margin: 1px 2px;
            border: 1px solid gray;
            background: lightgrey;
            border-radius: 7px;
            cursor: pointer;
            overflow: hidden;

        }

        .cont {
            text-align: center;
            border-top: transparent;
            font-family: oswald;
        }

        .institution-img {
            width: 100%;
            height: 80%;

        }

        #img {
            width: 100%;
        }

        .centerHeading {
            width: 100%;
            background-color: goldenrod;
            padding: 20px 0;
            box-shadow: 0 0 2px black;
        }

        .centerHeading h1 {
            text-align: center;
            color: white;
            font-family: oswald;
            font-weight: 700;
        }

        .center {
            position: relative;
            width: 600px;
            margin-top: 3%;
            padding: 10px;
            background: white;
            box-shadow: 0 0 1px black;
        }

        .center-images {
            width: 100%;
            display: flex;
            justify-content: left;
            align-items: center;
            overflow: auto;
            position: relative;
            scroll-behavior: smooth;
            box-shadow: 0 0 1px black;
            padding: 2px;
            background: black;
        }

        .mainSubRight {

            background-color: rgba(0, 0, 0, 0.1);
            padding: 25px;
            box-shadow: 0 0 5px black;
        }

        .rightLogin {
            margin-top: 5px;
            background-color: white;
            padding-bottom: 5%;
            box-shadow: 0 0 2px black;
        }

        .rightLogin h2 {
            margin-left: 50px;
            margin-bottom: 15px;
            color: white;
        }

        select {
            width: 96%;
            margin-left: 25px;
            height: 30px;
        }

        input {
            width: 70%;
            margin-left: 50px;
            height: 30px;
            padding: 0 20px;
            font-size: 16px;
        }

        #register {
            color: goldenrod;
        }

        #register:hover {
            text-decoration: underline;
        }

        #menu-bar {
            display: none;
        }

        #search {
            margin-top: 5%;
            margin-bottom: 5%;
            background-color: rgba(255, 255, 255, 0.7);
            padding-bottom: 5%;
        }
        #search1 {
            margin-top: 5%;
            margin-bottom: 5%;
            background-color: rgba(255, 255, 255, 0.7);
            padding-bottom: 5%;
            display: none;
        }

        .searchInput {

            padding: 20px 10px;
            background-color: darkblue;
            border-radius: 7px;
        }

        .searchInput input {
            background: rgba(255,255,255);
            font-size: 22px;
            letter-spacing: 2px;
            text-align: center;
            border: transparent;
            height: 45px;
            border-bottom-left-radius: 45px;
            border-top-left-radius: 45px;
        }

        .friends {
            display: flex;
            justify-content: space-between;
            color: black;
            font-size: 20px;
            padding: 10px 30px;
            margin-bottom: 10px;
            background-color: white;
            box-shadow: 0 0 5PX 0 black;
        }

        .main-scroll-div {
            width: 90%;
            height: 100%;
            display: flex;
            align-items: center;
            justify-content: space-between;
            border: 2px solidred;
        }

        .subFriends {
            position: relative;
            width: 550px;
            height: 50%;
        }

        .subFriends::before {
            position: absolute;
            width: 150px;
            height: 100%;
            content: "";
            left: 0;
            top: 0;
            z-index: 99;
            background-image: linear-gradient(90deg, white, transparent);
        }

        .subFriends::after {
            position: absolute;
            width: 150px;
            height: 100%;
            content: "";
            right: 0;
            top: 0;
            z-index: 99;
            background-image: linear-gradient(-90deg, black, transparent);
        }

        .scroll-images {
            width: 100%;
            height: auto;
            display: flex;
            justify-content: left;
            align-items: center;
            overflow: auto;
            position: relative;
            scroll-behavior: smooth;

        }
        .scroll-image{
            width: 100%;
            height: auto;
            display: flex;
            justify-content: left;
            align-items: center;
            overflow: auto;
            position: relative;
            scroll-behavior: smooth;

        }

        .child {
            min-width: 150px;
            height: 150px;
            margin: 1px 20px;
            cursor: pointer;
            border: 1px solid white;
            overflow: hidden;
            border-radius: 50%;
        }
        .child1 {
            min-width: 250px;
            height: 200px;
            margin: 1px 20px;
            cursor: pointer;
            border: 1px solid white;
            overflow: hidden;
            
        }

        .scroll-images::-webkit-scrollbar {
            -webkit-appearance: none;
        }

        .subChild {
            width: 100%;
            height: 100%;
        }

        .icon {
            color: gray;
            background-color: transparent;
            font-size: 50px;
            outline: none;
            border: none;
            cursor: pointer;
        }

        .icon:hover {
            color: yellow;
        }

        .childName {
            color: black;
            text-align: center;
            font-weight: 700;


        }

        .div-content-left {
            background-color: white;
            margin-top: 5px;
            padding: 30px;
            box-shadow: 0 0 1px black;
        }

        .div-content-left h1 {
            margin-top: 15px;
            margin-bottom: 15px;
            font-family: roboto;
        }

        .div-content-left ul li {
            margin-top: 5px;
        }

        .div-content-left ul li a {
            color: blue;
            font-weight: 700;
            font-family: lato;
        }

        .events {
            background: white;
            padding: 10px;
            margin-top: 5px;
            text-align: center;
            box-shadow: 0 0 2px black;
        }

        .event-img img {
            width: 100%;
            margin-top: 10px;
        }

        .event-img-con {
            text-align: center;
        }

        footer {
            width: 100%;
            background-color: black;
            padding: 20px 0;
        }

        .footer-notifications {
            width: 99%;
            margin: auto;
            display: flex;
            background-color: #FBE7A1;
            padding: 20px 0;
            border-radius: 20px;
            margin-bottom: 30px;
        }

        .footerLineLeft {
            width: 40%;
            height: 2px;
            background-color: gray;
            margin-left: 50px;
        }

        .footerLineLeft1 {
            width: 38%;
            height: 2px;
            background-color: gray;
            margin-left: 50px;
        }

        .footerNotification {
            margin: -10px 10px;
        }

        .footerLineRight {
            width: 35%;
            height: 2px;
            background-color: gray;
        }

        .footerLineRight1 {
            width: 33%;
            height: 2px;
            background-color: gray;
        }
        .div-post{
            padding: 10px 25%;            
        }
        .div-post button{
          padding: 5px 13px;
          
        }
    </style>
</head>

<body>
    <!--start header-->
    <header>
        <header>
            <div class="header">
                <div class="headerleft">
                    SENM
                </div>
                <div class="headercenter">
                    <ul>
                        <li><a href="home.html">Home </a> </li>
                        <li><a href="">Group</a> </li>
                        <li><a href="gallery.html">Text Book Center </a></li>
                        <li><a href="">shopping</a></li>
                        <li><a href="">Institutions</a></li>
                    </ul>
                </div>
                <div class="headerright">
                    <div class="div-right">
                        <ul>
                            <li><i class="material-icons" style="font-size:38px;color:white" id="menu-bar">menu</i></li>
                            <li><i class="material-icons" style="font-size:34px;color:white"
                                    id="notification">notifications_active</i></li>
                            <li style="color:white ;">
                                <div class="profile-pic"><img src="./asset1/custom1.png" alt=""></div>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </header>
    <!--end of header-->
    <!--start of main-->
    <main>
        <!--start main left-->
        <div class="main-left">
            <div class="mainsubleft">
                <ul>
                    <li>
                        <div><i class="material-icons" style="font-size:30px;color:navy;">home</i></div>
                        <div class="group" ><a href="" onclick="showPage()"> Home</a></div>
                    </li>
                    <li>
                        <div><i class="material-icons" style="font-size:30px;color:navy;">group_add</i></div>
                        <div class="group" ><a href="" onclick="showPage()"> Class Groups</a></div>
                    </li>
                    <li>
                        <div><i class="material-icons" style="font-size:30px;color:lightgray" id="icons">group_work</i>
                        </div>
                        <div class="group"><a href="">Group Work</a> </div>
                    </li>
                    <li>
                        <div><i class="material-icons" style="font-size:30px;color:rgba(144, 212, 243, 0.507)"
                                id="icons">people</i></div>
                        <div class="group"><a href="">Friends</a></div>
                    </li>
                    <li><i class="fa fa-question-circle" style="font-size:32px;color:goldenrod" id="icons"></i>
                        <div></div>
                        <div class="group"><a href="Qanda.html"> Qestion and Answers</a></div>
                    </li>
                    <li>
                        <div><i class="material-icons" style="font-size:30px;color:black;" id="icons"> share</i></div>
                        <div class="group"><a href="">Share link</a></div>
                    </li>
                    <li>
                        <div style="width:30px;height: 30px;"><img src="./Icon/help.png" alt="" id="img"></div>
                        <div class="group"><a href="">Ask for Help</a> </div>
                    </li>
                    <li>
                        <div style="width:30px;height: 30px;"><img src="./Icon/blog.png" alt="" id="img"></div>
                        <div class="group"><a href="">Add a Blog</a> </div>
                    </li>
                    <li><i class="fa fa-phone-square" style="font-size:33px;color:blue"></i>
                        <div class="group"><a href="">Customer care</a> </div>
                    </li>
                    <li><i class="material-icons" style="font-size:36px;color:green;margin-left: -5px;">message</i>
                        <div class="group"><a href="">Message</a> </div>
                    </li>
                </ul>

            </div>
            <div class="div-content-left">
                <h1> Most Popular Books</h1>
                <ul>
                    <li><a href="">The river between</a></li>
                    <li><a href="">Think like a man act like a woman</a></li>
                    <li><a href="">Pirates of the carebean</a></li>
                    <li><a href="">Sheldon in spineYard</a></li>
                    <li><a href="">Barack Obama biography</a></li>
                </ul>
            </div>
            <div class="div-content-left">
                <i class="fa fa-plus" style="margin-right: 10px;"></i>Create a Club
                <h1> Join Our Club</h1>
                <div class="event-img">
                    <img src="./asset1/qanda-club.jpg" alt="">
                    <div class="event-img-cont">
                        Qanda-Club
                    </div>
                </div>
                <div class="event-img">
                    <img src="./asset1/senm-ches.jpg" alt="">
                    <div class="event-img-cont">
                        SENM-Chess-Club
                    </div>
                </div>

            </div>
        </div>
        <!--end main left-->
        <!--start main center-->
        <div class="main-center-home">
            <div class="searchInput">
                <input type="search" placeholder="Search"><i class="fa fa-search"
                    style="font-size:20px;color:gray;background-color: lightgray;padding: 12.5px;padding-top: 12.5px;border-bottom-right-radius: 45px;border-top-right-radius: 45px;"></i>
            </div>
            <div class="search" id="search">
                <div class="friends">
                    <div style="text-decoration: 3px solid red underline;">Friends</div>
                    <div>Adverts</div>
                    <div>Asignments</div>
                </div>
                <div class="main-scroll-div">
                    <div><button class="icon" onclick="scrolll()"><i class="fa fa-angle-double-left"></i></button></div>
                    <div class="subFriends">
                        <div class="scroll-images">
                            <div class="childNameMain">
                                <li class="child"><img class="subChild" src="./asset1/cust2.png" alt=""></li>
                                <div class="childName">Grace Nyamheya</div>
                            </div>
                            <div class="childNameMain">
                                <li class="child"><img class="subChild" src="./asset1/pasp1.jpg" alt=""></li>
                                <div class="childName">Tony Nesh</div>
                            </div>
                            <div class="childNameMain">
                                <li class="child"><img class="subChild" src="./asset1/pasp2.jpg" alt=""></li>
                                <div class="childName">Joshua Odongo</div>
                            </div>
                            <div class="childNameMain">
                                <li class="child"><img class="subChild" src="./asset1/pasp3.jpg" alt=""></li>
                                <div class="childName">Stanley Livondo</div>
                            </div>
                            <div class="childNameMain">
                                <li class="child"><img class="subChild" src="./asset1/pasp4.jpg" alt=""></li>
                                <div class="childName">Bookaty Nextresa</div>
                            </div>
                            <div class="childNameMain">
                                <li class="child"><img class="subChild" src="./asset1/custom1.png" alt=""></li>
                                <div class="childName">Tim Wanjohi</div>
                            </div>
                            <div class="childNameMain">
                                <li class="child"><img class="subChild" src="./asset1/pasp1.jpg" alt=""></li>
                                <div class="childName">Tony Nesh</div>
                            </div>
                            <div class="childNameMain">
                                <li class="child"><img class="subChild" src="./asset1/pasp1.jpg" alt=""></li>
                                <div class="childName">Tony Nesh</div>
                            </div>
                            <div class="childNameMain">
                                <li class="child"><img class="subChild" src="./asset1/pasp1.jpg" alt=""></li>
                                <div class="childName">Tony Nesh</div>
                            </div>
                            <div class="childNameMain">
                                <li class="child"><img class="subChild" src="./asset1/pasp1.jpg" alt=""></li>
                                <div class="childName">Tony Nesh</div>
                            </div>

                        </div>
                    </div>
                    <div><button class="icon" onclick="scrollr()"><i class="fa fa-angle-double-right"></i></button>
                    </div>
                </div>
            </div>
            <div class="search1" id="search1">
                <div class="friends">
                    <div style="text-decoration: 3px solid green underline;">Groups</div>
                    <div>Adverts</div>
                    <div>Communities</div>
                </div>               
            </div>
            <div class="div-post">
                <label for="post">
                    Ask the world:
                </label> <br>
                <textarea name="post" id="post" cols="30" rows="auto"></textarea>
                <button>Post</button>
            </div>
            <div class="centerHeading">
                <h1>Register with an Institution</h1>
            </div>
            <div class="center">
                <div class="center-images">
                    <div class="institution"><img class="institution-img" src="./asset1/summit.jpg" alt="">
                        <div class="cont">
                            Summit Institute of Professionals
                        </div>
                    </div>
                    <div class="institution"><img class="institution-img" src="./asset1/uon.jpg" alt="">
                        <div class="cont">The University of Nairobi</div>
                    </div>
                    <div class="institution"><img class="institution-img" src="./asset1/Vision.jpg" alt="">
                        <div class="cont">Vision Institute</div>
                    </div>
                    <div class="institution"><img class="institution-img" src="./asset1/KU.jpg" alt="">
                        <div class="cont">Kenyatta University</div>
                    </div>
                    <div class="institution"><img class="institution-img" src="./asset1/mku.jpg" alt="">
                        <div class="cont">Mt Kenya University</div>
                    </div>
                    <div class="institution"><img class="institution-img" src="./asset1/strath.jpg" alt="">
                        <div class="cont">Stratmore University</div>
                    </div>
                </div>
            </div>
           
        </div>
        <!--end main center-->
        <!--start main right-->
        <div class="main-right">
            <div class="mainSubRight">
                <select name=" id="" >
            <option value=" 0">Select Institution</option>
                    <option value="">Summit Institute</option>
                    <option value="">Vision Institute</option>
                    <option value="">Strathmore</option>
                    <option value="">The University of Nairobi</option>
                    <option value=""></option>
                    <option value=""></option>
                    <option value=""></option>
                    <option value=""></option>
                    <option value=""></option>
                    <option value=""></option>
                    <option value=""></option>
                    <option value=""></option>
                    <option value=""></option>
                    <option value=""></option>
                    <option value=""></option>
                    <option value=""></option>
                    <option value=""></option>
                    <option value=""></option>
                    <option value=""></option>
                    <option value=""></option>
                    <option value=""></option>
                    <option value=""></option>
                    <option value=""></option>
                    <option value=""></option>
                    <option value=""></option>
                    <option value=""></option>
                    <option value=""></option>
                    <option value=""></option>
                    <option value=""></option>
                </select>
            </div>
            <div class="rightLogin">
                <h2>Log in :</h2>
                <input type="email" placeholder="email :"> <br> <br>
                <input type="password" placeholder="password :"> <br> <br>
                <input type="submit" value="login" style="width: 100px;"> <br> <br>
                <h2><a href="" id="register"> Register here :</a></h2>
            </div>
            <div class="events">
                <h1>Recent Events</h1>
                <div class="event-img">
                    <img src="./asset1/education-event.jpg" alt="">
                    <div class="event-img-cont">
                        Top Educational Events in Kenya
                    </div>
                </div>
                <div class="event-img">
                    <img src="./asset1/rural-img.jpg" alt="">
                    <div class="event-img-cont">
                        Rural Social Educational Program.
                    </div>
                </div>
            </div>
        </div>
        <!--end main right-->
    </main>
    <!--End of Main-->
    <!--StartFooter-->
    <footer>
        <div class="footer-notifications">
            <div class="footerLineLeft"></div>
            <div class="footerNotification"> <strong> Notifications</strong> </div>
            <div class="footerLineRight"></div>
        </div>
        <div class="footer-notifications">
            <div class="footerLineLeft"></div>
            <div class="footerNotification"><strong> Contact Us</strong> </div>
            <div class="footerLineRight"></div>
        </div>
        <div class="footer-notifications">
            <div class="footerLineLeft1"></div>
            <div class="footerNotification"><strong> Terms & Conditions</strong> </div>
            <div class="footerLineRight1"></div>
        </div>
    </footer>
    <script>
      function showPage(){
  const x = document.getElementById("search1").style.display='block'
  const y = document.getElementById("search").style.display='none';
  if (y.style.display === "none") {
      x.style.display = "block"
    } 
  else {
    y.style.display = "block";
  }
}
        function scrolll() {
            var left = document.querySelector(".scroll-images");
            left.scrollBy(350, 0)
        }
        function scrollr() {
            var right = document.querySelector(".scroll-images");
            right.scrollBy(-350, 0)
        }
        function scrollll() {
            var left = document.querySelector(".scroll-image");
            left.scrollBy(350, 0)
        }
        function scrolllr() {
            var right = document.querySelector(".scroll-image");
            right.scrollBy(-350, 0)
        }
    </script>
</body>

</html>
 <!--End of home page-->
 <!--Start of Institutions-->
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
   <link rel="stylesheet" href="style.css">
   <link rel="stylesheet" href="moreStyle.css">
</head>
<body>
    <header>
        <div class="header">
            <div class="headerleft">
                QANDA
            </div>
            <div class="headercenter">
                <ul>
                    <li><a href="home.html">Home </a> </li>
                    <li><a href="">Group</a> </li>
                    <li><a href="gallery.html">Text Book Center </a></li>
                    <li><a href="">shopping</a></li>
                    <li><a href="">Institutions</a></li>
                </ul>
            </div>
            <div class="headerright">
                <div class="div-right">
                    <ul>
                        <li><i class="material-icons" style="font-size:38px;color:white" id="menu-bar">menu</i></li>
                        <li><i class="material-icons" style="font-size:34px;color:white"
                                id="notification">notifications_active</i></li>
                        <li style="color:white ;">
                            <div class="profile-pic"><img src="./asset1/custom1.png" alt="">ladman</div>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </header>
    <!--end of header-->
    <div class="qanda-body">
   <div class="qanda-nav">
    <h1><span> Question & Answers</span></h1>  
   </div>   
  <div class="qanda-select">
    <h2>Choose your Institution</h2>
  </div>
   <div class="qanda-institutions">      
    <div><a href="cpa.html">CPA, </a> </div>
    <div><a href="">ATD, </a> </div>
    <div><a href="cams.html">CAMS,</a>  </div>
    <div><a href="">DICT,</a>  </div>
    <div><a href="">DCM, </a> </div>
    <div><a href="">CS,</a></div>
    <div><a href="">CIFA,  </a>  </div>
    <div><a href="">CICT, </a>  </div>
    <div><a href="">CCP, </a> </div>
    <div><a href="">KISME,</a></div>
    <div><a href="uon.html">UON, </a> </div>
    <div><a href="">KU,</a></div>
    <div><a href="">MKU,</a> </div>
    <div><a href="nazarene.html">NAZARINE,</a></div>
    <div><a href="">DAYSTER,</a></div>
    <div><a href="">USIU,</a></div>
    <div><a href="">MASENO, </a></div>
    <div><a href="">NAIROBI AVIATION,</a></div>
    <div><a href="">KENYA POLYTECHNIQUE,</a></div>
    <div><a href="">EGERTON,</a></div>
    <div><a href="">MOI UNIVERSITY,</a></div>
    <div><a href="">MASINDE MULIRO,</a></div>
    <div><a href="">RONGO UNIVERSITY,   </a></div>
    <div><a href="">STRATHMORE</a></div>
   </div>
</div>
</body>
</html>
<!--End of Institutions-->
<!--Start of CPA-->
<!DOCTYPE html>
<html lang="en">

<head>
        <meta charset="UTF 8">
        <meta http equiv="X UA Compatible" content="IE=edge">
        <meta name="viewport" content="width=device width, initial scale=1.0">
        <title>Q&A</title>
        <link rel="stylesheet" href="style.css">
        <link rel="stylesheet"
                href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
        <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
        <link rel="stylesheet"
                href="https://cdnjs.cloudflare.com/ajax/libs/font awesome/4.7.0/css/font awesome.min.css">
        <script src="https://kit.fontawesome.com/yourcode.js" crossorigin="anonymous"></script>
        <style>
                body {
                        background: rgba(0, 0, 0, 0.7);
                }

                p {
                        font-size: 20px;
                        padding: 40px;
                }

                #list {
                        display: none;
                        margin-left: 15px;
                }

                h4 {
                        display: none;
                        padding-right: 50px;
                }

                #searchbar {
                        margin-left: 7%;
                }

                #submit {
                        width: 150px;
                        font-size: 18px;
                        background-color: rgba(0,0,139,0.5);
                        padding: 10px;
                        color: white;
                        border-radius: 5px;
                        cursor: pointer;
                }
                #submit:hover{background: rgba(220,20,60,0.5);}
                .div-main {
                        min-height: 87vh;
                 background-image: linear-gradient(rgba(0,0,0,.7),rgba(0,0,0,.7),rgba(0,0,0)),url(./images/kasneb.png);background-repeat: no-repeat;background-size: 100% 100%;
                }
                .div-main ul li {
                        padding-left: 75px;
                        color: white;
                }

                input {
                        width: 60%;
                        font-size: 18px;
                        background-color: rgba(240,248,255,0.5);
                        padding: 10px;


                }

                .img{display: none;}

                button {
                        font-size: 18px;
                        padding: 7px;
                        cursor: pointer;                
                        margin: 5px;
                        background: rgba(240,248,255,0.4);
                        border-radius: 3px;
                }

                button:hover{background-color: rgba(0, 0, 0, 0.7);color: white;}

                .cpa{margin-top: 30px;}
                .div-cpa {
                        text-align: center;
                        color: gold;
                }

                .div-cpa h1 {
                       
                        font-size: 60px;
                }
        </style>
</head>

<body>
        <header>
                <div class="header">
                        <div class="headerleft">
                                QANDA
                        </div>
                        <div class="headercenter">
                                <ul>
                                        <li><a href="home.html">Home </a> </li>
                                        <li><a href="">Group</a> </li>
                                        <li><a href="books.html">Text Book Center </a></li>
                                        <li><a href="">Shopping</a></li>
                                        <li><a href="">Institutions</a></li>
                                </ul>
                        </div>
                        <div class="headerright">
                                <div class="div-right">
                                        <ul>
                                                <li><a href="home.html"> <i class="material-icons" style="font-size:38px;color:white"
                                                                id="menu-bar">menu</i></a></li>
                                                <li><i class="material-icons" style="font-size:34px;color:white"
                                                                id="notification">notifications_active</i></li>
                                                <li class="profile-pic-out" style="color:white;"><a href="">
                                                        <div class="profile-pic"><img src="./asset1/custom1.png"
                                                                        alt=""></div>
                                                        <div class="div-out">Logout</div> </a>

                                                </li>
                                        </ul>

                                </div>
                        </div>
                </div>
        </header>
        <main>
                <div class="div-main">
                        <div class="div-cpa">
                                <h1>CPA</h1>
                        </div>
                        <p>
                                Put the unit i.e Advanced Management Accounting and scroll to your question or seive
                                your specific Question in the following Format..
                                <strong>Unit(Advanced Management Accounting) month(Nov) Year(2020)
                                        Question(Question)Number(i.e 1),letter(i.e a),roman in bracket(i.e (ii))..
                                </strong>
                        </p>
                        <input type="text" id="searchbar" name="search" placeholder="Format i.e 2020 nov q1a(ii)">
                        <input type="submit" onclick="showPage(onclick)" id="submit">
                        <button id="button" onclick="window.location.reload()">clear</button>
                        
                        <!-- input=id-->
                        <!-- id=what to display-->
                        <!--input=what to display-->
                        <ul id="list">
                                <li class="cpa">Advanced Management Accounting Nov 2022 Question one<h1>(b) Circumstances that may potentially threaten the professional accountant’s compliance with the
                                        fundamental principles of ethics</h1>
                                    <button data-page1="page1" >Answer</button><div class="img" id="page1">  i) They provide a useful means for users to evaluate the overall impact of the organization to the
                                        whole community for users to make additional judgment on the performance and impact of the
                                        organization.<br>
                                        ii) They enable the organization to behave responsibly to the society and the environment by
                                        ensuring that it is accountable in its reporting<br>
                                        iii) They enhance the reputation of the firm in the eyes of the society
                                        iv) It gives the information to assess the effectiveness of the programs on ecology and community
                                        development.<br>
                                        v) The managers try to focus their attention on those activities where reports and evaluations are
                                        necessary.<br>
                                        vi) It provides information that allows management to compare the effectiveness of different social
                                        programs.<br>
                                        vii) It gives the right to manage and provide information to external groups that rely on the company
                                       requirements for social performance </div></li>
                                <li class="cpa">Advanced Management Accounting Nov 2022 Question two<h1>(d) Benefits an organization will derive from providing social and environmental reports.</h1>
                                    <button data-page1="page2" >Answer</button><div class="img" id="page2"> i) They provide a useful means for users to evaluate the overall impact of the organization to the
                                        whole community for users to make additional judgment on the performance and impact of the
                                        organization.<br>
                                        ii) They enable the organization to behave responsibly to the society and the environment by
                                        ensuring that it is accountable in its reporting<br>
                                        iii) They enhance the reputation of the firm in the eyes of the society
                                        iv) It gives the information to assess the effectiveness of the programs on ecology and community
                                        development.<br>
                                        v) The managers try to focus their attention on those activities where reports and evaluations are
                                        necessary.<br>
                                        vi) It provides information that allows management to compare the effectiveness of different social
                                        programs.<br>
                                        vii) It gives the right to manage and provide information to external groups that rely on the company
                                       requirements for social performance</div></li>
                                <li class="cpa">Advanced Management Accounting Nov 2022 Question three <h1> </h1>
                                    <button data-page1="page3" >Answer</button><div class="img" id="page3"></div>
                                </li>
                                <li class="cpa">Advanced Management Accounting Nov 2022 Question four<h1></h1>
                                    <button data-page1="page4" >Answer</button><div class="img" id="page4"> </div></li>
                                <li class="cpa">Advanced Management Accounting Nov 2022 Question five<h1></h1>
                                    <button data-page1="page5" >Answer</button><div class="img" id="page5"> </div></li>
                                <li class="cpa">Advanced Management Accounting Aug 2022 Question one<h1></h1>
                                    <button data-page1="page6" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Aug 2022 Question two<h1></h1>
                                    <button data-page1="page7" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Aug 2022 Question three<h1></h1>
                                    <button data-page1="page8" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Aug 2022 Question four<h1></h1>
                                    <button data-page1="page9" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Aug 2022 Question one<h1></h1>
                                    <button data-page1="page10" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Apr 2022 Question two<h1></h1>
                                    <button data-page1="page11" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Apr 2022 Question three<h1></h1>
                                    <button data-page1="page12" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Apr 2022 Question four<h1></h1>
                                    <button data-page1="page13" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Apr 2022 Question five<h1></h1>
                                    <button data-page1="page14" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Aug 2021 Question one<h1></h1>
                                    <button data-page1="page15" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Aug 2021 Question two<h1></h1>
                                    <button data-page1="page16" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Aug 2021 Question three<h1></h1>
                                    <button data-page1="page17" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Aug 2021 Question four<h1></h1>
                                    <button data-page1="page18" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Aug 2021 Question five<h1></h1>
                                    <button data-page1="page19" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Nov 2021 Question one<h1></h1>
                                    <button data-page1="page20" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Nov 2021 Question two<h1></h1>
                                    <button data-page1="page21" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Nov 2021 Question three<h1></h1>
                                    <button data-page1="page22" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Nov 2021 Question four<h1></h1>
                                    <button data-page1="page23" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Nov 2021 Question five<h1></h1>
                                    <button data-page1="page24" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Apr 2021 Question one<h1></h1>
                                    <button data-page1="page25" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Apr 2021 Question two<h1></h1>
                                    <button data-page1="page26" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Apr 2021 Question three<h1></h1>
                                    <button data-page1="page27" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Apr 2021 Question four<h1></h1>
                                    <button data-page1="page28" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Apr 2021 Question five<h1></h1>
                                    <button data-page1="page29" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Nov 2020 Question one<h1></h1>
                                    <button data-page1="page30" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Nov 2020 Question two<h1></h1>
                                    <button data-page1="page31" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Nov 2020 Question three<h1></h1>
                                    <button data-page1="page32" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Nov 2020 Question four<h1></h1>
                                    <button data-page1="page33" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Nov 2020 Question five<h1></h1>
                                    <button data-page1="page34" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting May 2019 Question one<h1></h1>
                                    <button data-page1="page35" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting May 2019 Question two<h1></h1>
                                    <button data-page1="page36" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting May 2019 Question three<h1></h1>
                                    <button data-page1="page37" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting May 2019 Question four<h1></h1>
                                    <button data-page1="page38" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting May 2019 Question five<h1></h1>
                                    <button data-page1="page39" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting May 2019 Question one<h1></h1>
                                    <button data-page1="page40" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Nov 2019 Question two<h1></h1>
                                    <button data-page1="page41" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Nov 2019 Question three<h1></h1>
                                    <button data-page1="page42" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Nov 2019 Question four<h1></h1>
                                    <button data-page1="page43" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Nov 2019 Question five<h1></h1>
                                    <button data-page1="page44" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting May 2018 Question one<h1></h1>
                                    <button data-page1="page45" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting May 2018 Question two<h1></h1>
                                    <button data-page1="page46" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting May 2018 Question three<h1></h1>
                                    <button data-page1="page47" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting May 2018 Question four<h1></h1>
                                    <button data-page1="page48" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting May 2018 Question five<h1></h1>
                                    <button data-page1="page49" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Nov 2018 Question one<h1></h1>
                                    <button data-page1="page50" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Nov 2018 Question two<h1></h1>
                                    <button data-page1="page51" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Nov 2018 Question three<h1></h1>
                                    <button data-page1="page52" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Nov 2018 Question four<h1></h1>
                                    <button data-page1="page53" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Nov 2018 Question five<h1></h1>
                                    <button data-page1="page54" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Dec 2017 Question one<h1></h1>
                                    <button data-page1="page55" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Dec 2017 Question two<h1></h1>
                                    <button data-page1="page56" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Dec 2017 Question three<h1></h1>
                                    <button data-page1="page57" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Dec 2017 Question four<h1></h1>
                                    <button data-page1="page58" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Dec 2017 Question five<h1></h1>
                                    <button data-page1="page59" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting May 2017 Question one<h1></h1>
                                    <button data-page1="page60" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting May 2017 Question two<h1></h1>
                                    <button data-page1="page61" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting May 2017 Question three<h1></h1>
                                    <button data-page1="page62" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting May 2017 Question four<h1></h1>
                                    <button data-page1="page63" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting May 2017 Question five<h1></h1>
                                    <button data-page1="page64" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting May 2016 Question one<h1></h1>
                                    <button data-page1="page65" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting May 2016 Question two<h1></h1>
                                    <button data-page1="page66" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting May 2016 Question three<h1></h1>
                                    <button data-page1="page67" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting May 2016 Question four<h1></h1>
                                    <button data-page1="page68" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting May 2016 Question five<h1></h1>
                                    <button data-page1="page69" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Nov 2016 Question one<h1></h1>
                                    <button data-page1="page70" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Nov 2016 Question two<h1></h1>
                                    <button data-page1="page71" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Nov 2016 Question three<h1></h1>
                                    <button data-page1="page72" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Nov 2016 Question four<h1></h1>
                                    <button data-page1="page73" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Nov 2016 Question five<h1></h1>
                                    <button data-page1="page74" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Pilot 2015 Question one<h1></h1>
                                    <button data-page1="page75" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Pilot 2015 Question two<h1></h1>
                                    <button data-page1="page76" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Pilot 2015 Question three<h1></h1>
                                    <button data-page1="page77" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Pilot 2015 Question four<h1></h1>
                                    <button data-page1="page78" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Pilot 2015 Question fiv<h1></h1>
                                    <button data-page1="page79" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Nov 2015 Question one<h1></h1>
                                    <button data-page1="page80" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Nov 2015 Question two<h1></h1>
                                    <button data-page1="page81" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Nov 2015 Question three<h1></h1>
                                    <button data-page1="page82" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Nov 2015 Question four<h1></h1>
                                    <button data-page1="page83" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting Nov 2015 Question five<h1></h1>
                                    <button data-page1="page84" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting May 2015 Question one<h1></h1>
                                    <button data-page1="page85" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting May 2015 Question two<h1></h1>
                                    <button data-page1="page86" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting May 2015 Question three<h1></h1>
                                    <button data-page1="page87" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting May 2015 Question four<h1></h1>
                                    <button data-page1="page88" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting May 2015 Question five<h1></h1>
                                    <button data-page1="page89" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting 2014 Nov Question one<h1></h1>
                                    <button data-page1="page90" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting 2014 Nov Question two<h1></h1>
                                    <button data-page1="page91" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting 2014 Nov Question three<h1></h1>
                                    <button data-page1="page92" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting 2014 Nov Question four<h1></h1>
                                    <button data-page1="page93" >Answer</button><div class="img" id="page2"> </div></li>
                                <li class="cpa">Advanced Management Accounting 2014 Nov Question five<h1></h1>
                                    <button data-page1="page94">Answer</button>
                                    <div class="img" id="page94"> </div>
                                </li>
                                <li class="cpa">Advanced Management Accounting 2014 May Question one<h1></h1>
                                    <button data-page1="page95">Answer</button>
                                    <div class="img" id="page95"> </div>
                                </li>
                                <li class="cpa">Advanced Management Accounting 2014 May Question two<h1></h1>
                                    <button data-page1="page96">Answer</button>
                                    <div class="img" id="page96"> </div>
                                </li>
                                <li class="cpa">Advanced Management Accounting 2014 May Question three<h1></h1>
                                    <button data-page1="page97">Answer</button>
                                    <div class="img" id="page97"> </div>
                                </li>
                                <li class="cpa">Advanced Management Accounting 2014 May Question four<h1></h1>
                                    <button data-page1="page98">Answer</button>
                                    <div class="img" id="page98"> </div>
                                </li>
                                <li class="cpa">Advanced Management Accounting 2014 May Question five<h1></h1>
                                    <button data-page1="page99">Answer</button>
                                    <div class="img" id="page99"> </div>
                                </li>
                                <li class="cpa">Advanced Management Accounting 2013 Nov Question one<h1></h1>
                                    <button data-page1="page100">Answer</button>
                                    <div class="img" id="page100"> </div>
                                </li>
                                <li class="cpa">Advanced Management Accounting 2013 Nov Question two<h1></h1>
                                    <button data-page1="page101">Answer</button>
                                    <div class="img" id="page102"> </div>
                                </li>
                                <li class="cpa">Advanced Management Accounting 2013 Nov Question three<h1></h1>
                                    <button data-page1="page103">Answer</button>
                                    <div class="img" id="page103"> </div>
                                </li>
                                <li class="cpa">Advanced Management Accounting 2013 Nov Question four<h1></h1>
                                    <button data-page1="page104">Answer</button>
                                    <div class="img" id="page104"> </div>
                                </li>
                                <li class="cpa">Advanced Management Accounting 2013 Nov Question five<h1></h1>
                                    <button data-page1="page105">Answer</button>
                                    <div class="img" id="page105"> </div>
                                </li>
                                <li class="cpa">Advanced Management Accounting 2013 May Question one<h1></h1>
                                    <button data-page1="page106">Answer</button>
                                    <div class="img" id="page106"> </div>
                                </li>
                                <li class="cpa">Advanced Management Accounting 2013 May Question two<h1></h1>
                                    <button data-page1="page107">Answer</button>
                                    <div class="img" id="page107"> </div>
                                </li>
                                <li class="cpa">Advanced Management Accounting 2013 May Question three<h1></h1>
                                    <button data-page1="page108">Answer</button>
                                    <div class="img" id="page108"> </div>
                                </li>
                                <li class="cpa">Advanced Management Accounting 2013 May Question four<h1></h1>
                                    <button data-page1="page109">Answer</button>
                                    <div class="img" id="page109"> </div>
                                </li>
                                <li class="cpa">Advanced Management Accounting 2013 May Question five<h1></h1>
                                    <button data-page1="page110">Answer</button>
                                    <div class="img" id="page110"> </div>
                                </li>
                                <li class="cpa">Advanced Management Accounting 2012 Nov Question one<h1></h1>
                                    <button data-page1="page111">Answer</button>
                                    <div class="img" id="page111"> </div>
                                </li>
                                <li class="cpa">Advanced Management Accounting 2012 Nov Question two<h1></h1>
                                    <button data-page1="page112">Answer</button>
                                    <div class="img" id="page112"> </div>
                                </li>
                                <li class="cpa">Advanced Management Accounting 2012 Nov Question three<h1></h1>
                                    <button data-page1="page113">Answer</button>
                                    <div class="img" id="page113"> </div>
                                </li>
                                <li class="cpa">Advanced Management Accounting 2012 Nov Question four<h1></h1>
                                    <button data-page1="page114">Answer</button>
                                    <div class="img" id="page114"> </div>
                                </li>
                                <li class="cpa">Advanced Management Accounting 2012 Nov Question five<h1></h1>
                                    <button data-page1="page115">Answer</button>
                                    <div class="img" id="page115"> </div>
                                </li>
                                <li class="cpa">Advanced Management Accounting 2012 May Question one<h1></h1>
                                    <button data-page1="page116">Answer</button>
                                    <div class="img" id="page116"> </div>
                                </li>
                                <li class="cpa">Advanced Management Accounting 2012 May Question two<h1></h1>
                                    <button data-page1="page117">Answer</button>
                                    <div class="img" id="page117"> </div>
                                </li>
                                <li class="cpa">Advanced Management Accounting 2012 May Question three<h1></h1>
                                    <button data-page1="page118">Answer</button>
                                    <div class="img" id="page118"> </div>
                                </li>
                                <li class="cpa">Advanced Management Accounting 2012 May Question four<h1></h1>
                                    <button data-page1="page119">Answer</button>
                                    <div class="img" id="page119"> </div>
                                </li>
                                <li class="cpa">Advanced Management Accounting 2012 May Question five<h1></h1>
                                    <button data-page1="page120">Answer</button>
                                    <div class="img" id="page120"> </div>
                                </li>
                                <li class="cpa">Advanced Management Accounting 2011 Nov Question one<h1></h1>
                                    <button data-page1="page121">Answer</button>
                                    <div class="img" id="page121"> </div>
                                </li>
                                <li class="cpa">Advanced Management Accounting 2011 Nov Question two<h1></h1>
                                    <button data-page1="page122">Answer</button>
                                    <div class="img" id="page122"> </div>
                                </li>
                                <li class="cpa">Advanced Management Accounting 2011 Nov Question three<h1></h1>
                                    <button data-page1="page123">Answer</button>
                                    <div class="img" id="page123"> </div>
                                </li>
                                <li class="cpa">Advanced Management Accounting 2011 Nov Question four<h1></h1>
                                    <button data-page1="page124">Answer</button>
                                    <div class="img" id="page124"> </div>
                                </li>
                                <li class="cpa">Advanced Management Accounting 2011 Nov Question five<h1></h1>
                                    <button data-page1="page125">Answer</button>
                                    <div class="img" id="page125"> </div>
                                </li>
                                <li class="cpa">Advanced Management Accounting 2011 May Question one<h1></h1>
                                    <button data-page1="page126">Answer</button>
                                    <div class="img" id="page126"> </div>
                                </li>
                                <li class="cpa">Advanced Management Accounting 2011 May Question two<h1></h1>
                                    <button data-page1="page127">Answer</button>
                                    <div class="img" id="page127"> </div>
                                </li>
                                <li class="cpa">Advanced Management Accounting 2011 May Question three<h1></h1>
                                    <button data-page1="page128">Answer</button>
                                    <div class="img" id="page128"> </div>
                                </li>
                                <li class="cpa">Advanced Management Accounting 2011 May Question four<h1></h1>
                                    <button data-page1="page129">Answer</button>
                                    <div class="img" id="page129"> </div>
                                </li>
                                <li class="cpa">Advanced Management Accounting 2011 May Question five<h1></h1>
                                    <button data-page1="page130">Answer</button>
                                    <div class="img" id="page130"> </div>
                                </li>
                                <!--End AMA-->
                                <!--Start AFR-->
                                <li class="cpa">Advanced Financial Reporting 2022 Nov Question one<h1></h1>
                                    <button data-page1="page131">Answer</button>
                                    <div class="img" id="page131"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2022 Nov Question two<h1></h1>
                                    <button data-page1="page132">Answer</button>
                                    <div class="img" id="page132"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2022 Nov Question three<h1></h1>
                                    <button data-page1="page133">Answer</button>
                                    <div class="img" id="page133"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2022 Nov Question four<h1></h1>
                                    <button data-page1="page133">Answer</button>
                                    <div class="img" id="page133"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2022 Nov Question five<h1></h1>
                                    <button data-page1="page134">Answer</button>
                                    <div class="img" id="page134"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2022 Aug Question one<h1></h1>
                                    <button data-page1="page135">Answer</button>
                                    <div class="img" id="page135"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2022 Aug Question two<h1></h1>
                                    <button data-page1="page136">Answer</button>
                                    <div class="img" id="page136"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2022 Aug Question three<h1></h1>
                                    <button data-page1="page137">Answer</button>
                                    <div class="img" id="page137"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2022 Aug Question four<h1></h1>
                                    <button data-page1="page138">Answer</button>
                                    <div class="img" id="page138"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2022 Aug Question one<h1></h1>
                                    <button data-page1="page139">Answer</button>
                                    <div class="img" id="page139"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2022 Apr Question two<h1></h1>
                                    <button data-page1="page140">Answer</button>
                                    <div class="img" id="page140"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2022 Apr Question three<h1></h1>
                                    <button data-page1="page141">Answer</button>
                                    <div class="img" id="page141"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2022 Apr Question four<h1></h1>
                                    <button data-page1="page142">Answer</button>
                                    <div class="img" id="page142"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2022 Apr Question five<h1></h1>
                                    <button data-page1="pag143">Answer</button>
                                    <div class="img" id="page143"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2021 Aug Question one<h1></h1>
                                    <button data-page1="page144">Answer</button>
                                    <div class="img" id="page144"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2021 Aug Question two<h1></h1>
                                    <button data-page1="page145">Answer</button>
                                    <div class="img" id="page145"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2021 Aug Question three<h1></h1>
                                    <button data-page1="page146">Answer</button>
                                    <div class="img" id="page146"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2021 Aug Question four<h1></h1>
                                    <button data-page1="page147">Answer</button>
                                    <div class="img" id="page147"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2021 Aug Question five<h1></h1>
                                    <button data-page1="page148">Answer</button>
                                    <div class="img" id="page148"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2021 Nov Question one<h1></h1>
                                    <button data-page1="page149">Answer</button>
                                    <div class="img" id="page149"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2021 Nov Question two<h1></h1>
                                    <button data-page1="page150">Answer</button>
                                    <div class="img" id="page150"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2021 Nov Question three<h1></h1>
                                    <button data-page1="page151">Answer</button>
                                    <div class="img" id="page151"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2021 Nov Question four<h1></h1>
                                    <button data-page1="page152">Answer</button>
                                    <div class="img" id="page152"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2021 Nov Question five<h1></h1>
                                    <button data-page1="page153">Answer</button>
                                    <div class="img" id="page153"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2021 Apr Question one<h1></h1>
                                    <button data-page1="page154">Answer</button>
                                    <div class="img" id="page154"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2021 Apr Question two<h1></h1>
                                    <button data-page1="page155">Answer</button>
                                    <div class="img" id="page155"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2021 Apr Question three<h1></h1>
                                    <button data-page1="page156">Answer</button>
                                    <div class="img" id="page156"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2021 Apr Question four<h1></h1>
                                    <button data-page1="page157">Answer</button>
                                    <div class="img" id="page157"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2021 Apr Question five<h1></h1>
                                    <button data-page1="page158">Answer</button>
                                    <div class="img" id="page158"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2020 Nov Question one A <h1></h1>
                                    <button data-page1="page159">Answer</button>
                                    <div class="img" id="page159"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2020 Nov Question oneb <h1>(b) Circumstances that may potentially threaten the professional accountant’s compliance with the
                                    fundamental principles of ethics</h1>
                                    <button data-page1="page160">Answer</button>
                                    <div class="img" id="page160">i) Self-Interest Threat – The threat that a financial or other interest or of immediate or close
                                        family will inappropriately influence the professional accountant’s judgment or behaviour. <br>
                                        ii) Self-Review Threat – The threat that a professional accountant will not appropriately evaluate
                                        the results of a previous judgment made or service performed by the professional accountant, or
                                        by another individual within the professional accountant’s firm or employing organisation, on
                                        which the accountant will rely when forming a judgment as part of providing a current service.<br>
                                        iii) Advocacy Threat – The threat that a professional accountant will promote a client’s or
                                        employer’s position to the point that the professional accountant’s objectivity is compromised.<br>
                                        iv) Familiarity Threat ─ The threat that due to a long or close relationship with a client or
                                        employer, a professional accountant will be too sympathetic to their interests or too accepting of
                                        their work.<br>
                                        v) Intimidation Threat – The threat that a professional accountant will be deterred from acting
                                        objectively because of actual or perceived pressures, including attempts to exercise undue
                                        influence over the professional accountant.
                                    </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2020 Nov Question oned
                                    <h1>(d) Benefits an organization will derive from providing social and environmental reports.</h1>
                                    <button data-page1="page161">Answer</button>
                                    <div class="img" id="page161">
                                        i) They provide a useful means for users to evaluate the overall impact of the organization to the
                                        whole community for users to make additional judgment on the performance and impact of the
                                        organization.<br>
                                        ii) They enable the organization to behave responsibly to the society and the environment by
                                        ensuring that it is accountable in its reporting<br>
                                        iii) They enhance the reputation of the firm in the eyes of the society
                                        iv) It gives the information to assess the effectiveness of the programs on ecology and community
                                        development.<br>
                                        v) The managers try to focus their attention on those activities where reports and evaluations are
                                        necessary.<br>
                                        vi) It provides information that allows management to compare the effectiveness of different social
                                        programs.<br>
                                        vii) It gives the right to manage and provide information to external groups that rely on the company
                                       requirements for social performance
                                    </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2020 Nov Question two A<h1></h1>
                                    <button data-page1="page162">Answer</button>
                                    <div class="img" id="page162"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2020 Nov Question 3b<h1></h1>
                                    <button data-page1="page163">Answer</button>
                                    <div class="img" id="page163"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2020 Nov Question 4a<h1></h1>
                                    <button data-page1="page164">Answer</button>
                                    <div class="img" id="page164"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2020 Nov Question 4B<h1></h1>
                                    <button data-page1="page165">Answer</button>
                                    <div class="img" id="page165"><img src="afrnov204b.png"></div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2020 Nov Question four<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2020 Nov Question five<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2019 May Question 1a<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2019 May Question 1b<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2019 May Question 1c<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2019 May Question 1d<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2019 May Question two<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2019 May Question 3a<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2019 May Question 4a<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2019 May Question five<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2019 May Question one<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2019 Nov Question 2a<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2019 Nov Question three<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2019 Nov Question 3a<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2019 Nov Question four<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2019 Nov Question five<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2018 May Question one<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2018 May Question two<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2018 May Question three<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2018 May Question four<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2018 May Question five<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2018 May Question one<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2018 Nov Question two<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2018 Nov Question 3a<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2018 Nov Question four<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2018 Nov Question 5a<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2018 Nov Question 5b<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2017 May Question one<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2017 May Question two<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2017 May Question three<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2017 May Question four<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2017 May Question five<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2017 May Question one<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2017 Nov Question two<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2017 Nov Question three<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2017 Nov Question four<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2017 Nov Question five<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                    
                                <li class="cpa">Advanced Financial Reporting 2016 May Question one<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2016 May Question two<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2016 May Question three<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2016 May Question four<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2016 May Question five<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2016 May Question one<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2016 Nov Question two<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2016 Nov Question three<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2016 Nov Question four<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2016 Nov Question five<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                    
                                <li class="cpa">Advanced Financial Reporting 2015 May Question one<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2015 May Question two<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2015 May Question three<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2015 May Question four<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2015 May Question five<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2015 May Question one<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2015 Nov Question two<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2015 Nov Question three<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2015 Nov Question four<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                                <li class="cpa">Advanced Financial Reporting 2015 Nov Question five<h1></h1>
                                    <button data-page1="page2">Answer</button>
                                    <div class="img" id="page2"> </div>
                                </li>
                            </ul>
                    
                        <div class="div-back"><a href="Qanda.html">
                                <div class="div-img-back"><img src="./Icon/back.png" alt=""></div>
                                <div class="back">Back</div>
                        </a> </div>

                </div>
                
        </main>

        <script>
                function showPage(onclick) {
                        let input = document.getElementById('searchbar').value
                        input = input.toLowerCase();
                        let x = document.getElementsByClassName('cpa');
                        for (i = 0; i < x.length; i++) {
                                if (!x[i].innerHTML.toLowerCase().includes(input)) {
                                        list.style.display = 'block';
                                        x[i].style.display = 'none'
                                }

                        }
                }
                function showPage1(page1) {
        document.querySelectorAll('.img').forEach(img => {
            img.style.display = 'none';
        })

        document.getElementById(page1).style.display = 'block';
    }
   
        document.querySelectorAll('button').forEach(button => {
            button.onclick = function () {
                showPage1(this.dataset.page1);
                
            }
            
       
    });
        </script>
</body>

</html>
<!--End of CPA-->
<!--style.css-->
@import url('https://fonts.googleapis.com/css2?family=Heebo:wght@100&family=Lato:wght@100&family=Oswald:wght@200&family=Roboto:wght@100&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;900&display=swap');

* {
    font-family: sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    outline: none;
    border: none;
    text-decoration: none;
    list-style: none;
    text-decoration: none;
}

.container {
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 20px;
    padding-bottom: 60px;

}

.container .content {
    text-align: center;
}

.container .content h3 {
    font-size: 30px;
    color: #333;
}

.container .content h1 span {
    color: gray;
    text-decoration: beige underline;
}

.container .content h3 span {
    background-color: orangered;
    color: white;
    border-radius: 5px;
    padding: 0 15px;
}

.container .content p {
    font-size: 25px;
    margin-bottom: 20px;
}

.container .content p strong {
    color: green;
}

.container .content .btn {
    display: inline-block;
    padding: 10px 30px;
    font-size: 20px;
    background: #333;
    color: #fff;
    margin: 0 5px;
    border-radius: 45px;
}

.container .content .btn:hover {
    background: darkblue;
}

.form-container {
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 20px;
    padding-bottom: 60px;
    background-image: linear-gradient(rgba(0, 0, 0, .7), rgba(0, 0, 0, .7)), url(./images/books.avif);
    background-repeat: no-repeat;
    background-size: 100% 100%;
}

.form-container form {
    width: 50%;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0 5px 10px rgba(0, 0, 0, 0.1);
    background: rgba(0, 0, 0, .4);
    text-align: center;
    box-shadow: 0 0 5px lightblue;
}

.form-container form h3 {
    font-size: 30px;
    text-transform: uppercase;
    margin-bottom: 10px;
    color: gold;

}

.form-container form input,
.form-container form select {
    width: 100%;
    padding: 10px 15px;
    font-size: 17px;
    margin: 8px 0;
    background: transparent;
    color: white;
    border-bottom: 1px solid gray;


}

.form-container form input::-webkit-input-placeholder {
    color: rgb(128, 128, 128);
}

.form-container form select option {
    background: #fff
}

.form-container form .form-btn {
    background: transparent;
    color: red;
    text-transform: capitalize;
    font-size: 20px;
    cursor: pointer;
    border: none;
}

.form-container form .form-btn:hover {

    color: white;
}

.form-container form p {
    margin-top: 10px;
    font-size: 20px;
    color: gainsboro;
}

.form-container form p a {
    color: goldenrod;
    text-decoration: underline;
}

.form-container form .error_msg {
    margin: 10px 0;
    display: block;
    background: crimson;
    color: #fff;
    border-radius: 5px;
    font-size: 20px;
    padding: 10px;
}

header {
    background: black;
    width: 100%;
    position: sticky;
    top: 0;
    z-index: 1000;
}

.header {
    width: 100%;
    display: flex;
    justify-content: space-between;
    border-bottom: 2px solid rgba(255, 255, 255, 0.3);
    height: 80px;
}

.headerleft {
    padding: 10px 10px 10px 30px;
    color: white;
    font-weight: 800;
    font-size: 30px;
    line-height: 50px;
    font-family: roboto;
}

.headercenter {
        padding: 10px;
}


.headercenter ul li {
    display: inline-block;
    height: 30px;
    color: white;
    margin: 20px;
position: relative;

}

.headercenter ul li a {
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    color: white;
}

.headercenter ul li a:hover {
    background: rgba(0, 128, 0, .7);
    padding: 5px 5px;
    border-radius: 5px;
}






.headerright {margin-top: 10px;
}


.headerright ul {
    display: flex;
}

.headerright ul li {
    
margin: 10px;
}


ul li .profile-pic-out {
    width: 35px;
    height: 35px;
    padding: 5px;
    cursor: pointer;
}

ul li .profile-pic img {
    border-radius: 50%;
    width: 35px;
    height: 35px;

}

ul li .div-out {
    margin-top: 40px;
    display: none;
    color: white;
}

ul li .profile-pic-out img:hover {
    background-color: rgba(255, 255, 255, 0.3);
    height: 45px;
    width: 55px;
    border-radius: 50%;
}

ul li .profile-pic-out:hover .div-out {
    display: block;
    position: relative;
}

ul li .profile-pic img {
    width: 35px;
    height: 35px;
}

#notification {
    border-radius: 50%;
    background-color: rgba(255, 255, 255, 0.7);
}
.qanda-body {
    width: 100%;
    min-height: 87vh;
    background-image: linear-gradient(rgba(0, 0, 0, .7),rgba(0, 0, 0, .7)), url(./images/qn.jpg);
    background-size: 100% 100%;background-repeat: no-repeat;margin: auto;
}

.qanda-nav {
    padding-top: 40px;
    text-align: center;
    color: goldenrod;
}

.qanda-nav h1 span {
   
    background: rgba(255, 255, 255, .3);
    padding: 5px 20px;
    border-radius: 45px;
}

.qanda-select {
    text-align: center;
    margin-top: 50px;
}

.qanda-select h2 {
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    color:#FFA500;
}

.qanda-institutions {
    display: flex;
    flex-wrap: wrap;
    padding: 10px 50px;
}

.qanda-institutions div {
    margin: 5px;
}

.qanda-institutions div a {
    font-size: 20px;
    color: whitesmoke;
    font-weight: 800;
}

.qanda-institutions div a:hover {
    color: gold;
    text-decoration: underline;
}

.div-main p {
    padding-left: 100px;
    padding-right: 200px;
    color: lightgray;
}

.div-back {
    width: 35px;
    height: 35px;
    margin: auto;
    margin-top: 50px;
}

.back {
    
    padding: 5px 13px;
    width: 100px;
    margin-left: -15px;
    margin-top: 5px;
    margin-bottom: 100px;
    font-weight: 700;
    font-size: 20px;
    box-shadow: 0 0 2px;
    position: relative;
    border-radius: 7px;
    text-align: center;
    background-color: rgba(0, 0, 0, 0.7);
    color: white;
}

.div-back img {
    width: 55px;
    height: 35px;
    background-color: rgba(255, 255, 255, 0.3);
    padding: 5px 13px;
    border-radius: 7px;
}

.div-back img:hover {
    background-color: rgba(197, 114, 114, 0.3);
    width: 55px;
    cursor: pointer;
    padding: 5px 13px;
    border-radius: 7px;
}

.div-back:hover .back {
    background-color: rgba(238, 223, 223, 0.7);
    display: block;
    color: black;
}

.tag {
    font-size: 1.0rem;
    margin: 1.5rem 1.2rem;
    padding: 5px 1.8rem;
    border-radius: 50px;
    background-color: #efefef;
    display: inline-block;
    color: black;
    cursor: pointer;
    border: 1px solid #ccc;
}

.main-center {
    background-color: white;
    margin-left: 2px;
    padding-top: 20px;

}


.main-center-select {
    padding-left: 50px;
}

.main-center h1 {
    padding: 10px 10px;
    margin-bottom: 50px;
    background-color: rgba(0, 0, 0, 0.1);
    width: 250px;
    margin-left: 20px;
    border-radius: 50px;
}

<!--End-->
<!--moreStyle-->
@media(max-width:750px) {  
    body{width: 100%;}  
    .headerright {
        margin-right: 10px;
    }
    .headercenter{display: none;}
    main {
        flex-direction: column;
    }

    .center {
        width: 100%;
        overflow: hidden;
    }
    .main-scroll-div {width: 100%;}
    .subFriends {
        width: 100%;
        overflow: hidden;
    }

    .mainsubleft {
    position: sticky;
        width: 100%;
        background-color: white;
        z-index: 100;
        top: 0;
        left: 0;
        bottom: 0;
    
    }
  .mainsubleft ul li{margin-bottom: 0;}
    #menu-bar {
        display: block;
    }
}
     <!--End-->                                            
                                                 

                                                 
