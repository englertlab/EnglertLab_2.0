---
title: Team
nav:
  order: 3
  tooltip: About our team
carousels:
  - images: 
    - image: /images/funding/ats_new.webp
    - image: /images/funding/csctr_new.webp
    - image: /images/funding/feds_new.webp
    - image: /images/funding/nhlbi_new.webp
    - image: /images/funding/osucom_new.webp
---

<h5>Team</h5>

The Englert Lab is comprised of six individuals ranging from undergraduate to medical fellows. Click on their names to meet them, learn about their work in the Englert lab, and more!

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="group: researcher" %}

{% include section.html %}

<h5>Alumni</h5>

{% include list.html data="members" component="portrait" filters="group: alumni" %}

{% include section.html background="images/background.jpg" dark=true %}

## Funding

Our work is made possible by funding from the following organizations.
{:.center}

{% include carousel.html height="25" unit="%" duration="10" number="1" %}

{:.center}