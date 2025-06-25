---
layout: archive
title: "Community resources"
permalink: /resources/
author_profile: true
---

{% include base_path %}

Here are a few of the community resources that I've helped develop. Click on
the project description to check out the resource. Additional information
related to the project are available in the thumbnails below the description,
including
open-access publications or preprints <nobr>(<i class="ai ai-fw ai-open-access-square"></i>)</nobr>,
non-OA publications <nobr>(<i class="fas fa-file-pdf" aria-hidden="true"></i>;</nobr>
available for *personal use only*),
GitHub repositories <nobr>(<i class="fab fa-fw fa-github" aria-hidden="true"></i>)</nobr>,
OSF projects <nobr>(<i class="ai ai-fw ai-osf"></i>)</nobr>, and
miscellaneous information <nobr>(<b>∼</b>)</nobr>.

{% for post in site.resources%}
  {% include archive-resource.html %}
{% endfor %}
