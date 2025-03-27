<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8"/>
        <meta http-equiv="X-UA-Compatible" content="IE=edge"/>
        <meta name="viewport" content="width=device-width,initial-scale=1.0"/>
        <title>pf card</title>
        <link rel="stylesheet" href="project.css">
        <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
        


.pfcar{

  background-color: white;
  border-radius: 5px;
  width: 250px;
  height: 230px;
  display: flex;
  align-items: center;
  justify-content: center;
  box-shadow: 2px 2px 2px rgba(0, 0, 0, 0.4);
}
.img{
  position: relative;
  display: flex;
  align-items: center;
  justify-content: center;
  border-color: rgb(24, 24, 26);
  border-width: 2px;
  border-style: solid;
  border-radius: 50px;
  margin-bottom: 5px;
  margin-top: -23px;
}
.imge{
  width: 100px;
  object-fit: cover;
  border-radius: 55px;
  border-color: white;
  border-width: 2px;

}
.pfcar{
  display: flex;
  flex-direction: column;
  align-items: center;
}
.name{
  display: flex;
  flex-direction: row;
  font-size: 15px;
  font-weight: bold;
  font-style: italic;
  
}
.logo{
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  column-gap: 0.50px;
}
.link{
  
  color: white;
  margin: 0 5px;
  width: 30px;
  height: 30px;
  display: flex;
  align-items: center;
  justify-content: center;
  text-decoration: none;
}
.face{
  background-color: rgb(59, 89, 152) ; 
  border-color: rgb(59, 89, 152);
  width: 20px; height: 20px;
  display: flex;
  align-items: center;
  justify-content: center;

}
.insta{

background-color: rgb(193, 53, 132);
width: 20px; height: 20px;
display: flex;
align-items: center;
justify-content: center;
}
.you{
  background-color: rgb(225, 0, 0);
  width: 20px; height: 20px;
  display: flex;
align-items: center;
justify-content: center;
}
.dis{
  background-color: rgb(114, 137, 218);
  width: 20px; height: 20px;
  display: flex;
align-items: center;
justify-content: center;
}
.second-button{
  background-color: rgb(14, 53, 124);
  color: white;
  border: none;
  height: 24px;
  width: 85px;
  border-radius: 43px;
  box-shadow: 2px 2px 2px rgba(0, 0, 0, 0.7);
}
.second-button:hover{
  border-radius: 43px;
  box-shadow: 2px 2px 2px rgba(0, 0, 0, 0.7);
}
.first-button{
  background-color: rgb(219, 19, 19);
  color: white;
  border: none;
  height: 24px;
  width: 85px;
  border-radius: 43px;
  box-shadow: 2px 2px 2px rgba(0, 0, 0, 0.7);
}
.first-button:hover{
  border-radius: 43px;
  box-shadow: 2px 2px 2px rgba(0, 0, 0, 0.7);
}
.pfcar::before{
  content: "";
  position: absolute;
  top: 5px;
  left: 2;
  width: 18.3%;
  height: 15%;
  background-color: rgb(31, 31, 32);
}
    </head>
    <body>
    <div class="pfcar">
        <div class="img">
            <img src="../imge.jpg" class="imge">
        </div>
        <div class="name">
            <span class="first-name">muhammed wassil</span>
            <span class="last-name">.rhimi</span>
        </div>
        <div class="logo">
            <a href="#" class="link" >
                <div class="face">    <i class='bx bxl-facebook'></i></div>
            </a>
            <a href="#" class="link" >
                <div class="insta"><i  class='bx bxl-instagram'></i></div>
            </a>
            <a href="#" class="link" >
                <div class="you"><i  class='bx bxl-youtube' ></i></div>
            </a>
            <a href="#" class="link" >
               <div class="dis"> <i  class='bx bxl-discord-alt' ></i></div>
            </a>
        </div>
        <div class="buttons">
            <button class="first-button">subscribe</button>
            <button class="second-button">message</button>
        </div>
    </div>
        

    </body>
</html>
