---
layout: post
title:  "Formas de incluir uma imagem."
# date:   2016-06-04 13:50:39
categories: historia
---

Formas de incluir uma imagem.

# Como?

```
{% raw %}
![first image]({{"/static/img/screenshot-post-page.png" | prepend: site.baseurl}})
{% endraw %}
```

# Resultado
![first image]({{"/static/img/screenshot-post-page.png" | prepend: site.baseurl}})