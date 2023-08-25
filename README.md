# BiteBuddy: XYZ Cafe Food Delivery Chatbot

Welcome to the repository for the XYZ Cafe Food Delivery website and its integrated chatbot. This project brings together a user-friendly food ordering platform and an AI-powered chatbot to enhance the customer experience and streamline the ordering process. The repository is organized into three main folders: frontend, backend, and db.

# Features
Place orders: Users can easily add items to their cart and place orders using the chatbot.
Track orders: Users can track their orders using the order ID.
Interactive chatbot: The integrated chatbot is powered by Google Dialogflow, providing real-time assistance to users with their orders and inquiries.

# Folder Structure
1. frontend: This folder contains all the HTML and CSS files that constitute the user interface of the website. It also includes relevant photos and graphics used on the website.
2. backend: The backend folder holds the Python FastAPI code that powers the server-side logic of the website. This includes handling orders, communicating with the chatbot, and managing user interactions.
3. db: This folder contains a dump of the database used for the project. To set up the required database, you can import this dump into your MySQL database using tools like MySQL Workbench.

# Getting Started
To get the XYZ Cafe Food Delivery Website and Chatbot up and running locally, follow these steps:

1. Clone the repository to your local machine:
   ```git clone https://github.com/harshpare12/BiteBuddy.git```

2. Set up the Database: Import the database dump file located in the db folder into your MySQL database using a tool like MySQL Workbench.
3. Configure the Backend: Navigate to the backend directory: cd backend.
4. Install the required Python packages: pip install "fastapi[all]", pip install mysql-connector
5. Set Up Dialogflow Chatbot: Obtain the necessary API credentials and integrate them into the backend code for chatbot communication.
6. Launch the Application:
   Start the FastAPI server: ```uvicorn main:app --reload```
   Access the website by opening a web browser and navigating to 'http://localhost:8000'
