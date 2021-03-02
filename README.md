# Unit-18-PWA-Homework
Unit 18 PWA Homework - Online/Offline Budget Trackers

[Link to deployed app]() 
(Click to open app)

GitHub Repo:    https://github.com/WillHeyer/Budget-Tracker


## Table of contents
* [General info](#general-info)  
* [User Story](#user-story)  
* [Instruction](#instructions)  
* [Business Context](#business-contect)  
* [Acceptance Criteria](#acceptance)  
* [Screenshots](#screenshots)  
* [Features](#features)  

## General info
A simple online/offline application that is used to track deposits and payments whether the user is connected to the internet or not with the help of service worker. When offline, entries are stored in IndexedDB and then uploaded to the database (MongoDB Atlas) when reconnected. Additionally, all data can be found in Cache Storage.

## User Story
AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling

## Business Context
Giving users a fast and easy way to track their money is important, but allowing them to access that information anytime is even more important. Having offline functionality is paramount to our applications success.

## Screenshots
![Example screenshot]()
![Example screenshot]()

## Features

Offline Functionality:

  * Enter deposits offline
  * Enter expenses offline

When brought back online:

  * Offline entries should be added to tracker.