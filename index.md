Welcome to Blogging 101, an introductory course designed to equip aspiring bloggers with the essential skills and knowledge needed to create compelling, engaging, and successful blogs.
Throughout this course, you will learn the basics of blog setup in Jekyll.
Join us as we embark on this exciting journey to harness the power of blogging to showcase student work and allow students to develop an impactful professional web presence!

## Posts

<!-- This code finds all the posts in `_posts` and generates a listing for them.
In most cases, you should never need to edit it. -->

<ul>
  {% for post in site.posts %}
    <li>
      <h3><a href="{{ post.url }}">{{ post.title }}</a> by {{ post.author }}</h3>
    </li>
  {% endfor %}
</ul>
