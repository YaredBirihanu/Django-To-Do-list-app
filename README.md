<h1 align="center">Hi 👋, I'm Yared Berhanu</h1>
<h3 align="center">A passionate backend developer from Ethiopia</h3>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=yaredbirihanu&label=Profile%20views&color=0e75b6&style=flat" alt="yaredbirihanu" /> </p>

<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=yaredbirihanu" alt="yaredbirihanu" /></a> </p>

- 🔭 I’m currently working on **Task management system**

- 🌱 I’m currently learning **python and django**

- 👨‍💻 All of my projects are available at [https://github.com/YaredBirihanu/portfolio-livestream](https://github.com/YaredBirihanu/portfolio-livestream)

- 💬 Ask me about **python , django**

- 📫 How to reach me **yaredbeby08@gmail.com**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://fb.com/https://web.facebook.com/glasnost.anoriniper" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="https://web.facebook.com/glasnost.anoriniper" height="30" width="40" /></a>
<a href="https://www.leetcode.com/https://leetcode.com/yared" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/leet-code.svg" alt="https://leetcode.com/yared" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.djangoproject.com/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/django.svg" alt="django" width="40" height="40"/> </a> <a href="https://expressjs.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="express" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> </a> <a href="https://postman.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://www.sqlite.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/sqlite/sqlite-icon.svg" alt="sqlite" width="40" height="40"/> </a> </p>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=yaredbirihanu&show_icons=true&locale=en&layout=compact" alt="yaredbirihanu" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=yaredbirihanu&show_icons=true&locale=en" alt="yaredbirihanu" /></p>

---

# Task Management Application

This is a Django-based web application designed to help users manage their tasks efficiently. It includes features like user authentication, task creation, updating, deletion, and reordering. Below is a detailed explanation of the project's functionality.

---

## Features

### 1. **User Authentication**
   - **Login**: Users can log in using the `CustomLoginView`, which redirects authenticated users to the task list page.
   - **Registration**: New users can register using the `RegisterPage` view, which automatically logs them in after successful registration.

### 2. **Task Management**
   - **Task List**: Authenticated users can view their tasks on the `TaskList` page. Tasks are filtered by the logged-in user, and incomplete tasks are counted.
   - **Task Search**: Users can search for tasks by title using the search bar.
   - **Task Detail**: Users can view the details of a specific task using the `TaskDetail` view.
   - **Task Creation**: Users can create new tasks using the `TaskCreate` view. Tasks are automatically associated with the logged-in user.
   - **Task Update**: Users can update existing tasks using the `TaskUpdate` view.
   - **Task Deletion**: Users can delete tasks using the `DeleteView`. Only tasks owned by the logged-in user can be deleted.
   - **Task Reordering**: Users can reorder tasks using the `TaskReorder` view, which updates the task positions in the database.

---

## Code Overview

### Views

1. **CustomLoginView**
   - Handles user login.
   - Redirects authenticated users to the task list page (`tasks`).

2. **RegisterPage**
   - Handles user registration.
   - Automatically logs in users after successful registration.
   - Redirects authenticated users to the task list page.

3. **TaskList**
   - Displays a list of tasks for the logged-in user.
   - Filters tasks by the logged-in user and counts incomplete tasks.
   - Implements a search functionality to filter tasks by title.

4. **TaskDetail**
   - Displays detailed information about a specific task.

5. **TaskCreate**
   - Allows users to create new tasks.
   - Automatically associates the task with the logged-in user.

6. **TaskUpdate**
   - Allows users to update existing tasks.

7. **DeleteView**
   - Allows users to delete tasks.
   - Ensures that only tasks owned by the logged-in user can be deleted.

8. **TaskReorder**
   - Handles task reordering.
   - Updates the task positions in the database based on user input.

---

## Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/your-repository.git
   cd your-repository
   ```

2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run Migrations**
   ```bash
   python manage.py migrate
   ```

4. **Create a Superuser (Optional)**
   ```bash
   python manage.py createsuperuser
   ```

5. **Run the Server**
   ```bash
   python manage.py runserver
   ```

6. **Access the Application**
   - Open your browser and go to `http://127.0.0.1:8000/`.
   - Register or log in to start managing your tasks.

---

## Technologies Used

- **Django**: A Python-based web framework for building the application.
- **Django Authentication**: Handles user authentication and authorization.
- **HTML/CSS**: For the front-end templates and styling.
- **MySQL**: Relational database for development

---

## Contributing

Contributions are welcome! If you'd like to contribute, please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes.
4. Submit a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact

For any questions or feedback, please reach out to [yaredbeby08@gmail.com](mailto:yaredbeby08@gmail.com).

---

<img width="960" alt="s4" src="https://github.com/user-attachments/assets/7daf51bf-1d0a-4af5-92a3-498a01e0c9e1" />
<img width="950" alt="s3" src="https://github.com/user-attachments/assets/0167e0ef-a0cf-47f0-8178-690524892b44" />
<img width="960" alt="s2" src="https://github.com/user-attachments/assets/e34e9832-00f7-4a95-a6d4-5a21669eda95" />
<img width="959" alt="s1" src="https://github.com/user-attachments/assets/bb209457-4ba6-4292-a98b-cb1b74b0c733" />
