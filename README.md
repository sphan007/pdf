# Remind You!

Assignment 1: Design  

10-18-17  

Fall 2017

by Steven Phan and Roberto Trejo Gonzalez

## Introduction

This easy to use application will let you set reminders on an specific date that will send notification straight to your phone. You can share reminders to colleague where they can get the same notifications also on their phone. There will be a drop down menu for the month, date, and year at the top. Then a text box below to put in the occasion.

## UML

## Classes/Class Groups
Interface - First thing the user should see  
Dates - This will contain the month, day, and year for the user to customize the specific date they want to set the reminder.  
Time - Hours and minutes. AM and PM.  
Type Box - Interface where the user can type. Limit to 30 characters.
Reminder - Should contain all the function that deals with the functionality of setting a reminder for a specific date
setReminder - Select date and time on specific date then put in text for the occasion for the reminder.  
shareReminder - Allow user to send a reminder to a colleague where if they have the same application, it will be added to their own personal calendar.  
setNotificationType - Ability to set certain type of notification such as sound, vibration, consistant reminder everyday or on the day of the occasion. Customizable features.

## Coding Strategy
First make the interface. It should contain a menu to choose the date and time. Once that is set, the user should be able to write what the occasion for that reminder is for. They should be presented to a text box to type in.  Each of these classes should be worked on one by one. Work should be split evenly for each class. One function per person for the class and test out each respective functions. Combine each of the respective functions of the class and make sure that the functionality of the application works as intended.

## Roadblocks

If the reminder collides with another's person reminder. There should be a prompt that tells the user that there is a collision with their schedule. Should have an check system to make sure that there will be no collision with the user and the person they are trying to share with.  
If there is a user that doesn't want to receive an reminder from a person, they should be able to decline it.  
If the interface doesn't work such as buttons not working or the resolution not being appealing to the eye of the user--there should be tests done for each minor function of the interface to make sure they work.  
Notification system might not work as intended such as getting a sound notification rather than a vibrating one or even not getting a notification at all. We can fix this by making sure each type of notification works based on what the user wants.
