---
layout: "challengecards"
title: "Challenges - Inspire Helsinki 2019 Data Challenge"
description: "Beat the other teams on a Data Challenge of your choosing in September 2019"
page: "challenges"
---
# Inspire Helsinki 2019 Data Challenges

The four challenges below were selected from the proposals received for the call for challenges. The challenge teams [sign up](./signup.html) before 16 August to solve one of these challenges during September 2019. The winners are awarded at the [Inspire Helsinki 2019](https://www.inspire-helsinki-2019.fi/) event in October.

See the [about](/about.html) and [awards & rules](/rules.html) pages for more information.

## Webinars

Each challenge will hold a webinar to present their challenge. Register to learn more!
<ul>
{% for challenge in site.data.challenges %}
{% if challenge.webinar %}
<li>{{challenge.title }} - {% if challenge.webinar.registration %}<a href="{{challenge.webinar.registration}}">{% endif %}{{challenge.webinar.time}}{% if challenge.webinar.registration %}</a>{% endif %}</li>
{% endif %}
{% endfor %}
</ul>
