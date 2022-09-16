# FirebaseChatApp
Chat App created using Firebase

## What Is It?
In this exercise, MITxPro tasked us with taking a simple front end chat application and making it fully functional using Firebase. We were provided with the styling and template of the app. Then, we needed to connect it to a Firebase project using Realtime Database and Authentication. We had to be able to authenticate the user and store the chat messages from each sender in the database. These messages were then displayed in the chat box with the sender identified before each message. I included a video of what the final product looked like.

## What I Found Challenging
I'm still new to Firebase, so I initially struggled with getting the sender established. Once, I identified how the messages were sent, it easily integrated the sender's informtion as well. Firebase is easy to use and makes developing applications a breeze compared to other services and frameworks I have used.

## How To Use This App
Create a Firebase account. Retrieve your configuration information and input it in the `firebase-chat.js` file where the empty spaces are located. In your Firebase console, create a Realtime Database so that you can `read` and `write` data. Next, set up your authentication using email and password. Drag the `firebase-chat.html` file into your browser.

To chat, create a user with an email and password and sign up. Then log in using that same informtion. Write a message in the chat input and select `Write`. In another browser, create another account. Write from that browser. You should see each message displayed with the sender's email before each message.