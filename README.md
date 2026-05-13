<!DOCTYPE html>
<html>
<head>
  <script>
    var internal = "instagram://user?username=leftunsaid.mp3";
    var fallback = "https://instagram.com/leftunsaid.mp3";

    // Try to open internal link
    window.location = internal;

    // If it fails, redirect to fallback after 2 seconds
    setTimeout(function() {
      window.location = fallback;
    }, 2000);
  </script>
</head>
<body>
  <p>Opening app... <a href="instagram://user?username=leftunsaid.mp3">Click here if nothing happens</a></p>
</body>
</html>
