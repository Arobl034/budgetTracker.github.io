# Budget Tracker :bank:

This is a simple Budget Tracker application with offline access and functionality.

## Purpose

This app was developed with the purpose to practice adding offline functionality through indexedDB.

## Functionality

1. Users can input their ongoing transactions by name and amount.
2. The transactions get stored in a noSQL database (mongodb) in the server.
3. If connection is lost, transactions are stored in the client side through indexedDB.
4. When network connection is re-established, the app queries indexedDB and if there is data, it is sent to the database in the server.

## User Interface

![Screen Shot 2020-05-06 at 10 58 55 PM](https://user-images.githubusercontent.com/58242373/81520494-7a5f9400-9312-11ea-912f-2a5a0af5615b.jpg)

## Deployed Heroku:
Deploy through Heroku. <a href="https://peaceful-brook-52779.herokuapp.com">Budget Tracker</a>
  - Heroku Add Ons: Install mLab MongoDB Sandbox
