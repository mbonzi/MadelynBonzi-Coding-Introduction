# 05.12.21-Sample-Coding
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <link href="style.css" rel="stylesheet" type="text/css">
  </head>
  <body>
    <nav>
    <div class="main-heading">
      <h1 id="top">Madelyn Bonzi's First Practice for HTML and CSS Coding</h1>
    </div>
    <div class="rel-path-head">
      <ul>
        <li><a href="#Welcome">Welcome!</a></li>
        <li><a href="#About_Me">About Me</a></li>
        <li><a href="#Curriculum">Web Developer Curriculum</a></li>
      </ul>
    </div>
  </nav>
    <br>
    <div class="heading-two">
      <h2 id="Welcome">Welcome to my page! </h2>
    </div>
    <div class="free-text">
      <p>This is the beginning of my coding career. I hope you enjoy seeing my initial progress and where I go from here!</p>
    </div>
    <div class="heading-two">
      <h2 id="About_Me">About Me</h2>
    </div>
    <div class="free-text">
      <p>
        If you were anything like me, when you graduated high school there were so many career fields that interested you that you could not pick just one.
        Not knowing exactly what I wanted to do, I enrolled in a community college in my local town while working two jobs simultaneously.
        I enrolled in courses for a math major, psychology major, fire, and EMT.
        If I didn't know what I wanted when I started undergraduate schooling, let me tell you that I was only getting for confused with every additional course that I enrolled in.
        By the time that I graduated, I had received two promotions, one at each job, and 4 Associates Degrees.
        I then transferred to a community college in Central California where I obtained one more degree within the next year, an AA-T in Kinesiology.
        This degree allowed my to transfer to California Polytechnic University in San Luis Obispo, California.
        After two years of working full-time and attending school full-time, I obtained a Bachelor of Science degree in Kinesiology.
        <br>
        <br>
        This degree propelled me towards my career in healthcare.
        Since graduating, I have worked at an orthopedic surgery clinic which utilizes my knowledge from school, personal training and experience from working at a physical therapy clinic.
        This career has increased my ability to lead a staff, work within a team environment, multitask, and maintain a clear thought-process while under pressure.
        What I did not expect to learn is that what I truly excelled at and enjoyed was organizing, editing, and entering data into our electronic medical record (EMR) systems.
        This part of the job is often described as <em>tedious but necessary</em>; however is what allowed me to finally make an informed decision on the future of my career.
        <br>
        <br>
        <strong> I am very excited for my future in program development and coding!!</strong>
        <br>
      </p>
      <br>
    </div>
    <div class="heading-two">
      <h2 id="Curriculum">Web Developer Curriculum and Tools</h2>
    </div>
    <div class="free-text">
      <form class="dropdown-list" action="index.html" method="post">
       <details>
        <strong><summary> Coding & Programming Courses and Certificates: </summary></strong>
          <ul>
            <li>Introduction to HTML</li>
            <li>Introduction to CSS</li>
            <li>Intermediate CSS </li>
            <li>Advanced CSS Grids</li>
          </ul>
       </details>
       <details>
         <strong><summary> In Progress Coding and Programming Tools: </summary></strong>
           <ul>
              <li>Intermediate HTML</li>
              <li>Intermediate to Advanced CSS</li>
              <li>ATOM</li>
              <li>GitHub</li>
          </ul>
        </details>
        <details>
         <strong><summary> Future Coding and Programming Tools/Certificates: </summary></strong>
           <ul>
              <li>Advanced HTML</li>
              <li>Advanced CSS</li>
              <li>Javascript</li>
              <li>GitHub</li>
              <li>Git</li>
              <li>Python</li>
              <li>React</li>
           </ul>
       </details>
      </form>
    </div>
    <br>
    <!-- DROPDOWN LIST NOT WORKING
<div class="free-text">
      <form class="dropdown-list" action="index.html" method="post">
        <h3><label for="next-courses">Next Steps in My Education:</label></h3>
        <select class="next-courses" name="next-courses" id="future-courses">
          <option value="Javascript">Javascript</option>
          <option value="Git">Git</option>
          <option value="GitHub">GitHub</option>
          <option value="React">React</option>
          <option value="Python">Python</option>
        </select>
      </form>
    </div>
--> 
    <br>
     <nav>
       <div class="rel-path-foot">
         <ul>
          <li><a href="#top">Navigate to Top:</a></li>
        </ul>
      </div>
    </nav>
    <br>
  </body>
</html>


/* style.css */
* {
  padding: 0;
  margin: 0;
  font-size: 20px;
  background-color: rgba(230, 196, 232, 0.5);
  text-align: left;
  color: black;
  text-decoration: none;
}

nav {
  background-color: rgba(211, 167, 220, 0.75);
}

.main-heading {
  text-align: center;
  background-color: rgba(194, 132, 207, 0.5);
  color: rgba(0, 10, 70, 1);
  letter-spacing: 0.3em;
  font-family: Georgia, serif;
  font-weight: 700;
  font-style: italic;
  text-transform: none;
  font-size: 3rem;
  text-decoration: underline;
}

.heading-two {
  color: dark-green;
  font-size: 2rem;
  text-align: left;
  font-family: Georgia, serif;
  background-color: rgba(211, 107, 249, 0.5)
}

.free-text {
  color: black;
  font-size: 1rem;
  background-color: rgba(238, 195, 253, 0.5)
}

.rel-path-head {
  color: rgba(26, 23, 98, 1);
  font-family: 'Times New Roman';
  background-color: light-yellow;
  float: left;
  justify-content: flex-start;
}

a {
  display: block;
  width: 300px;
  margin: auto;
  background-color: rgba(254, 235, 254, 1);
  color: black;
  text-align: left;
  font-size: 1rem;
  padding: 5px 5px;
  border-radius: 5px;
  font-family: Helvetica, serif;
  transition: color 1s linear 0.25s,
              font-size 750ms ease-in 0.25s;
}

.dropdown-list {
  background-color: rgb(100, 20, 20)
  color: black;
  font-size: 3rem;
  font: 'Times New Roman', serif;
}

a:hover {
  color: rgb(178, 8, 5);
  font-size: 1.5rem;
}
