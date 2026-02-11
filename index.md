---
title: Home
nav:
  order: 0
---

<p style="text-align:center;">
  Investigating appearance and performance in vision and cognition.
</p>

{% include section.html %}


{%- comment -%}
1) CURRENT PROJECTS — image left, text right
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
  image="images/RM illustration-2.jpg"
  link="projects"
  title="Current Projects"
  flip=false
  text=text
%}



{%- comment -%}
2) PUBLICATIONS — image right, text left
{%- endcomment -%}

{% capture text %}
Read our peer-reviewed journal articles, conference contributions, and other publications from the lab.

<div style="display:flex; justify-content:center; gap:40px; margin-top:20px; flex-wrap:wrap;">

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
  flip=true
  text=text
%}



{%- comment -%}
3) TEAM — image left, text right
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
  flip=false
  text=text
%}
