<!DOCTYPE html>
<html>
  <head>
    <title>Nanthan - Portfolio</title>
  </head>
  <style>
    body {
  font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}

/* Navigation Bar */

#home {
  background-color:  #7600bc;
  padding-bottom: 1cm;
  margin-left:-1cm;
  margin-right:-1cm;
  margin-top:-1cm;
  padding-top: 2cm;
  padding-bottom: 2cm;
  height: 5mm;
 }

.topmenu {
  color: lightgray;
  margin: 10px;
  padding: 20px;
  font-size: 20px;
  text-decoration:none;
}

.topmenu:hover {
  color: white;
  /* Add the styles here */
  font-weight: bolder;
  text-decoration: underline;
}

.topdiv {
  float: right;
  padding-right: 1cm;
}

.profile_name {
  float: left;
  padding-left: 2cm;
  color: white;
  font-size: 33px;
}

.profile_name .contact_info {
  font-size: 15px;
  font-style: italic;
  display: flex;
  align-items: center;
  flex-direction: row;
}

.contact_info img {
  width:25px;
  margin-right: 10px;
  float:left;
}

/* Titles */

h2 {
  text-align: justify;
  font-size: 50px;
  text-align: center;
  float: left;
  color: #7600bc;
  margin: 30px;
  margin-left: 60px;
  margin-top: 40px;
  margin-bottom: 0px;
}

.introduction {
  text-align: justify;
  font-size: 30px;
  text-align: center;
  float: left;
  margin-top: 30px;
  margin-bottom: 20px;
  animation-duration: 5s;
  position: relative;
}

/* Used in the About Me sections */

.container {
  display: flex;
}

/* About Me */

.about-me {
  display: flex;
  align-items: center;
}

#about-me h1 {
  font-size: 65px;
  margin-top: 90px;
  color: #7600bc;
}

#about-me p {
  font-size: 25px;
  color: rgb(128, 128, 128);
  margin-top: -1cm;
}

.profile_image {
  width: 550px;
  height: fit-content;
  vertical-align: middle;
  margin: 5px;
}

/* Skills */

.all_skills {
  display: flex;
  flex-direction: row;
  flex-flow: wrap;
}

.skill {
  border: 1px solid gray;
  display: block;
  border-radius: 6px;
  text-align: center;
  margin: 50px;
  padding: 10px;
  width: 2in;
  font-size: 20px;
  box-shadow: 0 3px 10px gray;
}

.skill img {
  height: 35px;
  align-items: center;
}

.skills h6 {
  align-items: center;
  font-size: 20px;
  margin-block-start: 8px;
  margin-block-end: 5px;
  font-weight: bold;
} 

.skills p {
  align-items: center;
  font-size: 15px;
  color: gray;
  margin-block-start: 5px;
  margin-block-end: 5px;
} 

.flex_center {
  display: flex;
  align-items: center;
  justify-content: center;
}

/* Projects */

.projects-container {
  margin-top: 30px;
  margin-left: 60px;
}

.projects-container hr {
  border: 1px solid lightgray;
  width: 75%;
  margin-left: 5cm;
}

.project-card {
  margin: 0 15px 15px 30px;
  padding-bottom: 5px;
}

.project-card h3 {
  font-size: 25px;
  margin-left: 30px;
}

.project-card li {
  font-size: 20px;
  margin-left: 30px;
}

/* Recommendations */

.all_recommendations {
  display: flex;
  align-items: center;
  margin-left: 1in;
  flex-direction: row;
  flex-flow: wrap;
  padding: 20px;
}

.recommendation {
  font-style: italic;
  text-align: left;
  width: 21.875rem;
  padding: 1rem;
  background-color: #fff;
  border-radius: 11px;
  box-shadow: 0 3px 10px var(--primary-shadow);
  padding: 20px;
  margin: 10px;
  border:1px solid gray;
  font-size: 18px;
  height:150px
}

.recommendation span {
  color: #7600bc;
  font-size: 20px;
  font-family: 'Times New Roman', Times, serif;
}

/* Scroll to Top Button */

.iconbutton{
  width: 48px;
  height: 48px;
  border-radius: 100%;
  background-color: #7600bc;
  display: flex;
  align-items: center;
  justify-content: center;
  position: fixed;
  right: 3%;
  bottom: 3%;
  cursor: pointer;
}

