# Welcome to the {{site_name}}!

These are the [ribbity](https://github.com/ctb/ribbity) docs!

ribbity is a tool that takes a Github issue tracker and turns it into a
Web site using [mkdocs](https://www.mkdocs.org/).

You can see a real live site here: [sourmash examples](https://sourmash-bio.github.io/sourmash-examples/).

Ribbity is simple to configure and easy to use. See below!

(And yes, this is a ribbity site itself, of course - see
[the ribbity-docs repo](https://github.com/ctb/ribbity-docs/issues) :).

## Start here!

{% for issue in issues_list %}
{% if issue.is_frontpage %}

[Example: {{issue.title}}]({{issue.output_filename}})

{% endif %}
{% endfor %}

---

## [All examples](examples.md)

---

## [All categories](labels.md)

