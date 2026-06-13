---
layout: page
title: On Stage
subtitle: A few moments outside the office
permalink: /onstage/
---

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/glightbox/dist/css/glightbox.min.css">

<style>
  .onstage-section { margin-top: 2.5rem; }
  .onstage-section h2 {
    font-family: var(--header-font);
    font-size: 1.4rem;
    font-weight: 800;
    border-bottom: 2px solid var(--navbar-border-col);
    padding-bottom: 0.3rem;
    margin-bottom: 0.6rem;
    color: var(--link-col);
  }
  .onstage-section .meta {
    color: var(--mid-col);
    font-size: 0.9rem;
    margin-bottom: 1rem;
  }
  .onstage-gallery {
    display: flex;
    flex-wrap: wrap;
    gap: 0.75rem;
    margin: 0.5rem 0 0;
  }
  .onstage-gallery a {
    display: block;
    width: calc(33.333% - 0.5rem);
    aspect-ratio: 4 / 3;
    overflow: hidden;
    border-radius: 0.25rem;
    background: var(--navbar-col);
  }
  .onstage-gallery a img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.3s;
    display: block;
  }
  .onstage-gallery a:hover img { transform: scale(1.05); }
  @media (max-width: 600px) {
    .onstage-gallery a { width: calc(50% - 0.375rem); }
  }
  .bjyt-video {
    position: relative;
    padding-bottom: 56.25%;
    height: 0;
    margin: 1.5rem 0 0;
    border-radius: 0.25rem;
    overflow: hidden;
  }
  .bjyt-video iframe {
    position: absolute;
    top: 0; left: 0;
    width: 100%;
    height: 100%;
  }
</style>

A few moments outside the office.

<section class="onstage-section">
<h2>Verdi &mdash; <em>Don Carlos</em></h2>
<div class="meta">Stadttheater Augsburg, premiered 17 October 2009 &middot; extra</div>
<p>Season opener for Theater Augsburg, conducted by Dirk Kaftan.</p>
<p class="meta"><em>No photos available.</em></p>
</section>

<section class="onstage-section">
<h2>Beethoven &mdash; <em>Fidelio</em></h2>
<div class="meta">Stadttheater Augsburg, December 2009 &middot; extra</div>
<p>Karl Kneidl's production, conducted by Kevin John Edusei with the Augsburger Philharmoniker.</p>
<div class="onstage-gallery">
  <a href="/assets/img/onstage/2009-fidelio-1.jpg" class="glightbox" data-gallery="fidelio"><img src="/assets/img/onstage/2009-fidelio-1.jpg" alt="Fidelio &mdash; Stadttheater Augsburg, 2009"></a>
</div>
</section>

<section class="onstage-section">
<h2>Puccini &mdash; <em>Turandot</em></h2>
<div class="meta">Freilichtbühne Augsburg (open-air), opened 26 June 2010 &middot; extra</div>
<p>Conducted by Dirk Kaftan &mdash; the long-awaited return of grand opera to the Augsburger Freilichtbühne.</p>
<div class="onstage-gallery">
  <a href="/assets/img/onstage/2010-turandot-1.jpg" class="glightbox" data-gallery="turandot"><img src="/assets/img/onstage/2010-turandot-1.jpg" alt="Turandot &mdash; Freilichtbühne Augsburg, 2010"></a>
  <a href="/assets/img/onstage/2010-turandot-2.jpg" class="glightbox" data-gallery="turandot"><img src="/assets/img/onstage/2010-turandot-2.jpg" alt="Turandot &mdash; Freilichtbühne Augsburg, 2010"></a>
  <a href="/assets/img/onstage/2010-turandot-3.jpg" class="glightbox" data-gallery="turandot"><img src="/assets/img/onstage/2010-turandot-3.jpg" alt="Turandot &mdash; Freilichtbühne Augsburg, 2010"></a>
</div>
</section>

<section class="onstage-section">
<h2><em>Austin</em> (Series 2, 2025)</h2>
<div class="meta">ABC TV / BBC &middot; non-speaking extra, Episode 8</div>
<p>Photographer at a press conference with Foreign Minister Keeds, played by Rob Collins.</p>
<div class="onstage-gallery">
  <a href="/assets/img/onstage/2025-austin-1.jpg" class="glightbox" data-gallery="austin"><img src="/assets/img/onstage/2025-austin-1.jpg" alt="Austin &mdash; Series 2, Episode 8"></a>
</div>
</section>

<section class="onstage-section">
<h2>Future Science Talks (Comedy Edition)</h2>
<div class="meta">Canberra, 2025 &middot; speaker</div>
<p>ANU scientists were challenged to explain their research with a comedic twist — 20 per cent humour, 80 per cent science. Peter's talk: why computers should play the telephone game, sparked by a swooping magpie attack.</p>
<div class="onstage-gallery">
  <a href="/assets/img/onstage/2025-scicomedy-1.jpg" class="glightbox" data-gallery="sci-comedy"><img src="/assets/img/onstage/2025-scicomedy-1.jpg" alt="Future Science Talks (Comedy Edition), Canberra 2025"></a>
  <a href="/assets/img/onstage/2025-scicomedy-2.jpg" class="glightbox" data-gallery="sci-comedy"><img src="/assets/img/onstage/2025-scicomedy-2.jpg" alt="Future Science Talks (Comedy Edition), Canberra 2025"></a>
</div>
{% include youtube.html id="5fRXgmkQRv0" %}
</section>

<script src="https://cdn.jsdelivr.net/npm/glightbox/dist/js/glightbox.min.js"></script>
<script>
  document.addEventListener('DOMContentLoaded', function() {
    GLightbox({ selector: '.glightbox', touchNavigation: true, loop: false });
  });
</script>
