# Custom Login Form Design

This project contains a modern and visually appealing login form created with pure HTML and CSS. The design is inspired by the login ui design, featuring a clean layout, social media login options, and a distinct background.

## Features

  * **Responsive Design:** The layout is fully responsive and adjusts gracefully on different screen sizes (desktops, tablets, and mobile phones).
  * **HTML & CSS:** Built using standard HTML5 and CSS3, making it easy to understand and integrate into any web project.
  * **Font Awesome Integration:** Uses Font Awesome for social media icons (Apple, Google, Facebook), which are easy to customize.
  * **Animated Button:** The "Continue" button features a subtle arrow animation on hover for a better user experience.
  * **Image Overlay:** A translucent golden overlay is applied to the background image to enhance readability and match the design's aesthetic.
## Live Demo

Click the button below to see the project live!

[![Live Demo](https://img.shields.io/badge/Live_Demo-blue?style=for-the-badge)](https://khalid-randhawa.web.app/apps-projects/Login-Project/index3.html)

## Getting Started

To use this login form, you only need to download and place a few files in your project directory.

### Prerequisites

You don't need any special tools or software. A modern web browser is all that's required to view the page.

### Installation

1.  **Download the files:**

      * `login.html`
      * `styles.css`

2.  **Create a folder:** Create a new folder (e.g., `login-project`) and place both `login.html` and `styles.css` inside it.

### Setting Up the Background Image

The design relies on a background image to achieve its unique look. To use your own image:

1.  **Choose your image:** Find a high-quality image that you want to use for the background.
2.  **Name the file:** Rename your image file to `bc.jpg`.
3.  **Place the file:** Put the `bc.jpg` file in the same directory as your `login.html` and `style.css` files.

The `style.css` file is already configured to look for an image named `bc.jpg`. If you wish to use a different filename, you must update the CSS code accordingly:

```css
/* In style.css, find this block: */
body {
    /* ... other styles ... */
    background-image: url('bc.jpg'); /* Change 'bc.jpg' to your filename */
    background-size: cover;
    background-position: center;
}
```

### Viewing the Page

Simply open the `login.html` file in your web browser, and you will see the login form. The design will adapt to your screen size.

-----

## File Structure

The project has a very simple file structure:

```
login-project/
├── login.html      # The HTML file for the login form
├── style.css       # The CSS file for all the styling
└── bc.jpg          # Your background image file
```

-----

## License

This project is open-source. Feel free to use, modify, and distribute it as you see fit.
