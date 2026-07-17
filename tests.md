---
layout: default
title: "قسم ألعاب واختبارات"
permalink: /games/
---

# 🎮 قسم ألعاب واختبارات الترفيهية

مرحباً بك في القسم الخاص بالألعاب الستاتيك والاختبارات التفاعلية الممتعة. هنا تجد كل ما هو جديد ومسلي!

## الإضافات المتاحة حالياً في هذا القسم:

<ul>
  {% for post in site.categories["ألعاب واختبارات"] %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> 
      <p style="font-size: 14px; color: #666; margin: 5px 0;">{{ post.description }}</p>
      <small style="color: #999;">تم النشر في: {{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>
