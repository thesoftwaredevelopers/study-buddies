<style>
  .image-spacing {
    margin-bottom: 20px; /* Adds space below each image */
  }
</style>

<div class="container">

  <p><a href="https://docs.google.com/document/d/1wbYcPTCfg8s0pp8VAVFCRjag8tJorO2LU7YyEfDUZ4o/edit?usp=sharing">Link to team contract</a></p>
  
  <h1 id="project-campus-jam">ICStudy</h1>
  <h1 id="Overview">Overview</h1>
  <h3 id="summary">Problem<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#overview" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h3>
  
  <p><em>The problem:</em> ICS students often spend more time than they need on their homework and don’t learn the material as effectively as they could, because they study alone and do not leverage the power of face-to-face study groups with peer mentors.</p>
  
  <p><em>The solution:</em> ICStudy is an application for UHM ICS students to self-organize face-to-face study groups around a course and/or specific homework or project topic.</p>
  
  <h3 id="approach">Approach<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#approach" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h3>
  
  <p>To use ICStudy, a student must login and set up their profile. The profile enables each student to list courses they have taken and for which they are willing to attempt to provide help (sensei), and courses they are currently taking and for which they might need help (grasshopper). Thus, all students are sensei in some courses and grasshoppers in other courses. Each student must also provide a head shot so that they can be visually identified.</p>
  
  <p>Another section of the site lists all of the ICS courses. Within each course, it is possible to see the grasshoppers and the senseis. A grasshopper can propose a study session around a topic currently being covered in their course (for example, “Write my essay on configuration management”, and a time to meet within ICSpace (i.e. 8:30-9:30pm tonight)). This proposal generates a notification to all of the grasshoppers and senseis, and they can respond by saying they intend to come at some point during the time period.</p>
  
  <p>There is an online calendar that shows all of the study sessions and who is attending.</p>
  
 <p>There are two styles of use for ICStudy:</p>

<ol>
    <li>You want to plan a group study session for later in the day or some subsequent day. In that case, you schedule the time period for sometime in the future.</li>
    <li>You are having a problem right now. In that case, you can go into ICStudy and schedule the session for “Right Now!”. This indicates you are right now in ICSpace and need help. All the other sensei and grasshoppers for that course will be notified, and hopefully a group will spontaneously form in a few minutes.</li>
</ol>
  <p>ICStudy seems great in theory, but there is a significant barrier to adoption: students are naturally inhibited about asking for or offering help. This might be overcome through the use of well-designed game mechanics.</p>

<p>Part of the design of ICStudy should be some kind of point system, or “levels”, or some other game mechanic to reward students for participating.</p>

<p>In addition, you can solicit gift cards or other kinds of rewards from the ICS Department or UH Manoa to reward the “best” sensei and grasshoppers in a given week, month, or semester. The challenge is to design the point system so that students cannot “game” the system to obtain points without actually helping others. You also want to prevent a “hui” of students from simply pretending to work together to get the most points and then split the prize without actually helping each other.</p>

<p>There must also be admins who monitor the site and who users can contact if they suspect inappropriate behavior.</p>

<p>Important design goals for ICStudy are:</p>

<ul>
    <li>To encourage use of ICSpace among ICS students.</li>
    <li>To minimize risk of inappropriate encounters by requiring all meetings to occur in ICSpace.</li>
    <li>To encourage face-to-face interaction among ICS students.</li>
</ul>

<p>There are other mechanisms (Slack, Piazza) for asynchronous, online help and support. ICStudy is designed to facilitate live, real-world help using ICSpace.</p>

  <p>Some mockup pages include:</p>
  
  <ul>
    <li>Landing page</li>
    <li>User home page</li>
    <li>Admin home page</li>
    <li>User profile page</li>
    <li>Calendar page</li>
    <li>Create Study Sesh page</li>
    <li>Study Session page</li>
    <li>Game mechanic page(s) (for example, a leaderboard?)</li>
  </ul>
  
  <h3 id="use-case-ideas">Use case ideas<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#use-case-ideas" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h3>
  
  <p>Whether or not the following bullet points list all pages or not, the completed use case should show an end-to-end scenario of using the system.</p>
  
