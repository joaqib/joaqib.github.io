---

layout: default
---

<div class="contact-cover">
    <div class="contact-cover__container w-container">
      <h3 class="contact-cover__title">Rellena el formulario para que nos pongamos en contacto contigo</h3>
      <div class="contact-cover__card w-form">
        <form class="contact-cover__form" data-name="Email Form" id="contactform" name="email-form" method="POST">
          <div class="contact-cover__form__row">
            <label class="contact-cover__label" for="name">Nombre:</label>
            <input class="w-input" data-name="Name" id="name" maxlength="256" name="name" placeholder="Barry Allen" required="required" type="text">
          </div>
          <div class="contact-cover__form__row">
            <label class="contact-cover__label" for="email">Email:</label>
            <input class="w-input" data-name="Email" id="email" maxlength="256" name="email" placeholder="theflash@justiceleague.com" required="required" type="email">
          </div>
          <div class="contact-cover__form__row">
            <label class="contact-cover__label" for="Web-2">Web:</label>
            <input class="w-input" data-name="Web" id="Web-2" maxlength="256" name="Web" placeholder="justiceleague.com" type="text">
          </div>
          <div class="contact-cover__form__row">
            <label class="contact-cover__label" for="services">Servicios:</label>
            <select class="w-select" data-name="services" id="services" name="services">
              <option value="">Select one...</option>
              <option value="desarrollo">Desarrollo Web</option>
              <option value="analitica">Analítica Digital</option>
              <option value="empezando">Estoy empezando</option>
            </select>
          </div>
          <div class="contact-cover__form__row">
            <label class="contact-cover__label" for="informacion">Información sobre tu negocio:</label>
            <textarea class="w-input" data-name="informacion" id="informacion" maxlength="5000" name="informacion" placeholder="Servicio express para salvar al mundo"></textarea>
          </div>
          <input type="text" name="_gotcha" style="display:none" />
          <input type="hidden" name="_next" value="//growthmile.com/nos-ponemos-a-trabajar.html" />
          <div class="contact-cover__cta-container">
            <input class="w-button" data-wait="Please wait..." type="submit" value="Submit">
          </div>
        </form>
        <script>
            var contactform =  document.getElementById('contactform');
            contactform.setAttribute('action', '//formspree.io/' + 'joaquin' + '@' + 'growthmile' + '.' + 'com');
        </script>
        <div class="w-form-done">
          <div>Thank you! Your submission has been received!</div>
        </div>
        <div class="w-form-fail">
          <div>Oops! Something went wrong while submitting the form</div>
        </div>
      </div>
    </div>
  </div>