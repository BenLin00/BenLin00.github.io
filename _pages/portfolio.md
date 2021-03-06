---
layout: page
title: My Portfolio of PM, SWE, and Consulting Projects
permalink: /portfolio
comments: false
---

<p>
Here are a few of my project highlights from over the past few years.
</p>
<a href="#PM_section" class="btn btn-peach">Product Management</a> 
<a href="#SWE_section" class="btn btn-teal">Software Engineering</a> 
<a href="#consulting_section" class="btn btn-purple">Consulting Projects</a>

<br>
<!-- PM Projects
================================================== -->
<section>
    <div id="PM_section" class="section-title">
        <h1 class = "display-4"><span>Product Management / Design </span></h1>
    </div>
</section>

<div class="row justify-content-between">

<div class="col-md-9 pr-5">
<h2> Spotify Public Queue Feature (Fall 2020)</h2>

<p> The most common PM interview question I get asked is: <br>
<u><b> "Tell me about your favorite product and what you would change about it" </b></u>
<br> <br>
I made a <b>mock-up</b> of my response: <br>
I LOVE Spotify -- a music streaming platform with great features to organize your favorite music, manage playlists, and discover new music. However, it’s social functionality is slightly lacking. Spotify Stories are currently in production and a fan favorite feature is the right column of the webapp -- "Friend Activity". Users love seeing what their friends are listening to in real-time. I built upon this. </p>

<p>User Research tells us:
<ul> <li>26% of Spotify users are Age 18-24 </li>
<li>29% of Spotify are Age 25-35 </li> </ul>
I started by building a couple user personas. Take James below as a example: a social college student bored in quarantine and missing his friends.
<img src="/assets/images/portfolio-photos/spotify/UserPersona.png" alt="James Spotify user persona">
</p>

<p>
Spotify needs a cleaner way to share songs. Currently, users share a url link via another social media. This is distracting for users. It's more convenient to have song recommendations in a centralized location -- right on the Spotify App.
</p>

<p>
I designed the workings of a new feature -- a <b> Public Queue </b> to contain all the songs your friends want to drop you. This would have the feel of a shared playlist, so users can see who's recommending which song, with controls to sort it by title, artist, or the user who dropped it. But songs would also pop-off the <u>Public Queue</u> and into <u>History</u>, characteristically of a queue. I made a demo in Figma below!:
<img src="/assets/images/portfolio-photos/spotify/PublicQueue.gif" alt="gif of public queue">
</p>

<br>
<p>
<h5> Social Feature </h5>
Having a Friend Activity <b>search function </b> on Spotify would both 1) allow users to see what specific friends have last listened to, and 2) create opportunity for song sharing through the familiar Spotify UI. I made demo for this as well below: <br>
<img src="/assets/images/portfolio-photos/spotify/ShareFriend.gif" alt="share song to friend's public queue gif"> <br>
Of course, we need a pop-up "Are you sure?" box, in case James drops a song on the wrong person by accident! 
</p>
<br>

<p>
<h5> Seamless Integration </h5>
Finally, this needs a little seamless integration! There's two ways users currently add to their private queue. I expanded on both below:

<div class="row">
<div class="col-sm">
<b> Right-Click </b>
<img src="/assets/images/portfolio-photos/spotify/rightClick.gif" alt="rightclick add song to queue gif" width = "100%">
</div>
<div class="col-sm">
<b> Click-and-Drag </b>
<img src="/assets/images/portfolio-photos/spotify/DragToIcon.gif" alt="drag to icon to add song to queue gif" width = "100%">
</div>
</div>
</p>

<br>
<h5> Use Cases</h5>
<ul>
    <li> Parties and other social gathering are accompanied by music. Playing someone's Public Queue would let anyone drop their song requests into aux wordlessly and from their own device.
    </li>
    <li> This feature centralizes song recommendations from several friends into one location -- it's casual and non-disruptive to another social media space.
    </li>
