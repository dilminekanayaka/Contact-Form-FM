# Frontend Mentor - Contact Form Solution

This is a solution to the Contact form challenge on [Frontend Mentor](https://www.frontendmentor.io/challenges/contact-form--G-hYlqKJj).

## Table of Contents

  - [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
  - [Author](#author)
  - [Acknowledgments](#acknowledgments)

## Overview

### The Challenge

Users should be able to:

- Complete the form and see a success toast message upon successful submission
- Receive form validation messages if:
  - A required field has been missed
  - The email address is not formatted correctly
- Complete the form only using their keyboard
- Have inputs, error messages, and the success message announced on their screen reader
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![Screenshot](./design/desktop-design.jpg)

### Links

- [Solution URL](https://your-solution-url.com)
- [Live Site URL](https://your-live-site-url.com)


### Built With

- HTML5 
- CSS 
- JavaScript

### What I Learned

This project helped me enhance my understanding of form validation and accessibility features. I implemented custom validation messages and ensured the form is fully navigable via keyboard and screen readers.

```html
<form>
  <label for="name">Name</label>
  <input type="text" id="name" required>
</form>
```
```
input:focus {
  outline: 2px solid blue;
}
```

```
const form = document.querySelector('form');
form.addEventListener('submit', (e) => {
  e.preventDefault();
  console.log('Form submitted!');
});
```

### Continued Development

In future projects, I plan to delve deeper into:

- Advanced CSS techniques such as animations and transitions
- Enhancing form validation with libraries like Formik or Yup
- Improving accessibility and ARIA roles

### Useful Resources

- [MDN Web Docs](https://developer.mozilla.org/) - A comprehensive resource for web development knowledge.
- [W3Schools](https://www.w3schools.com/) - Great for quick reference and tutorials.

### Author

- Frontend Mentor - [@dilminekanayaka](https://www.frontendmentor.io/profile/dilminekanayaka)
- Twitter - [@dilminekanayaka](https://www.twitter.com/dilminekanayaka)

### Acknowledgments

Special thanks to the Frontend Mentor community for their support and feedback throughout this challenge.
