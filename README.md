<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
        }

        h1 {
            color: #333;
        }

        .section {
            margin-top: 20px;
        }

        .languages,
        .frameworks,
        .tools {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            justify-content: center;
        }

        .icon {
            width: 40px;
            height: 40px;
            margin: 5px;
            transition: transform 0.3s ease-in-out;
        }

        .icon:hover {
            transform: scale(1.2);
        }

        .animate__animated {
            animation-duration: 1s;
        }

        .animate__fadeIn {
            animation-name: fadeIn;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
            }

            to {
                opacity: 1;
            }
        }
    </style>
</head>

<body>
    <h1 align="center">Hi 👋, I'm Prakash Kumar</h1>
    <h3 align="center">A passionate competitive programmer, cybersecurity enthusiast, and flutter developer from India</h3>
    <img align="right" alt="coding" width=400
        src="https://camo.githubusercontent.com/cae12fddd9d6982901d82580bdf321d81fb299141098ca1c2d4891870827bf17/68747470733a2f2f6d69726f2e6d656469756d2e636f6d2f6d61782f313336302f302a37513379765349765f7430696f4a2d5a2e676966" />
    <!-- Other content -->

    <div class="section animate__animated animate__fadeIn">
        <h3 align="left">Languages:</h3>
        <div class="languages">
            <!-- Insert language icons with appropriate class -->
            <img class="icon" src="path/to/language1.svg" alt="Language 1">
            <img class="icon" src="path/to/language2.svg" alt="Language 2">
            <!-- Add more language icons as needed -->
        </div>
    </div>

    <div class="section animate__animated animate__fadeIn">
        <h3 align="left">Frameworks:</h3>
        <div class="frameworks">
            <!-- Insert framework icons with appropriate class -->
            <img class="icon" src="path/to/framework1.svg" alt="Framework 1">
            <img class="icon" src="path/to/framework2.svg" alt="Framework 2">
            <!-- Add more framework icons as needed -->
        </div>
    </div>

    <div class="section animate__animated animate__fadeIn">
        <h3 align="left">Tools:</h3>
        <div class="tools">
            <!-- Insert tool icons with appropriate class -->
            <img class="icon" src="path/to/tool1.svg" alt="Tool 1">
            <img class="icon" src="path/to/tool2.svg" alt="Tool 2">
            <!-- Add more tool icons as needed -->
        </div>
    </div>

    <!-- Other content -->

    <!-- Script for adding animate.css library -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"></script>
</body>

</html>
