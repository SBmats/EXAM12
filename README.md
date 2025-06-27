<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Start Quiz</title>
    <style>
      body {
        font-family: sans-serif;
        background: #f0f0f0;
        display: flex;
        align-items: center;
        justify-content: center;
        height: 100vh;
        margin: 0;
      }
      button {
        padding: 20px 40px;
        font-size: 22px;
        border: none;
        background: #007bff;
        color: white;
        border-radius: 8px;
        cursor: pointer;
        transition: background 0.3s;
      }
      button:hover {
        background: #0056b3;
      }
    </style>
  </head>
  <body>
    <button onclick="location.href='quiz_with_result_report.html'">
      Start Quiz
    </button>
  </body>
</html>
