---
layout: page
title: History of Staffs, Officers and Directors
teams:
  -
    year: 2015
    staffs:
    officers:
    - name: Deyan Ginev
      role: Secretary
    - name: Michael Kohlhase
      role: President
    - name: Raniere Silva
      role: Treasurer
    - name: Frédéric Wang
      role: Vice-President
    directors:
    - name: Deyan Ginev
    - name: Michael Kohlhase
    - name: Moritz Schubotz
    - name: Raniere Silva
    - name: Frédéric Wang
---

{% for team in page.teams %}
<h2>{{team.year}}</h2>
{% if team.staffs %}
<h3>Staffs</h3>
<ul>
{% for staff in team.staffs %}
<li>{{staff.name}}, {{staff.role}}</li>
{% endfor %}
</ul>
{% endif %}
{% if team.officers %}
<h3>Officers</h3>
<ul>
{% for officer in team.officers %}
<li>{{officer.name}}, {{officer.role}}</li>
{% endfor %}
</ul>
{% endif %}
{% if team.directors %}
<h3>Directors</h3>
<ul>
{% for director in team.directors %}
<li>{{director.name}}</li>
{% endfor %}
</ul>
{% endif %}
{% endfor %}
