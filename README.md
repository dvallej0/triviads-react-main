Abstract
TriviADS was a project created with the purpose of creating a trivia game website that will engage all types of users from the ages of eight and up to be engaged in a fun and educational platform. While also helping the developers of the project to learn software engineering concepts, such as the Agile form which is a type of iterative approach to help the team to deliver the project. During the Agile approach and the whole project, all the developers learned what is a sprint stand-up and sprint review. TriviADS have selective categories to pick from such as Arts & Literature, Entertainment, Geography, History, Mythology & Folklore, Religion, Science, and Sports. Another feature offered on the TriviADS website will be a time that will be set to ten seconds, if the question is not answered in those twenty seconds, then the question will move on to the next one and the user will not get the points for that question. There are a total of fifty questions, but the fifty questions will be split into ten, twenty-five, and fifty; this will give the chance for the user to make the game as long as they want or shorter. Before starting a game, the user will have to create an account, so they can have all their information saved in there. Lastly, the tools used for Front-End were HTML, CSS, BootStrap, and React; for Back-End were Firebase, JavaScript, and React; for the Database were Firestore, and Firefoo.
Keywords: Agile, sprint standup, sprint review, Front-End, Back-End, Database, React, BootStrap, Firebase, Firestore, Firefoo.

Summary
The project TriviADS was done using the following tools for each section: for Front-End: HTML, CSS, BootStrap, and React; for Back-End: Firebase, JavaScript, and React; for Database: Firestore, and Firefoo. The developers were able to put each part of the project together by using React, which made the whole process easier. TrviADS is a trivia game website that was built with the mission of expanding the knowledge of the users through a fun and educational platform. While also, helping the developers to learn software engineering concepts that will help them in the future. One of the most important concepts that was learned from the project was Agile and how the approach works. There are two important things that make up the Agile approach and those are sprint stand-up and sprint reviews. TriviADS have selective categories to pick from, such as Arts & Literature, Entertainment, Geography, History, Mythology & Folklore, Religion, Science, and Sports. Another feature offered on the TriviADS website will be a time that will be set to twenty seconds, if the question is not answered in those twenty seconds, then the question will move on to the next question and the user will not get the points for that question. Also, the game doesn’t have a limit of how many participants can join the game, making it a super fun game for the whole family if they all wanted to participate. There are a total of fifty questions, but the fifty questions will be split into ten, twenty-five, and fifty, meaning that this gives the user the choice to make the game as short or long as they want to. Also, an account must be created by the user to play the game, this was done with the purpose of the user being able to see themselves in the leaderboard with the username they chose and also see how many games the person has created since they have joined TriviADS.


