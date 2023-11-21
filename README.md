<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>YouTube-like Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }

        header {
            background-color: #fff;
            padding: 10px;
            box-shadow: 0 1px 5px rgba(0, 0, 0, 0.1);
        }

        .container {
            max-width: 1200px;
            margin: auto;
        }

        main {
            display: flex;
            margin-top: 20px;
        }

        .video {
            flex: 2;
            margin-right: 20px;
        }

        .comments {
            flex: 1;
        }

        footer {
            background-color: #fff;
            padding: 10px;
            text-align: center;
            box-shadow: 0 -1px 5px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <!-- Header content, e.g., logo, search bar, user profile -->
            <h1>YouTube-like Page</h1>
            <p>Replicating the look of a YouTube page</p>
        </div>
    </header>

    <main class="container">
        <div class="video">
            <!-- Video player and details -->
            <iframe width="100%" height="400" src="https://www.youtube.com/embed/VIDEO_ID" frameborder="0" allowfullscreen></iframe>
            <h2>Video Title</h2>
            <p>Video description and other details</p>
        </div>

        <div class="comments">
            <!-- Comments section -->
            <h2>Comments</h2>
            <div>
                <p>User Comment 1</p>
                <p>User Comment 2</p>
                <!-- Add more comments as needed -->
            </div>
        </div>
    </main>

    <footer>
        <p>&copy; 2023 YouTube-like Page</p>
    </footer>
</body>
</html>
