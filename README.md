<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="website icon" type="img" href="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQbwoTi3LRMJuwXsZkbPVoC0LXxtPe2gnRybA&s">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Protest+Guerrilla&display=swap" rel="stylesheet" >
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Ubuntu:ital,wght@0,300;0,400;0,500;0,700;1,300;1,400;1,500;1,700&display=swap" rel="stylesheet">
    <style>
        *{
            box-sizing: border-box;
            margin: 0px;
            padding: 0px;
        }
        .All{
            background-color: #660033;
            height: 1200px;
        }
        .name{
            color: white;
            font-family:'Protest Guerrilla',sans-serif;
            padding-left: 70px;
            padding-top: 60px;
            font-size:30px;
        }
        .bt{
            background-color:#660033 ;
            color: white;
            width: 100px;
            height: 30px;
            margin-top:20px ;
            margin-left:70px ;
        }
        .bt:hover{
            cursor: pointer;
            color: black;
        }
        .tit{
            color: white;
            font-family: 'Ubuntu', sans-serif;
            margin-top:40px ;
            margin-left: 70px;
        }
        .about{
            color: white;
            font-size: 15px;
            padding-left: 70px;
            padding-top: 20px;
        }
        .tit1{
            font-family: 'Ubuntu', sans-serif;
            color: white;
        }
        .skills-table {
    border-collapse: collapse;
    text-align: center;
    font-family: 'Ubuntu', sans-serif;
    margin-left: 70px;
    margin-top: 30px;

}

.skills-table th, .skills-table td {
    border: 1px solid white;
    padding: 5px;
    color:#A0A0A0;
    ;
}

.skills-table th {
    background-color: #f4f4f4;
    color: black;
}
.soft{
    border-collapse: collapse;
    text-align: center;
    font-family: 'Ubuntu', sans-serif;
    margin-left: 70px;
    margin-top: 30px;
    position: absolute;
    left: 200px;
    top: 495px;
}
.soft th, .soft td {
    border: 1px solid white;
    padding: 5px;
    color: #A0A0A0;
}
.soft th {
    background-color: #f4f4f4;
    color: black;
}
.soft td:hover{
    background-color: black;
    cursor: pointer;
}
.skills-table td:hover{
    background-color: black;
    cursor: pointer;
}
.cert{
color: white;
font-family: 'Ubuntu', sans-serif;
margin-left: 70px;
margin-top: 40px;
}


.custom-bullets li {
    position: relative;
    padding-left: 70px; 
    margin-bottom: 10px;
    margin-top: 20px;
    color:#A0A0A0;
}

.custom-bullets li::before {
    content: "✔️";
    position: absolute;
    left: 40px;
    font-size: 18px; 
}
.ime{
    position: absolute;
    top: 50px;
    right:  150px;
    z-index: 1;
}
.anime{
    width: 50px;
    height: 50px;
    background-color: white;
    position: absolute;
    border-radius: 20%;
    top: 380px;
    right: 350px;
    animation-name: ani;
    animation-duration: 3s;
    animation-iteration-count: infinite;
    animation-timing-function: linear;
}
@keyframes ani{
0%{top: 380px;right: 350px;background-color: #660033;}
100%{top: 330px;right: 300px}

}
    </style>
</head>
<body>
    <div class="All">
    <p class="name">HI <br>
                    I'M JOMIS JERALD <br>
                    JAVA FULL STACK DEVELOPER
    </p>
 <a href="https://wa.me/qr/EPAC3M6P7ML7G1"> <button class="bt">Contact me</button></a>
    <h2 class="tit">ABOUT ME</h2>
    <p class="about">
        Jomis Jerald R.<br>
        I am a dedicated and detail-oriented Computer Applications <br> graduate from Bharathiar University,<br> with a focus on Java full-stack development and self-driven projects. <br> My academic journey has helped me develop <br> critical thinking, teamwork, and adaptability, qualities <br> that I am eager to apply in a professional setting.
      </p>
      <h2 class="tit 1">MY SKILLS</h2>
      <table class="skills-table">
        <tr>
            <th>TECHNICAL SKILLS</th>
        </tr>
        <tr>
            <td>CORE-JAVA</td>
        </tr>
        <tr>
            <td>JAVASCRIPT</td>
        </tr>
        <tr>
            <td>HTML 5 & CSS 3</td>
        </tr>
        <tr>
            <td>BOOTSTRAP 5</td>
        </tr>
        <tr>
            <td>REACT</td>
        </tr>
        <tr>
            <td>SQL</td>
        </tr>
        <tr>
            <td>GIT & GITHUB</td>
        </tr>
    </table>
    <table class="soft">
            <tr>
                <th>SOFT SKILLS</th>
            </tr>
            <tr>
                <td>TIME MANAGEMENT</td>
            </tr>
            <tr>
                <td>ADAPTABILITY</td>
            </tr>
            <tr>
                <td>CURIOUSITY</td>
            </tr>
            <tr>
                <td>WORK ETHIC</td>
            </tr>
            <tr>
                <td>PATIENCE</td>
            </tr>
    </table>
    <h2 class="cert">CERTIFICATES</h2>
    <ul class="custom-bullets">
        <li>I have completed the "Altaya Solutions" Full Stack Development course.</li>
        <li>I have completed the "Great Learning" Java online course.</li>
        <li>Naan Mudhalvan Certificate for completing Microsoft Office 365 Productivity.</li>
        <li>Be10X on ChatGPT & AI Tools Workshop.</li>
    </ul>
    <div class="ime"><img style="border-radius: 50%; width: 200px;height: 200px;" src="\e2a7efa8-47be-4590-a0c4-24bd0b5e779e (1).jfif " alt=""> </div>
    <div class="anime"></div>
    </div>
</body>
</html>
