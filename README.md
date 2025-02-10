# Budget-Tracker &middot; ![node](https://img.shields.io/badge/node-12.16.2-blue) ![compression](https://img.shields.io/badge/compression-1.7.4-blue) ![express](https://img.shields.io/badge/express-4.17.1-blue) ![lite-server](https://img.shields.io/badge/liteserver-2.5.3-blue) ![mongoose](https://img.shields.io/badge/mongoose-5.5.15-blue) ![morgan](https://img.shields.io/badge/morgan-1.9.1-blue)

![Budget-Tracker](/images/Budget-Tracker.png) 

## Description 
This application gives the user the ability to enter and track income and expenses in a line graph over time. 

## Table of Contents 
* [Installation](#installation) 
* [Usage](#usage) 
* [Third Party Contributors](#third-party-contributors) 
* [License](#license) 
* [Questions](#questions) 
 
## Installation 
1.  Install node: go to nodejs.org and download latest version and walk through the installation instructions  
2.  Go to project folder and enter: “npm install”. This will install all dependencies listed in the package.json file.  
3.  Run the application on the localhost server on Port 3000 by typing “node server.js”  
 
## Usage 
1.  Once the application has started, the page sets the initial budget value at $0 with an empty form with add and subtract funds buttons, and an empty table. ![Budget-Tracker-Begin](/images/Budget-Tracker-Begin.png)  
2.  The user can then enter a transaction name and value and select either the “Add Funds” button or the “Subtract Funds” button. Once a button is selected, that new item entered is now displayed in the table below, and it’s displayed in the chart below as a blue dot on the y-axis of the graph at the value that was entered. Directly below that value, on the x-axis displays the date it was entered ![Budget-Tracker-First-Entry](/images/Budget-Tracker-First-Entry.png)  
3.  When a second item is entered into the application, that second item is entered into the table and a second dot is displayed at the value from the result of either adding to the previous value or subtracting from it to get to the new total. In this example, 3000 was entered as a paycheck first, and 1000 was entered as rent which was subtracted from it. The two value dots are connected with a line and a blue fill color is displayed underneath them to help visualize the total value  ![Budget-Tracker-Results](/images/Budget-Tracker-Results.png) 
4.  When the Transaction table gets larger than six items, the rest of the items become hidden and a vertical scroll bar is provided on the right to view the rest of the items.  ![Budget-Tracker-Overtime](/images/Budget-Tracker-Overtime.png)  
5.  If the user decides they want to start over again, they can clear all the data from the table and the graph by clicking the “Clear All Data” button at the bottom below the graph. Once “Ok” is selected in the confirm dialogue box, all data is deleted from the database and the initial view is displayed as described in the beginning. 
![Budget-Tracker-Delete-All-Data](/images/Budget-Tracker-Delete-All-Data.png) 
 
## Third Party Contributors 
* User interface design, layout, table display, and chart display provided by the University of North Carolina Code Bootcamp. 
* Database connection, client data storage, and clear all data functionality provided by Nick Romano. 
 
## License 
There is not a license for this application. 

## Questions 
![GitHub Profile Image](https://avatars.githubusercontent.com/u/6642173?) 

 njr7romano@yahoo.com
