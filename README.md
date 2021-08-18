---
page:
  title: Microsoft Java Best Practices
permalink: /
---

# Microsoft Java Best Practices

## Best Practices for Java Developers

{% for p in site.pages %}{% if p.jbp -%}
- [{{ p.jbp.id }}]({{ p.url | relative_url }}): {{ p.title }}
{% endif %}{% endfor %}

## Using Azure SDK for Java

{% for p in site.pages %}{% if p.azsdk -%}
- [{{ p.azsdk.id }}]({{ p.url | relative_url }}): {{ p.title }}
{% endif %}{% endfor %}

## Best Practices for Java Library Developers

{% for p in site.pages %}{% if p.jldbp -%}
- [{{ p.jldbp.id }}]({{ p.url | relative_url }}): {{ p.title }}
{% endif %}{% endfor %}