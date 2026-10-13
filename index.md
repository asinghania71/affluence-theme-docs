---
title: Home
layout: home
nav_order: 1
description: Help for the Lush Shopify theme. Set up your store, customize every page, and find answers.
permalink: /
---

<div class="hero">
  <span class="hero__eyebrow">Lush Help Center</span>
  <h1>How can we help?</h1>
  <p>Set up your store, customize every page, and find answers. No code needed.</p>
  <button type="button" class="hero__search" onclick="lushOpenSearch()">
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" aria-hidden="true"><circle cx="11" cy="11" r="8"/><line x1="21" y1="21" x2="16.65" y2="16.65"/></svg>
    Search, for example "free shipping" or "countdown"
  </button>
  <div class="hero__links">
    Popular:
    <a href="{{ '/getting-started/' | relative_url }}">Set up your store</a> ·
    <a href="{{ '/customizing/cart/cart-type/' | relative_url }}">Cart type</a> ·
    <a href="{{ '/customizing/header-navigation/menus/' | relative_url }}">Menus</a> ·
    <a href="{{ '/getting-started/image-sizes/' | relative_url }}">Image sizes</a>
  </div>
</div>

<script>
  /* The hero box opens the site search (inside the menu on phones).
     Block comments only: the page HTML is compressed onto one line. */
  function lushOpenSearch() {
    var input = document.getElementById('search-input');
    if (!input) return;
    if (!input.offsetParent) document.getElementById('menu-button').click();
    input.focus();
    input.scrollIntoView({ block: 'center' });
  }
</script>

<h2>Customize your store</h2>

<div class="cards">
{% assign tiles = "Getting started|getting-started/|Install Lush, pick a style and work through the launch checklist.|styles/lush.jpg~Header and navigation|customizing/header-navigation/|Announcement bar, countdown, layouts, menus and the mobile menu.|header/layouts.png~Product pages|customizing/product-pages/|Gallery, variants, buy buttons, custom fields and delivery dates.|product/page.png~Cart|customizing/cart/|Drawer or page, free shipping bar, gift wrap, discounts and more.|cart/drawer.png~Collection pages|customizing/collection-pages/|Filters, sorting, product cards, badges and ribbons.|collection/page.png~Wishlist|customizing/wishlist/|Let shoppers save products, with no app or account.|wishlist/drawer.png~Search|customizing/search/|Suggestions as shoppers type, and a results page that never dead-ends.|search/predictive.png~Footer and newsletter|customizing/footer-newsletter/|Footer layouts, menus, social links and email signup.|footer/footer-mobile.png" | split: "~" %}
{% for tile in tiles %}{% assign t = tile | split: "|" %}
  <a class="card" href="{{ t[1] | relative_url }}">
    <span class="card__media"><img src="{{ '/assets/images/' | append: t[3] | relative_url }}" alt="" loading="lazy"></span>
    <span class="card__body"><span class="card__title">{{ t[0] }}</span><span class="card__text">{{ t[2] }}</span></span>
  </a>
{% endfor %}
</div>

<div class="home-heading">
  <h2>Six complete styles</h2>
  <a href="{{ '/getting-started/styles/' | relative_url }}">Compare styles →</a>
</div>

<div class="styles-grid cards">
{% assign styles = "Lush|Beauty and home,Noir|Luxury and fragrance,Atelier|Fashion and design,Bloom|Gifts and lifestyle,Terra|Food and craft,Catalog|Large catalogs" | split: "," %}
{% for s in styles %}{% assign p = s | split: "|" %}
  <a class="card" href="{{ '/getting-started/styles/' | relative_url }}">
    <span class="card__media"><img src="{{ '/assets/images/styles/' | append: p[0] | downcase | append: '.jpg' | relative_url }}" alt="" loading="lazy"></span>
    <span class="card__body"><span class="card__title">{{ p[0] }}</span><span class="card__text">{{ p[1] }}</span></span>
  </a>
{% endfor %}
</div>

<h2>Need a hand?</h2>

<div class="help-strip">
  <a class="card" href="{{ '/faq/' | relative_url }}"><span class="card__title">FAQ</span><span class="card__text">Answers to the most common questions.</span></a>
  <a class="card" href="{{ '/getting-started/image-sizes/' | relative_url }}"><span class="card__title">Image sizes</span><span class="card__text">The right size and shape for every image.</span></a>
  <a class="card" href="{{ '/getting-started/updating/' | relative_url }}"><span class="card__title">Updating the theme</span><span class="card__text">Get new features without losing your settings.</span></a>
  <a class="card" href="{{ '/support/' | relative_url }}"><span class="card__title">Contact support</span><span class="card__text">We reply within two business days.</span></a>
</div>
