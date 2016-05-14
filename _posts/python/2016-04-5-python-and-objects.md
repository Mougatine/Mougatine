---
layout: post
title:  Python & Objects
tag:    [Python]
---

I'm going to assume in this article, that you are already familiar with the idea of programming oriented object.

Therefore we'll see how does it looks like in Python.

## 1. Introduction

The class declaration begin like this:

{% highlight python %}
class Example(Object):
{% endhighlight %}

Note that what's between the parenthesis is the *parent* class.

**Object** is the default abstract class for every object in Python, note that you can avoid precising the parent class, Python will assume it is **Object**.

This is valid:

{% highlight python %}
class Example():
{% endhighlight %}

## 2. The Constructor

The class constructor is the function:
{% highlight python %}
def __init__(self, *args, **kwargs):
  ...
{% endhighlight %}

As you may already have guessed, every *method* of a class has for first argument **self**. It's equivalent to *this* in *C++*.


