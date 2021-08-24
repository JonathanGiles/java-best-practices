---
page:
  title: Microsoft Java Best Practices
permalink: /
title: Microsoft Java Best Practices
---

Java has been around for an exceptionally long time, and continues to find massive support from developers and businesses worldwide. It has a proven track record of reliably working in mission critical projects, where performance, supportability, wider ecosystem support, and Java's continued evolution see its adoption growing.

The Microsoft Java Best Practices website is for all Java developers. The goal is to distill years of Java experience down to a set of best practices that help developers build high-quality Java applications. The best practices are broken into different sections for Java developers, Java library developers, and users of the Azure SDK for Java.

## Best Practices for Java Developers

{% for p in site.pages %}{% if p.jbp -%}
- [{{ p.jbp.id }}]({{ p.url | relative_url }}): {{ p.title }} {% if p.draft -%}(Draft){% endif %}
{% endif %}{% endfor %}

## Using Azure SDK for Java

- Coming soon

{% unless true %}
{% for p in site.pages %}{% if p.azsdk -%}
- [{{ p.azsdk.id }}]({{ p.url | relative_url }}): {{ p.title }} {% if p.draft -%}(Draft){% endif %}
{% endif %}{% endfor %}
{% endunless %}

## Best Practices for Java Library Developers

{% for p in site.pages %}{% if p.jlbp -%}
- [{{ p.jlbp.id }}]({{ p.url | relative_url }}): {{ p.title }} {% if p.draft -%}(Draft){% endif %}
{% endif %}{% endfor %}