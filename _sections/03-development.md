---
heading: Software
subheading: We develop open<span class="text-red text-red--large">.</span>
intro: "For more than twenty years, PKP has been developing open infrastructure that improves and adapts with the changing scholarly publishing ecosystem. We believe that scholarship is best when it is diverse and global, and we build software to support those aims."
patterned: true
---

### Open Preprint Systems

In 2018, PKP announced a working partnership with SciELO to build the open source software necessary to host preprint servers. The requirements were clear: they needed a preprint server that was fully operable with OJS and could meet the decentralized, multilingual, and multidisciplinary needs of their network. With specifications and seed funding from SciELO, along with a generous donation from a Stanford University donor, Open Preprint Systems (OPS) was developed and released in English, Spanish, and Portuguese on February 28, 2020 alongside OJS/OMP 3.2.

OPS joins Open Monograph Press (OMP) and OJS as applications built using the PKP Web Application Library (PKP-WAL). Like all PKP software, OPS can be easily installed with basic infrastructure, is portable, and uses a plugin architecture to enable customization. Those familiar with OJS and OMP will recognize built-in support for a wide array of features, including multilingualism. Because it shares many words with OJS, when released, OPS was also partially available in an additional 15 languages.

The rise of preprints represents another element in the broader move toward open science. It is still early days for OPS, but we look forward to seeing how, like OJS, this software will adapt and grow to meet the needs of scholars around the world.

{:.blockquote--centered .blockquote--patterned}
> “PKP products build affordable state of art innovative open science research communication infrastructure worldwide. SciELO Network operation is highly dependent on OJS and more recently on OPS. We are proud to partner with PKP.” <cite>&ndash; **Abel Packer**  <br/>Director, SciELO Network</cite>

### Web Accessibility Audit

The release of OJS 3 in 2016 included significant user interface/user experience (UI/UX) improvements. It was also PKP’s first efforts towards making OJS accessible. In May 2019, as a follow-up to this work, community members at PKP’s SFU Sprint developed a roadmap to help guide PKP towards further compliance with web accessibility standards. One of the major recommendations was to conduct an in-depth accessibility audit on OJS. In 2019, an external vendor was contracted to evaluate the current state of OJS’ public reader interface for compliance with accessibility standards. The evaluation included a combination of automated tests and manual assessment done by people with distinct technologies and disabilities. Based on the results, PKP is now focussing its remediation efforts on OJS’ default theme. This work will not only benefit OJS, but by focusing on the default theme (part of the PKP-WAL), has implications for OMP and OPS as well.

### Translation

In January 2020, PKP began using Weblate, “[a web tool designed to ease translating for both developers and translators](https://translate.pkp.sfu.ca/engage/ojs/)” to translate PKP software. Since making this change, we have had a huge increase in translation contributions. To date, we have 159 active Weblate users. 

The translation project for OJS currently contains:

<article class="stats">
  {% for stat in site.data.development.translation %}
  <div class="stat">
    <span class="stat__value">{{ stat.value }}</span>
    <span class="stat__label">{{ stat.label }}</span>
  </div>
  {% endfor %}
</article>
