
# GileadMD

## Description

_Duration: 3 Week Sprint_

GileadMD is a medical records web application that was created to serve medical hospitals in Zimbabwe to start with. These hospitals have been using paper based medical charts for keeping patient records. I coverted a total of 20 charts, some for use in the ICU and some for use on the general floor. Generally speaking, I created forms to collect information and siplayed the information mostly on tables, and some on graphs.

## Screen Shots

![home page](/documentation/images/homepage.jpeg)
![Provider Dashboard](/documentation/images/providerdashboard.jpeg)
![Add Provider](/documentation/images/addprovider.jpeg)
![Patient Search](/documentation/images/patientsearch.jpeg)
![Vitals Form](/documentation/images/vitalsform.jpeg)
![Vitals Table](/documentation/images/vitalstable.jpeg)
![Temp Graph](/documentation/images/tempgraph.jpeg)

### Prerequisites

- [Node.js](https://nodejs.org/en/)
- [PostgreSQL](https://www.postgresql.org/download/)
- [Express.js](https://expressjs.com/)

## Installation

Before starting installation ensure that all prereqs are installed and working. You need to have a PostgreSQL database created and running in order to continue

1. Create a database named `gilead_solo`.
2. The queries in the `database.sql` file are set up to create all the necessary tables. The project is built on [Postgres](https://www.postgresql.org/download/), so you will need to make sure to have that installed. Use your client of choice to run the queries. 
3. Open your editor of choice and create a .env file with the following values:
	```
	SERVER_SESSION_SECRET=[put a sufficiently random and long string here]
	
4. Run an `npm install` in your terminal in the root of the project folder.
5. Run `npm run server` in your terminal.
6. Run `npm run client` in your terminal.
7. The `npm run client` command should open a browser window for you, but if it does not just open your browser and navigate to http://localhost:3000. Chrome is the only browser that is currently supported.

## Usage

1. A. For security reasons, we do not allow users to register. This is done to safeguard patient information. We the site owners register organizations, their admins in turn register providers and provide them the relevant login information.
1. B. Here is demo login information for you to do a click through if you use the link to our web app. Otherwise to run this on your local computer, you will need to do a manual insert to the organizations and the user table. To log into our web app, click [here](http://gileadmd.com/)here and use the information below
    Username: drbenhudsec
    Password: ben1900hudsec

2. If you are running this locally, you will need to add a patient to the system, search for them and add pull up charts to add seed data or view information. If you want to pull up a patient on our web app, here is demo information for a patient:

Demo Patient Details:
First Name: John
Middle Name: Johnny
Last Name: Doe
Date Of Birth: 01/01/1900

3. Finally, you also have the ability to delete patients from the system and if you have admin access, you can also add admins to the system.

4. I am now working with a friend to grow the functionality of this app beyond the baseline features that I created and aim to include other software systems such as patient scheduling, billing, benefits checking, claims processing etc.

## Built With

* React
* Redux
* Redux Sagas
* Redux Logger
* pg (Postgres)
* Material-UI
* React Bootstrap
* MUI Tables
* Passport
* Express
* Node
* bcryptjs
* VSCode
* Balsamiq

## Acknowledgement
Thanks to [Emerging Digital Academy](www.emergingacademy.org) who equipped and helped me with the skills that I need to make this application a reality.  I took their 20 week fullstack bootcamp and this is a direct result of the knowledge I gained with zero starting knowledge about computer programming. Also I am now working with a friend [Hunter Scheel](https://github.com/hunterEdward98) to grow and improve this application.

## Support
If you have suggestions or issues, please email me at [admin@gileadmd.com](admin@gileadmd.com)

## Thanks!

Thanks for reading! I hope you have a great day!
