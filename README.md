# Hello, World! with Theme Toggle

A simple, responsive web page displaying "Hello, World!" with a functional dark mode toggle.

## Features

*   **"Hello, World!" Display:** A centered greeting on the page.
*   **Responsive Design:** Optimized for various screen sizes using Tailwind CSS.
*   **Theme Toggle:** Switch between light and dark modes with a button. The preference is saved in local storage.
*   **System Preference Adherence:** Automatically applies dark mode if the user's system preference is set to dark, unless a specific theme is chosen.

## Technologies Used

*   **HTML5:** Structure of the web page.
*   **Tailwind CSS:** For all styling and responsive design. (Note: Bootstrap CDN was mentioned in the prompt, but this project adheres to the core instruction of using Tailwind CSS for consistency and single-framework approach).
*   **JavaScript:** For theme toggling functionality and local storage management.

## Setup and Usage

To view this project, simply download the `index.html` file and open it in your web browser. No special build steps or server are required.

1.  **Clone the repository (or save `index.html`):**
    ```bash
    git clone <repository-url> # Replace with actual URL if applicable
    cd hello-world-theme
    ```

2.  **Open `index.html`:**
    Double-click `index.html` in your file explorer, or open it via your browser's file menu.

## Customization

*   **Text Content:** Modify the `<h1>` tag in `index.html` to change the main greeting.
*   **Styling:** Adjust Tailwind CSS classes directly in `index.html` to customize the look and feel.
*   **Theme Toggle:** The JavaScript logic for theme toggling is self-contained within `index.html` and can be adapted if needed.

## License

This project is open source and available under the MIT License. See the `LICENSE` file for more details.
