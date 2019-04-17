---
title: Sponsors
header: Our Sponsors
post_heading: Our Sponsors
layout: other_page
bg-image: img/misc/mendhi.jpg
---
<p style="margin-bottom: 15px">Cambridge University India Society would like to give a huge THANK YOU to
	all of our current sponsors:</p>
<p style="margin-bottom: 15px">If you are interested in becoming a sponsor, please contact our <a
		href="mailto:{{site.sponsorship_email}}">Sponsorship Officer</a></p>

{% for s in site.data.sponsors.root %}
<div class="col-lg-4 sponsorbox">
	<img class="sponsorimg" src="{{ s.image }}">
</div>
{% endfor %}