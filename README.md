CodeCure


CodeCure is a web application developed using Flask, a web framework in Python that aims to assist patients in obtaining the necessary medical care for their needs. The system allows users to register as patients or doctors, book appointments, and predict diseases based on symptoms. Doctors can view and manage appointments, while patients can track their appointments and update their profiles. Additionally, the system provides information on various health-related topics through blog posts and also analyses mental health conditiion of patients.

Features
User Registration:

Patients and doctors can register using the system.
Patients provide basic information such as username, email, and password.
Doctors provide additional information, including their type of specialization.
User Login and Logout:

Users can log in to access personalized dashboards.
Sessions are managed to ensure secure access, and users can log out when done.
Appointment Booking:

Patients can book appointments with doctors.
Doctors can view and manage appointments assigned to them.
Disease Prediction:

A machine learning model predicts diseases based on user-input symptoms.
The system uses a Decision Tree Classifier trained on medical data.
Blog Section:

Information on various health-related topics is provided through blog posts.
Topics include Transforming Healthcare, Holistic Health, Nourishing Body, and Importance of Games.

Users can find information on different medical scans, such as  lung, and full body symptoms scans.
Project Structure
app.py: The main Flask application file containing routes and functionality.
templates: Contains HTML templates for rendering web pages.
static: Contains static files such as CSS, images, and data.
database.db: SQLite database file storing user and appointment information.
Data: Contains CSV files used for training and testing the disease prediction model.



Clone the repository: git clone https://github.com/VaibhavBajpaij/CodeCure-Healthcare-Website-GFGXNIET
Install dependencies: pip install -r requirements.txt
Run the application: python app.py

Dependencies
Flask
Flask-SQLAlchemy
Plotly
NumPy
TensorFlow
Scikit-learn![start](https://github.com/user-attachments/assets/2577274a-03fc-4372-9cef-1f981410e5b9)
![Screenshot 2024-09-14 170230](https://github.com/user-attachments/assets/5d257315-fd1e-4b77-958e-f97bddcb7cbd)
![Screenshot 2024-09-14 170214](https://github.com/user-attachments/assets/f887cb1d-c901-4b91-96f1-e7f96955b53b)
![Screenshot 2024-09-14 170153](https://github.com/user-attachments/assets/fe04b601-d05f-44a4-b2ec-5ba9250521a7)
![Screenshot 2024-09-14 170127](https://github.com/user-attachments/assets/2fb354af-581b-41c6-b948-20ec7c5d1c97)
![Screenshot 2024-09-14 170113](https://github.com/user-attachments/assets/2f43b485-bcef-434e-9285-ffe79b1791db)
![Screenshot 2024-09-14 170055](https://github.com/user-attachments/assets/151bd88f-6f06-4cb5-a0de-a26f3f612b3b)
![Screenshot 2024-09-14 170041](https://github.com/user-attachments/assets/6c414aa7-2c53-434a-ba0c-d35a33cb6c4b)
![Screenshot 2024-09-14 170022](https://github.com/user-attachments/assets/f2658771-ddc0-4d98-8779-5b1d82cabcc3)


