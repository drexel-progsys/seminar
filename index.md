---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
<h1>Paper Suggestions</h1>
For the list of paper suggestions, see the Suggestions link in the nav bar.

<h2>Term-by-term Meetings</h2>
{% for post in site.posts %}
<h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
{% endfor %}
