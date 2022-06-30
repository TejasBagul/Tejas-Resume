*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    list-style: none;
    font-family: 'Nunito', sans-serif;
}

body{
    background-color: #6e6e73;
}

.main-content{
    min-height: 100vh;
    width: 80%;
    margin: 2rem auto;
    display: grid;
    grid-template-columns: repeat(7, 1fr);
}

.left-section{
    grid-column: span 2;
    height: 100%;
    background-color: #0b090a;
}
.right-section{
    grid-column: span 5;
    background-color: #f7f7f7;
    height: 100%;
}


.left-content{
    padding: 2rem 3rem;
}
.profile{
    width: 100%;
    border-bottom: 1px solid #002333;
}

.image{
    width: 100%;
    text-align: center;
}
.profile-image img{
    width: 75%;
    border-radius: 50%;
    border: 8px solid #94D9EA;
    
}
.discription{
    font-size: 0.75rem;
    text-align: center;
    padding: 1rem;
    color: #f7f7f7;
}

.name{
    font-size: 1.2rem;
    color: white;
    text-align: center;
    text-transform: uppercase;
    letter-spacing: 1px;
    padding: 1.2rem 0;
}

.designation{
    font-size: 1rem;
    color: white;
    text-align: center;
    text-transform: uppercase;
    letter-spacing: 1px;
    padding: 1.2rem 0;
}

.career{
    font-size: 1.2rem;
    color: #94D9EA;
    text-align: center;
    text-transform: uppercase;
    letter-spacing: 1px;
    padding-bottom: 1rem;
}

.main-title{
    font-size: 1.8rem;
    text-transform: uppercase;
    letter-spacing: 1px;
    color: #f7f7f7ec;
    padding-top: 3rem;
}

.contact-info ul{
    padding-top: 2rem;
   
}

.contact-info ul li{
    padding: .4rem 0;
    display: flex;
    align-items: center;
    color: #718096;
}
.contact-info ul li i{
    padding-right: 1rem;
    font-size: 1.2rem;
    color: #2D9CDB;
}

.skills-section ul{
    padding-top: 2rem;
}
.skills-section ul li{
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    padding: .4rem 0;
}

.progress-bar{
    width: 100%;
    height: .4rem;
    background-color: #2f81ed5b;
    position: relative;
    border-radius: 12px;
}
.progress{
    height: 100%;
    position: absolute;
    left: 0;
    background-color: #2D9CDB;
    border-radius: 12px;
}
.js-progress{
    width: 80%;
}
.ps-progress{
    width: 70%;
}
.j-progress{
    width: 85%;
}
.c-progress{
    width: 80%;
}
.n-progress{
    width: 70%;
}
.w-progress{
    width: 78%;
}


.skill-title{
    text-transform: uppercase;
    color: #f7f7f7;
    font-size: 1rem;
}

.sub-title{
    padding-top: 2rem;
    font-size: 1.2rem;
    text-transform: uppercase;
    color: #f7f7f7;
}

.sub-para{
    color: #ccc;
    padding: .4rem 0;
}

.references-section li{
    color: #ccc;
    padding: .2rem 0;
}
.references-section li i{
    padding-right: .5rem;
    font-size: 1.2rem;
    color: #2D9CDB;
}

.right-main-content{
    padding: 2rem 3rem;
}


.right-title{
    letter-spacing: 1px;
    text-transform: uppercase;
    color: #2F80ED;
    margin-bottom: 1.2rem;
    position: relative;
}

.right-title::after{
    content: "";
    position: absolute;
    width: 60%;
    height: .2rem;
    background-color: #ccc;
    border-radius: 12px;
    right: 0;
    top: 50%;
    transform: translateY(-50%);
}

.para{
    line-height: 1.6rem;
    color: #718096;
    font-size: 1.1rem;
}

.sect{
    padding-bottom: 2rem;
}

.timeline{
    display: grid;
    grid-template-columns: repeat(2, 1fr);
}

.tl-title{
    letter-spacing: 1px;
    font-size: 1.3rem;
    color: #002333;
    text-transform: uppercase;
}
.tl-title-2{
    letter-spacing: 1px;
    font-size: 1.3rem;
    color: #2D9CDB;
    text-transform: uppercase;
}

.tl-content{
    border-left: 1px solid #ccc;
    padding-left: 2rem;
    position: relative;
    padding-bottom: 2rem;
}

.tl-title-2::before{
    content: "";
    position: absolute;
    width: .7rem;
    height: .7rem;
    background-color: #2D9CDB;
    border-radius: 50%;
    transform: translateX(-50%);
    left: 0;
}

