Portfolio Website using html,css and javascript along with some javascript libraries like 
AOS- Animate on Scroll, Kursor.js - Tracks and animates cursor, etc.
The Website has following features:-  
 - Dark and light version
 - Load content on scroll,
 - With HTML CSS & JavaScript
 - Responsive design
 - Task Bar has a Resume button to download Resume
 - About section has a progress bar which shows efficiency in the listed skills
 - Portfolio Section has a slider which shows all the projects and the main language used in them

It has a contact form which collects name, email and message which is then sent as a post request to backend where it is stored in a local mongodb server. All the saved data can then be obtained by making a GET at "/readData".
This uses Node.js along with Express.js to quickly and efficiently build the required rest API's.
Nodemon is used to continuously update the changes on the server.
