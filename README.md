Password Generator


![passwordGenerator](https://github.com/user-attachments/assets/2e937bfc-a550-405b-8d2e-aff1f608fcf2)

A React-based application that dynamically generates secure passwords with adjustable length, inclusion of numbers, special characters, and clipboard copying functionality.

Features

- Adjustable Password Length: Users can select a password length between 8 and 20 characters.
  
- Optional Number Inclusion: Users can choose to include numbers in the generated password.
  
- Optional Special Character Inclusion: Users can choose to include special characters such as `!@#$%^&*()+=|/?><{}[]` in the generated password.
  
- Clipboard Copy Functionality: Users can copy the generated password directly to their clipboard with a single click.
  
- Responsive UI: Designed with Tailwind CSS to ensure the interface looks good on all screen sizes.

Tech Stack

- React: The main framework used for building the application UI.
  
- useState: To manage password length, inclusion of numbers, special characters, and the generated password.

- useCallback: To optimize the performance of the password generation function and the clipboard copy function.

- useRef: For handling the clipboard copying of the generated password.

- useEffect: To trigger password generation when inputs (like length or allowed characters) change.


Installation and Setup

Prerequisites

    Node.js and npm should be installed on your system.

Steps

Clone the repository:

    git clone https://github.com/tasnifrahman/Password_Generator.git

Navigate to the project directory:

    cd password-generator

Install dependencies:

    npm install

Run the development server:

    npm run dev

    Open http://localhost:5137 in your browser to view the application.

Usage

-Password Length: Adjust the slider to set the desired length of the password (from 6 to 20 characters).

-Include Numbers: Toggle the checkbox to include/exclude numbers (0-9) in the password.

-Include Special Characters: Toggle the checkbox to include/exclude special characters (!@#$%^&*()+=|/?><{}[]) in the password.
    
-Copy Password: Click the "Copy" button to copy the generated password to your clipboard.
