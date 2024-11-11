**Project Overview**
The AI-Driven Wellness Advisor is an AI-powered healthcare web application that predicts potential diseases based on user-input symptoms. By leveraging a Support Vector Classifier (SVC) model, this web application provides real-time health predictions and wellness advice. The application is built using Flask and integrates machine learning for seamless interaction.

**Features**
Real-time disease prediction based on symptoms.
Machine learning integration with a Support Vector Classifier (SVC) model.
User-friendly interface for input and result visualization.
Built with Flask for backend, Vue.js for frontend, and MySQL for database storage.

**Requirements**
Python 3.x
Flask
scikit-learn
MySQL
Vue.js (for frontend)
Node.js (for frontend dependencies)
Google OAuth for authentication (if applicable)

**Installation
Follow these steps to set up the project locally:**

1. Clone the Repository
Open a terminal/command prompt and run the following command to clone the repository:

bash
Copy code
git clone https://github.com/KNikhesh/AI_Driven_Wellness_Advisor.git
2. Navigate to the Project Directory
Change into the project directory:

bash
Copy code
cd AI_Driven_Wellness_Advisor
3. Set Up the Virtual Environment
Create a virtual environment to manage the dependencies:

bash
Copy code
python -m venv venv
Activate the virtual environment:

**On Windows:**
bash
Copy code
venv\Scripts\activate
On macOS/Linux:
bash
Copy code
source venv/bin/activate
4. Install Dependencies
Install the required Python packages:

bash
Copy code
pip install -r requirements.txt
This will install all the necessary Python dependencies, including Flask, scikit-learn, and others.

5. Set Up Database
Ensure you have MySQL installed. Create a database for the application:

**sql**
Copy code
CREATE DATABASE health_diagnosis;
Import the database schema and data (if you have a .sql file):

bash
Copy code
mysql -u root -p health_diagnosis < schema.sql
6. Set Up Environment Variables
Create a .env file in the root of the project and add the following environment variables for Google OAuth (if applicable):

makefile
Copy code
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
You can also set other necessary environment variables as needed.

7. Start the Application
Run the Flask application:

bash
Copy code
python main.py
8. Frontend Setup (Vue.js)
Navigate to the frontend/ directory and install the dependencies:

bash
Copy code
cd frontend
npm install
Then, start the Vue.js development server:

bash
Copy code
npm run serve
Your application should now be running locally. You can access it by visiting http://localhost:5000 for the Flask backend and http://localhost:8080 for the frontend.

**Usage**
Once the application is running:

Navigate to the web application on your browser.
Input the symptoms as prompted.
Get real-time disease prediction and wellness advice based on the provided symptoms.
Contributing
Feel free to fork this repository and make improvements. Here are some ways you can contribute:

Report bugs.
Suggest features or enhancements.
Improve documentation.
To contribute, fork the repository, create a feature branch, make changes, and submit a pull request.
