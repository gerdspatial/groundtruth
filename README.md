---
layout: default
permalink: /
---

# Ground Truth
<br>

→ [RSS](https://buttondown.email/gerhard/rss)<br>
→ [JSON](https://feed2json.org/convert?url=https%3A%2F%2Fbuttondown.email%2Fgerhard%2Frss)<br>

I'm [Gerhard Lanz](https://gerhardla.nz) and this is **Ground Truth**—a daily newsletter on walking [Te Araroa](https://www.teararoa.org.nz) (The Long Pathway) in New Zealand. Ground Truth is time-bound and will operate only while I am on the trail, after which it will be [archived](https://buttondown.email/gerhard/archive). All email addresses will be deleted upon completion. Welcome to the trail crew.
<br>

<form
  action="https://buttondown.email/api/emails/embed-subscribe/gerhard"
  method="post"
  target="popupwindow"
  onsubmit="window.open('https://buttondown.email/garhard', 'popupwindow')"
  class="embeddable-buttondown-form">
  <label for="bd-email">Enter your email</label>
  <input type="email" name="email" id="bd-email" />
  <input type="hidden" value="1" name="embed" />
  <input type="submit" value="Subscribe" />
  <p>
  Powered by <a href="https://buttondown.email" target="_blank">Buttondown</a>.
  </p>
</form>
<ul>
  {% for post in site.posts %}
    <li>
        <span>{{ post.date | date: "%Y-%m-%d" }}</span> — <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