<ul>
    <li>New user goes to landing page, logs in, gets home page, sets up profile. (How do they learn how system works?)</li>
    <li>Admin goes to landing page, logs in, gets home page, edits site.</li>
    <li>User goes to landing page, logs in, requests study sesh.</li>
    <li>User is notified of study sesh, responds. (Can they respond via text message?)</li>
    <li>User checks their status with respect to game mechanics.</li>
</ul>
  
  <h3 id="beyond-the-basics">Beyond the basics<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#beyond-the-basics" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h3>
  
  <p>After implementing the basic functionality, here are ideas for more advanced features:</p>
  
<ul>
    <li>Text message interface. See notifications, and reply to confirm attendance all through text message.</li>
    <li>Slack integration to facilitate notification and organization of meetings.</li>
    <li>A Slack Bot to suggest and help implement ICStudy meetings.</li>
    <li>A rating system for meetings and sensei participation.</li>
</ul>
  <img src="images\diagramOne.jpg" alt="Diagram of ICStudy System" />
  
  <p>Diagrams which show the layout of the mockups for Milestone One</p>
  
  <User Guide>

  <p><a href="https://the-software-developers.vercel.app/">Link to deployed site</a></p>

  <p>Below are up to date screenshots of the current build</p>

  <!-- Placeholder for Screenshot 1 -->
  <img src="images\M1One.png" alt="Screenshot 1" class="image-spacing" />
  
  <p><em>Landing Page</em></p>
  
  <!-- Placeholder for Screenshot 2 -->
  <img src="images\M1Two.png" alt="Screenshot 2" class="image-spacing" />
  
  <p><em>Find Session Page</em> | Here you can find a session to join!</p>

  <!-- Placeholder for Screenshot 3 -->
  <img src="images\M1Three.png" alt="Screenshot 3" class="image-spacing" />
  
  <p><em>Profile Page</em> | View someone's profile or your own!</p>

  <img src="images\M2Three.png" alt="Screenshot 7" class="image-spacing" />

  <p><em>My Sessions</em> | View and manage your sessions!</p>

  <!-- Placeholder for Screenshot 4 -->
  <img src="images\M1Four.png" alt="Screenshot 4" class="image-spacing" />
  
  <p><em>Leaderboard</em> | View the leaderboard for all users!</p>

  <!-- Placeholder for Screenshot 5 -->
  <img src="images\M1Five.png" alt="Screenshot 5" class="image-spacing" />
  
  <p><em>Create Session</em> | Create a new study session!</p>

  <img src="images\M2One.png" alt="Screenshot 6" class="image-spacing" />

  <p><em>Calendar</em> | View a calendar which shows all of your sessions!</p>

  <!-- Developer Guide Section -->
  <h3 id="developer-guide">Developer Guide</h3>
  <ol>
    <li>Clone repo</li>
    <li>Run <code>npm install</code></li>
    <li>Setup database environment:
      <ul>
        <li>NeonDB, Vercel (link them together)</li>
      </ul>
    </li>
    <li>Create S3 bucket with AWS to store images
      <ul>
        <li>Create AWS account</li>
        <li>Use S3 service to create a bucket to store objects</li>
        <li>Setup and create IAM user to configure permissions and create access and secret keys</li>
        <li>Configure user policies and CORS permissions to allow clients to upload and PUT objects into the bucket</li>
      </ul>
    </li>
    <li>Add environment variables into local <code>.env</code> file (From AWS keys and NeonDB environment variables)</li>
    <li>Run <code>npm run dev</code>, site running on localhost</li>
  </ol>

  <p><a href="https://github.com/orgs/thesoftwaredevelopers/projects/1">M1 project board</a></p>
  <p><a href="https://github.com/orgs/thesoftwaredevelopers/projects/2">M2 project board</a></p>
  <p><a href="https://github.com/orgs/thesoftwaredevelopers/projects/4">M3 project board</a></p>

