<!DOCTYPE html>
<html>
<head>
  <title>Locked by Xyn</title>
  <style>
    body {
      background-color: black;
      color: red;
      text-align: center;
      margin-top: 50px;
      font-family: monospace;
    }
    input, button {
      padding: 10px;
      margin: 10px;
    }
  </style>
</head>
<body>
  <h1>Your phone locked by: Xyn</h1>
  <p>This phone is locked by: Xyn</p>
  <p>Team: Black Hat Xyn</p>

  <input type="password" id="pass" placeholder="Enter password">
  <br>
  <button onclick="check()">Unlock</button>

  <script>
    function check() {
      const p = document.getElementById("pass").value;
      if (p === "xyn123") {
        alert("Unlocked!");
      } else {
        alert("Wrong password!");
      }
    }
  </script>
</body>
</html>
