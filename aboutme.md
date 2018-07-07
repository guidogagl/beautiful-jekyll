---
layout: page
title: About me
subtitle: Why you'd want to go on a date with me
published: true
---

My name is Inigo Montoya. I have the following qualities:

- I rock a great mustache
- I'm extremely loyal to my family

What else do you need?

### my history

To be honest, I'm having some trouble remembering right now, so why don't you just watch [my movie](http://en.wikipedia.org/wiki/The_Princess_Bride_%28film%29) and it will answer **all** your questions.

{% instagram accesstokenpath: ./_plugins/token.txt %}
	<div>
		<h3>{{ item.caption.text }}</h3>
		<img src="{{ item.images.standard_resolution.url }}" />
	</div>
{% endinstagram %}

