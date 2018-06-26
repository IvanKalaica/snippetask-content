---
name: HTML5 boilerplate
language: html
read_more:
- https://html5boilerplate.com
---
This is a stripped version of original HTML5 boilerplate.
This one doesn't include any `javascript` libraries but just the core HTML structure with links to your `css/main.css` and `js/main.js` files.
For `manifest` file structure see [Web App Manifest Generator](https://tomitm.github.io/appmanifest/).

```html
<!doctype html>
<html lang="en">

<head>
  <meta charset="utf-8">
  <meta http-equiv="x-ua-compatible" content="ie=edge">
  <title></title>
  <meta name="description" content="">
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

  <link rel="manifest" href="site.webmanifest">
  <link rel="apple-touch-icon" href="icon.png">
  <!-- Place favicon.ico in the root directory -->

  <link rel="stylesheet" href="css/main.css">
</head>

<body>
  <!--[if lte IE 9]>
    <p class="browserupgrade">You are using an <strong>outdated</strong> browser. Please <a href="https://browsehappy.com/">upgrade your browser</a> to improve your experience and security.</p>
  <![endif]-->

  <!-- Add your site or application content here -->
  <p>Hello world! This is HTML5 Boilerplate.</p>
  
  <script src="js/main.js"></script>
</body>

</html>
```