---
layout: post
title:  "Incluindo um vídeo"
# date:   2016-06-04 13:50:39
categories: historia
youtubeurl: "https://www.youtube.com/watch?v=VQdV_lqzxOI"
---



Para exibir um vídeo basta usar o comando de um dos modos:

## Modo 1

```
{% raw %}
 {% youtube "https://www.youtube.com/watch?v=ho8-vK0L1_8" %}
{% endraw %}
```

## Modo 2 - using variables/front matter

```
{% raw %}
{% youtube page.youtubeurl %}
{% endraw %}
```

# Resultado

{% youtube page.youtubeurl %}

# Mais informações

> warning "Mais informações sobre o "Jekyll-Youtube"
> Saiba mais em [Jekyll-Youtube](https://github.com/dommmel/jekyll-youtube).


> info "Mais informações sobre o "Jekyll-Youtube"
> Saiba mais em [Jekyll-Youtube](https://github.com/dommmel/jekyll-youtube).



> note "Mais informações sobre como criar estas caixas"
> Saiba mais em [premonition](https://github.com/lazee/premonition).



> error "Mais informações sobre como criar estas caixas"
> Saiba mais em [premonition](https://github.com/lazee/premonition).