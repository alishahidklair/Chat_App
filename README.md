# A simple chat application using Flask and Fauna DB 

## How to run
* Web App: https://aliklairchatapp.herokuapp.com/
* Desktop App: https://appmaker.xyz/web2desk/download/E2tHA7lH1zF9jwQBuS51 - Linux, Windows, Mac
* `Console:`
*   `pip install requirements.txt`
*   `python main.py`

## Credits
* This project is an implemetation of the source code provided at: https://github.com/Bamimore-Tomi/fauna-chat 
* More help on making your own chat app can be found at: https://dev.to/bamimoretomi/building-instant-messaging-app-with-flask-socketio-and-fauna-3pj1
* My contributions include setting up the Fauna database, linking with the database, and changing some of the source code to make it all work, using Heroku to make a web app. and finally using https://appmaker.xyz/web2desk# to make a desktop app that launches the web app in native window in 3 opereating systems - Linux, Windows, Mac.
## Description
* This is a simple web application that allows chatting between 2 parties.
* The index page allows sign up and login. anyone can sign up as long as the username is not already registered (the user is redirected to the sign up page again). All the data is stored in the Fauna DB's free server. but the password is stored as a hash.
* The login page take email and password inputs from the user and redirects to the chat page. If both email and passord match.
* The chat page offers a basic chat UI. Which allows new chats to be started using the New Chat button and providing an email. If the email exists a new chat is created in the inbox.
* Then messages can be sent back and forth between the two users. Message history is saved in the DB and is displayed and the message box is auto scrolled after every new message. The inbox also show the most recent message under the username.
