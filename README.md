# assets
Public CSS assets used by our infrastructure sites

See [assets.strato](http://assets.strato) for some info.

## Base HTML template
```html
<!DOCTYPE html>
<html lang="en-us">
<head>
    <script src="https://use.fontawesome.com/afed2b1f81.js"></script>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="index.css" />
    <title>Example page</title>
</head>
<body>
    <div class="block">
        <div class="emoji"><h1>[icon]</h1></div>
        <div class="body-container">
        <div class="body">


        [HTML]
        

        </div>
        </div>
    </div>
</body>
</html>
```
Replace `[icon]` with an icon from the [Font Awesome](http://fontawesome.io/icons/) project.

Replace `[HTML]` with your site's body HTML, such as `<p>` tags and images.