</ul>
Both of these are perfect for our User Persona James, who loves to talk about music and share music between friends. The problem with Spotify's currently beta Group Session is that users can only override the currently playing song, and currently has a 5 person limit.
<br> <br>

<blockquote class="blockquote">
  <p class="mb-0">
  I used Asana as my Agile Scrum task manager and Figma to design these mockups. <br> 
  The clickable demo can be found
  <a href="https://www.figma.com/proto/jcbpf2iKJn1bSSD6oQyXAW/Spotify-Redesign?node-id=1%3A7&scaling=scale-down" target="_blank"> here.</a>  
  </p>
</blockquote>
<img src="/assets/images/portfolio-photos/spotify/FigmaDemo.png" alt="drag to icon to add song to queue gif" width="100%">
<br>
I created this project as part of the "Out In Tech" Fall 2020 University Mentorship program under the guidance of my mentor, Khoa Ma.

<hr style="height:8px;border:none;color:green;background-color:green;" />
<hr style="height:8px;border:none;color:green;background-color:green;" />
<hr>

<br>
<h2><u> Target COVID-19 Store Occupany Tracker (Aug 2020)</u></h2>
<img src="/assets/images/portfolio-photos/TargetMap.png" alt="Target capacity tracker in-app map" width="100%">


<h6> Hackathon Winner: "Overall Winner" and "Most Technically Challenging" </h6> 
<p> As part of the Target Diversity Leadership Symposium Conference during August 2020, I worked on a project with 3 teammates to design an app that would help customers locate nearby Target stores and how crowded each store is as it reaches maximum COVID-19 regulated capacity.</p>

<p>
<h6> Background </h6>
We created a mock-up of the application feel. During events where stores experience overcrowding, employees are often stationed at each entrance to limit customer capacity. The limited occupancy demands of COVID-19 have exacerbated this problem. This Fall 2020 Semester, a new Target store opened up next to UIUC campus where I was located. Nearly every other day during its first month of opening, there was a line of people waiting outside to enter the store.
</p>

<p>
<h6> Description </h6>
This app allows users to view nearby Target stores according to the user's GPS location. Store locations are highlighted on a Google Map Services-powered map in color according to occupancy--
<ul>
<li> Red: if there is a line of people waiting outside store </li>
<li> Yellow: if the store is approximately at max occupancy </li>
<li> Green: if the store occupancy is not near max occupancy. </li>
</ul>
</p>

<h6> Check out this demo!:</h6>
<video width="200" height="420" controls>
  <source src="/assets/videos/TargetCapacityTracker.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>
<br>

Check out the slides from our presentation <a target="_blank" href="https://ter.ps/targetHack">here</a>

<hr style="height:8px;border:none;color:green;background-color:green;" />
<hr style="height:8px;border:none;color:green;background-color:green;" />
<hr>

<br>
<h2><u> Spacial Smarts Product Pitch (October 2019)</u></h2>
<img src="/assets/images/portfolio-photos/SpatialSmartsWireFrame.png" alt="Spacial Smarts presentation wireframe" width="100%">

<h6> Overview </h6> 
<p> This is a technical product pitch I worked created alongside 4 teammates! This product is a online learning platform to improve spacial reasoning skills in children. </p>
<!-- pitchdeck -->
<p>
<h6> User Research </h6>
Looking at several long-term studies, Spacial Reasoning abilities in children during adolescence strongly correlated with advanced degrees in higher education. According to Vanderbilt Peabody College, "more than 90% of those holding STEM PhD's were in the top quartile in spatial ability during adolescence." As correlation is not causation, improving spacial reasoning in children may not affect their adult achievement<br>
Next, I conducted stakeholder interviews with teachers in both private and public schools. I also created a survey and gathered responses from 100 local K-12 teachers. Froom the data collected, 80% of these teachers already used technology in the classroom to reinforce their students' learning, 75% of which reported being wanting a change in curriculum to further incorporate spacial reasoning in education. 
</p>
<img src="/assets/images/portfolio-photos/SpatialSmartsData.png" alt="Spacial Smarts survey daya" width="70%">
<br>

