# for-test-01

1. Загальна структура сторінки

```html
<body>
  <header id="header"></header>
  <main>
    <section id="hero"></section>
    <section id="features"></section>
    <section id="team"></section>
  </main>
  <footer id="footer"></footer>
</body>
```

2. Логотип робити окремо від навігації


````html
<header id="header">
  <a href="./index.html"></a>
  <nav>
    <ul>
      <li>
        <a href="#hero">Studio</a>
      </li>
      <li>
        <a href="#portfolio">Portfolio</a>
      </li>
      <li>
        <a href="#contacts">Contacts</a>
      </li>
    </ul>
  </nav>
  <address>
    <ul>
      <li>
        <a href="mailto:info@devstudio.com">info@devstudio.com</a>
      </li>
      <li>
        <a href="tel:+110001111111">+11 (000) 111-11-11</a>
      </li>
    </ul>
  </address>
</header>
```

