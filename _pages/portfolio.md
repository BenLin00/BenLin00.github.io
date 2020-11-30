---
layout: page
title: My Portfolio of PM, SWE, and Consulting Projects
permalink: /portfolio
comments: false
---

<p>
Here are a few of my project highlights from over the past few years.
</p>
<a href="#PM_section" class="btn btn-peach">Product Design</a> 
<a href="#SWE_section" class="btn btn-teal">Software Engineering</a> 
<a href="#consulting_section" class="btn btn-purple">Consulting Projects</a>

<br>
<!-- PM Projects
================================================== -->
<section>
    <div id="PM_section" class="section-title">
        <h2><span>Product Management / Design </span></h2>
    </div>
</section>


<div class="row justify-content-between">

<div class="col-md-8 pr-5">
<h5> Spotify Public Queue Feature (Fall 2020)</h5>
<h6> "Tell me about your favorite product and what you would change about it" </h6>
<p> The most common PM interview question I get asked. I made a mock-up of what my response is: <br>
As an avid music listener, Spotify is a great way to organize your favorite music, manage playlists, and discover new music. However, it’s social function is slightly lacking. A fan-favorite feature of the webapp is the right column "Friend Activity" scroll, which allows my friends and I to see what song we’re listening to in real-time. Let's incorporate this into a new proposed feature. </p>


<p>
Currently, users right click on a song > share and send friends a link via other social media apps as a url. This convoluted share process is distracting and obstructive because users are forced to set up their listening experience, whether it's putting in headphones or opening the application anew on their device. If a customer is wanting and able to listen to music, they would already be listening to music. Sending someone a song over social media just gets ignored until an appropriate time. Instead, I designed a way to casually recommend songs.
</p>

<p>
This would have a search bar on the friend activity column so that users can search by name the user they want to send a song to, combined with the drag + drop UI that Spotify users are already familiar with, so users don't experience frustration with learning how to use a new feature. This is shown as with the demo below: <br> 

<h2> demo </h2>
<!-- insert demo here -->

<br>
New song suggestions are paired up with a new <b> Public Queue </b> in addition to the users' current private queue. Songs displayed in this public queue would appear similarly to a shared playlist, listing the user who added the song and ability to sort songs. However, when songs from this playlist are played, they will be removed from the listing as with a queue. The queue layout including the new public queue is displayed below: <br>

<h2> demo </h2>
<!-- insert demo here -->

<br>
Practically speaking, this is a seamless integration of increased social interaction of users on the platform. Enhanced social functions may also appeal to customers as a way to casually connect with friends.

<h6> USE CASES </h6>
Social gatherings are often accompanied by music. Multiple people wish to queue-up song requests at events. However, this requires crowding around a single device, or utilizing Spotify's beta Group Sessions, where users can only override the currently playing song at max 5 users.

<br> Personas
<br>
used Figma
I made this with Khoa</p>
<!-- make this a demo vid or gif -->
<img src = "/assets/images/portfolio-photos/QueueTheMusic.png" alt="Spotify QueueTheMusic Project Screenshot">

<hr>

<br>
<h5> Target COVID-19 Store Occupany Tracker (Aug 2020)</h5>
<h1> insert image here </h1>

<h6> Hackathon Winner: "Overall Winner" and "Most Technically Challenging" </h6> 
<p> As part of the Target Diversity Leadership Symposium Conference during August 2020, I worked on a project with 3 teammates to design an app that would help customers locate nearby Target stores and how crowded each store is as it reaches maximum COVID-19 regulated capacity.</p>

<p>
<h6> Background </h6>
We created a mock-up of what this application would look like. During events where stores experience overcrowding, employees are often stationed at each entrance to limit customer capacity. The limited occupancy demands of COVID-19 have exacerbated this problem. This Fall 2020 Semester, a new Target store opened up next to UIUC campus, where I was located. Nearly every other day during its first month of opening, there was a line of people waiting outside to enter the store.
</p>

