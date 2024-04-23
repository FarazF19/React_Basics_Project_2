
# Password Generator App

The Password Generator App is a simple React application that allows users to generate random passwords based on specified criteria such as length and character types.

## Description

This app utilizes React state management and hooks to dynamically generate passwords and provide a user-friendly interface for customizing password settings.

## Features

- **Password Length Slider**: Users can adjust the length of the generated password using a range slider. The length can be set between 6 and 100 characters.

- **Character Types**: Users can select whether to include numbers and special characters in the generated password by toggling checkboxes.

- **Copy to Clipboard**: Users can easily copy the generated password to the clipboard with the click of a button.

## How to Use

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Run `npm install` to install the dependencies.
4. Start the development server by running `npm start`.
5. Open your web browser and go to [http://localhost:3000](http://localhost:3000) to view the application.
6. Adjust the password length and select desired character types.
7. Click the "copy" button to copy the generated password to the clipboard.

## Technologies Used

- React
- useState hook
- useCallback hook
- useEffect hook
- useRef hook

## Code Structure

- `App.js`: The main React component responsible for rendering the application. It manages the state of password length, character types, and the generated password. It also provides the user interface for interacting with the password generator.

## Author

- Muhammad Faraz 
- Linkedin: https://www.linkedin.com/mfaraz7

## License

This project is licensed under the [MIT License](LICENSE).

