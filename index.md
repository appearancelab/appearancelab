---
title: Home
nav:
  order: 0
---

# The Psychophysics of Appearance Laboratory

<p style="text-align:center;">
  Investigating appearance and performance in vision and cognition.
</p>

{% include section.html %}

## Highlights

{%- comment -%}
1) Current projects kutucuğu
{%- endcomment -%}
{% capture text %}
Learn more about our ongoing projects.

{%
  include button.html
  link="projects"
  text="See our current projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/logo_nobo.png"
  link="projects"
  title="Current Projects"
  text=text
%}

{%- comment -%}
2) Publications – Articles kutucuğu
{%- endcomment -%}
{% capture text %}
Read our peer-reviewed journal articles and manuscripts.

{%
  include button.html
  link="publications/articles"
  text="Browse articles"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="publications/articles"
  title="Publications – Articles"
  flip=true
  style="bare"
  text=text
%}

{%- comment -%}
3) Publications – Abstracts kutucuğu
{%- endcomment -%}
{% capture text %}
Explore our conference talks, posters, and other abstracts.

{%
  include button.html
  link="publications/abstracts"
  text="Browse abstracts"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/share.jpg"
  link="publications/abstracts"
  title="Publications – Abstracts"
  text=text
%}
