---
layout: page
title: Events
permalink: /events
---


<i class="fa fa-envelope" aria-hidden="true"></i> For posting upcoming conferences to this list, send email to <a href="mailto:smbpdee@gmail.com">smbpdee@gmail.com</a>.

<div style="padding: 0 0 0 10%;">
{% for pp in site.data.conferences %}
    {% include event-template.html %}
{% endfor %}
</div>

<i class="fa fa-exclamation-circle" aria-hidden="true"></i> <b>Disclaimer:</b> We are not involved in the organization of any conferences mentioned below.
