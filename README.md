# Text Editor

#Description
This application is a web text editor. This application is designed and set up to be used as a PWA (Progressive Web Application). You can enter any notes, code, or thoughts. The content is saved in local storage as well as indexDB so that it can accessed while offline. The install button at the top of the page will set up the application as a PWA and prompt the user to install the application. Once the brower and PWA have been closed, the content of the editor remains on the page.![image](https://user-images.githubusercontent.com/110504360/219984598-50f25469-fd2f-4dae-b7df-c7a78b973be3.png)

User Story
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use

Acceptance Criteria
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application

#Installation
This program has been deployed to Heroku and can be found here  
Additionally there is an install button that should download it locally for you.

#Usage- add screenshots, website

![image](https://user-images.githubusercontent.com/110504360/219986027-2e73d85d-6923-41b9-b4f7-8882edf3897e.png)
![image](https://user-images.githubusercontent.com/110504360/219986031-59e0fd30-fab1-4909-9857-7a4a3cfffcd5.png)


#License- MIT


#Contributions![image](https://user-images.githubusercontent.com/110504360/219984709-e9ccf5ea-b129-456a-8575-b98ed1c61e41.png)
