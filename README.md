**AI-Driven Wellness Advisor**

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

**SQL**

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

**AI_Driven_Wellness_Advisor/

│
├── main.py                   # Flask application entry point

├── requirements.txt          # Python dependencies

├── .env                      # Environment variables for sensitive data (e.g., API keys)

├── static/                   # Static files like images, CSS, and JS

│   ├── css/                  # Stylesheets

│   ├── js/                   # JavaScript files

│   └── images/               # Image assets
│
├── templates/                # HTML templates for Flask

│   ├── index.html            # Home page template

│   ├── login.html            # Login page template

│   └── other_templates.html  # Additional templates

│
├── frontend/                 # Frontend code (Vue.js)

│   ├── src/                  # Vue.js source code

│   │   ├── components/       # Vue components

│   │   ├── views/            # Vue views (pages)

│   │   └── App.vue           # Main Vue component

│   ├── public/               # Public assets (e.g., index.html)

│   └── package.json          # Frontend dependencies and scripts

│
├── models/                   # Machine learning models

│   ├── svc_model.pkl         # Trained SVC model for disease prediction

│   └── other_models/         # Other models or preprocessing steps (if any)
│
├── database/                 # Database schema and migration files

│   └── schema.sql            # SQL schema to set up the database
│
├── tests/                    # Test cases for Flask routes and machine learning model

│   ├── test_routes.py        # Tests for the Flask routes

│   └── test_model.py         # Tests for the machine learning model
│
└── LICENSE                   # License file**


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


**About Us**

Welcome to the Medical Health Center, where health meets technology for a brighter, healthier future.

**Our Vision**

We envision a world where access to healthcare information is not just a luxury but a fundamental right. Our journey began with a simple yet powerful idea: to empower individuals with the knowledge and tools they need to take control of their health.

**Who We Are**

We are a passionate team of healthcare professionals, data scientists, and technology enthusiasts who share a common goal: to make healthcare accessible, understandable, and personalized for you. With years of experience in both healthcare and cutting-edge technology, we've come together to create this platform as a testament to our commitment to your well-being.

**Our Mission**

At this website, our mission is to provide you with a seamless and intuitive platform that leverages the power of artificial intelligence and machine learning. We want to assist you in identifying potential health concerns based on your reported symptoms, all while offering a wealth of educational resources to enhance your health literacy.

**How We Do It**

Our platform utilizes a robust machine learning model trained on a vast dataset of symptoms and diseases. By inputting your symptoms, our system generates accurate predictions about potential illnesses, allowing you to make informed decisions about your health.

**Your Well-being, Our Priority**

Your health is our top priority. We understand that navigating the complexities of healthcare can be daunting. That's why we've gone the extra mile to provide not only accurate predictions but also comprehensive information about each disease. You'll find descriptions, recommended precautions, medications, dietary advice, and workout tips to support your journey to better health.

**Join Us on This Journey**

We invite you to explore our platform, engage with our educational content, and take control of your health journey. Together, we can revolutionize the way individuals access and understand healthcare information.

Thank you for choosing **AI-Driven Wellness Advisor** as your trusted health companion. We are here to empower you with knowledge, support, and a brighter, healthier future.


**Contact Us**

Have questions or need assistance? We're here to help!

Customer Support
Our dedicated customer support team is available to assist you with any inquiries or issues you may have. Whether it's a technical question, feedback, or a general inquiry, we're just a message away.

Get in Touch
Feel free to reach out to us via email or through the contact form below. We value your feedback and are committed to providing you with the best possible experience.
Email: karupatinikesh@gmail.com
Phone: +916302213707

Stay Connected
Stay up-to-date with the latest news, updates, and health tips by following us on social media. Connect with us on Facebook or Instagram to join our growing community.

Location
KNM Deva, Andhra Pradesh, India
