---
layout: post-index
permalink: /lecture_3/
title: 수치 자료형과 연산자
description: "수치 자료형과 연산자 소개 및 예제"
tags: [Jekyll, theme, install, setup]
image:
  <!--feature: abstract-11.jpg
  credit: dargadgetz
  creditlink: http://www.dargadgetz.com/ios-7-abstract-wallpaper-pack-for-iphone-5-and-ipod-touch-retina/-->
share: true
---


[Jekyll](http://naver.com)
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


<!-- 이미지 기능 -->
![Twitter Card summary large image screenshot]({{ site.url }}/images/twitter-card-summary-large-image.jpg)
![Twitter Card summary large image screenshot]({{ site.url }}/images/twitter-card-summary-large-image.jpg)

<!-- 동영상 기능 -->
<iframe width="560" height="315" src="//www.youtube.com/embed/SU3kYxJmWuQ" frameborder="0"> </iframe>

<!-- 코드입력부 기능 -->
{% highlight html linenos %}
{% raw %}
def add(a,b):
  return a+b
  
print add(1,2)
{% endraw %}
{% endhighlight %}


<!-- 코드 출력부 기능 -->
{% highlight html %}
<iframe width="560" height="315" src="//www.youtube.com/embed/SU3kYxJmWuQ" frameborder="0"> </iframe>
{% endhighlight %}