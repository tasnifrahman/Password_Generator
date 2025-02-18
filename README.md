Password Generator

A React-based application that dynamically generates secure passwords with adjustable length, inclusion of numbers, special characters, and clipboard copying functionality. The project is designed to be responsive, simple, and user-friendly.
Features

    Adjustable Password Length: Users can select a password length between 6 and 20 characters.
    Optional Number Inclusion: Users can choose to include numbers in the generated password.
    Optional Special Character Inclusion: Users can choose to include special characters such as !@#$%^&*()+=|/?><{}[] in the generated password.
    
    Clipboard Copy Functionality: Users can copy the generated password directly to their clipboard with a single click.
    
    Real-time Password Update: Password is generated and updated dynamically as user changes input preferences.
    Responsive UI: Designed with Tailwind CSS to ensure the interface looks good on all screen sizes.
    ![passwordGenerator](https://github.com/user-attachments/assets/7ae298be-fac8-46a6-b873-54f1f0f1f3c2)


Tech Stack

    React: The main framework used for building the application UI.
        Hooks:
            useState: To manage password length, inclusion of numbers, special characters, and the generated password.
            useCallback: To optimize the performance of the password generation function and the clipboard copy function.
            useRef: For handling the clipboard copying of the generated password.
            useEffect: To trigger password generation when inputs (like length or allowed characters) change.
    Tailwind CSS: For styling the application, providing a clean and responsive design.

Installation and Setup
Prerequisites

    Node.js and npm should be installed on your system. You can download them from here.

Steps

    Clone the repository:

git clone https://github.com/your-username/password-generator.git

Navigate to the project directory:

cd password-generator

Install dependencies:

npm install

Run the development server:

    npm start

    Open http://localhost:3000 in your browser to view the application.

Usage

    Password Length: Adjust the slider to set the desired length of the password (from 6 to 20 characters).
    Include Numbers: Toggle the checkbox to include/exclude numbers (0-9) in the password.
    Include Special Characters: Toggle the checkbox to include/exclude special characters (!@#$%^&*()+=|/?><{}[]) in the password.
    Copy Password: Click the "Copy" button to copy the generated password to your clipboard.
