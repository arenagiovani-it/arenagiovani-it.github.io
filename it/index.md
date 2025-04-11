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
                <h3 class="card-title h3 ">Area 1</h3>
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
          <h3 class="card-title h3 ">Area 2</h3>
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
          <h3 class="card-title h3 ">Area 3</h3>
          <p class="card-text font-serif">"L'Area 3 coordina tutti i progetti promossi da Arena Giovani, gestisce i servizi informatici interni e cura i rapporti con le associazioni e le possibili collaborazioni. Attualmente comprende l’Ufficio Oratopia (in collaborazione con le Aree 1 e 3), l’Ufficio Informatico (gestito dall’Area 3) e l’Ufficio Bibliotecando (collegato all’Ufficio Cultura e Pubblica Istruzione).</p>
        </div>
      </div>
    </div>
    <!--end card-->
  </div>
</div>




<div class="container">
  <div class="row">
    <div class="col-sm">
    <div class="card-wrapper card-space">
      <div class="card card-bg card-big no-after">
        <div class="card-body">
          <div class="head-tags">
            <a class="card-tag" href="/proposte/">Proposte</a>
            <span class="data">01/01/2025</span>
          </div>
          <h3 class="card-title h5 ">Proposta Centro Giovani</h3>
          <p class="card-text font-serif">Il progetto Arena Giovani intende presentare un documento ufficiale alla Giunta Comunale per chiedere chiarimenti su specifici aspetti delle politiche giovanili. L’obiettivo è promuovere un dialogo costruttivo tra le istituzioni e i giovani del territorio, favorendo una partecipazione più attiva e consapevole alla vita politica e sociale della comunità.</p>
          <div class="it-card-footer">
            <span class="card-signature">Da Area 2</span>
            <a class="btn btn-outline-primary btn-sm" href="/proposte/centrogiovani/">Centro Giovani</a>
          </div>
        </div>
      </div>
    </div>
    </div>
    <div class="col-sm">
    <div class="card-wrapper card-space">
      <div class="card card-bg card-big no-after">
        <div class="card-body">
          <div class="head-tags">
            <a class="card-tag" href="/comune/instanze/">Instanze</a>
            <span class="data">01/04/2025</span>
          </div>
          <h3 class="card-title h5 ">Richiesta di informazione a ogni singolo assessorato</h3>
          <p class="card-text font-serif">Il progetto Arena Giovani si appresta a presentare un documento ufficiale alla Giunta Comunale con l’obiettivo di richiedere chiarimenti e informazioni dettagliate in merito a specifici ambiti relativi alle politiche giovanili. Tale iniziativa nasce dalla volontà di promuovere un dialogo costruttivo tra le istituzioni e i giovani del territorio, al fine di favorire una maggiore partecipazione attiva e consapevole alla vita politica e sociale della comunità.</p>
          <div class="it-card-footer">
            <span class="card-signature">di Area 3</span>
            <a class="btn btn-outline-primary btn-sm" href="/comune/instanze/R-d-I-992739/">Link Button</a>
          </div>
        </div>
      </div>
    </div>
    </div>
  </div>
</div>
</main>

