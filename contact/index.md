---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our group is always looking for outstanding you! 
We recruit students with strong independent ability all year round, including master's candidates and doctoral candidates! 
We can provide excellent conditions to help you realize your pursuit.

{%
  include button.html
  type="email"
  text="Email"
  link="wangg@cqu.edu.cn"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.cme.cqu.edu.cn/"
%}

{% include section.html %}


{% capture col2 %}

{%
  include figure.html
  image="images/cqu.png"
  caption=""
%}

{% endcapture %}

{% include cols.html col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Let’s find something 
meaningful together!
{% endcapture %}

{% capture col2 %}

{% endcapture %}

{% capture col3 %}
Advanced equipment, excellent team! Join us!
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
