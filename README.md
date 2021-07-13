# Microsoft Teams Clone

A mobile Application used for chatting and video calling.I used flutter as the platform and Android Studio as the IDE.

## Getting Started

This application enables users to connect via chats and video calls.

Design Considerations
Assumptions and Dependencies:
Internet Connectivity

Android Version 9 and above


General Constraints

Not more than 7 people can join the meet at a time.

Development Methods

Authentication and log in using google services

Chat messaging using firebase

Video  calling using Agora SDK

token generation server for video calling using Node.js

Detailed System Design


When the app is opened depending on whether the user has already logged in login screen or dashboard is shown
At the login screen forgot password feature is available where the users can reset passwords by requesting a reset link through the mail. Also, the option Is available to register a new user.
The dashboard has three tabs :
1.Chat View: All the previous one to one chats are displayed here. If there are no chats then the user is shown a promo to talk to a dummy account where a chatbot can be enabled in future. The search button is available where the user can search for others using their usernames and initiate a conversation. 
The conversation screen is the one where the chats between the uses are available. Also, users can initiate a video call and continue the conversation there, the meeting chats will also be stored in the chats.
2.Group View: All the groups user is a part of are visible here. The create a group button is available where the user can create a group and add participants by searching them with their user name. The group stores all the conversations between the participants, users can initiate a video call and continue the conversation there, the meeting chats will also be stored in the chats. 
3.Meet View: Options are available either to host a meeting or to join a meeting. A meeting can be joined in the two roles: Audience Role: where the user can just be a spectator and Participant Role where the user can be part of the call and messages in the call.
The dashboard also has a signout button to log the user out of the account. user info can also be viewed on the dashboard.


Design Doc:https://jeewa.bit.ai/docs/view/W8DbVQK1idA5OP7T 

UI Schema: https://framer.com/projects/lMKesNM3YqA5Eur44P4j-28kg8
