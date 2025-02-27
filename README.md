# Portfolio

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sai Charan Portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Raleway:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Grechen+Fuemen&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Dosis:wght@200..800&display=swap" rel="stylesheet">
    <style>
        *
        {
            margin: 0;
            padding: 0;
        }

        .nav
        {
            font-size: larger;
            list-style-type: none;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            margin-top: -90px;
            display: flex;
            gap: 100px;
            padding-left: 500px;

            
        }
        .nav a {
            text-decoration: none;
            color:aliceblue;
            
        }

        .selfbeside{
            display: flex;
            justify-content: space-evenly;
            margin-top: 100px;
            gap: 40px;
        }
        
        .self h1 
        {
            color: rgb(135, 139, 139);
            font-size: 40px;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            font-size: 50px;
        }

        .self h2{
            color: rgb(135, 139, 139);
            font-size: 15px;
            font-family: "Raleway", serif;
            font-weight: 400;
            line-height: 23px; 
            margin-top: -20px;           

        }
        
        a:hover
        {
            color: #b74b4b;
        }

        .edu1
        {
            border: 1px solid white;
            height: 200px;
            width: 400px;
            border-radius: 8px;
            background-color: rgb(69, 66, 68);
            border: none;
            font-family:Verdana, Geneva, Tahoma, sans-serif
        }

        .education1{
            display: flex;
            justify-content: space-around;
            margin-top: 60px;

        }

        .card {
            background: linear-gradient(to right, #818080, #535252);
            border-radius: 10px;
            padding: 20px;
            width: 320px;
            color: black;
            box-shadow: 10px 20px 60px rgb(68, 32, 32);
        }

        .header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 10px;
        }

        .badge {
            background: black;
            color: white;
            padding: 5px 10px;
            border-radius: 15px;
            font-size: 14px;
        }

        .grad1{
            background: #ececec;
            color: black;
            font-weight: bold;
            border-radius: 20px;
            width: 150px;
        }

        .degree {
            font-size: 14px;
            background: lightgray;
            padding: 5px 10px;
            border-radius: 10px;
            display: inline-block;
            margin: 5px 5px 10px 0;
        }

        h2 {
            font-size: 18px;
            margin: 10px 0;
        }

        .university {
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .location {
            display: flex;
            align-items: center;
            gap: 10px;
            font-size: 14px;
            color: #232222;
        }

        .icon {
            width: 16px;
            height: 16px;
        }

        .card:hover
        {
             transform: scale(1.1);
        }

        .card1 {
            background: linear-gradient(to right, #818080, #6c2626);
            border-radius: 10px;
            padding: 20px;
            height: 120px;
            width: 320px;
            color: black;
            box-shadow: 10px 20px 90px rgb(79, 35, 35);
        }

        .view:hover
        {
            transform: scale(1.1);
        }

        .serif
        {
            font-family: "Raleway", serif;
        }


        .button {
            display: flex;
            align-items: center;
            width: 110px;
            padding: 10px 20px;
            background-color: white;
            border-radius: 30px;
            box-shadow: 5px 6px 10px rgb(114, 47, 47);
            background: linear-gradient(to right, #818080, #cfcbcb);
        }
        .button img {
            width: 30px;
            height: auto;
            margin-right: 10px;
        }
        .button span {
            font-size: 20px;
            font-weight: 500;
            color: black;
            font-family: "Raleway", serif;
        }

        .skill
        {
            display: flex;
            justify-content: space-around;
            margin-left: 250px;
            margin-right: 250px;

        }
        .button:hover{
            transform: scale(1.1);
        }

        .project1
        {
            height: 290px;
            width: 800px;
            background: rgb(65, 3, 35);
            background: linear-gradient(90deg, rgba(75, 2, 45, 0.685) 99%,);
            border-radius: 60px;
            margin-left: 180px;
            display: flex;
            

        }

        .subproject1
        {
            height: 250px;
            width: 300px;
            background-color: #45152f;
            border-radius: 40px;
            margin-top: 20px;
            margin-left: 10px;
            

        }
        .subproject2
        {
            margin-left: 20px;
            margin-top: 20px;
        }
        .worked
        {
            color: rgb(190, 183, 183);
            font-family: "Raleway", serif;
            font-weight:300 ;
        }
        .resume
        {
            height: 290px;
            width: 800px;
            background: rgb(65, 3, 35);
            border-radius: 60px;
            margin-left: 200px;
        }
        .resume-name
        {
            color: #b74b4b;
            text-align:center;
            font-family: "Dosis", serif;
            
        }
        .resume-domain
        {
            color: #818080;
            font-family: "Dosis", serif;
            font-weight: 700;
            text-align: center;
        }
        .connect
        {
            
             display: flex;
             justify-content: space-around;
             margin-left: 250px;
             margin-right: 250px;
             gap:30px
    
            
        }
        .resumehover:hover
        {
            transform: scale(1.1);
        }
        .a:hover{
            transform: scale(1.1);
        }
        .footer{
            width: 98.5vw;
            height: 30px;
            background-color: darkgoldenrod;
            color: black;
            text-align: center;
            font-size: 23px;
        }

        @media (max-width: 1024px) {
    .nav {
        padding-left: 0;
        justify-content: center;
        gap: 50px;
        margin-top: -70px;
    }

    .selfbeside {
        flex-direction: column;
        align-items: center;
        text-align: center;
        margin-top: 50px;
    }

    .self h1 {
        font-size: 35px;
    }

    .self h2 {
        font-size: 14px;
        line-height: 22px;
    }

    .education1 {
        flex-direction: column;
        align-items: center;
        gap: 20px;
    }

    .skill {
        flex-wrap: wrap;
        justify-content: center;
        margin: 20px;
    }

    .button {
        margin-bottom: 10px;
    }

    .connect {
        flex-wrap: wrap;
        justify-content: center;
        gap: 20px;
    }
}

@media (max-width: 768px) {
    .nav {
        flex-direction: column;
        align-items: center;
        gap: 15px;
        margin-top: -50px;
    }

    .selfbeside {
        flex-direction: column;
        align-items: center;
        text-align: center;
        gap: 20px;
    }

    .self h1 {
        font-size: 30px;
    }

    .self h2 {
        font-size: 12px;
    }

    .education1 {
        flex-direction: column;
        align-items: center;
    }

    .card {
        width: 90%;
    }

    .skill {
        flex-direction: column;
        align-items: center;
        gap: 10px;
    }

    .button {
        width: auto;
    }

    .project1,
    .resume {
        width: 90%;
        margin-left: auto;
        margin-right: auto;
    }
}

@media (max-width: 480px) {
    .nav {
        flex-direction: column;
        align-items: center;
        gap: 10px;
    }

    .self h1 {
        font-size: 25px;
    }

    .self h2 {
        font-size: 12px;
    }

    .education1 {
        flex-direction: column;
    }

    .card {
        width: 100%;
        padding: 15px;
    }

    .skill {
        flex-direction: column;
        align-items: center;
        gap: 5px;
    }

    .button {
        width: 100px;
    }

    .project1,
    .resume {
        width: 95%;
        border-radius: 30px;
    }
}

        
    </style>
</head>
<body style="background-color: black;">
    <div style="position: fixed;">
        <ul class="nav" >
            <li><a href="">Home </a></li>
            <li><a href="" style="color: #b74b4b;">About </a></li>
            <li><a href="">Skills</a></li>
            <li><a href="" style="color: #b74b4b;">Projects</a></li>
            <li><a href="">Contact</a></li>
        </ul>
    </div>
    <div class="selfbeside">
        <div>
            <img src="https://i.ibb.co/KMVg85P/DALL-E-2025-02-27-16-58-37-A-man-with-a-normal-well-proportioned-body-and-a-cute-toy-like-face-He-ha.webp" alt="" height="530px" width="500px" style="border-radius: 50%; margin-top:-60px;padding-left:50px;box-shadow:10px 10px 10px rgb(97, 32, 32)">
        </div>

        <div class="self" style="margin-top: 80px;">
              <h1>Hi,it's <span style=" color: #b74b4b;">Sai Charan</span><br><span style="font-size: 1.9rem;"> i'm a <span style=" color: #b74b4b;" > Frontend Developer </span></span></h1>
              <br>
              <h2>A Front-End Developer with expertise in HTML, CSS, JavaScript, SQL, and Python is responsible for designing and
                developing the user interface (UI) and user experience (UX) of web applications. flexibility to work across various stages of
                the application, from design implementation to server-side integration, making them an asset in full-stack or collaborative teams</h2>
        </div>
    </div>
    <!-- EDUCATION -->

    <div>
        <h1 style="color:#b74b4b;font-family:Arial, Helvetica, sans-serif;text-align: center;font-size:40px">Education</h1>
    </div>

    <div class="education1">
        <!-- Bachelor's Degree Card -->
        <div class="card">
            <div class="header">
                <span class="badge">2021 - 2024</span>
                <span class="grad1" style="text-align: center;">🎓 Graduation</span>
            </div>
            <span class="degree" >Bachelor’s Degree</span>
            <span class="degree">BCOM(CA)</span>
            <h2>Bachelor of Commerce</h2>
            <div class="university">
                <img class="icon" src="https://img.icons8.com/ios-filled/50/university.png" alt="University">
                <span>PVKK Degree College</span>
            </div>
            <div class="location">
                <img class="icon" src="https://img.icons8.com/ios-filled/50/marker.png" alt="Location">
                <span>Anantapur, Andhra Pradesh</span>
            </div>
        </div>
    
        <!-- Intermediate Card -->
        <div class="card">
            <div class="header">
                <span class="badge">2019 - 2021</span>
                <span class="grad1" style="text-align: center;">🎓 Intermediate</span>
            </div>
            <span class="degree">Intermediate</span>
            <span class="degree">CEC</span>
            <div class="university">
                <img class="icon" src="https://img.icons8.com/ios-filled/50/university.png" alt="University">
                <span>Sri Vivekananda College</span>
            </div>
            <div class="location">
                <img class="icon" src="https://img.icons8.com/ios-filled/50/marker.png" alt="Location">
                <span>Anantapur, Andhra Pradesh</span>
            </div>
        </div>
    
        <!-- Schooling Card -->
        <div class="card">
            <div class="header">
                <span class="badge"> 2019 </span>
                <span class="grad1" style="text-align: center;">🎓 School</span>
            </div>
            <span class="degree">Schooling</span>
            <div class="university">
                <img class="icon" src="https://img.icons8.com/ios-filled/50/university.png" alt="University">
                <span>Lakshmi E.M School</span>
            </div>
            <div class="location">
                <img class="icon" src="https://img.icons8.com/ios-filled/50/marker.png" alt="Location">
                <span>Anantapur, Andhra Pradesh</span>
            </div>
        </div>
    </div>
 <!-- CERTIFICATIONS -->
  <br><br>

 <div>
    <H1 style="color:#b74b4b;font-family:Arial, Helvetica, sans-serif;text-align: center;font-size:40px">Certifications</H1>
</div>

 <div class="education1">
    <div class="card1">
        <div class="header">
            <span class="badge"><img src="https://tse4.mm.bing.net/th?id=OIP.4NWSX9_uB2Vid_jX2aEmwQHaEK&pid=Api&P=0&h=180" style="height: 30px;width:70px" alt=""></span>
            <span  style="text-align: center;"><img  style="height: 30px;" src="https://logos-world.net/wp-content/uploads/2021/10/Python-Emblem.png" alt=""></span>
        </div>
        <span style="font-weight:bold;" class="serif">GET STARTED WITH PYTHON</span>
        <h2 class="view" style="font-size: bold;background: linear-gradient(to right, #818080, #cfcbcb);;height:25px;width:80px;border-radius:20px;box-shadow:00px 10px 20px rgb(8, 0, 3);"><a href="https://www.coursera.org/account/accomplishments/verify/HR64MPALJXCJ?utm_source%3Dandroid%26utm_medium%3Dcertificate%26utm_content%3Dcert_image%26utm_campaign%3Dsharing_cta%26utm_product%3Dcourse" target="_blank" style="text-decoration: none;color:black;font-weight:bold"> 👁‍🗨View</a></h2>
    </div>

    <div class="card1">
        <div class="header">
            <span class="badge"><img src="https://static.vecteezy.com/system/resources/previews/026/135/319/large_2x/meta-social-media-symbol-logo-design-illustration-with-black-background-free-vector.jpg" style="height: 30px;width:70px" alt=""></span>
            <span  style="text-align: center;"><img style="height: 30px;"   src="https://vectorified.com/images/html-css-icon-2.png" alt=""></span>
        </div>
        <span style="font-weight:bold;" class="serif">HTML AND CSS IN DEPTH</span>
        <h2 class="view" style="font-size: bold;background: linear-gradient(to right, #818080, #cfcbcb);height:25px;width:80px;border-radius:20px;box-shadow:00px 10px 20px rgb(8, 0, 3)"><a href="https://www.coursera.org/account/accomplishments/verify/B0Q6LQJJU2AA?utm_source%3Dandroid%26utm_medium%3Dcertificate%26utm_content%3Dcert_image%26utm_campaign%3Dsharing_cta%26utm_product%3Dcourse" target="_blank" style="text-decoration: none;color:black;font-weight:bold"> 👁‍🗨View</a></h2>
    </div>

</div>
<div class="education1">
    <div class="card1">
        <div class="header">
            <span class="badge"><img src="https://static.vecteezy.com/system/resources/previews/026/135/319/large_2x/meta-social-media-symbol-logo-design-illustration-with-black-background-free-vector.jpg" style="height: 30px;width:70px" alt=""></span>
            <span  style="text-align: center;"><img style="height: 30px; width:25px" src="https://www.pngitem.com/pimgs/m/681-6810582_javascript-logo-svg-hd-png-download.png" alt=""></span>
        </div>
        <span style="font-weight:bold;" class="serif">PROGRAMMING WITH JAVASCRIPT</span>
        <h2 class="view" style="font-size: bold;background: linear-gradient(to right, #818080, #cfcbcb);height:25px;width:80px;border-radius:20px;box-shadow:00px 10px 20px rgb(8, 0, 3)"><a href="https://www.coursera.org/account/accomplishments/verify/7S8FCBAJ0WUY?utm_source%3Dandroid%26utm_medium%3Dcertificate%26utm_content%3Dcert_image%26utm_campaign%3Dsharing_cta%26utm_product%3Dcourse" target="_blank" style="text-decoration: none;color:black;font-weight:bold"> 👁‍🗨View</a></h2>
    </div>

    <div class="card1">
        <div class="header">
            <span class="badge"><img src="https://d8qb5cxd9qhkd.cloudfront.net/employers/atlassian/logos/atlassian_logo-1200x630.webp" style="height: 30px;width:70px" alt=""></span>
            <span  style="text-align: center;"><img style="height: 30px;" src="https://www.pngarts.com/files/8/Github-Logo-PNG-Picture.png" alt=""></span>
        </div>
        <span style="font-weight:bold;"  class="serif">COMPLETE CERTIFICATION FOR VERSION CONTROL OF GIT</span>
        <h2 class="view" style="font-size: bold;background: linear-gradient(to right, #818080, #cfcbcb);height:25px;width:80px;border-radius:20px;box-shadow:00px 10px 20px rgb(8, 0, 3)"><a href="https://www.coursera.org/account/accomplishments/verify/1J6QQI9ZBAVF?utm_source%3Dandroid%26utm_medium%3Dcertificate%26utm_content%3Dcert_image%26utm_campaign%3Dsharing_cta%26utm_product%3Dcourse" target="_blank" style="text-decoration: none;color:black;font-weight:bold">👁‍🗨View</a></h2>
    </div>

</div>
<!-- skills -->
 <br><br>
<div>
    <h1 style="color:#b74b4b;font-family:Arial, Helvetica, sans-serif;text-align: center;font-size:40px">Skills</h1>
</div>
<br><br>

<div class="skill">
<div class="button" style="width:90px;">
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/61/HTML5_logo_and_wordmark.svg" alt="HTML5 Logo" width="30">
    <span>Html5</span>
</div>
<div class="button" style="width:70px;">
    <img src="https://img.icons8.com/?size=100&id=21278&format=png&color=000000" alt="HTML5 Logo" width="30">
    <span>Css</span>
</div>
<div class="button">
    <img  style="margin-left: -10px;" src="https://img.icons8.com/?size=100&id=Nkym0Ujb8VGI&format=png&color=000000" alt="HTML5 Logo" width="30">
    <span >Javascript</span>
</div>
<div class="button">
    <img src="https://img.icons8.com/?size=100&id=25Sjy8fKExYA&format=png&color=000000" alt="HTML5 Logo" width="30">
    <span>Reactjs</span>
</div>

</div>
<!--  -->
<br><br>
<div style="display: flex;gap:50px">
<div class="button" style="margin-left: 350px;">
    <img src="https://img.icons8.com/?size=100&id=13441&format=png&color=000000" alt="HTML5 Logo" width="30">
    <span>Python</span>
</div>
<div class="button" style="width: 70px;">
    <img src="https://img.icons8.com/?size=100&id=77694&format=png&color=000000" alt="HTML5 Logo" width="30">
    <span>Sql</span>
</div>
<div class="button">
    <img  style="margin-left: -10px;" src="https://img.icons8.com/?size=100&id=84710&format=png&color=000000" alt="HTML5 Logo" width="30">
    <span>Bootstrap</span>
</div>
</div>

<!-- projects -->
 <br><br><br>
 <div>
    <h1 style="color:#b74b4b;font-family:Arial, Helvetica, sans-serif;text-align: center;font-size:30px">Projects i'have <br>Worked On  </h1>
</div>

<!-- 3 -->
 <br><br><br>
<div class="project1" style="background-color: rgb(21, 24, 62);">
    <div class="subproject1" style="background-color: rgb(26, 26, 106);">
       <img src="https://i.ibb.co/QFk6sGcb/Bizland-website.png" alt="" style="height: 220px;width:280px;margin-top:15px;margin-left:10px;border-radius:30px">
    </div>
    <div class="subproject2">
           <h1 style="color: white;font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;font-size:40px">Bizland</h1>
           <h2 class="worked">worked on</h2>
           <span class="degree a"><a href="https://saigcharan.github.io/BIZLAND/" target="_blank" style="text-decoration: none; color: black;">website</a></span>

           <h5 style="color: rgb(156, 152, 152);">Technologies i have used</h5>
           <br>
    <div style="display: flex;gap:30px">
        <div class="button" style="width:90px;box-shadow:2px 2px 2px rgb(49, 49, 101)">
            <img src="https://upload.wikimedia.org/wikipedia/commons/6/61/HTML5_logo_and_wordmark.svg" alt="HTML5 Logo" width="30">
            <span>Html5</span>
        </div>
        <div class="button" style="width:70px;box-shadow:2px 2px 2px rgb(44, 44, 92)">
            <img src="https://img.icons8.com/?size=100&id=21278&format=png&color=000000" alt="HTML5 Logo" width="30">
            <span>Css</span>
        </div>
        <div class="button" style="margin-right: 10px;box-shadow:2px 2px 2px rgb(43, 43, 106)">
            <img  style="margin-left: -10px;" src="https://img.icons8.com/?size=100&id=84710&format=png&color=000000" alt="HTML5 Logo" width="30">
            <span>Bootstrap</span>
        </div>
    </div>
           

    </div>
</div>
<br><br>

<br><br>
<div class="project1">
    <div class="subproject1">
        <img src="https://i.ibb.co/szGDDHG/Travel-website.png" alt="" style="height: 220px;width:280px;margin-top:15px;margin-left:10px;border-radius:30px">
    </div>
    <div class="subproject2">
           <h1 style="color: white;font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;font-size:40px">Travelville</h1>
           <h2 class="worked">worked on</h2>
           <span class="degree a"><a href="https://saigcharan.github.io/Travelville/" target="_blank" style="text-decoration: none; color: black;">website</a></span>

           <h5 style="color: rgb(150, 147, 147);">Technologies i have used</h5>
           <br>
    <div style="display: flex;gap:30px">
        <div class="button" style="width:90px;">
            <img src="https://upload.wikimedia.org/wikipedia/commons/6/61/HTML5_logo_and_wordmark.svg" alt="HTML5 Logo" width="30">
            <span>Html5</span>
        </div>
        <div class="button" style="width:70px;">
            <img src="https://img.icons8.com/?size=100&id=21278&format=png&color=000000" alt="HTML5 Logo" width="30">
            <span>Css</span>
        </div>
        <div class="button" style="margin-right: 10px;">
            <img  style="margin-left: -10px;" src="https://img.icons8.com/?size=100&id=84710&format=png&color=000000" alt="HTML5 Logo" width="30">
            <span>Bootstrap</span>
        </div>
    </div>
           

    </div>
</div>
<div>
    <H1 style="color:#b74b4b;font-family:Arial, Helvetica, sans-serif;text-align: center;font-size:30px">Checkout my <br> Resume</H1>
</div>
<br><br>
<div class="resume" style="background-color: #111010;">
    <img src="https://i.ibb.co/KMVg85P/DALL-E-2025-02-27-16-58-37-A-man-with-a-normal-well-proportioned-body-and-a-cute-toy-like-face-He-ha.webp" alt="" style="border-radius: 50%;height:140px;width:150px;margin-left:330px;margin-top:13px">
    <h1 class="resume-name">Gangavaram Saicharan</h1>
    <h2 class="resume-domain">Web developer/Front-end-developer</h2>
    <button class="resumehover" style="background-color: #565252;height:40px;width:120px;font-size:20px;font-weight:600;border-radius:20px;border:2px solid #c84a4a;margin-left:345px;"><a href="https://pdf.ac/3XL8WX" target="_blank" style="text-decoration: none;color:#cb5454">Resume</a></button>
</div>
<br><br><br>
<!-- CONNECT WITH ME -->
<div>
    <h1 style="color:#b74b4b;font-family:Arial, Helvetica, sans-serif;text-align: center;font-size:30px">Connect with me </h1>
</div>
<br>

    <div class="connect">
        <div class="button" style="width:140px;">
            <img src="https://img.icons8.com/?size=100&id=Xy10Jcu1L2Su&format=png&color=000000" alt="HTML5 Logo" width="30">
            <span><a href="https://www.instagram.com/__charan_143?igsh=OWV4NGxqNTllamF2" target="_blank" style="font-weight: bold;color:black;text-decoration:none">Instagram</a></span>
        </div>
        <div class="button" style="width:140px;">
            <img src="https://img.icons8.com/?size=100&id=13930&format=png&color=000000" alt="HTML5 Logo" width="30">
            <span><a href="https://www.linkedin.com/in/saicharan-gangavaram-b0621a253?" target="_blank" style="font-weight: bold;color:black;text-decoration:none">Linkedin</a></span>
        </div>
        <div class="button"style="width:140px;" >
            <img  style="margin-left: -10px;" src="https://img.icons8.com/?size=100&id=118497&format=png&color=000000" alt="HTML5 Logo" width="30">
            <span><a href="https://www.facebook.com/share/1DfH7SEvVk/" target="_blank" style="font-weight: bold;color:black;text-decoration:none">Facebook</a></span>
        </div>
        
    </div>
    <br><br>

    <div class="button" style="width: 350px;margin-left:450px">
        <img src="https://img.icons8.com/?size=100&id=37246&format=png&color=000000" alt="HTML5 Logo" width="30">
        <span><a href="https://mail.google.com/mail/u/0/#inbox?compose=CllgCJNsMBjxQgvxVXVdWhTMDFTBnvvDWVshwmHxFPgMmXfWwKCGLHtmMjXXCVpdMZPVBLvWZVB" target="_blank" style="font-weight: bold;color:black;text-decoration:none">gangavaramcharan5@gmail.com</a></span>
    </div>
 <br>
    <div>
        <img style="height: 300px;width:300px;margin-left:470px" src="https://i.ibb.co/qYX3F1tf/DALL-E-2025-02-27-17-07-28-A-professional-looking-man-with-a-normal-well-proportioned-body-and-a-cut.webp" alt="">
    </div><br><br><br>

    <div class="footer">
        <p>Thank You For Visting</p>
    </div>

</body>
</html>