<h6> Business Strategy </h6>
<p>
(Under Construction)
</p>

<h6> Check out our pitch deck here!: <a target="_blank" href="https://docs.google.com/presentation/d/1Vu0N-vrJTUN76HIuFM6-M9vyxxhRwdQXCoAQ-JD5GzA/edit?usp=sharing">here</a></h6>
<br>

<hr style="height:8px;border:none;color:green;background-color:green;" />
<hr style="height:8px;border:none;color:green;background-color:green;" />
<hr>

<!-- close col-md-9 div -->
</div>

<div class="col-md-3">
<div class="sticky-top sticky-top-80">
<h5>Product Management / Design Projects</h5>
<p> Some of my favorite PM projects where I've practiced thinking like a user-oriented PM. </p>

<a href="#PM_section" class="btn btn-peach">Product Management</a> 
<a href="#SWE_section" class="btn btn-teal">Software Engineering</a> 
<a href="#consulting_section" class="btn btn-purple">Consulting Projects</a>

</div>
</div>

<!-- close row justify-content-between -->
</div>

<br>
<!-- SWE Projects
================================================== -->
<section>
    <div id="SWE_section" class="section-title">
        <h2><span> Software Engineering Experience (Under Construction)</span></h2>
    </div>
</section>

<div class="row justify-content-between">

<div class="col-md-9 pr-5">

<h2> Google STEP Internship - Google Classroom Autograder (Summer 2020)</h2>
<br>
<h5> Project Overview </h5>
<p> 
During my Summer 2020 internship, I worked with two other co-interns to build a Full-Stack Web Application. This application is an autograder for virtual teachers to autograde student coursework submissions on Google Classroom. The application used the OAuth for an instructor to login to the website with the same account they use for Google Classroom. We used the Google Classroom API such that the website pulled all the courses, assignments, and submissions from an instructor's Google Classroom account. Next, we created pagination and a frontend for the teacher to view a single students' submission of a worksheet. This frontend allows a teacher to mark out the response area from the student for each question.
</p>
<p>
After each questions' response area has been marked accordingly, the application parses the responses as images from each student. The Google Cloud Vision API is next implemented to parse out the written text. All responses for a single question are converted to Strings, and similar responses to a question are grouped together in buckets. 
</p>
<p>
Finally, the instructor is able to assign a point value to each bucket of responses. This allows for partial grading, for example, all responses with the answer "Rome" can be assigned a 10pt value, while all responses answered "Italy" can be assigned 5pts. This application greatly cuts down on the amount of time a teacher would spend grading each student's answer to each question, as they would now only need to grade each unique response to each question once. 
</p>

<video width="600" height="350" controls>
  <source src="/assets/videos/GoogleAutograderDemo.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>

<br>
<p>
<h6> Technical Specifications </h6>
For this project, we utilized several APIs and other tools. This includes GCP Datastore to store metadata on each assignment submission, the teachers' students, and grades. We used GCP Blobstore to store the assignments and parsed out student responses. 
<br>
We also used Google OAuth so that teachers would be able to log into our third-party application with their GSuite account, and used the Google Classroom API to pull all of a teacher's courses they are teaching, their students' submissions, and write grades back to the Google Classroom for the students to know their grades. We used the Google cloud Vision API in order to parse out student handwritten responses and cluster similar responses for partial grading. Finally, I used the Materialize.css framework. <br>
The front-end was bulit in Vanilla Javascript, HTML/CSS. The backend was built using Java Servlets.
</p>

<h5> Development Process </h5>
<h6> Background</h6>
For this project, I, along with my two podmates, designed the project for approval before it could begin. Aside from writing the Design Doc, this all began with good-old-fashioned brainstorming. Classroom instructors, where grading reportedly causes teachers to spend several hours a week working overtime. This has only been projected to increased due to the transition to online learning during the COVID-19 Pandemic. Mmoreover, research shows that giving feedback immediately after assignment submissions improves students responses in a positive manner, leader to higher memory retension. By creating a tool that curts down grading time, instructors can spend their limited time in more valuable ways as students get the efficient feedback they need to suceed.  
<br>