/*Media Querries*/
@media screen and (max-width:823px){
    .right-title::after{
        width: 40%;
    }
}
@media screen and (max-width:681px){
    .right-title::after{
        width: 30%;
    }
}
@media screen and (max-width:780px){
    .timeline{
        grid-template-columns: repeat(1, 1fr);
    }
}
@media screen and (max-width:780px){
    .left-section{
        grid-column: span 3;
    }
    .right-section{
        grid-column: span 4;
    }
}
@media screen and (max-width:1200px){
    .main-content{
        grid-template-columns: repeat(1, 1fr);
    }
    .profile img{
        width: 40%;
    }
}
@media screen and (max-width:700px){
    .profile img{
        width: 60%;
    }
}
@media screen and (max-width:390px){
    .name{
        font-size: 1.5rem;
    }
}


<!---Html Part-->

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Resume</title>
    <link rel="preconnect" href="https://fonts.gstatic.com" />
    <link rel="stylesheet" href="Tejas.css" />
    <link
      href="https://fonts.googleapis.com/css2?family=Poppins:wght@100;300;400;600&display=swap"
      rel="stylesheet"
    />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"
    />
  </head>
  <body>
    <main class="main-content">
      <section class="left-section">
        <div class="left-content">
          <div class="profile-image">
            <div class="image">
              <img src="Tejas Passport Size Photo.JPG" alt="" />
            </div>
            <h2 class="name">Tejas Bagul</h2>
            <p class="sub-para">Associate Software Engineer</p>
          </div>
          <div class="contact-info">
            <h3 class="main-title">Contact Information</h3>
            <ul>
              <li>
                <i class="fa fa-phone"></i>
                +917558324464
              </li>
              <li>
                <i class="fa fa-google"></i>
                tejasbagul2017@gmail.com
              </li>
              <li>
                <i class="fa fa-linkedin"></i>
                https://www.linkedin.com/in/tejas-bagul-b243691ba
              </li>
              <li>
                <i class="fa fa-github"></i>
                https://github.com/TejasBagul
              </li>
              <li>
                <i class="fa fa-instagram"></i>
                @mr.hollister._07
              </li>
              <li>
                <i class="fa fa-map-marker"></i>
                Nashik, Maharashtra
              </li>
            </ul>
          </div>
          <div class="description">
            Software developer
          </div>
          <div class="skills-section">
            <h3 class="main-title">Skills</h3>
            <ul>
              <li>
                <p class="skill-title">SQL</p>
                <div class="progress-bar">
                  <div class="progress js-progress"></div>
                </div>
              </li>
              <li>
                <p class="skill-title">Java</p>
                <div class="progress-bar">
                  <div class="progress ps-progress"></div>
                </div>
              </li>
              <li>
                <p class="skill-title">HTML</p>
                <div class="progress-bar">
                  <div class="progress c-progress"></div>
                </div>
              </li>
              <li>
                <p class="skill-title">CSS</p>
                <div class="progress-bar">
                  <div class="progress ps-progress"></div>
                </div>
              </li>
              <li>
                <p class="skill-title">Javascript</p>
                <div class="progress-bar">
                  <div class="progress n-progress"></div>
                </div>
              </li>
              <li>
                <p class="skill-title">MERN</p>
                <div class="progress-bar">
                  <div class="progress ps-progress"></div>
                </div>
              </li>
            </ul>
          </div>
          <div class="references-section">
            <h3 class="main-title">Achievements</h3>
            <div class="referee">
             <!---- <h6 class="sub-title">Paper presentation Competition-</h6> -->
              <p class="sub-para">●	Winner at State level Paper Presentation Competition in Sau. Sundarabai Manik Adsul Polytechnic, Ahmednagar.</p>
                <p class="sub-para">● Winner at National level Paper presentation Competition in Samartha group of Institutions College of engineering, Belhe, Ahmednagar.</p>
                <p class="sub-para">● Winner at State level Debate Competition Dr. V.V.P. Polytechnic, Loni, Ahmednagar.</p>
            </div>
          <!--<div class="references-section">
            <h3 class="main-title">Certified COURSES</h3>
            <div class="referee">
              <h6 class="sub-title">Full Stack Web Development Courses-</h6>
              <p class="sub-para">Newton School (March 2022 - present) </p>
              <h6 class="sub-title"> Hardware in Loop Technology Course</h6>
            </div> -->
            <div class="referee">
              <h6 class="sub-title">Soft Skills</h6>
              <p class="sub-para">● Ability to work under pressure<br> ● Leadership <br> ●	Quick Learner</p>
            </div>
            <div class="referee">
              <h6 class="sub-title">Languages Known</h6>
              <p class="sub-para">● English<br> ● Marathi <br> ● Hindi</p>
            </div>
            <div class="referee">
              <h6 class="sub-title">Hobbies</h6>
              <p class="sub-para">●	Guitarist <br> ● Dancer <br> ● Trekker</p>
            </div>
      </section>
      <section class="right-section">
        <div class="right-main-content">
          <section class="about sect">
            <h2 class="right-title">About Me</h2>
            <p class="para">
     <<<<< Hi,I'm a very ambitious front-end developer looking for a role in an established IT company with the opportunity to work with the technologies on challenging and diverse projects.
           I'm quietly confident, naturally curious, and perpetually working on improving my chops one design problem at a time>>>....
            </p>
          </section>
          <section class="experince sect">
            <h2 class="right-title">Experience</h2>
            <div class="timeline">
              <div class="left-tl-content">
                <h5 class="tl-title">Motherson Sumi wiring India Ltd pune</h5>
                <p class="para">25- March-2K21 to 24-April-2K22</p>
              </div>
              <div class="right-tl-content">
                <div class="tl-content">
                  <h5 class="tl-title-2">Graduate Enginner Trainee (VDP)</h5>
                  <p class="para">
                    <span>&#8226;</span> Hands on Experiance on oracle Software<br>
                    <span>&#8226;</span> Implemented Purchasing form Import/Local Supply Chain<br>
                    <span>&#8226;</span> Tracking Daily Shortage Sheet on Excel.
                  </p>
                </div>
              </div>
            </div>
            <!---<div class="timeline">
              <div class="left-tl-content">
                <h5 class="tl-title">Noitavonee India, Kolhapur</h5>
                <p class="para">28-December-2K21 to 28-April-2K22</p>
              </div> 
              <div class="right-tl-content">
                <div class="tl-content">
                  <h5 class="tl-title-2">Intern</h5>
                  <p class="para">
                    <span>&#8226;</span> Worked on silo NFT website project.<br>
                    <span>&#8226;</span> Implemented in codeigniters framework using PHP,HTML,CSS,JS.<br>
                    <span>&#8226;</span> Worked on chrome extension for wallet creation.<br>
                    <span>&#8226;</span> Research and learning in Blockchain.
                  </p>
                </div>
              </div>
            </div>->
            <!-- <div class="timeline">
              <div class="left-tl-content">
                <h5 class="tl-title">Google Inc</h5>
                <p class="para">2019 - 2020</p>
              </div>
              <div class="right-tl-content">
                <div class="tl-content">
                  <h5 class="tl-title-2">Lead Web developer</h5>
                  <p class="para">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Molestias cupiditate vitae voluptatem deleniti, laboriosam
                    odio nobis quae fugit facilis quo.
                  </p>
                </div>
              </div>
            </div> -->
            <!-- <div class="timeline">
              <div class="left-tl-content">
                <h5 class="tl-title">Apple</h5>
                <p class="para">2020 - Present</p>
              </div>
              <div class="right-tl-content">
                <div class="tl-content">
                  <h5 class="tl-title-2">Senior Developer</h5>
                  <p class="para">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Molestias cupiditate vitae voluptatem deleniti, laboriosam
                    odio nobis quae fugit facilis quo.
                  </p>
                </div>
              </div>
            </div> -->
          </section>
          <section class="education sect">
            <h2 class="right-title">education</h2>
            <div class="timeline">
              <div class="left-tl-content">
                <h5 class="tl-title">Sandip institute of  Engineering and Management, Nashik.</h5>
                <p class="para">2017 - 2020</p>
              </div>
              <div class="right-tl-content">
                <div class="tl-content">
                  <h5 class="tl-title-2">Bachelor in Electrical Engineer</h5>
                  <p class="para">
                    Board : Savitribai Phule Pune University, Pune.
                    B.Tech (2020) - 6.83 (60.10 % Agg) <br> | T.Y. (2019) – 7.40 (65.12%) </br>| S.Y. (2018) – 5.52 (48.57%)
                  </p>
                </div>
              </div>
            </div>
            <div class="timeline">
              <div class="left-tl-content">
                <h5 class="tl-title">Government Polytechnic, Ahmednagar.</h5>
                <p class="para">2014 - 2017</p>
              </div>
              <div class="right-tl-content">
                <div class="tl-content">
                  <h5 class="tl-title-2">Diploma</h5>
                  <p class="para">
                    Board : Maharashtra State Board of Technical Education, Mumbai. <br>
                    Percent : 83.15%
                  </p>
                </div>
              </div>
            </div>
            <div class="timeline">
              <div class="left-tl-content">
                <h5 class="tl-title"> Vidya Vikas Public School, Babhaleshwar Ahmednagar</h5>
                <p class="para">2014</p>
              </div>
              <div class="right-tl-content">
                <div class="tl-content">
                  <h5 class="tl-title-2">School</h5>
                  <p class="para">
                    Board: Maharashtra State Board of Secondary and Higher Secondary Education, Pune.<br>
                    Percent : 83.20 %
                  </p>
                </div>
              </div>
            </div>
          </section>
          <section class="awards sect">
            <h2 class="right-title">Projects</h2>
            <div class="timeline">
              <div class="left-tl-content">
                <h5 class="tl-title">BE Project: </h5>
                <p class="para">2019- 2020</p>
              </div>
              <div class="right-tl-content">
                <div class="tl-content">
                  <h5 class="tl-title-2">Solar Bag-pack –</h5>
                  <p class="para">
                    <span>&#8226;</span>●	It is a system which uses solar energy to charge the several devices in the bag during traveling, trekking or other purposes.<br>
                   <!---- <a href="https://github.com/SohamPatil1888/Time-Table-App" style="color: #718096;">More details...</a>-->
                  </p>
                </div>
              </div>
            </div>
            <div class="timeline">
              <div class="left-tl-content">
                <h5 class="tl-title">Diploma project: </h5>
                <p class="para">2016 - 2017</p>
              </div>
              <div class="right-tl-content">
                <div class="tl-content">
                  <h5 class="tl-title-2">Smart Energy Meter-</h5>
                  <p class="para">
                    <span>&#8226;</span> ● It is a system which operates on GSM module provides electricity utilization to consumers also it conveys the message through certain codes and gives access to consumer to pause the utility connection till interval breaks.<br>
                   <!---- <span>&#8226;</span> Implemented machine learning concept using python.<br>
                    <span>&#8226;</span> Wrote frontend code in HTML,CSS,JS. <br>
                    <a href="https://github.com/harshwardhanedu/car_price_prediction/tree/master" style="color: #718096;">More details...</a> -->
                  </p>
                </div>
              </div>
            </div>
           <!---- <div class="timeline">
              <div class="left-tl-content">
                <h5 class="tl-title"> <br>Mini Project</h5>
                <p class="para">Mini Project</p>
              </div> -->
               <!--<div class="right-tl-content">
                <div class="tl-content">
                  <h5 class="tl-title-2">MERN Stack </h5>
                  <p class="para">
                    <span>&#8226;</span> Worked on student committees which are currently working in
                    campus to provide multiple events for students.<br>
                    <span>&#8226;</span> Provided an online registration <br>
                    <a href="https://github.com/harshwardhanedu/Student-Association-System/tree/master" style="color: #718096;">More details...</a>
                  </p>
                </div>
              </div>
            </div> -->
          </section>
          <section class="awards sect">
            <h2 class="right-title">Certified Cource</h2>
            <div class="timeline">
              <div class="left-tl-content">
                <h5 class="tl-title">Full Stack Web Development course</h5>
              </div>
              <div class="right-tl-content">
                <div class="tl-content">
                  <h5 class="tl-title-2">Newton School</h5>
                  <p class="para">
                    March 2K22 - Present
                  </p>
                </div>
              </div>
              <div class="left-tl-content">
                <h5 class="tl-title">Hardware and Loop Technology</h5>
              </div>
              <div class="right-tl-content">
                <div class="tl-content">
                  <h5 class="tl-title-2">Sandip University Nashik</h5>
                  <p class="para">
                    March 2K18
                  </p>
                </div>
              </div>
            </section>
            <section class="awards sect">
              <h2 class="right-title">Declaration</h2>
              <div class="timeline">
                <div class="left-tl-content">
                  <h5 class="tl-title">I solemnly declare that the above information is true and correct to the best of my knowledge.</h5>
                </div>
                <div class="right-tl-content">
                  <div class="tl-content">
                  <!---- <h5 class="tl-title-2">Newton School</h5> -->
                    <p class="para">
                      Date- <br>
                      Place- 
                    </p>
                  </div>
                </div>
            </div>
          </section>
        </div>
      </section>
    </main>
  </body>
</html>



