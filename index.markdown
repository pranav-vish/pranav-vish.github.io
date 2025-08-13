---
layout: single
author_profile: true
---

## About Me

I am a Machine Learning Engineer and AI Consultant at Yokogawa Electric Corporation in Tokyo, Japan, where I develop end-to-end AI solutions to drive intelligent automation in manufacturing.

I graduated with a Bachelor's degree in Mathematics and Computing from IIT Hyderabad, where I cultivated a deep interest in Computer Vision, Speech Systems and deep learning theory in general.

I am particularly passionate about advancing AI systems that go beyond pattern recognition and towards reasoning, adaptability, and generalization. I enjoy working on challenging problems that demand structured thinking.

## Featured Projects

{% for project in site.projects limit:3 %}
- [{{ project.title }}]({{ project.url | relative_url }}) - {{ project.excerpt | strip_html | truncate: 100 }}
{% endfor %}

[View all projects →](/projects/)

## Recent Blog Posts

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

[View all posts →](/blog/)
