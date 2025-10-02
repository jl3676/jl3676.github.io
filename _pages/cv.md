---
layout: page
permalink: /cv/
title: cv
nav: true
nav_order: 5
description:
cv_pdf: /assets/pdf/Jing_Jing_Li_CV.pdf
---

{% assign cv_url = page.cv_pdf | relative_url %}
{% assign home_url = '/' | relative_url %}

<script type="text/javascript">
  window.open("{{ cv_url }}", "_blank");
  window.location.href = "{{ home_url }}";
</script>

<div style="text-align: center; padding: 50px;">
  <p>Opening CV in a new tab...</p>
  <p>If the PDF doesn't open automatically, <a href="{{ cv_url }}" target="_blank">click here</a>.</p>
  <p><a href="{{ home_url }}">Return to home page</a></p>
</div>
