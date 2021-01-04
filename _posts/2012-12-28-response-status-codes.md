---
title: Using site variables example
new: Hello {{ site.elements }}
layout: null
---

### Success

{{ page.new | flatify }}!!!

At {{ site.company }}, you have complete control over your integrations. We have implemented many resources for you, such as {{site.elements}}, {{site.formulas}}, and {{site.commonResource}}.

Our {{ site.elements }} use all the basic REST API operations, such as:

* `GET`, `PUT`, `DELETE` returns `200 OK` on success,
* `POST ` returns 201 on success

The above paragraph is an example using `site variables`.