List of Figures
Figure 1 Home Page……………………………………………………………………………….7
Figure 2 Sign-Up………………………………………………………………………….…….…8
Figure 3 Login…………………………………………………………………………………..…8
Figure 4 Mobile View…………………………………………………………………………..…8
Figure 5 className in React ……………………………………………………………………..8
Figure 6 Login Code……………………………………………………………………………..11
Figure 7 Sign-In with Google…………………………………………………………………....11
Figure 8 Dashboard………………………………………………………………………………11
Figure 9 Game…………………………………………………………………………………....11
Figure 10 Questions Database…………………………………………………………………...13
Figure 11 Users Database………………………………………………………………………..13
Figure 12 Game ID Database…………………………………………………………………....14
Figure 13 Players Database……………………………………………………………………...14
Figure 14 Sign Up Database…………………………………………………………………….15
Front-End
	The pages that were done by the front-end developer were: home, login, register, about us, dashboard, profile, waiting room, game, and navigation bar. It was decided that the colors that would be used as the background of the website would be purple and pink. These two colors were used because it is the color the developers thought would give a unique style to the project and add a friendly environment to the users. Also, the buttons were made in black so the user could read them and the sentences or script in white, this was all done so the user would be able to read it clearly and not struggle. The most important page of the website was the dashboard because this is the place where it gives the user the chance to be themselves and not limit themselves, in the sense, that in this section they get to pick the category they would like to play on and the amount of questions they would like to answer, also whether they would like to play solo or multiplayer. Even though the solo player might not be as competitive as the multiplayer,  it still gives the chance for the user to compete against their record. For example, if a user scored 1800 points for a game, in the next game the user can try to beat that record making it harder and more competitive. The home page was done to give details about what is TriviADS, the features the website brings, and how the game is played. Also, the navigation bar and the website is responsive, meaning that if a user decides to make a window smaller the website will adapt to the measures of that website. TriviADS is also made for the phone, making it playable at any place the user decides to be, for example, if a user is in an Uber and it is a boring trip, the user can get their phone out, go to our website and start playing simple as that. The waiting room is where all the players will go and wait for the host to start the game and the waiting room is only useful for the multiplayer because where everyone waits for all the players to join. The game is where the actual fun begins because it is where all the players get to answer a question, they must answer the question in twenty seconds otherwise they will not get points for it.  At the beginning of the project, the plan for front-end was just to use HTML and CSS, but then it was noticed that just by using only these two tools the project and front-end part of the project wouldn’t achieve the expectations we had set for each other, so it was decided to add React and BootStrap. React was added so the developer working on the backend would be able to keep on advancing without having to wait for the front-end developer to have the decorations done, just a simple architecture of the website was enough for the backend to work with. Bootstrap was then added to facilitate the work for the front-end developer in the sense that instead of the developer creating a whole new class with its property for one section of the project, the developer would get it from BootStrap and add it to the front-end saving time for more advancements of the project. The way to add a class in react using  BootStrap is by writing className = “”.
Figure 1: Home Page:


Figure 2: Sign-Up:
Figure 3: Login



Figure 4: Mobile View:

Figure 5 className in React

Back-End
The backend was super important when it came down to implementing the functionalities of the website. Without the backend, TriviADS would just be a cover page. The backend was built using React and Firebase. React was used for building the user interface and is employed to create the frontend components and manage their state. On the other hand, firebase provides prebuilt back-end functions and a NoSQL database which helped the developers advance the progress of the project. The login is where the user will input their information to get access to the website and get to play, as login is a requirement of the website before playing. To give this section of the project functionality React hooks were used, this tool managed the state of email and password inputs. In other words, when the user inputs their email and password and clicks submit the information that was imputed is checked against what is stored in the user collection, if is not saved then the website will make the user go and create an account, otherwise, they will be able to log in and play as many games as they want to. TriviADS website, also, welcomes new users to join the website and play games. This is done when the user registers with their email, username, and password. This is handled in the register.js file which uses the Firebase function that registers a new user on our website. Also, if a user doesn’t want to register, TriviADS gives the choice to the user to log in with their Google account, which Firebase provides that prebuilt function to help the users to log in with their Google account. The dashboard is where the user gets to pick the fun categories that TriviADS offers, and the amount of questions they want to answer, such as ten, twenty-five, and fifty. Also, this is the place where the user gets to choose if they want to play solo or multiplayer with friends and family members. When a user is done picking their preferences for the game they click “create game” and a four-digit code is generated for them and they can choose to share that code with other players. If the user is joining a game they must enter the correct code to join, otherwise, a message stating that an invalid code has been entered will appear and they can try again. After they enter the correct code and click join they are sent to the waiting room. The waiting room serves as an intermediate stage for the dashboard and the game. All the players will be shown as a list from top to bottom, not having any specific order. The person that created the game must start the game by clicking “start” or wait for all the players to join to start the game. The component listens for real-time updates to the game document in Firestore, ensuring that the list of participants remains up-to-date as new users join.  The Game.js component is the core of the trivia gameplay experience. It manages the game state, including the current question, user answers, and game timer. The component subscribes to real-time updates from the game document in Firestore, ensuring that all participants have the most recent game state. When a new question is presented, a countdown timer is started, giving users a limited amount of time to answer. Users can submit their answers by clicking on the available options, then their points are calculated and shown on the screen. After the game is finished it shows the game is over and from there, users can choose to return to the Dashboard, join another game, or create a new game.
Figure 6: Login Code

Figure 7 Sign-In with Google


