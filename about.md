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
* <arthur.douillard@epita.fr>
* [Curriculum Vitae](/public/cv/cv.pdf)
* [Linkedin](https://linkedin.com/in/arthurdouillard)
* [Github](https://github.com/BoBibelo)
* [Twitter](https://twitter.com/bobibelo)

## Blog Design

* Based on [Hyde](http://hyde.getpoole.com/)
* Also based on [Hydejacked](http://qwtel.com/hydejack/2016/03/08/introducing-hydejack/)
