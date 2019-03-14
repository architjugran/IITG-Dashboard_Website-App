# IITG-Dashboard_Website-App

1. Time table : We have scraped all of IIT Guwahati’s website data using BeautifulSoup and Python to display the daywise timetable in both the app and website on selection of Department, Programme and Semester.

2. The dashboard in the app and website displays the clickable club names . 

3. Each club page has the following tabs ( for both app and website): 
a. Home : Club name ,description and photo
b. Events : All events appear as individual cards displaying heading, date, description, venue, time, contact info.
c. Resources : All resources have a title and a clickable URL which fires an intent to open the browser with the specified URL
d. Announcement : They appear as individual cards showing heading , time, date and description.
e. Gallery : Any images uploaded by the club secretaries will appear here 

4. New club pages and modifications in club page can be done only on website only if user is authorized. App only displays data . Also , the database of both the app and website is common and in sync. Anything added/updated on the website will appear in the app automatically. 

5. Master credentials used for creating new club pages after sign in
a. Username : admin@iitg.ac.in
b. Password : admin1234

6. When master credentials are used to create a new club page, a new set of credentials will be generated for the new club page . Now using those credentials , a person will be authorized only to make changes/additions in that club page only

7. An event calendar ( on website) uses Google Calendar API. All events added on different club pages will get automatically added to the common event calendar

8. The home page displays general information about IIT Guwahati.

9. The database is maintained using Firebase Realtime Database of Firebase , Google’s mobile and web application development platform.
