---
title: "Jupyter Notebook"
layout: notebook
---
<head>
    <script>
      function resizeIframe(obj) {
        obj.style.height = obj.contentWindow.document.body.scrollHeight + 'px';
      }
    </script>
</head>

<h4><a href="../bond_screen.html">Back to screen list</a></h4>

{% raw %}
<iframe src="bond_screen_v3.html"
    style="position: absolute; height: 100%; border: none"
    onload="resizeIframe(this)"
    sandbox="allow-same-origin allow-scripts"
    width="100%"
    height="100%"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>
{% endraw %}
