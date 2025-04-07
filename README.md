- 👋 Hi, I’m @R132116
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
R132116/R132116 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<p>&nbsp;</p>

<html>
<head>
  <title>Fast.com Web View</title>
  <style>
    html, body {
      margin: 0;
      padding: 0;
      height: 100%;
    }
    #webview {
      width: 100%;
      height: 100%;
      border: none;
    }
  </style>
</head>
<body>
  <iframe id="webview"></iframe>

  <script>
    window.onload = function() {
      var webview = document.getElementById("webview");

      function resizeWebview() {
        webview.style.height = window.innerHeight + "px";
      }

      // Resize the web view when the window is resized
      window.addEventListener("resize", resizeWebview);

      // Load the Fast.com website into the web view
      webview.src = "https://fast.com";

      // Initially resize the web view
      resizeWebview();
    };
  </script>
</body>
</html>
