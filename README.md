<!DOCTYPE html>
<html>
<head>
  <script>
    var internal = "your-internal-uri-here";
    var fallback = "https://dgdfgdg.com";

    // Try to open internal link
    window.location = internal;

    // If it fails, redirect to fallback after 2 seconds
    setTimeout(function() {
      window.location = fallback;
    }, 2000);
  </script>
</head>
<body>
  <p>Opening app... <a href="https://dgdfgdg.com">Click here if nothing happens</a></p>
</body>
</html>
