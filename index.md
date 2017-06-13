---
layout: default
---


| #          | Title                                                          | Difficulty | Solution         |
|:-----------|:---------------------------------------------------------------|:-----------|:-----------------|
| 1          | [Two Sum](https://leetcode.com/problems/two-sum/#/description) | Easy       |[O(n)](2015/11/15/two-sum)|

<div class="home">
	<section>
		<h2 class="smallcap">about</h2>
		<p><a href="https://leetcoder2017.github.io/leetcode/">Leetcode2017</a>Provide best solutions</p>
	</section>
	<section>
		<h2 class="smallcap">solutions</h2>
		<ul class="post-list">
			{% for post in site.posts limit:5 %}
			<li>
				<a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
			</li>
			{% endfor %}
		</ul>
		<p><a href="{{ "/archives/" | prepend: site.baseurl }}">view more...</a></p>
	</section>
</div>