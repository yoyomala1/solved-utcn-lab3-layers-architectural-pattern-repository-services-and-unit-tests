Download Link: https://assignmentchef.com/product/solved-utcn-lab3-layers-architectural-pattern-repository-services-and-unit-tests
<br>
The objective of this assignment is to allow students to become familiar with layers architectural pattern, repository, services and unit tests.

2. Application Description

Use JAVA/C# Desktop to design and implement a ticket selling system or the Untold festival. The application should have two types of users (a cashier and an administrator) which must provide a username and a password to use the application.

The administrator user can perform the following operations:

<ul>

 <li>CRUD(Create, Retrieve, Update and Delete) on cashiers’ information.</li>

 <li>CRUD on the performances at UNTOLD (Tiesto/ Armin/ Martin Garrix/ …). Keep track of the Genre (Techno, Pop, Rap), Title (One last night in Berlin), Date and time of the show (2021 – 08 – 03 1am) and the Maximum Number of tickets per show (20000).</li>

 <li>Administrators can export all the tickets that were sold for a certain show (either in a csv or json file).</li>

</ul>

The cashier can perform the following operations:

<ul>

 <li>Sell tickets to a show. A ticket contains the show and can contain one or more places (I can buy a ticket for me and my brother).</li>

 <li>The system should notify the cashier when the number of tickets per show was exceeded.</li>

 <li>A cashier can see all the tickets that were sold for a show, cancel a reservation, or edit it.</li>

</ul>




<h2>3. Application Constraints</h2>

<ul>

 <li>The data will be stored in a relational database.</li>

 <li>Use the Layers architectural pattern to organize your application.</li>

 <li>Passwords are encrypted when stored to the database with a one-way encryption algorithm (base 64).</li>

 <li>Provide unit tests for the number of tickets for show exceeded validation and the encryption algorithm.</li>

 <li>Your application should prove the use of validations (for example if the number of places in the sell ticket screen is bellow 1).</li>

 <li>Use <strong>factory method (not factory)</strong> for export to csv/xml.</li>

</ul>

<h2>4. Requirements</h2>

<ul>

 <li>Create the analysis and design document (see the template).</li>

 <li>Implement and test the application.</li>

</ul>

<strong> </strong>

<strong> </strong>