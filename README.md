# Building a Simple Note Taking API with Node.js, Express and MongoDB #

## Backend Developer Assignment: Simple Note-Taking API ##
Overview

Develop a RESTful API for a simple note-taking application using Node.js and Express.js, with MongoDB
as the database. The API should allow users to create, retrieve, update, and delete text notes.

## Assignment Requirements ##

MongoDB Setup:

Use MongoDB to store notes. Each note should have a title, content, and timestamps for creation and
last modification.

## API Endpoints:

• Create Note: Endpoint to add a new note to the database.
• Retrieve Notes: Endpoint to get a list of all notes, with an option to retrieve a single note by its
ID.
• Update Note: Endpoint to update the content of an existing note.
• Delete Note: Endpoint to delete a note from the database.
Data Validation:
• Implement validation for note creation and updating. Ensure that the title and content fields are
provided and are of appropriate lengths.
Error Handling:
• Develop comprehensive error handling for the API, covering scenarios like invalid input, trying to
access or modify non-existent notes, etc.
Basic Authentication (Optional):
• If time permits, add a simple authentication mechanism (like Basic Auth) to protect the
endpoints.
Documentation:
• Document the API endpoints, including details about request methods, URL paths, expected
request body format, and response formats.

## Testing:
• Write basic tests to ensure API endpoints are functioning as expected.
