---
title: welcome
date: 2018-12-18 17:10:10
tags:
---
**Welcome to my Blog**
{% blockquote David Levithan, Wide Awake %}
Do not just seek happiness for yourself. Seek happiness for all. Through kindness. Through mercy.
{% endblockquote %}

{% codeblock %}
Vue.component('blog-post', {
  // camelCase in JavaScript
  props: ['postTitle'],
  template: '<h3>{{ postTitle }}</h3>'
})
{% endcodeblock %}
