# Module 21 Challenge Project - Module 21 MERN Challenge: Book Search Engine
This program is a search engine for books... use this application to get information on that one book you've been thinking about. First Sign up and create an account. Then once you're signed in, search for that one book you can't get off you mind. Or search for a theme like "Star Wars" and pull up all those books that meet that theme. After you searched for the book or books, you'll see images, authors, titles and description detail on each book listed. Enjoy the book search...


## Running the Book Search Engine.
* From the Terminal prompt, in this projects main folder you can perform a series of script functions that will compact, build and startup the MERN style application. Here are a list of scripts that are available to run via the terminal:

    * develop       : Concurrently changes to the client folder builds the package and starts the browser instance then to the server folder to start the server.

    * start         : Runs the build and changes to the server folder to start the server.

    * build         : Changes to the client folder and runs the build.

    * install       : Installs node modules.



* This application uses GraphQL with an Apollo Server to store and query all your favorite book searches. By using MongoDB, Node.js and Express.js the application runs so much faster and efficient then just using local storage alone.


### Special Notes:
* The server.js file is the main driver for starting the application server. I've created a structured layout for the javascript project itself. You will see the following folders: 
    
    - client

      * public - Contains boiler plate REACT data.
    
      * src - Folder for client data files.
      
         * components - Forms and Navigation bar.

         * pages - Logic for Saving and Searching books.

         * utils - Mutations and query detail.


         
    - server
      
      * config - Configuration settings for MongoDB

      * controllers - N/A

      * models - Database file definitions.

      * routes - N/A

      * schemas- TypeDefs and Resolvers for database searching. 

      * utils - JSON Web-Token settings for authentication.


* Packages installed for this application were:
    
    - apollo-server-express: "^3.11.1"
    - bcrypt: "^5.0.0"
    - express: "^4.17.1"
    - jsonwebtoken: "^8.5.1"
    - mongoose: "^5.9.10"
    - @testing-library/jest-dom: "^4.2.4"
    - @testing-library/react: "^9.3.2"
    - @testing-library/user-event: "^7.1.2"
    - bootstrap: "^4.4.1"
    - graphql: "^16.6.0"
    - jwt-decode: "^2.2.0"
    - react: "^16.13.1"
    - react-bootstrap: "^1.0.1"
    - react-dom: "^16.13.1"
    - react-router-dom: "^5.1.2"
    - react-scripts: "3.4.1"
    - concurrently: "^5.3.0"


* Link to Heroku.
https://mern-challenge-book-search.herokuapp.com/

### Screen Shots.
![image](https://user-images.githubusercontent.com/108200823/200008700-70c93af7-7be2-41d2-9932-46e3595adda7.png)
![image](https://user-images.githubusercontent.com/108200823/200008755-79f7a4ae-9515-4074-b22f-a37518422e9a.png)
![image](https://user-images.githubusercontent.com/108200823/200008885-c4ac8fac-17c0-447d-9553-9e3e65448d9e.png)
