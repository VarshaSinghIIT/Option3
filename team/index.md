---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team



{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
%}


{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd"
%}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: programmer"
%}
{:.center}



{% include section.html %}

## Join

No positions available now

## Funding

Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html
  style="square"

  image1="images/DST.png"
  link1=""
  tooltip1="Department of Science and Technology"

  image2="images/IIT.png"
  link2=""
  tooltip2="Indian Institute of Technology"

  
%}
