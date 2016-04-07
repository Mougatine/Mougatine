---
layout: page
title: About
---

{% comment %}
  This inserts the "about" photo and text from `_config.yml`.
  You can edit it there (jekyll needs restart!) or remove it and provide your own photo/text.
  Don't forget to add the `me` class to the photo, like this: `![alt](src){:.me}`.
{% endcomment %}

{% if site.author.photo %}
  ![{{ site.author.name }}]({{ site.author.photo }}){:.me}
{% endif %}

{{ site.author.about }}

***

## References

<div class="sidebar-social">
<a href="https://github.com/BoBibelo"><i class="fa fa-github fa-2x"></i></a>
<a href="https://linkedin.com/in/arthurdouillard"><i class="fa fa-linkedin-square fa-2x"></i></a>
<a href="https://twitter.com/bobibelo"><i class="fa fa-twitter-square fa-2x"></i></a>
<a href="mailto:arthur.douillard@epita.fr"><i class="fa fa-envelope-o fa-2x"></i></a>
</div>

And my CV: <a href="/public/cv/cv.pdf"><i class="fa fa-file-text fa-2x"></i></a>

## Blog Design

* Based on [Hyde](http://hyde.getpoole.com/)
* Also based on [Hydejacked](http://qwtel.com/hydejack/2016/03/08/introducing-hydejack/)
