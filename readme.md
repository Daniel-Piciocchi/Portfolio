
# Portfolio - Beginner Friendly Website

A website created from scratch using introductory to web development tools html and CSS.


## Table of Contents

- html
- css
- wireframes
- git

## HTML

Began by creating the skeleton (! + Enter in VScode), followed by links to CSS style sheets, one representing a universal style sheet, and the other specific to the page being represented. Additionally, the main container, navigation container, quote container, body container, and footer were created.

The header contains a home button logo on the left hand side, and 4 navigation buttons, 'About', 'Blog', 'Work', and 'Contact' along the right hand side.

Inside the body a quote container was created followed by space for a 'Profile Pic' on the left-hand side, and space for a brief intro with a name and description on the right-hand side of the image.

A section containing the footer was implemented to sit center and bottom of the page with social media links to 'GitHub', 'LinkdIn', and a 'Contact' button that links to another page for leaving details.

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <meta http-equiv="X-UA-Compatible" content="IE=edge" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <title>Home</title>
        <link rel="stylesheet" href="./styles/styleSheet.css" />
        <link rel="stylesheet" href="./styles/homeStyleSheet.css" />
    </head>
    <body>
        <main class="container">
            <img
                id="hamburger"
                src="./images/hamburger-menu.png"
                width="50"
                height="50"
            />
            <div class="navigationContainer">
                <div class="logo">
                    <a href="./home.html" alt="Logo Home Page">
                        <img
                            src="./images/coding-logo.png"
                            width="70"
                            height="50"
                        />
                    </a>
                </div>
                <nav>
                    <a id="navArrow" href="./pages/about.html">About</a>
                    <a id="navArrow" href="./pages/blogs/blog.html">Blog</a>
                    <a id="navArrow" href="./pages/work.html">Work</a>
                    <a id="navArrow" href="./pages/contact.html">Contact</a>
                </nav>
            </div>
            <section class="quoteContainer">
                <p>'Just trying to keep the power on in Jurassic Park'</p>
            </section>
            <section class="bodyContainer">
                <img
                    class="profilePic"
                    src="./images/profile-pic.png"
                    width="224"
                    height="183"
                />
                <div class="intro">
                    <p>Daniel Piciocchi</p>
                    <p>Future Full Stack-Developer</p>
                </div>
            </section>
            <footer>
                <a href="https://github.com/Daniel-Piciocchi" target="_blank">
                    <img
                        class="socialMediaLogos"
                        src="./images/github-logo.png"
                        a="github-logo"
                    />
                </a>
                <a href="https://au.linkedin.com/" target="_blank">
                    <img
                        class="socialMediaLogos"
                        src="./images/linked-in-logo.png"
                        a="linked-in-logo"
                        height="64"
                        href="https://au.linkedin.com/"
                    />
                </a>
                <a href="./pages/contact.html">
                    <img
                        class="socialMediaLogos"
                        src="./images/contact-background.png"
                        a="linked-in-logo"
                        height="64"
                    />
                </a>
            </footer>
        </main>
    </body>
</html>
```
## CSS

