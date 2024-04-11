# PG Life - Full-Stack Web Application

PG Life is a comprehensive Full-Stack Web Application designed to simplify the process of finding paying guest accommodations (PGs). It provides users with a user-friendly interface to browse through a list of PGs and their main specifications, enabling them to conveniently select their preferred accommodation based on various criteria such as city, rent, and rating. Additionally, users can add selected PGs to their favorites list for easy reference.

# Technologies Used
- Frontend:

    - HTML
    - CSS
    - Bootstrap 5
    - JavaScript
- Backend:

    - PHP
- Database:

    - MySQL

# Features
1. **Browse PG Listings:**

Users can view a comprehensive list of PG accommodations along with their main specifications, such as location, facilities, rent, and rating.

2. **Search Functionality:**

Users can search for PGs based on specific criteria, either by selecting a city from the provided options or by using the search bar to find accommodations that match their preferences.

3. **Filtering Options:**

The application provides filtering options, allowing users to sort PGs according to rent and rating. This feature enables users to refine their search results based on their budget and preferences.

4. **Favorite List:**

Users can add selected PGs to their favorite list, making it easier to keep track of preferred accommodations. This feature enhances user experience by providing a convenient way to manage and revisit preferred options.

5. **Authentication and Authorization:**

Certain features, such as accessing the dashboard and managing favorites, are available only to logged-in users. This ensures that users can access personalized functionalities securely.

6. **Guest Access:**

Users can browse the entire web page and view PG listings without the need to log in. This feature enhances accessibility and allows users to explore available accommodations without any barriers.

# Usage
1. **Browsing PG Listings:**

Users can simply visit the website and start browsing through the available PG listings without logging in.

2. **Search and Filter:**

To find specific PG accommodations, users can either select a city from the provided options or use the search bar to narrow down their options. Additionally, filtering options based on rent and rating are available to refine search results.

3. **Adding to Favorites:**

Upon finding preferred PG accommodations, users can add them to their favorites list for easy reference. This can be done by clicking on the respective option provided alongside each listing.

4. **Authentication (Optional):**

Users who wish to access additional features, such as managing favorites and accessing the dashboard, can create an account and log in to the application.

# Prerequisites
- Web server software (e.g., Apache)
- Database server (e.g., MySQL)
- PHP (>=7.0)
- XAMPP or similar software for local development (optional but recommended)

# Installation Steps
- Download the Project:

    - Download the PG Life project files from the provided source or repository.

- Setup Web Server:

    - If you're using XAMPP, move the project folder to the htdocs directory (or equivalent) of your XAMPP installation.

- Database Setup:

    - Open phpMyAdmin or any MySQL client tool.
    - Create a new database for the project (e.g., pg_life_db).
    - Import the provided SQL file (pg_life_database.sql) into the newly created database. This file contains the necessary table structures and sample data.

- Configure Database Connection:

    - Navigate to the project directory and locate the config.php file.
    - Open the config.php file and update the database connection parameters (hostname, username, password, database name) to match your local database configuration.

- Start Web Server and Database:

    - If you're using XAMPP, start Apache and MySQL services from the XAMPP control panel.

- Access the Application:

    - Open your web browser and navigate to the URL where the project is hosted (e.g., http://localhost/pg-life).
    - You should now be able to access the PG Life application.

# Note
- This application is designed to simplify the process of finding PG accommodations and enhance user experience through intuitive browsing, searching, and filtering functionalities.

- Users can explore the entire web page and access basic features without the need to log in. However, creating an account and logging in enables access to personalized features and enhances usability.

- The application prioritizes simplicity, usability, and convenience to provide users with a seamless experience in finding and selecting PG accommodations.
