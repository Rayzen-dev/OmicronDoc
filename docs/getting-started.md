# Getting started

## Download
First of all, we have to download packages [here](https://github.com/Rayzen-dev/Omicron/archive/refs/heads/master.zip "Get Omicron packages"), easy nah?

After, include the needed files in your project, link files with HTML file.

## CSS
```html
<link rel="stylesheet" href="path/to/omicron.min.css" />
```

## JS
_Note: jQuery needs to be loaded before include Omicron_
```html
<script src="path/to/omicron.min.js"></script>
```

Then, load all the components.
```javascript
Omicron.AutoInit();
```

## Basic template
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- General meta tags needed-->
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8" />
    <!-- Needed for responsive design -->
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- SEO tags -->

    <!-- Import Omicron style -->
    <link rel="stylesheet" href="path/to/omicron.min.css">
</head>
<body>
    <!-- Body of your website -->
    
    <!-- jQuery lib -->
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <!-- Import Omicron JavaScript -->
    <script src="path/to/omicron.min.js"></script>
</body>
</html>
```