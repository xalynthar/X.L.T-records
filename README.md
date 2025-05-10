<!-- index.html -->
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Demo Submission - [Your Label Name]</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 40px;
      background-color: #f9f9f9;
    }
    form {
      background: white;
      padding: 20px;
      border-radius: 8px;
      max-width: 400px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    input, textarea {
      width: 100%;
      margin-top: 10px;
      padding: 10px;
      border: 1px solid #ddd;
      border-radius: 4px;
    }
    button {
      margin-top: 15px;
      padding: 10px;
      background-color: black;
      color: white;
      border: none;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <h1>Submit Your Demo</h1>
  <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST" enctype="multipart/form-data">
    <label>Your Name:</label>
    <input type="text" name="name" required>

    <label>Email:</label>
    <input type="email" name="email" required>

    <label>Message:</label>
    <textarea name="message" rows="4" required></textarea>

    <label>Demo File (MP3/WAV/ZIP):</label>
    <input type="file" name="file" required>

    <button type="submit">Submit Demo</button>
  </form>
</body>
</html>