<p>
<h6> Description </h6>
This app allows users to view nearby Target stores according to the user's GPS location. Store locations are highlighted on a Google Map Services-powered map in color according to occupancy-- <br>
Red: if there is a line of people waiting outside store <br> Yellow: if the store is approximately at max occupancy <br> Green: if the store occupancy is not near max occupancy. <br>

<h2> Insert Map Image here and Demo</h2>
</p>

Check out the slides from our presentation <a target="_blank" href="ter.ps/targetHack">here</a>

<hr>

<!-- close col-md-5 div -->
</div>

<div class="col-md-4">
<div class="sticky-top sticky-top-80">
<h5>Product Management / Design Projects</h5>
<p> These are some of my favorite PM projects. I've really practiced thinking like a PM and what would be best for a target user / persona. </p>

<a href="#PM_section" class="btn btn-peach">Product Design</a> 
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
        <h2><span> Software Engineering Experience </span></h2>
    </div>
</section>

<div class="row justify-content-between">

<div class="col-md-8 pr-5">

<h5> Google STEP Internship - Google Classroom Autograder (Summer 2020)</h5>
<p> 
During my Summer 2020 internship, I worked with two other co-interns to build a Full-Stack Web Application. This application is an autograder for virtual teachers to autograde student coursework submissions on Google Classroom. <br>

This application used the OAuth for an instructor to login to the website with the same account they use for Google Classroom. We used the Google Classroom API such that the website pulled all the courses, assignments, and submissions from an instructor's Google Classroom account. Next, we created pagination and a frontend for the teacher to view a single students' submission of a worksheet. This frontend allows a teacher to mark out the response area from the student for each question.
<br>
After each questions' response area has been marked accordingly, the application parses the responses as images from each student. The Google Cloud Vision API is next implemented to parse out the written text. All responses for a single question are converted to Strings, and similar responses to a question are grouped together in buckets. 
<br>
Finally, the instructor is able to assign a point value to each bucket of responses. This allows for partial grading, for example, all responses with the answer "Rome" can be assigned a 10pt value, while all responses answered "Italy" can be assigned 5pts. This application greatly cuts down on the amount of time a teacher would spend grading each student's answer to each question, as they would now only need to grade each unique response to each question once. 
<br>

<h6> Technical Specifications </h6>
database design, Google OAuth, Google Classroom API, Google Cloud Vision API, Materialize.css

<h6> What I did </h6>
asdf <br>
Also, Agile dev design doc writing, code reviews, scope prioritization, roadmapping, and prototyping. <br>
//Significance with COVID-19
</p>
<img src = "/assets/images/blog-photos/google-podmates.jpg" alt="Google Project Image">

<hr>

<br>
<h5> National Institutes of Health Internship (Summer 2019) </h5>
<p> Machine Learning and stuff. Machine Learning and stuff. Machine Learning and stuff. <br>
I worked within the Division of Technical Resources at NIH, specifically the Utilities Engineering Branch. NIH has a Central Utility Plant (CUP) on campus to generate hot/cold water and steam for its hospitals and research buildings. I worked primarily in Matlab to improve a model that would predict the amount of utilities that needed to be generated on a given hour. For example, a hot, low-humidity day might require more cold water generation, especially as the load/demand for cold water within the hospital increases. These predictions hypothetically create virtual, predicted savings as the CUP operators could adjust their production accordingly.
<br> <br>
I also did front-end web development there too! Since I often found myself with time leftover, I picked up a secondary project -- working on the dynamic web pages of a website used to in Angular to do perform a datapull from the PI OSIsoft internal database in a convenient UI for the operators to act off of.
<br>
My cointerns, Marissa, Alex, and I pictured below:
</p>
<img src = "/assets/images/portfolio-photos/NIH_cointerns.jpg" alt="NIH Cointerns">

<hr>

<br> 
<h5> HackUMBC - Cardiac Connection (Fall 2019) </h5>
<p> I competed in  HackUMBC Fall 2019! I built an app similar to Tinder, but with a bit more HCI (Human-Computer Interaction) pushed into it. <br>
At this particularly hackathon, the majority of the sponsors had come up with challenges such as "Best Data Visualization Hack" or something along those lines. But none of them provided a dataset, and I didn't want to waste time at a 24-hour hackathon doing data mining and cleansing. <br>

