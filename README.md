# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![Screenshot of Desktop Huddle landing page with single introductory solution](./design/desktop-design.jpg)

![Screenshot of Desktop active-states Huddle landing page with single introductory solution](./design/active-states.jpg)

![Screenshot of Mobile Huddle landing page with single introductory solution](./design/mobile-design.jpg)

### Links

- Solution URL: [https://github.com/Sammed-NJ/huddle-landing-page-with-single-introductory-section-master.git](https://github.com/Sammed-NJ/huddle-landing-page-with-single-introductory-section-master.git)
- Live Site URL: [https://huddle-landing-page-with-single-introductory-section-master.netlify.app/](https://huddle-landing-page-with-single-introductory-section-master.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- some JS used

### What I learned

This was usefull challenge.

```html
<div class="main-container">
  <img id="img" src="images/bg-desktop.svg" />

  <div class="container">
    <nav>
      <img src="images/logo.svg" alt="logo" />
    </nav>

    <div class="contant">
      <div class="contant-img">
        <img src="images/illustration-mockups.svg" alt="logo" />
      </div>

      <div class="contant-text">
        <h1>
          Build The Community <br />
          Your Fans Will Love
        </h1>

        <p>
          Huddle re-imagines the way we build communities. You have a voice, but
          so does your audience. Create connections with your users as you
          engage in genuine discussion.
        </p>

        <button>Register</button>
      </div>
    </div>

    <footer>
      <div class="social-media">
        <a href="#">
          <button>
            <svg
              aria-hidden="true"
              focusable="false"
              data-prefix="fab"
              data-icon="facebook-f"
              class="svg-inline--fa fa-facebook-f fa-w-10"
              role="img"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 320 512"
            >
              <path
                fill="currentColor"
                d="M279.14 288l14.22-92.66h-88.91v-60.13c0-25.35 12.42-50.06 52.24-50.06h40.42V6.26S260.43 0 225.36 0c-73.22 0-121.08 44.38-121.08 124.72v70.62H22.89V288h81.39v224h100.17V288z"
              ></path>
            </svg>
          </button>
        </a>

        <a href="#">
          <button>
            <svg
              aria-hidden="true"
              focusable="false"
              data-prefix="fab"
              data-icon="twitter"
              class="svg-inline--fa fa-twitter fa-w-16"
              role="img"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 512 512"
            >
              <path
                fill="currentColor"
                d="M459.37 151.716c.325 4.548.325 9.097.325 13.645 0 138.72-105.583 298.558-298.558 298.558-59.452 0-114.68-17.219-161.137-47.106 8.447.974 16.568 1.299 25.34 1.299 49.055 0 94.213-16.568 130.274-44.832-46.132-.975-84.792-31.188-98.112-72.772 6.498.974 12.995 1.624 19.818 1.624 9.421 0 18.843-1.3 27.614-3.573-48.081-9.747-84.143-51.98-84.143-102.985v-1.299c13.969 7.797 30.214 12.67 47.431 13.319-28.264-18.843-46.781-51.005-46.781-87.391 0-19.492 5.197-37.36 14.294-52.954 51.655 63.675 129.3 105.258 216.365 109.807-1.624-7.797-2.599-15.918-2.599-24.04 0-57.828 46.782-104.934 104.934-104.934 30.213 0 57.502 12.67 76.67 33.137 23.715-4.548 46.456-13.32 66.599-25.34-7.798 24.366-24.366 44.833-46.132 57.827 21.117-2.273 41.584-8.122 60.426-16.243-14.292 20.791-32.161 39.308-52.628 54.253z"
              ></path>
            </svg>
          </button>
        </a>

        <a href="#">
          <button>
            <svg
              aria-hidden="true"
              focusable="false"
              data-prefix="fab"
              data-icon="instagram"
              class="svg-inline--fa fa-instagram fa-w-14"
              role="img"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 448 512"
            >
              <path
                fill="currentColor"
                d="M224.1 141c-63.6 0-114.9 51.3-114.9 114.9s51.3 114.9 114.9 114.9S339 319.5 339 255.9 287.7 141 224.1 141zm0 189.6c-41.1 0-74.7-33.5-74.7-74.7s33.5-74.7 74.7-74.7 74.7 33.5 74.7 74.7-33.6 74.7-74.7 74.7zm146.4-194.3c0 14.9-12 26.8-26.8 26.8-14.9 0-26.8-12-26.8-26.8s12-26.8 26.8-26.8 26.8 12 26.8 26.8zm76.1 27.2c-1.7-35.9-9.9-67.7-36.2-93.9-26.2-26.2-58-34.4-93.9-36.2-37-2.1-147.9-2.1-184.9 0-35.8 1.7-67.6 9.9-93.9 36.1s-34.4 58-36.2 93.9c-2.1 37-2.1 147.9 0 184.9 1.7 35.9 9.9 67.7 36.2 93.9s58 34.4 93.9 36.2c37 2.1 147.9 2.1 184.9 0 35.9-1.7 67.7-9.9 93.9-36.2 26.2-26.2 34.4-58 36.2-93.9 2.1-37 2.1-147.8 0-184.8zM398.8 388c-7.8 19.6-22.9 34.7-42.6 42.6-29.5 11.7-99.5 9-132.1 9s-102.7 2.6-132.1-9c-19.6-7.8-34.7-22.9-42.6-42.6-11.7-29.5-9-99.5-9-132.1s-2.6-102.7 9-132.1c7.8-19.6 22.9-34.7 42.6-42.6 29.5-11.7 99.5-9 132.1-9s102.7-2.6 132.1 9c19.6 7.8 34.7 22.9 42.6 42.6 11.7 29.5 9 99.5 9 132.1s2.7 102.7-9 132.1z"
              ></path>
            </svg>
          </button>
        </a>
      </div>
    </footer>
  </div>
</div>
```

```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  background-color: hsl(257, 40%, 49%);
  font-family: "Open Sans", sans-serif;
  color: white;
}

.main-container #img {
  width: 1550px;
  height: auto;
}

.container {
  display: flex;
  flex-direction: column;
  position: absolute;
  top: 0;
}

.container nav,
.contant,
footer {
  width: 90%;
  margin: auto;
}

.container nav {
  min-height: 15vh;
  padding: 2rem 0;
}

.container .contant {
  min-height: 75vh;
  display: flex;
  justify-content: center;
  align-items: center;
}

.container .contant .contant-img img {
  width: 60rem;
  padding: 1rem;
}

.container .contant .contant-text {
  align-self: flex-start;
  padding: 5rem 2rem 0 2rem;
}

.container .contant .contant-text h1 {
  font-size: 3rem;
}

.container .contant .contant-text p {
  margin: 2rem 0 3rem 0;
  font-size: 1.4rem;
  color: rgb(216, 216, 216);
}

.container .contant .contant-text button {
  font-size: 1.4rem;
  padding: 1.5rem 5rem;
  border-radius: 5rem;
  border: none;
  color: hsl(257, 40%, 49%);
  box-shadow: 4px 2px 10px rgba(0, 0, 0, 0.5);
  cursor: pointer;
  transition: 0.3s ease-in-out;
}

.container .contant .contant-text button:hover {
  box-shadow: 8px 4px 10px rgba(0, 0, 0, 0.7);
  background-color: hsl(300, 72%, 67%);
  color: white;
}

.container footer {
  min-height: 10vh;
  display: flex;
  justify-content: flex-end;
}

.container footer button {
  padding: 1rem;
  overflow: hidden;
  background-color: rgba(255, 255, 255, 0);
  border: 2px solid white;
  border-radius: 100%;
  margin: 0 0.6rem;
  color: white;
  cursor: pointer;
}

.container footer button:hover {
  border: 2px solid hsl(300, 72%, 67%);
  color: hsl(300, 72%, 67%);
}

.container footer button svg {
  width: 25px;
  height: 25px;
}

@media screen and (max-width: 500px) {
  .main-container {
    overflow: hidden;
  }
  .main-container #img {
    width: 550px;
    height: auto;
  }

  .container nav img {
    width: 40%;
  }

  .container .contant {
    flex-wrap: wrap;
  }

  .container .contant .contant-img img {
    width: 30rem;
  }

  .container .contant .contant-text {
    text-align: center;
    padding: 5rem 2rem 0rem 2rem;
  }

  .container .contant .contant-text h1 {
    font-size: 1.5rem;
  }

  .container .contant .contant-text p {
    font-size: 1rem;
    width: 90%;
    margin: auto;
    padding: 1.6rem 0;
  }

  .container .contant .contant-text button {
    font-size: 1rem;
    padding: 1rem 3rem;
  }

  .container footer {
    min-height: 10vh;
    display: flex;
    justify-content: center;
  }

  .container footer button {
    margin: 2rem 0.6rem;
    padding: 0.6rem;
  }

  .container footer button svg {
    width: 15px;
    height: 15px;
  }
}
```

```js
  <script>
    let width = window.innerWidth;
    if(width === 500) {
      document.getElementById("img").src = 'images/bg-mobile.svg';
    }
    console.log(width);

  </script>
```
