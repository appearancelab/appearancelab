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
1) CURRENT PROJECTS
{%- endcomment -%}
{% capture text %}

We investigate appearance and performance in a range of ongoing projects in vision and cognition.

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
  image="images/background 2.png"
  link="projects"
  title="Current Projects"
  text=text
%}

{%- comment -%}
2) PUBLICATIONS (ARTICLES + ABSTRACTS)
{%- endcomment -%}
{% capture text %}

Read our peer-reviewed journal articles, conference contributions, and other publications from the lab.

<div style="display:flex; justify-content:center; gap:30px; margin-top:20px; flex-wrap:wrap;">

  <div>
    {%
      include button.html
      link="publications/articles"
      text="See our published articles"
      icon="fa-solid fa-arrow-right"
      flip=true
      style="bare"
    %}
  </div>

  <div>
    {%
      include button.html
      link="publications/abstracts"
      text="See our published abstracts"
      icon="fa-solid fa-arrow-right"
      flip=true
      style="bare"
    %}
  </div>

</div>

{% endcapture %}

{%
  include feature.html
  image="images/background 1-1.png"
  link="publications/articles"
  title="Publications"
  text=text
%}

{%- comment -%}
3) TEAM
{%- endcomment -%}
{% capture text %}

Meet the members of the Psychophysics of Appearance Laboratory.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/logo_nobo.png"
  link="team"
  title="Our Team"
  text=text
%}
