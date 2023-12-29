---
title: 'test'
permalink: /test
---
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Delayed Redirect</title>
</head>
<body>
  <script>
    // Add a delay (in milliseconds) before the redirect
    const delay = 2000; // 2000 milliseconds = 2 seconds
    const destinationUrl = "https://www.google.com/";

    setTimeout(() => {
      window.location.href = destinationUrl;
    }, delay);
  </script>
</body>
</html>