/* Form Pop-up */

.popup {
  width:400px;
  background-color: #e8bcf0;
  border-radius: 3mm;
  top: 50%;
  left:50%;
  transform: translate(-50%,-50%);
  text-align: center;
  position: fixed;
  /* padding: 30px; */
  visibility: hidden;
}

.popup img {
  padding-top: 20px;
}

.popup button {
  background-color: #fff;
  border: 1px solid #7600bc;
  color: #7600bc;
  display: block;
  border-radius: 6px;
  text-align: center;
  margin: 50px;
  padding: 10px;
  width: 2in;
  font-size: 20px;
  margin-left: 25%;
}

.popup button:hover {
  background-color: #fff;
  border: 2px solid #7600bc;
  color: #7600bc;
  display: block;
  font-weight: bolder;
  text-align: center;
  cursor: pointer;
  margin-left: 25%;
}

/* Recommendation Form */

input, textarea {
  font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif; 
  margin: 10px;  
  width:100%;
}

fieldset {
  display: flexbox;
  align-content: center;
  justify-content: center;  
  padding: 25px; 
  margin-left: 50px; 
  margin-right: 50px;   
  border: thin solid white;
  width: 50%;
}

/* Buttons */

button {
  background-color: #fff;
  border: 1px solid #7600bc;
  color: #7600bc;
  display: block;
  border-radius: 6px;
  text-align: center;
  margin: 50px;
  padding: 10px;
  width: 2in;
  font-size: 20px;
}

