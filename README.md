---
page:
  title: Java Best Practices
permalink: /
title: Java Best Practices
---

Java has been around for an exceptionally long time, and continues to find massive support from developers and businesses worldwide. It has a proven track record of reliably working in mission critical projects, where performance, supportability, wider ecosystem support, and Java's continued evolution see its adoption growing.

The Java Best Practices website is for all Java developers. The goal is to distill years of Java experience down to a set of best practices that help developers build high-quality Java applications and libraries. This documentation is open-source and contributions are appreciated! You can find all documentation [over on GitHub](https://github.com/JonathanGiles/java-best-practices).

## Best Practices for Java Developers

{% for p in site.pages %}{% if p.jbp -%}
- [{{ p.jbp.id }}]({{ p.url | relative_url }}): {{ p.title }} {% if p.draft -%}(Draft){% endif %}
{% endif %}{% endfor %}

## Best Practices for Java Library Developers

{% for p in site.pages %}{% if p.jlbp -%}
- [{{ p.jlbp.id }}]({{ p.url | relative_url }}): {{ p.title }} {% if p.draft -%}(Draft){% endif %}
{% endif %}{% endfor %}
