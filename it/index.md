---
layout: default
title: Homepage di esempio
description: Questo è un esempio di homepage con utilizzo del componente "hero"
lang: it
ref: homepage
permalink: /
order: 1
---

{% include hero.html %}

<main class="container my-4" markdown="1">

{% include posts.html %}
<div class="row">
  <div class="col-12 col-lg-4">
    <!--start card-->
    <div class="card-wrapper">
      <div class="card">
        <div class="card-body">
          <div class="links" href="ciao">
              <div class="img-responsive-wrapper">
                <div class="img-responsive">
                  <figure class="img-wrapper">
                    <img src="https://placehold.co/310x190/0066cc/FFFFFF/?text=IMMAGINE%20DI%20ESEMPIO" title="titolo immagine" alt="descrizione immagine">
                  </figure>
                </div>
              </div>
                <h3 class="card-title h5 ">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor…</h3>
                <p class="card-text font-serif">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
          </div>
        </div>
      </div>
    </div>
    <!--end card-->
  </div>
  <div class="col-12 col-lg-4">
    <!--start card-->
    <div class="card-wrapper">
      <div class="card">
        <div class="card-body">
        <div class="img-responsive-wrapper">
          <div class="img-responsive">
            <figure class="img-wrapper">
              <img src="https://placehold.co/310x190/0066cc/FFFFFF/?text=IMMAGINE%20DI%20ESEMPIO" title="titolo immagine" alt="descrizione immagine">
            </figure>
          </div>
        </div>
          <h3 class="card-title h5 ">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor…</h3>
          <p class="card-text font-serif">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
        </div>
      </div>
    </div>
    <!--end card-->
  </div>
  <div class="col-12 col-lg-4">
    <!--start card-->
    <div class="card-wrapper">
      <div class="card">
        <div class="card-body">
        <div class="img-responsive-wrapper">
          <div class="img-responsive">
            <figure class="img-wrapper">
              <img src="https://placehold.co/310x190/0066cc/FFFFFF/?text=IMMAGINE%20DI%20ESEMPIO" title="titolo immagine" alt="descrizione immagine">
            </figure>
          </div>
        </div>
          <h3 class="card-title h5 ">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor…</h3>
          <p class="card-text font-serif">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
        </div>
      </div>
    </div>
    <!--end card-->
  </div>
</div>


</main>

