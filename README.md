<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dynamic Website Renderer</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            overflow: hidden; /* Prevent scrolling */
        }
        iframe {
            width: 100%;
            height: 100vh; /* Full height of the viewport */
            border: none; /* Remove borders */
        }
    </style>
</head>
<body>
    <iframe id="dynamic-iframe" src=""></iframe>

    <script>
        // Replace this URL with the one you want to render
        const url = "https://angular.dev"; 
        document.getElementById('dynamic-iframe').src = url;
    </script>
</body>
</html>
