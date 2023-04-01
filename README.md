# week3coursera
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8"> <!-- biblio pour les caracters speciaux bhal virgule accent ...-->
        <meta http-equiv="X-UA-compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, user-scalable=no">
       <link rel="stylesheet" href="style.css"> <!-- liason avec le page css-->
       <link rel="stylesheet" href="css/bootstrap.min.css"> <!-- liason avec le bootstrap-->
       <title> module3</title>
    </head>
    <style>
    * {
        box-sizing: border-box;
      }
    
      body{
          margin: 0;
          padding: 0;
        font-family: "Comic Sans MS", cursive, sans-serif;
      }
      
      header{
        background-color: grey;
        width: 100%;
        padding: 20px;
        align-items: center;
      }
    
      .button{ /* hna 9adit chkel dial css kifma bghet ana */
        padding: 16px;
        background-color: transparent;
        border: none;
        cursor: pointer; /* bach souris twli yed  */
       } 
    
       .menu1{
        display:flex;
        padding:20px; /*zdtha */
       }
    
       .menu{
         display:none; /* bach may banuch les choix unless 7teti la sourie fu9ha */
         position:absolute;
         background-color: aliceblue;
         min-width:100px;
       } 
    
       .menu2{   /*bach chicken w beef w sushi ijiw l t7t */
        margin-bottom: 50px; /* bach tale3 taswira dial menu lfo9*/
         margin-left: auto; /* ijiw f jenb */
         position: relative;
         display: inline-block; /* chi te7t chi */
       }
    
       
    
       .menu2 a {  /* kifach tay banu links ta3ek */
        color:darkred;
        padding: 12px 16px;
        text-decoration:underline; /*kat gad line decoration dial text li baghin */
        display:block; /* llinks te7t ba3diyatkum bach yban m encadri b block */
        text-align: center;
       }
    
       .menu2 a:hover{   /* ghir la couleur li bghiti t afficha meni t7et la sourie */
        background: rgb(53, 53, 53);
      }
    
      .menu2:hover .menu {   /* hover bach ila 7teti la sourie iban w menu bach iban dakchi ta3u */
        display:block; /* bach i banu menu t7et la sourie ta3k ibanu lik les choix ta7t ba3dyathom  */
      }
      
      h1 {
        margin-bottom: 15px;
        text-align: center;
        font-size: 50px;
      
      }
    
      .box{
        width: 100%;
        overflow: none;
      }
      
      .content-name{
        text-align: center;
        border: 4px solid black;
        width: 100px;
        height: 40px;
        padding: 5px;
        float: right;
        margin-right: 36px;
        margin-top: 0px;
        font-weight: bold;
        position: relative;
      }
       
      .content{
        background-color: grey;
        border: 5px solid black;
        width: 90%;
        height: auto;
        margin: 2.5%;
        color: black;
        padding: 10px; 
      } 
      
      /**** DESKTOP ****/
      @media (min-width: 992px) {
        .col-lg-4 {
            float: left;
          width: 33.33%;
        }
        .menu2{
          display:none;
        }
    
      }
      /**** TABLETTE ****/
      @media (min-width: 768px) and (max-width: 991px) {
        .col-md-6,.col-md-12 {
          float: left;
        }
        .col-md-6 {
          width: 50%;
        }
        .col-md-12 {
          margin-left: -10px;
          width: 100%;
        }
        .name3{
          margin-right: 65px;
          width: 100px;
        }
        .menu2{
          display:none;
        }
      }
      /**** MOBILE *****/
      @media (min-width: 0px) and (max-width: 767px) {
        .col-sm-12 {
            float: left;
          width: 100%;
        }
        .content-name{
          margin-right: 30px;
        }
        .menu2{
          display: block;
        }
      }
    </style>
    <body>
    <header>
        <div class="menu1">
        <h2 id="h2">Food,LLC</h2>  
        <div class="menu2"> 
            <!-- hadi hatit fiha tswera dial menu -->
       <button onclick="myFunction()" class="button"> <img src="menulogo.png" class="pic" width="50px" height="50px"></button> 
        <!-- hna hatit dekshi li west le menu avec les liens li ghadi ydiwni lihom-->
       <div class="menu"> 
       <a href="#Chicken">Chicken</a>
       <a href="#Beef">Beef</a>
       <a href="#Sushi">Sushi</a>
    </div>
    </div>
    </header>
    </div>
    <div class="h1">
    <h1>Our Menu</h1>
    </div>
     <!-- had les col bash mn nwsel lmedia ngad css dialhom fde9a mashi kola whda rassha -->
    <div class="col-lg-4 col-md-6 col-sm-12">
        <div class="box" id="Chicken">
            <p class="content-name ">Chicken</p>
            <p class="content" id>Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim.
                Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim.
                Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim.
                Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim.
                Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim.
                <br> <a href="#h2"> back to the top</a> </p>
               
        </div>
    </div>
  
    <div class="col-lg-4 col-md-6 col-sm-12">
        <div class="box" id="Beef">
             <p class="content-name ">Beef</p>
             <p class="content">Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim.
                Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim.
                Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim.
                Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim.
                Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim.
               <br> <a href="#h2"> back to the top</a> </p>
                
        </div>
    </div>
  
    <div class="col-lg-4 col-md-12 col-sm-12">
        <div class="box" id="Sushi">
            <p class="content-name ">Sushi</p>
            <p class="content">Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim.
                Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim.
                Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim.
                Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim.
                Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim.
               <br> <a href="#h2"> back to the top</a> </p>
                
        </div>	
    </div>
  
    </body>
</html>
