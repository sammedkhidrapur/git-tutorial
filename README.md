<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Create Account</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
</head>
<body>
  <video autoplay muted loop>
  <source src="3949.mp4" type="video/mp4">
</video>
  <div class="container">
    <h1>Create-account-form</h1>
    <form id="create-account-form">
      <label for="username">Username</label>
      <input type="text" id="username" name="username" required>
      
      <label for="email">Email id</label>
      <input type="email" id="email" name="email " required>
      
      <label for="password">Password</label>
      <input type="password" id="password" name="password" required>
      
      <label for="confirm-password">Confirm Password</label>
      <input type="password" id="confirm-password" name="confirm-password" required>
      
      <button type="submit">Submit</button>
    </form>
    <p id="message"></p>
  </div>
  <script src="script.js"></script>
</body>
</html>
