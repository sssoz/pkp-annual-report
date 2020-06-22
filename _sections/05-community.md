---
heading: Community
subheading: Community makes us open<span class="text-red text-red--large">.</span>
intro: "How does the world’s most widely used free and open source journal publishing platform remain open? The answer is easy: <strong>you</strong>. Behind PKP is a vibrant, passionate, and international community of contributors who help to make our software better, together."
---

### [Some heading here]

{:.blockquote--patterned}
> “{% include placeholder.html %}” <cite>&ndash; **Allan Bell** <br/>[title, institution]</cite>

---

{% assign data = site.data.community.you %}

### You publish <span class="text-red">open<span class="text-red--large">.</span></span>

{% assign content = data[0].content %}
{% assign img = data[0].img %}
{% assign credit = data[0].credit %}
{% include you.html content=content img=img credit=credit %}

#### [PKP 2019]

{% include placeholder-long.html %}

#### [Library Publishing]

{% include placeholder.html %}

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

#### [SCOSS]

{% include placeholder-long.html %}

#### [Development Partners]

{% include placeholder.html %}

---

### [Why do you support PKP?]

> <cite>**University of Toronto**</cite> <br/>“{% include placeholder.html %}”

{:.blockquote--centered}
> <cite>**Ubiquity**</cite> <br/>“{% include placeholder.html %}”

{:.blockquote--right}
> <cite>**SciELO**</cite> <br/>“{% include placeholder.html %}”
