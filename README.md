# Project 2

Web Programming with Python and JavaScript
This is a flask application similar in concept Slack. I call it JOFLACK.
The application is mobile responsive

2 Python files:
application.py is the backend.
loginrequired.py provides fuction for login_required decorator (need to have username and channel in order to get to index.html)

3 html pages:

1:index.html:
 page where all the chatting happens. You can also add and deletes channels. No two channels can have the same name.
 Includes personal touch of being able to delete your messages.

2:sign_in.html:
 initial page when you enter the app. Can login in.2 logged in  users cannot have the same username. Will throw an error if you try. Also prevented from submiting a username if input field is blank.

3: Channels.html.

  Page user is directed to after signing in. Can get to this page in index.html as well. Users can choose between adding a new channel or entering an exitsing channel. The form will prevent a user from entering a new channel and trying to enter an existing channel.

2 javascript files:

1: index.js:
   this is the main Javascript file that has all of the socket.io code including rotues for sending messages, adding channels, deleting channels and deleting messages.

2: channelverify.js:
   This script has the code to prevent a creating a channel with the same name as an existing channel.

"/" (index):