So instead, my two friends and I decided to throw something together a little more fun! We built a Javascript App using Cordova, which allowed us to demo on either Android or iOS. This application allowed users to swipe either left or right on card profiles, containing a person's photo and short bio. I also utilized the Google Cloud API -- GCP datastore buckets to store these profiles and fetch them for the app. <br>

We also built a Fitbit App, which would take note of your heart rate. This would be used to ping the mobile app on someone's device to automatically swipe right when the users' heart rate escalates. <br>

<h6> Next Steps </h6>
Unfortunately, this is only a 24-hour hackathon, so of course features went unfinished. Our next step would include an interface for users to build their own profile, rather than simply swiping on other profiles. Another feature to implement would be real-time chat. <br>
The Fitbit would not communicate, however, because using the Fitbit API requires someone to manually review the request to utilize it. Because we overlooked this at the start of our project design, we were unable to get access to use the API in time. A next step would be incorporating the Fitbit and Mobile apps to communicate.
</p>

Check out the devpost from the hackathon <a target="_blank" href="https://devpost.com/software/cardiac-chemistry">here</a>

<hr>

<!-- close col-md-5 div -->
</div>

<div class="col-md-4">
<div class="sticky-top sticky-top-80">
<h5>Software Engineering Projects</h5>
<p> These are some of my favorite SWE projects. beep boop. </p>

<a href="#PM_section" class="btn btn-peach">Product Design</a> 
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
        <h2><span> Consulting Experience </span></h2>
    </div>
</section>

<div class="row justify-content-between">

<div class="col-md-8 pr-5">

<h5> Expressions Kenya (Fall 2020) </h5>
<p> Stuff about Expressions and what I did. Stuff about Expressions and what I did. Stuff about Expressions and what I did. Stuff about Expressions and what I did. Stuff about Expressions and what I did. Stuff about Expressions and what I did. Stuff about Expressions and what I did. Stuff about Expressions and what I did. Stuff about Expressions and what I did. Stuff about Expressions and what I did. Stuff about Expressions and what I did.  </p>
<img src = "/assets/images/portfolio-photos/QueueTheMusic.png" alt="Spotify QueueTheMusic Project Screenshot">

<br> <br>
<h5> Captial Area Food Bank - Data Analytics (Spring 2020) </h5>
<p> 
The Capital Area Food Bank (CAFB) is one of the largest Food Banks in the mid-atlantic region. They serve 380,000 individuals in the DC, MD, and VA area. My team consisting of 3 other team members and myself, were tasked with optimizing their impact by identifying areas of greatest opportunity. 
<br>
The CAFB has 450+ Food Assistance Partners. This includes emergencies, soup kitchens, senior programs, among others. Given the census tract data on the area, we used Python to identify outlier areas of underserved populations where the CAFB can potentially reallocate resources. Due to the COVID-19 pandemic, implementing any of these changes has been delayed. However, please view the poster below as our provided recommendations.
<br>
insert information on data sources -- CAFB Distribution Location data, Census Socioeconomic Data, folium data visualization
</p>

<img src = "/assets/images/portfolio-photos/CAFB_poster.png" alt="CAFB Consulting Project Recommendations Poster">

</div>

<div class="col-md-4">
<div class="sticky-top sticky-top-80">
<h5>Consulting Projects</h5>
<p> I'm part of the QUEST Honors Program at the University of Maryland! As part of the program, I've worked in teams on these projects with Engineerings, CMNS, and Business students to consult for various organizations. </p>

<a href="#PM_section" class="btn btn-peach">Product Design</a> 
<a href="#SWE_section" class="btn btn-teal">Software Engineering</a> 
<a href="#consulting_section" class="btn btn-purple">Consulting Projects</a>

</div>
</div>

<!-- close row justify-content-between -->
</div>