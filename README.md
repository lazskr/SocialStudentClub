Users can sign up and become members of the social student club website where they can: 
o	Sign up/login. 
o	Manage their user information. 
o	Join a club.
o	View updates from clubs they’re members of.
o	See upcoming club events and RSVP. 

Users can make a club and become club managers and be able to: 
o	Sign up/log in. 
o	Manage their user information.
o	View their members. 
o	Post updates both publicly, and privately to their members. 
o	Create and update club events. 
o	See who has RVSP’d for an event. 
o	Can sign up to receive email notifications from clubs for updates and special events.

System admins exist on the website and can: 
o	Manage their user information. 
o	Manage Users.
o	Manage Clubs.
o	Sign-up other Admins. 

•	All users can link their Google account as a method for logging into the website via an established server-side connection with Google Cloud’s API.
•	User’s who are not logged into the website may still view all the clubs and their associated information from the home page.
•	HTML and CSS were used for the frontend of the website to provide page structure and styling respectively. JavaScript, specifically, Vue.js 2 (JavaScript library) was used for the front-friend to provide dynamic content. Utilizing Vue.js enabled for protection against Cross-Site Scripting attacks (XXS). 
•	Node.js (a JavaScript runtime environment) was used for the backend of the website. Specifically, it provided the web server which would be used to access the database, as well as create sessions for users.
•	MySQL was used to provide a relational database for the website. Prepared statements were used in Node.js to ensure that SQL injection was not possible by the user.
