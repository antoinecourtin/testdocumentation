# Accueil doc perso Antoine

en cours

## Pages dans le repo

<!-- prettier-ignore-start -->

| source          | link                                                           |
| --------------- | -------------------------------------------------------------- |
{% for page in site.pages -%}
| {{ page.path }} | [{{ page.url | relative_url }}]({{ page.url | relative_url }}) |
{% endfor %}

<!-- prettier-ignore-end -->

## ressources 

https://jekyll-rtd-theme.rundocs.io


## The license

The theme is available as open source under the terms of the MIT License
