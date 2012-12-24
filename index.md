---
layout: page
title: ozamasa
tagline: ozamasa
---
{% include JB/setup %}

Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)

## Update Author Attributes

In `_config.yml` remember to specify your own data:
    
    title : My Blog =)
    
    author :
      name : Name Lastname
      email : blah@email.test
      github : username
      twitter : username

The theme should reference these variables whenever needed.
    
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

## To-Do

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.

## Google Map

<div>
<iframe width="640" height="480" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" src="https://maps.google.co.jp/maps?f=q&amp;source=s_q&amp;hl=ja&amp;geocode=&amp;q=%E9%95%B7%E9%87%8E%E7%9C%8C%E5%A1%A9%E5%B0%BB%E5%B8%82%E5%A1%A9%E5%B0%BB%E7%94%BA%EF%BC%96+%E9%98%BF%E7%A4%BC%E7%A5%9E%E7%A4%BE&amp;aq=0&amp;oq=%E3%81%82%E3%82%8C%E3%81%84%E3%81%98%E3%82%93%E3%81%98%E3%82%83&amp;sll=34.728949,138.455511&amp;sspn=36.91496,66.796875&amp;brcurrent=3,0x601d03eb20770b8b:0xf49ff935b611cda3,0&amp;ie=UTF8&amp;hq=%E9%98%BF%E7%A4%BC%E7%A5%9E%E7%A4%BE&amp;hnear=%E9%95%B7%E9%87%8E%E7%9C%8C%E5%A1%A9%E5%B0%BB%E5%B8%82%E5%A1%A9%E5%B0%BB%E7%94%BA%EF%BC%96&amp;t=m&amp;cid=6587365227707278172&amp;ll=36.105636,137.973089&amp;spn=0.033286,0.054932&amp;z=14&amp;output=embed"></iframe><br /><small><a href="https://maps.google.co.jp/maps?f=q&amp;source=embed&amp;hl=ja&amp;geocode=&amp;q=%E9%95%B7%E9%87%8E%E7%9C%8C%E5%A1%A9%E5%B0%BB%E5%B8%82%E5%A1%A9%E5%B0%BB%E7%94%BA%EF%BC%96+%E9%98%BF%E7%A4%BC%E7%A5%9E%E7%A4%BE&amp;aq=0&amp;oq=%E3%81%82%E3%82%8C%E3%81%84%E3%81%98%E3%82%93%E3%81%98%E3%82%83&amp;sll=34.728949,138.455511&amp;sspn=36.91496,66.796875&amp;brcurrent=3,0x601d03eb20770b8b:0xf49ff935b611cda3,0&amp;ie=UTF8&amp;hq=%E9%98%BF%E7%A4%BC%E7%A5%9E%E7%A4%BE&amp;hnear=%E9%95%B7%E9%87%8E%E7%9C%8C%E5%A1%A9%E5%B0%BB%E5%B8%82%E5%A1%A9%E5%B0%BB%E7%94%BA%EF%BC%96&amp;t=m&amp;cid=6587365227707278172&amp;ll=36.105636,137.973089&amp;spn=0.033286,0.054932&amp;z=14" style="color:#0000FF;text-align:left">大きな地図で見る</a></small>
</div>
