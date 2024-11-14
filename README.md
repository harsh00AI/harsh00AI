<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Will You Be Mine?</title>
  <style>
    body {
      background-color: #fbe8e7;
      font-family: Arial, sans-serif;
      color: #4a4a4a;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }
    .container {
      text-align: center;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0px 10px 20px rgba(0, 0, 0, 0.1);
      background-color: #ffffff;
    }
    h1 {
      color: #ff6b6b;
      font-size: 2.5em;
    }
    p {
      font-size: 1.2em;
      margin-top: 20px;
      color: #333;
    }
    .btn-yes, .btn-no {
      margin: 15px;
      padding: 15px 30px;
      font-size: 1.2em;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      color: #ffffff;
    }
    .btn-yes {
      background-color: #ff6b6b;
    }
    .btn-no {
      background-color: #bbbbbb;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Hi Siddhi,</h1>
    <p>I’ve wanted to tell you something for a while now. Every moment spent with you feels so special. I can't help but wonder: will you be mine?</p>
    <button class="btn-yes" onclick="alert('Yay! You said yes!')">Yes</button>
    <button class="btn-no" onclick="alert('Oh no! Maybe someday?')">No</button>
  </div>
</body>
</html>
