# Note Taker

**Github URL**
https://github.com/usualketchup/notetaker

**Heroku URL** 



## Description

* An application is used to write, save, and delete notes. This application uses an express backend and saves and retrieves note data from a JSON file.The following HTML routes have been created:

  * GET `/notes` -  Returns the `notes.html` file.

  * GET `*` - Returns the `index.html` file

* The application has a `db.json` file on the backend that stores and retrieves notes using the `fs` module.

* The following API routes have been created:

  * GET `/api/notes` - Reads the `db.json` file and returns all saved notes as JSON.

  * POST `/api/notes` - Receives a new note to save on the req.body, adds it to the `db.json` file, and then returns the new note to the user.

  * DELETE `/api/notes/:id` - Receives a query parameter containing the id of a note to delete. It gives each note a unique `id` when it's saved. In order to delete a note, user needs to read all notes from the `db.json` file, also removes the note with the given `id` property, and then rewrites the notes to the `db.json` file.


## User Story

* Upon launching the app, users would be able to take persistent notes allows him to write, read and delete information available when needed.It allows users to create and save notes, view previously saved notes and delete previously saved notes.

## Technologies Used:

    * HTML
    * CSS 
    * JQuery
    * Bootstrap
    * Visual Studio Code
    * NPM that uses Express, Data Parser, FS
    * Local PORT Server

## Challenges:

* This activity took some time to do because building the backend without that much experience with it took a lot of time. I feel like I have more of a concrete understanding of running servers and deploying from Heroku.

![image](public/assets/images/notetaker.gif)

