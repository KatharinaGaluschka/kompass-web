---
title: Kontakt
permalink: /kontakt/
---

Bitte verwenden Sie das Kontaktformular für Fragen zur Studie, oder wenn Sie teilnehmen möchten.

<form action="https://formspree.io/katharina.galuschka@med.uni-muenchen.de"
      method="POST">
  <input type="text" name="name" placeholder="Ihr Name">
  <input type="email" name="_replyto" placeholder="Ihre E-Mail-Adresse">
  <input type="tel" name="telefonnummer" placeholder="Ihre Telefonnummer">
  <input type="text" name="wohnort" placeholder="Ihre Wohnort">
  <textarea name="nachricht" placeholder="Bitte hier Nachricht eingeben…" required="" rows="12"></textarea>

  <input type="hidden" name="_subject" value="KOMPASS: Neuer E-Mail-Kontakt" />
  <input type="hidden" name="_language" value="de" />
  <input type="text" name="_gotcha" style="display:none" />
  <input type="submit" value="Absenden">

  <input type="hidden" name="_next" value="{{ '/kontakt/success' | absolute_url }}" />
</form>
