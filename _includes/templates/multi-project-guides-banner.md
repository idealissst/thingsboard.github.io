{% if docsPrefix == "pe/" %}

{% include templates/guides-banner-pe.md %}

{% elsif docsPrefix contains "paas/" %}

{% include templates/guides-banner-paas.md %}

{% else %}

{% include templates/guides-banner.md %}

{% endif %}
