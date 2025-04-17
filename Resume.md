<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Resume - Kasarapu Mohan Reddy</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      background-color: #f8f9fa;
      padding-top: 80px;
    }
    .resume-container {
      text-align: center;
    }
    .resume-img {
      max-width: 90%;
      border: 1px solid #ccc;
      border-radius: 10px;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .resume-img:hover {
      transform: scale(1.02);
      box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3);
    }
    .download-btn {
      margin-top: 20px;
      padding: 10px 20px;
      font-weight: bold;
      background-color: #f1c40f;
      color: #000;
      border: none;
      border-radius: 5px;
      transition: background-color 0.3s ease;
    }
    .download-btn:hover {
      background-color: #d4ac0d;
    }
  </style>
</head>
<body>

  <div class="container resume-container">
    <h1>Kasarapu Mohan Reddy</h1>
    <h5 class="text-muted">AWS DevOps Engineer</h5>
    <p>Click the image to view full screen or download below.</p>

    <a href="resume.jpg" target="_blank">
      <img src="resume.jpg" alt="Resume" class="resume-img">
    </a>

    <br>
    <a href="resume.jpg" download>
      <button class="download-btn">Download Resume</button>
    </a>
  </div>

</body>
</html>
