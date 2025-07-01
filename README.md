**QUESTION :**

    Create a Page with Meta Tags and Favicon. Add <meta> tags for SEO and link a favicon to the tab.

**CODE :**

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <meta name="description" content="Centered and simple Django page with favicon." />
  <meta name="keywords" content="Django, HTML, Meta Tags, Favicon, Simple Page" />
  <meta name="author" content="Srisha" />

  <link rel="icon" href="{% static 'images/favicon.ico' %}" type="image/x-icon" />

  <style>
    body {
      background-color: #e8f4fc;
      font-family: sans-serif;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      color: #222;
      text-align: center;
    }

    h1 {
      color: #005b99;
      margin-bottom: 10px;
    }

    p {
      font-size: 16px;
    }

    footer {
      position: absolute;
      bottom: 20px;
      font-size: 14px;
      color: #666;
    }
  </style>

  <title>{% block title %}Simple Centered Page{% endblock %}</title>
</head>
<body>

  <h1>Hello from Django</h1>
  <p>This is a simple, centered page with soft colors and a favicon.</p>

  <footer>Made by Srisha</footer>

</body>
</html>
```

**OUTPUT :**
![alt text](Output.png)
