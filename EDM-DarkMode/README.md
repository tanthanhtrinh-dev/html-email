# 🌒 Dark Mode Email
[source][]
```html
<html>
  <head>
    <meta name="color-scheme" content="light dark">
    <meta name="supported-color-schemes" content="light dark">
    <style>
      :root {
        color-scheme: light dark;
        supported-color-schemes: light dark;
      }
      body {
        background-color: #eee;
        color: #111;
      }
      @media (prefers-color-scheme: dark) {
        body {
          background-color: #111;
          color: #eee;
        }
      }
    </style>
  </head>
  <body>
    🖖 Hello Dark Mode!
  </body>
</html>
```