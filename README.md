# Lab 10 - Race Track

## Introduction
In this lab you will create a very basic race simulation game using threads. 

## Exercise 1
Run Semaphore application an observe how a thread is created and started. 

## Exercise 2
Analyize CarRace class and idientify what is missing and what instructions you need to add in orther to start the race for 4 created and ready to race cars.

## Exercise 3 
Put together Semaphore and CarRace so that race starts when semaphore is green (Semaphor thread has finised execution). For implementing this exercise you will use join() method. 

Strating with this exercise you will work in raceapp package. Copy in the raceapp package the classes from racedemo package and do necessary changes there.

## Exercise 4
Update application from exercise 3 so that sound start playing when cars start racing and stops when all cars finished.

## Exercise 6
Add a mechanism to detect and display (in text mode or graphical) the standing order after race finish and race duration for each of the car. 

## Exercise 7 
Create a thread which increment a timer (long variable each 10 miliseconds). The thread will be started when race start and will be stopped when race ends. After timer is stopped will display measured time.
