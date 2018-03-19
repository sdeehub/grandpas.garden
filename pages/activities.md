---
layout: default
subheadline: "กิจกรรมขององค์กร"
title: "กิจกรรมและโครงการต่างๆ"
teaser: "โมบายล์เพจเจอร์ออฟไลน์บลูทูธอัปเดต คลีนิก ดีวีดีสล็อตเวอร์ชวลเมลามีนเมล เทมเพลต โพรโทคอลโมไบล์หล่ะ ดีวีดีทรานแซ็คชั่นไฮโดรลิก แคสสินี ซิริอุสโนวาเยภุยยสิกา"
header:
   image_fullwidth: "D4.jpg"
   caption: "Photo by Michał Parzuchowski on Unsplash"
   caption_url: https://unsplash.com/@mparzuchowski
permalink: "/activities/"
---

<div id="blog-index" class="row">
	<div class="medium-8 columns t30">

		<h1>{{ page.title }}</h1>
		{% if page.teaser %}<p class="teaser">{{ page.teaser }}</p>{% endif %}

<h2>มีนาคม 2561</h2><br/>
		<dl class="accordion" data-accordion>
			{% assign counter = 1 %}
			{% for post in site.posts limit:1000 %}
        {% assign first_dir = post.path | remove_first: "_posts/" | split: "/" | first %}
          {% if first_dir == 'event_03' %}
            <dd class="accordion-navigation">
      			<a href="#panel{{ counter }}"><span class="iconfont"></span> {% if post.subheadline %}{{ post.subheadline }} › {% endif %}<strong>{{ post.title }}</strong></a>
      				<div id="panel{{ counter }}" class="content">
      					{% if post.meta_description %}{{ post.meta_description | strip_html | escape }}{% elsif post.teaser %}{{ post.teaser | strip_html | escape }}{% endif %}
      					<a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}" title="Read {{ post.title | escape_once }}"><strong>{{ site.data.language.read_more }}</strong></a><br><br>
      				</div>
      			</dd>
			    {% endif %}  
			{% assign counter=counter | plus:1 %}
			{% endfor %}
		</dl>

<h2>กุมภาพันธ์ 2561</h2><br/>
		<dl class="accordion" data-accordion>
			{% assign counter = 1 %}
			{% for post in site.posts limit:1000 %}
        {% assign first_dir = post.path | remove_first: "_posts/" | split: "/" | first %}
          {% if first_dir == 'event_02' %}
            <dd class="accordion-navigation">
      			<a href="#panel{{ counter }}"><span class="iconfont"></span> {% if post.subheadline %}{{ post.subheadline }} › {% endif %}<strong>{{ post.title }}</strong></a>
      				<div id="panel{{ counter }}" class="content">
      					{% if post.meta_description %}{{ post.meta_description | strip_html | escape }}{% elsif post.teaser %}{{ post.teaser | strip_html | escape }}{% endif %}
      					<a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}" title="Read {{ post.title | escape_once }}"><strong>{{ site.data.language.read_more }}</strong></a><br><br>
      				</div>
      			</dd>
			    {% endif %}  
			{% assign counter=counter | plus:1 %}
			{% endfor %}
		</dl>

<h2>มกราคม 2561</h2><br/>
		<dl class="accordion" data-accordion>
			{% assign counter = 1 %}
			{% for post in site.posts limit:1000 %}
        {% assign first_dir = post.path | remove_first: "_posts/" | split: "/" | first %}
          {% if first_dir == 'event_01' %}
            <dd class="accordion-navigation">
      			<a href="#panel{{ counter }}"><span class="iconfont"></span> {% if post.subheadline %}{{ post.subheadline }} › {% endif %}<strong>{{ post.title }}</strong></a>
      				<div id="panel{{ counter }}" class="content">
      					{% if post.meta_description %}{{ post.meta_description | strip_html | escape }}{% elsif post.teaser %}{{ post.teaser | strip_html | escape }}{% endif %}
      					<a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}" title="Read {{ post.title | escape_once }}"><strong>{{ site.data.language.read_more }}</strong></a><br><br>
      				</div>
      			</dd>
			    {% endif %}  
			{% assign counter=counter | plus:1 %}
			{% endfor %}
		</dl>

	</div><!-- /.small-12.columns -->

  <div class="medium-4 columns t30">
		{% include _sidebar_event.html %}
	</div><!-- /.medium-5.columns -->
</div><!-- /.row -->
