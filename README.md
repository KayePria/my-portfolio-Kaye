Welcome to my GitHub page.
<!DOCTYPE html>

<head>
    <link rel="stylesheet" href="style.css">
    <title> Kaye Pria</title>
    <meta name="description" content="Hire a professional writer today">
    <meta name="keywords" content="Writers in Stockholm, Freelance UX and CX, Hire writers">
    <meta name="author" content="Cattrina Mott">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<style>
    @import url('https://fonts.googleapis.com/css?family=Montserrat');
.header-container {
  display: grid;
  width: 70vw;
  min-width: 400px;
  grid-template-columns: auto auto;
  grid-gap: 5px;
  padding: 5px;
  color: white;
  margin: auto;
}

body {
  min-width: 450px;
}

#header {
  font-family: montserrat;
  text-align: center;
  font-style: initial;
  color: whitesmoke;
}

.resume-container {
  display: grid;
  width: 68vw;
  min-width: 400px;
  grid-template-columns:auto-fit (1fr, 1fr);
  grid-gap: 5px;
  padding: 5px;
  background-color: slategray;
  color: white;
  margin: auto;
}

#work-experience {
  color: white;
}

#education {
  color: white;
}

#about-me {
  grid-column-start: 1;
  grid-column-end: 3;
  padding: 10px;
  text-align: justify;
}

.resources-container {
  display: grid;
  width: 68vw;
  min-width: 400px;
  grid-template-columns: auto auto;
  grid-gap: 5px;
  padding: 5px;
  background-color: slategray;
  color: white;
  margin: auto;
}

#learning-strategies {
  margin: auto;
  width: 70%;
}

#resources {
  margin: auto;
  width: 70%;
}

body {
  width: 90vw;
  font-family: montserrat;
  background-image: linear-gradient(black, rgb(51, 51, 51));
}

footer {
  font-size: smaller;
  color: white;
  text-align: center;
}


h4 {
  text-align: center;
  font-weight: bold;
}

img {
  border-radius: 25px;
  padding: 20px;
  width: 200px;
  height: auto;
}

@media screen and (max-width: 600px) {
  img {
    display: none;
  }
  .resume-container {
  display: grid;
  min-width: 350px;
  grid-template-columns: auto-fit;
  grid-gap: 5px;
  padding: 5px;
  background-color: slategray;
  color: white;
  margin: auto;
}
  #about-me {
  padding: 10px;
  text-align: justify;
}

}
</style>
<body>
    <div class="header-container">
        <div id="header" aria-roledescription="Contact details">
            <h1> Kaye Malabanan Pria - Resume </h1>
            <h2> Intern </h2>
            <h3>kaye.pria@g.batstate-u.edu.ph 09155111915</h3>
        </div>

        <div id="profile-img">
            <img src="https://cdn5.vectorstock.com/i/thumb-large/67/24/engineer-icon-profession-and-job-vector-33186724.jpg" alt="Kaye Pria Profile Image"></img>
        </div>
    </div>

    <div class="resume-container" aria-roledescription="Resume">
        <div id="work-experience">
            <h4>Skills</h4>
            <ul>
                <li><i>Microsoft Office</i> - 2012- 2021</li>
                <li><i>Arduino Coding</i> - 2018 - 2021</li>
                <li><i>Verilog Coding</i> - 2020 - 2021 </li>
                <li><i>MATLAB</i> - 2019 - 2021</li>
                <li><i>Multisim</i> - 2018 - 2021</li>
                <li><i>Cadence</i> - 2020 - 2021</li>

            </ul>

        </div>
        <div id="education">
            <h4>Education</h4>
            <ul>
                <li>Recto Memorial National High School - Junior High School</li>
                <li>San Pablo Colleges - Senior High School</li>
                <li>Batangas State University - Present</li>
            </ul>
        </div>


        <div id="about-me">
            <hr />
            <h4>About Me</h4>
            <p>I am Kaye Malabanan Pria, I am 21 years old and I live in Brgy. Bungoy, Dolores, Quezon. I am now a 4th year student taking up Bachelor of Science in Electronics and Communication Engineering Major in Microelectronics in Batangas State University. 
            </p>
            <br />
            <p>Let's chat! You can contact me directly via <a href="https://www.linkedin.com/in/cattrina-mott"
                    target="_blank" aria-label="Contact me on Slack">Slack </a>
                <hr />
        </div>
    </div>

    <div class="resources-container" aria-roledescription="Contact details">

        <div id="learning-strategies">
            <h4>Let's be friends!</h4>
            <p> The following is my social media username:</p>
            <ul>
                <li>Kaye Pria on Facebook</li>
                <li>kayepria on Instagram</li>
                <li>kaye_pria on Twitter</li>

            </ul>


        </div>
        <div id="resources">
            <h4>Resources</h4>
            <p> The following provide useful resources when completing the FooCoding program</p>
            <ul>
                <li> <a href="https://github.com/FooCoding/curriculum" target="_blank">FooCoding Curriculum</a></li>
                <li> <a href="https://www.w3schools.com/" target="_blank">W3 Schools</a></li>
                <li> <a href="https://frontendmasters.com" target="_blank">The Front End Handbook</a></li>
                <li> <a href="https://www.freecodecamp.org/" target="_blank">Free Code Camp</a></li>

            </ul>
        </div>
        <div>

        </div>
    </div>

</body>

</footer>








</html>
