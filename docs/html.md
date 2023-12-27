# HTML Structure

## Header

This section is alwaus fixed on top and contains the logo, the navigation and the option menu.

**_Code Example_**

```html
<header class="header">
  <div id="container">
    <!-- Logo -->
    <div id="logo">...</div>

    <!-- Navigation -->
    <nav>
      <div class="navbar">
        <ulclass="navbar-link">
          ...
        </ul>
      </div>
    </nav>

    <div class="overlay">...</div>
  </div>
</header>
```

---

## Logo Settings

You can set your logo or the name of your website in here.

**_Code Example_**

```html
<div id="logo">
  <a class="logo-name" href="#">
    <img class="logo" src="images/logo.png" alt="Logo" />
    <h2>Name.</h2>
  </a>
</div>
```

---

## Navigation Type and Structure

This Website has a Menu for navigation. The navigation links are inside the Option Menu.

**_Code Example_**

```html
<nav class="navbar" data-navbar>
  <ul class="navbar-list">
    <li>
      <a href="#" class="navbar-link">...</a>
    </li>
    <li>
      <a href="#" class="navbar-link">...</a>
    </li>
    <li>
      <a href="#" class="navbar-link">...</a>
    </li>
  </ul>
</nav>
```

## Hero

This section contains the page title and subtitles.

**_Code Example_**

```html
<section class="section hero" aria-label="home">
  <div class="container">
    <div class="hero-content">
      <h1 class="h1 hero-title">...</h1>
      <p class="hero-subtitle">...</p>
      <div class="hero-banner">
        <img
          src="./assets/images/hero-banner.jpg"
          width="800"
          height="800"
          alt="Hero"
          class="w-100"
        />
      </div>
      <p class="section-text">...</p>
      <a href="#" class="btn has-before">
        <span class="span">Download CV</span>
        <ion-icon
          class="down"
          name="download-outline"
          aria-hidden="true"
        ></ion-icon>
      </a>
    </div>
  </div>
</section>
```

## Content

These sections contains the contents of the webpage.

**_Code Example_**

```html
<div id="section-name" class="container">...</div>
```

## Footer

This section contains the Social Links, Copyright Info and Contact Information.

**_Code Example_**

```html
<footer class="footer">
  <div class="container">
    <ul class="footer-list">
      <li>
        <p class="h4 footer-list-title" id="contact">...</p>
      </li>
      <li>
        <a href="mailto:info@.com" class="footer-link">...</a>
      </li>
    </ul>
    <ul class="footer-list">
      <li>
        <p class="h4 footer-list-title">...</p>
      </li>
      <li>
        <a href="#" class="footer-link">...</a>
      </li>
    </ul>
    <ul class="social-list">
      <li>
        <a href="#" class="social-link">
          <ion-icon name="logo-dribbble"></ion-icon>
        </a>
      </li>
      <li>
        <a href="#" class="social-link">
          <ion-icon name="logo-instagram"></ion-icon>
        </a>
      </li>
    </ul>
  </div>
</footer>
```
