---
layout: contact_page
title: Kontakt
description: Kontaktformular easytheory
---

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
          <label for="phone">Phone:</label>
        </div>
        <div class="col-75">
          <input type="tel" name="phone" class="phone-mail" id="phone">
        </div>
      </div>
      <div class="row">
        <div class="col-25"><label for="message">Message:</label></div>
        <div class="col-75"><textarea rows="10" cols="80" name="message" id="message" required></textarea>
          <input type="hidden" name="shared_secret" value="70259406b8d46e07674e8b7317c56a4a803cac35" />
        </div>
      </div>
      <div class="row">
        <div class="col-25"><label for="attachment">Attachment:</label></div>
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
        <input value="send message" type="submit">
      </div>
      </div>
    </form>
    <div class="thank-you hidden">
      <div>
        <img src="img/photo-1529590089538-86ace5ee4666.jpeg" alt="Thank you">
      </div>
      <div class="thank-you--message">
        <h2>We just wanted to say thanks</h2>
        <span>We will check and reply shortly</span>
      </div>
    </div>
    <div class="sending-error hidden">
      <div>
        <h2>Ops... we just couldn't receive your feedback</h2>
        <span>Please manually send us your feedback by using </span>
        <a class="email" href="#">your preferred mail client</a>
      </div>
    </div>
    <div class="spinner hidden">
      <div class="lds-dual-ring"></div>
    </div>
    <script src="{{ "/assets/js/contact.js" | absolute_url }}"></script>