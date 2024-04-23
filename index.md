---
layout: default
---

# Large Language Models

This is site is a collection of LLM experiments, observations, and other information related to GPTs, LLMs, and transformer models.

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

- Twitter: [@essobi](https://x.com/essobi)
- GitHub: [Essobi](https://github.com/essobi)
- GitHub: [data2json](https://github.com/data2json)
