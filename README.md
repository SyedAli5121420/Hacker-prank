<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>System Hack</title>
  <style>
    body {
      background: black;
      color: lime;
      font-family: monospace;
      padding: 20px;
    }
    .terminal {
      max-width: 600px;
      margin: auto;
      white-space: pre-wrap;
    }
  </style>
</head>
<body>
  <div class="terminal" id="terminal"></div>
  <script>
    const lines = [
      "Initializing Hack.exe...",
      "Connecting to server 192.168.1.1...",
      "Bypassing firewall...",
      "Access granted. Downloading files...",
      "Installing rootkit...",
      "Encrypting files...",
      "Self-destruct sequence initiated. 😱",
      "Data extracted successfully "
    ];

    let index = 0;
    function typeLine() {
      if (index < lines.length) {
        const terminal = document.getElementById("terminal");
        terminal.textContent += lines[index] + "\n";
        index++;
        setTimeout(typeLine, 1000);
      }
    }
    typeLine();
  </script>
</body>
</html>

</body>
</html>
