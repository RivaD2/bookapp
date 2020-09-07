# Project Name: book_app
**Authors**: Michael Wohl & Riva Davidowski
**Version**: 1.0.0 (increment the patch/fix version number if you make more commits past your first submission)

**Overview:
This app implements a basic full-stack application for a book list which will include the ability to search the Google Books API, add books to a database, and then render those books from a PostgreSQL database. This app also provides the ability to update the details of a book or remove it from the collection.**

### Getting Started
* Created a basic `server.js file`. 
* We made sure the server is listening for connections on a `PORT`. The view engine needs to be set and serve your static CSS files.
* Installed necessary NPM packages and ensured that they are documented as dependencies in  `package.json`.
* For server-side rendering, EJS looks for a folder called `views`. I had to create a `views` folder, with a `pages` subfolder. 
* Within this subfolder, I created a file called `index.ejs`. 
**Note: with server-side rendering, index.ejs is analogous to the typical index.html file that we are used to, but will also allow EJS syntax for templating.**
* Created a basic HTML scaffold in `index.ejs` file which contains several elements that can be viewed in the browser, such as a heading element that says `"Hello World"`. 
* Created a basic CSS file with several rules, such as an obvious background color. These served as a "proof of life" that the files are connected as expected, both locally and when deployed.
* For testing purposes, we included a temporary route such as `app.get('/hello')` and rendered the `index.ejs` file. We turned on the server and validated that the HTML elements and basic CSS styles are being rendered as expected. This route is useful for the future if we need to test an application without relying on data from a database.

**Architecture:**
* For this project, we are using EJS for JS templating, Git, Github, Node.js to run Nodemon environment, Express, SQL, Postgres, and Google Books APIs.

**Change Log:**

01-01-2001 4:59pm - Application now has a fully-functional express server, with GET and POST routes for the book resource.

**Credits and Collaborations:** Collaboration with Michael Wohl

----------------------------

**FEATURE 1: Scaffolding of files for set up and test route creation**
**Scaffolding of HTML files and server-side rendering and implementation of a test route to validate that the HTML elements and basic CSS styles are being rendered as expected**

Estimate of time needed to complete: 2hrs

Start time: 4:00pmpm, 8/24/2020

Finish time: 5pm

Actual time needed to complete: 1hr

------
**FEATURE 2: Implementing a app.post route that allows user to search the Google Books API so that they can view the results their search**

Estimate of time needed to complete: 1hrs

Start time: 5pm: 8/24/2020

Finish time: 6:08

Actual time needed to complete: 1hr8min

-----------------
**FEATURE 3: Creating constructor function and a route handler for a `POST` request to `/searches`. This route's callback will use Superagent to proxy a request to the Google Books API and return a list of ten books that match the search query.**

Estimate of time needed to complete: 2hrs

Start time: 611pm 8/24/2020

Finish time: 7:30pm

Actual time needed to complete: 1hr30 min

----
**FEATURE 4: As a user, I want a simple, clean looking UI so that my application is easy to navigate.**

Estimate of time needed to complete: 4 hrs

Start time: 3:00pm

Finish time: 7:30pm

Actual time needed to complete: 4hrs30min

Actual time needed to complete: 3hrs30min

-------
**FEATURE 5: Saving books to display on the home page so users can see all of the books from their collection in a single view.**
- Built our `index.ejs` file to utilize the database results when rendering the page. Followed correct EJS syntax to iterate over an array of book objects and rendered each one in a similar manner, according wireframes provided

Estimate of time needed to complete: 4 hrs

Start time: 2pm

Finish time: 6:00pm

Actual time needed to complete: 4hrs

--------

**Feature 6: Heroku Deployment**
- In the Deploy tab, connected an instance to our repository and enabled automatic deploys from the master branch. Deployed our application and made sure there were no errors.
Estimate of time needed to complete: 30 min

Start time: 3pm

Finish time: 3:45pm

Actual time needed to complete: 45min

-------
**Feature 7: Creating a table in which to store each book added by the user and a schema for your books table.** 
- This schema should contain the following properties:
id as the primary key
author
title
isbn
image_url
description

Estimate of time needed to complete: 1hr

Start time: 2:30pm

Finish time: 3:45pm

Actual time needed to complete: 1hr15min

-----

**Feature 8: Adding at least two books to your database and in your Heroku instance, provision a Postgres database**
- Migrate your local database to Heroku, using the following format for your command: `heroku pg:push books_app DATABASE_URL --app <partner 1 initials>-<partner 2 initials>-booklist`
- Make sure that your schema is properly documented in your book app repository’s main README.md file. If you made a schema file, make sure it is added, committed, and pushed to GitHub.

Estimate of time needed to complete: 1.5hrs

Start time: 1:30pm

Finish time: 3:40pm

Actual time needed to complete: 2hrs10min





