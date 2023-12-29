# Getting Started

## Installation

To initiate your site template exploration, proceed with the steps outlined below:

1.  Open the `package` folder to find all the templates files.

2.  Upload these files to your Web Server in order to use it on your Website.

3.  Make sure you upload all the required files/folders listed below:

    - `template/assets/css` : Stylesheets Folder
    - `template/assets/css/styles.css` : Main Stylesheet File
    - `template/assets/js` : Javascript Folder
    - `template/assets/js/script.js` : Main Javascript File
    - `template/assets/images` : Image Folder
    - `template/index.html` : Index File/Homepage

---

## Page Options

These features you need to set up before editing your site template:

### Changing Fonts

You can use Google Fonts API by adding a stylesheet link to request desired web font(s) inside each page **head** tags.

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

If you want to use self-hosted fonts, use the following code at the top of the `style.css` file.

```css
@font-face {
  font-family: "MyWebFont";
  src: url("fonts/webfont.woff2") format("woff2"), url("fonts/webfont.woff")
      format("woff"), url("fonts/webfont.ttf") format("truetype"), url("fonts/webfont.svg#svgFontName")
      format("svg");
}
```

You need to place the fonts files inside `fonts` folder in the template **_Root Folder_**.

---

### Smooth Scroll

Smooth scrollbar is a **_HTML Element_** that allows high performance scrollbars. To enable it you need to set `scroll-behaviour` as `smooth` in the `style.css` stylesheet file.

**_Code Example_**

```css
html {
  scroll-behavior: smooth;
}
```

---

### Page Color Scheme

The colors used in the page can be change in the `root` elemment in the `style.css` file.

- Open the `style.css` file and in the `:root` section, find the colors area.

- You can adjust the variable name and the color of the whole page.

**_Note_**: The variable name must be change throughout the whole stylesheet.

---

## Custom JS Code

You can add your custom Javascript Code in the `assets/script.js` file.

**_Code Example_**

```js
function functionName() {
  //Add here your custom js code
}
```

---

## Changing Images

You can change the images in the page by following these steps:

- Go to `assets/images` folder.

- Replace the images in that folder with your relevant images.

---

## Changing Resueme

You can change your resume and make it available for download.

- Go to `assets/resuem` folder

- Replace the `resuem.pdf` file with your resume

