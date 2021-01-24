---
layout: contact_page
title: Kontakt
description: Kontaktformular easytheory
---

Hast du Anmerkungen, Fragen, Lob oder Kritik an der easytheory App? Oder hast du einen inhaltlichen Fehler bei den Theoriefragen gefunden? Nutze einfach das unten stehende Formular um uns zu erreichen.

 <form id="contactForm" method="POST" action="" enctype="multipart/form-data">
      <div class="row">
        <div class="col-25">
          <label for="name">Name:</label>
        </div>
        <div class="col-75">
          <input type="text" name="name" id="name">
        </div>
      </div>
      <div class="row">
        <div class="col-25">
          <label for="email">Email:</label>
        </div>
        <div class="col-75">
          <input type="email" name="email" class="phone-mail" id="email">
        </div>
      </div>
      <div class="row">
        <div class="col-25">
          <label for="phone">Telefon:</label>
        </div>
        <div class="col-75">
          <input type="tel" name="phone" class="phone-mail" id="phone">
        </div>
      </div>
      <div class="row">
        <div class="col-25"><label for="message">Nachricht:</label></div>
        <div class="col-75"><textarea rows="10" cols="80" name="message" id="message" required></textarea>
          <input type="hidden" name="shared_secret" value="70259406b8d46e07674e8b7317c56a4a803cac35" />
        </div>
      </div>
      <div class="row">
        <div class="col-25"><label for="attachment">Anhang:</label></div>
        <div class="col-75"><input type="file" id="attachment" name="attachment" accept="pdf,doc,docx,odt,image/*"
            multiple>
        </div>
      </div>
      <div class="row">
        <div class="col-25"><label for="attachment">Captcha:</label></div>
        <div class="col-75">
          <!-- This data-sitekey need to be change for production -->
          <div class="g-recaptcha" data-sitekey="6LeLCvwUAAAAALtUc5i8oXCB0fJVi4TezIW0jIh7"
            data-callback="onReCaptchaOK"></div>
          <input type="hidden" name="hiddenReCaptcha" id="hiddenReCaptcha">
        </div>
      </div>
      <div class="row">
        <input value="Nachricht senden" type="submit">
      </div>
    </form>
    