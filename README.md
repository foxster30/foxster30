---
layout: default
---

# Selamat Datang di Profil Saya 👋

Berikut adalah postingan dan proyek terbaru saya:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.date | date: "%d %B %Y" }} - {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

---
[Kembali ke GitHub](https://github.com/foxster30)
