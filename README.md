# PGLIFE
A Full-stack Internshala project that will help people find PG 

PG Life is a Full-Stack Web Application. This is a project that I was assigned to make during my
Internshala Full Stack Web Development Internship Training. I got the guidance, and following that
I made this web application with my own understanding and knowledge. It is customized according to
what I thought would be better functionalities in this app, from the user perspective.

The entire web app is fully responsive and is operational from any device.

Technology use:- HTML, CSS, Bootstrap 5, Javascript, AJAX, PHP, MySQL.

This web app has the following functionalities:-

1. The home page:-
--------------------
	a. Search bar, where the user can enter the city name(in any case), and PGs listed in that city(if exists in the database), will be shown as a list.
	b. Contains main cities in the form of circular sections, clicking upon which user can get the list of pgs existing in that city.


2. The PG list page:-
----------------------
	a. Shows the list of all the PGs and their main features in the selected city, in the form of beautiful cards.
	b. Filter bar, using which the PGs can be sorted according to rent and rating, in ascending or descending order.
	c. User can see here which PG is being marked interested by how many users, to know popularity.
	d. After logging in, the user can mark any PG(s) as interested, from the list itself, by clicking on the heart icon.
	e. The heart icon toggles style in terms of fill color when alternatively clicked to like or dislike the pg. Based upon click, the interested user's number remains updated dynamically.
		

3. The PG details page:-
-------------------------
	a. In the property list page, if any user clicks on the "View" button, that pg's entire details are displayed in the PG details page.
	b. Images of the selected PG are being viewed at the top front as a beautiful carousel.
	c. The page shows all the details such as amenities, testimonials, and address of the PG.
	d. User can see the selected PG is being marked interested by how many users, to know popularity.
	e. After logging in, the user can mark any PG(s) as interested, from the list itself, by clicking on the heart icon.
	f. The heart icon toggles style in terms of fill color when alternatively clicked to like or dislike the pg. Based upon click, the interested user's number remains updated dynamically.


4. The dashboard:-
--------------------
	a. Appears only for the logged-in users.
	b. Shows the account details of the logged-in users.
	c. Below profile details, there is a section for Interested properties, which shows the cards of those PGs that the logged-in user marked interested, across any city.
	d. From this list, the user can click the heart icon on any PG card, to remove that PG from the interested list, and that specific page section gets dynamically changed according to the user's action.


5. The Navbar:-
----------------
	a. Contains brand name.
	b. If NOT logged in, it shows the option to sign and log in.
	c. If logged in, it shows the option to go to Dashboard and Logout. Also, it displays the user's first name who is being logged in currently, by using SESSION.
	D. Totally responsive toggler navbar.


6. The Breadcrumb:-
--------------------
	a. Beautify shows the relative location of the user in the web app.
	b. Contains hyperlinks to easily navigate back and forth an endpoint.


7. The Footer:-
-----------------
	a. Shows the list(containing hyperlinks) to show the list of PGs in the most popular cities.
	b. Displays copyright information.


8. The entire web app can be surfed without logging in for user's ease and attraction for new users. Only certain features such as a dashboard, and marking interest are available upon login.

9. Through the entire web app, each and every exception is handled well using custom codes and UI,	such that they are easily managed, and the user can get to know the fault.
