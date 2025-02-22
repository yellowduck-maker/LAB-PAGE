---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

北京市海淀区颐和园路5号(5 yiheyuan road, haidian district, Beijing)\\
北京大学 (Peking University), 100871\\
北京大学理科2号楼2228室(Room 2228, Science Building #2)

{%
  include button.html
  type="email"
  text="janechenjing@pku.edu.cn"
  link="janechenjing@pku.edu.cn"
%}
{%
  include button.html
  type="phone"
  text="86-10-62756824"
  link="86-10-62756824"
%}
{%
  include button.html
  type="personal page"
  text="page"
  tooltip="personal page"
  link="https://sai.pku.edu.cn/info/1362/2249.htm"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
