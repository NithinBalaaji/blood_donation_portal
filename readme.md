﻿# Blood Donation Portal
## Installation Instructions
### Prerequisites

 - NodeJs
 - MongoDB
 - NPM

### Installation

    git clone https://github.com/adwaith007/Blood-Donation-Portal.git
    cd Blood-Donation-Portal
    npm install

   
  Make sure that your mongo daemon is running, else run this command.
  

    sudo service mongod start

 Copy configuration files and make changes in it. Make changes only in index.js file and not in config.example.js file.
 

    cp config/config.example.js config/index.js

 Start your app using the following command

    npm start

Try hitting localhost:3000/test on your browser. If you get this message then your installtion is successful.

    {"success":true}
### Developing

See [CONTRIBUTING.md](CONTRIBUTING.md)