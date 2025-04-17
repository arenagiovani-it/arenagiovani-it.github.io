---
layout: default
title: Crea il tuo account arena giovani
description: 
lang: it
ref: homepage
permalink: /form-9927/
order: 1
---
<div class="container">
<p>*NB: Ogni form è facoltativo </p>
    <form action="mailto:gabriel.jones@18f.it?subject=Modulo" method="POST" enctype="text/plain">
      <label for="nome">Nome:</label><br>
      <input type="text" name="nome" id="nome"><br><br>
      <label for="nome">Social:</label><br>
      <input type="text" name="Social" id="Social"><br><br>      
      <label for="bio">Breve presentazione (facoltativa):</label><br>
      <textarea name="bio" id="bio" rows="4" cols="40"></textarea><br><br>
      <label>Vuoi pubblicare una tua foto sul sito?</label><br>
      <input type="radio" id="foto-si" name="foto_ok" value="Sì">
      <label for="foto-si">Sì</label>
      <input type="radio" id="foto-no" name="foto_ok" value="No">
      <label for="foto-no">No</label><br><br>
      <label>Vuoi pubblicare la tua email di arena giovani? (iniziali@ufficio.arenagiovani.it)</label><br>
      <input type="radio" id="email-si" name="email_ok" value="Si">
      <label for="email-si">Si</label>
      <input type="radio" id="email-no" name="email_ok" value="No">
      <label for="email-no">No</label><br><br>
      <label for="consenso">Acconsenti alla pubblicazione delle informazioni fornite?</label><br>
      <input type="radio" id="consenso-si" name="consenso" value="Si" required>
      <label for="consenso-si">Si</label>
      <input type="radio" id="consenso-no" name="consenso" value="No">
      <label for="consenso-no">No</label><br><br>
      <p><i>Per la foto: inviala separatamente alla mail indicata o con contatti non ufficiali tipo whatsapp, instagram o quant'altro.</i></p>
      <input type="submit" value="Invia">
    </form>
</div>
