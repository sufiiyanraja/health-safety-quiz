!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quiz Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="quiz-container">
        <h1>Health & Safety Quiz</h1>
        <form id="quiz-form">
            <div class="question">
                <p>All health and safety initiatives start with risk assessments. (True/False)</p>
                <input type="radio" name="q1" value="True"> True
                <input type="radio" name="q1" value="False"> False
            </div>
            <div class="question">
                <p>Bomb threat investigations must be conducted by a security officer with an explosives expert. (True/False)</p>
                <input type="radio" name="q2" value="True"> True
                <input type="radio" name="q2" value="False"> False
            </div>
            <!-- Add more questions here -->
            <button type="submit">Submit</button>
        </form>
        <div id="result"></div>
    </div>

    <script src="script.js"></script>
</body>
</html>