<h6> User Research </h6>
<p>
Upon coming to a project in mind, we began by writing detailed User Stories to justify why this is a necessary feature, and how this could potentially save teachers at least 20% of their current work time, if not more. From the customer perspective, teachers being pushed to an online learning environment has caused a huge increase in workload as most K-12 teachers are over the age of 40. As a generation who may struggle with technology more, these users were not familiar with an efficient way to grade several submissions at a time. 
</p>

<h6> Design </h6>
<p>
Before begining to software engineer this application, we built a rough-draft basic wireframe to demonstrate the designed pagination and content of the webapp. The Figma skeleton can be viewed
<a href="https://www.figma.com/file/B2gGkcMt7zzasnSggxhjYG/Goog?node-id=0%3A1" target="_blank"> here.</a>
</p>

We also created a prototype website, which can be viewed <a href="https://autograderprototype--rsampdev.repl.co/pages/courses.html" target="_blank"> here.</a>

Next, the project was split into individual contributor parts. We created a 8-week timeline against a detailed list of features and tasks. These features were then prioritized into P0, P1, and P2 prioritity levels, based off of MVP Goals and MVP Non-Goals. The only thing left is to build it, the demo for which is above.
</p>
<img src = "/assets/images/blog-photos/google-podmates.jpg" alt="Google Project Image">

<hr style="height:8px;border:none;color:green;background-color:green;" />
<hr style="height:8px;border:none;color:green;background-color:green;" />
<hr>

<br>
<h5> National Institutes of Health Internship (Summer 2019) </h5>
<p>  <br>
I worked within the Division of Technical Resources at NIH, specifically the Utilities Engineering Branch. NIH has a Central Utility Plant (CUP) on campus to generate hot/cold water and steam for its hospitals and research buildings. I worked primarily in Matlab to improve a model that would predict the amount of utilities that needed to be generated on a given hour. For example, a hot, low-humidity day might require more cold water generation, especially as the load/demand for cold water within the hospital increases. These predictions hypothetically create virtual, predicted savings as the CUP operators could adjust their production accordingly.
</p>
<p>
I also did front-end web development there too! Since I often found myself with time leftover, I picked up a secondary project -- working on the dynamic web pages of a website used to in Angular to do perform a datapull from the PI OSIsoft internal database in a convenient UI for the operators to act off of.
<br>
My cointerns, Marissa, Alex, and I pictured below:
</p>
<img src = "/assets/images/portfolio-photos/NIH_cointerns.jpg" alt="NIH Cointerns">

<hr style="height:8px;border:none;color:green;background-color:green;" />
<hr style="height:8px;border:none;color:green;background-color:green;" />
<hr>

<br> 
<h5> HackUMBC - Cardiac Connection (Fall 2019) </h5>
<p> I competed in  HackUMBC Fall 2019! I built an app similar to Tinder, but with a bit more HCI (Human-Computer Interaction) pushed into it. The devpost for this hackathon project can be found 
<a href="https://devpost.com/software/cardiac-chemistry" target="_blank"> here.</a>
<br>
At this particularly hackathon, the majority of the sponsors had come up with challenges such as "Best Data Visualization Hack" or something along those lines. But none of them provided a dataset, and I didn't want to waste time at a 24-hour hackathon doing data mining and cleansing. <br>

So instead, my two friends and I decided to throw something together a little more fun! We built a Javascript App using Cordova, which allowed us to demo on either Android or iOS. This application allowed users to swipe either left or right on card profiles, containing a person's photo and short bio. I also utilized the Google Cloud API -- GCP datastore buckets to store these profiles and fetch them for the app. <br>

<img src = "/assets/images/portfolio-photos/CardiacConnection/cardiac_connection_mobile.jpg" alt="Cardiac Connection Mobile Frontend">


