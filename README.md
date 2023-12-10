## chat-app

## Introduction
Chat application that enables multiple users to communicate among each other. The App enables to broadcast each message that receives from sender to every receipient.

## Tech Used:
* React Native
* Spring boot
* Websockets

## Prerequisites
   * Install Java software 
   * Install NodeJs software

## Local setup

1. Clone this public repository to your local folder
   * `https://github.com/menjamuri/chat-app.git`
2. Setup Backend
   * Run `mvn clean install` to build backend application
   * Run 'mvn spring-boot:run' to run the application
3. Setup Client
   * Run 'npm install' under client/chat folder
   * Run 'npm start' to start the client App
   * Run `http://localhost:19006/`

## How to test?

* Open the url `http://localhost:19006/`. Please enter the name of the user and you will be to send the messages. 
* In order to test, Repeat the above step in another tab with different username. Two sessions will be created and chat app enables communication between the two.