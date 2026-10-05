---
layout: default
lang: en
permalink: /
alt_url: /pt/
description: A cozy shared grocery list for families. Tap what you need and it jumps to the top.
---

<div class="hero">
  <img src="{{ '/assets/mascot.png' | relative_url }}" alt="A fox resting its chin on a woven basket">
  <h1>Foxy Basket</h1>
  <p class="tagline">Grocery lists that feel like home.</p>
  {% if site.app_store_url %}
  <a class="badge" href="{{ site.app_store_url }}">Get it on the App Store</a>
  {% else %}
  <p class="muted">Coming soon to the App Store for iPhone.</p>
  {% endif %}
</div>

<div class="cards">
  <div class="card">
    <h3>It remembers</h3>
    <p>Your list keeps every staple. Tap what you need this trip and it jumps to the top. Tap it again in the store and it drops back down, ready for next week.</p>
  </div>
  <div class="card">
    <h3>Your own order</h3>
    <p>Sort by aisle, A–Z or category, or make a custom order for your favorite store. Everyone on the list picks their own.</p>
  </div>
  <div class="card">
    <h3>Made for families</h3>
    <p>Invite people by @username or email, choose who can add, edit or delete, and see changes as they happen.</p>
  </div>
</div>

## Private by design

Your lists are only visible to people you invite. There are no ads and no tracking, and you can delete your account and everything in it from Settings. Read the [privacy policy]({{ '/privacy/' | relative_url }}).
