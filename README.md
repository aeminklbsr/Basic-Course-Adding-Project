# Basic Course Adding Project

## About the Project

This project is a simple course adding system designed for universities or other educational institutions. It allows users to add, update, and delete courses. Additionally, it provides a list of all available courses. The goal of this project is to streamline the course management process for educational institutions.

## Features

- **Add Courses**: Users can add new courses.
- **Update Courses**: Users can make changes to existing courses.
- **Delete Courses**: Users can remove unwanted courses from the system.
- **List Courses**: Users can view a list of all available courses.

## Technologies Used

- **Backend**:
  - **Python** and **Flask**: Used for creating the backend server and handling API requests.
- **Frontend**:
  - **HTML**, **CSS**, and **JavaScript**: Used for building the user interface.
  - **Bootstrap**: Used for responsive design and styling.
- **Database**:
  - **SQLite**: Used for storing course information.

## Getting Started

### Prerequisites

- Python 3.x
- Flask
- SQLite

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/aeminklbsr/Basic-Course-Adding-Project.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Basic-Course-Adding-Project
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

### Running the Application

1. Initialize the database:
    ```bash
    flask db init
    flask db migrate
    flask db upgrade
    ```
2. Start the Flask server:
    ```bash
    flask run
    ```
3. Open your web browser and go to `http://127.0.0.1:5000` to view the application.

## Usage

- To add a course, navigate to the "Add Course" page and fill out the form.
- To update a course, go to the course list, select a course, and click the "Edit" button.
- To delete a course, go to the course list, select a course, and click the "Delete" button.
- To view all courses, navigate to the "Course List" page.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request to propose changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact

- **Name**: Ahmet Emin KOLBASAR
- **GitHub**: [aeminklbsr](https://github.com/aeminklbsr)

---
