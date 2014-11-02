---
layout: post-index
permalink: /lecture_7/
title: 사전 및 집합
description: "사전 및 집합 문법 소개 및 예제"
tags: [Jekyll, theme, themes, responsive, blog, modern]
image:
  feature: abstract-1.jpg
  credit: dargadgetz
  creditlink: http://www.dargadgetz.com/ios-7-abstract-wallpaper-pack-for-iphone-5-and-ipod-touch-retina/
---
수정1

<html>
<body>

{% for post in paginator.posts %}
<article class="hentry">
  <header>
    <div class="entry-meta">
      <span class="entry-date date published updated"><time datetime="{{ post.date | date_to_xmlschema }}"><a href="{{ site.url }}{{ post.url }}">{{ post.date | date: "%B %d, %Y" }}</a></time></span><span class="author vcard"><span class="fn"><a href="{{ site.url }}/about/" title="About {{ site.owner.name }}">{{ site.owner.name }}</a></span></span>{% if site.disqus_shortname and post.comments %}&nbsp; &bull; &nbsp;<span class="entry-comments"><a href="{{ site.url }}{{ post.url }}#disqus_thread">Comment</a></span>{% endif %}
    </div><!-- /.entry-meta -->
    {% if post.link %}
      <h1 class="entry-title"><a href="{{ site.url }}{{ post.url }}" rel="bookmark" title="{{ post.title }}"><i class="fa fa-angle-double-right"></i></a> <a href="{{ post.link }}">{{ post.title }}</a></h1>
    {% else %}
      <h1 class="entry-title"><a href="{{ site.url }}{{ post.url }}" rel="bookmark" title="{{ post.title }}" itemprop="url">{{ post.title }}</a></h1>
    {% endif %}
  </header>
  <div class="entry-content">
    {{ post.content }}
  </div><!-- /.entry-content -->
</article><!-- /.hentry -->
{% endfor %}

<!-- 댓글 기능 -->
<a href="http://foo.com/bar.html#disqus_thread">Link</a>.

    <div id="disqus_thread"></div>
    <script type="text/javascript">
        var disqus_shortname = 'slhblog';
        (function() {
            var dsq = document.createElement('script'); dsq.type = 'text/javascript'; dsq.async = true;
            dsq.src = '//' + disqus_shortname + '.disqus.com/embed.js';
            (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(dsq);
        })();
    </script>
    <noscript>Please enable JavaScript to view the <a href="http://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>


<div class="pagination">
  {% if paginator.previous_page %}
    {% if paginator.previous_page == 1 %}
      <a href="{{ site.url }}" class="btn">Previous</a>
    {% else %}
      <a href="{{ site.url }}/page{{ paginator.previous_page }}" class="btn">Previous</a>
    {% endif %}
  {% else %}
    Previous
  {% endif %}
  <ul class="inline-list">
    <li>
      {% if paginator.page == 1 %}
        <span class="current-page">1</span>
      {% else %}
        <a href="{{ site.url }}">1</a>
      {% endif %}
    </li>
    {% for count in (2..paginator.total_pages) %}
      <li>
        {% if count == paginator.page %}
          <span class="current-page">{{ count }}</span>
        {% else %}
          <a href="{{ site.url }}/page{{ count }}">{{ count }}</a>
        {% endif %}
      </li>
    {% endfor %}
  </ul>
  {% if paginator.next_page %}
    <a href="{{ site.url }}/page{{ paginator.next_page }}" class="btn">Next</a>
  {% else %}
    Next
  {% endif %}
</div><!-- /.pagination -->

<!-- 댓글 기능 -->
<a href="http://foo.com/bar.html#disqus_thread">Link</a>.

    <div id="disqus_thread"></div>
    <script type="text/javascript">
        var disqus_shortname = 'slhblog';
        (function() {
            var dsq = document.createElement('script'); dsq.type = 'text/javascript'; dsq.async = true;
            dsq.src = '//' + disqus_shortname + '.disqus.com/embed.js';
            (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(dsq);
        })();
    </script>
    <noscript>Please enable JavaScript to view the <a href="http://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>

</body>
</html>