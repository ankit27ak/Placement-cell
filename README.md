# Placement cell App
  
 <b>  I developed a web application called "CareerCamp Connect," which was a Placement Cell management system for a company. The main goal was to create an interface where employees could input data into the database and then download it in CSV format to compile various reports.
 A company constantly needs to download their data to compile different reports. You need to create an
interface for the employees of this company to fill in the data into the database and then download it in CSV
format.Team Career Camp wants to maintain a database of all the student interviews [only for their ownuse]. <b> 

## Table of Contents
-  <b> [Features](#features)</b>
-  <b> [Getting Started](#getting-started)</b>
-  <b> [Tech Stack](#Tech-Stack) </b>
-  <b> [Project Demo](#Project-Demo) </b>
-  <b> [Author](#Author)</b>

## Features
-  <b>1. Authentication System </b>
     <p>The web application had a secure sign-up and sign-in system exclusively for company employees. This ensured that only authorized users could access and manage the data.</p>
-  <b> 2. Student Database Management  </b>
    <p>Employees could view and manage a list of students, including their batch, college, and placement status (placed or not placed). The application allowed adding new students to the database with their respective course scores, such as DSA Final Score, WebD Final Score, and React Final Score.</p>
-  <b> 3. Interview Scheduling</b>
    <p> The application provided a section to create and manage interviews, where employees could specify the company name and date for each interview.</p>
-  <b> 4. Student Allocation </b>
    <p>Employees had the ability to allocate students to specific interviews. This helped in organizing and tracking the interview process efficiently.</p>
-  <b> 5. Result Mapping </b>
    <p>The application had a feature to map the results of interviews for each student, indicating whether they passed, failed, were on hold, or didn't attempt the interview</p>
-  <b> 6. External Jobs List </b>
   <p>Additionally, the application featured a minimalistic page that fetched real available jobs in India for React and Node.js using open APIs. The job details were retrieved from APIs such as GitHub Jobs API.</p>
-  <b> 7. CSV Data Export </b>
-  <p> Lastly, employees could download a complete CSV file containing all the relevant data, including student ID, name, college, placement status, course scores, interview date, company name, and interview result. This export functionality made it easier for the company to compile reports.</p>

## Getting Started
-  <b> 1. &nbsp; Clone Git Repo  </b>
    <br>----<i> git clone   == </i><br><br>
-  <b> 2.  &nbsp;Install NPM dependencies </b>
   <br>----<i> npm install</i> <br><br>
-  <b> 2.  &nbsp;Set Up .env file  </b>
   <br>----<i> add mongodb your url</i> <br><br>
-  <b> 3. &nbsp; Then simply start your app </b>
   <br>----<i>npm start </i><br><br>


### Prerequisites
- <b>NodeJs Any Version</b>

### Usage


## Tech Stack

-  <b> 1.Front-end </b>
    <p>HTML, CSS, Tailwind CSS , JavaScript: For creating the user interface and handling client-side interactions.
       For building a dynamic and responsive user interface, especially for the External Jobs List page</p>
- <b> 2.Back-end </b>
   <p>Node.js: For server-side development and handling API requests.
      Express.js: As a framework to create the application's server-side routes and manage the HTTP requests and responses.
      MongoDB: As the database to store and manage the student, interview, and result data.</p>
-  <b> 3. Authentication </b>
    <p>Passport.js: For implementing the authentication system and managing user sign-up and sign-in.</p>
-  <b> 4. CSV Export</b>
    <p>fast-csv: A Node.js library used to generate the CSV file with the required student and interview data.</p>
-  <b> 5. External API Integration </b>
   <p> Axios: A promise-based HTTP client for Node.js, used to fetch job data from the GitHub Jobs API and other open APIs</p>
-  <b> 6.Deployment </b>
   <p>The application was deployed using cloud services like render, depending on the preferred platform.</p>



## Author


- Name: Ankit Kumar
- GitHub: <a><b>https://github.com/ankit27ak/Placement-cell</a></b>
