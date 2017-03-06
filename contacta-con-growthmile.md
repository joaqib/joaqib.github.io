---

layout: default
---

<div class="contact-cover">
    <div class="contact-cover__container w-container">
      <h3 class="contact-cover__title">Rellena el formulario para que nos pongamos en contacto contigo</h3>
      <div class="contact-cover__card w-form">
        <form class="contact-cover__form" data-name="Email Form" id="email-form" name="email-form" action="https://formspree.io/joaquin@growthmile.com" method="POST">
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
          <div class="contact-cover__cta-container">
            <input class="w-button" data-wait="Please wait..." type="submit" value="Submit" onclick="__gaTracker('send', 'event', 'form-submission', 'click', 'contact-page-cta');">
          </div>
        </form>
        <div class="w-form-done">
          <div>Thank you! Your submission has been received!</div>
        </div>
        <div class="w-form-fail">
          <div>Oops! Something went wrong while submitting the form</div>
        </div>
      </div>
    </div>
  </div>