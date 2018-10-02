---
title: Home
layout: default
date: 25-09-2018
---

<p>Typing some text here to see the results of css.</p>

{% capture lorem %}
<p><strong>Strong Paragraph \_o_(>.<)_o_/</strong></p>

<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras ultricies quis turpis sit amet venenatis. Mauris
    euismod imperdiet nisl, nec imperdiet dolor egestas sed. Pellentesque auctor felis sit amet turpis accumsan
    volutpat. Pellentesque vestibulum congue ex eu tempor. Ut in urna eros. Donec id sapien interdum, consequat risus
    non, pellentesque turpis. Nulla a eros ac nisi mattis ullamcorper. Maecenas eget malesuada sapien, sed mollis diam.</p>
{% endcapture %}

{% for i in (2..6) %}
  <h{{ i }}>Header {{ i }}</h{{ i }}>
  <p>Some dummy text haHAA</p>
{% endfor %}

<h2>Code block</h2>

```py
def hello_world():
    print("hello world!")


if __name__ == "__main__":
    hello_world()

```

{{ lorem }}
