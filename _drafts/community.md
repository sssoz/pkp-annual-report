---
heading: Community
subheading: Community makes us open<span class="text-red text-red--large">.</span>
intro: "Behind PKP is a vibrant, passionate, and international community who help to make our software better, together. Their voices and contributions are everything to us, and we endeavour to find ways to actively support, educate, and engage them."
---

{% assign data = site.data.community.you %}

### You publish <span class="text-red">open<span class="text-red--large">.</span></span>

{% assign content = data[0].content %}
{% assign img = data[0].img %}
{% assign credit = data[0].credit %}
{% include you.html content=content img=img credit=credit %}

#### [PKP 2019]

{% include placeholder-long.html %}

#### Events

PKP both offers, and attends, conferences, events, and workshops around the world. In 2019, our team was invited to present workshops in Indonesia (HEBII International Workshop for Journal Editors) and South Africa (UCT-SPARC Africa Open Access Symposium).

By far our biggest event was PKP 2019, our bi-annual International Scholarly Publishing Conference co-hosted by the Universitat Autònoma de Barcelona (UAB) November 18-22, 2019. In addition to a two-day sprint, the event included six workshops, five keynote speakers, and XX presentations attended by XX participants from XX countries.

We also held three development sprints. In May, PKP held a pre-conference sprint as part of the Library Publishing Forum at Simon Fraser University (Canada). Then in July, the University of Pittsburgh (USA) hosted a three-day sprint. Our final sprint, as mentioned above, was in Barcelona (Spain) for PKP 2019. Our thanks to each of these institutions for providing space, staff, and support. Sprints are free, fun, and interactive events for community members to brainstorm important tasks, set priorities, and work collaboratively. Participants don’t just talk about improvements either. In 2019, PKP sprints made direct and real-time contributions towards documentation, user testing, accessibility, XML, metadata, and more.

#### [PS Clients]

<ul class="stats">
  {% for stat in site.data.community.ps_clients limit:1 %}
  <li class="stat stat--featured">
    <span class="stat__value">{{ stat.value }}</span>
    <span class="stat__label">{{ stat.label }}</span>
    <p>{{ stat.description }}</p>
  </li>
  {% endfor %}
  {% for stat in site.data.community.ps_clients offset:1 %}
  <li class="stat">
    <span class="stat__value">{{ stat.value }}</span>
    <span class="stat__label">{{ stat.label }}</span>
  </li>
  {% endfor %}
</ul>

---

### You support <span class="text-red">open<span class="text-red--large">.</span></span>

{% assign content = data[1].content %}
{% assign img = data[1].img %}
{% assign credit = data[1].credit %}
{% include you.html content=content img=img credit=credit %}

#### [Contributors]

{% include placeholder-long.html %}

#### [Strategic Partners]

{% include placeholder.html %}

#### [Translation]

[contributor stats]

---

### You sustain <span class="text-red">open<span class="text-red--large">.</span></span>

{% assign content = data[2].content %}
{% assign img = data[2].img %}
{% assign credit = data[2].credit %}
{% include you.html content=content img=img credit=credit %}

#### [Development Partners]

{% include placeholder.html %}

---

### [Why do you support PKP?]

> <cite>**University of Toronto**</cite> <br/>“{% include placeholder.html %}”

{:.blockquote--centered}
> <cite>**Ubiquity**</cite> <br/>“{% include placeholder.html %}”

{:.blockquote--right}
> <cite>**SciELO**</cite> <br/>“{% include placeholder.html %}”
