# AirPods Product Website

A responsive, animated product page for Apple AirPods, built with HTML, SCSS and JavaScript. It covers the whole journey from landing page to product details to a checkout form, and works on phones, tablets and desktops.

**Live:** https://pranaylachuluri.github.io/Airpods-website/

![Screenshot](https://github.com/user-attachments/assets/06ca2144-5a81-414c-bb24-14842c8e0350)

## Features

- **Animated hero:** AirPods float over a dark circular background, with entrance animations made in GSAP
- **Responsive layout:** adapts from phone to desktop
- **Product details:** a section on battery life, charging time and other specs
- **Checkout flow:** a purchase form with quantity selection and a separate pop-up for shipping details
- **Scroll animations** with ScrollMagic

## Built with

- HTML5
- SCSS, compiled to `assets/css/styles.css`
- JavaScript
- [GSAP](https://gsap.com/) and ScrollMagic for animations

## Project structure

```
index.html
assets/
  scss/styles.scss   # source styles
  css/styles.css     # compiled styles
  js/main.js         # mobile menu and GSAP animations
  img/               # product images
  icons/
```

## Run locally

Open `index.html` in a browser. To edit the styles, change `assets/scss/styles.scss` and compile it with Sass:

```bash
npx sass assets/scss/styles.scss assets/css/styles.css
```

This is a front-end demo only. It does not take real payments.
