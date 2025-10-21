# CS465-Full-Stack-Development-1
Architecture

Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).
Why did the backend use a NoSQL MongoDB database?

For this project we used the MEAN (MongoDB, Express.js, Angular, and Node.js) stack development to create the Travlr Getaway Application. Express.js is designed to simplify the process of building APIs and web applications and is a framework built on top of Node.js. Express.js works on the server-side of the development to build the API and web applications to manage paths to different pages (routes) and handles messages browsers send to the servers (HTTP requests). Angular on the other hand, which we used for the SPA (single-page application), allows all the work to be done on the client-side and minimized client-server traffic. The Express.js had multiple pages with repetitive HTML but the SPA made it possible to see the information needed all on one page. JavaScript is the language that is used to make our application interactive, running in the browser. Node.js allows JavaScript to run on the servers. JavaScript allows developer to update the content (adding, removing, and updating) for the user without reloading the page. JavaScript also supports asynchronous operation, which we used such as the await/asynch operations. The backend used a NoSQL MongoDB database because it stores data in a JSON type format which makes it great for handling unstructured and dynamic data. It also offers flexibility, and scalability allowing developers to manage growing/larger datasets. Allow we did make many values 'required' throughout development it is much easier than creating a table when dealing with datasets for a project such as this. It also uses JavaScript which fit right in with the MEAN stack development. 


Functionality

How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?
Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.

JSON (JavaScript Object Notation) is derived from JavaScript but is strictly a data format used to store and exchange data that is easy for machines to generate and parse and well as easy for humans to read and write. JavaScript is a programming language used to build web applications, that executes logic and manipulation of DOM elements. JSON serves as a medium for data exchange and is used to bridge the frontend and backend in web development. The backend sends data to the frontend in JSON format by APIs. JSON is also used to send data from the frontend to the backend for operations GET, PUT, POST, DELETE (or CRUD). This works well with the MongoDB database that uses BSON which is very compatible with JSON. The beginning for the project started with a static HTML and was then refactored to used handlebars and static JSON data. This saved a lot of coding time as instead of using several lines of code we could save the header and footer and use handlebars to insert this information where ever we needed to. We also used trip tags before and after the HTML block then manipulated the HTML. The benefits that come from reusable user interface (UI) components are faster code maniputation, less errors, less cluttered code, and quicker debugging. 

Testing

Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.



Reflection

How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?
