#YelpCamp

It is a full-stack web application developed using Express JS, MongoDB, and EJS and Bootstrap 5.Completely resposnive with added security and PassportJS authentiacation.

# Demo-Preview

https://limitless-depths-70935.herokuapp.com

#Installation

1 - Setup the development environment

    VS Code editor.

    Git Bash

    NodeJS

    MongoDB

        Download the Community server and select the Insall Mongod as server.
 
        Start Windows Powershell (press the Windows Start button and type ‘powershell’ to find the shortcut) and type the following command: New-Item -ItemType directory -Path         C:\data\db
   
        Add the mongodb installation C:\MongoDB\bin location to the path variable in System variables.

        run mongod command in terminal to start mongo server.

        run mongo command in seprate terminal to open mongodb shell.
        

2 - Install the depndencies

       git clone the project repository

       npm install will install the project's dependencies
       

3 - External APIs

    Cloudinary Registration for Image Storage

        Sign up for free account --> does not require credit card to start

        mbed the Account API Key and API Secret directly into .env

     MapBox for interactive clustered Map

        sign up and have access to a default public token --> can make new tokens if you want

        include token in .env --> MAPBOX_TOKEN=asdfasdfasdfasdf
