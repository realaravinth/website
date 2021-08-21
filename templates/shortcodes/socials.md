{% set name = name %}
{% set text = text %}
{% for var in config.extra.socials %}
	{% if var.name ==  name %}
	  {% if var.name ==  "email" %}
		[{{ var.link }}]("mailto:{{ var.link }}")
	  {% else %}
		[{{ text }}]({{ var.link }})
	  {% endif %}
	{% endif %}
{% endfor %}