Figure 8 Dashboard

Figure 9 Game

Database
Lastly, an implementation of a database needed to be done. This is where the website gets all the main information, such as the questions that the users will be answering. Without the questions that are stored in the database, TriviADS wouldn’t be a trivia game and it would be something else. The database was originally going to use SQL and accessed with PHPMyAdmin. This change was done because the game needed to be multiplayer, and Firebase offers a real-time database that permits the transfer of data fast and also allows the users to interact in real-time, in other words, play online. Without the database, there would not be multiplayer, meaning it plays a key role in the TriviADS website because multiplayer is a feature the website offers. Security plays a big role in any type of website and TriviADS is not an exception. Firestore helped achieve that with the use of Cloud Firestore security rules that allowed control access to the database. Since the project was changed to use Google Firebase there had to be a change from SQL to NoSQL, therefore the schema had to change from tables to JSON. There was a GUI client available called Firefoo, that offered a free 14-day trial, allowing for very easy importing of the data, in this case, the questions. The source for some of the questions came from www.trivianerds.com and more were created by the team. The functions to access the database were done using JavaScript. The database is kept secure by creating rules for Firestore which state who can access what in the database. The schema is the setup for the collections. The  “questions” were divided into separate collections with the category name as of the collection name for example, geography would be the category and all the questions relating to geography will be stored in there. The answers are stored as a list of values with three incorrect options and one correct option. This was done to allow for less repeated options and options that don’t make sense when presented to the user, for example, when the question asked for a name and presented an option for a year.
Figure 10 Questions Database

	The “users” collection was made with the keys, “authProvider”, “email”, and “username”. The collection was made to store the username for use on the website if they did not use Google as their sign in.
Figure 11 Users Database
The “GameId” collection stores all the games created with a 4-digit number used as the document ID. In each document the key-value pairs are “access: 4-digit number”, “category: category name”, “createdBy: useremail”, “isStarted: true/false”, “numOfQuestions: number of questions”.
Figure 11 GameID Database

	The “players” collection stores the points that each player accumulates in a particular game. It contains the keys, “gameID”, “name”, “points”, and  “role”.
Figure 13 Players Database






Figure 14 Sign Up Database




Conclusion
In conclusion, the team successfully developed a trivia game website using React, Google Firebase, and Bootstrap. Throughout the project, the team aimed to create a website that would provide users with an engaging and enjoyable experience while also improving the developers' skills in software development, learning to work in a team, and learning how to use Agile.
Using React, helped to create a dynamic user interface that is responsive and easy to navigate. Google Firebase provided a secure and reliable backend that enabled the team to store user data, question data, and manage the game. Bootstrap allowed us to create a visually appealing design that is both functional and aesthetically pleasing.
TriviADS website offers a range of features, including multiple categories of trivia questions, a real-time leaderboard when playing, and a user registration system. It is believed that these features provide users with a fun and engaging experience that will keep them coming back for more.
Overall, the team is proud of the work we have done on TriviADS and even though the team was not able to implement every feature that was in the plan, the team feels that it has accomplished the goals of creating a good-quality trivia game website. The team hopes that our website will continue to be a source of entertainment and enjoyment for users for years to come.
References
(n.d.). From Trivia Nerd: https://www.trivianerd.com/
(n.d.). From React: https://react.dev/
Add data to Cloud Firestore. (2023, April 27). From Firebase:
https://firebase.google.com/docs/firestore/manage-data/add-data?hl=en&authuser=0
Authenticate Using Google with JavaScript. (2023, April 27). From Firebase: https://firebase.google.com/docs/auth/web/google-signin?hl=en&authuser=0
Authenticate with Firebase using Password-Based Accounts using Javascript. (2023, April 27). FromFirebase:https://firebase.google.com/docs/auth/web/password-auth?hl=en&authuser=0
Get realtime updates with Cloud Firestore. (2023, April 27). From Firebase: https://firebase.google.com/docs/firestore/query-data/listen?hl=en&authuser=0
 
Appendices
A1. createUserWithEmailAndPassword

A2. signInWithGoogle

A3. onAuthStateChanged

