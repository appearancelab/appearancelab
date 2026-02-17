---
title: Home
nav:
  order: 0
---

<p style="text-align:center; font-size:1.6rem; font-weight:500; margin-top:10px; margin-bottom:40px;">
Investigating appearance and performance in vision and cognition.
</p>

{% include section.html %}



{%- comment -%}
1) CURRENT PROJECTS
{%- endcomment -%}

{% capture text %}
We investigate appearance and performance across a range of ongoing projects in vision science and cognition — from redundancy masking to perceptual organization and appearance.

{%
  include button.html
  link="projects"
  text="Explore current projects"
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
2) PUBLICATIONS
{%- endcomment -%}

{% capture text %}
Read peer-reviewed journal articles, conference papers, and scientific outputs from the lab.

<div style="display:flex; justify-content:center; gap:50px; margin-top:18px; flex-wrap:wrap;">

  <div>
    {%
      include button.html
      link="publications/articles"
      text="Articles"
      icon="fa-solid fa-arrow-right"
      flip=true
      style="bare"
    %}
  </div>

  <div>
    {%
      include button.html
      link="publications/abstracts"
      text="Abstracts"
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
  link="publications"
  title="Publications"
  flip=true
  text=text
%}



{%- comment -%}
3) TEAM
{%- endcomment -%}

{% capture text %}
Meet the researchers and collaborators of the Psychophysics of Appearance Laboratory.

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



{%- comment -%}
4) NEWS / TALKS (NEW SECTION — hub completeness)
{%- endcomment -%}

{% capture text %}
Follow lab news, conference presentations, invited talks, and PALab seminar series.

{%
  include button.html
  link="blog"
  text="See all news"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{% endcapture %}

{%
  include feature.html
  image="images/background 2.png"
  link="blog"
  title="News & Talks"
  flip=true
  text=text
%}
