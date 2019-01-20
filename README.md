# Postman Tests
A Collection of tests I've written in Postman based off of various API projects/validations

# Overview #
I'm a QA Analyst from a non-technical background who wants to help other QA testers and Analysts learn to validate APIs/begin transitioning their testing from manual to more automated. I've got over a decade of manual testing experience and have spent the past few years exploring the best way(s) to teach myself code & test automation. Throughout this time I've experienced multiple periods of frustration with how little information there was available about automated testing & API testing written to/from a wholly QA perspective, vs. from those with engineering backgrounds/already fully versed in code. If the latter is you this project might be like learning the alphabet. But if you're about to give up attempting API testing because you can't figure out the difference between a string, number, endpoint, variable, or why when you try something it says "undefined"—you're in the right place.


## Setup ##
* Make sure you have installed/downloaded Postman
* (if you have a GitHub account) fork and/or clone this repository (Forking is how you save/favorite)
* (if not) favorite/save the link to these tests
* Download the collection called PostmanTrainingCollectionTests located inside this repository. You will need it for Step 1

## Step 1 ##
### Summary ###
In this step, we'll use the import function to add a collection of existing requests (tests) to Postman.

## Instructions ##
* Open Postman.
* Click on the import button located in the top left corner of Postman.
* After the Import window opens, either drag and drop the file you saved on your machine, or use the "Choose Files" button to locate the collection file called PostmanTrainingCollectionTests that you downloaded above.
* After importing, you should have a collection called PostmanTrainingCollectionTests on the left side of your Postman. If you click on it, the list of requests should expand/close.

## Step 2 ##
### Summary ###
In this step, we'll Send a New test/request (from inside the collection we imported in Step 1 above) to validate that the open source LibraryOfCongress/chronam API is returning a 200 status (OK) response

* Click on the first request from the collection "LibraryofCongress_200 Status"
* Click the Send button
* Verify that after "Loading" finishes you see two things: 1) a large amount of data (default is html) returned in the "Body" at the bottom of your window, and 2) the "Status" 200 OK
* Click on the Tests tab
* You should see a green Pass button and "Response Status 200" in the same portion of your window as the Response data from above
* If you like, you can scroll to the far right, to the SNIPPETS section and select/insert a portion of code. Edit it to fit the API test, (ex: Response body: Contains string, and alter the code to include "National Endowment for the Humanities") Place/write this SNIPPET/new test directly underneath the Status 200 test. 
* Click on Send again to see if your tests pass or fail.

## Step 3 ##
### Summary ###
Now that you should be comfortable Sending a request and parsing out the Response Status (200 is what you want to see) and Pass or Fail in the Test tab, you can select another Request from the collection to run - OR - add your own.

## Instructions ##
* On the left side of the window, underneath the PostmanTrainingCollectionTests Collection, select a new Request (ex: LOC_Content Response Validation). Click to open.
* Click on the Tests tab
* Hit the Send button
* Verify your Tests Pass