button:hover {
  background-color: #7600bc;
  border: 1px solid #7600bc;
  color: #fff;
  display: block;
  border-radius: 6px;
  text-align: center;
  cursor: pointer;
}
  </style>
  <body>
    <!-- Navigation Bar -->
    <nav>
      <div id="home">
        <div class="profile_name">
          Nanthan S Nair
          <div class="contact_info">
            <img src="html_finalprojimages/envelope.png" alt="https://icons8.com/icon/124377/circled-envelope"/>
          123@gmail.com
        </div>
        <div style="clear:both;"></div>
        <div class="contact_info">
          <img src="html_finalprojimages/phone.png" alt="https://icons8.com/icon/124377/circled-envelope"/>
          +13456764598

        </div>
        </div>
        <div class="topdiv">
          <a class="topmenu" href="#about-me">About Me</a>
          <!-- Add the links for Skills, Projects and Recommendation here -->
          <a class="topmenu" href="#skills">Skills</a>
          <a class="topmenu" href="#projects">Projects</a>
          <a class="topmenu" href="#recommendations">Recommendations</a>
        </div>
      </div>    
    </nav>

    <!-- About Me -->
    <section id="about-me" class="container">
      <div>
        <img src="html_finalprojimages/coworking-male-programmer-writing-program-code.gif" class="profile_image"/>
      </div>

      <div>
          <h1>
            Hi, I'm Nanthan <img src="html_finalprojimages/waving-hand.png" width="60px"/>
          </h1>
          <p>
            I am a full stack developer 
            I have worked on applications and microservices in my collage clubs
            I like to watch youtube an study
          </p>
      </div>
    </section>
              
    <!-- Skills -->
    <section id="skills">
      <h2>Skills</h2>
      <div style="clear:both;"></div>

      <div class="all_skills">
        <div class="skill">
          <img src="html_finalprojimages/html5.png"/>
          <h6>HTML</h6>
          <p>3 Months experience</p>
        </div>  

        <div class="skill">
          <img src="html_finalprojimages/js.jpeg"/>
          <h6>JavaScript</h6>
          <p>2 Monthsexperience</p>
        </div>  

        <!-- Add more skills here -->
        <div class="skill">
            <img src="html_finalprojimages/java.png"/>
            <h6>Java</h6>
            <p>.5 years experience</p>
          </div>  

          <div class="skill">
            <img src="html_finalprojimages/node.png"/>
            <h6>Node</h6>
            <p>1 Month experience</p>
          </div>  

          <div class="skill">
            <img src="html_finalprojimages/react.png"/>
            <h6>React</h6>
            <p>1 Monthexperience</p>
          </div>  

      </div>
    </section>
          
    <!-- Projects -->
    <section class="projects" id="projects">
        <h2>Projects</h2>
        <div style="clear:both;"></div>
        <div id="projects-container" class="projects-container">
          <div class="project-card">
            <h3>Amazon Clone Website</h3>
            <ul>
              <li>Designed and developed a fully functional e-commerce website mimicking the functionalities of Amazon, including user authentication, product browsing, and checkout.</li>
            </ul>
          </div>
          <hr>
          <div class="project-card">
            <h3>Electronic Voting Machine</h3>
            <ul>
              <li>Engineered an electronic voting machine application allowing secure and efficient voting processes, incorporating cryptographic protocols to ensure integrity and confidentiality.</li>
            </ul>
          </div>
          <hr>
          <div class="project-card">
            <h3>Flutter Weather App</h3>
            <ul>
              <li>Developed a cross-platform mobile application using Flutter framework that provides real-time weather updates and forecasts based on user's location, utilizing APIs from various weather services.</li>
            </ul>
          </div>
        </div>
      </section>
      <div style="clear:both;"></div>
      

    <!-- Recommendations -->
    <section id="recommendations">
      <h2>Recommendations</h2>
      <div style="clear:both;"></div>
      <div class="all_recommendations" id="all_recommendations">
        <div class="recommendation">
          <span>&#8220;</span>
          Nanthan demonstrates exceptional aptitude in swiftly grasping fundamental concepts of Web development. 
          His positive attitude and collaborative nature make him an invaluable asset to any team. 
          
          <span>&#8221;</span>
        </div>
        <div class="recommendation">
          <span>&#8220;</span>
          Working with Nanthan is a breeze; his quick learning ability and positive attitude make collaboration seamless. 
          He's a natural team player, always ready to lend a hand and share insights. 
          Nanthan is always ready in taking initiative which propels projects forward effortlessly.
          <span>&#8221;</span>
        </div>
        <div class="recommendation">
          <span>&#8220;</span>
          Nanthan is a joy to work with; his curiosity drives innovation, and his proactive nature keeps the team motivated.
        He's a reliable teammate who consistently goes above and beyond to deliver exceptional results.
          <span>&#8221;</span>
        </div>
      </div>
    </section>

    <!-- Recommendation Form -->
    <section id="contact">
      <div class="flex_center">
        <fieldset>
          <legend class="introduction">Leave a Recommendation</legend>          
          <input type="text" placeholder="Name (Optional)"> <br/>
          <textarea id="new_recommendation" cols="500" rows="10" placeholder="Message"></textarea>
          <div class="flex_center">
            <button id="recommend_btn" onclick="addRecommendation()">Submit</button>
          </div>
        </fieldset>
      </div>
    </section>

    <div class="iconbutton">
      <a href="#home">
        <!--Add the code here for the logo to appear and the icon to be actionable-->
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="white" width="63px">
            <path stroke-linecap="round" stroke-linejoin="round" d="M15 11.25l-3-3m0 0l-3 3m3-3v7.5M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
          </svg>
      </a>
    </div>

    <div class="popup" id="popup" class="flex_center">
      <img src="html_finalprojimages/checkmark--outline.svg"/>
      <h3>Thanks for leaving a recommendation!</h3>
      <button onclick="showPopup(false)">Ok</button>
    </div>
  <script>
  function addRecommendation() {
    // Get the message of the new recommendation
    let recommendation = document.getElementById("new_recommendation");
    // If the user has left a recommendation, display a pop-up
    if (recommendation.value != null && recommendation.value.trim() != "") {
      console.log("New recommendation added");
      //Call showPopup here
      showPopup(true);
      // Create a new 'recommendation' element and set it's value to the user's message
      var element = document.createElement("div");
      element.setAttribute("class","recommendation");
      element.innerHTML = "\<span\>&#8220;\</span\>" + recommendation.value + "\<span\>&#8221;\</span\>";
      // Add this element to the end of the list of recommendations
      document.getElementById("all_recommendations").appendChild(element); 
      
      // Reset the value of the textarea
      recommendation.value = "";
    }
  }
  
  function showPopup(bool) {
    if (bool) {
      document.getElementById('popup').style.visibility = 'visible'
    } else {
      document.getElementById('popup').style.visibility = 'hidden'
    }
  }
  </script>
  </body>
  
</html>
