This project is a **Flask-based University Recommendation System** designed to help students discover suitable universities based on three key criteria:

* **SAT Score**
* **Annual Budget (Expenses)**
* **Preferred State**

The system loads data from a CSV file (`KMeans_University.csv`) containing information about various universities such as SAT requirements, expenses, state, and type. It uses this data to:

* Filter and display **eligible universities** based on SAT score.
* Further refine the list to show **recommended universities** based on budget and location.

The app features a clean web interface built using HTML (Jinja templates) and enables users to interact with the system via form input. Results are rendered dynamically based on user input.

### Technologies Used

* **Flask** – for building the backend server
* **Pandas** – for data processing
* **HTML/CSS (Jinja2 templates)** – for frontend rendering

### Features

* Simple form-based user interface
* Filters universities based on input
* Returns two tables: SAT-eligible and fully recommended universities
* Handles missing values gracefully

This project is ideal for students and educators exploring college options within academic and financial constraints.
