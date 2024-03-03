# Architecture

<b>Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).</b>

The site used Express, HTML, and JavaScript to display the pages.  Routes and controllers were created using Express and JavaScript to handle requests from the browser for a page.  Express then either retrieves the static HTML page or generates the requested page using handlebars templates and data populated from the database.  All of these tools work together to handle server requests and send that result to the front end.

The Angular part of the project worked different.  Upon the first load of the page, the entire single page application (SPA) gets sent to the end user.  Once it is there, all of the page rending and code execution takes place in the browser on the client side of things.

With Express, many calls get made to the server.  With a SPA, the initial load will take longer to get all the code from the backend but after that no additional calls are required for navigating pages within the SPA.

<b>Why did the backend use a NoSQL MongoDB database?</b>

MongoDB scales well and queries fast.  The documents that are stored in MongoDB align well with JSON format and that makes it a good match for front end applications.

# Functionality

<b>How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?</b>

JSON is a method for formatting Data.  It can be utilized with many programmming language.  JavaScript is a programming language that uses JSON to define its objects.  The front end and back end are connected through the use of JSON and APIs.  RESTful APS use JSON to field requests and send responses.

<b>Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.</b>

An example of improving functionality through refactoring code was when we replaced some static HTML pages with templates using Handlebars.  This enables the structure of a page to be reused while also being able to change the data displayed on said page.  A

# Testing

<b>Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.</b>

HTTP methods are a diferent type of way the client can interact with the server.  Some of the most utilized methods are GET, POST, PUT, and DELETE.  These API endpoints are what enables the client to communicate with the server without needing the kind of access we might have at the back end.  Authenticating the specific login credentials for the end user in this scenario allows us to give that hyper specific control over to the end user and giving them a valid JWT so that they can reach these endpoints that will only work with any relevant information regarding them.

# Reflection

<b>How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?</b>

This course has shown me something important!  It's shown me that I may want to pursue a career in full stack development.  While I struggled due to illness this term, I still very much enjoyed learning these things and hope to mvoe forward into Full Stack II to learn more and solve any pitfalls I had this term as well!  I've also learned far more about Javascript, Node, Express, Handlebars, and Postman which will come in great use going forward.
