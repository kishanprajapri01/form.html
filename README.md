<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Simple HTML Form</title>
  <style>
    .body{
      backgroun color👱‍♂️
  </style>
</head>
  <h1>simple form</h1>
<body>
  <h2>Contact Form</h2>
  <form action="/submit" method="post">
    <label for="name">Name:</label><br />
    <input type="text" id="name" name="name" required><br /><br />

    <label for="email">Email:</label><br />
    <input type="email" id="email" name="email" required><br /><br />

    <label for="message">Message:</label><br />
    <textarea id="message" name="message" rows="4" cols="30" required></textarea><br /><br />

    <button type="submit">Submit</button>
  </form>
</body>
</html>
