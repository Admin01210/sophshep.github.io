<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>PUBG Mobile Tournament Registration</title>
  <style>
    body {
      background-color: #0e0e0e;
      font-family: 'Segoe UI', sans-serif;
      color: white;
      padding: 30px;
    }

    .container {
      max-width: 400px;
      margin: auto;
      background-color: #1a1a1a;
      padding: 25px;
      border-radius: 10px;
    }

    h2 {
      text-align: center;
      margin-bottom: 20px;
      color: #e91e63;
    }

    label {
      display: block;
      margin-top: 15px;
      font-size: 14px;
      color: #ccc;
    }

    input {
      width: 100%;
      padding: 10px;
      border-radius: 6px;
      margin-top: 5px;
      border: none;
      background-color: #2a2a2a;
      color: white;
    }

    input:disabled {
      background-color: #1f1f1f;
      color: #666;
    }

    button {
      margin-top: 25px;
      padding: 12px;
      width: 100%;
      background-color: #e91e63;
      border: none;
      color: white;
      font-size: 16px;
      border-radius: 6px;
      cursor: pointer;
    }

    button:disabled {
      background-color: #444;
      cursor: not-allowed;
    }
  </style>
</head>
<body>
  <div class="container">
    <h2>Player Registration</h2>
    <form>
      <label>Region</label>
      <input type="text" value="South Asia" disabled>

      <label>Email</label>
      <input type="email" value="abdurrahman6605@gmail.com" required>

      <label>Discord Username</label>
      <input type="text" value="handsome06153" required>

      <label>Nickname</label>
      <input type="text" value="HEREisHandsome" disabled>

      <label>UID</label>
      <input type="text" value="5397871241" disabled>

      <label>Current Rank</label>
      <input type="text" value="Ace Dominator" disabled>

      <button type="submit" disabled>Submit</button>
    </form>
  </div>
</body>
</html>
