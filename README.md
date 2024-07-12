# ProfilePeek

ProfilePeek is a simple web application that allows users to enter their ID and retrieve their profile information such as name, email, phone number, address, and gender. This project uses PHP for backend processing and Bootstrap for styling.

## Features

-   User can input their ID to fetch profile information.
-   Displays user data or a "User Not Found" message if the ID is not recognized.
-   Responsive design with Bootstrap for a consistent and attractive UI.

## Getting Started

### Prerequisites

-   A web server with PHP support (e.g., Apache, Nginx).
-   Basic understanding of HTML, PHP, and Bootstrap.

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/emanebied/profilepeek.git
    ```
2. Navigate to the project directory
    ```sh
    cd profilepeek
    ```
3. Move the project files to your web server's root directory (e.g., /var/www/html for Apache).

## Screenshots:

### Home Page
![index](https://github.com/user-attachments/assets/ea918a22-a1a3-4258-9357-ffc40a90a97e)

### ProfilePeek 
![userInfo](https://github.com/user-attachments/assets/555f096b-6b16-4ab3-85ba-05bda2d68307)

## Usage

1. Open your web browser and navigate to the URL where the project is hosted (e.g., http://localhost/profilepeek).
2. Enter a valid ID (200108, 200109, 200110) to view the corresponding profile data.
3. If an unrecognized ID is entered, a "User Not Found" message will be displayed.

### Example IDs

-   200108: Eman Ebied
-   200109: Fatma Mohamed
-   200110: Mohamed Ali

### Code Structure

-   index.php: Main file containing HTML and PHP code to handle user input and display profile information.
-   bootstrap.min.css: Bootstrap CSS for styling the application.
-   jquery.slim.min.js, popper.min.js, bootstrap.min.js: JavaScript files for Bootstrap functionality.

## Contribution:

Contributions to my ProfilePeek application are most welcome! If you find any issues or have suggestions for improvements or want to add new features, please open an issue or submit a pull request.
