<h1 align="center">
             ManageIt 👩🗒️👨
</h1>

![image](https://user-images.githubusercontent.com/78029145/179185741-5f1030a2-7667-4f5e-b70a-1064bd0a290d.png)

## Overview of the App

<table>
<tr>
<td>
This application can be used by any user to store the personal employee details of the employees in the workplace including - name, email, department, all update/delete and filter the details later as per requirements. The admins can also group employee related to workplace and can also delete them later once they are done with them. 
</td>
</tr>
</table>

There are 4 different sections in the app as follows:

1. <b>Employee Details Section</b> - This section contains a table to display the details of the employees stored which includes : Full Name , Salary , Bonus , Phone Number ,Role , Department , Location , HireDate.

2. <b>Add Employee Section</b> - This section contains a table where user adds the details of a new employee.

3. <b>Remove Employee Section</b> - In this section , user can delete the details of the employee from the list which is not required anymore.

4. <b>Filter Employee Section</b> - This section is the filtering section of employee so that we can get details of any employee when needed immediately.

## Tech Stack Used 

<img src="https://img.shields.io/badge/python%20-%2314354C.svg?&style=for-the-badge&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/html5%20-%2314354C.svg?&style=for-the-badge&logo=html5&logoColor=white"/> <img src="https://img.shields.io/badge/css3%20-%2314354C.svg?&style=for-the-badge&logo=css3&logoColor=white"/> <img src="https://img.shields.io/badge/javascript%20-%2314354C.svg?&style=for-the-badge&logo=javascript&logoColor=white"/> <img src="https://img.shields.io/badge/bootstrap%20-%2314354C.svg?&style=for-the-badge&logo=bootstrap&logoColor=white"/> <img src="https://img.shields.io/badge/mysql%20-%2314354C.svg?&style=for-the-badge&logo=mysql&logoColor=white"/> 

## Libraries Used 

* Django

* SQLite

## Structure Of The Project

* The home page of the application contains:
   1. <b>Landing Page</b> - Here users can get started with using our application
   2. <b>Link to Employee Section</b> - Add, Update, Delete employee details for any workplace

* A admin page which can be accessed by the administrative department of the office for the detailed information of the employees.
  
## UI Of The Web Application

### 1. Home Page
<pre>
<img src="https://user-images.githubusercontent.com/78029145/193518919-b446f813-6451-404b-bedf-8813e3aae51b.png" width="1000"> <img src="https://user-images.githubusercontent.com/78029145/193518944-c6b27421-db3f-4890-b261-e80992ac600b.png" width="1000">
</pre>


### 2. Employee Details Page
<pre>
  <img width="960" alt="image" src="https://github.com/Sanchariii/ManageIt/assets/88083502/07691b31-11f2-4aba-874d-59f274f4633c"><img width="960" alt="image" src="https://github.com/Sanchariii/ManageIt/assets/88083502/80c37af4-d098-4df0-bb52-6349c98b541b"><img width="960" alt="image" src="https://github.com/Sanchariii/ManageIt/assets/88083502/2fe5b34c-a9c8-459f-ba93-ccd9a8ac6e08"><img width="960" alt="image" src="https://github.com/Sanchariii/ManageIt/assets/88083502/0d14a7cd-f6e0-46b4-807f-527499c78f74">
</pre>

### 3. Admin Page
<pre>
  <img width="960" alt="image" src="https://github.com/Sanchariii/ManageIt/assets/88083502/6c55bdc3-6990-4b67-970e-2aa520ee7f66">
</pre>

## Future Prospects

- Add a Meeting Section to update about the upcoming or incomplete meetings in the workplace
- Add more dynamic layouts in the application

## Run Locally

1. Clone the project
  ```bash
    git clone https://github.com/Sanchariii/ManageIt.git
  ```

2. Go to the project directory
  ```bash
    cd ManageIt
  ```

3. Install dependencies
  ```bash
    pip install -r requirements.txt
  ```

4. Start the server
  ```bash
    python manage.py runserver
  ```

5. Create a superuser
  ```bash
    python manage.py createsuperuser
  ```

6. Run the application on your local server
  ```bash
    python manage.py runserver
  ```

## Contributing
 
 Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

* Fork the repository.

* Create a new branch (`git checkout -b feature/your_feature_name`).

* Make your changes.

* Commit your changes (`git commit -am 'Add new feature'`).

* Push to the branch (`git push origin feature/your_feature_name`).

* Create a new Pull Request.

## License

This project is licensed under the [DBaJ-NC-CFL](./LICENCE.md).

