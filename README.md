# VSAC-Job-Applicant-Code-Review-Exercise

Summary:
Thank you for your interest in applying for the Senior Web Programmer Analyst position at the Vermont
Student Assistance Corporation (VSAC). To be considered for the position, the Web Team is asking you
to submit the code for a Grails web application that will be responsible for searching for and displaying
meals via the usage of the free tier of TheMealDB.com API. The documentation for this API can be found
at: https://www.themealdb.com/api.php. Please note that we are not expecting a zip file containing
only the code but are expecting that you use a Version Control Management System (VCMS) i.e., Git,
Mercurial, Subversion, etc., but preferably Git to store, manage, and subsequently develop the
application we’re requesting you to build. I recommend using GitHub or Bitbucket to store the code
remotely. Where you choose to store the code is up to you, as long as it publicly accessible. This link is
essential in the consideration for your application for employment as version control, and code
management are an essential part of the job.
Minimum Project Requirements:
The code we will be evaluating is a simple Grails web application written under the web profile to be
able to search for meals based on the different criterion as outlined within the API documentation and
display the results onto a page. Once the results have been displayed onto the page the user should
then be able to either view further information on the meal or save the meal to a database to be viewed
later. There are one of two options you must use as a database:
1) H2
a. An in-memory SQL database which is built into the Grails framework.
2) MySQL
a. The data source that your application references must either be publicly accessible,
meaning I can connect to it running your code locally, or include the SQL script(s)
used to create it so I can create my own instance of the database.

Requirements:
1) The application that is to be written must be written in Grails 3.3.6 or higher.
2) Employ the usage of a modern front-end framework such as Bootstrap or Skeleton.
3) Implement the usage of SiteMesh, another built-in Grails framework feature to design, and code
the overall layout of the web application which should look something along the lines of:
4) Include the following pages/views:
a. Main landing page, which for brevity’s sake can also be the search page.
b. Page listing the saved items from previous searches
c. Either a button or a link to delete the item from a previous search
d. Page with the ability to edit a saved meal.
5) Ability to search for meals.
6) Display the search results or inform the end user that no results were found.
7) Display the results in a fashion that is mobile friendly.
8) Include the ability to save, edit, and delete a meal from the database via the usage of GORM the
built-in Object Relational Mapping (ORM) protocol that comes standard in Grails. You have
plenty of leeway in terms of how you want to design the database to store the data, but your
application must be database driven and use at least one Grails Domain Class.
Summary:
We are expecting to see a Grails web application that is written in version 3.3.6+ that contains the ability
to interface with a JSON REST API by saving, updating, and subsequently deleting the saved meal items
in a RDBMS solution. To go above and beyond the minimum requirements and really stand out from the
rest of the competition, add Spring Security to the application. Good luck on completing the exercise.
My colleagues and I are looking forward to reviewing your finished product. Thanks again for you
interest in the position.
