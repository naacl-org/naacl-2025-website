---
title: Sponsors
layout: single
permalink: /sponsors/
sidebar: false
toc: true
toc_sticky: true
toc_label: "&nbsp;Sponsorship Tier"
platinum:
  - url: https://toloka.ai/
    image_path: /assets/images/logos/toloka.png
    alt: Toloka AI
    title: Toloka AI
  - url: https://research.adobe.com/
    image_path: /assets/images/logos/Adobe.jpg
    alt: Adobe
    title: Adobe
  - url: https://megagon.ai/
    image_path: /assets/images/logos/Megagon.png
    alt: Megagon
    title: Megagon
  - url: https://home.baidu.com/home/index
    image_path: /assets/images/logos/Baidu Logo-RGB.png
    alt: Baidu
    title: Baidu
  - url: https://www.capitalone.com/tech/ai-research/
    image_path: /assets/images/logos/Capital_One.webp
    alt: Capital One
    title: Capital One
gold:
  - url: https://machinelearning.apple.com
    image_path: /assets/images/logos/Apple.png
    alt: Apple
    title: Apple
  - url: https://www.bloomberg.com/company/values/tech-at-bloomberg/
    image_path: /assets/images/logos/Bloomberg.png
    alt: Bloomberg
    title: Bloomberg
bronze:
  - url: https://translated.com/welcome
    image_path: /assets/images/logos/translated.png
    alt: Translated
    title: Translated
diversity:
  - url: https://machinelearning.apple.com
    image_path: /assets/images/logos/Apple.png
    alt: Apple
    title: Apple
---

NAACL 2025 is extremely grateful to all sponsors, who are listed below. We simply couldn’t run the conference without the help of these generous organizations. We thank them sincerely for their ongoing support of the NLP/CL community.

If your organization would like to sponsor NAACL or other conferences in the ACL family, 
please refer to our [**Sponsorship Booklet**](https://2025.aclweb.org/assets/Sponsorship%20brochure%20for%20ACL%202025%20conferences%20-%202025-01-03.pdf) 
for information about sponsorship rates and benefits. 
For any questions regarding sponsorship, please email sponsoring@aclweb.org. The deadline to sponsor NAACL 2025 is Friday, March 28th, 2025.

<style>
.sponsors-list { justify-content: flex-start; }
.sponsors-list > a {
  display: flex;
  flex-direction: row;
  justify-content: center;
  background-color: #fff;
  border: 1px solid #d3d3d3;
  border-radius: 5px;
  align-items: center;
  margin: 0.2em;
  padding: 0.5em;
  text-align: center;
}
.sponsors-list a { text-decoration: none; }
.sponsors-list > a > .dummy-padding { margin-top: 100%; }
.sponsors-list > a > img { margin: 0; }
.sponsors-list > a:hover { box-shadow: 0 0 10px #00000044; }
.sponsors-list > a:hover > img { box-shadow: none !important; }
</style>

{% assign diamond_sponsors = site.data.sponsors | where: "tier", "diamond" %}
{% if diamond_sponsors.size > 0 %}
## Diamond

{% include sponsors-list id="diamond" layout="third" %}
{% endif %}

{% assign platinum_sponsors = site.data.sponsors | where: "tier", "platinum" %}
{% if platinum_sponsors.size > 0 %}
## Platinum

{% include sponsors-list id="platinum" layout="third" %}
{% endif %}

{% assign gold_sponsors = site.data.sponsors | where: "tier", "gold" %}
{% if gold_sponsors.size > 0 %}
## Gold

{% include sponsors-list id="gold" layout="third" %}
{% endif %}

{% assign silver_sponsors = site.data.sponsors | where: "tier", "silver" %}
{% if silver_sponsors.size > 0 %}
## Silver

{% include sponsors-list id="silver" layout="third" %}
{% endif %}

{% assign bronze_sponsors = site.data.sponsors | where: "tier", "bronze" %}
{% if bronze_sponsors.size > 0 %}
## Bronze

{% include sponsors-list id="bronze" layout="third" %}
{% endif %}

{% assign diversity_sponsors = site.data.sponsors | where: "tier", "diversity" %}
{% if diversity_sponsors.size > 0 %}
## Diversity and Inclusion Ally

{% include sponsors-list id="diversity" layout="third" %}
{% endif %}
