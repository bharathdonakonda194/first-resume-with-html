# first-resume-with-html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!--google fonts-->

    <a href="<link rel="preconnect" href="https://fonts.gstatic.com">
        <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@200&display=swap" rel="stylesheet"></a>

        <!--font awsome-->

        <script src="https://kit.fontawesome.com/f226088c08.js" crossorigin="anonymous"></script>


    <title>resume</title>
    <link href="style/style.css" rel="stylesheet">
    </head>
<body>
    <div class="box">
        <div class="header">
            <div class="header-right">
                <div class="name">
                    <div class="firstname">Bharath</div>
                    <div class="lastname">Donakonda</div>
                </div>
            </div>
    </div>
</div>
     <div class="header-left">
        <div class="email">
            <p>mailforbharath123@gmail.com</p>
                 <i class="fas fa-envelope-square"></i>
             </div>
        </div>
    </div>
</div>

                <div class="github"><i class="fab fa-github-alt"></i>   
                <p>github/bharath194</p>
                 </div>
            <div class="linkedin"><i class="fab fa-linkedin"></i>
                <p>linked/in/bharathdonakonda</p>
             </div>
            <div class="phone number">
                <i class="fas fa-phone"></i><p>91-00-00-00-89</p>
             </div>
    <hr>
    <div class="objective"></div>
    <div class="obj-head ">
        <i class="fas fa-bullseye"></i>
        <h2>objective :</h2>
        <p>To pursue a challenging career where i can apply my existing knowledge and creativity,acquire 
            new skills and contribute effectively to the organization
        </p>
    </div>
    </div>
    <div class="eaducation"></div>
    <div class="ed-head gray"></div>
    <i class="fas fa-school"></i>
        <h2>education :</h2>
    <table>
    <tr>
        <th>board</th>
        <th>institution</th>
        <th>year of passing</th>
        <th>percentage</th>
    </tr>
    <tr>
        <td>b.com(c.s)</td>
        <td>sree venkateshwara college</td>
        <td>2017</td>
        <td>75%</td>
    </tr>
    <tr>
        <td>intermediate board</td>
        <td>sree trevani college</td>
        <td>2014</td>
        <td>65%</td>
    </tr>
    <tr>
        <td>ssc board</td>
        <td>Model high school</td>
        <td>2012</td>
        <td>87%</td>
        </tr>
    </table>
    <div class="skills"></div>
    <div class="sk-head gray"></div>
    <i class="fas fa-allergies"></i>
    <h2>skills :</h2>
    <ul> 
    <li>Html</li>
    <li>CSS</li>
    <li>JavaSript</li>
    <li>JQuery</li>
    <li>PHP</li>
    <li>MYSQL</li>
    </ul>
    <div class="achivements"></div>
    <div class="achiv-head"></div>
    <i class="fas fa-trophy"></i>
    <h2>Achivements :</h2>
    <p>received awards, won competitions, achieved high grades in studies, volunteering, participating in sporting events, etc.
    </p>
    
    
</body>
</html>


#css for the above resume
body{
    margin:0%;
    padding:0%;
    background: white;
    font-family:'Poppins', sans-serif;
    font-size: 30px;
    
}
h1{
    margin:0;
    font:weight 400;

}
h2{
    margin:0;
    font-weight:400;
    display:inline;
    text-decoration: black underline;

}
.box{
    background: white; 
    width:40rem;
    padding:3rem;
    margin:1rem auto;
    border-radius:0.5;
    


}
.header{
  display:grid;
  grid-template-columns: 40% 60%;

}
.header-right{
    width: 50%;
    display: grid;
    justify-items: center;
    font-size: 50px;


}
.first-name{
    font-weight:600;
    margin:0;
    ;
}
.last-name{
    font-weight: 300;
    margin:0;

}
.header-left{
    display:grid;
    justify-items: flex;
    align-items: flex;
    font-size: 3rem;
    

}
.email{
    font-size: 30px;
}
.header-left p{
    display: inline;
}
.github{
    font-size: 30px;

}
.header-left p{
    display:inline-block;
}
}
.icon{
    color: rgb(190,190,190);
    font-size:4rem;
    margin-left:1rem;
    display: inline-block;
    

}

    
}
.gray{
    background: rgb(133, 133, 133);
    color:white;
    padding:0.5rem;
    border-radius: 0.3rem;
}
table{
    border:2px solid black;
    margin:1rem 0;
    width:100%;
    text-align: center;
    border-collapse: collapse;

}
td,th{
    border:1px solid black;
    padding: 0.4rem;
}