We also built a Fitbit App, which would take note of your heart rate. This would be used to ping the mobile app on someone's device to automatically swipe right when the users' heart rate escalates. <br>

<img src = "/assets/images/portfolio-photos/CardiacConnection/cardiac_connection_fitbit.jpg" alt="Cardiac Connection Fitbit App">


<h6> Next Steps </h6>
This was only a 24-hour hackathon -- many of our features went unfinished. Our next step would include an interface for users to build their own profile, rather than simply swiping on other profiles. Another feature to implement would be real-time chat. <br>
The Fitbit would not communicate, however, because using the Fitbit API requires someone to manually review the request to utilize it. Because we overlooked this at the start of our project design, we were unable to get access to use the API in time. A next step would be incorporating the Fitbit and Mobile apps to communicate.
</p>

Check out the devpost from the hackathon <a target="_blank" href="https://devpost.com/software/cardiac-chemistry">here</a>

<hr style="height:8px;border:none;color:green;background-color:green;" />
<hr style="height:8px;border:none;color:green;background-color:green;" />
<hr>

<!-- close col-md-5 div -->
</div>

<div class="col-md-3">
<div class="sticky-top sticky-top-80">
<h5>Software Engineering Projects</h5>
<p> These are some of my favorite SWE projects. beep boop. </p>

<a href="#PM_section" class="btn btn-peach">Product Management</a> 
<a href="#SWE_section" class="btn btn-teal">Software Engineering</a> 
<a href="#consulting_section" class="btn btn-purple">Consulting Projects</a>

</div>
</div>

<!-- close row justify-content-between -->
</div>

<br>
<!-- Consulting Projects
================================================== -->
<section>
    <div id="consulting_section" class="section-title">
        <h2><span> Consulting Experience (Under Construction)</span></h2>
    </div>
</section>

<div class="row justify-content-between">

<div class="col-md-9 pr-5">

<h5> Expressions Kenya (Fall 2020) </h5>
<p> Expressions is an agricultural-tech start-up in Kenya. During the Fall 2020 semester, they were looking to pitch to investors with a minimum ask of $250,000 with a target goal of $1.5MM USD. In this case, the team deed to build more credibility to the company.  </p>

<!-- solar transitions stuff -->
<hr style="height:8px;border:none;color:green;background-color:green;" />
<hr style="height:8px;border:none;color:green;background-color:green;" />
<hr>

<br> <br>
<h5> Captial Area Food Bank - Data Analytics (Spring 2020) </h5>
<p> 
The Capital Area Food Bank (CAFB) is one of the largest Food Banks in the mid-atlantic region. They serve 380,000 individuals in the DC, MD, and VA area. My team consisting of 3 other team members and myself, were tasked with optimizing their impact by identifying areas of greatest opportunity. 
<br>
The CAFB has 450+ Food Assistance Partners. This includes emergencies, soup kitchens, senior programs, among others. Given the census tract data on the area, we used Python to identify outlier areas of underserved populations where the CAFB can potentially reallocate resources. Due to the COVID-19 pandemic, implementing any of these changes has been delayed. However, please view the poster below as our provided recommendations.
<br>
This data analytics project includeed data from the CAFB Distribution Location data and Census Socioeconomic Data. We used folium to perform the featured data visualization.
</p>

<img src = "/assets/images/portfolio-photos/CAFB_poster.png" alt="CAFB Consulting Project Recommendations Poster">

</div>

<div class="col-md-3">
<div class="sticky-top sticky-top-80">
<h5>Consulting Projects</h5>
<p> I'm part of the QUEST Honors Program at the University of Maryland! As part of the program, I've worked in teams on these projects with Engineerings, CMNS, and Business students to consult for various organizations. </p>

<a href="#PM_section" class="btn btn-peach">Product Management</a> 
<a href="#SWE_section" class="btn btn-teal">Software Engineering</a> 
<a href="#consulting_section" class="btn btn-purple">Consulting Projects</a>

</div>
</div>

<!-- close row justify-content-between -->
</div>