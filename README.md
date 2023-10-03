# Sign-Up-Form Proect-6

**Project Title:** User Registration Page

**Project Overview:**
This project involves creating a simple user registration page using HTML and CSS. The page allows users to enter their details, including their first name, last name, email, phone number, and password. It also includes password confirmation to ensure the user enters the correct password. The registration form has basic validation to ensure that the passwords match before submission.

**HTML Structure:**
- `<!DOCTYPE html>`: Declares the document type.
- `<html lang="en">`: The HTML root element with the language attribute set to English.
- `<head>`: Contains metadata and links to external resources.
    - `<meta charset="UTF-8">`: Sets the character encoding to UTF-8.
    - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Defines the viewport settings for responsive design.
    - `<title>Document</title>`: The title of the webpage.
    - `<style>`: for styles an external file is used called index.css.
- `<body>`: The main content of the webpage.
    - `<div id="container">`: The main container for the page.
        - `<div id="container1">`: A container for the background image and content.
            - `<div id="container2">`: A container for the dark overlay and the registration form.
                - `<div id="container3">`: A container for the logo and title.
                    - `<img src="dendro.png" alt="logo" width="70px" height="70px" class="logo">`: Logo image.
                    - `<h1 id="h1">Dendro</h1>`: Website title.
            - `<main>`: The main content area.
                - `<div id="h3">`: A container for a welcome message.
                    - `<h1>WELCOME TO OUR REGISTER PAGE.</h1>`: Welcome message.
                - `<div id="h2">`: A container for the introductory text.
                    - Text describing the purpose of the registration page.
                - `<form action="#" onSubmit="return checkPassword(this)">`: The registration form with an `onSubmit` event handler.
                    - Input fields for first name, last name, email, phone number, password, and password confirmation.
                    - Submit button for creating an account.
        - `<footer id="foto">`: The footer section with a photo credit link.
            - Attribution link to the photo used in the background.

**CSS Styles:**
- Styles are defined within the `<style>` element.
- Styles are applied to various elements using IDs and classes.
- Styling includes setting background images, colors, fonts, positioning, and sizes.

**JavaScript Function:**
- JavaScript function `checkPassword(form)` is used for password validation.
- It checks if the password fields are filled and if the passwords match.
- If the passwords match, it redirects the user to a new page.
- If not, it displays an alert message.

**External Resources:**
- The page uses an external image as a background (`img.jpg`) and a logo (`dendro.png`).
- It also includes a link to a photo on Unsplash in the footer.

**Responsiveness:**
- The page is designed to be responsive to different screen sizes.

**Notes:**
- The project is a simple registration page with basic functionality and minimal styling.
- It includes placeholders and comments for further development and improvements.

Please note that this is a basic registration page template, and for production use, you should consider implementing more robust security measures and server-side validation for user data.