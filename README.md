### Assignment - Full Stack Developer

#### Skills Required to complete this assignment
- NodeJS
- Angular
- MySQL
- Docker
- TDD
- SASS

#### Purpose of this assignment is to assess the ability of the Developer to
- develop Front End using Angular
- develop Backend using NodeJS
- quickly learn and use different frameworks.
- measure the speed at which the user can quickly change the application to meet the requirements
- write test cases


#### Backend - ( Node JS )
Use the below framework to develop API interface
- https://medium.com/@phcollignon/node-rest-api-jwt-in-typescript-e6a8ae5cd8f8

Replace MongoDB with MySQL - use connection pooling.
Run MySQL instance in Docker
- https://dev.mysql.com/doc/mysql-installation-excerpt/5.5/en/docker-mysql-getting-started.html

Write a SQL file to create table structure ( as defined in the above API )
- https://github.com/Philippe-Collignon/rest-api-node-jwt-typescript/tree/master/src/models

Write Test cases for API ( any framework is fine - eg framework is given below )
- Ref: https://scotch.io/tutorials/test-a-node-restful-api-with-mocha-and-chai

#### Frontend - ( Angular ) 
https://dev.to/ronakpatel70/creating-pwa-using-angular-7-step-by-step-guide-1mb3

Nav Bar will contain the following
- Home   ( Public Access - Defualt Landing Page )
- Login ( Shown only if the user is NOT logged in )
- Products ( Shown only if the user is logged in ) 
- Logout ( Shown only if the user is logged in )

Home Page (  layout something like ) https://www.codeproject.com/KB/scripting/1248738/product-list-1.png
  - Ignore Search Products in the above Screen Layout
  - List of Products from backend and display it in a table
  - ( If logged in ) Clicking on the Product will show a screen to update the product using JSON Schema Form 
  - ( If logged in ) Clicking on Add Product functionality again use JSON Schema Form to capture product information and will make an API call to save the product.
  - ( If logged in ) allow multiple product selection to delete.

Login will contain 2 Tabs ( eg. https://bootsnipp.com/snippets/M0a ) 
- use JSON Schema Form ( https://www.npmjs.com/package/angular6-json-schema-form ) to render UI

Login & Register will have 2 fields user name & password
- Successful registration will also login the user and redirect to the home page

Logout will logout the user and will return to the Home Page.

Write test cases for Home page - when logged in and when not logged in.

#### Deliverables
- Upload all codes in Github and share the link.
- One Repository for Backend and one for Frontend
- Create Installation Instructions ( assume Angular, Node JS are installed )
- Provide steps to run the test cases ( API & UI )

#### Duration
- 7 days to complete.

