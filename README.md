cross-document-messaging-demo
=============================

These are the Cross-Document Messaging Demos you see in Day2 morning section.

The three folders represent three local webservers with different ports:
cross-document-messaging (main page running port 8080)
cross-document-messaging-other-domain (8081)
cross-document-messaging-third-domain (8082)

In order to run all these webservers, you need to install Google AppEngine on you laptop first:
https://developers.google.com/appengine/downloads#Google_App_Engine_SDK_for_Python

Select and download and install the latest version for your operating system.
After successfully install the Google AppEngine. Run it and select "File > Add Existing Application" on the menu and select one of the folders above. You may need to update the Port (NOT the "Admin Port") number after selecting the folder. Repeat this untill you add all three folders and then finally start them all.

1. direct access demo: 
http://localhost:8080/1.direct-access.html

2. postMessage demo: 
http://localhost:8080/2.post-message.html

3. ChannelMessage demo: 
http://localhost:8080/3.channel-messaging.html
