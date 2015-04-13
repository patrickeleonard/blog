---
layout: page
title: My name is Patrick.
tagline: This is a blog.
---
{% include JB/setup %}

##This is a test of headings

    here's some stuff? in a box?


# Heading 1 test

## Heading 2 test

### Heading 3 test

#### Heading 4 test

##### Heading 5 test

###### Heading 6 test

\#hashtag

>quotes
>>double quotes

    Code block
      beep beep boop

*italics*
_italics also_
**bold**
__bold also__

## Sample Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

