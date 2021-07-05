The challenge was to create an application called Note Taker that can be used to write and save notes. This application will use an Express.js back end and will save and retrieve note data from a JSON file.

The front end of the application was provided in a starter code for the challenge. Our job is to build the back end, connect the two, and then deploy the entire application to Heroku.

User Story
AS A small business owner
I WANT to be able to write and save notes
SO THAT I can organize my thoughts and keep track of tasks I need to complete
Acceptance Criteria
GIVEN a note-taking application
WHEN I open the Note Taker
THEN I am presented with a landing page with a link to a notes page
WHEN I click on the link to the notes page
THEN I am presented with a page with existing notes listed in the left-hand column, plus empty fields to enter a new note title and the note’s text in the right-hand column
WHEN I enter a new note title and the note’s text
THEN a Save icon appears in the navigation at the top of the page
WHEN I click on the Save icon
THEN the new note I have entered is saved and appears in the left-hand column with the other existing notes
WHEN I click on an existing note in the list in the left-hand column
THEN that note appears in the right-hand column
WHEN I click on the Write icon in the navigation at the top of the page
THEN I am presented with empty fields to enter a new note title and the note’s text in the right-hand column

The Mock-Up

The following images show the web application's appearance and functionality: NOTE: Please use locahost:8080 if application does not automatically go there. 

Existing notes are listed in the left-hand column with empty fields on the right-hand side for the new note’s title and text.

Note titled “Balance accounts” reads, “Balance account books by end of day Monday,” with other notes listed on the left.

Getting Started

The application is in a n file on the back end that will be used to store and retrieve notes using the fs module.

The following HTML routes should be created:

GET /notes should return the notes.html file.

GET * should return the index.html file.

The following API routes should be created:

GET /api/notes should read the db.json file and return all saved notes as JSON.

POST /api/notes should receive a new note to save on the request body, add it to the db.json file, and then return the new note to the client. You'll need to find a way to give each note a unique id when it's saved (look into npm packages that could do this for you).

*** Did not complete the Bonus***


This Challenge is to be graded based on the following criteria:


Satisfies all of the preceding acceptance criteria plus the following:

Application front end must connect to an Express.js back end.

Application back end must store notes with unique IDs in a JSON file.

Application must be deployed to Heroku.


Application deployed at live URL.

Application loads with no errors.

Application GitHub URL submitted.

GitHub repository contains application code.


Application console is free of errors.

Repository has a unique name.

Repository follows best practices for file structure and naming conventions.

Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.

Repository contains multiple descriptive commit messages.

Repository contains quality README file with description, screenshot, and link to deployed application.

