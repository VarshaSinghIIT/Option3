---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# <i class="fas fa-envelope"></i>Contact

Dr. Varsha Singh's office is on the 3rd floor in Room 402F, Block II, Indian Institute of Technology, Delhi. And her work space is in Block IV, IITD. 
{%
  include link.html
  type="email"
  icon=""
  text="vsingh@iitd.ac.in"
  tooltip=""
  link="vsingh@iitd.ac.in"
  style="button"
%}
{%
  include link.html
  type="phone"
  icon=""
  text=""
  tooltip=""
  link=""
  style="button"
%}
{%
  include link.html
  type=""
  icon=""
  text=""
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/That+St+%26+The+Other+St,+Porters+Lake,+NS+B3E+1H3,+Canada/@44.7389237,-63.3033296,20.78z/data=!4m5!3m4!1s0x4b5a31023bb02565:0xb9505694e83a53d7!8m2!3d44.7389353!4d-63.3030828"
  style="button"
%}
{:.center}

{% include section.html %}

### <i class="fas fa-mail-bulk"></i>Mailing Address

402F, Block II
Indian Institute of Technology, Delhi
New Delhi - 110016

{% capture col1 %}
{%
  include figure.html
  image="images/photo.jpg"
  caption="The Center for Wit and Sagacity"
%}
{% endcapture %}
{% capture col2 %}
{%
  include figure.html
  image="images/photo.jpg"
  caption="Department of Metaphor"
%}
{% endcapture %}
{% include two-col.html col1=col1 col2=col2 %}
