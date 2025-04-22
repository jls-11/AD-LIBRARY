# AD-library
### 📁 Download

[➡️ Jetzt den Ordner `caller` als ZIP herunterladen](https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/jls-11/AD-library/tree/main/caller)

[➡️ Jetzt den Ordner `ambient sounds` als ZIP herunterladen](https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/jls-11/AD-library/tree/main/ambient%20sounds)



<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <title>GIF Links mit Kopierbutton</title>
  <style>
    .gif-block {
      margin-bottom: 1rem;
    }
    .copy-button {
      margin-left: 1rem;
      padding: 4px 8px;
      font-size: 0.9rem;
      cursor: pointer;
    }
    code {
      background: #f0f0f0;
      padding: 4px 6px;
      border-radius: 4px;
    }
  </style>
</head>
<body>

<h2>🎞️ GIF Links mit Trigger</h2>

<div class="gif-block">
  <code id="gif0">https://link.com/gif0.gif</code>
  <button class="copy-button" onclick="copyToClipboard('gif0')">📋 Copy</button>
</div>

<div class="gif-block">
  <code id="gif1">https://link.com/gif1.gif</code>
  <button class="copy-button" onclick="copyToClipboard('gif1')">📋 Copy</button>
</div>

<script>
function copyToClipboard(id) {
  const text = document.getElementById(id).innerText;
  navigator.clipboard.writeText(text).then(() => {
    alert("Kopiert: " + text);
  });
}
</script>

</body>
</html>

