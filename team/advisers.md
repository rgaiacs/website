---
layout: page
title: Board of Advisers
advisers:
---

Will be announced soon.

{% for people in page.advisers %}
<div class="people">
<div class="people-photo">
{%if people.photo %}
<img src="{{people.photo}}">
{% endif %}
</div>
<div class="people-info">
<p><strong>{{people.name}}</strong></p>
<p>{{people.description}}</p>
{% if people.website %}
<a href="{{people.website}}">
<span class="icon">{% include website-icon.html %}</span>
</a>
{% endif %}
{% if people.email %}
<a href="mailto:{{people.email}}">
<span class="icon">{% include email-icon.html %}</span>
</a>
{% endif %}
{% if people.github %}
<a href="http://github.com/{{people.github}}">
<span class="icon">{% include github-icon.html %}</span>
</a>
{% endif %}
{% if people.twitter %}
<a href="http://twitter.com/{{people.twitter}}">
<span class="icon">{% include twitter-icon.html %}</span>
</a>
{% endif %}
</div>
</div>
{% endfor %}
