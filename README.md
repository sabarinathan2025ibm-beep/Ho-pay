<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Code Playground</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header class="topbar">
    <h1>Code Playground</h1>
    <div class="controls">
      <button id="themeBtn">Toggle Theme</button>
      <button id="runBtn">Run Sample</button>
    </div>
  </header>

  <main class="container">
    <section class="editor">
      <label for="code">JavaScript editor</label>
      <textarea id="code" spellcheck="false">
// Try this sample:
console.log("Hello from the playground!");
document.getElementById('output').textContent = "Output: Hello from the playground!";
      </textarea>
      <div class="actions">
        <button id="executeBtn">Execute</button>
        <button id="clearBtn">Clear</button>
      </div>
    </section>

    <section class="output">
      <h2>Output</h2>
      <pre id="output">Ready.</pre>
    </section>
  </main>

  <footer class="footer">
    <small>Save files to your Drive and serve the folder publicly to share a link.</small>
  </footer>

  <script src="script.js"></script>
</body>
</html>
