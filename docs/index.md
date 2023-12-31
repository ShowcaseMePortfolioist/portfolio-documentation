# Getting Started

## Installation

To begin exploring your site template, follow these steps:

1.  Open the `template` folder to locate all template files.

2.  Upload these files to your Web Server for use on your Website.

3.  Ensure you upload all the necessary files/folders listed below:

    - `template/assets/css` : Stylesheets Folder
    - `template/assets/css/styles.css` : Main Stylesheet File
    - `template/assets/js` : Javascript Folder
    - `template/assets/js/script.js` : Main Javascript File
    - `template/assets/images` : Image Folder
    - `template/index.html` : Index File/Homepage

---

## Page Options

These settings need configuration before editing your site template:

### Changing Fonts

Utilize Google Fonts API by adding a stylesheet link to request desired web font(s) inside each page's **head** tags.

**_Code Example_**

```html
<link
  href="https://fonts.googleapis.com/css2?family=Syne:wght@400;600;700;800&display=swap"
  rel="stylesheet"
/>
```

Style an element with the requested web font in a stylesheet:

**_Code Example_**

```css
html,
body {
  font-family: "Poppins", sans-serif;
}
```

For self-hosted fonts, use this code at the top of the `style.css` file.

```css
@font-face {
  font-family: "MyWebFont";
  src: url("fonts/webfont.woff2") format("woff2"), url("fonts/webfont.woff")
      format("woff"), url("fonts/webfont.ttf") format("truetype"), url("fonts/webfont.svg#svgFontName")
      format("svg");
}
```

Place the font files inside the `fonts` folder in the template's Root Folder..

---

### Smooth Scroll

Enable smooth scrolling by setting `scroll-behavior` as `smooth` in the `style.css` stylesheet file.

**_Code Example_**

```css
html {
  scroll-behavior: smooth;
}
```

---

### Page Color Scheme

Adjust page colors in the `root` element within the `style.css` file.

- Open `style.css`

- Inside the `:root` section, locate the color area.

- Modify the variable name and associated color for the entire page.

**_Note_**: Ensure the variable name change reflects throughout the stylesheet.

---

## Custom JS Code

Add your custom JavaScript Code within the `assets/script.js` file.

**_Code Example_**

```javascript
function functionName() {
  //Add here your custom js code
}
```

---

## Changing Images

Replace images on the page following these steps:

- Navigate to the` assets/images` folder.

- Substitute the existing images with your relevant images.

---

## Changing Resume

Update your resume for download:

- Visit the `assets/resume` folder.

- Replace the `resume.pdf` file with your updated resume.
