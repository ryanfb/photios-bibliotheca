---
layout: default
---

<span style="float:right;">[View this project on GitHub](https://github.com/dcthree/antigrapheus)</span>

{% capture readme %}
{% include_relative README.md %}
{% endcapture %}

{{ readme | remove_first: "# photios-bibliotheca" }}
