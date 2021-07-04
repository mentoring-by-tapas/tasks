# Subject
Create Dynamic User Interface with Data Handling

# User Stories
Here are the User Stories to accomplish

## 1. User List
- Create a JSON file called `users.json` with the data of three users. Each of the user can have details like name, age, and address.
- Create an HTML file with basic structure.
- Create a JavaScript file and add the script file reference to the JavaScript file.
- Now fetch the user data into the JavaScript file within a function.
- Read all the User data, create required DOM elememts and add the details to the HTML using the UI, LI tags.
- Add some basic styling to make the page look better.
- At the end the HTML page should list all the users from the JSON file.

Hints: Use JavaScript `fetch` API.

## 2. Movies List
Repeat the above example with the movies data. The movies array should have movie details like cover photo, title, director, and rating.

## 3. Movie List on Demand.
Update the movie example with the folowings,
- Added a button called `Load Movies`.
- Add a click handler to lead the movies data when user click on the button. The movie data should not be loaded by default.

## 4. Employee & Department
- Craete two JSON files, employee.json and department.json.
- The employee.json file should have an array of employees(say, 5 employees). each of the employee should have details like, id, name, dept_id, salary, date_of_birth, joining_date, isParmanent. Here is an example of an employee record,
```json
{
  "id": "E-001",
  "name": "Tapas Adhikary",
  "dept_id": "D-004",
  "salary": 34564840,
  "date_of_birth": 02-03-1982,
  "joining_date": 07-14-2007,
  "isParmanent": true
}
```
- Now the department.json should have array of departments. Each of the department should have a dept_id and dept_name.
- Make the data such a way that 2 employees belong to one department and other 2 belong to another department and the last employee belonng to the last department. So total 5 employees and 3 departments.
- Now in the HTML you should show the list of employees by fetching the data using JavaScript. When user click in the emplyee name, show the name of the department the employe belogs to.
