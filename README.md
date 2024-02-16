# Festival-Management-website-and-database-management-system
It is a complete college fest website design along with management of the database system of all participants and events.


COLLEGE FESTIVAL WEBSITE INTEGRATED WITH DATABASE.
	This project has a fully working website connected to a database that is managed by an admin panel.


A). Features:

- made with HTML5,CSS3,Javascript,Jquery,PHP
- neat, simple, and modern design
- fully responsive
- cross-browser optimization
- use of Google Maps and Google Calendar
- pdf viewer 


********************************************************************************************************************************************

B). 
FRONTEND:
It has wonderful exciting front web pages.

1). Events
There are several different types of events shown on different pages of the navbar. Each  of these has a registration form along with all the details of events which are fetched from the database of events.

2). Sponsors of the fest had been displayed along with a wonderful guest list.

3). Registration button
It takes you to  the registration form from where participants can get their unique ID to further take part in any event.

4). Participant login button
It will make participants see all the events they have registered for along with their timings and changes if any.

5). Admin login page
This will enable the admisitrator to enter into the admin panel of the website change any data of the complete fest and look for other details such as how many people have visited the website and how the event is enlarging on social media platforms.

ADMIN PANEL :
Admin Dashboard  or panel to use during college fests.

1). Overview - 
uog Admin is a full-featured, multipurpose admin, built with Bootstrap 4 Framework, HTML5, CSS, Javascript, and PHP.
It is a fully responsive admin dashboard that is user-friendly and can be operated with great ease.

2). How to use -
Index Page - The first page that is opened after the admin is logged in is the Index Page. When opened, we can see statistics related to Fest's database in the middle area.
When clicking on the UOG logo in the top left corner or on 'Home' in the navigation area, we are directed to the index page.

Along with the index page, all other pages have the following parts in the left menu - 
- Query Box - This is an input field that takes any query as input and prints the corresponding results. Some queries have been provided handy for non-MySQL users. If you want to  see your queries in the Available Queries section, type them in the file 'availableQueries.txt' inside the folder admin_uog and save it.

- Event Menu - It takes care of showing all events in Google Calendar, creating an event, editing and deleting events.

- Managers Menu - Information associated with Managers - all Manager's details, adding a Manager, editing and deleting a Manager data, can be done using this menu.

- Participants Menu -  Information associated with Participants - all Participant details, important/required details of Participants, and deleted Participants, can be selected from this menu.

- Volunteers Menu - Information associated with Volunteers - all Volunteer details, adding a Volunteer, editing and deleting a Volunteer data, can be done using this menu .

- Sponsors Menu - Information associated with Sponsors - all Sponsors details, adding a Sponsor, editing and deleting a Sponsor data, can be done from this menu.

- Chief Guests Menu - Information associated with Chief Guests - all Chief Guests details, adding a Chief Guest, editing and deleting a Chief Guest data, can be done using this menu.

- Interface  
	- PDF Viewer - To view any PDF/text file, a PDF viewer can be used. Also, PDF can be printed and downloaded.
	
- Logout  tab - To successfully come out of UOG Admin, this tab has to be clicked.	


C). Installation :
Here you can see two folders, front_uog and admin_uog
	front_uog-> It consists of all the files, necessary to run the frontend webpages
	admin_uog-> It consists of all the files, necessary to run the admin panel of uog,i.e. uog Admin.

To run the code on localhost, on your PC, 

1). Install Xampp from https://www.apachefriends.org/index.html

2). Go to Xampp-control, in the XAMPP folder, and start Apache and Mysql

3). Now, save the two folders, front_uog, and admin_uog in the folder 'htdocs', which you will find in the XAMPP folder itself.

4). Open any web browser, preferably Chrome, and now search for "localhost/phpmyadmin/" in the URL tab, this will take you to your phpmyadmin page.

5). Go to import and import the database using the file uog.sql provided in this folder.

6). Create a user and give it all the privileges of the imported database.

7). In both the folders, front_uog and admin_uog, you will find a file "linc.php", this file makes the connection of the webpages with the database. Open this file in any text    editor and change the name of the user and password to the same one you have created in previous steps. Save the changes.

8). Again go to any web browser, preferably Chrome, and in the URL tab, type "localhost/front_uog/mainpage.php", this will take you to the website.

9). Now the website can be  traversed.

10). To login to the admin panel, go to the admin menu in the navigation bar, valid credentials are:-
Username:-  zahid
Password:-  inahidmal
(These credentials can be changed as per convenience.)

