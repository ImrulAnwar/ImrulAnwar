<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .container {
            max-width: 80vw; /* Set the maximum width of the container */
            margin: 0 auto; /* Center the container horizontally */
            padding: 20px; /* Add some padding for spacing */
        }

        .flex-container {
            display: flex;
            justify-content: space-between; /* Distribute items evenly along the main axis */
            margin-top: 20px; /* Add margin for spacing */
        }

        .flex-container > div {
            flex: 1;
            margin: 0 10px; /* Add some margin between the images */
        }
    </style>
</head>
<body>
    <div class="container">
        <h1 align="center">Hi 👋, I'm Imrul Anwar</h1>
        <h3 align="center">Native Android & Fullstack Developer</h3>
        <p>
            <!-- Your content here -->
        </p>
        <h3 align="left">Socials</h3>
        <p align="left">
            <!-- Your social links here -->
        </p>
        <h3 align="left">Tools For Android: </h3>
        <p align="left">
            <!-- Your Android tools here -->
        </p>
        <h3 align="left">Languages and Tools:</h3>
        <p align="left">
            <!-- Your languages and tools here -->
        </p>
        <div class="flex-container">
            <div>
                <img style="height: 200px; width: auto;" src="https://github-readme-stats.vercel.app/api/top-langs?username=imrulanwar&show_icons=true&locale=en&layout=compact" alt="imrulanwar" />
            </div>
            <div>
                <img style="height: 200px; width: auto;" src="https://github-readme-streak-stats.herokuapp.com/?user=imrulanwar&" alt="imrulanwar" />
            </div>
        </div>
    </div>
</body>
</html>
