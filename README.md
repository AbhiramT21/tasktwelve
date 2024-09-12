# Registration Form

This project is a simple registration form created using HTML, CSS, and JavaScript. The form collects user details and includes basic client-side validation. Upon successful submission, the user is redirected to a confirmation page.

## Project Structure

- `index.html` - The main registration form page.
- `submit.html` - The confirmation page shown after form submission.
- `style.css` - The CSS file that styles the registration form.
- `script.js` - The JavaScript file that contains form validation logic.

## Features

- **Form Fields**: Includes fields for First Name, Last Name, Email ID, Phone Number, Password, and Confirm Password.
- **Password Validation**: Ensures that the passwords match before form submission.
- **Styling**: Basic styling to improve the appearance of the form.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone <your-repository-url>
   cd taskten
   ```

2. **Open with Live Server**:
   - Open `index.html` in VSCodium or any other editor.
   - Use the Live Server extension to run the project.

## Usage

1. **Access the Form**:
   - Navigate to `http://localhost:5500` (or the port specified by Live Server) in your web browser to see the registration form.

2. **Fill Out the Form**:
   - Enter your details into the form fields.
   - The form includes basic client-side validation to check if the passwords match.

3. **Submit the Form**:
   - Click the "Submit" button to be redirected to the `submit.html` page, which will show a confirmation message.

## Files

### `index.html`
The main HTML file containing the registration form.

### `submit.html`
The HTML file displayed after form submission, confirming successful registration.

### `style.css`
The CSS file used for styling the registration form.

### `script.js`
The JavaScript file used for validating the form data, specifically checking if the passwords match.
