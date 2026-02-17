---
title: Home
nav:
  order: 0
---

<p style="text-align:center; font-size:1.5rem; font-weight:500; margin-top:20px;">
  Investigating appearance and performance in vision and cognition.
</p>

{% include section.html %}

{%- comment -%} 1 — ABOUT {%- endcomment -%}

{% capture text %}
Learn more about the Psychophysics of Appearance Laboratory, our mission, and research focus.

{% include button.html
  link="about"
  text="About the lab"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{% endcapture %}

{% include feature.html
  image="images/background 1-1.png"
  link="about"
  title="About"
  flip=false
  text=text
%}



{%- comment -%} 2 — TEAM {%- endcomment -%}

{% capture text %}
Meet the members of the Psychophysics of Appearance Laboratory.

{% include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{% endcapture %}

{% include feature.html
  image="images/logo_nobo.png"
  link="team"
  title="Our Team"
  flip=false
  text=text
%}



{%- comment -%} 3 — PUBLICATIONS {%- endcomment -%}

{% capture text %}
Read our peer-reviewed journal articles, conference contributions, and other publications from the lab.

<div style="display:flex; justify-content:center; gap:40px; margin-top:20px; flex-wrap:wrap;">

{% include button.html
  link="publications/articles"
  text="Articles"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% include button.html
  link="publications/abstracts"
  text="Abstracts"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

</div>
{% endcapture %}

{% include feature.html
  image="images/background 1-1.png"
  link="publications/articles"
  title="Publications"
  flip=false
  text=text
%}



{%- comment -%} 4 — CURRENT PROJECTS {%- endcomment -%}

{% capture text %}
We investigate appearance and performance across a range of ongoing projects in vision science and cognition.

{% include button.html
  link="projects"
  text="Explore current projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{% endcapture %}

{% include feature.html
  image="images/RM illustration-2.jpg"
  link="projects"
  title="Current Projects"
  flip=false
  text=text
%}



{%- comment -%} 5 — NEWS / TALKS {%- endcomment -%}

{% capture text %}
Follow lab news, conference presentations, invited talks, and PALab seminar series.

{% include button.html
  link="blog"
  text="See all news"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{% endcapture %}

{% include feature.html
  image="images/background 2.png"
  link="blog"
  title="News & Talks"
  flip=false
  text=text
%}



{%- comment -%} 6 — CONTACT {%- endcomment -%}

{% capture text %}
Get in touch for collaborations, visits, student opportunities, or general inquiries.

{% include button.html
  link="contact"
  text="Contact us"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{% endcapture %}

{% include feature.html
  image="images/background 2.png"
  link="contact"
  title="Contact"
  flip=false
  text=text
%}
