---
heading: Community
subheading: Community makes us open<span class="text-red text-red--large">.</span>
intro: "How does the world’s most widely used free and open source journal publishing platform remain open? The answer is easy: <strong>you</strong>. Behind PKP is a vibrant, passionate, and international community of contributors who help to make our software better, together."
---

### [Some heading here]

{:.blockquote--patterned}
> “{% include placeholder.html %}” <cite>&ndash; **Allan Bell** <br/>[title, institution]</cite>

---

### You publish <span class="text-red">open<span class="text-red--large">.</span></span>

{:.colour-bg}
{% include placeholder-short.html %}

#### [PKP 2019]

{% include placeholder-long.html %}

#### [Library Publishing]

{% include placeholder.html %}

#### [PS Clients]

<article class="stats">
{% for stat in site.data.community.ps_clients limit:1 %}
<div class="stat">
  <span class="stat__value">{{ stat.value }}</span>
  <span class="stat__label">{{ stat.label }}</span>
</div>
{% endfor %}
</article>

<article class="stats">
  {% for stat in site.data.community.ps_clients offset:1 %}
  <div class="stat">
    <span class="stat__value">{{ stat.value }}</span>
    <span class="stat__label">{{ stat.label }}</span>
  </div>
  {% endfor %}
</article>

---

### You support <span class="text-red">open<span class="text-red--large">.</span></span>

{:.colour-bg}
{% include placeholder-short.html %}

#### [Contributors]

{% include placeholder-long.html %}

#### [Strategic Partners]

{% include placeholder.html %}

#### [Translation]

[contributor stats]

---

### You sustain <span class="text-red">open<span class="text-red--large">.</span></span>

{:.colour-bg}
{% include placeholder-short.html %}

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
