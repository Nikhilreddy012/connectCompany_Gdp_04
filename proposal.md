# RFP - Connect Company

## Statement of Purpose :


-	In any business climate, creating associations and extending effort can enormously affect your organization's primary concern. This connect company may increases the market visibility, systems administration and connect job goal to the company, manages the time, provides more opportunities to the user by projecting all the available updates about all the companies in one platform. In this applications users can have the easy accessibility to view the events from different companies and they can fix the remainders and schedule the events.

## Overview

-	This application is all about connecting the user to companies. So far there are only a few platforms where a user can connect to companies. So we have developed our idea based on this concept. This Connect company is used to connect the job aspirant to the company events. So in this platform where user login into the connect company website and he/she can view the events organized by the companies.
There are multiple side advantages through this connect company firstly The companies can minimize advertisement for hiring the people and from the user point of view instead of he/she searching for the job openings on the mega-platforms simply he/she can look in to connect company for the events.
The user should have a valid username and password to enter into the system and also get notifications about the updates on subscribed channels.
How the application will works
- Each organization will be registered in the portal and they can post events happening in their company like an interview, Tech talks, or any updates on the company.
-	Users can open and subscribe to the company events or companies listed in the portal.
-	User can submit their request to join in the upcoming events.
-	They can get updates and emails on the subscribed events.

After subscribing to the event,
-	The user should be able to see a list of events happening and subscribed by him to return to the starting location (show on a map?)
The website is cooperative, not complex to find the company and subscribe to the events happening.

## Benefits
-	This application is a user-friendly application 
-	By utilizing this application the companies can reduce their money spending on advertising.
-	The user will be up to date with the company events.  
-	This Website acts as a bridge between user and company.
-	There is clear transparency between users and companies

## Epics / User Stories / Tasks:
### Backend
-	Create login Api
-	Create database schema with realtionships
-	Create login and register API.
-	Create Add API to add company person by admin to the system
-	Create Add event API for company person to add/create event/Job
-	Create Subscribe API to subscribe in events or job
-	Create ApplyEvent API to apply for event/job
-	Create ListEvents to view all the events/jobs applied

### Fronend:
-	Create Login page 
-	Create Register page
-	Create 3 different dashboards for 3 different users
-	Create Application submission view to submit event or job by a company
-	Create a Different pages which show all the companies and events in each company.

 
## Acceptance criteria checklist:
-	Verifying the User Authentication page
-	Verifying that the user could register for the events successfully
-	After a user searches for an event, the results should include a differnet companies.
-	Confirmation that the user will receive updated notifications for upcoming events and tasks.
-	Verifying that the interface is simple to use

## Contract scope / budget / schedule (2 semesters):
-  We students from Northwest Missouri State University as a team doing this project under the guidance of Dr. Badami Charles for two semesters using various technologies. 
# Budget
| S. No. | Name                                                            | Role              | Hourly Pay                | Hours/ Week | Estimated Cost/ Week |
|------|--------------------------------------------------------------------|--------------------|------------------------| ------------- | ---------- |
| 1    | [Nikhil Reddy Pannala](https://github.com/NikhilReddy012)           |  Developer  | $45 |   9 - 12 |  $405 - $540 |
| 2    | [Venkat Sai Jarugula](https://github.com/jarugulavenkat7)                   |  Developer | $45 | 9 - 12 | $405 - $540 |
| 3    | [SaiKiran Gangidi](https://github.com/saikiranreddygangidi)                   |  Developer | $45 | 9 - 12 | $405 - $540 |
| 4    | [Vivek Drakshapally](https://github.com/vivekd31)                   |  Developer | $45 | 9 - 12 | $405 - $540 |
| 5    | [Swetha Gahana](https://github.com/swetha34)                   |  Developer | $45 | 9 - 12 | $405 - $540 |
|    |               |   |  | Material Resources  | $1000 |
|    |               |   |  | Total  | $3025 - $3700 |



### Project: Connect Company
### Overall Status: On Track
### Major Milestones:
| Stage | Date |
|------|--------------------------------------------------------------------|
|Milestone 1 | 30 October 2021 |
|Milestone 2 | 30 November 2021 |
|Milestone 3 | 30 January 2022 |
|Milestone 4 | 30 February 2022 |
|Milestone 5 | 30 March 2022 |
|Completion | 30 April 2022 |
## ProjectTeam:
|Project Lead | Nikhil Reddy Pannala |
|------|--------------------------------------------------------------------|
|Team Members | Venkat Sai Jarugula |
| | SaiKiran Gangidi |
| | Vivek Drakshapally |
| | Swetha Gahana |
## Schedule:

-	**Sprint-1**: In the initial sprint we have built the plan and we have sorted the technologies we are dealing with and we gathered the requirements.
-	**Sprint-2** : In the Second Sprint we have built the UI Page using Vue js and build backend using adonis js .Then we have connected the backend with the frontend using 	 rest API we majorly using Axios for connection.
-	**Sprint-3**: In the Third Sprint we have built the database in MYSQL and deployed the application in Heroku and using a remote free SQL database.


 End of semester GDP-1

 GDP-2 

-	**Sprint-4**: Create Database models and schema
-	**Spring-5** : Developing the relations between different tables ( like one-to-one ,many-to -many)
-	**Sprint-6**: Design web APIs
-	**Sprint-7**: Create APIs to communicated with backend database
-	**Sprint-8”: Design all the User Interface pages based on backend requirements
-	**Sprint-9** Integration with both frontend and backend.
-	**Sprint-10**: Testing and fixing issues, Deployment of the application.


## User interface sketches
![](GDP%20Images/registerForm.png)
![](GDP%20Images/loginForm.png)
![](GDP%20Images/welcome.png)

## Technology stack descriptions:

### Backend framework 
- The backend Framework we are using is adonisJs which is writtern in JavaSprint
- It is a fully optimized frame work which advanced methods and feature for relation struture data operation.

### Backend free app host 
- The Backend app host for our project would be *HEROKU*
### Data host 
- The data host we are planning to use is freesqldatabase which provides as three free database
### Front-end plan 
- For the frontend  we planning to use vue js framework which is an component based framework
### Front-end responsive design 
- The Front-end responsive design would be *Bootstrap*


## E-R diagram displayed:
![](https://github.com/Nikhilreddy012/connectCompany_Gdp_04/blob/main/GDP%20Images/ER%20Diagram.jpeg "ERDiagram")

## Consistent set of sample data in Excel, use one sheet for each entity
![](GDP%20Images/Capture1.PNG)
![](GDP%20Images/Capture3.PNG)
![](GDP%20Images/Capture5.PNG)
![](GDP%20Images/Capture4.PNG)
![](GDP%20Images/Capture2.PNG)

## Risks and assumptions:


-	The user should be able to login into page using email id and password
-	Displaying the different dashboards for each of the accounts Admin, User, and Committe User.
-	Making sure the system is compatible with all web browsers (Firefox, Google Chrome,Internet Explorer, Safari, Edge, etc.)
-	MySQL database that holds all info on organizations, organization's events and user informaqtion.
-	Admin should be able to view a list of all organizations, organization's events and the user who registered for the particular events.
 
