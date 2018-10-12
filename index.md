---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
#variável array tags
tags:
    - C#
    - PowerShell
    - HTML
    - CSS
    - Javascript
#variável HelloWorld
helloworld: Hello World!
---

<h1>page.helloworld</h1>

{% for tag in page.tags %}
    <h2>{{tag}}</h2>
{% endfor %}

<h3>{{include}}</h3>
