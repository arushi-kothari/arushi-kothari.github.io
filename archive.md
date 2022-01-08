---
layout: page
title: Archive
---

<section class="archive-post-list">
<table>
{% for post in site.posts %}
    <tr>
        <td style="width: 135px; color: grey" nowrap>{{ post.date | date: "%B %-d %Y" }}</td>
        <td><a href="{{ post.url | relative_url }}" style="color:black">{{ post.title }}</a></td>
    </tr>
{% endfor %}
</table>
</section>
