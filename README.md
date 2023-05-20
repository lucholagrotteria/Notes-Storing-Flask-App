<h1>Notes Storing Flask App</h1>

This project is a Flask-based web application for taking notes. It allows registered users to create and manage their notes.
I used the basic SHA256 algorithm, it would be better if you use a different one if you decide to scale the app and launch it, like BCrypt. 

<h2>Project Structure</h2>
The project consists of the following files and folders:

<ul>
  <li>main.py: The main file of the project. It creates and runs the Flask application.</li>
  <li>__init__.py: The Flask application initialization file. It configures the database and registers views and routes.</li>
  <li>auth.py: Contains routes and logic related to user authentication (registration, login, logout).</li>
  <li>models.py: Defines the database data models using SQLAlchemy. It includes user and note models.</li>
  <li>views.py: Contains views and routes for the user interface, including the home page and note deletion.</li>
  <li>database.db: SQLite database file.</li>
</ul>
<h2>System Requirements</h2>
<ul>
  <li>Python 3.x</li>
  <li>Flask</li>
  <li>Flask SQLAlchemy</li>
  <li>Flask Login</li>
</ul>
<h2>Installation and Setup</h2>
<ol>
  <li>Clone the repository or download the files to your local machine.</li>
  <li>Create a virtual environment for the project.</li>
  <li>Activate the virtual environment.</li>
  <li>Install project dependencies by running the following command:</li>
  
  `pip install -r requirements.txt`

  <li>Set the application secret key in the __init__.py file. Replace 'asdadsahdhgwgqqe ahrwgqefe' with your own secret key.</li>
  <li>Start the application by running the following command:</li>

    `python main.py`
  
  <li>Open your web browser and access http://localhost:5000 to see the application in action.</li>
</ol>
<h2>Usage</h2>
<ul>
  <li>Sign up or log in to the application using the respective option.</li>
  <li>Once authenticated, you will be able to access the home page where you can view your existing notes and add new notes.</li>
  <li>To delete a note, simply click the "Delete" button next to the corresponding note.</li>
</ul>
