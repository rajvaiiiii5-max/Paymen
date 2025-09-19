<!DOCTYPE html>
<html lang="ne">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>German Grammar Course Levels</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      background: #f0f4f8;
      margin: 0;
    }

    h1 {
      margin-bottom: 50px;
      text-align: center;
      font-size: 2.2rem;
      color: #1e3a8a;
    }

    .level-buttons {
      display: flex;
      gap: 30px;
      flex-wrap: wrap;
      justify-content: center;
    }

    .level-buttons a {
      display: flex;
      justify-content: center;
      align-items: center;
      width: 100px;
      height: 100px;
      background: #1e3a8a;
      color: white;
      text-decoration: none;
      font-size: 1.5rem;
      font-weight: bold;
      border-radius: 50%;
      box-shadow: 0px 5px 15px rgba(0,0,0,0.3);
      transition: all 0.3s ease;
    }

    .level-buttons a:hover {
      background: #2563eb;
      transform: translateY(-5px) scale(1.1);
      box-shadow: 0px 10px 20px rgba(0,0,0,0.4);
    }

    @media (max-width: 500px) {
      .level-buttons a {
        width: 70px;
        height: 70px;
        font-size: 1.2rem;
      }
    }
  </style>
</head>
<body>

  <h1>German Grammar Course</h1>

  <div class="level-buttons">
    <a href="#A1">A1</a>
    <a href="#A2">A2</a>
    <a href="#B1">B1</a>
    <a href="#B2">B2</a>
  </div>

</body>
</html>
