# Easily integrate a Watson Assistant Chatbot in a PHP web app

This project allows you to easily integrate a responsive banner at the bottom of web page with a button to a chat panel powered by IBM Watson.


## Prerequisites

In order to use this code, it's necessary to have:

1. An IBM Cloud account. It's free of charge, no credit card required (only a valid email address)
2. A Watson Assistant Lite Service (free of charge)
3. A trained Watson Assistant Workspace
4. A PHP application


## How to use

1. Download or fork code
2. Edit php/ChatBot.php file with Watson Assistant credentials (username & password), release date of api, Workspace ID of the selected Virtual Assistant
3. Edit CSS to fit in your web application's graphics
4. Edit getWatsonAssistantData() in js/chatbot.js with context variable names to be checked in order to perform actions
5. Edit useWatsonAssistantData() in js/chatbot.js with personal code to perform actions


## Tutorials

Please find tutorials on how to train Watson Assistant here: link to come (Italian spoken, but with English interface)


## Notes

This code uses an local hosted version of:

1. Carbon Design System: http://www.carbondesignsystem.com/
2. Material Design Lite: https://getmdl.io/

You can also use your own graphic framework.


## Disclaimer

This is not an official asset. It has been created by me and it's not intended for professional use. However, it follows all guidelines you can find in https://console.bluemix.net/docs/services/conversation/ and in https://www.ibm.com/watson/developercloud/assistant/api/v1/.
For Watson Services SLAs, please have a look here: https://www-03.ibm.com/software/sla/sladb.nsf/sla/bm-0038-09.


## Outcome

Here some screenshots of the outcome, in both desktop and mobile screens.

### Desktop layout
![Bottom assistant desktop](https://github.com/lucacrippa88/watson-assistant-php/blob/master/screenshots/bottom-assistant.PNG)
![Bottom assistant desktop chat](https://github.com/lucacrippa88/watson-assistant-php/blob/master/screenshots/bottom-assistant-open.PNG)
### Mobile layout
![Bottom assistant mobile](https://github.com/lucacrippa88/watson-assistant-php/blob/master/screenshots/bottom-assistant-mobile.PNG)
![Bottom assistant mobile chat](https://github.com/lucacrippa88/watson-assistant-php/blob/master/screenshots/bottom-assistant-mobile-open.PNG)
