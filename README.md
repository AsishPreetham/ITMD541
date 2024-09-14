<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="styles.css">
  <title></title>
</head>
<body>
  <div class="image-container">
    <p>Asish Preetham Gundala</p>
    <p>I am from Andhra Pradesh, India</p>
    <p>I do not have ant experience in Web development. But, I want to learn. </p>
    <p>2024 </p>
  </div>
</body>
</html>

HTML

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="styles.css">
  <title>Image</title>
</head>
<body>
  <div class="image-container">
    <p>Your name</p>
    <p>Where you are from?</p>
    <p>What experience do you have as a web developer?</p>
    <p>What year are you in at IIT</p>
  </div>
</body>
</html>
CSS (styles.css)

body {
  margin: 0;
  padding: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background-color: #f2f2f2;
}

.image-container {
  padding: 50px;
  margin: 20px;
  border: 15px solid green;
  text-align: center;
  background-color: white;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}