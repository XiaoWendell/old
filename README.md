<code>
  ---
  layout: home
  title: Welcome to My Blog
  ---

  ## Hello, World!

  欢迎来到我的博客，我会在这里分享一些我所学到的知识和经验。希望我的博客可以帮助到你。

  ## 最新文章

  {% for post in site.posts %}
  - [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%Y-%m-%d" }}
  {% endfor %}
</code>
