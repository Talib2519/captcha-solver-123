# Captcha Solver Application

This is a simple, single-file web application designed to demonstrate a basic captcha solving mechanism. It displays an image (either a default local image or one provided via a URL parameter) and allows users to input the text they see in the image to verify.

## Features

*   **Dynamic Image Loading**: Displays a captcha image. Defaults to `sample.png` but can load an image from a URL parameter (`?url=https://example.com/captcha.png`).
*   **User Input**: Provides an input field for users to type the captcha text.
*   **Verification**: Checks the user's input against a predefined correct answer.
*   **Responsive Design**: Built with Tailwind CSS for a modern and responsive user interface across various devices.
*   **Single-File**: All necessary HTML, CSS (via CDN), and JavaScript are contained within `index.html`.

## Getting Started

To run this application, simply open the `index.html` file in your web browser.

### Usage

1.  **Default Captcha**: Open `index.html` directly in your browser. The `sample.png` image will be displayed.
2.  **Custom Captcha (URL Parameter)**: You can provide an external image URL using the `url` query parameter.
    For example: `index.html?url=https://example.com/path/to/your/captcha.png`
    *(Note: For security reasons, browsers may block loading images from different origins if the server does not send appropriate CORS headers. For local testing, ensure the URL is accessible or use a local image.)*

3.  **Solve**:
    *   Observe the text displayed in the captcha image.
    *   Type the text into the input field. The expected text for the default `sample.png` is `ADCR3`.
    *   Click the "Submit" button or press Enter.
    *   A message will indicate whether your input was correct or incorrect.

## Technologies Used

*   **HTML5**: Structure of the web page.
*   **Tailwind CSS**: For styling and responsive design (via CDN).
*   **JavaScript**: For dynamic content, URL parameter handling, and captcha verification logic.

## Project Structure

*   `index.html`: The main and only HTML file containing the application.
*   `sample.png`: The default captcha image.
*   `README.md`: This file.
*   `LICENSE`: The MIT License for this project.

## License

This project is open-sourced under the MIT License. See the `LICENSE` file for more details.
