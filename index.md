---
layout: page
title: User Experience research and design
permalink: /
---

Information &amp; Design is Gerry Gaffney’s user experience (UX) and usability company, based in Melbourne, Australia.

Since 1991, we’ve been helping clients understand their users and design successful applications. We’ve worked in government, consulting, education, finance, risk &amp; compliance, engineering and manufacturing.

We can help you understand the strategic and tactical steps to take to develop customer-centred products and services.

See some of the [clients we’ve helped][clients].

What’s new
----------

Gerry interviewed Debra Levin Gelman on the topic of [Designing for Kids][designingforkids] (August), and the authors of [The Moderator’s Survival Kit][moderatorssurvivalkit] (July) on the User Experience podcast.

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

[jekyll]:                 http://jekyllrb.com
[jekyll-gh]:              https://github.com/jekyll/jekyll
[jekyll-help]:            https://github.com/jekyll/jekyll-help
[clients]:                /clients/
[designingforkids]:       http://uxpod.com/design-for-kids-an-interview-with-debra-levin-gelman/
[moderatorssurvivalkit]:  http://uxpod.com/the-moderators-survival-guide-an-interview-with-donna-tedesco-and-fiona-tranquada/

<h1 class="page-heading">Posts</h1>

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

      <h2>
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      </h2>
    </li>
  {% endfor %}
</ul>

<p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>
