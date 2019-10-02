---
layout: default
---

<body>
  <div class="index-wrapper">
    <div class="aside">
      <div class="info-card">
        <h1>Bonjour</h1>
        <a href="http://alaeri.asia.wiki.org" target="_blank"><img src="https://htmlcss.fandom.com/favicon.ico" alt="" width="25"/></a>
        <a href="https://www.linkedin.com/in/emmanuel-requier-b673786" target="_blank"><img src="http://linkedin.com/favicon.ico" alt="" width="22"/></a>
        <a href="https://medium.com/@alaeri" target="_blank"><img src="https://medium.com/favicon.ico" alt="" width="22"/></a>
      </div>
      <div id="particles-js"></div>
    </div>

    <div class="index-content">
      <ul class="artical-list">
        {% for post in site.categories.blog %}
        <li>
          <a href="{{ post.url }}" class="title">{{ post.title }}</a>
          <div class="title-desc">{{ post.description }}</div>
        </li>
        {% endfor %}
      </ul>
    </div>
  </div>
</body>
