# Easy-Med

Easy-Med is a comprehensive healthcare platform designed to facilitate organ donation, transplantation, and door-to-door medical services. Our mission is to simplify healthcare access, ensuring patients receive timely and efficient care.

## Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Application](#running-the-application)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## About the Project

Easy-Med connects donors and recipients with top medical professionals to streamline organ donation and transplantation processes. Additionally, it offers doorstep healthcare services, providing medical consultations, diagnostics, and treatments in the comfort of patients' homes.

## Features

- **Organ Donation and Transplantation:** 
  - Register as a donor or recipient.
  - Manage donor and recipient profiles.
  - Schedule and track transplantation procedures.

- **Door-to-Door Medical Services:** 
  - Book home medical consultations.
  - Access diagnostic and treatment services at home.
  - Maintain personal health records.

- **User Authentication:** 
  - Secure login and registration for patients and doctors.
  - Role-based access control.

## Technologies Used

- **Frontend:** 
  - HTML5
  - CSS3
  - JavaScript

- **Backend:** 
  - PHP
  - MySQL

## Getting Started

To set up the project locally, follow these steps:

### Prerequisites

- Web server (e.g., Apache)
- PHP (version 7.0 or higher)
- MySQL database

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/risavjhagithubrit/Easy-Med.git
   cd Easy-Med
   ```

2. **Set up the database:**

   - Create a MySQL database named `easymed`.
   - Import the provided SQL file to set up the necessary tables:

     ```bash
     mysql -u your_username -p easymed < path_to_sql_file.sql
     ```

3. **Configure the database connection:**

   - Open `connection.php` located in the root directory.
   - Update the database credentials:

     ```php
     $servername = "localhost";
     $username = "your_username";
     $password = "your_password";
     $dbname = "easymed";
     ```

### Running the Application

1. **Start the web server:**

   Ensure your web server is running and has access to the Easy-Med project directory.

2. **Access the application:**

   Open your web browser and navigate to `http://localhost/Easy-Med/index.html` to start using the application.

## Project Structure

```bash
Easy-Med/
├── admin/
├── css/
├── doctor/
├── img/
├── js/
├── lib/
├── patient/
├── scss/
├── about.html
├── appointment.html
├── connection.php
├── contact.html
├── create-account.php
├── index.html
├── login.php
├── logout.php
├── service.html
├── signup.php
├── team.html
└── README.md
```

- **`admin/`**: Contains administrative dashboard files.
- **`css/`**: Stylesheets for the application.
- **`doctor/`**: Doctor-specific functionalities and pages.
- **`img/`**: Images used in the application.
- **`js/`**: JavaScript files for interactive features.
- **`lib/`**: External libraries.
- **`patient/`**: Patient-specific functionalities and pages.
- **`scss/`**: Sass files for styling.

## Contributing

We welcome contributions to enhance Easy-Med. To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add YourFeature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a Pull Request.

## License

This project is licensed under the MIT License.

## Contact

For inquiries or feedback, please contact [risavjhagithubrit](https://github.com/risavjhagithubrit).

```

Feel free to customize this README to better fit your project's specifics. 
