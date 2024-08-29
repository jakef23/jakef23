<!DOCTYPE html>
<html>
<head>
    <title>Interactive Button</title>
</head>
<body>
    <button id="myButton">Click Me!</button>

    <script>
        // Get the button element by its id
        const button = document.getElementById('myButton');

        // Add a click event listener to the button
        button.addEventListener('click', function() {
            alert('You clicked the button!');
        });
    </script>
</body>
</html>
