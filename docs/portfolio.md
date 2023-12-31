# Portfolio

## Carousel Slider

This template provides an elegant way to showcase your work using a Carousel Slider powered by Javascript.

**_Code Example_**

```html
<div class="slider" data-slider>
  <ul class="slider-container service-list" data-slider-container>
    <li class="slider-item" data-slider-item data-aos="fade-up">
      <div class="service-card">
        <div class="card-icon">
          <ion-icon name="desktop-outline"></ion-icon>
        </div>
        <h3 class="h3 card-title">...</h3>
        <p class="card-text">...</p>
        <span class="text-lg card-number">01</span>
        <a href="#" class="layer-link" aria-label="services"></a>
      </div>
    </li>
  </ul>
</div>
```

---

## Project Page

The project page consists of five sections.

### Hero

This section contains titles, subtitles, images, and documents.

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
          alt="Name"
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

---

### Services

This section contains information about the services you offer.

**_Code Example_**

```html
<section class="service" aria-labelledby="service-label" id="service">
  <div class="container">
    <div class="title-wrapper">
      <div>
        <p class="section-subtitle">....</p>
        <h2 class="h2 section-title" id="service-label">...</h2>
      </div>
      <p class="section-text">...</p>
    </div>
    <div class="slider" data-slider>
      <ul class="slider-container service-list" data-slider-container>
        <li class="slider-item" data-slider-item data-aos="fade-up">
          <div class="service-card">
            <div class="card-icon">
              <ion-icon name="desktop-outline"></ion-icon>
            </div>
            <h3 class="h3 card-title">...</h3>
            <p class="card-text">...</p>
            <span class="text-lg card-number">01</span>
            <a href="#" class="layer-link" aria-label="service"></a>
          </div>
        </li>
      </ul>
    </div>
  </div>
</section>
```

---

### Skills

This section showcases your skills in an elegant way.

**_Code Example_**

```html
<li>
  <div class="progress-wrapper">
    <p class="progress-label">Design</p>
    <data class="progress-value" value="90">90%</data>
  </div>
  <div class="progress-bg">
    <div class="progress" style="width: 90%;"></div>
  </div>
</li>
```

---

### Portfolio

This section showcases your work in a well-crafted carousel.

**_Code Example_**

```html
<li class="slider-item" data-aos="fade-up">
  <div class="portfolio-card img-holder" style="--width: 600; --height: 600;">
    <img
      src="./assets/images/portfolio.jpg"
      width="600"
      height="600"
      loading="lazy"
      alt="portfolio"
      class="img-cover"
    />
    <div class="card-content">
      <h3 class="h3 card-title">...</h3>
      <p class="card-text">...</p>
    </div>
    <a href="#" class="layer-link"></a>
  </div>
</li>
```

---

### Blog

This section talks about your perspective and the latest news on recent technologies.

**_Code Example_**

```html
<div class="blog-card">
  <figure
    class="card-banner img-holder"
    data-aos="fade-left"
    style="--width: 700; --height: 470;"
  >
    <img
      src="./assets/images/blog-2.jpg"
      width="700"
      height="470"
      loading="lazy"
      alt="UX in Ecommerce – 5 things to avoid."
      class="img-cover"
    />
  </figure>
  <div class="card-content" data-aos="fade-right">
    <time class="time" datetime="...">
      <span class="span text-lg">...</span>...
    </time>
    <div>
      <h3 class="h3 card-title">...</h3>
      <p class="card-text">...</p>
      <a href="#" class="btn has-before">
        <span class="span">Read more</span>
        <ion-icon name="arrow-forward"></ion-icon>
      </a>
    </div>
  </div>
</div>
```
