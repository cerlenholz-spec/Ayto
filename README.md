<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1,viewport-fit=cover" />
  <title>AYTO – Matches & Nights Tracker</title>

  <!-- PWA META -->
  <link rel="manifest" href="manifest.json">
  <meta name="theme-color" content="#7aa2ff">
  <link rel="apple-touch-icon" href="icon-192.png">

  <script>
    if ("serviceWorker" in navigator) {
      navigator.serviceWorker.register("service-worker.js");
    }
  </script>

  <!-- dein CSS / Styles bleiben hier -->
  <style>
    /* … dein bisheriges CSS … */
  </style>
</head>
<body>
  <!-- … dein bisheriges HTML (Board, Matrix, Nights etc.) … -->

  <script>
    // … dein bisheriges JavaScript …
  </script>
</body>
</html>