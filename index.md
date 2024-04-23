---
layout: default
title: Home
---

# Large Language Models

This is site is a collection of LLM experiments, observations, and other informations.

## Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      - {{ post.date | date: "%B %-d, %Y" }}
    </li>
  {% endfor %}
</ul>

## Contact

You can reach me through the following channels:

- Email: [essobi_@_gmail.com](mailto:essobi_@_gmail.com)
- Twitter: [@essobi](https://x.com/essobi)
- GitHub: [Essobi](https://github.com/essobi)
- GitHub: [data2json](https://github.com/data2json)

