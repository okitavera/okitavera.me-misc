---
permalink: /okita-kernel-mi9se/
layout: page.njk
title: Okitavera Kernel For Xiaomi Mi 9 SE
desc: A Custom Kernel for Xiaomi Mi 9 SE to enhance performance and battery-life
---

> [XDA Thread](https://forum.xda-developers.com/mi-9-se/development/kernel-okitakernel-v1-0-mi-9-se-27-2019-t3934029)
> [Source tree](https://github.com/okitavera/msm-4.9-grus-okita)

{% for kernel in collections.kernel %}
{{ set ver = kernel.fileSlug }}
<span class="txt--big txt--700">Version {{ kernel.fileSlug }} &nbsp;&nbsp; {% if kernel.data.download %}<a class="btn btn--small bg--accent" href="{{ kernel.data.download }}">Download</a>{% endif %}
</span>
<blockquote>
<span class="txt--700">Changelog</span>
{{ kernel.templateContent | safe }}
</blockquote>
{% endfor %}
