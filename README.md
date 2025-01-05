# CS360

Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
  The goals for this Event Tracking application would be to develop a user-friendly mobile application that will meet all the user’s needs:
  1.	A database with two tables to store the event details and user logins and passwords. The user login and password database will be used for the application to verify the user’s login credentials and will only allow access if the username and password are correct. The event database will be used to store all the details of each event that have been added to the database.
  2.	A screen for logging into the app. The login screen will be simple but user-friendly for logging in to the user’s account. It will have a field for username and password and a button to sign in. It will verify the username and password are correct after the fields are populated and button is clicked.
  3.	A user-friendly display of upcoming events. The display of schedule events will be seamless and simple for the user to view. It will give the user the ability to click on events to see the details of selected event.
  4.	The ability for the user to add and remove events. The user will be able to add new or remove existing events from the tracker. When adding a new event, the user will be prompted to populate the events details which will be stored in the database. When removing an event, the user will be asked if they are sure they would like to remove the event. The removed event will remove the events details from the database.
  5.	Notifications to the users of upcoming events. The application will have the ability to push notifications to the user’s mobile device if the user chooses to. This function will be optional for each end.

What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
The Event Tracking Application will have multiple screens:
  1.	A login screen, where a user will be able to login to their event tracker database.
  2.	A home screen, where the user will be able to navigate to all the other screens.
  3.	A tracker screen, where the user will be able to see all the upcoming events.
  4.	Event screen where the user will be able to see the details of any given event; this screen will be accessible from the tracker screen based on an Event selection by the user. This screen will also serve as the user’s ability to remove events. 
  5.	Add Event screen will be where the user has the ability to add a new event and its details.
  6.	Account screen, where the user will be able to manage their account and invite other users to their Tracker database.
  7.	Notification screen, where the user will have messages in more detail about any notification that was pushed to their mobile device. 

How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?
  I first started with the login screen design/layout. After that I wrote the code and with every feature I added to the code I would test that it would work properly using the android emulator. I think in the future I would do the same thing, add code and test as I went to make sure everything was working as expected.
  
How did you test to ensure your code was functional? Why is this process important, and what did it reveal?
  I tested by running the Android emulator. This process is important to make sure everything is working as expected, it would give you the errors during the build process which could then be used to determine where the error existed.
  
Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?
  I was having issues with the ViewList on my app. I was never able to get it functioning or displaying. I was able to confirm that the data was being recorded in the SQL database but could never get it to display.
  
In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
  I would say in the login screen/function of my app I was successful. I was able to get the code working to add new users to the database then check back for current users while logging in. 
