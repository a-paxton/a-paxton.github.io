---
layout: archive
title: "Miscellany"
permalink: /miscellany/
author_profile: true
---

{% include base_path %}

## Helpful work management resources

* **[Workona](https://workona.com/)**:
  I can't say enough amazing things about Workona. If you're anything like me,
  you constantly keep dozens or hundreds of tabs open about any number of
  separate tasks you're doing at any given time. Workona is a fabulous tab
  management tool that I can't recommend highly enough. (With immense thanks
  to [Theo Rhodes](https://www.oswego.edu/psychology/content/theo-rhodes) for
  the recommendation.)
* **[Toggl](http://toggl.com/)**:
  I find that one of the biggest hurdles to productivity is first knowing how
  you are spending your time. Toggl is an easy-to-use tool that can help you
  figure out what you're doing day-to-day at whatever level of granularity you'd
  like.
* **[Spoonflower](https://blog.spoonflower.com/2018/06/how-to-design-a-fabric-research-poster-with-canva/)**:
  If you've been curious about cloth posters but haven't been interested in
  dropping 100 USD or more for one, try out Spoonflower. They're a fabric-printing
  service that easily accommodates research poster needs. Posters tend to run
  about 20 USD---and with rush shipping for 25 USD, it's still cheaper than most
  paper poster-printing services.

***

## Educational resources

* **[*R for Psychological Science* (Danielle Navarro)](https://psyr.djnavarro.net/index.html)**:
  If you're looking for a friendly way to learn R, I cannot recommend this
  resource highly enough. I've been using it in my lab since spring 2020 as a
  general-purpose introduction for R in our domain.

***

## Supplementary material

Here's some additional information from various publications. Click on the
relational operator <nobr>(<b>∼</b>)</nobr> to access the additional
information. Links to the relevant paper (either 
open-access <nobr><i class="ai ai-fw ai-open-access-square"></i></nobr> or 
not <nobr><i class="fas fa-file-pdf" aria-hidden="true"></i></nobr>; provided for
**personal use only**) are given. Where applicable, links to 
GitHub repositories <nobr>(<i class="fab fa-fw fa-github" aria-hidden="true"></i>)</nobr> and 
OSF projects <nobr>(<i class="ai ai-fw ai-osf"></i>)</nobr> that were instrumental in the related
material are also provided.

{% for post in site.miscellany %}
  {% include archive-single-cv.html %}
{% endfor %}
