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
                    <img src="https://placehold.co/310x190/378a80/FFFFFF/?text=Area%201" title="" alt="">
                  </figure>
                </div>
              </div>
                <h3 class="card-title h5 ">Area 1</h3>
                <p class="card-text font-serif">L'Area 1 è dedicata alle competenze relative alle aree tematiche delle politiche giovanili. Comprende tre uffici che si occupano rispettivamente di sport e tempo libero, cultura e pubblica istruzione, pari opportunità e benessere del personale.</p>
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
                    <img src="https://placehold.co/310x190/378a80/FFFFFF/?text=Area%202" title="" alt="">
            </figure>
          </div>
        </div>
          <h3 class="card-title h5 ">Area 2</h3>
          <p class="card-text font-serif">L'Area 2 si occupa della gestione dei rapporti con il pubblico, delle proposte da presentare in Comune, dei contatti con Arena Giovani e delle relazioni con la stampa. Comprende due uffici: l'Ufficio Pubblico, responsabile della comunicazione con i cittadini, del blog ufficiale e dei social media; e l'Ufficio Stampa, che cura la posta in entrata e i rapporti con i media.</p>
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
                    <img src="https://placehold.co/310x190/378a80/FFFFFF/?text=Area%203" title="" alt="">
            </figure>
          </div>
        </div>
          <h3 class="card-title h5 ">Area 3</h3>
          <p class="card-text font-serif">"L'Area 3 coordina tutti i progetti promossi da Arena Giovani, gestisce i servizi informatici interni e cura i rapporti con le associazioni e le possibili collaborazioni. Attualmente comprende l’Ufficio Oratopia (in collaborazione con le Aree 1 e 3), l’Ufficio Informatico (gestito dall’Area 3) e l’Ufficio Bibliotecando (collegato all’Ufficio Cultura e Pubblica Istruzione).</p>
        </div>
      </div>
    </div>
    <!--end card-->
  </div>
</div>


</main>

