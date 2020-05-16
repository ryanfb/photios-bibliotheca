---
layout: default
---

<span style="float:right;">[View this project on GitHub](https://github.com/ryanfb/photios-bibliotheca)</span>
<div class="clear"></div>
{% capture readme %}
{% include_relative README.md %}
{% endcapture %}

{{ readme | remove_first: "# photios-bibliotheca" }}
