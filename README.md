# **Grocery Web Application**

The Grocery Web Application is an online platform designed to make grocery shopping easier for users. It allows users to browse products, add them to their cart, and checkout seamlessly. The application also includes a meal planning feature where users can discover meal ideas based on the products they are interested in.

## 📋 **Features**

    **Meal Planning**: Users can select a product (e.g., chicken) and the system will provide meal suggestions for it in the meal planning page.
    **User and Employee Sides**: Separate interfaces for users and employees with distinct functionalities.
    **Account Creation**: Users can create an account, upload a profile picture, and manage their personal information.
   ** Homepage Management**: Users can add products to their homepage for easy access and re-purchase in the future.
    **Purchase History**: Users can view their past purchases for easy reordering.

## 💡 **What I Learned**

* **Full Stack Development**: Gained experience in both frontend and backend web development.
* **React**: Learned how to build and manage dynamic user interfaces with React.
* **Flask**: Integrated Flask to handle backend operations and serve API endpoints.
* **Database Integration & Management**: Managed data in the SQLite database using queries to store, retrieve, and update product and user information.
* **Debugging**: Improved debugging skills through console log troubleshooting.
* **Team Collaboration**: Worked effectively within a small team, meeting tight project deadlines.
* **Frontend Design**: Gained hands-on experience designing intuitive and responsive web pages.
* **Database Design**: Created database tables using Flask and interacted with them through API calls.
* **Routing with React**: Learned how to properly route between different pages and components in React.

## 🛠️ **Technologies Used**

* **Frontend**: React, JavaScript, HTML, CSS
* **Backend**: Flask (Python), SQLite (Database)
* **Development Tools**: Postman (for API testing), Git (version control)

## **How to run**

The website isn't deployed, but if you're interested in running it here are the steps below:

### **Installation**

1. **Clone the repository**:
```
git clone https://github.com/repo-name.git
```
2. **Install Dependencies**:

* Install gh-pages:
```
npm install gh-pages --save-dev
```
* Install axios:
```
    npm install axios
```
3. **Move to the Backend Directory**:
```
cd backend
```
4. **Run the Database**:
```
python main.py
```
5. **Start the Application**:

* Open a different terminal, navigate to the main application directory, and run:
```
npm start
```
By following these steps, you have successfully pulled the files, run the database, and started the application.

### **Additional Development Commands**

Here are some additional commands we used during the development process:

**Install pip**:
```
python get-pip.py
```
**Install pipenv**:
```
pip install pipenv
```
OR
```
py -m pip install pipenv
```
**Set up the virtual environment**:
```
pipenv shell
```
**Install dependencies**:
```
pip install python_decouple flask flask_restx flask_sqlalchemy flask_jwt_extended flask_migrate
```
**Manage dependencies**:
```
pip freeze > requirements.txt
```
**Set up Flask app**:
```
$env:FLASK_APP = 'main.py'
```
**Initialize the migration repository**:
```
flask db init
```
**Initialize the database**:
```
flask shell
```
**Inside the Flask shell, run**:
```
db.create_all()
```
**Create a migration**:
```
flask db migrate -m "message"
```
**Apply the migration**:
```
flask db upgrade
```
**Start the Flask server**:
```
python main.py
```
**Initialize the webpage**:
```
npm start
```
