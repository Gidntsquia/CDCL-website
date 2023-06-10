---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Dr. Derek A. Paley
Director, Maryland Robotics Center
Director, UMD Autonomous Micro Air Vehicle Team
Principal Investigator, AI and Autonomy for Multi-Agent Systems (ArtIAMAS)
Director, Collective Dynamics and Control Laboratory
Willis H. Young Jr. Professor of Aerospace Engineering Education
Department of Aerospace Engineering and Institute for Systems Research, University of Maryland
Office: 3150 Martin Hall, 4298 Campus Dr., College Park, MD 20742
(301) 405-5757 | (301) 314-0213 (fax)
Lab: 3247 Kim Engineering Building, 8228 Paint Branch Dr.
dpaley@umd.edu | http://cdcl.umd.edu

{%
  include button.html
  type="email"
  text="jane@smith.com"
  link="jane@smith.com"
%}
{%
  include button.html
  type="phone"
  text="(301) 405-5757 "
  link="+1-301-405-5757"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://goo.gl/maps/BxeH5JCDhFsvvnuUA"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/derek_paley.jpg"
  caption="Derek Paley, Director of the Lab"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/kim_building.jpg"
  caption="Our Lab"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

