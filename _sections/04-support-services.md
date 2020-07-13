---
heading: Support Services
subheading: We serve open<span class="text-red text-red--large">.</span>
intro: "The passion and expertise of our team has, since day one, been an integral part of our success. In addition to providing paid consultation and hosting services, PKP supports and serves scholarly publishing around the world through strategic projects, online engagement, documentation, and education."
highlighted: true
patterned: true
---

### Coalition Publica

Coalition Publica is a partnership between long-standing collaborators Érudit and PKP to establish a national infrastructure dedicated to the digital production and dissemination of research results in the Canadian humanities and social sciences (HSS). It is funded by two Canadian Foundation for Innovation grants: Major Science Initiative (2017-2022) and Cyberinfrastructure (2017-2020).

Coalition Publica is focussed on three key activities: **1)** developing a support program for Canadian scholarly journals in the humanities and social sciences; **2)** aligning Érudit and PKP’s technological developments to create a national production, dissemination, and research infrastructure offering a comprehensive range of scholarly publishing services to the Canadian community; and **3)** organizing research activities focused on the evolution of the scholarly publishing sector.

In 2019-2020, Coalition Publica’s national campaign was a great success: the annual objective to include 20 new journals was reached very quickly and a waiting list was established for 2021. The team also recognized the need for a holistic Digital Object Identifier (DOI) strategy, developing a Metadata Working Group in 2019 to achieve two main deliverables: **1)** a best practices guide for OJS metadata for journals, and **2)** a report to PKP and Érudit with technical recommendations to improve metadata quality in their respective systems.

### Institutional Hosting

In 2019, PKP Publishing Services piloted an Institutional Hosting package with the University of British Columbia and the Colorado Alliance of Research Libraries. Designed specifically for libraries, the package offered free and unlimited student journals along with our premium OJS hosting and support services. The idea came about upon realization that we were uniquely situated to support larger institutions, both in expertise and experience. Upon analysis, we also realized we were able to provide volume-based discounts based on size. Now offered widely, the Institutional package is available to universities and colleges who wish to have hosting support for five or more journals. Hosting is free for student and course-journals provided they have faculty representation to ensure some level of continuity.

### Community Support

As our community grows, so too does our expertise. PKP staff and community members are available online when you need help, have a question, or just want to reach out.

<article class="stats">
  {% for stat in site.data.support-services.support %}
  <div class="stat">
    <h4>{{ stat.service }}</h4>
    <span class="stat__value">{{ stat.value }}</span>
    <span class="stat__label">{{ stat.label }}</span>
  </div>
  {% endfor %}
</article>
