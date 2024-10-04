---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Email is best!

{%
  include button.html
  type="email"
  text="gkacherg@asu.edu"
  link="gkacherg@asu.edu"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/Faculty%2FAdministration+Building/@33.608785,-112.1619686,16z/"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/logo.jpg"
  caption="Lab Logo - Concept 1"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/logo2.jpg"
  caption="Lab Logo - Concept 2"
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
