<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Knowledge Quest</title>
    <link rel="stylesheet" href="styles.css"> <!-- Include your CSS file for styling -->
</head>
<body>

    <header>
        <h1>Welcome to Knowledge Quest</h1>
        <p>Embark on a quest to gather knowledge and solve challenges!</p>
    </header>

    <section id="characterCreation">
        <h2>Create Your Avatar</h2>
        <!-- Form for avatar creation -->
        <form action="create_avatar.php" method="post">
            <!-- Avatar customization options go here -->
            <button type="submit">Start Quest</button>
        </form>
    </section>

    <section id="gameMap">
        <h2>Explore the Game Map</h2>
        <!-- Interactive map goes here with clickable regions -->
        <div class="region" id="mathRegion">
            <h3>Math Mountains</h3>
            <p>Challenge yourself with math puzzles and quizzes in the Math Mountains region.</p>
            <a href="math_region.php">Enter Math Mountains</a>
        </div>
        <!-- More regions go here -->
    </section>

    <footer>
        <p>&copy; 2023 Knowledge Quest. All rights reserved.</p>
    </footer>

</body>
</html>

