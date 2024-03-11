<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ITS ME WEBSITE STOLER</title>
</head>
<body>
    <h1>Hello, <span id="name"></span>!</h1>

    <script>
        // JavaScript to get name and display it
        var name = prompt("Please enter your name:");
        document.getElementById("name").textContent = name;
    </script>
</body>
</html>
