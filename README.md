
<H1>C# Appointment Application</H1>

<H2>Instructions to run on local computer</H2>
<h3>Step 1.Create a mySQL database under the name "Client Schedule", with username being "sqlUser" and password as "Passw0rd!".</h3>
<h3>Step 2.Run SQL_SCHEMA_CREATION file in mysql</h3>
<H3>Step 3.Download zip file and open in Visual Studio</H3>
<H3>Step 4. Download packages for dependencies </H3>
<h4>MySql.Data by Oracle</h4>
<h4>MySql.Data.MySqlClient .Net Core Class Library</h4>
<h4>NuGet.Common</h4>
<h4>NuGet.Configuration</h4>
<h4>NuGet.Frameworks</h4>
<h4>NuGet.Packaging</h4>
<h4>NuGet.Versioning by Microsoft</h4>
<H3>Step 5.Run program on local computer</H3>
<H2>Project Technologies</H2>
<h3>.NET Frameworks</h3>
<h3>Mysql</h3>


<H2>Project Requirements</H2>
A.   Create an application by completing the following tasks in C#:

1.   Create a login form that has the ability to do the following:

a.   Determine a user’s location.

b.   Translate login and error control messages (e.g., “The username and password do not match.”) into English and one additional language.

c.   Verify the correct username and password.

2.   Provide the ability to add, update, and delete customer records.

a.   Validate each of the following requirements for customer records:

•    that a customer record includes name, address, and phone number fields

•    that fields are trimmed and non-empty

•    that the phone number field allows only digits and dashes

b.   Add exception handling that can be used when performing each of the following operations for customer records:

•    “add” operations

•    “update” operations

•    “delete database” operations

3.   Provide the ability to add, update, and delete appointments, capture the type of appointment, and link to a specific customer record in the database.

a.   Validate each of the following requirements for appointments:

•    Require appointments to be scheduled during the business hours of 9:00 a.m. to 5:00 p.m., Monday–Friday, eastern standard time.

•    Prevent the scheduling of overlapping appointments.

b.   Add exception handling that can be used when performing each of the following operations for appointments:

•    “add” operations

•    “update” operations

•    “delete database” operations

4.   Create a calendar view feature, including the ability to view appointments on a specific day by selecting a day of the month from a calendar of the months of the year.

5.   Provide the ability to automatically adjust appointment times based on user time zones and daylight saving time.

6.   Create a function that generates an alert whenever a user who has an appointment within 15 minutes logs in to their account.

7.   Create a function that allows users to generate the three reports listed using collection classes, incorporating a lambda expression into the code for each of the following reports:

•    the number of appointment types by month

•    the schedule for each user

•    one additional report of your choice

8.   Record the timestamp and the username of each login in a text file named “Login_History.txt,” ensuring that each new record is appended to the log file.
