<h1 align="center">Hi 👋, I'm Yash Datir</h1>
<h3 align="center">A passionate MERN Stack developer from India</h3>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Yash Datir - Web Developer</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background-color: #f0f0f0;
      text-align: center;
      padding: 50px;
    }

    #typing-effect {
      font-size: 24px;
      font-weight: bold;
      color: #333;
      white-space: nowrap;
      overflow: hidden;
      border-right: 3px solid #333;
    }
  </style>
</head>
<body>
  <div id="typing-effect"></div>

  <script>
    const text = "My name is Yash Datir and I am a Web Developer";
    let index = 0;

    function typeText() {
      document.getElementById('typing-effect').textContent = text.slice(0, index);
      index++;

      if (index > text.length) {
        index = 0; // Restart the typing effect
      }

      setTimeout(typeText, 100); // Adjust the typing speed (in milliseconds)
    }

    // Start the typing effect
    typeText();
  </script>
</body>
</html>
