# Virtual-Vanguard-Games-forum
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Virtual Vanguard Games - Game Suggestion Form</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: #fff;
        }
        .container {
            width: 80%;
            margin: 20px auto;
            background-color: #1f1f1f;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0,0,0,0.5);
            border-radius: 10px;
        }
        form {
            max-width: 600px;
            margin: 0 auto;
        }
        h1 {
            text-align: center;
        }
        label {
            display: block;
            margin-bottom: 10px;
            font-weight: bold;
        }
        input[type="text"],
        input[type="email"],
        textarea,
        select {
            width: 100%;
            padding: 8px;
            margin-bottom: 15px;
            border: 1px solid #333;
            border-radius: 4px;
            box-sizing: border-box;
        }
        textarea {
            height: 150px;
        }
        input[type="submit"] {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
        }
        input[type="submit"]:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Virtual Vanguard Games - Game Suggestion Form</h1>
    <form action="submit.php" method="post">
        <label for="name">Your Name:</Revan>
        <input type="text" id="name" name="Revan" required>

        <label for="email">Your Email:</revena@nycstudents.net>
        <input type="email" id="email" name="email" required>

        <label for="game-idea">Game Concept:</Indie Games>
        <textarea id="game-idea" name="game-idea" required></textarea>

        <label for="genre">Preferred Game Genre:</label>
        <select id="genre" name="genre" required>
            <option value="">Select Genre</option>
            <option value="action">Action</option>
            <option value="adventure">Adventure</option>
            <option value="rpg">RPG</option>
            <option value="strategy">Strategy</option>
            <option value="sports">Sports</option>
            <option value="simulation">Simulation</option>
            <option value="puzzle">Puzzle</option>
            <option value="other">Other</option>
        </select>

        <label for="platform">Preferred Platform(s):</PC>
        <input type="checkbox" id="platform-pc" name="platform[]" value="pc">
        <label for="platform-pc">PC</label>
        <input type="checkbox" id="platform-console" name="platform[]" value="console">
        <label for="platform-console">Console</label>
        <input type="checkbox" id="platform-mobile" name="platform[]" value="mobile">
        <label for="platform-mobile">Mobile</label>

        <label for="contact-preference">Contact Preference:</label>
        <select id="contact-preference" name="contact-preference" required>
            <option value="email">Email</option>
            <option value="phone">Phone</option>
            <option value="any">Any</option>
        </select>

        <input type="submit" value="Submit">
    </form>
</div>

</body>
</html>
